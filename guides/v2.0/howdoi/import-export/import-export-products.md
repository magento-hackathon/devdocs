---
layout: default
group: howdoi
subgroup: BB
title: Import export products
menu_title: Import export products
menu_node: parent
menu_order: 1

github_link: howdoi/import-export/import-export-products.md
---


# How do I Import and Export Products in Magento 2 (with Examples)
This guide will explain based on examples how you can faciliate the import export feature of Magento 2. It highlights what is working out of the box and also what is not working as you wuld might expect it.
Presentation as source https://de.slideshare.net/bennolippert/magento-2-product-import-export
## Creating a valid import file
  In ordner to create a valid import file you have to stick to this preferences:
  File Formatting
    CSV
    UTF-8
    |
    Does filename matter???

  Field delimiter out of the box is , complex field entries are delimited with | .
## Fixed Format  
  There is a maximum of 86 fields which can be used in an import file. A complete list of the files can be found [here](http://docs.magento.com/m2/ce/user_guide/system/data-attributes-product.html)

  You should pay special attention to complex fields, we will introduce this complex format first in the Example of importing a configurable product.
  
## Product Import Examples for Magento 2
  {%include example-create-virtual.md%}
  Example of importing a virtual product

  Example of importing a simple product
  Example of importing custom attributes
  Example of importing a configurable product
  Example of importing a grouped product
  Example of importing bundled products
  Example of importing custom options
  Example of importing product images
  Example of importing additional images
  Example of importing custom image attributes
  Example of importing cross-sells, up-sells, and related products
  Example of how to import tiered pricing
Potential issues and common problems
  Issues importing a previous export
  How a simple product can change its type unexpectedly
  Potential problems importing configurable products
    What happens if the simple products don’t exist?
    You can’t use import/export to remove associated simple products
    How a configurable product can change its type unexpectedly
  Potential problems with image importing
    You can’t import videos
    Changing base images
  You can’t import a downloadable product in Magento 2
  You can’t create new attribute options
  Empty attribute values
  Only update one of multiple store views
  Removing website association
  Product reviews
  Super-attribute label feature is gone
  Group pricing
