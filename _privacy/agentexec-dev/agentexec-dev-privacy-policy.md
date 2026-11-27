---
claim_count: 6
description: ''
doc:
  data_categories:
  - category: identifying
    text: Public wallet addresses and transaction payload hashes are processed for RPC pre-flight simulations and EIP-3009 x402 payment validation.
  - category: device
    text: Standard HTTP logs (IP addresses, request status codes, user-agent headers) and optional API key identifiers may be processed for rate-limiting, security auditing, and DDoS defense.
  - category: financial
    text: On-chain USDC payer addresses, authorization nonces, and settlement transaction hashes may be retained with those logs.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: RPC pre-flight simulations and x402 payment validation
    text: Public wallet addresses and transaction payload hashes are processed for RPC pre-flight simulations and EIP-3009 x402 payment validation.
  - purpose: rate-limiting, security auditing, DDoS defense
    text: may be processed for rate-limiting, security auditing, and DDoS defense.
  retention:
  - period: null
    scope: On-chain USDC payer addresses, authorization nonces, settlement transaction hashes
    text: may be retained with those logs.
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
name: AgentExec
provenance_date: '2026-11-09'
provider_name: AgentExec
provider_slug: agentexec-dev
slug: agentexec-dev-privacy-policy
source_date: '2026-11-09'
source_filename: agentexec-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentexec.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentExec\naid: agentexec-dev\nurl: https://agentexec.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Public wallet addresses and transaction payload hashes are processed for RPC pre-flight simulations and\n    EIP-3009 x402 payment validation.\n- category: device\n  text: Standard HTTP logs (IP addresses, request status codes, user-agent headers) and optional API key identifiers\n    may be processed for rate-limiting, security auditing, and DDoS defense.\n- category: financial\n  text: On-chain USDC payer addresses, authorization\
  \ nonces, and settlement transaction hashes may be retained with\n    those logs.\npurposes:\n- purpose: RPC pre-flight simulations and x402 payment validation\n  text: Public wallet addresses and transaction payload hashes are processed for RPC pre-flight simulations and\n    EIP-3009 x402 payment validation.\n- purpose: rate-limiting, security auditing, DDoS defense\n  text: may be processed for rate-limiting, security auditing, and DDoS defense.\nretention:\n- scope: On-chain USDC payer addresses, authorization nonces, settlement transaction hashes\n  period: null\n  text: may be retained with those logs.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentexec-dev/privacy/agentexec-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
summary_line: 6 quoted statements, read from AgentExec's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Blockchain
- WebMCP
- Base
- Finance
---
