---
api_specs:
- filename: craigmbrown-com-a2a-api-openapi.yml
  format: yaml
  label: Craig Brown (BlindOracle) A2a API
  slug: craigmbrown-com-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craigmbrown-com/openapi/craigmbrown-com-a2a-api-openapi.yml
- filename: craigmbrown-com-bundle-api-openapi.yml
  format: yaml
  label: Craig Brown (BlindOracle) Bundle API
  slug: craigmbrown-com-bundle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craigmbrown-com/openapi/craigmbrown-com-bundle-api-openapi.yml
- filename: craigmbrown-com-discovery-api-openapi.yml
  format: yaml
  label: Craig Brown (BlindOracle) Discovery API
  slug: craigmbrown-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craigmbrown-com/openapi/craigmbrown-com-discovery-api-openapi.yml
- filename: craigmbrown-com-execution-api-openapi.yml
  format: yaml
  label: Craig Brown (BlindOracle) Execution API
  slug: craigmbrown-com-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craigmbrown-com/openapi/craigmbrown-com-execution-api-openapi.yml
- filename: craigmbrown-com-identity-api-openapi.yml
  format: yaml
  label: Craig Brown (BlindOracle) Identity API
  slug: craigmbrown-com-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craigmbrown-com/openapi/craigmbrown-com-identity-api-openapi.yml
- filename: craigmbrown-com-payment-api-openapi.yml
  format: yaml
  label: Craig Brown (BlindOracle) Payment API
  slug: craigmbrown-com-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craigmbrown-com/openapi/craigmbrown-com-payment-api-openapi.yml
- filename: craigmbrown-com-provider-api-openapi.yml
  format: yaml
  label: Craig Brown (BlindOracle) Provider API
  slug: craigmbrown-com-provider-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craigmbrown-com/openapi/craigmbrown-com-provider-api-openapi.yml
- filename: craigmbrown-com-utility-api-openapi.yml
  format: yaml
  label: Craig Brown (BlindOracle) Utility API
  slug: craigmbrown-com-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craigmbrown-com/openapi/craigmbrown-com-utility-api-openapi.yml
- filename: craigmbrown-com-verify-us-api-openapi.yml
  format: yaml
  label: Craig Brown (BlindOracle) Verify Us API
  slug: craigmbrown-com-verify-us-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/craigmbrown-com/openapi/craigmbrown-com-verify-us-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: Agent IDs ( X-Agent-Id header values)
  - category: device
    text: API request metadata (IP, user agent, endpoint called)
  - category: financial
    text: On-chain transaction hashes
  - category: other
    text: Commitment hashes (SHA256 values, not the underlying positions)
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: protecting agent operations
    text: How BlindOracle protects agent operations through privacy-by-design architecture.
  retention:
  - period: 90 days
    scope: API logs
    text: API logs 90 days
  - period: Permanent (immutable)
    scope: On-chain data
    text: On-chain data Permanent (immutable)
  - period: As long as relays retain (no deletion guarantee)
    scope: Nostr events
    text: Nostr events As long as relays retain (no deletion guarantee)
  - period: Settlement + 30 days
    scope: Commitment reveals
    text: Commitment reveals Settlement + 30 days
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
name: Craig Brown (BlindOracle)
provenance_date: '2026-11-09'
provider_name: Craig Brown (BlindOracle)
provider_slug: craigmbrown-com
slug: craigmbrown-com-privacy-policy
source_date: '2026-11-09'
source_filename: craigmbrown-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://craigmbrown.com/blindoracle/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Craig Brown (BlindOracle)\naid: craigmbrown-com\nurl: https://craigmbrown.com/blindoracle/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Agent IDs ( X-Agent-Id header values)\n- category: device\n  text: API request metadata (IP, user agent, endpoint called)\n- category: financial\n  text: On-chain transaction hashes\n- category: other\n  text: Commitment hashes (SHA256 values, not the underlying positions)\npurposes:\n- purpose: protecting agent operations\n  text: How BlindOracle protects agent operations through privacy-by-design\
  \ architecture.\nretention:\n- scope: API logs\n  period: 90 days\n  text: API logs 90 days\n- scope: On-chain data\n  period: Permanent (immutable)\n  text: On-chain data Permanent (immutable)\n- scope: Nostr events\n  period: As long as relays retain (no deletion guarantee)\n  text: Nostr events As long as relays retain (no deletion guarantee)\n- scope: Commitment reveals\n  period: Settlement + 30 days\n  text: Commitment reveals Settlement + 30 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/craigmbrown-com/privacy/craigmbrown-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
summary_line: 9 quoted statements, read from Craig Brown (BlindOracle)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Agent Marketplace
- Security Audits
- x402
- Payments
- Blockchain
- MCP
- A2A
- Trust
---
