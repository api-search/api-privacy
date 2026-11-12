---
api_specs:
- filename: coudrebros-eu-auth-api-openapi.yml
  format: yaml
  label: Coudre Bros. Auth API
  slug: coudrebros-eu-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-auth-api-openapi.yml
- filename: coudrebros-eu-health-api-openapi.yml
  format: yaml
  label: Coudre Bros. Health API
  slug: coudrebros-eu-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-health-api-openapi.yml
- filename: coudrebros-eu-mint-api-openapi.yml
  format: yaml
  label: Coudre Bros. Mint API
  slug: coudrebros-eu-mint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-mint-api-openapi.yml
- filename: coudrebros-eu-notary-api-openapi.yml
  format: yaml
  label: Coudre Bros. Notary API
  slug: coudrebros-eu-notary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-notary-api-openapi.yml
- filename: coudrebros-eu-payment-api-openapi.yml
  format: yaml
  label: Coudre Bros. Payment API
  slug: coudrebros-eu-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-payment-api-openapi.yml
- filename: coudrebros-eu-prerequisites-api-openapi.yml
  format: yaml
  label: Coudre Bros. Prerequisites API
  slug: coudrebros-eu-prerequisites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coudrebros-eu/openapi/coudrebros-eu-prerequisites-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: Cardano address provided at registration (POST /register) — this is a public blockchain identifier.
  - category: device
    text: IP address (server access logs) — retained for 14 days, then automatically deleted.
  - category: identifying
    text: API key (generated, bound to the registered address) — remains active indefinitely until manually revoked by the operator; there is currently no automatic expiration.
  deletion:
    route: null
    text: You have the right to access, rectify, or erase your data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operating and securing the API
    text: Operating and securing the API (rate limiting, abuse protection)
  - purpose: Issuing and managing API keys
    text: Issuing and managing API keys bound to a Cardano address
  retention:
  - period: 14 days
    scope: Server access logs
    text: 'Server access logs (containing IP addresses): 14 days.'
  - period: null
    scope: API keys and bound Cardano address
    text: 'API keys and their bound Cardano address: kept until the key is revoked or the service is discontinued.'
  rights:
  - right: access, rectify, erase
    text: You have the right to access, rectify, or erase your data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: Data is not shared with third parties beyond what is technically necessary to operate the service (e.g. hosting).
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Coudre Bros.
provenance_date: '2026-11-09'
provider_name: Coudre Bros.
provider_slug: coudrebros-eu
slug: coudrebros-eu-privacy-policy
source_date: '2026-11-09'
source_filename: coudrebros-eu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.coudrebros.eu/nft_api/#privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Coudre Bros.\naid: coudrebros-eu\nurl: https://www.coudrebros.eu/nft_api/#privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Cardano address provided at registration (POST /register) — this is a public blockchain identifier.\n- category: device\n  text: IP address (server access logs) — retained for 14 days, then automatically deleted.\n- category: identifying\n  text: API key (generated, bound to the registered address) — remains active indefinitely until manually revoked\n    by the operator; there is currently no automatic expiration.\n\
  purposes:\n- purpose: Operating and securing the API\n  text: Operating and securing the API (rate limiting, abuse protection)\n- purpose: Issuing and managing API keys\n  text: Issuing and managing API keys bound to a Cardano address\nretention:\n- scope: Server access logs\n  period: 14 days\n  text: 'Server access logs (containing IP addresses): 14 days.'\n- scope: API keys and bound Cardano address\n  period: null\n  text: 'API keys and their bound Cardano address: kept until the key is revoked or the service is discontinued.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: You have the right to access, rectify, or erase your data.\nrights:\n- right: access, rectify, erase\n  text: You have the right to access, rectify, or erase your data.\nsale_or_sharing:\n  stance: unstated\n  text: Data is not shared with third parties beyond what is technically necessary to operate the\
  \ service (e.g.\n    hosting).\n"
source_yaml_url: https://artifacts.apis.io/coudrebros-eu/privacy/coudrebros-eu-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 9 quoted statements, read from Coudre Bros.'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cardano
- Blockchain
- Stake Pool
- NFT
- Minting
- Notary
- AI Agents
- MCP
- Web3
---
