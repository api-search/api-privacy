---
api_specs:
- filename: catalog-guard-api-catalog-api-openapi.yml
  format: yaml
  label: Catalog Guard API Catalog API
  slug: catalog-guard-api-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/catalog-guard-api/openapi/catalog-guard-api-catalog-api-openapi.yml
claim_count: 6
description: ''
doc:
  data_categories:
  - category: identifying
    text: the business or contact name, email, approximate row-count range, brief non-sensitive summary, request status, and the consent timestamp and consent version recorded when you submit
  - category: location
    text: country, existing-store answer, brief goal/context
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: evaluate and reply to diagnostic request
    text: These details are used solely to evaluate and reply to that request, not for marketing opt-in.
  - purpose: evaluate and respond to launch request
    text: These details are used solely to evaluate and respond to the request, not for marketing opt-in.
  retention:
  - period: null
    scope: diagnostic request records
    text: Diagnostic-request records are retained only as long as reasonably needed to evaluate and respond to the request, then may be deleted or de-identified.
  - period: null
    scope: launch request records
    text: Records are retained only as long as reasonably needed to evaluate and respond to the request, then may be deleted or de-identified.
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
name: Catalog Guard API
provenance_date: '2026-11-09'
provider_name: Catalog Guard API
provider_slug: catalog-guard-api
slug: catalog-guard-api-privacy-policy
source_date: '2026-11-09'
source_filename: catalog-guard-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://catalogguard.noahcortezj-c.workers.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Catalog Guard API\naid: catalog-guard-api\nurl: https://catalogguard.noahcortezj-c.workers.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: the business or contact name, email, approximate row-count range, brief non-sensitive summary, request status,\n    and the consent timestamp and consent version recorded when you submit\n- category: location\n  text: country, existing-store answer, brief goal/context\npurposes:\n- purpose: evaluate and reply to diagnostic request\n  text: These details are used solely to evaluate and reply\
  \ to that request, not for marketing opt-in.\n- purpose: evaluate and respond to launch request\n  text: These details are used solely to evaluate and respond to the request, not for marketing opt-in.\nretention:\n- scope: diagnostic request records\n  period: null\n  text: Diagnostic-request records are retained only as long as reasonably needed to evaluate and respond to the\n    request, then may be deleted or de-identified.\n- scope: launch request records\n  period: null\n  text: Records are retained only as long as reasonably needed to evaluate and respond to the request, then may\n    be deleted or de-identified.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/catalog-guard-api/privacy/catalog-guard-api-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
summary_line: 6 quoted statements, read from Catalog Guard API's own page on 2026-11-09.
synthetic: false
tags:
- E-Commerce
- catalog-validation
- Shopify
- Data Quality
- CSV validation
- product-data-qa
- data-preflight
- Data Validation
- Retail
---
