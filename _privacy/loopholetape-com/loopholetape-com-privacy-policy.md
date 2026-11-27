---
api_specs:
- filename: loopholetape-com-discovery-api-openapi.yml
  format: yaml
  label: loopholetape-com Discovery API
  slug: loopholetape-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loopholetape-com/openapi/loopholetape-com-discovery-api-openapi.yml
- filename: loopholetape-com-free-api-openapi.yml
  format: yaml
  label: loopholetape-com Free API
  slug: loopholetape-com-free-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loopholetape-com/openapi/loopholetape-com-free-api-openapi.yml
- filename: loopholetape-com-paid-api-openapi.yml
  format: yaml
  label: loopholetape-com Paid API
  slug: loopholetape-com-paid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loopholetape-com/openapi/loopholetape-com-paid-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Every request records: time, client IP address, user agent'
  - category: financial
    text: A settlement records the payer address, network, transaction id, amount, route and outcome.
  - category: behavioral
    text: MCP calls also record the JSON-RPC method, the tool name and its arguments (each cut to 80 characters).
  - category: communication
    text: keeps the delivery endpoint you give (a Discord webhook URL, or a Telegram bot token and chat id) encrypted at rest
  deletion:
    route: subscription end (webhook endpoint)
    text: it is deleted when the subscription ends
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: abuse control, service statistics, learning which routes callers ask for
    text: 'Uses: abuse control (rate limits, replay refusal), service statistics, and learning which routes callers ask for.'
  residency:
  - region: service's own server
    text: Records stay on the service's own server
  retention:
  - period: ten-minute retry window
    scope: compact check rows
    text: keep a SHA-256 hash of the signed payment with the request and the response for the ten-minute retry window
  - period: when the subscription ends
    scope: webhook registration
    text: it is deleted when the subscription ends
  - period: no fixed deletion schedule yet
    scope: all records
    text: there is no fixed deletion schedule yet
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Nothing we record is sold or shared.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: loopholetape-com
provenance_date: '2026-11-09'
provider_name: loopholetape-com
provider_slug: loopholetape-com
slug: loopholetape-com-privacy-policy
source_date: '2026-11-09'
source_filename: loopholetape-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://loopholetape.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: loopholetape-com\naid: loopholetape-com\nurl: https://loopholetape.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Every request records: time, client IP address, user agent'\n- category: financial\n  text: A settlement records the payer address, network, transaction id, amount, route and outcome.\n- category: behavioral\n  text: MCP calls also record the JSON-RPC method, the tool name and its arguments (each cut to 80 characters).\n- category: communication\n  text: keeps the delivery endpoint you give (a Discord webhook URL,\
  \ or a Telegram bot token and chat id) encrypted\n    at rest\npurposes:\n- purpose: abuse control, service statistics, learning which routes callers ask for\n  text: 'Uses: abuse control (rate limits, replay refusal), service statistics, and learning which routes callers\n    ask for.'\nretention:\n- scope: compact check rows\n  period: ten-minute retry window\n  text: keep a SHA-256 hash of the signed payment with the request and the response for the ten-minute retry window\n- scope: webhook registration\n  period: when the subscription ends\n  text: it is deleted when the subscription ends\n- scope: all records\n  period: no fixed deletion schedule yet\n  text: there is no fixed deletion schedule yet\nresidency:\n- region: service's own server\n  text: Records stay on the service's own server\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: subscription end (webhook endpoint)\n  text: it is deleted when\
  \ the subscription ends\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: Nothing we record is sold or shared.\n"
source_yaml_url: https://artifacts.apis.io/loopholetape-com/privacy/loopholetape-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- sale_or_sharing
summary_line: 11 quoted statements, read from loopholetape-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Solana
- Risk Management
---
