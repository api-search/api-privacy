---
api_specs:
- filename: infer-by-flow7-catalog-api-openapi.yml
  format: yaml
  label: Infer by Flow7 Catalog API
  slug: infer-by-flow7-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infer-by-flow7/openapi/infer-by-flow7-catalog-api-openapi.yml
- filename: infer-by-flow7-inference-api-openapi.yml
  format: yaml
  label: Infer by Flow7 Inference API
  slug: infer-by-flow7-inference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infer-by-flow7/openapi/infer-by-flow7-inference-api-openapi.yml
- filename: infer-by-flow7-status-api-openapi.yml
  format: yaml
  label: Infer by Flow7 Status API
  slug: infer-by-flow7-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infer-by-flow7/openapi/infer-by-flow7-status-api-openapi.yml
- filename: infer-by-flow7-generation-api-openapi.yml
  format: yaml
  label: Infer by Flow7 Generation API
  slug: infer-by-flow7-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infer-by-flow7/openapi/infer-by-flow7-generation-api-openapi.yml
- filename: infer-by-flow7-messages-api-openapi.yml
  format: yaml
  label: Infer by Flow7 Messages API
  slug: infer-by-flow7-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infer-by-flow7/openapi/infer-by-flow7-messages-api-openapi.yml
- filename: infer-by-flow7-usage-api-openapi.yml
  format: yaml
  label: Infer by Flow7 Usage API
  slug: infer-by-flow7-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infer-by-flow7/openapi/infer-by-flow7-usage-api-openapi.yml
