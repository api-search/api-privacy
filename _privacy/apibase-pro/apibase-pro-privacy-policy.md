---
api_specs:
- filename: apibase-pro-tools-api-openapi.yml
  format: yaml
  label: APIbase Tools API
  slug: apibase-pro-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apibase-pro/openapi/apibase-pro-tools-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Agent credentials: API keys (stored as SHA-256 hashes, never in plaintext), agent identifiers.'
  - category: financial
    text: 'Payment data: USDC wallet addresses, transaction hashes, escrow records.'
  - category: contact
    text: Messages sent through the contact form are stored with the name, e-mail address, message text and IP address you submit
  - category: device
    text: IP addresses in application logs (only in Nginx access logs, retained 15 days).
  - category: behavioral
    text: 'Request logs: Request IDs, tool IDs, timestamps, response status codes.'
  deletion:
    route: Request to support@apibase.pro
    text: We delete data on request where technically possible; on-chain records and public receipts cannot be deleted and contain no name, e-mail or IP address.
  dpa:
    available: true
    text: For order data the merchant is the controller and APIbase is the processor ( DPA ).
    url: null
  purposes:
  - purpose: Authenticate and authorize API requests
    text: Authenticate and authorize API requests.
  - purpose: Process payments and maintain financial ledger
    text: Process x402 and MPP micropayments, debit refund credit balances, and maintain the financial ledger.
  - purpose: Abuse prevention and rate limiting
    text: Enforce rate limits and prevent abuse.
  - purpose: System health monitoring
    text: Monitor system health and performance.
  retention:
  - period: Indefinite
    scope: Ledger and public receipts
    text: Indefinite (financial record, append-only; wallet addresses and hashes only)
  - period: Not more than 15 days
    scope: Nginx and Loki logs
    text: Nginx and Loki logs Not more than 15 days
  - period: 12 months
    scope: Contact messages
    text: Messages sent through the contact form are stored with the name, e-mail address, message text and IP address you submit, and kept for 12 months, then deleted.
  - period: 14 days (30 days after an appeal is resolved)
    scope: Moderation evidence
    text: Moderation evidence 14 days (30 days after an appeal is resolved)
  - period: until the order is closed plus 30 days
    scope: Delivery address (merchant orders)
    text: 'Delivery address: until the order is closed plus 30 days.'
  rights:
  - right: access
    text: You may ask for access to, and correction of, data we hold about you.
  - right: correction
    text: You may ask for access to, and correction of, data we hold about you.
  - right: deletion
    text: We delete data on request where technically possible
  - right: objection
    text: You may object to processing based on legitimate interest
  - right: complaint to supervisory authority
    text: in the European Economic Area or the United Kingdom, complain to your supervisory authority.
  role:
    text: The Operator is the controller for platform data (agent identities, API keys, ledger, logs, receipts, contact form). For order data the merchant is the controller and APIbase is the processor
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or share data with advertisers or data brokers.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: APIbase
provenance_date: '2026-11-09'
provider_name: APIbase
provider_slug: apibase-pro
slug: apibase-pro-privacy-policy
source_date: '2026-11-09'
source_filename: apibase-pro-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apibase.pro/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: APIbase\naid: apibase-pro\nurl: https://apibase.pro/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: The Operator is the controller for platform data (agent identities, API keys, ledger, logs, receipts, contact\n    form). For order data the merchant is the controller and APIbase is the processor\ndata_categories:\n- category: identifying\n  text: 'Agent credentials: API keys (stored as SHA-256 hashes, never in plaintext), agent identifiers.'\n- category: financial\n  text: 'Payment data: USDC wallet addresses, transaction hashes, escrow records.'\n- category: contact\n  text: Messages sent\
  \ through the contact form are stored with the name, e-mail address, message text and IP address\n    you submit\n- category: device\n  text: IP addresses in application logs (only in Nginx access logs, retained 15 days).\n- category: behavioral\n  text: 'Request logs: Request IDs, tool IDs, timestamps, response status codes.'\npurposes:\n- purpose: Authenticate and authorize API requests\n  text: Authenticate and authorize API requests.\n- purpose: Process payments and maintain financial ledger\n  text: Process x402 and MPP micropayments, debit refund credit balances, and maintain the financial ledger.\n- purpose: Abuse prevention and rate limiting\n  text: Enforce rate limits and prevent abuse.\n- purpose: System health monitoring\n  text: Monitor system health and performance.\nretention:\n- scope: Ledger and public receipts\n  period: Indefinite\n  text: Indefinite (financial record, append-only; wallet addresses and hashes only)\n- scope: Nginx and Loki logs\n  period: Not more than\
  \ 15 days\n  text: Nginx and Loki logs Not more than 15 days\n- scope: Contact messages\n  period: 12 months\n  text: Messages sent through the contact form are stored with the name, e-mail address, message text and IP address\n    you submit, and kept for 12 months, then deleted.\n- scope: Moderation evidence\n  period: 14 days (30 days after an appeal is resolved)\n  text: Moderation evidence 14 days (30 days after an appeal is resolved)\n- scope: Delivery address (merchant orders)\n  period: until the order is closed plus 30 days\n  text: 'Delivery address: until the order is closed plus 30 days.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: For order data the merchant is the controller and APIbase is the processor ( DPA ).\ndeletion:\n  route: Request to support@apibase.pro\n  text: We delete data on request where technically possible; on-chain records and public receipts cannot be deleted\n    and contain no\
  \ name, e-mail or IP address.\nrights:\n- right: access\n  text: You may ask for access to, and correction of, data we hold about you.\n- right: correction\n  text: You may ask for access to, and correction of, data we hold about you.\n- right: deletion\n  text: We delete data on request where technically possible\n- right: objection\n  text: You may object to processing based on legitimate interest\n- right: complaint to supervisory authority\n  text: in the European Economic Area or the United Kingdom, complain to your supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or share data with advertisers or data brokers.\n"
source_yaml_url: https://artifacts.apis.io/apibase-pro/privacy/apibase-pro-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from APIbase's own page on 2026-11-09.
synthetic: false
tags:
- Gateways
- Artificial Intelligence
- MCP
- Payments
---
