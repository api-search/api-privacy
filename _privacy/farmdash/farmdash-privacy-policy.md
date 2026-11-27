---
api_specs:
- filename: farmdash-account-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Account API
  slug: farmdash-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-account-api-openapi.yml
- filename: farmdash-autopilot-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Autopilot API
  slug: farmdash-autopilot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-autopilot-api-openapi.yml
- filename: farmdash-delegation-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Delegation API
  slug: farmdash-delegation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-delegation-api-openapi.yml
- filename: farmdash-execution-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Execution API
  slug: farmdash-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-execution-api-openapi.yml
- filename: farmdash-executionauthority-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Execution Authority API
  slug: farmdash-executionauthority-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-executionauthority-api-openapi.yml
- filename: farmdash-history-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub History API
  slug: farmdash-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-history-api-openapi.yml
- filename: farmdash-intelligence-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Intelligence API
  slug: farmdash-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-intelligence-api-openapi.yml
- filename: farmdash-planning-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Planning API
  slug: farmdash-planning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-planning-api-openapi.yml
- filename: farmdash-proof-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Proof API
  slug: farmdash-proof-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-proof-api-openapi.yml
- filename: farmdash-reputation-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Reputation API
  slug: farmdash-reputation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-reputation-api-openapi.yml
- filename: farmdash-research-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Research API
  slug: farmdash-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-research-api-openapi.yml
- filename: farmdash-risk-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Risk API
  slug: farmdash-risk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-risk-api-openapi.yml
- filename: farmdash-session-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Session API
  slug: farmdash-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-session-api-openapi.yml
- filename: farmdash-strategy-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Strategy API
  slug: farmdash-strategy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-strategy-api-openapi.yml
- filename: farmdash-swap-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Swap API
  slug: farmdash-swap-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-swap-api-openapi.yml
- filename: farmdash-wallet-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Wallet API
  slug: farmdash-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-wallet-api-openapi.yml
- filename: farmdash-agent-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Agent API
  slug: farmdash-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-agent-api-openapi.yml
- filename: farmdash-payments-api-openapi.yml
  format: yaml
  label: FarmDash Agent Hub Payments API
  slug: farmdash-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/farmdash/openapi/farmdash-payments-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: We do not collect, request, or store off-chain personally identifiable information such as your legal name, physical address, email address, phone number, government identity number
  - category: identifying
    text: Your public account identity across FarmDash is strictly your public cryptographic wallet address (e.g. 0x... on EVM or base58 on Solana).
  - category: device
    text: we temporarily process incoming IP addresses and user-agent strings.
  - category: behavioral
    text: Separate first-party acquisition measurement records a random, non-fingerprint-derived correlation identifier and bounded landing, navigation and product-value events
  - category: financial
    text: We persist on-chain transaction hashes and payment receipts (such as USDC subscription payments and x402 micropayments)
  deletion:
    route: Disconnect wallet and clear browser local storage
    text: You can terminate your local session at any time simply by disconnecting your wallet and clearing your browser local storage.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: DeFi intelligence and wallet context
    text: To deliver DeFi intelligence, wallet context, and verifiable transaction workflows, FarmDash processes and selectively persists the following technical information
  - purpose: Security and DDoS protection
    text: To protect the Signal Architect API, x402 TollBooth, and frontend against distributed denial-of-service (DDoS) and bot flooding, we temporarily process incoming IP addresses and user-agent strings.
  - purpose: Payment verification
    text: to verify prepaid activations and prevent replay or double-spending.
  retention:
  - period: up to 30 days
    scope: Acquisition identifier
    text: A random identifier stored in browser local storage is valid for up to 30 days
  - period: null
    scope: Installation analytics
    text: Current installation-attribution analytics do not presently have automatic expiry; retention is operator-managed until automated retention is implemented.
  - period: null
    scope: Historical consent and payment hashes
    text: Cryptographic legal consent signatures and on-chain payment hashes are retained in the database solely as immutable compliance evidence
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Your browsing behavior across FarmDash is never sold, rented, or shared.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FarmDash.one
provenance_date: '2026-11-09'
provider_name: FarmDash.one
provider_slug: farmdash
slug: farmdash-privacy-policy
source_date: '2026-11-09'
source_filename: farmdash-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.farmdash.one/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FarmDash.one\naid: farmdash\nurl: https://www.farmdash.one/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We do not collect, request, or store off-chain personally identifiable information such as your legal name,\n    physical address, email address, phone number, government identity number\n- category: identifying\n  text: Your public account identity across FarmDash is strictly your public cryptographic wallet address (e.g.\n    0x... on EVM or base58 on Solana).\n- category: device\n  text: we temporarily process incoming IP\
  \ addresses and user-agent strings.\n- category: behavioral\n  text: Separate first-party acquisition measurement records a random, non-fingerprint-derived correlation identifier\n    and bounded landing, navigation and product-value events\n- category: financial\n  text: We persist on-chain transaction hashes and payment receipts (such as USDC subscription payments and x402\n    micropayments)\npurposes:\n- purpose: DeFi intelligence and wallet context\n  text: To deliver DeFi intelligence, wallet context, and verifiable transaction workflows, FarmDash processes and\n    selectively persists the following technical information\n- purpose: Security and DDoS protection\n  text: To protect the Signal Architect API, x402 TollBooth, and frontend against distributed denial-of-service\n    (DDoS) and bot flooding, we temporarily process incoming IP addresses and user-agent strings.\n- purpose: Payment verification\n  text: to verify prepaid activations and prevent replay or double-spending.\n\
  retention:\n- scope: Acquisition identifier\n  period: up to 30 days\n  text: A random identifier stored in browser local storage is valid for up to 30 days\n- scope: Installation analytics\n  period: null\n  text: Current installation-attribution analytics do not presently have automatic expiry; retention is operator-managed\n    until automated retention is implemented.\n- scope: Historical consent and payment hashes\n  period: null\n  text: Cryptographic legal consent signatures and on-chain payment hashes are retained in the database solely as\n    immutable compliance evidence\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Disconnect wallet and clear browser local storage\n  text: You can terminate your local session at any time simply by disconnecting your wallet and clearing your browser\n    local storage.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: Your browsing\
  \ behavior across FarmDash is never sold, rented, or shared.\n"
source_yaml_url: https://artifacts.apis.io/farmdash/privacy/farmdash-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 13 quoted statements, read from FarmDash.one's own page on 2026-11-09.
synthetic: false
tags:
- DeFi
- DeFAI
- AI Agents
- MCP
- OpenAPI
- x402
- Blockchain
- Cryptocurrency
- airdrop tracking
- Developer Tools
- Agent Readiness
- Machine Payments
- Hyperliquid
- Wallet Intelligence
- zero custody
---
