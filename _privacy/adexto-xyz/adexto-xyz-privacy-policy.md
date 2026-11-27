---
api_specs:
- filename: adexto-xyz-x402-api-openapi.yml
  format: yaml
  label: ADEXTO X402 API
  slug: adexto-xyz-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adexto-xyz/openapi/adexto-xyz-x402-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: It does not ask for your name, email, phone number or identity documents
  - category: location
    text: The raw IP is not stored, but the date is not secret, so treat this as pseudonymous, not anonymous.
  - category: financial
    text: 'The last 1,000 trades read from chain: transaction hash, chain, market, amounts, prices, the trading and receiving addresses, and the time.'
  - category: behavioral
    text: a list of caller hashes, each the first 16 hex characters of a SHA-256 of that day's date and the caller's IP
  - category: communication
    text: 'Telegram alerts. For a group that follows markets with the bot: the chat id and title, the markets it follows, and the Telegram user id of whoever added them.'
  deletion:
    route: Ask us to delete the off-chain records tied to your address, such as a referral handle, through the contact page
    text: Ask us to delete the off-chain records tied to your address, such as a referral handle, through the contact page . We cannot delete or change anything on chain.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: rate limiting
    text: Public endpoints, including the MCP server, the A2A agent and the RPC proxy, count requests per IP to enforce rate limits.
  - purpose: prevent payment reuse
    text: To stop a payment authorization being used twice, it records each payer address with the nonces of its EIP-3009 authorizations until they expire.
  retention:
  - period: 60 days
    scope: MCP usage counts
    text: Kept for 60 days.
  - period: up to six hours
    scope: A2A agent tasks
    text: A2A task keeps what you sent for up to six hours
  - period: up to six hours
    scope: Launch details prepared over MCP
    text: Launch details prepared over MCP are kept in memory for up to six hours until the launch is registered.
  - period: null
    scope: Rate-limit counters
    text: The counters live in the process memory and are lost when it restarts. They are never written to disk.
  rights:
  - right: erasure of off-chain records
    text: Ask us to delete the off-chain records tied to your address, such as a referral handle, through the contact page
  - right: clear browser storage
    text: Clear the browser keys above at any time, or choose Essential only in the storage notice.
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
name: ADEXTO
provenance_date: '2026-11-09'
provider_name: ADEXTO
provider_slug: adexto-xyz
slug: adexto-xyz-privacy-policy
source_date: '2026-11-09'
source_filename: adexto-xyz-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://adexto.xyz/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ADEXTO\naid: adexto-xyz\nurl: https://adexto.xyz/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: It does not ask for your name, email, phone number or identity documents\n- category: location\n  text: The raw IP is not stored, but the date is not secret, so treat this as pseudonymous, not anonymous.\n- category: financial\n  text: 'The last 1,000 trades read from chain: transaction hash, chain, market, amounts, prices, the trading and\n    receiving addresses, and the time.'\n- category: behavioral\n  text: a list of caller hashes,\
  \ each the first 16 hex characters of a SHA-256 of that day's date and the caller's\n    IP\n- category: communication\n  text: 'Telegram alerts. For a group that follows markets with the bot: the chat id and title, the markets it follows,\n    and the Telegram user id of whoever added them.'\npurposes:\n- purpose: rate limiting\n  text: Public endpoints, including the MCP server, the A2A agent and the RPC proxy, count requests per IP to enforce\n    rate limits.\n- purpose: prevent payment reuse\n  text: To stop a payment authorization being used twice, it records each payer address with the nonces of its EIP-3009\n    authorizations until they expire.\nretention:\n- scope: MCP usage counts\n  period: 60 days\n  text: Kept for 60 days.\n- scope: A2A agent tasks\n  period: up to six hours\n  text: A2A task keeps what you sent for up to six hours\n- scope: Launch details prepared over MCP\n  period: up to six hours\n  text: Launch details prepared over MCP are kept in memory for up to six\
  \ hours until the launch is registered.\n- scope: Rate-limit counters\n  period: null\n  text: The counters live in the process memory and are lost when it restarts. They are never written to disk.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Ask us to delete the off-chain records tied to your address, such as a referral handle, through the contact\n    page\n  text: Ask us to delete the off-chain records tied to your address, such as a referral handle, through the contact\n    page . We cannot delete or change anything on chain.\nrights:\n- right: erasure of off-chain records\n  text: Ask us to delete the off-chain records tied to your address, such as a referral handle, through the contact\n    page\n- right: clear browser storage\n  text: Clear the browser keys above at any time, or choose Essential only in the storage notice.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adexto-xyz/privacy/adexto-xyz-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 14 quoted statements, read from ADEXTO's own page on 2026-11-09.
synthetic: false
tags:
- DeFi
- Token Launch
- Bonding Curve
- AI Agents
- Blockchain
---
