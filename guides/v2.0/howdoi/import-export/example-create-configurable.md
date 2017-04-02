## Example of importing a configurable product

First step is to create a configurable product:

| sku | attribute_set_code | product_type | product_websites | name | price |
|----------------|----------------|----------------|----------------|----------------|----------------|
| Configurable-example | Bottom | configurable | base | Configurable Example Product Name | 99.0000 |

[Example create configurable ](examples/create-configurable.csv)

Second step is to associate the simple products to the configurable. In this example we use the available Magento 2 sample data to associate to our configurable product.

| sku | attribute_set_code | product_type | configurable_variations | configurable_variation_labels |
|----------------|----------------|----------------|----------------|----------------|----------------|
| Configurable-example | Bottom | configurable | "sku=WSH12-28-Green,color=Green,size=28&#124;sku=WSH12-28-Purple,color=Purple,size=28&#124;sku=WSH12-28-Red,color=Red,size=28" | "color=Color,size=Size" |

[Example associate simples](examples/configurable-associate-simples.csv)

It's also possible to combine both steps in one file:

| sku | attribute_set_code | product_type | product_websites | name | price | configurable_variations | configurable_variation_labels |
|----------------|----------------|----------------|----------------|----------------|----------------|
| Configurable-example | Bottom | configurable | base | Configurable Example Product Name | 99.0000 | "sku=WSH12-28-Green,color=Green,size=28&#124;sku=WSH12-28-Purple,color=Purple,size=28&#124;sku=WSH12-28-Red,color=Red,size=28" | "color=Color,size=Size" |

[Example create configurable and associate simples](examples/create-configurable-associate-simples.csv)