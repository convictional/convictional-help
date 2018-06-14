---
title: "Pricing Guide"
date: 2018-01-31
toc: true
author: Roger Kirkness
---
## Importing CSV
To import pricing via CSV, please use the following format:

List Name, Start Date, End Date, Currency, Conversion Rate, List Markup, Rounding, Sku, SKU Cost, SKU Markup, Markup Type

ie. 1Price List,2018-01-23,2018-03-15,USD,1.2,120,99,54321,9.99,5,fixed

## Elements

* Price List Name: A descriptive name for the price list ('price list')
* Start date: the first date this pricing should apply ('2018-01-15)
* End date: last date this pricing should apply on ('2018-03-15')
* Currency: currency of the shop(s) you want to sync with. ('CAD')
* Conversion Rate: conversion rate to apply ('1.2' = prices x 1.2)
* List Markup: percentage markup ('200' = prices x 2)
* Rounding: last two digits you want prices rounded up to ('99' = $1.99)
* Sku: A variant-specific SKU ('ABC-123')
* Base Price: base price for that SKU ('9.99')
* Markup (Amount): in percent (ie. '120') or dollars ('5')
* Markup Type: 'fixed' for dollar markup or 'percent' for percentage

## Requirements

* Do not include headers in your CSV file.
* If the upload fails, double check the format.
* Leave empty spaces for optional fields (ie. ",,,")

## Example

Here is [a link to an example file](https://docs.google.com/spreadsheets/d/1adlpyOlVsCVIxEsWbHAsWaSQ6V8aTkTXV0XvSa-yq2Y/edit?usp=sharing). Remember not to include headers.

## Exceptions Pricing

Convictional allows you to setup exceptions to your price lists. This makes it easier to manage any non-standard pricing for a particular trading partner or group of trading partners. Instead of changing your base prices for the duration of an event, you can setup an additional price list called an exception list that will only sync with your partner when active.

### Setting Up Exceptions

An exceptions price list is the same as a regular price list. You can import it and set various parameters (conversion rate, markdowns, etc.) that will apply to the SKUs on it. There are a few key things to consider when setting it up though, including:

* Start date: when does this pricing start to apply?
* End date: when does this pricing stop applying?
* Code: the code has start with the code for the main price list, with a dash and a suffix

### List Code

Say you have a price list for all your trading partners or shops in Canada. The base prices for all those partners or shop in Canada would be set in a price list with the name "CANADA". The exceptions to this list would have a dash and an "E" as a suffix (ie. "-E"). So the list name would be: "CANADA-E".

### Importing Exceptions

Importing a price list of exceptions is the same as importing any other price list outside of the factors discussed above. Here is an [article](http://help.convictional.com/pricing-csv-uploads/) on how to import exceptions prices. 

### Use Cases

There are many use cases for a flexible approach to pricing like this one:
* Sale pricing
* Clearance pricing
* Time or date-specific prices
* Flash sales

### Benefits

The benefit to this approach is you do not have to change your base price list in order to set up exceptions. In some systems you would need to change the base price in order to update pricing for one-off events. This approach allows you to setup one-off pricing without changing your base prices, so you can revert back to base prices automatically when the exceptions end.
