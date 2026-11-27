---
api_specs:
- filename: counterpartycheck-com-account-api-openapi.yml
  format: yaml
  label: Counterparty Check Account API
  slug: counterpartycheck-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counterpartycheck-com/openapi/counterpartycheck-com-account-api-openapi.yml
- filename: counterpartycheck-com-check-api-openapi.yml
  format: yaml
  label: Counterparty Check Check API
  slug: counterpartycheck-com-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counterpartycheck-com/openapi/counterpartycheck-com-check-api-openapi.yml
- filename: counterpartycheck-com-mcp-api-openapi.yml
  format: yaml
  label: Counterparty Check MCP API
  slug: counterpartycheck-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counterpartycheck-com/openapi/counterpartycheck-com-mcp-api-openapi.yml
- filename: counterpartycheck-com-pricing-api-openapi.yml
  format: yaml
  label: Counterparty Check Pricing API
  slug: counterpartycheck-com-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counterpartycheck-com/openapi/counterpartycheck-com-pricing-api-openapi.yml
- filename: counterpartycheck-com-receipts-api-openapi.yml
  format: yaml
  label: Counterparty Check Receipts API
  slug: counterpartycheck-com-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counterpartycheck-com/openapi/counterpartycheck-com-receipts-api-openapi.yml
- filename: counterpartycheck-com-screen-api-openapi.yml
  format: yaml
  label: Counterparty Check Screen API
  slug: counterpartycheck-com-screen-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counterpartycheck-com/openapi/counterpartycheck-com-screen-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'API keys: stored only as one-way hashes, with their balance and status.'
  - category: financial
    text: 'Purchases: Stripe''s references for card purchases (session and payment IDs, amounts).'
  - category: financial
    text: 'Per-call crypto payments: payment references such as wallet addresses and blockchain transaction IDs, which are public on the blockchain.'
  - category: device
    text: 'Technical data: IP addresses are used briefly in memory for rate limiting and the free daily screen allowance, and are never written to disk.'
  - category: behavioral
    text: 'Usage records: the time of each call, the endpoint, the payment method, the amount charged and the verdict.'
  deletion:
    route: Email chtwebllc@gmail.com
    text: To ask about or delete data associated with your API key, email chtwebllc@gmail.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the check
    text: the names, emails, domains, addresses, bank or wallet details you submit are used to run the check and then discarded.
  - purpose: Rate limiting and free allowance
    text: IP addresses are used briefly in memory for rate limiting and the free daily screen allowance
  - purpose: Accounting, tax and dispute
    text: Usage and purchase records are kept as long as needed for accounting, tax and dispute purposes.
  retention:
  - period: null
    scope: Check request contents
    text: We do not store the contents of check requests
  - period: null
    scope: Usage and purchase records
    text: Usage and purchase records are kept as long as needed for accounting, tax and dispute purposes.
  - period: null
    scope: IP addresses
    text: IP addresses are used briefly in memory for rate limiting and the free daily screen allowance, and are never written to disk.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, use it for advertising, or set tracking cookies.
  subprocessors:
    text: Who processes data for us Stripe (card payments), Coinbase and other x402 facilitators (per-call payments), our hosting provider, and the public data sources queried during a check (domain registries through RDAP, and DNS resolvers operated by Cloudflare and Google).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Counterparty Check
provenance_date: '2026-11-09'
provider_name: Counterparty Check
provider_slug: counterpartycheck-com
slug: counterpartycheck-com-privacy-policy
source_date: '2026-11-09'
source_filename: counterpartycheck-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://counterpartycheck.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Counterparty Check\naid: counterpartycheck-com\nurl: https://counterpartycheck.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'API keys: stored only as one-way hashes, with their balance and status.'\n- category: financial\n  text: 'Purchases: Stripe''s references for card purchases (session and payment IDs, amounts).'\n- category: financial\n  text: 'Per-call crypto payments: payment references such as wallet addresses and blockchain transaction IDs, which\n    are public on the blockchain.'\n- category: device\n  text: 'Technical\
  \ data: IP addresses are used briefly in memory for rate limiting and the free daily screen allowance,\n    and are never written to disk.'\n- category: behavioral\n  text: 'Usage records: the time of each call, the endpoint, the payment method, the amount charged and the verdict.'\npurposes:\n- purpose: Run the check\n  text: the names, emails, domains, addresses, bank or wallet details you submit are used to run the check and then\n    discarded.\n- purpose: Rate limiting and free allowance\n  text: IP addresses are used briefly in memory for rate limiting and the free daily screen allowance\n- purpose: Accounting, tax and dispute\n  text: Usage and purchase records are kept as long as needed for accounting, tax and dispute purposes.\nretention:\n- scope: Check request contents\n  period: null\n  text: We do not store the contents of check requests\n- scope: Usage and purchase records\n  period: null\n  text: Usage and purchase records are kept as long as needed for accounting, tax and\
  \ dispute purposes.\n- scope: IP addresses\n  period: null\n  text: IP addresses are used briefly in memory for rate limiting and the free daily screen allowance, and are never\n    written to disk.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Who processes data for us Stripe (card payments), Coinbase and other x402 facilitators (per-call payments),\n    our hosting provider, and the public data sources queried during a check (domain registries through RDAP, and\n    DNS resolvers operated by Cloudflare and Google).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email chtwebllc@gmail.com\n  text: To ask about or delete data associated with your API key, email chtwebllc@gmail.com .\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, use it for advertising, or set tracking cookies.\n"
source_yaml_url: https://artifacts.apis.io/counterpartycheck-com/privacy/counterpartycheck-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- sale_or_sharing
summary_line: 14 quoted statements, read from Counterparty Check's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Fraud Prevention
- Sanctions Screening
- Compliance
- AI Agents
- MCP
- x402
- Know Your Counterparty
---
