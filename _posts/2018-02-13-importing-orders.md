---
title: "Importing Orders"
date: 2018-02-13
toc: true
---
## Introduction
To import orders via CSV, please use the following format:
code,partner,date,sku,quantity,name,company,
city,zip,state,country,addressOne,addressTwo

## Elements
* Code (required): the order number in source system
* Partner: the company this order is from
* Date: the date of the order in ISO8601 format
* Item SKU: the SKU of an order item
* Item Quantity: the quantity of that order item
* Ship Name: the full name of the customer
* Ship Company (Optional): the customer's business
* Ship City: the city to ship to
* Ship Zip: the zip or postal code to ship to
* Ship State: the state or province to ship to
* Ship Country: the country to ship to
* Ship Address One: the first address line
* SHip Address Two (Optional): the second address line

## Requirements
* Do not include headers in your CSV file.
* If the upload fails, double check the format.
* Leave empty spaces for optional fields (ie. ",,,")