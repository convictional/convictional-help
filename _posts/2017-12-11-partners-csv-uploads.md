---
title: "Importing Partners"
date: 2018-01-31
toc: true
author: Roger Kirkness
---
To import partners via CSV, please use the following format:

email, price list, relationship, active, invited, force, billing

partner@domain.com,My Price List,child, true, true, true, true

## Elements

* Email: The business email for this partner
* Price list: The name of their price list
* Relationship: Relative to you: 'parent', 'child' or 'self'
* Active: Do you want to sync with them?
* Invited: Have they been invited?
* Force: Overwrite products? Excludes prices/inventory.
* Billing: Do you want to bill them here?

## Requirements

* Do not include headers in your CSV file.
* If the upload fails, double check the format.
* Leave empty spaces for optional fields (ie. ",,,")
