---
title: "Quick Ordering"
date: 2018-07-06
toc: true
author: Roger Kirkness
---
## Introduction

Convictional offers an easy way for your partners to order from you via email. The format has to be just right in order for the Convictional Bot to understand what your partner wants on their order. This article covers how it works.

## Setup

You can have your customers order using our email: orders@in.convictional.com or you can forward an email at your domain to that email (ie. forward orders@domain.com -> orders@in.convictional.com).

> You can even use your existing orders email. Any emails from someone not connected to your account will be ignored by this service.

## Format

The subject line of the email has to be your companyId. To confirm what your companyId is, visit [your settings page](https://app.convictional.com/settings).

The format for the body of a quick order contains two major sections: addresses and items. 

To start a section, type "*" then the name in block caps. To end it, type a forward slash ("/") and then the name in block caps.

```
*ITEMS
/ITEMS
*ADDRESS
/ADDRESS
```

To enter a SKU, enter the SKU, an equals sign and the quantity you want:

```
*ITEMS
SKU123=7
SKU432=2
SKU567=4
/ITEMS
```

To enter an address, enter the attribute, an equals sign and a value:

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

## Support & Feedback

We support quick ordering. If you have any questions or want to setup blind quick ordering (ie. an email at your domain) and want some help, get in touch.