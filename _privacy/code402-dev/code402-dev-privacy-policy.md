---
api_specs:
- filename: code402-dev-autonomous-api-openapi.yml
  format: yaml
  label: Code402 Autonomous API
  slug: code402-dev-autonomous-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/code402-dev/openapi/code402-dev-autonomous-api-openapi.yml
- filename: code402-dev-fx-api-openapi.yml
  format: yaml
  label: Code402 Fx API
  slug: code402-dev-fx-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/code402-dev/openapi/code402-dev-fx-api-openapi.yml
- filename: code402-dev-modules-api-openapi.yml
  format: yaml
  label: Code402 Modules API
  slug: code402-dev-modules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/code402-dev/openapi/code402-dev-modules-api-openapi.yml
- filename: code402-dev-multimodal-api-openapi.yml
  format: yaml
  label: Code402 Multimodal API
  slug: code402-dev-multimodal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/code402-dev/openapi/code402-dev-multimodal-api-openapi.yml
- filename: code402-dev-quota-api-openapi.yml
  format: yaml
  label: Code402 Quota API
  slug: code402-dev-quota-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/code402-dev/openapi/code402-dev-quota-api-openapi.yml
- filename: code402-dev-receipt-api-openapi.yml
  format: yaml
  label: Code402 Receipt API
  slug: code402-dev-receipt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/code402-dev/openapi/code402-dev-receipt-api-openapi.yml
- filename: code402-dev-tools-api-openapi.yml
  format: yaml
  label: Code402 Tools API
  slug: code402-dev-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/code402-dev/openapi/code402-dev-tools-api-openapi.yml
- filename: code402-dev-webhooks-api-openapi.yml
  format: yaml
  label: Code402 Webhooks API
  slug: code402-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/code402-dev/openapi/code402-dev-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  data_categories:
  - category: identifying
    text: They can include an IP-derived allowance key for free-tier access, a payment address for paid access, tool name, timestamp and payment amount.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Comparison of supplied records
    text: POST /commerce/reconcile processes the JSON records you submit and returns an exception report.
  retention:
  - period: null
    scope: Comparison handler
    text: The comparison handler has no record-retention store.
  - period: null
    scope: Legacy routes
    text: Legacy routes can retain operational records such as funnel events, settlement metadata and receipts according to their implementation.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Cloudflare provides compute, storage and DNS infrastructure.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Code402
provenance_date: '2026-11-09'
provider_name: Code402
provider_slug: code402-dev
slug: code402-dev-privacy-policy
source_date: '2026-11-09'
source_filename: code402-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://code402.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Code402\naid: code402-dev\nurl: https://code402.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: They can include an IP-derived allowance key for free-tier access, a payment address for paid access, tool\n    name, timestamp and payment amount.\npurposes:\n- purpose: Comparison of supplied records\n  text: POST /commerce/reconcile processes the JSON records you submit and returns an exception report.\nretention:\n- scope: Comparison handler\n  period: null\n  text: The comparison handler has no record-retention store.\n- scope:\
  \ Legacy routes\n  period: null\n  text: Legacy routes can retain operational records such as funnel events, settlement metadata and receipts according\n    to their implementation.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare provides compute, storage and DNS infrastructure.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/code402-dev/privacy/code402-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
summary_line: 5 quoted statements, read from Code402's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Reconciliation
- x402
- AI Agents
- Verification
- MCP
- ISO 20022
---
