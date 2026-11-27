---
api_specs:
- filename: runcrate-api-openapi.json
  format: json
  label: Runcrate API API
  slug: runcrate-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runcrate/openapi/_original/runcrate-api-openapi.json
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information (name, email address, password)
  - category: financial
    text: Payment information (processed securely through Stripe)
  - category: behavioral
    text: Usage data (instance configurations, deployment logs)
  - category: communication
    text: Communications (support tickets, feedback)
  - category: location
    text: approximate location from your IP address
  - category: device
    text: your browser and device
  deletion:
    route: account deletion, or deleting saved requests in the dashboard
    text: When you delete your account, we will delete or anonymize your personal information within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve services
    text: Provide, maintain, and improve our services
  - purpose: Process transactions
    text: Process your transactions and send related information
  - purpose: Monitor usage and trends
    text: Monitor and analyze trends, usage, and activities
  retention:
  - period: 30 days
    scope: Personal information after account deletion
    text: When you delete your account, we will delete or anonymize your personal information within 30 days.
  - period: 30 days
    scope: Saved prompts and answers (when setting is on)
    text: we keep what each model call in that environment sent and what came back for 30 days
  rights:
  - right: Access
    text: Access and receive a copy of your personal data
  - right: Correction
    text: Correct inaccurate or incomplete data
  - right: Deletion
    text: Request deletion of your data
  - right: Object or restrict
    text: Object to or restrict processing of your data
  - right: Portability
    text: Export your data in a portable format
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
name: Runcrate
provenance_date: '2026-11-10'
provider_name: Runcrate
provider_slug: runcrate
slug: runcrate-privacy-policy
source_date: '2026-11-10'
source_filename: runcrate-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.runcrate.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Runcrate\naid: runcrate\nurl: https://www.runcrate.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information (name, email address, password)\n- category: financial\n  text: Payment information (processed securely through Stripe)\n- category: behavioral\n  text: Usage data (instance configurations, deployment logs)\n- category: communication\n  text: Communications (support tickets, feedback)\n- category: location\n  text: approximate location from your IP address\n- category: device\n  text: your browser and device\n\
  purposes:\n- purpose: Provide and improve services\n  text: Provide, maintain, and improve our services\n- purpose: Process transactions\n  text: Process your transactions and send related information\n- purpose: Monitor usage and trends\n  text: Monitor and analyze trends, usage, and activities\nretention:\n- scope: Personal information after account deletion\n  period: 30 days\n  text: When you delete your account, we will delete or anonymize your personal information within 30 days.\n- scope: Saved prompts and answers (when setting is on)\n  period: 30 days\n  text: we keep what each model call in that environment sent and what came back for 30 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion, or deleting saved requests in the dashboard\n  text: When you delete your account, we will delete or anonymize your personal information within 30 days.\nrights:\n- right: Access\n\
  \  text: Access and receive a copy of your personal data\n- right: Correction\n  text: Correct inaccurate or incomplete data\n- right: Deletion\n  text: Request deletion of your data\n- right: Object or restrict\n  text: Object to or restrict processing of your data\n- right: Portability\n  text: Export your data in a portable format\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/runcrate/privacy/runcrate-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 17 quoted statements, read from Runcrate's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- GPU
- Inference
- Compute
- Platform
---
