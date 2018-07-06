---
title: "Quick Ordering"
date: 2018-07-06
toc: true
author: Roger Kirkness
---
## Introduction

Convictional offers an easy way for your partners to order from you via email. The format has to be just right in order for the Convictional Bot to understand what your partner wants on their order.

## Setup

There are a few ways to approach setting up quick ordering. You can have your customers order using our email: orders@in.convictional.com or you can forward an email at your domain to that email (ie. forward orders@domain.com -> orders@in.convictional.com).

## Format

The format for quick orders contains two major sections: addresses and items. To start a section, type "*" then the name in block caps. To end it, type a forward slash ("/") and then the name in block caps.

```
*ITEMS
/ITEMS
*ADDRESS
/ADDRESS
```

To enter a SKU, enter the SKU, an equals sign and the quantity you want like this:

```
*ITEMS
SKU123=7
SKU432=2
SKU567=4
/ITEMS
```

Here is a full list of optional attributes for the address section (spaces allowed):

```
*ADDRESS
name=(the name or company)
company=(the company name)
phone=(phone number)
email=(the contact email)
type=(billing or shipping)
city=(the address)
zip=(the zip or postal code)
state=(the province, state or territory name)
country=(the country)
address=(first address line)
extra=(second address line)
/ADDRESS
```

The subject line has to be your Convictional companyId.

## Example

**To**: orders@in.convictional.com
**Subject**: convictional-wholesale
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

We support quick ordering. If you have any questions or want to setup blind quick ordering (ie. an email at your domain) and want some help, get in touch.