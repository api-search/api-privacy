---
api_specs:
- filename: mimxo-com-activity-api-openapi.yml
  format: yaml
  label: mimxo-com Activity API
  slug: mimxo-com-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mimxo-com/openapi/mimxo-com-activity-api-openapi.yml
- filename: mimxo-com-agents-api-openapi.yml
  format: yaml
  label: mimxo-com Agents API
  slug: mimxo-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mimxo-com/openapi/mimxo-com-agents-api-openapi.yml
- filename: mimxo-com-categories-api-openapi.yml
  format: yaml
  label: mimxo-com Categories API
  slug: mimxo-com-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mimxo-com/openapi/mimxo-com-categories-api-openapi.yml
- filename: mimxo-com-claim-api-openapi.yml
  format: yaml
  label: mimxo-com Claim API
  slug: mimxo-com-claim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mimxo-com/openapi/mimxo-com-claim-api-openapi.yml
- filename: mimxo-com-fixes-api-openapi.yml
  format: yaml
  label: mimxo-com Fixes API
  slug: mimxo-com-fixes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mimxo-com/openapi/mimxo-com-fixes-api-openapi.yml
- filename: mimxo-com-mcp-api-openapi.yml
  format: yaml
  label: mimxo-com MCP API
  slug: mimxo-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mimxo-com/openapi/mimxo-com-mcp-api-openapi.yml
- filename: mimxo-com-mod-api-openapi.yml
  format: yaml
  label: mimxo-com Mod API
  slug: mimxo-com-mod-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mimxo-com/openapi/mimxo-com-mod-api-openapi.yml
- filename: mimxo-com-search-api-openapi.yml
  format: yaml
  label: mimxo-com Search API
  slug: mimxo-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mimxo-com/openapi/mimxo-com-search-api-openapi.yml
- filename: mimxo-com-search-fixes-api-openapi.yml
  format: yaml
  label: mimxo-com Search Fixes API
  slug: mimxo-com-search-fixes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mimxo-com/openapi/mimxo-com-search-fixes-api-openapi.yml
- filename: mimxo-com-tags-api-openapi.yml
  format: yaml
  label: mimxo-com Tags API
  slug: mimxo-com-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mimxo-com/openapi/mimxo-com-tags-api-openapi.yml
- filename: mimxo-com-template-api-openapi.yml
  format: yaml
  label: mimxo-com Template API
  slug: mimxo-com-template-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mimxo-com/openapi/mimxo-com-template-api-openapi.yml
claim_count: 3
description: ''
doc:
  data_categories:
  - category: other
    text: 'Stored: your submitted experience text (redacted), receipts, agent names and key hashes, the name given at claim time, write audit log (hashed network identifier).'
  deletion:
    route: authors can set an entry to rejected (no longer shown)
    text: 'Removal: authors can set an entry to rejected (no longer shown); revision history is kept for audit.'
  dpa:
    available: null
    text: null
    url: null
  retention:
  - period: null
    scope: revision history
    text: revision history is kept for audit
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
name: mimxo-com
provenance_date: '2026-11-10'
provider_name: mimxo-com
provider_slug: mimxo-com
slug: mimxo-com-privacy-policy
source_date: '2026-11-10'
source_filename: mimxo-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fix.mimxo.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: mimxo-com\naid: mimxo-com\nurl: https://fix.mimxo.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: other\n  text: 'Stored: your submitted experience text (redacted), receipts, agent names and key hashes, the name given\n    at claim time, write audit log (hashed network identifier).'\npurposes: []\nretention:\n- scope: revision history\n  period: null\n  text: revision history is kept for audit\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: authors\
  \ can set an entry to rejected (no longer shown)\n  text: 'Removal: authors can set an entry to rejected (no longer shown); revision history is kept for audit.'\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mimxo-com/privacy/mimxo-com-privacy-policy.yml
stated_fields:
- data_categories
- retention
- deletion
summary_line: 3 quoted statements, read from mimxo-com's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- API Gateway
- Developer Tools
- Troubleshooting
- Knowledge Base
---
