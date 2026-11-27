---
api_specs:
- filename: bizverify-account-api-openapi.yml
  format: yaml
  label: BizVerify Account API
  slug: bizverify-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-account-api-openapi.yml
- filename: bizverify-auth-api-openapi.yml
  format: yaml
  label: BizVerify Auth API
  slug: bizverify-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-auth-api-openapi.yml
- filename: bizverify-billing-api-openapi.yml
  format: yaml
  label: BizVerify Billing API
  slug: bizverify-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-billing-api-openapi.yml
- filename: bizverify-entities-api-openapi.yml
  format: yaml
  label: BizVerify Entities API
  slug: bizverify-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-entities-api-openapi.yml
- filename: bizverify-meta-api-openapi.yml
  format: yaml
  label: BizVerify Meta API
  slug: bizverify-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-meta-api-openapi.yml
- filename: bizverify-public-api-openapi.yml
  format: yaml
  label: BizVerify Public API
  slug: bizverify-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-public-api-openapi.yml
- filename: bizverify-search-api-openapi.yml
  format: yaml
  label: BizVerify Search API
  slug: bizverify-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-search-api-openapi.yml
- filename: bizverify-tools-api-openapi.yml
  format: yaml
  label: BizVerify Tools API
  slug: bizverify-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-tools-api-openapi.yml
- filename: bizverify-verification-api-openapi.yml
  format: yaml
  label: BizVerify Verification API
  slug: bizverify-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizverify/openapi/bizverify-verification-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data Email address, hashed password
  - category: behavioral
    text: Usage data API call logs, endpoints accessed, timestamps
  - category: device
    text: Technical data IP addresses, user agent strings
  - category: financial
    text: Billing data Credit purchase history, Stripe customer ID
  deletion:
    route: Email to legal@bizverify.co to exercise erasure right
    text: Erasure — Request deletion of your personal data (“right to be forgotten”).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authentication and service delivery
    text: Account data Email address, hashed password Authentication, service delivery
  - purpose: Billing and service improvement
    text: Usage data API call logs, endpoints accessed, timestamps Billing, service improvement
  - purpose: Rate limiting, abuse prevention, security
    text: Technical data IP addresses, user agent strings Rate limiting, abuse prevention, security
  - purpose: Payment processing and invoicing
    text: Billing data Credit purchase history, Stripe customer ID Payment processing, invoicing
  residency:
  - region: United States
    text: Fly.io Application hosting and infrastructure United States
  retention:
  - period: 30 days
    scope: Account data
    text: Deleted within 30 days of account deletion.
  - period: 90 days
    scope: API usage logs
    text: API usage logs — Retained for 90 days, then automatically purged.
  - period: 90 days
    scope: IP addresses
    text: IP addresses — Retained for 90 days for rate limiting and security purposes.
  - period: 7 years
    scope: Billing records
    text: Billing records — Retained as required by applicable tax and accounting laws (typically 7 years).
  rights:
  - right: Access
    text: Access — Request a copy of the personal data we hold about you.
  - right: Rectification
    text: Rectification — Request correction of inaccurate or incomplete data.
  - right: Erasure
    text: Erasure — Request deletion of your personal data (“right to be forgotten”).
  - right: Restriction
    text: Restriction — Request that we limit processing of your data in certain circumstances.
  - right: Data portability
    text: Data portability — Receive your data in a structured, machine-readable format.
  - right: Objection
    text: Objection — Object to processing based on legitimate interest.
  role:
    text: BizVerify (“we”, “us”, “our”) is the data controller responsible for your personal data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: For transfers of personal data to the United States, we rely on the EU-U.S. Data Privacy Framework or Standard Contractual Clauses as appropriate.
  - mechanism: SCC
    text: For transfers of personal data to the United States, we rely on the EU-U.S. Data Privacy Framework or Standard Contractual Clauses as appropriate.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BizVerify
provenance_date: '2026-11-09'
provider_name: BizVerify
provider_slug: bizverify
slug: bizverify-privacy-policy
source_date: '2026-11-09'
source_filename: bizverify-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bizverify.co/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BizVerify\naid: bizverify\nurl: https://bizverify.co/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: BizVerify (“we”, “us”, “our”) is the data controller responsible for your personal data.\ndata_categories:\n- category: identifying\n  text: Account data Email address, hashed password\n- category: behavioral\n  text: Usage data API call logs, endpoints accessed, timestamps\n- category: device\n  text: Technical data IP addresses, user agent strings\n- category: financial\n  text: Billing data Credit purchase history, Stripe customer ID\npurposes:\n- purpose: Authentication and service\
  \ delivery\n  text: Account data Email address, hashed password Authentication, service delivery\n- purpose: Billing and service improvement\n  text: Usage data API call logs, endpoints accessed, timestamps Billing, service improvement\n- purpose: Rate limiting, abuse prevention, security\n  text: Technical data IP addresses, user agent strings Rate limiting, abuse prevention, security\n- purpose: Payment processing and invoicing\n  text: Billing data Credit purchase history, Stripe customer ID Payment processing, invoicing\nretention:\n- scope: Account data\n  period: 30 days\n  text: Deleted within 30 days of account deletion.\n- scope: API usage logs\n  period: 90 days\n  text: API usage logs — Retained for 90 days, then automatically purged.\n- scope: IP addresses\n  period: 90 days\n  text: IP addresses — Retained for 90 days for rate limiting and security purposes.\n- scope: Billing records\n  period: 7 years\n  text: Billing records — Retained as required by applicable tax and accounting\
  \ laws (typically 7 years).\nresidency:\n- region: United States\n  text: Fly.io Application hosting and infrastructure United States\ntransfers:\n- mechanism: DPF\n  text: For transfers of personal data to the United States, we rely on the EU-U.S. Data Privacy Framework or Standard\n    Contractual Clauses as appropriate.\n- mechanism: SCC\n  text: For transfers of personal data to the United States, we rely on the EU-U.S. Data Privacy Framework or Standard\n    Contractual Clauses as appropriate.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email to legal@bizverify.co to exercise erasure right\n  text: Erasure — Request deletion of your personal data (“right to be forgotten”).\nrights:\n- right: Access\n  text: Access — Request a copy of the personal data we hold about you.\n- right: Rectification\n  text: Rectification — Request correction of inaccurate or incomplete data.\n- right: Erasure\n  text: Erasure — Request\
  \ deletion of your personal data (“right to be forgotten”).\n- right: Restriction\n  text: Restriction — Request that we limit processing of your data in certain circumstances.\n- right: Data portability\n  text: Data portability — Receive your data in a structured, machine-readable format.\n- right: Objection\n  text: Objection — Object to processing based on legitimate interest.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/bizverify/privacy/bizverify-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from BizVerify's own page on 2026-11-09.
synthetic: false
tags:
- Business Verification
- KYB
- Entity Verification
- Compliance
- MCP
- Agent-Native
- Developer Tools
---
