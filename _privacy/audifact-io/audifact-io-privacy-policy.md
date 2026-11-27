---
api_specs:
- filename: audifact-io-account-api-openapi.yml
  format: yaml
  label: Audifact Account API
  slug: audifact-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-account-api-openapi.yml
- filename: audifact-io-admin-api-openapi.yml
  format: yaml
  label: Audifact Admin API
  slug: audifact-io-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-admin-api-openapi.yml
- filename: audifact-io-agents-api-openapi.yml
  format: yaml
  label: Audifact Agents API
  slug: audifact-io-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-agents-api-openapi.yml
- filename: audifact-io-auth-api-openapi.yml
  format: yaml
  label: Audifact Auth API
  slug: audifact-io-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-auth-api-openapi.yml
- filename: audifact-io-events-api-openapi.yml
  format: yaml
  label: Audifact Events API
  slug: audifact-io-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-events-api-openapi.yml
- filename: audifact-io-explorer-api-openapi.yml
  format: yaml
  label: Audifact Explorer API
  slug: audifact-io-explorer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-explorer-api-openapi.yml
- filename: audifact-io-internal-api-openapi.yml
  format: yaml
  label: Audifact Internal API
  slug: audifact-io-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-internal-api-openapi.yml
- filename: audifact-io-ledger-api-openapi.yml
  format: yaml
  label: Audifact Ledger API
  slug: audifact-io-ledger-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-ledger-api-openapi.yml
- filename: audifact-io-mcp-api-openapi.yml
  format: yaml
  label: Audifact MCP API
  slug: audifact-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-mcp-api-openapi.yml
- filename: audifact-io-org-api-openapi.yml
  format: yaml
  label: Audifact Org API
  slug: audifact-io-org-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-org-api-openapi.yml
- filename: audifact-io-verification-api-openapi.yml
  format: yaml
  label: Audifact Verification API
  slug: audifact-io-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-verification-api-openapi.yml
- filename: audifact-io-web-api-openapi.yml
  format: yaml
  label: Audifact Web API
  slug: audifact-io-web-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-web-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account data: email address, name, optional organization name, password (stored in hashed form when set)'
  - category: identifying
    text: 'OAuth sign-in: when you use GitHub or Google, we receive the provider account identifiers and profile fields'
  - category: financial
    text: 'Payment data: billing is handled by Stripe. We receive customer IDs, subscription status, and payment metadata - not your full card number.'
  - category: location
    text: approximate location derived from IP
  - category: device
    text: 'Technical and security data: IP address (and hashed forms used for rate limiting), browser type, request logs'
  - category: behavioral
    text: 'Advertising and measurement data: when you visit our website or landing pages, Google may receive device and usage signals via the Google tag'
  - category: communication
    text: support or feedback correspondence you send us
  deletion:
    route: Email support@audifact.io to request account closure
    text: To request account closure, email support@audifact.io .
  dpa:
    available: true
    text: Enterprise customers may request a Data Processing Agreement (DPA) at support@audifact.io .
    url: support@audifact.io
  purposes:
  - purpose: Provide, secure, and maintain the Service
    text: Provide, secure, and maintain the Service (authentication, metering, verification, support).
  - purpose: Process payments and subscriptions
    text: Process payments and manage subscriptions and Event Credits.
  - purpose: Transactional email
    text: Send transactional email (for example email verification, password reset, and security or account notices).
  - purpose: Marketing measurement
    text: Measure and improve marketing, including Google Ads performance and conversion tracking
  - purpose: Abuse detection
    text: Detect abuse, rate-limit credential stuffing and spam signups, protect integrity of the ledger, and comply with law.
  residency:
  - region: United States
    text: We are based in the United States and process information on servers located in the United States.
  retention:
  - period: null
    scope: Event records
    text: Event records are retained to preserve hash-chain integrity and independent verification.
  - period: null
    scope: Account closure
    text: We disable access and anonymize or delete account-identifying information where feasible.
  rights:
  - right: access, correct, delete, restrict, object
    text: you may have rights to access, correct, delete, restrict, or object to certain processing, or to data portability
  - right: erasure
    text: Where privacy law grants erasure rights, we will honor requests for personal data we control
  role:
    text: For account, billing, and site operations, we act as a data controller .
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: If you access the Service from outside the U.S., you understand that your information may be transferred to, stored in, and processed in the U.S. and other countries where our providers operate.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Audifact
provenance_date: '2026-11-09'
provider_name: Audifact
provider_slug: audifact-io
slug: audifact-io-privacy-policy
source_date: '2026-11-09'
source_filename: audifact-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://audifact.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Audifact\naid: audifact-io\nurl: https://audifact.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For account, billing, and site operations, we act as a data controller .\ndata_categories:\n- category: contact\n  text: 'Account data: email address, name, optional organization name, password (stored in hashed form when set)'\n- category: identifying\n  text: 'OAuth sign-in: when you use GitHub or Google, we receive the provider account identifiers and profile fields'\n- category: financial\n  text: 'Payment data: billing is handled by Stripe. We receive customer IDs, subscription status,\
  \ and payment metadata\n    - not your full card number.'\n- category: location\n  text: approximate location derived from IP\n- category: device\n  text: 'Technical and security data: IP address (and hashed forms used for rate limiting), browser type, request\n    logs'\n- category: behavioral\n  text: 'Advertising and measurement data: when you visit our website or landing pages, Google may receive device\n    and usage signals via the Google tag'\n- category: communication\n  text: support or feedback correspondence you send us\npurposes:\n- purpose: Provide, secure, and maintain the Service\n  text: Provide, secure, and maintain the Service (authentication, metering, verification, support).\n- purpose: Process payments and subscriptions\n  text: Process payments and manage subscriptions and Event Credits.\n- purpose: Transactional email\n  text: Send transactional email (for example email verification, password reset, and security or account notices).\n- purpose: Marketing measurement\n\
  \  text: Measure and improve marketing, including Google Ads performance and conversion tracking\n- purpose: Abuse detection\n  text: Detect abuse, rate-limit credential stuffing and spam signups, protect integrity of the ledger, and comply\n    with law.\nretention:\n- scope: Event records\n  period: null\n  text: Event records are retained to preserve hash-chain integrity and independent verification.\n- scope: Account closure\n  period: null\n  text: We disable access and anonymize or delete account-identifying information where feasible.\nresidency:\n- region: United States\n  text: We are based in the United States and process information on servers located in the United States.\ntransfers:\n- mechanism: other\n  text: If you access the Service from outside the U.S., you understand that your information may be transferred\n    to, stored in, and processed in the U.S. and other countries where our providers operate.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n\
  \  url: support@audifact.io\n  text: Enterprise customers may request a Data Processing Agreement (DPA) at support@audifact.io .\ndeletion:\n  route: Email support@audifact.io to request account closure\n  text: To request account closure, email support@audifact.io .\nrights:\n- right: access, correct, delete, restrict, object\n  text: you may have rights to access, correct, delete, restrict, or object to certain processing, or to data portability\n- right: erasure\n  text: Where privacy law grants erasure rights, we will honor requests for personal data we control\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/audifact-io/privacy/audifact-io-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Audifact's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Auditing
- Ledger
- Compliance
- Agents
- Platform
---
