---
api_specs:
- filename: algovault-com-openapi-generated.yml
  format: yaml
  label: AlgoVault API
  slug: algovault-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/algovault-com/openapi/_ae-authored/algovault-com-openapi-generated.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personal names, emails, or account information (unless you subscribe via Stripe)
  - category: device
    text: SHA-256 hash of your IP address (we never store raw IPs)
  - category: financial
    text: We store your API key and subscription status. We do not store credit card numbers.
  - category: behavioral
    text: Tool called (e.g., get_trade_call, scan_funding_arb)
  deletion:
    route: Email request
    text: To request deletion of any data associated with your API key or IP hash, email [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: API request logging
    text: We log the following for each API call
  retention:
  - period: 90 days
    scope: Request logs
    text: Request logs are retained for 90 days, then automatically deleted.
  - period: indefinitely
    scope: Call performance data (aggregated, anonymous)
    text: Call performance data (aggregated, anonymous) is retained indefinitely as part of our published track record.
  rights:
  - right: Deletion
    text: To request deletion of any data associated with your API key or IP hash, email [email protected] .
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
name: AlgoVault
provenance_date: '2026-11-09'
provider_name: AlgoVault
provider_slug: algovault-com
slug: algovault-com-privacy-policy
source_date: '2026-11-09'
source_filename: algovault-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://algovault.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AlgoVault\naid: algovault-com\nurl: https://algovault.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Personal names, emails, or account information (unless you subscribe via Stripe)\n- category: device\n  text: SHA-256 hash of your IP address (we never store raw IPs)\n- category: financial\n  text: We store your API key and subscription status. We do not store credit card numbers.\n- category: behavioral\n  text: Tool called (e.g., get_trade_call, scan_funding_arb)\npurposes:\n- purpose: API request logging\n  text: We log\
  \ the following for each API call\nretention:\n- scope: Request logs\n  period: 90 days\n  text: Request logs are retained for 90 days, then automatically deleted.\n- scope: Call performance data (aggregated, anonymous)\n  period: indefinitely\n  text: Call performance data (aggregated, anonymous) is retained indefinitely as part of our published track record.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request\n  text: To request deletion of any data associated with your API key or IP hash, email [email protected] .\nrights:\n- right: Deletion\n  text: To request deletion of any data associated with your API key or IP hash, email [email protected] .\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/algovault-com/privacy/algovault-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 9 quoted statements, read from AlgoVault's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Trading
- Finance
- MCP
- Cryptocurrency
---
