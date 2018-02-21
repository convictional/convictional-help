---
title: "How Sync Works"
date: 2018-02-21
toc: true
---
## Introduction
Convictional allows you to setup exceptions to your price lists. This makes it easier to manage any non-standard pricing for a particular trading partner or group of trading partners. Instead of changing your base prices for the duration of an event, you can setup an additional price list called an exception list that will only sync with your partner when active.

## Setting Up Exceptions
An exceptions price list is the same as a regular price list. You can import it and set various parameters (conversion rate, markdowns, etc.) that will apply to the SKUs on it. There are a few key things to consider when setting it up though, including:
* Start date: when does this pricing start to apply?
* End date: when does this pricing stop applying?
* Code: the code has start with the code for the main price list, with a dash and a suffix

## List Code
Here is an example of how the price list code should work. Say you have a price list for all your trading partners or shops in Canada. The base prices for all those partners or shop in Canada would be set in a price list with the code "CANADA". The exceptions to this list would have a dash and a suffix to tell you what they mean. This could be "CANADA-SALE" or "CANADA-1".

## Importing Exceptions
Importing a price list of exceptions is the same as importing any other price list outside of the factors discussed above. Here is an [article](http://help.convictional.com/pricing-csv-uploads/) on how to import exceptions prices. 

## Use Cases
There are many use cases for a flexible approach to pricing like this one:
* Sale pricing
* Clearance pricing
* Time or date-specific prices
* Flash sales

## Benefits
The benefit to this approach is you do not have to change your base price list in order to set up exceptions. In some systems you would need to change the base price in order to update pricing for one-off events. This approach allows you to setup one-off pricing without changing your base prices, so you can revert back to base prices automatically when the exceptions end.