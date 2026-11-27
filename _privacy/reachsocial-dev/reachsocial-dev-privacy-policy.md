---
api_specs:
- filename: reachsocial-dev-catalog-api-openapi.yml
  format: yaml
  label: ReachSocial Catalog API
  slug: reachsocial-dev-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachsocial-dev/openapi/reachsocial-dev-catalog-api-openapi.yml
- filename: reachsocial-dev-jobs-api-openapi.yml
  format: yaml
  label: ReachSocial Jobs API
  slug: reachsocial-dev-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachsocial-dev/openapi/reachsocial-dev-jobs-api-openapi.yml
- filename: reachsocial-dev-operations-api-openapi.yml
  format: yaml
  label: ReachSocial Operations API
  slug: reachsocial-dev-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachsocial-dev/openapi/reachsocial-dev-operations-api-openapi.yml
- filename: reachsocial-dev-owner-api-openapi.yml
  format: yaml
  label: ReachSocial Owner API
  slug: reachsocial-dev-owner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachsocial-dev/openapi/reachsocial-dev-owner-api-openapi.yml
- filename: reachsocial-dev-payments-api-openapi.yml
  format: yaml
  label: ReachSocial Payments API
  slug: reachsocial-dev-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachsocial-dev/openapi/reachsocial-dev-payments-api-openapi.yml
- filename: reachsocial-dev-resolve-api-openapi.yml
  format: yaml
  label: ReachSocial Resolve API
  slug: reachsocial-dev-resolve-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachsocial-dev/openapi/reachsocial-dev-resolve-api-openapi.yml
- filename: reachsocial-dev-services-api-openapi.yml
  format: yaml
  label: ReachSocial Services API
  slug: reachsocial-dev-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachsocial-dev/openapi/reachsocial-dev-services-api-openapi.yml
claim_count: 5
description: ''
doc:
  data_categories:
  - category: identifying
    text: ReachSocial stores client identifiers, hashed API keys, request metadata, hashed inputs, usage, payment receipts, and operational logs
  - category: identifying
    text: Wallet sign-in stores the public wallet address, a short-lived session, and connected-agent records.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, secure, and troubleshoot the service
    text: needed to provide, secure, and troubleshoot the service
  retention:
  - period: up to 30 days
    scope: Paid request records
    text: A paid request stores its service, normalized input, payment reference, and result-recovery record for up to 30 days.
  - period: null
    scope: Payment receipts
    text: payment receipts are retained for accounting and replay protection
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ReachSocial
provenance_date: '2026-11-10'
provider_name: ReachSocial
provider_slug: reachsocial-dev
slug: reachsocial-dev-privacy-policy
source_date: '2026-11-10'
source_filename: reachsocial-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://reachsocial.dev/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ReachSocial\naid: reachsocial-dev\nurl: https://reachsocial.dev/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: ReachSocial stores client identifiers, hashed API keys, request metadata, hashed inputs, usage, payment\n    receipts, and operational logs\n- category: identifying\n  text: Wallet sign-in stores the public wallet address, a short-lived session, and connected-agent records.\npurposes:\n- purpose: Provide, secure, and troubleshoot the service\n  text: needed to provide, secure, and troubleshoot the service\nretention:\n\
  - scope: Paid request records\n  period: up to 30 days\n  text: A paid request stores its service, normalized input, payment reference, and result-recovery record for up\n    to 30 days.\n- scope: Payment receipts\n  period: null\n  text: payment receipts are retained for accounting and replay protection\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/reachsocial-dev/privacy/reachsocial-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
summary_line: 5 quoted statements, read from ReachSocial's own page on 2026-11-10.
synthetic: false
tags:
- Social
- Data
- Public
- Payments
---