- filename: infer-by-flow7-chat-completions-api-openapi.yml
  format: yaml
  label: Infer by Flow7 Chat Completions API
  slug: infer-by-flow7-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infer-by-flow7/openapi/infer-by-flow7-chat-completions-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and workspace data email address; password hash; account type, workspace or organization name, roles, memberships, and invitations
  - category: device
    text: IP address, approximate location derived from IP, user agent, browser/device information, and referring page where collected
  - category: financial
    text: Stripe customer, Checkout Session, Payment Intent, charge, and refund identifiers
  - category: communication
    text: support messages, case references, and response records
  - category: behavioral
    text: Infer does not intend to store full card numbers or card security codes
  deletion:
    route: privacy request workflow or email
    text: Submit a request through the privacy-request workflow or email privacy@flow7.org
  dpa:
    available: true
    text: under the Data Processing Addendum
    url: null
  purposes:
  - purpose: account and API service
    text: Create accounts, provide API access, route inference, meter usage, maintain wallets, and provide support
  - purpose: security and fraud prevention
    text: Authenticate users, prevent fraud and abuse, secure systems, enforce spend/rate limits, and investigate incidents
  - purpose: ads measurement via X pixel
    text: Measure the results of Infer’s ads on X with the X pixel on Infer’s public pages
  residency:
  - region: United States and other countries
    text: Infer and its service providers may process personal data in the United States and other countries that may have different data-protection laws
  retention:
  - period: up to approximately 24 hours
    scope: Generated response body
    text: a generated response body may be temporarily retained for idempotent replay for up to approximately 24 hours
  - period: generally up to seven years
    scope: Request metadata and usage receipts
    text: 'Request metadata and usage receipts: generally up to seven years when connected to billing, supplier reconciliation, fraud, accounting, or legal evidence'
  - period: null
    scope: Account and workspace data
    text: ordinarily deleted or deidentified within 30 days after those needs end
  - period: 12 to 24 months
    scope: Security and audit logs
    text: 'Security and audit logs: generally 12 to 24 months'
  rights:
  - right: access
    text: access personal data
  - right: delete
    text: delete data
  - right: withdraw consent
    text: withdraw consent
  - right: appeal
    text: appeal a privacy decision
  role:
    text: Infer generally acts as processor or service provider under the Data Processing Addendum
    value: both
  sale_or_sharing:
    stance: conditional
    text: Infer treats a Global Privacy Control signal as an opt-out of that sharing
  subprocessors:
    text: The Subprocessor Notice describes relevant provider categories, names payment, identity, and infrastructure providers
    url: null
  transfers:
  - mechanism: SCC
    text: the European Commission Standard Contractual Clauses
  - mechanism: adequacy
    text: an adequacy decision
  - mechanism: other
    text: the UK International Data Transfer Addendum
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Infer by Flow7
provenance_date: '2026-11-09'
provider_name: Infer by Flow7
provider_slug: infer-by-flow7
slug: infer-by-flow7-privacy-policy
source_date: '2026-11-09'
source_filename: infer-by-flow7-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://infer.flow7.org/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Infer by Flow7\naid: infer-by-flow7\nurl: https://infer.flow7.org/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Infer generally acts as processor or service provider under the Data Processing Addendum\ndata_categories:\n- category: identifying\n  text: Account and workspace data email address; password hash; account type, workspace or organization name, roles,\n    memberships, and invitations\n- category: device\n  text: IP address, approximate location derived from IP, user agent, browser/device information, and referring\n    page where collected\n- category: financial\n  text: Stripe\
  \ customer, Checkout Session, Payment Intent, charge, and refund identifiers\n- category: communication\n  text: support messages, case references, and response records\n- category: behavioral\n  text: Infer does not intend to store full card numbers or card security codes\npurposes:\n- purpose: account and API service\n  text: Create accounts, provide API access, route inference, meter usage, maintain wallets, and provide support\n- purpose: security and fraud prevention\n  text: Authenticate users, prevent fraud and abuse, secure systems, enforce spend/rate limits, and investigate\n    incidents\n- purpose: ads measurement via X pixel\n  text: Measure the results of Infer’s ads on X with the X pixel on Infer’s public pages\nretention:\n- scope: Generated response body\n  period: up to approximately 24 hours\n  text: a generated response body may be temporarily retained for idempotent replay for up to approximately 24 hours\n- scope: Request metadata and usage receipts\n  period: generally\
  \ up to seven years\n  text: 'Request metadata and usage receipts: generally up to seven years when connected to billing, supplier reconciliation,\n    fraud, accounting, or legal evidence'\n- scope: Account and workspace data\n  period: null\n  text: ordinarily deleted or deidentified within 30 days after those needs end\n- scope: Security and audit logs\n  period: 12 to 24 months\n  text: 'Security and audit logs: generally 12 to 24 months'\nresidency:\n- region: United States and other countries\n  text: Infer and its service providers may process personal data in the United States and other countries that\n    may have different data-protection laws\ntransfers:\n- mechanism: SCC\n  text: the European Commission Standard Contractual Clauses\n- mechanism: adequacy\n  text: an adequacy decision\n- mechanism: other\n  text: the UK International Data Transfer Addendum\nsubprocessors:\n  url: null\n  text: The Subprocessor Notice describes relevant provider categories, names payment, identity,\
  \ and infrastructure\n    providers\ndpa:\n  available: true\n  url: null\n  text: under the Data Processing Addendum\ndeletion:\n  route: privacy request workflow or email\n  text: Submit a request through the privacy-request workflow or email privacy@flow7.org\nrights:\n- right: access\n  text: access personal data\n- right: delete\n  text: delete data\n- right: withdraw consent\n  text: withdraw consent\n- right: appeal\n  text: appeal a privacy decision\nsale_or_sharing:\n  stance: conditional\n  text: Infer treats a Global Privacy Control signal as an opt-out of that sharing\n"
source_yaml_url: https://artifacts.apis.io/infer-by-flow7/privacy/infer-by-flow7-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Infer by Flow7's own page on 2026-11-09.
synthetic: false
tags:
- AI/ML inference
- LLM API gateway
- Responses-compatible API
- Coding-agent tooling
- Developer Tools
- Usage-Based Billing
- Prepaid billing
- Agent-Native
- Agent Skills
- Model Routing
---
