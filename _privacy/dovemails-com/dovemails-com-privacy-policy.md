---
api_specs:
- filename: dovemails-com-send-api-openapi.yml
  format: yaml
  label: dovemails-com Send API
  slug: dovemails-com-send-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dovemails-com/openapi/dovemails-com-send-api-openapi.yml
- filename: dovemails-com-status-api-openapi.yml
  format: yaml
  label: dovemails-com Status API
  slug: dovemails-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dovemails-com/openapi/dovemails-com-status-api-openapi.yml
claim_count: 5
description: ''
doc:
  deletion:
    route: per-contact erase
    text: Data per-contact export and erase
  dpa:
    available: true
    text: a GDPR data processing agreement
    url: null
  retention:
  - period: 30-day
    scope: message history on Free plan
    text: 30-day message history
  rights:
  - right: data subject access and erasure
    text: DSAR export and erase
  role:
    text: Senders' recipient data is processed by Dovemails on the sender's behalf
    value: processor
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
name: dovemails-com
provenance_date: '2026-11-09'
provider_name: dovemails-com
provider_slug: dovemails-com
slug: dovemails-com-privacy-policy
source_date: '2026-11-09'
source_filename: dovemails-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dovemails.com/#privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: dovemails-com\naid: dovemails-com\nurl: https://dovemails.com/#privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: Senders' recipient data is processed by Dovemails on the sender's behalf\ndata_categories: []\npurposes: []\nretention:\n- scope: message history on Free plan\n  period: 30-day\n  text: 30-day message history\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: a GDPR data processing agreement\ndeletion:\n  route: per-contact erase\n  text: Data per-contact export and erase\nrights:\n- right: data subject access\
  \ and erasure\n  text: DSAR export and erase\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dovemails-com/privacy/dovemails-com-privacy-policy.yml
stated_fields:
- role
- retention
- dpa
- deletion
- rights
summary_line: 5 quoted statements, read from dovemails-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- Software-as-a-Service
- Marketing
---
