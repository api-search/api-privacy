---
api_specs:
- filename: twitterapi-io-oapi-api-openapi.yml
  format: yaml
  label: TwitterAPI.io Oapi API
  slug: twitterapi-io-oapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitterapi-io/openapi/twitterapi-io-oapi-api-openapi.yml
- filename: twitterapi-io-plants-api-openapi.yml
  format: yaml
  label: TwitterAPI.io Plants API
  slug: twitterapi-io-plants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitterapi-io/openapi/twitterapi-io-plants-api-openapi.yml
- filename: twitterapi-io-twitter-api-openapi.yml
  format: yaml
  label: TwitterAPI.io Twitter API
  slug: twitterapi-io-twitter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitterapi-io/openapi/twitterapi-io-twitter-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: financial
    text: From Stripe we keep your customer and payment-method identifiers, the card brand, its last four digits, expiry date and a card fingerprint
  - category: location
    text: your approximate location derived from your IP address
  - category: device
    text: your browser and device type, and identifiers stored in cookies
  - category: communication
    text: If you email us or contact support we keep the message, your email address and our reply.
  deletion:
    route: Email hello@twitterapi.io to request account deletion
    text: Write to hello@twitterapi.io from the email address of your account. There is no delete button in the dashboard yet, so deletion is done by our staff on request
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: 'To provide the service: create and secure your account, issue API keys, answer API requests.'
  - purpose: Billing
    text: 'To bill you: count usage, charge credits, process payments, refunds and affiliate payouts.'
  - purpose: Security and abuse prevention
    text: 'To keep the service safe: enforce rate limits and the free-tool limits, detect fraud, abuse and duplicate accounts, and investigate incidents.'
  - purpose: Product and marketing measurement
    text: 'To understand and improve the product and our marketing: measure which pages and features are used, which channels bring visitors and customers, and whether our advertising works.'
  residency:
  - region: United States
    text: In our account database, on servers in the United States, linked to your API key and credit balance.
  retention:
  - period: null
    scope: Account record including Google user data
    text: While your account exists. It is not deleted automatically; we delete it when you ask us to.
  - period: 15 days
    scope: Detailed log of each billed API call
    text: 15 days, then deleted automatically.
  - period: null
    scope: Payment, invoice and payout records
    text: As long as accounting, tax and anti-fraud rules require, also after the account is deleted.
  - period: null
    scope: Caches
    text: From minutes to about 5 days.
  rights:
  - right: Access copy
    text: You can ask us at any time to give you a copy of the personal information we hold about you
  - right: Correction
    text: to correct it
  - right: Deletion
    text: to delete your account and the information in it
  - right: Object to processing
    text: the right to object to processing
  - right: Data portability
    text: the right to data portability
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: Provider What for What they receive Google (sign-in) Signing you in
    url: null
  transfers:
  - mechanism: SCC
    text: Where the law requires it, we rely on appropriate safeguards for those transfers, such as standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TwitterAPI.io
provenance_date: '2026-11-10'
provider_name: TwitterAPI.io
provider_slug: twitterapi-io
slug: twitterapi-io-privacy-policy
source_date: '2026-11-10'
source_filename: twitterapi-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://twitterapi.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TwitterAPI.io\naid: twitterapi-io\nurl: https://twitterapi.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: financial\n  text: From Stripe we keep your customer and payment-method identifiers, the card brand, its last four digits,\n    expiry date and a card fingerprint\n- category: location\n  text: your approximate location derived from your IP address\n- category: device\n  text: your browser and device type, and identifiers stored in cookies\n- category: communication\n  text: If you email us or contact support we keep the message, your email\
  \ address and our reply.\npurposes:\n- purpose: Provide the service\n  text: 'To provide the service: create and secure your account, issue API keys, answer API requests.'\n- purpose: Billing\n  text: 'To bill you: count usage, charge credits, process payments, refunds and affiliate payouts.'\n- purpose: Security and abuse prevention\n  text: 'To keep the service safe: enforce rate limits and the free-tool limits, detect fraud, abuse and duplicate\n    accounts, and investigate incidents.'\n- purpose: Product and marketing measurement\n  text: 'To understand and improve the product and our marketing: measure which pages and features are used, which\n    channels bring visitors and customers, and whether our advertising works.'\nretention:\n- scope: Account record including Google user data\n  period: null\n  text: While your account exists. It is not deleted automatically; we delete it when you ask us to.\n- scope: Detailed log of each billed API call\n  period: 15 days\n  text: 15 days,\
  \ then deleted automatically.\n- scope: Payment, invoice and payout records\n  period: null\n  text: As long as accounting, tax and anti-fraud rules require, also after the account is deleted.\n- scope: Caches\n  period: null\n  text: From minutes to about 5 days.\nresidency:\n- region: United States\n  text: In our account database, on servers in the United States, linked to your API key and credit balance.\ntransfers:\n- mechanism: SCC\n  text: Where the law requires it, we rely on appropriate safeguards for those transfers, such as standard contractual\n    clauses.\nsubprocessors:\n  url: null\n  text: Provider What for What they receive Google (sign-in) Signing you in\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@twitterapi.io to request account deletion\n  text: Write to hello@twitterapi.io from the email address of your account. There is no delete button in the dashboard\n    yet, so deletion is done by our staff on request\nrights:\n- right:\
  \ Access copy\n  text: You can ask us at any time to give you a copy of the personal information we hold about you\n- right: Correction\n  text: to correct it\n- right: Deletion\n  text: to delete your account and the information in it\n- right: Object to processing\n  text: the right to object to processing\n- right: Data portability\n  text: the right to data portability\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/twitterapi-io/privacy/twitterapi-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from TwitterAPI.io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- xAPI
- Data Provider
- REST
- Third Party
---
