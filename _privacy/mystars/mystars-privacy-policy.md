---
api_specs:
- filename: mystars-mystars-faas-fulfilment-api-api-openapi.yml
  format: yaml
  label: MyStars FaaS MyStars FaaS — Fulfilment API
  slug: mystars-mystars-faas-fulfilment-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystars/openapi/mystars-mystars-faas-fulfilment-api-api-openapi.yml
- filename: mystars-orders-api-openapi.yml
  format: yaml
  label: MyStars FaaS Orders API
  slug: mystars-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystars/openapi/mystars-orders-api-openapi.yml
- filename: mystars-pricing-api-openapi.yml
  format: yaml
  label: MyStars FaaS Pricing API
  slug: mystars-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystars/openapi/mystars-pricing-api-openapi.yml
- filename: mystars-recipients-api-openapi.yml
  format: yaml
  label: MyStars FaaS Recipients API
  slug: mystars-recipients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystars/openapi/mystars-recipients-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Telegram account information — your Telegram user ID, username, first name, and photo URL
  - category: financial
    text: Transaction data — payment amounts, payment method (GRAM or USDT), blockchain transaction hashes, transaction status, and timestamps.
  - category: device
    text: Technical data — IP addresses (forwarded via proxy headers), browser user agent, and device type for security and rate limiting purposes.
  - category: behavioral
    text: Referral tracking data — referral codes, attribution sources (cookie or Telegram start parameter), and referral relationship records.
  deletion:
    route: Contact us
    text: Request deletion of your Microsoft Clarity session recordings — contact us and we will remove identified sessions within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Processing Stars purchases
    text: Processing your Telegram Stars purchases and delivering Stars to your account.
  - purpose: Verifying blockchain payments
    text: Verifying blockchain payments and managing transaction status.
  - purpose: Referral commissions
    text: Calculating and distributing referral commissions.
  - purpose: Fraud prevention and security
    text: Preventing fraud and enforcing rate limits.
  residency:
  - region: Russian Federation
    text: it transfers this data to servers in the Russian Federation
  retention:
  - period: indefinitely
    scope: Transaction records
    text: Transaction records — retained indefinitely for financial record-keeping and legal compliance.
  - period: 365 days
    scope: Referral cookies
    text: Referral cookies — expire after 365 days from the date of first click.
  - period: 30 days
    scope: Clarity session recordings
    text: Clarity session recordings — retained for 30 days, then permanently deleted.
  rights:
  - right: Access
    text: Request information about the data we hold about your account.
  - right: Deletion
    text: Request deletion of non-essential data associated with your account.
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
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MyStars FaaS
provenance_date: '2026-11-10'
provider_name: MyStars FaaS
provider_slug: mystars
slug: mystars-privacy-policy
source_date: '2026-11-10'
source_filename: mystars-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mystars.tg/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MyStars FaaS\naid: mystars\nurl: https://mystars.tg/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Telegram account information — your Telegram user ID, username, first name, and photo URL\n- category: financial\n  text: Transaction data — payment amounts, payment method (GRAM or USDT), blockchain transaction hashes, transaction\n    status, and timestamps.\n- category: device\n  text: Technical data — IP addresses (forwarded via proxy headers), browser user agent, and device type for security\n    and rate limiting purposes.\n\
  - category: behavioral\n  text: Referral tracking data — referral codes, attribution sources (cookie or Telegram start parameter), and referral\n    relationship records.\npurposes:\n- purpose: Processing Stars purchases\n  text: Processing your Telegram Stars purchases and delivering Stars to your account.\n- purpose: Verifying blockchain payments\n  text: Verifying blockchain payments and managing transaction status.\n- purpose: Referral commissions\n  text: Calculating and distributing referral commissions.\n- purpose: Fraud prevention and security\n  text: Preventing fraud and enforcing rate limits.\nretention:\n- scope: Transaction records\n  period: indefinitely\n  text: Transaction records — retained indefinitely for financial record-keeping and legal compliance.\n- scope: Referral cookies\n  period: 365 days\n  text: Referral cookies — expire after 365 days from the date of first click.\n- scope: Clarity session recordings\n  period: 30 days\n  text: Clarity session recordings\
  \ — retained for 30 days, then permanently deleted.\nresidency:\n- region: Russian Federation\n  text: it transfers this data to servers in the Russian Federation\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us\n  text: Request deletion of your Microsoft Clarity session recordings — contact us and we will remove identified\n    sessions within 30 days.\nrights:\n- right: Access\n  text: Request information about the data we hold about your account.\n- right: Deletion\n  text: Request deletion of non-essential data associated with your account.\n- right: Withdraw consent\n  text: You can withdraw or change your consent at any time via “Cookie settings” in the site footer.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mystars/privacy/mystars-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 16 quoted statements, read from MyStars FaaS's own page on 2026-11-10.
synthetic: false
tags:
- Telegram
- telegram-stars
- telegram-premium
- Payments
- Cryptocurrency
- TON
- Fulfilment
- Blockchain
- Digital Goods
- reseller-api
---
