---
api_specs:
- filename: emission-factors-com-bulk-api-openapi.yml
  format: yaml
  label: emission-factors-com Bulk API
  slug: emission-factors-com-bulk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-bulk-api-openapi.yml
- filename: emission-factors-com-calculate-api-openapi.yml
  format: yaml
  label: emission-factors-com Calculate API
  slug: emission-factors-com-calculate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-calculate-api-openapi.yml
- filename: emission-factors-com-cleanest-hours-api-openapi.yml
  format: yaml
  label: emission-factors-com Cleanest Hours API
  slug: emission-factors-com-cleanest-hours-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-cleanest-hours-api-openapi.yml
- filename: emission-factors-com-compare-api-openapi.yml
  format: yaml
  label: emission-factors-com Compare API
  slug: emission-factors-com-compare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-compare-api-openapi.yml
- filename: emission-factors-com-fuel-emissions-api-openapi.yml
  format: yaml
  label: emission-factors-com Fuel Emissions API
  slug: emission-factors-com-fuel-emissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-fuel-emissions-api-openapi.yml
- filename: emission-factors-com-health-api-openapi.yml
  format: yaml
  label: emission-factors-com Health API
  slug: emission-factors-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-health-api-openapi.yml
- filename: emission-factors-com-intensity-api-openapi.yml
  format: yaml
  label: emission-factors-com Intensity API
  slug: emission-factors-com-intensity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-intensity-api-openapi.yml
- filename: emission-factors-com-lookup-api-openapi.yml
  format: yaml
  label: emission-factors-com Lookup API
  slug: emission-factors-com-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-lookup-api-openapi.yml
- filename: emission-factors-com-mcp-api-openapi.yml
  format: yaml
  label: emission-factors-com MCP API
  slug: emission-factors-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-mcp-api-openapi.yml
- filename: emission-factors-com-methodology-api-openapi.yml
  format: yaml
  label: emission-factors-com Methodology API
  slug: emission-factors-com-methodology-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-methodology-api-openapi.yml
- filename: emission-factors-com-openapi-json-api-openapi.yml
  format: yaml
  label: emission-factors-com Openapi.json API
  slug: emission-factors-com-openapi-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-openapi-json-api-openapi.yml
- filename: emission-factors-com-plant-emissions-api-openapi.yml
  format: yaml
  label: emission-factors-com Plant Emissions API
  slug: emission-factors-com-plant-emissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-plant-emissions-api-openapi.yml
- filename: emission-factors-com-rate-api-openapi.yml
  format: yaml
  label: emission-factors-com Rate API
  slug: emission-factors-com-rate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-rate-api-openapi.yml
- filename: emission-factors-com-status-api-openapi.yml
  format: yaml
  label: emission-factors-com Status API
  slug: emission-factors-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-status-api-openapi.yml
- filename: emission-factors-com-utility-rate-api-openapi.yml
  format: yaml
  label: emission-factors-com Utility Rate API
  slug: emission-factors-com-utility-rate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/emission-factors-com/openapi/emission-factors-com-utility-rate-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: IP address, user-agent, request path and query (for example the ZIP code you looked up), status code and timing.
  - category: location
    text: the coordinates you send to /api/lookup/by-coordinates are forwarded to it
  deletion:
    route: email to the address given on the page
    text: Questions or deletion requests
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Rate limiting, debugging, and aggregate usage statistics
    text: Rate limiting, debugging, and aggregate usage statistics.
  retention:
  - period: up to one hour
    scope: Rate-limit counters
    text: held in memory for up to one hour to enforce the per-IP rate limit
  - period: null
    scope: CSV uploads to /api/bulk
    text: CSV files uploaded to /api/bulk are processed in memory and not stored
  - period: null
    scope: Request logs
    text: Request logs are kept by Railway under its log-retention policy and are not backed up elsewhere.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell or share your data
  subprocessors:
    text: Cloudflare - DNS, TLS and request proxying
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: emission-factors-com
provenance_date: '2026-11-09'
provider_name: emission-factors-com
provider_slug: emission-factors-com
slug: emission-factors-com-privacy-policy
source_date: '2026-11-09'
source_filename: emission-factors-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://emission-factors.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: emission-factors-com\naid: emission-factors-com\nurl: https://emission-factors.com/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: IP address, user-agent, request path and query (for example the ZIP code you looked up), status code and\n    timing.\n- category: location\n  text: the coordinates you send to /api/lookup/by-coordinates are forwarded to it\npurposes:\n- purpose: Rate limiting, debugging, and aggregate usage statistics\n  text: Rate limiting, debugging, and aggregate usage statistics.\nretention:\n- scope: Rate-limit\
  \ counters\n  period: up to one hour\n  text: held in memory for up to one hour to enforce the per-IP rate limit\n- scope: CSV uploads to /api/bulk\n  period: null\n  text: CSV files uploaded to /api/bulk are processed in memory and not stored\n- scope: Request logs\n  period: null\n  text: Request logs are kept by Railway under its log-retention policy and are not backed up elsewhere.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare - DNS, TLS and request proxying\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to the address given on the page\n  text: Questions or deletion requests\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell or share your data\n"
source_yaml_url: https://artifacts.apis.io/emission-factors-com/privacy/emission-factors-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- sale_or_sharing
summary_line: 9 quoted statements, read from emission-factors-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Emission
- Carbon
- Energy
- Sustainability
---
