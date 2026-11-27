---
api_specs:
- filename: chikocorp-com-batch-api-openapi.yml
  format: yaml
  label: ChikoCorp Batch API
  slug: chikocorp-com-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikocorp-com/openapi/chikocorp-com-batch-api-openapi.yml
- filename: chikocorp-com-batches-api-openapi.yml
  format: yaml
  label: ChikoCorp Batches API
  slug: chikocorp-com-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikocorp-com/openapi/chikocorp-com-batches-api-openapi.yml
- filename: chikocorp-com-cases-api-openapi.yml
  format: yaml
  label: ChikoCorp Cases API
  slug: chikocorp-com-cases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikocorp-com/openapi/chikocorp-com-cases-api-openapi.yml
- filename: chikocorp-com-credits-api-openapi.yml
  format: yaml
  label: ChikoCorp Credits API
  slug: chikocorp-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikocorp-com/openapi/chikocorp-com-credits-api-openapi.yml
- filename: chikocorp-com-preflight-api-openapi.yml
  format: yaml
  label: ChikoCorp Preflight API
  slug: chikocorp-com-preflight-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikocorp-com/openapi/chikocorp-com-preflight-api-openapi.yml
- filename: chikocorp-com-reports-api-openapi.yml
  format: yaml
  label: ChikoCorp Reports API
  slug: chikocorp-com-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikocorp-com/openapi/chikocorp-com-reports-api-openapi.yml
- filename: chikocorp-com-screen-api-openapi.yml
  format: yaml
  label: ChikoCorp Screen API
  slug: chikocorp-com-screen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikocorp-com/openapi/chikocorp-com-screen-api-openapi.yml
- filename: chikocorp-com-verification-api-openapi.yml
  format: yaml
  label: ChikoCorp Verification API
  slug: chikocorp-com-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikocorp-com/openapi/chikocorp-com-verification-api-openapi.yml
- filename: chikocorp-com-watchlist-api-openapi.yml
  format: yaml
  label: ChikoCorp Watchlist API
  slug: chikocorp-com-watchlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikocorp-com/openapi/chikocorp-com-watchlist-api-openapi.yml
- filename: chikocorp-com-webhooks-api-openapi.yml
  format: yaml
  label: ChikoCorp Webhooks API
  slug: chikocorp-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikocorp-com/openapi/chikocorp-com-webhooks-api-openapi.yml
- filename: chikocorp-com-x402-api-openapi.yml
  format: yaml
  label: ChikoCorp X402 API
  slug: chikocorp-com-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chikocorp-com/openapi/chikocorp-com-x402-api-openapi.yml
claim_count: 7
description: ''
doc:
  data_categories:
  - category: other
    text: Screening sends public addresses to TRON data providers to compute blacklist, sanctions, balance, transfer, and risk signals.
  - category: other
    text: Saved reports, cases, batch rows, watchlist items, API keys, usage counters, billing state, and alert delivery records are stored only for authenticated workflows
  deletion:
    route: Settings
    text: You can export account data or request deletion from Settings.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: compute screening signals
    text: Screening sends public addresses to TRON data providers to compute blacklist, sanctions, balance, transfer, and risk signals.
  - purpose: aggregate analytics
    text: to understand aggregate product usage, page performance, and conversion paths.
  retention:
  - period: null
    scope: reports, alerts and batch data
    text: Retention caps are enforced when REPORT_RETENTION_DAYS , ALERT_EVENT_RETENTION_DAYS , or BATCH_RETENTION_DAYS are configured.
  rights:
  - right: export account data
    text: You can export account data or request deletion from Settings.
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
name: ChikoCorp
provenance_date: '2026-11-09'
provider_name: ChikoCorp
provider_slug: chikocorp-com
slug: chikocorp-com-privacy-policy
source_date: '2026-11-09'
source_filename: chikocorp-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://usdt.chikocorp.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ChikoCorp\naid: chikocorp-com\nurl: https://usdt.chikocorp.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: other\n  text: Screening sends public addresses to TRON data providers to compute blacklist, sanctions, balance, transfer,\n    and risk signals.\n- category: other\n  text: Saved reports, cases, batch rows, watchlist items, API keys, usage counters, billing state, and alert delivery\n    records are stored only for authenticated workflows\npurposes:\n- purpose: compute screening signals\n  text: Screening sends public addresses to TRON data\
  \ providers to compute blacklist, sanctions, balance, transfer,\n    and risk signals.\n- purpose: aggregate analytics\n  text: to understand aggregate product usage, page performance, and conversion paths.\nretention:\n- scope: reports, alerts and batch data\n  period: null\n  text: Retention caps are enforced when REPORT_RETENTION_DAYS , ALERT_EVENT_RETENTION_DAYS , or BATCH_RETENTION_DAYS\n    are configured.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings\n  text: You can export account data or request deletion from Settings.\nrights:\n- right: export account data\n  text: You can export account data or request deletion from Settings.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chikocorp-com/privacy/chikocorp-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 7 quoted statements, read from ChikoCorp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Cryptocurrency
- x402
- Payments
- Stablecoins
- TRON
- Risk Screening
- Developer Tools
- Diagnostics
---
