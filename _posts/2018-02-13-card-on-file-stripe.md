---
title: "Setup card-on-file payments"
date: 2018-02-13
toc: true
author: Roger Kirkness
---
## Introduction

Convictional allows a wholesaler to accept payments a few different ways. If you want your customers to be able to pay on terms, you will need Apruve. If you just want to bill a credit card on file, which tends to have higher fees, you can do that too with Stripe.

### Step One

Connecting Stripe is easy. When you join Convictional as a wholesaler, we will generate an optional Stripe account for you to use. You will get an email from Stripe shortly after signing up with a link to create an account. If you already have one, you can use that instead.

![stripeConnect](https://github.com/rogerkirkness/convictional-help/blob/master/assets/images/stripeConnect.png?raw=true)

### Step Two

Once you have a Stripe account setup, you will be able to control all aspects of the billing relationship with your customer, while we can access your account in order to automate billing for orders. This means you can offer a subscription program, issue refunds and more.

### How Customers Onboard

When your retail customers go to create Convictional accounts in order to sync up with you, they will be asked to add a credit card. We will store that card under **your** Stripe account, giving you more control over the relationsihp and making it easy for us to bill them.

![stripeConnect](https://github.com/rogerkirkness/convictional-help/blob/master/assets/images/stripeAddCard.png?raw=true)

### How Customers Pay

Now that we have billing information for your customer, we can bill them for any orders that contain your products. Billing will be based on the pricing you have setup and assigned that custmomer. Once a day we will go through and bill for all the orders that shipped that day.The charge will go against the customers card on file and you (and the customer) will be notified.

## Conclusion

Card on file can be an easy way to bill your customers. Because Apruve costs the same or less and allows your customers to pay a once monthly invoice with all of their orders (while you get paid on shipment), we recommend it over card on file, but you can use what works best for you.