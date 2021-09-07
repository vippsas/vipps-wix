# Vipps for Wix

The Vipps product page is here: https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/Wix/

See the main GitHub page for Vipps contact information, etc: https://github.com/vippsas 

# Description

Official Vipps Payment for Wix. More than 3.6 million Norwegians use Vipps. Give them a fast and familiar shopping experience in Wix too!

This is the official Vipps plugin that provides a direct integration with Wix. Now you can let your customers choose Vipps directly in the checkout.

You can also do important back office tasks such as capture and refund directly from Wix. Easy for your customer and easy for you.

Read [information from Vipps](https://www.vipps.no/produkter-og-tjenester/bedrift/ta-betalt-paa-nett/ta-betalt-paa-nett/Wix/) about the plugin.

# Vipps Express Checkout
Vipps does not yet have a solution for express checkout in Wix

# Vipps Payment
When you enable this plugin, your customers will be able to choose Vipps as a payment method directly in the checkout. There is no need to go via a third party payment method. If your customer choose Vipps, the customer fills in their contact information and is then asked to enter their phone number in the Vipps dialogue. Then the customer confirms the payment in the Vipps app. The order is now completed and are now stored in your Wix store.

# How to get started
- Sign up to use Vipps på Nett [vipps.no/shopify](https://api.vippsbedrift.no/v1/partial/signup/vippspanett/shopify?utm_source=produktsideShopify&utm_medium=crude&utm_campaign=VippspanettShopify).
- After 1-2 days you will get an email with login details to Vipps Developer Portal, where you can get the API credentials
- Download and configure

# How to get Vipps account keys from Vipps Developer Portal
1. Sign in to the Vipps Portal at https://portal.vipps.no/ using Bank ID
2. Select the "Utvikler" ("Developer") tab and choose Production Keys. Here you can find the merchant serial number (6 figures)
3. Click on "Show keys" under the API keys column to see “Client ID”, “Client Secret” and “Vipps Subscription Key”

See: [Getting Started](https://github.com/vippsas/vipps-developers/blob/master/vipps-developer-portal-getting-started.md) with the Vipps Portal, and the Vipps eCommerce [FAQ](https://github.com/vippsas/vipps-ecom-api/blob/master/vipps-ecom-api-faq.md).

# Installation
Install Vipps for Wix by following [these instructions](https://crude.no/vipps-for-wix/).

# Important notes
To enable automatic capture when fulfilling orders in Wix, you'll need to install our assistant app together with the actual payment gateway. How to install the assistant app is outlined in the installation instructions above.

There is a special quirk you need to be aware of: When fulfilling, you need to add a tracking number to the order to make the auto-capture run. You can leave the tracking number field empty, and you dont need to send email to the customer from Wix, but you need to submit the tracking number form.

Remember, you can also use the Vipps Portal to capture the orders.

# How can I get help if I have any issues?
For issues with your Vipps for Wix installation contact us via our [support system here](https://crude.no/vipps-wix-support/). For other issues you should contact [Vipps](https://github.com/vippsas/vipps-developers/blob/master/contact.md).

# Vipps FAQ
See the [Vipps eCom API FAQ](https://github.com/vippsas/vipps-ecom-api/blob/master/vipps-ecom-api-faq.md) for more help with Vipps eCommerce.
