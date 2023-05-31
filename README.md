# Vipps for Wix

The Vipps product page is [Vipps Wix plugins](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/Wix/).
To contact Vipps, see the [contact us](https://developer.vippsmobilepay.com/docs/vipps-developers/contact/) page.

<!-- START_COMMENT -->

💥 Please use the documentation pages here: <https://developer.vippsmobilepay.com/docs/vipps-plugins/wix/>. 💥

<!-- END_COMMENT -->


## Description

Official Vipps Payment for Wix. More than 4 million Norwegians use Vipps. Give them a fast and familiar shopping experience in Wix too!

This is the official Vipps plugin that provides a direct integration with Wix. Now you can let your customers choose Vipps directly in the checkout.

You can also do important back office tasks such as capture and refund directly from Wix. Easy for your customer and easy for you.

Read [information from Vipps](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/Wix/) about the plugin.

## Vipps Payment

When you enable this plugin, your customers will be able to choose Vipps as a payment method directly in the checkout. There is no need to go via a third party payment method. If your customer choose Vipps, the customer fills in their contact information and is then asked to enter their phone number in the Vipps dialogue. Then the customer confirms the payment in the Vipps app. The order is now completed and are now stored in your Wix store.

## Vipps Express Checkout

Vipps does not yet have a solution for express checkout in Wix

## Vipps Recurring Payments

Vipps does not have a solution for recurring payments in Wix

## How to get started

- Log into [portal.vipps.no](https://portal.vipps.no/login) with BankID.
- Sign up to use *Vipps på Nett*
- After 1-2 days you will get an email with login details to Vipps Developer Portal, where you can get the API credentials
- Download and configure

## How to get Vipps account keys from Vipps Developer Portal

1. Sign in to the [Vipps Portal](https://portal.vipps.no/) using BankID.
2. Select the *Utvikler* ("Developer") tab and choose *Production Keys*. Here, you can find the merchant serial number (6 figures).
3. Click on *Show keys* under the API keys column to see *Client ID*, *Client Secret* and *Vipps Subscription Key*.

See: [API Keys](https://developer.vippsmobilepay.com/docs/vipps-developers/common-topics/api-keys) for more details.

## Installation

Install Vipps for Wix by following the instructions at [Crude: Vipps for Wix](https://crude.no/vipps-for-wix/), or read more below.

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

It is not possible to capture an order from within Wix Admin. You will need to use the [Vipps Portal](https://portal.vipps.no) to do the captures on each order. This is very important, because, if you forget to capture the orders, you won’t get the payment.

This is due to limitations in Wix and lack of support for making the necessary API calls to Vipps. We are simply not able to automate this or make it possible to do captures directly in Wix.

Norwegian law is strict: Is it not legal to do the capture before the goods are sent or provided to the customer. This is different in other countries, and because of this there is limited support for the Norwegian reserve and capture requirements.

We are aware that this is not the most optimal solution for merchants, but this is a restriction which we can’t go around for now. We will of course optimize this as soon as it is possible.

Learn more about [the difference between reserve and capture](https://developer.vippsmobilepay.com/docs/vipps-developers/faqs/reserve-and-capture-faq/#what-is-the-difference-between-reserve-capture-and-direct-capture).

## How to manage the Vipps orders in Wix Admin

See [Order management in Wix](order-management.md).

## How can I get help if I have any issues?

For issues with your Vipps for Wix installation, contact us via our [support system](https://crude.no/vipps-wix-support/). For other issues, contact [Vipps](https://developer.vippsmobilepay.com/docs/vipps-developers/contact/).

## Vipps FAQ

See the [Vipps API FAQ](https://developer.vippsmobilepay.com/docs/vipps-developers/faqs/) for more help with Vipps eCommerce.
