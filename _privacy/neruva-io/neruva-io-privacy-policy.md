---
api_specs:
- filename: neruva-io-agent-cognitive-api-openapi.yml
  format: yaml
  label: neruva-io Agent Cognitive API
  slug: neruva-io-agent-cognitive-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neruva-io/openapi/neruva-io-agent-cognitive-api-openapi.yml
- filename: neruva-io-agent-federated-api-openapi.yml
  format: yaml
  label: neruva-io Agent Federated API
  slug: neruva-io-agent-federated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neruva-io/openapi/neruva-io-agent-federated-api-openapi.yml
- filename: neruva-io-audit-api-openapi.yml
  format: yaml
  label: neruva-io Audit API
  slug: neruva-io-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neruva-io/openapi/neruva-io-audit-api-openapi.yml
- filename: neruva-io-commons-api-openapi.yml
  format: yaml
  label: neruva-io Commons API
  slug: neruva-io-commons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neruva-io/openapi/neruva-io-commons-api-openapi.yml
- filename: neruva-io-hd-native-api-openapi.yml
  format: yaml
  label: neruva-io Hd Native API
  slug: neruva-io-hd-native-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neruva-io/openapi/neruva-io-hd-native-api-openapi.yml
- filename: neruva-io-health-api-openapi.yml
  format: yaml
  label: neruva-io Health API
  slug: neruva-io-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neruva-io/openapi/neruva-io-health-api-openapi.yml
- filename: neruva-io-indexes-api-openapi.yml
  format: yaml
  label: neruva-io Indexes API
  slug: neruva-io-indexes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neruva-io/openapi/neruva-io-indexes-api-openapi.yml
- filename: neruva-io-me-api-openapi.yml
  format: yaml
  label: neruva-io Me API
  slug: neruva-io-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neruva-io/openapi/neruva-io-me-api-openapi.yml
- filename: neruva-io-memory-api-openapi.yml
  format: yaml
  label: neruva-io Memory API
  slug: neruva-io-memory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neruva-io/openapi/neruva-io-memory-api-openapi.yml
- filename: neruva-io-neruva-api-openapi.yml
  format: yaml
  label: neruva-io Neruva API
  slug: neruva-io-neruva-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neruva-io/openapi/neruva-io-neruva-api-openapi.yml
- filename: neruva-io-pii-api-openapi.yml
  format: yaml
  label: neruva-io Pii API
  slug: neruva-io-pii-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neruva-io/openapi/neruva-io-pii-api-openapi.yml
- filename: neruva-io-records-api-openapi.yml
  format: yaml
  label: neruva-io Records API
  slug: neruva-io-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neruva-io/openapi/neruva-io-records-api-openapi.yml
claim_count: 8
description: ''
doc:
  data_categories:
  - category: other
    text: 'Neruva stores what your agent sends it: records, facts and the text needed to search them.'
  - category: other
    text: It also logs each call (time, operation, namespace) to meter use and fix problems.
  deletion:
    route: API or email request
    text: You can forget or export your data through the API at any time, or email me and I will delete your namespaces and key.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: store and search agent data
    text: 'Neruva stores what your agent sends it: records, facts and the text needed to search them.'
  - purpose: metering and troubleshooting
    text: It also logs each call (time, operation, namespace) to meter use and fix problems.
  residency:
  - region: USA
    text: On Google Cloud in the us-central1 region (USA), encrypted in transit and at rest.
  rights:
  - right: forget or export data
    text: You can forget or export your data through the API at any time
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: It is not used to train models, not sold, and not shared with anyone except the hosting provider that runs the service.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: neruva-io
provenance_date: '2026-11-10'
provider_name: neruva-io
provider_slug: neruva-io
slug: neruva-io-privacy-policy
source_date: '2026-11-10'
source_filename: neruva-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://neruva.io/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: neruva-io\naid: neruva-io\nurl: https://neruva.io/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: other\n  text: 'Neruva stores what your agent sends it: records, facts and the text needed to search them.'\n- category: other\n  text: It also logs each call (time, operation, namespace) to meter use and fix problems.\npurposes:\n- purpose: store and search agent data\n  text: 'Neruva stores what your agent sends it: records, facts and the text needed to search them.'\n- purpose: metering and troubleshooting\n  text: It also logs each call (time, operation,\
  \ namespace) to meter use and fix problems.\nretention: []\nresidency:\n- region: USA\n  text: On Google Cloud in the us-central1 region (USA), encrypted in transit and at rest.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: API or email request\n  text: You can forget or export your data through the API at any time, or email me and I will delete your namespaces\n    and key.\nrights:\n- right: forget or export data\n  text: You can forget or export your data through the API at any time\nsale_or_sharing:\n  stance: conditional\n  text: It is not used to train models, not sold, and not shared with anyone except the hosting provider that runs\n    the service.\n"
source_yaml_url: https://artifacts.apis.io/neruva-io/privacy/neruva-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 8 quoted statements, read from neruva-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Memory
- Artificial Intelligence
- Agents
- MCP
---
