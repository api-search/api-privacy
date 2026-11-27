---
api_specs:
- filename: seaweb-tech-openapi-generated.yml
  format: yaml
  label: seaweb-tech API
  slug: seaweb-tech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seaweb-tech/openapi/_ae-authored/seaweb-tech-openapi-generated.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: other
    text: Potential data includes website/security logs; account, authentication, API-key, support, and quota data; FastMCP queries, tool arguments, and returned identifiers; and publisher listings and contacts.
  - category: contact
    text: publisher listings and contacts
  - category: financial
    text: SeaWeb does not receive raw payment card numbers.
  deletion:
    route: pending operational review
    text: Publish request, identity-verification, automated deletion (`prepare_account_deletion` RPC), and exception procedures only after operational review.
  dpa:
    available: null
    text: null
    url: null
  retention:
  - period: 30 days
    scope: security logs
    text: security logs 30 days
  - period: 90 days
    scope: query/telemetry
    text: query/telemetry 90 days
  - period: up to 72 hours
    scope: grounded live-search cache
    text: grounded live-search cache up to 72 hours
  - period: plus 30 days
    scope: active publisher data
    text: active publisher data plus 30 days
  - period: up to 30 days
    scope: backups
    text: backups up to 30 days (retaining last 5 snapshots)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Candidate subprocessors include Amazon Web Services (AWS) for compute and indexing infrastructure
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: seaweb-tech
provenance_date: '2026-11-10'
provider_name: seaweb-tech
provider_slug: seaweb-tech
slug: seaweb-tech-privacy-policy
source_date: '2026-11-10'
source_filename: seaweb-tech-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://seaweb.tech/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: seaweb-tech\naid: seaweb-tech\nurl: https://seaweb.tech/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: other\n  text: Potential data includes website/security logs; account, authentication, API-key, support, and quota data;\n    FastMCP queries, tool arguments, and returned identifiers; and publisher listings and contacts.\n- category: contact\n  text: publisher listings and contacts\n- category: financial\n  text: SeaWeb does not receive raw payment card numbers.\npurposes: []\nretention:\n- scope: security logs\n  period: 30 days\n  text: security\
  \ logs 30 days\n- scope: query/telemetry\n  period: 90 days\n  text: query/telemetry 90 days\n- scope: grounded live-search cache\n  period: up to 72 hours\n  text: grounded live-search cache up to 72 hours\n- scope: active publisher data\n  period: plus 30 days\n  text: active publisher data plus 30 days\n- scope: backups\n  period: up to 30 days\n  text: backups up to 30 days (retaining last 5 snapshots)\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Candidate subprocessors include Amazon Web Services (AWS) for compute and indexing infrastructure\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: pending operational review\n  text: Publish request, identity-verification, automated deletion (`prepare_account_deletion` RPC), and exception\n    procedures only after operational review.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/seaweb-tech/privacy/seaweb-tech-privacy-policy.yml
stated_fields:
- data_categories
- retention
- subprocessors
- deletion
summary_line: 10 quoted statements, read from seaweb-tech's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- ContextAPI
- Search
- Extraction
- Monitoring
---
