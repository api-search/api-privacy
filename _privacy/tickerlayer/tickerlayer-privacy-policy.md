---
api_specs:
- filename: tickerlayer-openapi-generated.yml
  format: yaml
  label: TickerLayer API
  slug: tickerlayer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickerlayer/openapi/_ae-authored/tickerlayer-openapi-generated.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account and sign-in data: your email address, a password hash held by our authentication provider, and account identifiers.'
  - category: financial
    text: 'Billing data: when you buy a plan by card, our payment processor collects your card details directly; we do not receive or store full card numbers.'
  - category: location
    text: WebSocket connection records (the source IP address and country, the API key used, and when and how each connection ended)
  - category: device
    text: 'Usage and technical data: request logs, timestamps, IP addresses, device and browser type, error diagnostics, and security signals needed to operate, secure, and improve the Services.'
  - category: communication
    text: 'Support communications: information you send when you contact us by email, through a form, or through the support chat where it is available.'
  - category: behavioral
    text: 'Product interactions: search terms typed into the public symbol directory, symbol lists pasted into the coverage checker and which entries were not covered, symbol or market requests you submit'
  deletion:
    route: Account settings or email request
    text: You can request deletion of your account from your account settings or by email.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and secure the Services
    text: To provide, maintain, and secure the Services; to authenticate users, connectors, and agents
  - purpose: Payments and invoicing
    text: To process payments, issue invoices and receipts, send renewal reminders, and keep the records that tax and accounting law require.
  - purpose: Fraud and security
    text: To detect, prevent, and respond to fraud, abuse, chargebacks, or security incidents.
  - purpose: Product planning
    text: To understand which markets and symbols people look for, so we can decide what coverage to add next
  retention:
  - period: null
    scope: Account data
    text: We keep account data for as long as your account exists and for a limited period afterwards to meet legal, accounting, and security obligations.
  - period: 7 days
    scope: WebSocket connection records
    text: WebSocket connection records (the source IP address and country, the API key used, and when and how each connection ended) are kept for 7 days
  - period: null
    scope: Blockchain records of pay-per-call payments
    text: Blockchain records of pay-per-call payments are permanent by the nature of public networks and are outside our control.
  rights:
  - right: access, correct, delete, port, object
    text: you may have rights to access, correct, delete, port, or object to certain processing, or to lodge a complaint with a supervisory authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information as a “sale” is commonly understood in U.S. state privacy laws
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Where we transfer personal data across borders, we implement appropriate safeguards as required by applicable law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TickerLayer
provenance_date: '2026-11-10'
provider_name: TickerLayer
provider_slug: tickerlayer
slug: tickerlayer-privacy-policy
source_date: '2026-11-10'
source_filename: tickerlayer-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tickerlayer.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TickerLayer\naid: tickerlayer\nurl: https://tickerlayer.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account and sign-in data: your email address, a password hash held by our authentication provider, and\n    account identifiers.'\n- category: financial\n  text: 'Billing data: when you buy a plan by card, our payment processor collects your card details directly; we\n    do not receive or store full card numbers.'\n- category: location\n  text: WebSocket connection records (the source IP address and country, the API\
  \ key used, and when and how each\n    connection ended)\n- category: device\n  text: 'Usage and technical data: request logs, timestamps, IP addresses, device and browser type, error diagnostics,\n    and security signals needed to operate, secure, and improve the Services.'\n- category: communication\n  text: 'Support communications: information you send when you contact us by email, through a form, or through the\n    support chat where it is available.'\n- category: behavioral\n  text: 'Product interactions: search terms typed into the public symbol directory, symbol lists pasted into the\n    coverage checker and which entries were not covered, symbol or market requests you submit'\npurposes:\n- purpose: Provide and secure the Services\n  text: To provide, maintain, and secure the Services; to authenticate users, connectors, and agents\n- purpose: Payments and invoicing\n  text: To process payments, issue invoices and receipts, send renewal reminders, and keep the records that tax\n\
  \    and accounting law require.\n- purpose: Fraud and security\n  text: To detect, prevent, and respond to fraud, abuse, chargebacks, or security incidents.\n- purpose: Product planning\n  text: To understand which markets and symbols people look for, so we can decide what coverage to add next\nretention:\n- scope: Account data\n  period: null\n  text: We keep account data for as long as your account exists and for a limited period afterwards to meet legal,\n    accounting, and security obligations.\n- scope: WebSocket connection records\n  period: 7 days\n  text: WebSocket connection records (the source IP address and country, the API key used, and when and how each\n    connection ended) are kept for 7 days\n- scope: Blockchain records of pay-per-call payments\n  period: null\n  text: Blockchain records of pay-per-call payments are permanent by the nature of public networks and are outside\n    our control.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Where we transfer personal\
  \ data across borders, we implement appropriate safeguards as required by applicable\n    law.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings or email request\n  text: You can request deletion of your account from your account settings or by email.\nrights:\n- right: access, correct, delete, port, object\n  text: you may have rights to access, correct, delete, port, or object to certain processing, or to lodge a complaint\n    with a supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information as a “sale” is commonly understood in U.S. state privacy laws\n"
source_yaml_url: https://artifacts.apis.io/tickerlayer/privacy/tickerlayer-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from TickerLayer's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Market Data
- Real-Time
- Finance
---
