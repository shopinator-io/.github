# Shopinator: Shopify apps you can trust

We build Shopify apps for real problems in real stores: incomplete delivery addresses, buyers who want to know when
an order arrives, and checkout rules Shopify doesn't cover on its own. Every app comes with security, data privacy
and direct support built in, and is available in English, German, Spanish, French and Italian.

[Website](https://shopinator.io) · [Shopify App Store](https://apps.shopify.com/partners/cs86) ·
[Documentation](https://shopinator.io/docs) · [Custom Shopify apps](https://shopinator.io/custom-apps) ·
[Support](mailto:support@shopinator.io)

## Apps

### Address Validator: address validation for Shopify checkout

<a href="https://apps.shopify.com/checkout-address-validator-1"><img src="https://shopinator.io/shopify/app-store-badge-dark.svg" alt="Get Address Validator on the Shopify App Store" height="48"></a>

Shopify blocks an address without a postal code where the country needs one, but it only warns about a missing house
number, and buyers can skip the warning. Address Validator turns that warning into a block, can require a postal code
where Shopify leaves it optional, and lets you write your own regex pattern per country for any check you need. Fewer
parcels come back as undeliverable.

- Blocks checkout when the house number or the postal code is missing
- Also checks express checkouts: Shop Pay, PayPal, Apple Pay and Google Pay
- Rules per country: require a postal code where Shopify leaves it optional, or write your own regex pattern
- Parcel lockers, pickup points, P.O. boxes and "s/n" addresses pass, for example Packstation, Paczkomat and Point Relais
- Buyer messages in 33 languages, editable for every language your store publishes
- An address tester that runs any address through your rules, without placing an order
- Pause the block with one setting; your rules stay saved
- Admin in English, German, Spanish, French and Italian
- Works on every Shopify plan; no Shopify Plus needed, because the check runs as a Shopify Function

$4.99 a month or $49.99 a year, billed through Shopify, with a 14-day free trial.

[Address Validator](https://shopinator.io/address-validator) ·
[Docs](https://shopinator.io/docs/address-validator) ·
[Shopify address validation explained](https://shopinator.io/docs/address-validator/shopify-address-validation) ·
[Country rules and regex patterns](https://shopinator.io/docs/address-validator/country-rules) ·
[Postal codes](https://shopinator.io/docs/address-validator/postal-codes)

### Delivery Date: estimated delivery dates for Shopify

Coming soon to the Shopify App Store.

Delivery Date shows buyers when an order arrives, before they buy. The estimated delivery date appears on the product
page, in the cart, under the delivery address in checkout, and on the Thank you and Order status pages.

- A cut-off countdown that shows how long is left to order for shipping today
- Delivery times per country, for products in stock and out of stock, with overrides per product
- Cut-off, working days, closures and public holidays for every location
- Optional delivery times measured from your own fulfilled orders
- Wording in English, German, French, Spanish and Italian, editable for every store language
- Works on every Shopify plan except Starter; only the date inside the checkout steps needs Shopify Plus

$9.99 a month or $99 a year, billed through Shopify, with a 14-day free trial.

[Delivery Date](https://shopinator.io/delivery-date) · [Docs](https://shopinator.io/docs/delivery-date) ·
[How delivery dates are calculated](https://shopinator.io/docs/delivery-date/how-dates-are-calculated)

## Custom Shopify apps

We also build private apps for a single store: checkout rules with Shopify Functions, fields and messages in
checkout and customer accounts, theme blocks, admin pages for your team, and connections to your ERP, warehouse or
shipping provider. You get a proposal with scope, timeline and price before any work starts.
[Custom Shopify app development](https://shopinator.io/custom-apps)

## How we work

- **Your data stays small and close.** Settings live in your own store as app-owned metafields. Outside Shopify we
  keep only the session needed to connect the app, in Amazon DynamoDB in Frankfurt, Germany.
- **No buyer data leaves Shopify.** Address Validator's check runs inside Shopify checkout; Delivery Date reads only the
  shipping country.
- **Security by default.** Encryption in transit and at rest, secrets read at runtime from encrypted storage, Admin
  API access limited by an IP allowlist, and dependencies kept up to date.
- **Direct support.** The people who build the apps answer every message.

## In your language

The website and the documentation are available in
[English](https://shopinator.io), [Deutsch](https://shopinator.io/de), [Español](https://shopinator.io/es),
[Français](https://shopinator.io/fr) and [Italiano](https://shopinator.io/it).

## Legal

[Privacy Policy](https://shopinator.io/privacy-policy) · [Imprint](https://shopinator.io/legal)
