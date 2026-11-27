---
api_specs:
- filename: degenhedge-com-fees-api-openapi.yml
  format: yaml
  label: DegenHedge Fees API
  slug: degenhedge-com-fees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/degenhedge-com/openapi/degenhedge-com-fees-api-openapi.yml
- filename: degenhedge-com-market-data-api-openapi.yml
  format: yaml
  label: DegenHedge market data API
  slug: degenhedge-com-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/degenhedge-com/openapi/degenhedge-com-market-data-api-openapi.yml
- filename: degenhedge-com-record-api-openapi.yml
  format: yaml
  label: DegenHedge Record API
  slug: degenhedge-com-record-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/degenhedge-com/openapi/degenhedge-com-record-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: contact
    text: email address; name (if given)
  - category: financial
    text: 'Payment information: processed by Stripe . We do not store full card numbers; we receive limited transaction and customer-reference data from Stripe.'
  - category: device
    text: IP address, device/browser (user-agent), pages viewed, and similar usage data
  - category: communication
    text: any messages you send us
  - category: identifying
    text: your Telegram username/ID when you connect to our bot
  deletion:
    route: null
    text: after which we delete or de-identify it
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and deliver the Service
    text: 'To: provide and deliver the Service and signal alerts; create and manage your account; process subscriptions and billing'
  - purpose: marketing emails
    text: send transactional and (with your sign-up) marketing emails such as the weekly recap
  - purpose: security and fraud prevention
    text: maintain security and prevent fraud
  - purpose: improve the Service
    text: improve the Service
  retention:
  - period: null
    scope: personal information
    text: We keep personal information for as long as your account is active and as needed for the purposes above, then for a reasonable period to meet legal, tax, accounting, and dispute-resolution needs, after which we delete or de-identify it.
  rights:
  - right: access, correct, delete, or obtain a copy
    text: you may have rights to access, correct, delete, or obtain a copy of your personal information
  - right: opt out of certain sharing
    text: and to opt out of certain sharing
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information, and we do not share it for cross-context behavioral advertising.
  subprocessors:
    text: Stripe (payments), Resend (email delivery), Telegram (alert delivery), Cloudflare (hosting/CDN/security), and analytics providers.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DegenHedge
provenance_date: '2026-11-09'
provider_name: DegenHedge
provider_slug: degenhedge-com
slug: degenhedge-com-privacy-policy
source_date: '2026-11-09'
source_filename: degenhedge-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://degenhedge.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DegenHedge\naid: degenhedge-com\nurl: https://degenhedge.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: email address; name (if given)\n- category: financial\n  text: 'Payment information: processed by Stripe . We do not store full card numbers; we receive limited transaction\n    and customer-reference data from Stripe.'\n- category: device\n  text: IP address, device/browser (user-agent), pages viewed, and similar usage data\n- category: communication\n  text: any messages you send us\n- category: identifying\n  text: your Telegram\
  \ username/ID when you connect to our bot\npurposes:\n- purpose: provide and deliver the Service\n  text: 'To: provide and deliver the Service and signal alerts; create and manage your account; process subscriptions\n    and billing'\n- purpose: marketing emails\n  text: send transactional and (with your sign-up) marketing emails such as the weekly recap\n- purpose: security and fraud prevention\n  text: maintain security and prevent fraud\n- purpose: improve the Service\n  text: improve the Service\nretention:\n- scope: personal information\n  period: null\n  text: We keep personal information for as long as your account is active and as needed for the purposes above,\n    then for a reasonable period to meet legal, tax, accounting, and dispute-resolution needs, after which we delete\n    or de-identify it.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Stripe (payments), Resend (email delivery), Telegram (alert delivery), Cloudflare (hosting/CDN/security),\n    and\
  \ analytics providers.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: after which we delete or de-identify it\nrights:\n- right: access, correct, delete, or obtain a copy\n  text: you may have rights to access, correct, delete, or obtain a copy of your personal information\n- right: opt out of certain sharing\n  text: and to opt out of certain sharing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information, and we do not share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/degenhedge-com/privacy/degenhedge-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from DegenHedge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Prediction Markets
- Kalshi
- Bitcoin
- Trading Signals
- Telegram
- Sports Betting
- MCP
- Market Data
---
