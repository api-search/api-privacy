---
api_specs:
- filename: bumit-ai-v1-openapi.json
  format: json
  label: BUMIT API V1 API
  slug: bumit-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bumit-ai/openapi/_original/bumit-ai-v1-openapi.json
claim_count: 8
description: ''
doc:
  data_categories:
  - category: device
    text: The hosting infrastructure may process technical connection information to deliver, operate and protect requests.
  - category: behavioral
    text: 'Each completed business verification records one anonymous structured usage event using a closed, predefined vocabulary (for example: input type, outcome, reason code, timestamp).'
  deletion:
    route: operator maintenance; hosting infrastructure controls its own logs
    text: They are periodically removed as part of operator maintenance; removal is not automatic, so records may remain somewhat longer until the next maintenance run.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate service and improve reliability
    text: Anonymous verification usage events and aggregate MCP activity statistics are used to operate BUMIT, understand usage and adoption, analyse reliability, identify problems and improve the service.
  retention:
  - period: up to 365 days
    scope: anonymous usage events and MCP activity statistics
    text: Anonymous verification usage events and aggregate MCP activity statistics are normally retained for up to 365 days.
  - period: 90-day retention target
    scope: self-reported MCP request counters
    text: These aggregate request counters have a 90-day retention target and are removed through operator maintenance, not automatically.
  - period: null
    scope: hosting infrastructure logs
    text: BUMIT does not state a deletion period for them.
  rights:
  - right: privacy questions contact
    text: Privacy-related questions can be sent to the address below.
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
name: BUMIT
provenance_date: '2026-11-09'
provider_name: BUMIT
provider_slug: bumit-ai
slug: bumit-ai-privacy-policy
source_date: '2026-11-09'
source_filename: bumit-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bumit.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BUMIT\naid: bumit-ai\nurl: https://bumit.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: The hosting infrastructure may process technical connection information to deliver, operate and protect\n    requests.\n- category: behavioral\n  text: 'Each completed business verification records one anonymous structured usage event using a closed, predefined\n    vocabulary (for example: input type, outcome, reason code, timestamp).'\npurposes:\n- purpose: operate service and improve reliability\n  text: Anonymous verification usage events\
  \ and aggregate MCP activity statistics are used to operate BUMIT, understand\n    usage and adoption, analyse reliability, identify problems and improve the service.\nretention:\n- scope: anonymous usage events and MCP activity statistics\n  period: up to 365 days\n  text: Anonymous verification usage events and aggregate MCP activity statistics are normally retained for up to\n    365 days.\n- scope: self-reported MCP request counters\n  period: 90-day retention target\n  text: These aggregate request counters have a 90-day retention target and are removed through operator maintenance,\n    not automatically.\n- scope: hosting infrastructure logs\n  period: null\n  text: BUMIT does not state a deletion period for them.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: operator maintenance; hosting infrastructure controls its own logs\n  text: They are periodically removed as part of operator\
  \ maintenance; removal is not automatic, so records may\n    remain somewhat longer until the next maintenance run.\nrights:\n- right: privacy questions contact\n  text: Privacy-related questions can be sent to the address below.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bumit-ai/privacy/bumit-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 8 quoted statements, read from BUMIT's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Trust
- Verification
- Swiss
---
