---
api_specs:
- filename: journalize-dev-accounts-api-openapi.yml
  format: yaml
  label: journalize-dev Accounts API
  slug: journalize-dev-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-accounts-api-openapi.yml
- filename: journalize-dev-export-api-openapi.yml
  format: yaml
  label: journalize-dev Export API
  slug: journalize-dev-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-export-api-openapi.yml
- filename: journalize-dev-health-api-openapi.yml
  format: yaml
  label: journalize-dev Health API
  slug: journalize-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-health-api-openapi.yml
- filename: journalize-dev-journal-api-openapi.yml
  format: yaml
  label: journalize-dev Journal API
  slug: journalize-dev-journal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-journal-api-openapi.yml
- filename: journalize-dev-journalize-api-openapi.yml
  format: yaml
  label: journalize-dev Journalize API
  slug: journalize-dev-journalize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-journalize-api-openapi.yml
- filename: journalize-dev-llms-txt-api-openapi.yml
  format: yaml
  label: journalize-dev Llms.txt API
  slug: journalize-dev-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-llms-txt-api-openapi.yml
- filename: journalize-dev-privacy-api-openapi.yml
  format: yaml
  label: journalize-dev Privacy API
  slug: journalize-dev-privacy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-privacy-api-openapi.yml
- filename: journalize-dev-register-api-openapi.yml
  format: yaml
  label: journalize-dev Register API
  slug: journalize-dev-register-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-register-api-openapi.yml
- filename: journalize-dev-reports-api-openapi.yml
  format: yaml
  label: journalize-dev Reports API
  slug: journalize-dev-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-reports-api-openapi.yml
- filename: journalize-dev-robots-txt-api-openapi.yml
  format: yaml
  label: journalize-dev Robots.txt API
  slug: journalize-dev-robots-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-robots-txt-api-openapi.yml
- filename: journalize-dev-security-txt-api-openapi.yml
  format: yaml
  label: journalize-dev Security.txt API
  slug: journalize-dev-security-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-security-txt-api-openapi.yml
- filename: journalize-dev-skill-md-api-openapi.yml
  format: yaml
  label: journalize-dev SKILL.md API
  slug: journalize-dev-skill-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-skill-md-api-openapi.yml
- filename: journalize-dev-terms-api-openapi.yml
  format: yaml
  label: journalize-dev Terms API
  slug: journalize-dev-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-terms-api-openapi.yml
- filename: journalize-dev-well-known-api-openapi.yml
  format: yaml
  label: journalize-dev .well Known API
  slug: journalize-dev-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/journalize-dev/openapi/journalize-dev-well-known-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your public key , generated at registration and stored so we can verify your signed requests going forward.
  - category: financial
    text: 'Payment data : paid calls settle via the x402 protocol using a blockchain wallet address on Base.'
  - category: communication
    text: 'The directive text you submit — literal Beancount syntax: account names, dates, amounts, currencies, and any narration text you write into a transaction.'
  - category: device
    text: 'Standard infrastructure logs : like any web service, our hosting provider logs IP addresses, timestamps, and requested endpoints for security and debugging.'
  deletion:
    route: null
    text: If you believe we hold data about you — including as a third party mentioned in someone else's directive narration — and want it reviewed, deleted, or explained, contact us below.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Verifying signed requests and payments
    text: stored so we can verify your signed requests going forward
  - purpose: Security, dispute resolution, and abuse prevention
    text: every request — including free ones, and failed or rejected ones — is logged with an action, an outcome, and a timestamp, for security, dispute resolution, and abuse prevention.
  retention:
  - period: null
    scope: Standard infrastructure logs
    text: Retained for a limited period, never sold or used for advertising.
  rights:
  - right: Review, deletion, or explanation
    text: If you believe we hold data about you — including as a third party mentioned in someone else's directive narration — and want it reviewed, deleted, or explained, contact us below.
  - right: Export of ledger data
    text: You can retrieve the complete literal text of everything you've stored at any time via GET /export (or the export_ledger MCP tool)
  role:
    text: We are a processor of your accounting records, not a claimant on them.
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data to third parties, and we do not use any data collected through the Service for advertising.
  subprocessors:
    text: Our hosting provider , which runs the infrastructure the Service runs on.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: journalize-dev
provenance_date: '2026-11-09'
provider_name: journalize-dev
provider_slug: journalize-dev
slug: journalize-dev-privacy-policy
source_date: '2026-11-09'
source_filename: journalize-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://journalize.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: journalize-dev\naid: journalize-dev\nurl: https://journalize.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: We are a processor of your accounting records, not a claimant on them.\ndata_categories:\n- category: identifying\n  text: Your public key , generated at registration and stored so we can verify your signed requests going forward.\n- category: financial\n  text: 'Payment data : paid calls settle via the x402 protocol using a blockchain wallet address on Base.'\n- category: communication\n  text: 'The directive text you submit — literal Beancount syntax: account names, dates,\
  \ amounts, currencies, and\n    any narration text you write into a transaction.'\n- category: device\n  text: 'Standard infrastructure logs : like any web service, our hosting provider logs IP addresses, timestamps,\n    and requested endpoints for security and debugging.'\npurposes:\n- purpose: Verifying signed requests and payments\n  text: stored so we can verify your signed requests going forward\n- purpose: Security, dispute resolution, and abuse prevention\n  text: every request — including free ones, and failed or rejected ones — is logged with an action, an outcome,\n    and a timestamp, for security, dispute resolution, and abuse prevention.\nretention:\n- scope: Standard infrastructure logs\n  period: null\n  text: Retained for a limited period, never sold or used for advertising.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Our hosting provider , which runs the infrastructure the Service runs on.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n\
  \  route: null\n  text: If you believe we hold data about you — including as a third party mentioned in someone else's directive\n    narration — and want it reviewed, deleted, or explained, contact us below.\nrights:\n- right: Review, deletion, or explanation\n  text: If you believe we hold data about you — including as a third party mentioned in someone else's directive\n    narration — and want it reviewed, deleted, or explained, contact us below.\n- right: Export of ledger data\n  text: You can retrieve the complete literal text of everything you've stored at any time via GET /export (or the\n    export_ledger MCP tool)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell data to third parties, and we do not use any data collected through the Service for advertising.\n"
source_yaml_url: https://artifacts.apis.io/journalize-dev/privacy/journalize-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from journalize-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Accounting
- Artificial Intelligence
- Fintech
- Ledger
---
