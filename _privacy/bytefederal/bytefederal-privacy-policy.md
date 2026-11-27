---
api_specs:
- filename: bytefederal-verifications-api-openapi.yml
  format: yaml
  label: Bytefederal Verifications API
  slug: bytefederal-verifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bytefederal/openapi/bytefederal-verifications-api-openapi.yml
claim_count: 4
description: ''
doc:
  data_categories:
  - category: identifying
    text: telephone number, date of birth, taxpayer identification or social security number, official government-issued photo identification
  - category: contact
    text: email, address, telephone number
  - category: financial
    text: bank account information
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Risk management and legal compliance
    text: whether for our business risk-management purposes or to comply with legal requirements applicable to us
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
name: Bytefederal
provenance_date: '2026-11-09'
provider_name: Bytefederal
provider_slug: bytefederal
slug: bytefederal-privacy-policy
source_date: '2026-11-09'
source_filename: bytefederal-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bytefederal.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bytefederal\naid: bytefederal\nurl: https://www.bytefederal.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: telephone number, date of birth, taxpayer identification or social security number, official government-issued\n    photo identification\n- category: contact\n  text: email, address, telephone number\n- category: financial\n  text: bank account information\npurposes:\n- purpose: Risk management and legal compliance\n  text: whether for our business risk-management purposes or to comply with legal requirements applicable\
  \ to us\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bytefederal/privacy/bytefederal-privacy-policy.yml
stated_fields:
- data_categories
- purposes
summary_line: 4 quoted statements, read from Bytefederal's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Payments
- Banking
- Technology
---
