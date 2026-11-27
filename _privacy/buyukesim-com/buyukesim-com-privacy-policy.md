---
api_specs:
- filename: buyukesim-com-bundle-crypto-quote-php-api-openapi.yml
  format: yaml
  label: BuyUKeSIM Bundle Crypto Quote.php API
  slug: buyukesim-com-bundle-crypto-quote-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buyukesim-com/openapi/buyukesim-com-bundle-crypto-quote-php-api-openapi.yml
- filename: buyukesim-com-crypto-quote-php-api-openapi.yml
  format: yaml
  label: BuyUKeSIM Crypto Quote.php API
  slug: buyukesim-com-crypto-quote-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buyukesim-com/openapi/buyukesim-com-crypto-quote-php-api-openapi.yml
- filename: buyukesim-com-payment-methods-php-api-openapi.yml
  format: yaml
  label: BuyUKeSIM Payment Methods.php API
  slug: buyukesim-com-payment-methods-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buyukesim-com/openapi/buyukesim-com-payment-methods-php-api-openapi.yml
- filename: buyukesim-com-reviews-list-php-api-openapi.yml
  format: yaml
  label: BuyUKeSIM Reviews List.php API
  slug: buyukesim-com-reviews-list-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buyukesim-com/openapi/buyukesim-com-reviews-list-php-api-openapi.yml
- filename: buyukesim-com-topup-quote-php-api-openapi.yml
  format: yaml
  label: BuyUKeSIM Topup Quote.php API
  slug: buyukesim-com-topup-quote-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buyukesim-com/openapi/buyukesim-com-topup-quote-php-api-openapi.yml
- filename: buyukesim-com-travel-crypto-quote-php-api-openapi.yml
  format: yaml
  label: BuyUKeSIM Travel Crypto Quote.php API
  slug: buyukesim-com-travel-crypto-quote-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buyukesim-com/openapi/buyukesim-com-travel-crypto-quote-php-api-openapi.yml
- filename: buyukesim-com-travel-packages-php-api-openapi.yml
  format: yaml
  label: BuyUKeSIM Travel Packages.php API
  slug: buyukesim-com-travel-packages-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buyukesim-com/openapi/buyukesim-com-travel-packages-php-api-openapi.yml
- filename: buyukesim-com-vpn-crypto-quote-php-api-openapi.yml
  format: yaml
  label: BuyUKeSIM Vpn Crypto Quote.php API
  slug: buyukesim-com-vpn-crypto-quote-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buyukesim-com/openapi/buyukesim-com-vpn-crypto-quote-php-api-openapi.yml
- filename: buyukesim-com-vpn-plans-php-api-openapi.yml
  format: yaml
  label: BuyUKeSIM Vpn Plans.php API
  slug: buyukesim-com-vpn-plans-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buyukesim-com/openapi/buyukesim-com-vpn-plans-php-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: Optional email . Only if you choose to enter one, at checkout or later from your own order page.
  - category: financial
    text: Order details . The product you bought, the crypto amount, payment status, and a lookup code so you can find the order later.
  - category: device
    text: Every public page runs a small beacon that pings our server about every 50 seconds with the page you are on, the page you came from, and a random id your browser generates and keeps in local storage.
  - category: location
    text: Country signal . A coarse country (from Cloudflare), stored with your order and in our own server-side statistics.
  - category: communication
    text: Support messages . If you use live chat or the Telegram bot, the messages you send and a random visitor id so we can reply.
  deletion:
    route: Order email deletion via order page; other requests by contacting us
    text: An email you added yourself from your order page is deleted the moment you switch reminders off there; for anything else, ask us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Deliver eSIM and process crypto payment
    text: Only what is strictly needed to take a crypto payment and deliver a digital eSIM
  - purpose: Analytics
    text: 'Our analytics are first-party and self-hosted : no Google, no third-party analytics product, no advertising network.'
  - purpose: Affiliate referral credit
    text: to credit an affiliate referral
  - purpose: Support
    text: the messages you send and a random visitor id so we can reply
  retention:
  - period: null
    scope: Visit records
    text: The whole row is deleted two days after your last page view.
  - period: 180 days
    scope: Support messages
    text: Chat and Telegram messages, 180 days.
  - period: 30 days
    scope: Request and security logs
    text: 'The API log records endpoint, status code, duration and country, and nothing that identifies you: 30 days, or 7 for the admin panel’s own traffic.'
  - period: 14 days
    scope: Web server logs
    text: Web server logs rotate after 14 days.
  - period: null
    scope: Order records
    text: These have no fixed deletion date, because your eSIM, your top-ups and your refund window all depend on them.
  - period: 180 days
    scope: Email message body
    text: The message body itself is erased after 180 days, because an order email contains a link that opens your order.
  rights:
  - right: access, correct, or delete
    text: you may have rights to access, correct, or delete personal data (for example under the GDPR or CCPA)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Sell, rent, or share your data with data brokers or advertisers
  subprocessors:
    text: Cloudflare CDN, TLS and DDoS protection. Every request to the site passes through it, and it is where the coarse country signal comes from.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BuyUKeSIM
