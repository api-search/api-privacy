---
api_specs:
- filename: openkrill-app-openapi-generated.yml
  format: yaml
  label: openkrill-app API
  slug: openkrill-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openkrill-app/openapi/_ae-authored/openkrill-app-openapi-generated.yml
claim_count: 6
description: ''
doc:
  data_categories:
  - category: behavioral
    text: We log the tool name and the inputs your client sends (not your chat) to improve speed and reliability
  deletion:
    route: 'Store Price Tracker: a store owner can ask for a store to be removed through the support page'
    text: A store owner can ask for a store to be removed through the support page or disallow StorePriceTracker in robots.txt.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: improve speed and reliability
    text: We log the tool name and the inputs your client sends (not your chat) to improve speed and reliability
  - purpose: count daily users
    text: To count how many different callers use each plugin per day, we hash the network address and user agent together with a random value
  retention:
  - period: 30 days
    scope: tool input log
    text: delete the logs after 30 days
  - period: null
    scope: daily caller hashes
    text: That day's hashes are kept only so a caller is not counted twice, and are deleted once the day is over
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
name: openkrill-app
provenance_date: '2026-11-10'
provider_name: openkrill-app
provider_slug: openkrill-app
slug: openkrill-app-privacy-policy
source_date: '2026-11-10'
source_filename: openkrill-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tools.openkrill.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: openkrill-app\naid: openkrill-app\nurl: https://tools.openkrill.app/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: We log the tool name and the inputs your client sends (not your chat) to improve speed and reliability\npurposes:\n- purpose: improve speed and reliability\n  text: We log the tool name and the inputs your client sends (not your chat) to improve speed and reliability\n- purpose: count daily users\n  text: To count how many different callers use each plugin per day, we hash the network address and\
  \ user agent\n    together with a random value\nretention:\n- scope: tool input log\n  period: 30 days\n  text: delete the logs after 30 days\n- scope: daily caller hashes\n  period: null\n  text: That day's hashes are kept only so a caller is not counted twice, and are deleted once the day is over\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: 'Store Price Tracker: a store owner can ask for a store to be removed through the support page'\n  text: A store owner can ask for a store to be removed through the support page or disallow StorePriceTracker in\n    robots.txt.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/openkrill-app/privacy/openkrill-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 6 quoted statements, read from openkrill-app's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MarineBiology
- Data Analytics
- EnvironmentalResearch
- Open Data
---
