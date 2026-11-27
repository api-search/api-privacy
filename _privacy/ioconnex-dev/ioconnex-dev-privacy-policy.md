---
api_specs:
- filename: ioconnex-dev-affiliate-api-openapi.yml
  format: yaml
  label: ioconnex-dev Affiliate API
  slug: ioconnex-dev-affiliate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ioconnex-dev/openapi/ioconnex-dev-affiliate-api-openapi.yml
- filename: ioconnex-dev-billing-api-openapi.yml
  format: yaml
  label: ioconnex-dev Billing API
  slug: ioconnex-dev-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ioconnex-dev/openapi/ioconnex-dev-billing-api-openapi.yml
- filename: ioconnex-dev-convert-api-openapi.yml
  format: yaml
  label: ioconnex-dev Convert API
  slug: ioconnex-dev-convert-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ioconnex-dev/openapi/ioconnex-dev-convert-api-openapi.yml
- filename: ioconnex-dev-fetch-api-openapi.yml
  format: yaml
  label: ioconnex-dev Fetch API
  slug: ioconnex-dev-fetch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ioconnex-dev/openapi/ioconnex-dev-fetch-api-openapi.yml
- filename: ioconnex-dev-health-api-openapi.yml
  format: yaml
  label: ioconnex-dev Health API
  slug: ioconnex-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ioconnex-dev/openapi/ioconnex-dev-health-api-openapi.yml
- filename: ioconnex-dev-paid-api-openapi.yml
  format: yaml
  label: ioconnex-dev Paid API
  slug: ioconnex-dev-paid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ioconnex-dev/openapi/ioconnex-dev-paid-api-openapi.yml
- filename: ioconnex-dev-price-api-openapi.yml
  format: yaml
  label: ioconnex-dev Price API
  slug: ioconnex-dev-price-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ioconnex-dev/openapi/ioconnex-dev-price-api-openapi.yml
- filename: ioconnex-dev-search-api-openapi.yml
  format: yaml
  label: ioconnex-dev Search API
  slug: ioconnex-dev-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ioconnex-dev/openapi/ioconnex-dev-search-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: We store your Stripe customer identifier, the email address from your Checkout session, and the SHA-256 hash of your subscriber key.
  - category: financial
    text: payer wallet address, payment amount, and authorization signatures.
  - category: device
    text: IP address, request path, user-agent, timestamp, and usage counters
  - category: communication
    text: support correspondence and any information you send us when you contact us.
  deletion:
    route: email hello@ioconnex.dev
    text: To exercise these rights, email hello@ioconnex.dev.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate, meter, bill and support services
    text: To operate, meter, bill for, and support the Services;
  - purpose: abuse, fraud and attack prevention
    text: To prevent abuse, fraud, attacks, and overload, and to enforce our Terms;
  - purpose: legal and tax compliance
    text: To comply with legal, tax, and accounting obligations.
  residency:
  - region: United States
    text: The Services are operated in the United States.
  retention:
  - period: 12 months
    scope: operational and security logs
    text: 'Operational and security logs: retained up to 12 months, then deleted or anonymized'
  - period: 7 years
    scope: payment and tax records
    text: 'Payment and tax records: retained as required by law, generally 7 years.'
  - period: 5 minutes
    scope: x402 payment signatures in server memory
    text: temporarily hold payment signatures in server memory (up to 5 minutes)
  rights:
  - right: access or portable copy
    text: access or receive a portable copy of it
  - right: correct inaccuracies
    text: correct inaccuracies
  - right: request deletion
    text: request deletion
  - right: opt out of sale or sharing
    text: opt out of any sale or sharing of personal information
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information, and we do not share it for cross-context behavioral advertising
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ioconnex-dev
provenance_date: '2026-11-09'
provider_name: ioconnex-dev
provider_slug: ioconnex-dev
slug: ioconnex-dev-privacy-policy
source_date: '2026-11-09'
source_filename: ioconnex-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://search.ioconnex.dev/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ioconnex-dev\naid: ioconnex-dev\nurl: https://search.ioconnex.dev/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We store your Stripe customer identifier, the email address from your Checkout session, and the SHA-256\n    hash of your subscriber key.\n- category: financial\n  text: payer wallet address, payment amount, and authorization signatures.\n- category: device\n  text: IP address, request path, user-agent, timestamp, and usage counters\n- category: communication\n  text: support correspondence and any information\
  \ you send us when you contact us.\npurposes:\n- purpose: operate, meter, bill and support services\n  text: To operate, meter, bill for, and support the Services;\n- purpose: abuse, fraud and attack prevention\n  text: To prevent abuse, fraud, attacks, and overload, and to enforce our Terms;\n- purpose: legal and tax compliance\n  text: To comply with legal, tax, and accounting obligations.\nretention:\n- scope: operational and security logs\n  period: 12 months\n  text: 'Operational and security logs: retained up to 12 months, then deleted or anonymized'\n- scope: payment and tax records\n  period: 7 years\n  text: 'Payment and tax records: retained as required by law, generally 7 years.'\n- scope: x402 payment signatures in server memory\n  period: 5 minutes\n  text: temporarily hold payment signatures in server memory (up to 5 minutes)\nresidency:\n- region: United States\n  text: The Services are operated in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\n\
  dpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@ioconnex.dev\n  text: To exercise these rights, email hello@ioconnex.dev.\nrights:\n- right: access or portable copy\n  text: access or receive a portable copy of it\n- right: correct inaccuracies\n  text: correct inaccuracies\n- right: request deletion\n  text: request deletion\n- right: opt out of sale or sharing\n  text: opt out of any sale or sharing of personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information, and we do not share it for cross-context behavioral advertising\n"
source_yaml_url: https://artifacts.apis.io/ioconnex-dev/privacy/ioconnex-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from ioconnex-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- MCP
- Search
- Document Conversion
- Price-Tracking
---
