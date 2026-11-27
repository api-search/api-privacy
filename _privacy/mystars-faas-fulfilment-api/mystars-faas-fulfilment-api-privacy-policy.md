---
api_specs:
- filename: mystars-faas-fulfilment-api-mystars-faas-fulfilment-api-api-openapi.yml
  format: yaml
  label: MyStars FaaS — Fulfilment API MyStars FaaS — Fulfilment API
  slug: mystars-faas-fulfilment-api-mystars-faas-fulfilment-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystars-faas-fulfilment-api/openapi/mystars-faas-fulfilment-api-mystars-faas-fulfilment-api-api-openapi.yml
- filename: mystars-faas-fulfilment-api-orders-api-openapi.yml
  format: yaml
  label: MyStars FaaS — Fulfilment API Orders API
  slug: mystars-faas-fulfilment-api-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystars-faas-fulfilment-api/openapi/mystars-faas-fulfilment-api-orders-api-openapi.yml
- filename: mystars-faas-fulfilment-api-pricing-api-openapi.yml
  format: yaml
  label: MyStars FaaS — Fulfilment API Pricing API
  slug: mystars-faas-fulfilment-api-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystars-faas-fulfilment-api/openapi/mystars-faas-fulfilment-api-pricing-api-openapi.yml
- filename: mystars-faas-fulfilment-api-recipients-api-openapi.yml
  format: yaml
  label: MyStars FaaS — Fulfilment API Recipients API
  slug: mystars-faas-fulfilment-api-recipients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystars-faas-fulfilment-api/openapi/mystars-faas-fulfilment-api-recipients-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: your Telegram user ID, username, first name, and photo URL
  - category: financial
    text: payment amounts, payment method (GRAM or USDT), blockchain transaction hashes, transaction status, and timestamps
  - category: identifying
    text: the public wallet address you connect via TON Connect
  - category: device
    text: browser user agent, and device type for security and rate limiting purposes
  - category: device
    text: IP addresses (forwarded via proxy headers)
  - category: behavioral
    text: mouse movement, scrolls, taps, rage-clicks
  deletion:
    route: contact us
    text: Request deletion of your Microsoft Clarity session recordings — contact us and we will remove identified sessions within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Stars purchases and delivery
    text: Processing your Telegram Stars purchases and delivering Stars to your account.
  - purpose: Referral commissions
    text: Calculating and distributing referral commissions.
  - purpose: Fraud prevention and rate limits
    text: Preventing fraud and enforcing rate limits.
  residency:
  - region: Russian Federation
    text: it transfers this data to servers in the Russian Federation
  retention:
  - period: indefinitely
    scope: Transaction records
    text: Transaction records — retained indefinitely for financial record-keeping and legal compliance.
  - period: 30 days
    scope: Clarity session recordings
    text: Clarity session recordings are retained for 30 days (shorter than Clarity's 90-day default), then permanently deleted.
  - period: 365 days
    scope: Referral cookies
    text: Referral cookies — expire after 365 days from the date of first click.
  - period: a limited period
    scope: Technical logs
    text: Technical logs — IP addresses and request logs are retained for a limited period for security monitoring.
  rights:
  - right: Access to account data
    text: Request information about the data we hold about your account.
  - right: Deletion of non-essential data
    text: Request deletion of non-essential data associated with your account.
  - right: Clear referral cookies
    text: Clear referral cookies at any time by deleting cookies in your browser settings.
  - right: Disconnect wallet
    text: Disconnect your TON wallet at any time via the TON Connect interface.
  - right: Withdraw consent
    text: You can withdraw or change your consent at any time via “Cookie settings” in the site footer.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: it transfers this data to servers in the Russian Federation
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MyStars FaaS — Fulfilment API
provenance_date: '2026-11-10'
provider_name: MyStars FaaS — Fulfilment API
provider_slug: mystars-faas-fulfilment-api
slug: mystars-faas-fulfilment-api-privacy-policy
source_date: '2026-11-10'
source_filename: mystars-faas-fulfilment-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mystars.tg/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MyStars FaaS — Fulfilment API\naid: mystars-faas-fulfilment-api\nurl: https://mystars.tg/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your Telegram user ID, username, first name, and photo URL\n- category: financial\n  text: payment amounts, payment method (GRAM or USDT), blockchain transaction hashes, transaction status, and timestamps\n- category: identifying\n  text: the public wallet address you connect via TON Connect\n- category: device\n  text: browser user agent, and device type for security and rate limiting purposes\n\
  - category: device\n  text: IP addresses (forwarded via proxy headers)\n- category: behavioral\n  text: mouse movement, scrolls, taps, rage-clicks\npurposes:\n- purpose: Stars purchases and delivery\n  text: Processing your Telegram Stars purchases and delivering Stars to your account.\n- purpose: Referral commissions\n  text: Calculating and distributing referral commissions.\n- purpose: Fraud prevention and rate limits\n  text: Preventing fraud and enforcing rate limits.\nretention:\n- scope: Transaction records\n  period: indefinitely\n  text: Transaction records — retained indefinitely for financial record-keeping and legal compliance.\n- scope: Clarity session recordings\n  period: 30 days\n  text: Clarity session recordings are retained for 30 days (shorter than Clarity's 90-day default), then permanently\n    deleted.\n- scope: Referral cookies\n  period: 365 days\n  text: Referral cookies — expire after 365 days from the date of first click.\n- scope: Technical logs\n  period:\
  \ a limited period\n  text: Technical logs — IP addresses and request logs are retained for a limited period for security monitoring.\nresidency:\n- region: Russian Federation\n  text: it transfers this data to servers in the Russian Federation\ntransfers:\n- mechanism: other\n  text: it transfers this data to servers in the Russian Federation\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact us\n  text: Request deletion of your Microsoft Clarity session recordings — contact us and we will remove identified\n    sessions within 30 days.\nrights:\n- right: Access to account data\n  text: Request information about the data we hold about your account.\n- right: Deletion of non-essential data\n  text: Request deletion of non-essential data associated with your account.\n- right: Clear referral cookies\n  text: Clear referral cookies at any time by deleting cookies in your browser settings.\n- right: Disconnect wallet\n\
  \  text: Disconnect your TON wallet at any time via the TON Connect interface.\n- right: Withdraw consent\n  text: You can withdraw or change your consent at any time via “Cookie settings” in the site footer.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mystars-faas-fulfilment-api/privacy/mystars-faas-fulfilment-api-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 21 quoted statements, read from MyStars FaaS — Fulfilment API's own page on 2026-11-10.
synthetic: false
tags:
- Telegram
- telegram-stars
- telegram-premium
- Payments
- Cryptocurrency
- TON
- gram
- USDT
- Fintech
- Fulfilment
- Digital Goods
- Non-Custodial
- NoKYC
---
