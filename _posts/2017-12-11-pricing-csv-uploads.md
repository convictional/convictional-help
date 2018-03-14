---
title: "Importing Prices"
date: 2018-01-31
toc: true
---
## Introduction
To import pricing via CSV, please use the following format:

Price List Code, Price List Name, Start Date, End Date, Currency Description, Conversion Rate, List Markup, Rounding, Sku, Base Price, Markup, Markup Type

ie. 12345,Price List,2018-01-23,2018-03-15,USD,1.2,120,99,54321,9.99,5,fixed

## Elements
* Price List Code (required): A unique code for the price list. ('12345')
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
