---
api_specs:
- filename: monkt-openapi-generated.yml
  format: yaml
  label: Monkt API
  slug: monkt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monkt/openapi/_ae-authored/monkt-openapi-generated.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information (email and password)
  - category: financial
    text: Payment information (processed securely by our payment provider)
  - category: behavioral
    text: Usage data for service functionality
  - category: other
    text: Document transformation outputs
  deletion:
    route: Request deletion; permanent deletion upon request
    text: Data can be permanently deleted upon request
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service functionality
    text: Usage data for service functionality
  retention:
  - period: 7 days
    scope: transformed outputs
    text: 'Start plan: 7 days'
  - period: 30 days
    scope: transformed outputs
    text: 'Pro plan: 30 days'
  - period: Custom duration as specified in contract
    scope: transformed outputs
    text: 'Enterprise plan: Custom duration as specified in contract'
  - period: immediately deleted
    scope: original files
    text: Original files are processed and immediately deleted after transformation.
  rights:
  - right: deletion
    text: Request deletion of your data
  - right: access
    text: Access your transformed documents within the storage period
  - right: export
    text: Export your data
  - right: account closure
    text: Close your account
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
name: Monkt
provenance_date: '2026-11-10'
provider_name: Monkt
provider_slug: monkt
slug: monkt-privacy-policy
source_date: '2026-11-10'
source_filename: monkt-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://monkt.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Monkt\naid: monkt\nurl: https://monkt.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information (email and password)\n- category: financial\n  text: Payment information (processed securely by our payment provider)\n- category: behavioral\n  text: Usage data for service functionality\n- category: other\n  text: Document transformation outputs\npurposes:\n- purpose: service functionality\n  text: Usage data for service functionality\nretention:\n- scope: transformed outputs\n  period: 7 days\n  text: 'Start plan: 7\
  \ days'\n- scope: transformed outputs\n  period: 30 days\n  text: 'Pro plan: 30 days'\n- scope: transformed outputs\n  period: Custom duration as specified in contract\n  text: 'Enterprise plan: Custom duration as specified in contract'\n- scope: original files\n  period: immediately deleted\n  text: Original files are processed and immediately deleted after transformation.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion; permanent deletion upon request\n  text: Data can be permanently deleted upon request\nrights:\n- right: deletion\n  text: Request deletion of your data\n- right: access\n  text: Access your transformed documents within the storage period\n- right: export\n  text: Export your data\n- right: account closure\n  text: Close your account\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/monkt/privacy/monkt-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 14 quoted statements, read from Monkt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Document Processing
- Automation
---
