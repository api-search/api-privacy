---
api_specs:
- filename: tabnine-groups-api-openapi.yml
  format: yaml
  label: Tabnine Groups API
  slug: tabnine-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabnine/openapi/tabnine-groups-api-openapi.yml
- filename: tabnine-main-api-openapi.yml
  format: yaml
  label: Tabnine Main API
  slug: tabnine-main-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabnine/openapi/tabnine-main-api-openapi.yml
- filename: tabnine-schemas-api-openapi.yml
  format: yaml
  label: Tabnine Schemas API
  slug: tabnine-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabnine/openapi/tabnine-schemas-api-openapi.yml
- filename: tabnine-users-api-openapi.yml
  format: yaml
  label: Tabnine Users API
  slug: tabnine-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tabnine/openapi/tabnine-users-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: behavioral
    text: Lines of code
  - category: device
    text: User machine details, including CPU type, available processors, and memory
  - category: identifying
    text: One-way hashed, nonidentifiable data, including user email, hostname, and IP
  - category: behavioral
    text: Aggregated number of suggestions/completions per programming language
  deletion:
    route: null
    text: Tabnine doesn’t retain any user code beyond the immediate time frame required for inferencing the model.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: System health and quality of service
    text: The Tabnine cluster collects operational metrics and logs to ensure system health and quality of service.
  retention:
  - period: null
    scope: Code context
    text: This context is deleted immediately after the server returns the answer to the client.
  - period: a week
    scope: Operational metrics and logs
    text: Metrics and logs data are retained for a week.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Tabnine NEVER retains or shares any of your code with third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: No third-party APIs are used.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Tabnine
provenance_date: '2026-11-10'
provider_name: Tabnine
provider_slug: tabnine
slug: tabnine-privacy-policy
source_date: '2026-11-10'
source_filename: tabnine-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://docs.tabnine.com/main/welcome/readme/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Tabnine\naid: tabnine\nurl: https://docs.tabnine.com/main/welcome/readme/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: Lines of code\n- category: device\n  text: User machine details, including CPU type, available processors, and memory\n- category: identifying\n  text: One-way hashed, nonidentifiable data, including user email, hostname, and IP\n- category: behavioral\n  text: Aggregated number of suggestions/completions per programming language\npurposes:\n- purpose: System health and quality of service\n  text: The Tabnine cluster\
  \ collects operational metrics and logs to ensure system health and quality of service.\nretention:\n- scope: Code context\n  period: null\n  text: This context is deleted immediately after the server returns the answer to the client.\n- scope: Operational metrics and logs\n  period: a week\n  text: Metrics and logs data are retained for a week.\nresidency: []\ntransfers:\n- mechanism: other\n  text: No third-party APIs are used.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: Tabnine doesn’t retain any user code beyond the immediate time frame required for inferencing the model.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: Tabnine NEVER retains or shares any of your code with third parties.\n"
source_yaml_url: https://artifacts.apis.io/tabnine/privacy/tabnine-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- sale_or_sharing
summary_line: 10 quoted statements, read from Tabnine's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Developer Tools
- Code Completion
- Self-Hosted
- Enterprise
- Privacy
---
