# Cart Product Details

## Introduction

> This extension allows you to add short description attribute to items in cart from your custom themes  `Magento_Checkout/templates/cart/item/default.phtml`


## Installation

>    Place App folder under Magento root directory

>    Now you are able to  get short descrtion in for template file with 
`<?php echo $_item->getProduct()->getData('short_description');?>`
