---
api_specs:
- filename: taskhawktech-com-opaque-event-interface-openapi.json
  format: json
  label: TaskHawk Opaque Event Interface
  slug: taskhawk-opaque-event-interface
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taskhawktech-com/openapi/taskhawktech-com-opaque-event-interface-openapi.json
- filename: taskhawktech-com-billing-api-openapi.yml
  format: yaml
  label: TaskHawk Systems Billing API
  slug: taskhawktech-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taskhawktech-com/openapi/taskhawktech-com-billing-api-openapi.yml
- filename: taskhawktech-com-events-api-openapi.yml
  format: yaml
  label: TaskHawk Systems Events API
  slug: taskhawktech-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taskhawktech-com/openapi/taskhawktech-com-events-api-openapi.yml
- filename: taskhawktech-com-governance-api-openapi.yml
  format: yaml
  label: TaskHawk Systems Governance API
  slug: taskhawktech-com-governance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taskhawktech-com/openapi/taskhawktech-com-governance-api-openapi.yml
- filename: taskhawktech-com-media-api-openapi.yml
  format: yaml
  label: TaskHawk Systems Media API
  slug: taskhawktech-com-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taskhawktech-com/openapi/taskhawktech-com-media-api-openapi.yml
- filename: taskhawktech-com-shield-api-openapi.yml
  format: yaml
  label: TaskHawk Systems Shield API
  slug: taskhawktech-com-shield-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taskhawktech-com/openapi/taskhawktech-com-shield-api-openapi.yml
- filename: taskhawktech-com-signup-api-openapi.yml
  format: yaml
  label: TaskHawk Systems Signup API
  slug: taskhawktech-com-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/taskhawktech-com/openapi/taskhawktech-com-signup-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: name, email address, and organization name when you submit a contact form, sign up for an API key, or communicate with us.
  - category: identifying
    text: API keys, operator identifiers, and authentication tokens issued to your account.
  - category: financial
    text: billing details processed by our payment processors.
  - category: device
    text: IP address, browser type, and operating system collected automatically through standard web server logs when you access the website or API.
  - category: behavioral
    text: API call metadata (endpoint, timestamp, response code, latency) associated with your API key.
  deletion:
    route: Verified request to legal@taskhawktech.com
    text: Deletion may be subject to a legal hold or a documented backup cycle; we explain an applicable exception when responding to a verified request.
  dpa:
    available: null
    text: Data is processed subject to the applicable data protection agreements.
    url: null
  purposes:
  - purpose: Provide and operate the gateway and APIs
    text: To provide, operate, and maintain the Kevros Runtime Enforcement Gateway and associated APIs.
  - purpose: Process enforcement attestation requests
    text: To process enforcement attestation requests and enforce policies on your behalf.
  - purpose: Process payments
    text: To process payments and manage subscriptions through secure payment processors.
  - purpose: Communication
    text: To communicate with you about your account, service updates, or security notices.
  - purpose: Legal compliance
    text: To comply with legal obligations.
  residency:
  - region: United States
    text: Public website and business-contact processing may occur in the United States.
  retention:
  - period: null
    scope: Personal information without a specific period
    text: Where no specific period is stated, we retain personal information only as reasonably needed for the disclosed purpose, contractual obligations, security, dispute resolution, and required records.
  - period: null
    scope: Financial records
    text: Financial records follow applicable tax and accounting requirements.
  - period: null
    scope: Customer deployments
    text: A customer-controlled deployment follows the customer's configured retention and deletion policy.
  rights:
  - right: Access
    text: Access the personal information we hold about you.
  - right: Correction
    text: Request correction of inaccurate information.
  - right: Deletion
    text: Request deletion of your personal information.
  - right: Objection or restriction
    text: Object to or restrict certain processing activities.
  - right: Portability
    text: Data portability (receive your data in a structured format).
  - right: Opt out of sale
    text: Opt out of the sale of personal information (we do not sell personal information).
  role:
    text: TaskHawk acts as controller for its own business-contact, account, billing, and website purposes, and as processor when acting on a customer's documented instructions.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Where law restricts an international transfer, an appropriate lawful transfer basis and required safeguards must be in place before that processing.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TaskHawk Systems
provenance_date: '2026-11-10'
provider_name: TaskHawk Systems
provider_slug: taskhawktech-com
slug: taskhawktech-com-privacy-policy
source_date: '2026-11-10'
source_filename: taskhawktech-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://taskhawktech.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TaskHawk Systems\naid: taskhawktech-com\nurl: https://taskhawktech.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: TaskHawk acts as controller for its own business-contact, account, billing, and website purposes, and as\n    processor when acting on a customer's documented instructions.\ndata_categories:\n- category: contact\n  text: name, email address, and organization name when you submit a contact form, sign up for an API key, or communicate\n    with us.\n- category: identifying\n  text: API keys, operator identifiers, and authentication tokens issued to your account.\n- category:\
  \ financial\n  text: billing details processed by our payment processors.\n- category: device\n  text: IP address, browser type, and operating system collected automatically through standard web server logs\n    when you access the website or API.\n- category: behavioral\n  text: API call metadata (endpoint, timestamp, response code, latency) associated with your API key.\npurposes:\n- purpose: Provide and operate the gateway and APIs\n  text: To provide, operate, and maintain the Kevros Runtime Enforcement Gateway and associated APIs.\n- purpose: Process enforcement attestation requests\n  text: To process enforcement attestation requests and enforce policies on your behalf.\n- purpose: Process payments\n  text: To process payments and manage subscriptions through secure payment processors.\n- purpose: Communication\n  text: To communicate with you about your account, service updates, or security notices.\n- purpose: Legal compliance\n  text: To comply with legal obligations.\nretention:\n\
  - scope: Personal information without a specific period\n  period: null\n  text: Where no specific period is stated, we retain personal information only as reasonably needed for the disclosed\n    purpose, contractual obligations, security, dispute resolution, and required records.\n- scope: Financial records\n  period: null\n  text: Financial records follow applicable tax and accounting requirements.\n- scope: Customer deployments\n  period: null\n  text: A customer-controlled deployment follows the customer's configured retention and deletion policy.\nresidency:\n- region: United States\n  text: Public website and business-contact processing may occur in the United States.\ntransfers:\n- mechanism: other\n  text: Where law restricts an international transfer, an appropriate lawful transfer basis and required safeguards\n    must be in place before that processing.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Data is processed subject to the\
  \ applicable data protection agreements.\ndeletion:\n  route: Verified request to legal@taskhawktech.com\n  text: Deletion may be subject to a legal hold or a documented backup cycle; we explain an applicable exception\n    when responding to a verified request.\nrights:\n- right: Access\n  text: Access the personal information we hold about you.\n- right: Correction\n  text: Request correction of inaccurate information.\n- right: Deletion\n  text: Request deletion of your personal information.\n- right: Objection or restriction\n  text: Object to or restrict certain processing activities.\n- right: Portability\n  text: Data portability (receive your data in a structured format).\n- right: Opt out of sale\n  text: Opt out of the sale of personal information (we do not sell personal information).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/taskhawktech-com/privacy/taskhawktech-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from TaskHawk Systems's own page on 2026-11-10.
synthetic: false
tags:
- AI Governance
- Agent Security
- Runtime Enforcement
- Policy Enforcement
- Provenance
- Compliance
- Prompt Injection Detection
- Media Attestation
- Post-Quantum Cryptography
- Formal Verification
- x402
- L402
- Machine Payments
- MCP
- A2A
- Agent-Native
- Government
- Defense
---
