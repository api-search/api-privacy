---
api_specs:
- filename: hasmcp-providers-api-openapi.yml
  format: yaml
  label: HasMCP Providers API
  slug: hasmcp-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasmcp/openapi/hasmcp-providers-api-openapi.yml
- filename: hasmcp-servers-api-openapi.yml
  format: yaml
  label: HasMCP Servers API
  slug: hasmcp-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasmcp/openapi/hasmcp-servers-api-openapi.yml
- filename: hasmcp-variables-api-openapi.yml
  format: yaml
  label: HasMCP Variables API
  slug: hasmcp-variables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hasmcp/openapi/hasmcp-variables-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: We store name, email, and picture URL to ensure consistent account access.
  - category: contact
    text: Email is used as the unique identifier.
  - category: device
    text: Local Storage Used for user preferences and non-sensitive session tokens to enhance performance.
  - category: behavioral
    text: Tool calls count - Token counts (tiktoken) - Response sizes (bytes) - Error rate percentages - Unique User counts
  deletion:
    route: contact email
    text: For data exports or account deletion requests, contact [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account access
    text: We store name, email, and picture URL to ensure consistent account access.
  - purpose: usage statistics
    text: 'We collect aggregated usage statistics to help you manage your mesh:'
  - purpose: defensive rate limiting
    text: IP addresses are used for defensive thresholds only and are not associated with specific User accounts.
  retention:
  - period: 30 days
    scope: account deletion data
    text: Upon account deletion, IAM configs, audit-logs, and secret vault data are purged within 30 days.
  - period: 6 years
    scope: aggregated billing data
    text: Aggregated billing data is retained for 6 years to comply with IRS regulations.
  - period: null
    scope: debug payloads
    text: Request and response payloads in the Debug Console are volatile. They are streamed via secure SSE directly to your browser, never written to disk, and discarded immediately.
  rights:
  - right: data export
    text: For data exports or account deletion requests, contact [email protected] .
  - right: account deletion
    text: For data exports or account deletion requests, contact [email protected] .
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
name: HasMCP
provenance_date: '2026-11-09'
provider_name: HasMCP
provider_slug: hasmcp
slug: hasmcp-privacy-policy
source_date: '2026-11-09'
source_filename: hasmcp-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hasmcp.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: HasMCP\naid: hasmcp\nurl: https://hasmcp.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We store name, email, and picture URL to ensure consistent account access.\n- category: contact\n  text: Email is used as the unique identifier.\n- category: device\n  text: Local Storage Used for user preferences and non-sensitive session tokens to enhance performance.\n- category: behavioral\n  text: Tool calls count - Token counts (tiktoken) - Response sizes (bytes) - Error rate percentages - Unique User\n    counts\npurposes:\n- purpose:\
  \ account access\n  text: We store name, email, and picture URL to ensure consistent account access.\n- purpose: usage statistics\n  text: 'We collect aggregated usage statistics to help you manage your mesh:'\n- purpose: defensive rate limiting\n  text: IP addresses are used for defensive thresholds only and are not associated with specific User accounts.\nretention:\n- scope: account deletion data\n  period: 30 days\n  text: Upon account deletion, IAM configs, audit-logs, and secret vault data are purged within 30 days.\n- scope: aggregated billing data\n  period: 6 years\n  text: Aggregated billing data is retained for 6 years to comply with IRS regulations.\n- scope: debug payloads\n  period: null\n  text: Request and response payloads in the Debug Console are volatile. They are streamed via secure SSE directly\n    to your browser, never written to disk, and discarded immediately.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n \
  \ url: null\n  text: null\ndeletion:\n  route: contact email\n  text: For data exports or account deletion requests, contact [email protected] .\nrights:\n- right: data export\n  text: For data exports or account deletion requests, contact [email protected] .\n- right: account deletion\n  text: For data exports or account deletion requests, contact [email protected] .\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hasmcp/privacy/hasmcp-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 13 quoted statements, read from HasMCP's own page on 2026-11-09.
synthetic: false
tags:
- Company
- No-Code
- Low-Code
- MCP
- API Gateway
---
