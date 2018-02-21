---
title: "How Sync Works"
date: 2018-02-16
toc: true
---
## Introduction
Convictional automates a lot of things that you and your customers might be used to doing manually. It can be helpful to understand exactly what Convictional is doing with your information in order to make it easier for you to trade online. This is an overview of how the syncing relationships that we maintain work and what you can expect from us.

![syncing](https://github.com/rogerkirkness/convictional-help/blob/master/assets/images/syncing.png?raw=true)

## Manual Syncing
In you want, you can manually trigger the syncing process to run anytime you make a change. Go to Settings and select which job you want to run. You will see a description of what will happen (ie. sync all my products to child shops) and a button to click in order to run it. Depending on API limitations and amount of records involved, it can take some time for information to propagate. Check back in a few minutes to see how things are progressing.

### Orders

**Retailer > Convictional > Wholesaler**

Orders sync to us from your partners within an hour. Depending on the platform we might be able to get at them in real time and use that information to update inventory (Shopify) or not. Orders arrive with all the information you need to manage and fulfill them.

Once we get orders into Convictional, we can sync them into your system of record. This process end to end takes at most two hours for the various syncing jobs to work through. By this point you will have the order in your system of record for fulfillment without any effort.

### Order Updates

**Wholesaler > Convictional > Retailer**

Order updates (ie. fulfillments) sync from your system of record to our system once an hour. This allows us to constantly stay current on what has been shipped. This information is important as we are syncing with other trading partners.

We sync order updates with your trading partners once an hour. So they should have a good sense of what is happening with their orders, and have the tracking information and other data they need in order to be able to maintain their customer relationships without your involvement.

### Products

**Wholesaler > Convictional > Retailer**

Product catalogs sync from your system of record to our system every eight hours (3x/day). This ensures we have current information about what products you want to be listed without overdoing API calls to your system of record. Generally catalogs don't change that often, and you can manually trigger a sync when they do, so eight hours is more than enough to sync what we need.

Products are then synced with your trading partners once every eight hours. All new products will be added in an "unpublished" state to avoid them from showing up on the front-end of your customers store without their express permission. Products are updated with all the current information including current pricing, inventory, SKUs, titles, descriptions and more.

### Product Updates

**Wholesaler > Convictional > Retailer**

Product updates (ie. inventory changes) sync from your system of record to our system once an hour. This ensures that we can constantly stay on top of what is happening inventory wise with your products. We only get inventory information (as opposed to the whole catalog) to make sure things stay fast even if your customers are self-hosting their ecommerce platform.

Product updates are synced with your trading partners once an hour to make sure they have current information. Depending on the platform we may be able to do a full inventory sync once an hour by listening for a service and responding with inventory counts. Other platforms allow bulk updating but don't explicitly call for inventory updates. You can rest assured that inventory is syncing with your partners on a regular basis without dealing with each platform.

### Billing
We automate the billing process once a day. That means regardless of which gateway (ie. Apruve, Stripe) you choose for your billing of customers, we will invoice them or charge their card once a day. There is no way to manually trigger this, to avoid double/overcharging.

## Conclusion
Convictional makes it easy to manage trading relationships and share information but we feel strongly that our customers should be empowered to understand and manage the syncing process.