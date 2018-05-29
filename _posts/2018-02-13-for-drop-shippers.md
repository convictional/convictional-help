---
title: "Quickstart for Partners"
date: 2018-02-13
toc: true
author: Chris Grouchy
---
## Introduction
Welcome to Convictional. Consider this your very own dropshipping hub. Convictional takes all of the pain away from dropshipping by making data sharing and billing happen automatically.

Your wholesale supplier will automatically receive any orders containing their product(s). The wholesale supplier will then be able to drop ship the order to the end consumer on your behalf.

## Step 1: Receive Email Invite

Retailers (dropshippers) must receive an Invite Email from the wholesaler. Please contact your wholesaler if you have not received an Invite Email. It will look like the screenshot below in your email inbox:

![emailInvite](https://github.com/rogerkirkness/convictional-help/blob/master/assets/images/emailInvite.png?raw=true)

The email will contain the following message:

![emailInvite](https://github.com/rogerkirkness/convictional-help/blob/master/assets/images/emailInviteBody.png?raw=true)

When you click the link, you’ll be taken to a page where you will create your account.

## Step 2: Create Your Account

The link from the email will take you to a signup page where you can create your own account:

![emailInvite](https://github.com/rogerkirkness/convictional-help/blob/master/assets/images/signUp.png?raw=true)

You’ll be able to select the ecommerce platform that currently use by clicking on the dropdown menu under "Platform".

![emailInvite](https://github.com/rogerkirkness/convictional-help/blob/master/assets/images/selectPlatform.png?raw=true)

Select the platform that your store is on (Shopify, BigCommerce, or WooCommerce), and create your account by entering your own email and a unique password. Also, enter in your Shop URL. This is important, as the Shop URL is specific to your store and what we use for integration:

Note: if you are on Shopify, please copy/paste your admin URL and not your store URL.

After your click Sign up, you will have to enter in your credit card information. This will create an account for your wholesaler to bill you in the future for orders that contain their products.

## Step 3: Connect Your Store in Settings

### For Shopify

If you’re using Shopify, ensure that you have selected Shopify in the Platform dropdown. Then click Connect Shopify. From there, you will go through the standard app install process for a Shopify app. Depending on the wholesaler you are working with, the app may be unlisted, but that is okay and you will still control persmissions and have a secure connection to us.

### For WooCommerce

If you’re using WooCommerce, you will need to provide the WooCommerce Consumer Key and the Secret Key. These can be easily found (or generated) in your WooCommerce admin under Settings > API. Here is the [WooCommerce documentation explaining how this works](https://github.com/woocommerce/woocommerce/wiki/Getting-started-with-the-REST-API#generate-keys).

If you would like to get tracking information to share with your customers into your WooCommerce shop you will need to purchase and install the [WooCommerce Shipment Tracking plugin](https://docs.woocommerce.com/document/shipment-tracking/).

### For BigCommerce

If you’re using BigCommerce, ensure that you have selected BigCommerce in the Platform dropdown and provided the URL for your store to us. You will need to provide the Client ID, Client Secret and Access Token for an API account so that we can connect with your store and trade with you. To get that information, here is an official document explaining how this works: [help document](https://developer.bigcommerce.com/api/#obtaining-oauth-tokens)

Convictional needs permissions from you when you create your API Account. Login to your BigCommerce store, go to Advanced Settings > API Accounts. Create a new API Account and provide the following permissions:
![bigcommerce-permissions](https://github.com/rogerkirkness/convictional-help/blob/master/assets/images/bigcommerce-permissions.png?raw=true)

## Step 4: Go Back to Your Ecommerce Platform, Publish Your "Products"

Once you’ve successfully connected your store, your wholesaler’s products will appear in your ecommerce store admin in the product section. Don’t worry, they will not be published yet.

Two quick things to note at this stage:

1. Products will be remain **unpublished** and will not be visible to consumers until you mark them as visible in your ecommerce store admin. You have full control over their visibility. They are not shoppable until you publish them. 

2. It may take up to an hour for products to appear in your admin. So don’t worry if they don’t appear immediately. If you don’t see the products in your ecommerce store admin, contact your wholesaler and they can "run a sync" to your store at anytime.

3. If you would like to merchandise the products yourself (change descriptions, update SEO, switch out photos, or anything else) and would rather your partner not overwrite your work, just ask your wholesaler. They can either continue to feed updates to existing products, or just sync them once.

## Step 5: Accept Orders

Once you have published your products to your store, you are now ready to accept orders! When you receive a sale containing your wholesaler’s product(s), the order, product details, and customer details will be sent to your wholesaler. They can then fulfill the order. It’s that simple. 

#### 1. You will receive inventory and order updates once an hour.

#### 2. Your wholesaler will receive any orders containing their products once an hour.

#### 3. You will receive an up-to-date catalog automatically twice a day.

#### 4. You will be billed once a day to the card on file for your orders that day

## Step 6: Pay Your Wholesaler

When you receive an sale containing your wholesaler’s product(s), you will need to pay your wholesaler the specified wholesale price. 

The price you charge on your store will be set by the wholesaler (which is the wholesale price + a markup). Your take is the difference.

You have two options for paying your wholesaler. Typically the wholesaler will support one or both but you have to pay with the method they prefer:

### Pay with Stripe:

Your wholesaler can charge you through Stripe (you will automatically set up a Stripe account when signing up for Convictional). You can ensure that you are connected to Stripe in Settings. Your wholesaler will bill you when you receive an order. We will notify them when an order has been placed so they can collect payment. 

### Pay through Apruve

Apruve is a B2B payment gateway. With Apruve, your wholesaler can automatically send you one invoice at the end of each day that an order containing their product(s) has been placed. Then you can pay for all orders that day through a single invoice. 

With Apruve, your wholesaler will get paid for the order when it has been shipped (Apruve will finance the order), and you pay when you receive an invoice. Please email [roger@convictional.com](mailto:roger@convictional.com) to set up an account with Apruve. Learn more: apruve.com

Once you set up an account, you can enter in your Apruve Merchant ID and Apruve API Key. 

Note that in order to use Convictional as a retailer, you must either have a credit card in the system (via Stripe) or an account set up with Apruve. 
