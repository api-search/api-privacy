---
api_specs:
- filename: agentpay-so-acp-api-openapi.yml
  format: yaml
  label: AgentPay Labs ACP API
  slug: agentpay-so-acp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentpay-so/openapi/agentpay-so-acp-api-openapi.yml
- filename: agentpay-so-agentrank-api-openapi.yml
  format: yaml
  label: AgentPay Labs Agent Rank API
  slug: agentpay-so-agentrank-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentpay-so/openapi/agentpay-so-agentrank-api-openapi.yml
- filename: agentpay-so-agents-api-openapi.yml
  format: yaml
  label: AgentPay Labs Agents API
  slug: agentpay-so-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentpay-so/openapi/agentpay-so-agents-api-openapi.yml
- filename: agentpay-so-ap2-api-openapi.yml
  format: yaml
  label: AgentPay Labs AP2 API
  slug: agentpay-so-ap2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentpay-so/openapi/agentpay-so-ap2-api-openapi.yml
- filename: agentpay-so-commerce-api-openapi.yml
  format: yaml
  label: AgentPay Labs Commerce API
  slug: agentpay-so-commerce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentpay-so/openapi/agentpay-so-commerce-api-openapi.yml
- filename: agentpay-so-escrow-api-openapi.yml
  format: yaml
  label: AgentPay Labs Escrow API
  slug: agentpay-so-escrow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentpay-so/openapi/agentpay-so-escrow-api-openapi.yml
- filename: agentpay-so-health-api-openapi.yml
  format: yaml
  label: AgentPay Labs Health API
  slug: agentpay-so-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentpay-so/openapi/agentpay-so-health-api-openapi.yml
- filename: agentpay-so-marketplace-api-openapi.yml
  format: yaml
  label: AgentPay Labs Marketplace API
  slug: agentpay-so-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentpay-so/openapi/agentpay-so-marketplace-api-openapi.yml
- filename: agentpay-so-merchants-api-openapi.yml
  format: yaml
  label: AgentPay Labs Merchants API
  slug: agentpay-so-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentpay-so/openapi/agentpay-so-merchants-api-openapi.yml
- filename: agentpay-so-payments-api-openapi.yml
  format: yaml
  label: AgentPay Labs Payments API
  slug: agentpay-so-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentpay-so/openapi/agentpay-so-payments-api-openapi.yml
- filename: agentpay-so-webhooks-api-openapi.yml
  format: yaml
  label: AgentPay Labs Webhooks API
  slug: agentpay-so-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentpay-so/openapi/agentpay-so-webhooks-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: the merchant name and email you provide
  - category: financial
    text: optional funding details needed to complete a payment you approve
  - category: device
    text: a hashed API key
  - category: behavioral
    text: spend-limit and mandate records, receipts, and operational logs used for security and reliability
  deletion:
    route: request using the address below
    text: You can request deletion using the address below; regulatory-hold data may be retained where the law requires it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account and key creation
    text: We use this information to create and authenticate your merchant key, apply the spend limit you set
  - purpose: payment settlement
    text: settle card or crypto payments you authorize
  - purpose: service email
    text: send service email such as a one-time API key
  - purpose: security and diagnostics
    text: maintain security, diagnose failures, and comply with applicable law
  retention:
  - period: null
    scope: merchant account data and payment audit records
    text: We retain merchant account data and payment audit records for as long as the account is active and as required for receipts, chargebacks, and legal obligations.
  rights:
  - right: access
    text: you can request access, correction, or deletion of information associated with the service using the address below
  - right: correction
    text: you can request access, correction, or deletion of information associated with the service using the address below
  - right: key rotation or recovery
    text: You can rotate or recover an API key
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or use it for advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentPay Labs
provenance_date: '2026-11-09'
provider_name: AgentPay Labs
provider_slug: agentpay-so
slug: agentpay-so-privacy-policy
source_date: '2026-11-09'
source_filename: agentpay-so-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentpay.so/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentPay Labs\naid: agentpay-so\nurl: https://agentpay.so/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: the merchant name and email you provide\n- category: financial\n  text: optional funding details needed to complete a payment you approve\n- category: device\n  text: a hashed API key\n- category: behavioral\n  text: spend-limit and mandate records, receipts, and operational logs used for security and reliability\npurposes:\n- purpose: account and key creation\n  text: We use this information to create and authenticate your\
  \ merchant key, apply the spend limit you set\n- purpose: payment settlement\n  text: settle card or crypto payments you authorize\n- purpose: service email\n  text: send service email such as a one-time API key\n- purpose: security and diagnostics\n  text: maintain security, diagnose failures, and comply with applicable law\nretention:\n- scope: merchant account data and payment audit records\n  period: null\n  text: We retain merchant account data and payment audit records for as long as the account is active and as required\n    for receipts, chargebacks, and legal obligations.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request using the address below\n  text: You can request deletion using the address below; regulatory-hold data may be retained where the law requires\n    it.\nrights:\n- right: access\n  text: you can request access, correction, or deletion of information associated\
  \ with the service using the address\n    below\n- right: correction\n  text: you can request access, correction, or deletion of information associated with the service using the address\n    below\n- right: key rotation or recovery\n  text: You can rotate or recover an API key\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/agentpay-so/privacy/agentpay-so-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from AgentPay Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Research
- Robotics
- Automation
- Platform
---
