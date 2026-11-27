---
api_specs:
- filename: fluentedi-compute-api-openapi.yml
  format: yaml
  label: FluentEDI Compute API
  slug: fluentedi-compute-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluentedi/openapi/fluentedi-compute-api-openapi.yml
- filename: fluentedi-crypto-api-openapi.yml
  format: yaml
  label: FluentEDI Crypto API
  slug: fluentedi-crypto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluentedi/openapi/fluentedi-crypto-api-openapi.yml
- filename: fluentedi-data-api-openapi.yml
  format: yaml
  label: FluentEDI Data API
  slug: fluentedi-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluentedi/openapi/fluentedi-data-api-openapi.yml
- filename: fluentedi-doc-api-openapi.yml
  format: yaml
  label: FluentEDI Doc API
  slug: fluentedi-doc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluentedi/openapi/fluentedi-doc-api-openapi.yml
- filename: fluentedi-edi-api-openapi.yml
  format: yaml
  label: FluentEDI Edi API
  slug: fluentedi-edi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluentedi/openapi/fluentedi-edi-api-openapi.yml
- filename: fluentedi-meta-api-openapi.yml
  format: yaml
  label: FluentEDI Meta API
  slug: fluentedi-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluentedi/openapi/fluentedi-meta-api-openapi.yml
- filename: fluentedi-schedule-api-openapi.yml
  format: yaml
  label: FluentEDI Schedule API
  slug: fluentedi-schedule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluentedi/openapi/fluentedi-schedule-api-openapi.yml
- filename: fluentedi-text-api-openapi.yml
  format: yaml
  label: FluentEDI Text API
  slug: fluentedi-text-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluentedi/openapi/fluentedi-text-api-openapi.yml
- filename: fluentedi-time-api-openapi.yml
  format: yaml
  label: FluentEDI Time API
  slug: fluentedi-time-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluentedi/openapi/fluentedi-time-api-openapi.yml
- filename: fluentedi-web-api-openapi.yml
  format: yaml
  label: FluentEDI Web API
  slug: fluentedi-web-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fluentedi/openapi/fluentedi-web-api-openapi.yml
claim_count: 4
description: ''
doc:
  data_categories:
  - category: behavioral
    text: the tool name the transport (rest, mcp or batch) whether the call succeeded, and the error code if not how long it took the country and edge location the request arrived at the user-agent string
  deletion:
    route: null
    text: discarded when the request ends
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: understand which tools are worth maintaining
    text: Ordinary access telemetry, kept to understand which tools are worth maintaining
  retention:
  - period: null
    scope: request and response bodies
    text: Request and response bodies are processed in memory and discarded when the request ends.
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
name: FluentEDI
provenance_date: '2026-11-09'
provider_name: FluentEDI
provider_slug: fluentedi
slug: fluentedi-privacy-policy
source_date: '2026-11-09'
source_filename: fluentedi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fluentedi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FluentEDI\naid: fluentedi\nurl: https://fluentedi.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: the tool name the transport (rest, mcp or batch) whether the call succeeded, and the error code if not how\n    long it took the country and edge location the request arrived at the user-agent string\npurposes:\n- purpose: understand which tools are worth maintaining\n  text: Ordinary access telemetry, kept to understand which tools are worth maintaining\nretention:\n- scope: request and response bodies\n  period: null\n  text: Request\
  \ and response bodies are processed in memory and discarded when the request ends.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: discarded when the request ends\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fluentedi/privacy/fluentedi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 4 quoted statements, read from FluentEDI's own page on 2026-11-09.
synthetic: false
tags:
- EDI
- X12
- Retail EDI
- AI Agents
- MCP
- Developer Tools
- JSON
- Cryptography
- Data Validation
- Supply Chain
---
