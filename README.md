<!-- START_METADATA
---
title: Vipps for Wix plugin
sidebar_position: 1
description: Provide Vipps payments for Wix.
pagination_next: null
pagination_prev: null
---
END_METADATA -->

# Vipps Payment for Wix

![Support and development by Crude ](./docs/images/crude.svg#gh-light-mode-only)![Support and development by Crude](./docs/images/crude_dark.svg#gh-dark-mode-only)

![Vipps](./docs/images/vipps.png) *Available for Vipps.*

![MobilePay](./docs/images/mp.png) *Coming soon for use of Checkout for MobilePay in Finland and Denmark.*

*This plugin is built and maintained by [Crude](https://crude.no/).
For support, contact the [support forum on WordPress.org](https://wordpress.org/support/plugin/woo-vipps).*

<!-- START_COMMENT -->
💥 Please use the plugin pages on [https://developer.vippsmobilepay.com](https://developer.vippsmobilepay.com/docs/plugins-ext/wix/). 💥
<!-- END_COMMENT -->

This is the official *Vipps Payment for Wix*. More than 4 million Norwegians use Vipps. Give them a fast and familiar shopping experience in Wix, too!

This plugin provides a direct integration with Wix. Now, you can let your customers choose Vipps directly in the checkout.

You can also do important back office tasks such as capture and refund directly from Wix. Easy for your customer, and easy for you.

## Vipps Payment

When you enable this plugin, your customers will be able to choose Vipps as a payment method directly in the checkout. There is no need to go via a third party payment method. If your customer choose Vipps, the customer fills in their contact information and is then asked to enter their phone number in the Vipps dialogue. Then, the customer confirms the payment in the Vipps app. The order is completed and are stored in your Wix store.

## Vipps Express Checkout

Vipps does not yet have a solution for express checkout in Wix.

## Vipps Recurring Payments

Vipps does not have a solution for recurring payments in Wix.

## How to get started

- Sign up to use [*Payment Integration*](https://vippsmobilepay.com/online/payment-integration).
- After 1-2 days, you will get an email with login details to the Merchant Portal, [portal.vippsmobilepay.com](https://portal.vippsmobilepay.com/), where you can get the API credentials.
- Download and configure.

For more details, see [Applying for services](https://developer.vippsmobilepay.com/docs/knowledge-base/applying-for-services/).

## How to get account keys

1. Sign in to the [portal.vippsmobilepay.com](https://portal.vippsmobilepay.com/).
2. In the *Developer* section, choose *Production Keys*. Here, you can find the merchant serial number (6 figures).
3. Click on *Show keys* under the *API keys* column to see *Client ID*, *Client Secret*, and *Vipps Subscription Key*.

See:

- [Logging in to the portal](https://developer.vippsmobilepay.com/docs/knowledge-base/portal)
- [How to find the API keys](https://developer.vippsmobilepay.com/docs/knowledge-base/portal#how-to-find-the-api-keys).

## Installation

Install *Vipps for Wix* by following the instructions at [Crude: Vipps for Wix](https://crude.no/vipps-for-wix/), or read more below.

### Log in to your Wix Admin

1. Go to *Settings* > *Accept payments*

   ![image](https://user-images.githubusercontent.com/61109180/132360200-30587852-ebab-443b-94d1-ac01606301c0.png)

1. Choose *See more payment options*

   ![image](https://user-images.githubusercontent.com/61109180/132362154-4246aaed-995e-41f9-8ba0-2bb142f66794.png)

1. Click *connect* button on Vipps

   ![image](https://user-images.githubusercontent.com/61109180/132362264-f25a9a7d-b4ba-4339-862f-4c260743bc69.png)

1. Enter API keys and click *connect* button

   ![image](https://user-images.githubusercontent.com/61109180/132362356-7900361e-ca7f-4092-9a9e-784e8afe7fcb.png)

## Important notes

It is not possible to capture an order from within Wix Admin. You will need to use the Vipps MobilePay [Merchant Portal](https://portal.vippsmobilepay.com) to do the captures on each order. This is very important, because, if you forget to capture the orders, you won’t get the payment.

This is due to limitations in Wix and lack of support for making the necessary API calls to Vipps. We are simply not able to automate this or make it possible to do captures directly in Wix.

Norwegian law is strict: Is it not legal to do the capture before the goods are sent or provided to the customer. This is different in other countries, and because of this there is limited support for the Norwegian reserve and capture requirements.

We are aware that this is not the most optimal solution for merchants, but this is a restriction which we can’t go around for now. We will of course optimize this as soon as it is possible.

Learn more about [the difference between reserve and capture](https://developer.vippsmobilepay.com/docs/knowledge-base/reserve-and-capture/#what-is-the-difference-between-reserve-capture-and-direct-capture).

## How to manage the Vipps orders in Wix Admin

See [Order management in Wix](order-management.md).

## How can I get help if I have any issues?

For issues with your Vipps for Wix installation, contact us via our [support system](https://crude.no/vipps-wix-support/). For other issues, contact [Vipps](https://developer.vippsmobilepay.com/docs/contact/#contact-details).

## FAQ

See the [Knowledge base](https://developer.vippsmobilepay.com/docs/knowledge-base/) for more help with Vipps eCommerce.

## Support

For issues with this plugin,
contact the [support forum on WordPress.org](https://wordpress.org/support/plugin/woo-vipps).