provenance_date: '2026-11-09'
provider_name: BuyUKeSIM
provider_slug: buyukesim-com
slug: buyukesim-com-privacy-policy
source_date: '2026-11-09'
source_filename: buyukesim-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://buyukesim.com/en/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BuyUKeSIM\naid: buyukesim-com\nurl: https://buyukesim.com/en/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Optional email . Only if you choose to enter one, at checkout or later from your own order page.\n- category: financial\n  text: Order details . The product you bought, the crypto amount, payment status, and a lookup code so you can\n    find the order later.\n- category: device\n  text: Every public page runs a small beacon that pings our server about every 50 seconds with the page you are\n    on, the page you came from, and\
  \ a random id your browser generates and keeps in local storage.\n- category: location\n  text: Country signal . A coarse country (from Cloudflare), stored with your order and in our own server-side statistics.\n- category: communication\n  text: Support messages . If you use live chat or the Telegram bot, the messages you send and a random visitor\n    id so we can reply.\npurposes:\n- purpose: Deliver eSIM and process crypto payment\n  text: Only what is strictly needed to take a crypto payment and deliver a digital eSIM\n- purpose: Analytics\n  text: 'Our analytics are first-party and self-hosted : no Google, no third-party analytics product, no advertising\n    network.'\n- purpose: Affiliate referral credit\n  text: to credit an affiliate referral\n- purpose: Support\n  text: the messages you send and a random visitor id so we can reply\nretention:\n- scope: Visit records\n  period: null\n  text: The whole row is deleted two days after your last page view.\n- scope: Support messages\n\
  \  period: 180 days\n  text: Chat and Telegram messages, 180 days.\n- scope: Request and security logs\n  period: 30 days\n  text: 'The API log records endpoint, status code, duration and country, and nothing that identifies you: 30 days,\n    or 7 for the admin panel’s own traffic.'\n- scope: Web server logs\n  period: 14 days\n  text: Web server logs rotate after 14 days.\n- scope: Order records\n  period: null\n  text: These have no fixed deletion date, because your eSIM, your top-ups and your refund window all depend on\n    them.\n- scope: Email message body\n  period: 180 days\n  text: The message body itself is erased after 180 days, because an order email contains a link that opens your\n    order.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare CDN, TLS and DDoS protection. Every request to the site passes through it, and it is where the\n    coarse country signal comes from.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route:\
  \ Order email deletion via order page; other requests by contacting us\n  text: An email you added yourself from your order page is deleted the moment you switch reminders off there; for\n    anything else, ask us.\nrights:\n- right: access, correct, or delete\n  text: you may have rights to access, correct, or delete personal data (for example under the GDPR or CCPA)\nsale_or_sharing:\n  stance: prohibited\n  text: Sell, rent, or share your data with data brokers or advertisers\n"
source_yaml_url: https://artifacts.apis.io/buyukesim-com/privacy/buyukesim-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from BuyUKeSIM's own page on 2026-11-09.
synthetic: false
tags:
- eSIM
- Cryptocurrency
- Privacy
- Telecommunications
- Travel
---
