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
How do I Import and Export Products in Magento 2 (with Examples)
Presentation as source https://de.slideshare.net/bennolippert/magento-2-product-import-export
Creating a valid import file
  File Formatting
    CSV
    UTF-8
    |
    Does filename matter???
  Fields
    Link to user doc field reference:  http://docs.magento.com/m2/ce/user_guide/system/data-attributes-product.html
  Special attention to complex fields
  Key differences between M1 and M2
  Minimum required fields to import a virtual or simple product
Product Import Examples for Magento 2
  {%include import-export-products.md%}
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
