---
layout: page
title: Systems
permalink: /system-administration/systems/
parent: System Administration
---

# Systems

## ERP (Enterprise Resource Planning)

The ERP system dashboard gives you access to different pages in the system depending on your user role. The following are some of the key areas

**Products**

The products section allows you to add and manage all the products. You can modify the products name, sku, stock, price, categories, tags, description, images, etc.

**Commerce**

The commerce section gives you access to orders place, customers, coupon management, and other sales reports.

**Users**

Users section is used to add and manage users, their information, and their roles.

**Website**

The pages, media, appearance, and settings sections allow you to modify and configure the websites. 



## Inventory Management

### Bill of Material (BOM)

​	SKU convention 

​		school-product-color-size

### Stock

The **out of stock threshold** can be set so that a replacement order is placed before we actually run out. If you know that you sell a lot of one product, you can set the threshold higher.

## Ecommerce

### Sites

Main - [donaldsuniform.store](http://donaldsuniform.store)

​	Contains the master catalog for all the stores

Schools - e.g. [cretinderhamhillhs.donaldsuniform.store](http://cretinderhamhillhs.donaldsuniform.store) 

​	Contains only the catalog items for that school

### Sku convention

General

​	school-product-color-size

- School id is 0000 in the sku if it applies to multiple schools

### Categories

Categories are used to denote which schools, age groups, genders and product categories a product is in. 

**Gender and Age Groups**

Products are either assigned to the *Girls*, *Boys*, or *Girls* and *Boys* categories. Each gender category has a sub categories for each grade that its products pertain to. For example, if a product is associated with Girls 9-12, then it would be in the following categories:

- Girls

- Girls -> Grade 9

- Girls -> Grade 10

- Girls -> Grade 11

- Girls -> Grade 12

### Payment Processing

For collecting payments from users via credit or debit card, we use [Stripe](http://stripe.com/). It is a payment gateway and merchant account.

Charges for Stripe will vary depending on usage. Successful credit card charges are 2.9% + 30 cents. There are no setup fees, monthly fees, or card storage fees.

## Point of Sale

### Registers

These are the kiosks at each outlet location

### Kiosks

We are using the SeePoint™ Interactive Kiosk System

- Allow users to sign into a register

- Register lists out all schools

- Each school contains all it's available products and variations

- Allows user to add products to cart for a customer

- Connected to 

  - Barcode scanner

  - Stripe credit card reader

  - Epson printer to print receipt 

​	

## Order Fulfillment

Epluno stores, fulfills, and ships each order at its warehouse. By doing so, we do not have to rely on 3rd parties to fulfill orders. 

### Back Orders

Products that are not available in the store can be put on back order. They will be listed as a separate order in the system.

Currently Donalds has multiple ways of handling a back ordered item:

1. Exclusive school item they will typically ship at no cost. 

2. Optional items may be setup for store pickup or charged a shipping cost. 

## Decoration

We can add custom decoration to apparel at our warehouse. Theses might include things like school logos on their uniform.