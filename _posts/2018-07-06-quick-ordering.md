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

The format for quick orders contains two major sections: addresses and items.

* Type "*ITEMS" to start item section. Type "/ITEMS" to end the items section.
* Type "*ADDRESS" to enter address. Type "/ADDRESS" to end the address section.

To enter a SKU, enter the SKU, an equals sign and the quantity you want.

```
SKU123=7
SKU432=2
SKU567=4
```

Here is a full list of possible attributes for the address section:

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

As long as their email follows this order, it will make it through.

The subject line has to be your Convictional companyId.

## Example

Here is an example of what it looks like when it's put together.

Subject: convictional-wholesale
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

## Support

We support quick ordering like any other product. If you have any questions or want to setup blind quick ordering (ie. an email at your domain) and want some help, get in touch.