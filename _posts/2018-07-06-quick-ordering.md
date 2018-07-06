---
title: "Quick Ordering"
date: 2018-07-06
toc: true
author: Roger Kirkness
---

## Introduction

Convictional offers an easy way for your partners to order from you via email. The format has to be just right in order for the Convictional Bot to understand what your partner wants.

## Setup

There are a few ways to approach setting up quick ordering. You can have your customers order using our email: orders@in.convictional.com. Alternatively you can forward an email at your domain (ie. quickorder@domain.com). Once we get an order in the right format, we'll load it into your system.

## Format

The format for quick orders contains two major sections: addresses and items. The goal is to easily get orders into your system, not necessarily give you all the functionality you are used to when it comes to ordering. Think speed, where you can clarify (or don't need) details later.

* Type "*ITEMS" to start entering items in the email. Type "/ITEMS" to end the items section.
* Type "*ADDRESS" to start entering the address. Type "/ADDRESS" to end the address section.

Each item and address attribute are a key/value pair separated by an equals sign. You have to use the supplier's SKU and then equals the quantity. For example: SKU123=3 would order 3 units of SKU123.

Each address attribute has a name, to keep it simple. Here's the full list of options:

* name: the name of the company or person ordering
* company: if you want, a company name for the address
* phone: the phone number of the destination location
* email: the email for the order, if different
* type: the address type (shipping vs. billing, lowercase)
* city: the city
* zip: the zip or postal code
* postal: the postal code, if you insist
* state: the state, province or territory
* country: the country
* address: the first address line
* extra: the second address line

As long as their email follows this order, it will make it through into your system. Ultimately we can then sync this order with your system of record like any of your other B2B orders.

The subject line has to be your Convictional companyId. If you company ID was convictional-wholesale, the subject line needs to be: convictional-wholesale. This is how we route the order into your system.

## Example

Here is an example of what it looks like when it's put together.

Subject: convictional-wholesale
Body:
```
*ITEMS
SKU=3
ANOTHERSKU=2
THIRDSKU=1
/ITEMS

*ADDRESS
name=Customer Name
company=Convictional, Inc.
phone: 4165550000
email: email@domain.com
type: shipping
city: Toronto
zip: M5V 4B3
state: Ontario
country: Canada
address: 123 St.
extra: #101
/ADDRESS
```
