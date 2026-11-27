---
api_specs:
- filename: hilt-so-account-api-openapi.yml
  format: yaml
  label: Hilt Account API
  slug: hilt-so-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-account-api-openapi.yml
- filename: hilt-so-agent-commerce-api-openapi.yml
  format: yaml
  label: Hilt Agent Commerce API
  slug: hilt-so-agent-commerce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-agent-commerce-api-openapi.yml
- filename: hilt-so-api-keys-api-openapi.yml
  format: yaml
  label: Hilt API Keys API
  slug: hilt-so-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-api-keys-api-openapi.yml
- filename: hilt-so-auth-api-openapi.yml
  format: yaml
  label: Hilt Auth API
  slug: hilt-so-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-auth-api-openapi.yml
- filename: hilt-so-billing-api-openapi.yml
  format: yaml
  label: Hilt Billing API
  slug: hilt-so-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-billing-api-openapi.yml
- filename: hilt-so-checkout-api-openapi.yml
  format: yaml
  label: Hilt Checkout API
  slug: hilt-so-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-checkout-api-openapi.yml
- filename: hilt-so-checkout-domains-api-openapi.yml
  format: yaml
  label: Hilt Checkout Domains API
  slug: hilt-so-checkout-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-checkout-domains-api-openapi.yml
- filename: hilt-so-hilt-pay-api-api-openapi.yml
  format: yaml
  label: Hilt Hilt Pay API
  slug: hilt-so-hilt-pay-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-hilt-pay-api-api-openapi.yml
- filename: hilt-so-hilt-payme-connector-api-openapi.yml
  format: yaml
  label: Hilt Hilt PayMe Connector API
  slug: hilt-so-hilt-payme-connector-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-hilt-payme-connector-api-openapi.yml
- filename: hilt-so-integrations-api-openapi.yml
  format: yaml
  label: Hilt Integrations API
  slug: hilt-so-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-integrations-api-openapi.yml
- filename: hilt-so-memberships-api-openapi.yml
  format: yaml
  label: Hilt Memberships API
  slug: hilt-so-memberships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-memberships-api-openapi.yml
- filename: hilt-so-pay-me-api-openapi.yml
  format: yaml
  label: Hilt Pay Me API
  slug: hilt-so-pay-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-pay-me-api-openapi.yml
- filename: hilt-so-products-api-openapi.yml
  format: yaml
  label: Hilt Products API
  slug: hilt-so-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-products-api-openapi.yml
- filename: hilt-so-receipt-api-openapi.yml
  format: yaml
  label: Hilt Receipt API
  slug: hilt-so-receipt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-receipt-api-openapi.yml
- filename: hilt-so-solana-api-openapi.yml
  format: yaml
  label: Hilt Solana API
  slug: hilt-so-solana-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-solana-api-openapi.yml
- filename: hilt-so-support-api-openapi.yml
  format: yaml
  label: Hilt Support API
  slug: hilt-so-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-support-api-openapi.yml
- filename: hilt-so-system-api-openapi.yml
  format: yaml
  label: Hilt System API
  slug: hilt-so-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-system-api-openapi.yml
- filename: hilt-so-testing-api-openapi.yml
  format: yaml
  label: Hilt Testing API
  slug: hilt-so-testing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-testing-api-openapi.yml
- filename: hilt-so-webhooks-api-openapi.yml
  format: yaml
  label: Hilt Webhooks API
  slug: hilt-so-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hilt-so/openapi/hilt-so-webhooks-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: account information such as name, email address, hashed password, and authentication metadata
  - category: financial
    text: payment and receipt data such as wallet addresses, transaction signatures, amounts, and timestamps
  - category: device
    text: technical data such as IP addresses, device metadata, request logs, and rate-limit signals
  - category: behavioral
    text: membership and access data such as identity labels, renewal status, delivery status, and support context
  deletion:
    route: email
    text: To exercise these rights, email privacy@hilt.so .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and secure the service
    text: 'We use personal data to: provide and secure the Hilt service'
  - purpose: verify payments and generate receipts
    text: verify on-chain payment flows and generate receipts
  - purpose: support and disputes
    text: respond to customer support requests and investigate delivery disputes
  - purpose: legal compliance and fraud prevention
    text: comply with legal obligations and prevent fraud or abuse
  retention:
  - period: null
    scope: account data
    text: We retain account data for as long as the account remains active and for a limited period after closure where needed for security, tax, bookkeeping, or dispute handling.
  - period: null
    scope: receipt, payment, and support records
    text: Receipt, payment, and support records may be retained for longer where necessary for auditability, fraud prevention, or legal obligations.
  rights:
  - right: access, correction, deletion, restriction, objection, export
    text: you may have rights to access, correct, delete, restrict, object to, or export certain personal data
  role:
    text: Hilt is currently operated in the United Kingdom by Paul Wild as a sole trader business under the trading name Hilt and acts as the controller of personal data processed through hilt.so
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Hilt
provenance_date: '2026-11-09'
provider_name: Hilt
provider_slug: hilt-so
slug: hilt-so-privacy-policy
source_date: '2026-11-09'
source_filename: hilt-so-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.hilt.so/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Hilt\naid: hilt-so\nurl: https://www.hilt.so/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Hilt is currently operated in the United Kingdom by Paul Wild as a sole trader business under the trading\n    name Hilt and acts as the controller of personal data processed through hilt.so\ndata_categories:\n- category: identifying\n  text: account information such as name, email address, hashed password, and authentication metadata\n- category: financial\n  text: payment and receipt data such as wallet addresses, transaction signatures, amounts, and timestamps\n- category: device\n\
  \  text: technical data such as IP addresses, device metadata, request logs, and rate-limit signals\n- category: behavioral\n  text: membership and access data such as identity labels, renewal status, delivery status, and support context\npurposes:\n- purpose: provide and secure the service\n  text: 'We use personal data to: provide and secure the Hilt service'\n- purpose: verify payments and generate receipts\n  text: verify on-chain payment flows and generate receipts\n- purpose: support and disputes\n  text: respond to customer support requests and investigate delivery disputes\n- purpose: legal compliance and fraud prevention\n  text: comply with legal obligations and prevent fraud or abuse\nretention:\n- scope: account data\n  period: null\n  text: We retain account data for as long as the account remains active and for a limited period after closure\n    where needed for security, tax, bookkeeping, or dispute handling.\n- scope: receipt, payment, and support records\n  period: null\n\
  \  text: Receipt, payment, and support records may be retained for longer where necessary for auditability, fraud\n    prevention, or legal obligations.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email\n  text: To exercise these rights, email privacy@hilt.so .\nrights:\n- right: access, correction, deletion, restriction, objection, export\n  text: you may have rights to access, correct, delete, restrict, object to, or export certain personal data\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/hilt-so/privacy/hilt-so-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from Hilt's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Solana
- Stablecoins
- USDC
- Crypto Payments
- Agentic Payments
- x402
- Checkout
- Subscription
- Webhook
- MCP
- Entitlements
- Micropayments
- Developer Tools
- Fintech
- A2A
---
