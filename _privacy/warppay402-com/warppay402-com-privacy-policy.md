---
api_specs:
- filename: warppay402-com-feeds-api-openapi.yml
  format: yaml
  label: WarpPay402 Studio Feeds API
  slug: warppay402-com-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warppay402-com/openapi/warppay402-com-feeds-api-openapi.yml
- filename: warppay402-com-public-data-feed-api-openapi.yml
  format: yaml
  label: WarpPay402 Studio Public Data Feed API
  slug: warppay402-com-public-data-feed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warppay402-com/openapi/warppay402-com-public-data-feed-api-openapi.yml
- filename: warppay402-com-tools-api-openapi.yml
  format: yaml
  label: WarpPay402 Studio Tools API
  slug: warppay402-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warppay402-com/openapi/warppay402-com-tools-api-openapi.yml
claim_count: 8
description: ''
doc:
  data_categories:
  - category: other
    text: 'API and MCP Query Inputs: To execute requested agent services (such as web scraping, PDF document text extraction, structured JSON parsing, real estate valuation, and smart contract verification), our gateway processes the parameter inputs passed in your HTTP and JSON-RPC payloads'
  - category: other
    text: All transaction hashes, interacting wallet addresses, block numbers, and cryptographic signatures constitute public blockchain records.
  - category: device
    text: incoming connections temporarily generate standard edge logs (IP addresses, Cloudflare Ray IDs, User-Agent strings, and request timestamps)
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Real-time execution
    text: Target parameters and prompt inputs are evaluated in volatile memory solely to return output payloads directly to the calling client or autonomous agent.
  - purpose: Security and rate limiting
    text: to protect our cluster against malicious traffic and run real-time rate limiters
  - purpose: Sanctions and AML compliance
    text: Every incoming payment signature on x402 endpoints and every sender address submitted to the ERC-4337 / ERC-7677 paymaster RPC is evaluated using cryptographic set-membership checks
  retention:
  - period: 5 to 60 seconds
    scope: Input data in memory
    text: Certain public attestation feeds, oracle spot data, and wallet solvency checks are stored in volatile memory caches (typically 5 to 60 seconds)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, license, or monetize user query inputs, transaction histories, or agent payloads to data brokers, commercial advertisers, or analytical third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: WarpPay402 Studio
provenance_date: '2026-11-10'
provider_name: WarpPay402 Studio
provider_slug: warppay402-com
slug: warppay402-com-privacy-policy
source_date: '2026-11-10'
source_filename: warppay402-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.warppay402.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: WarpPay402 Studio\naid: warppay402-com\nurl: https://www.warppay402.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: other\n  text: 'API and MCP Query Inputs: To execute requested agent services (such as web scraping, PDF document text\n    extraction, structured JSON parsing, real estate valuation, and smart contract verification), our gateway processes\n    the parameter inputs passed in your HTTP and JSON-RPC payloads'\n- category: other\n  text: All transaction hashes, interacting wallet addresses, block numbers, and cryptographic signatures\
  \ constitute\n    public blockchain records.\n- category: device\n  text: incoming connections temporarily generate standard edge logs (IP addresses, Cloudflare Ray IDs, User-Agent\n    strings, and request timestamps)\npurposes:\n- purpose: Real-time execution\n  text: Target parameters and prompt inputs are evaluated in volatile memory solely to return output payloads directly\n    to the calling client or autonomous agent.\n- purpose: Security and rate limiting\n  text: to protect our cluster against malicious traffic and run real-time rate limiters\n- purpose: Sanctions and AML compliance\n  text: Every incoming payment signature on x402 endpoints and every sender address submitted to the ERC-4337 /\n    ERC-7677 paymaster RPC is evaluated using cryptographic set-membership checks\nretention:\n- scope: Input data in memory\n  period: 5 to 60 seconds\n  text: Certain public attestation feeds, oracle spot data, and wallet solvency checks are stored in volatile memory\n    caches (typically\
  \ 5 to 60 seconds)\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, license, or monetize user query inputs, transaction histories, or agent payloads to\n    data brokers, commercial advertisers, or analytical third parties.\n"
source_yaml_url: https://artifacts.apis.io/warppay402-com/privacy/warppay402-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- sale_or_sharing
summary_line: 8 quoted statements, read from WarpPay402 Studio's own page on 2026-11-10.
synthetic: false
tags:
- x402
- Micropayments
- AI Agents
- MCP
- A2A
- Agent-Native
- Web Scraping
- Data Extraction
- Blockchain
- DeFi
- Base
- Solana
- Smart Contracts
- Data Feed
- Developer Tools
---
