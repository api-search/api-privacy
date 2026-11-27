---
api_specs:
- filename: tanod-dev-agentscan-api-openapi.yml
  format: yaml
  label: tanod-dev Agentscan API
  slug: tanod-dev-agentscan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tanod-dev/openapi/tanod-dev-agentscan-api-openapi.yml
- filename: tanod-dev-chainpeek-api-openapi.yml
  format: yaml
  label: tanod-dev Chainpeek API
  slug: tanod-dev-chainpeek-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tanod-dev/openapi/tanod-dev-chainpeek-api-openapi.yml
- filename: tanod-dev-dnspeek-api-openapi.yml
  format: yaml
  label: tanod-dev Dnspeek API
  slug: tanod-dev-dnspeek-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tanod-dev/openapi/tanod-dev-dnspeek-api-openapi.yml
- filename: tanod-dev-findpeek-api-openapi.yml
  format: yaml
  label: tanod-dev Findpeek API
  slug: tanod-dev-findpeek-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tanod-dev/openapi/tanod-dev-findpeek-api-openapi.yml
- filename: tanod-dev-imagepeek-api-openapi.yml
  format: yaml
  label: tanod-dev Imagepeek API
  slug: tanod-dev-imagepeek-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tanod-dev/openapi/tanod-dev-imagepeek-api-openapi.yml
- filename: tanod-dev-mlpeek-api-openapi.yml
  format: yaml
  label: tanod-dev Mlpeek API
  slug: tanod-dev-mlpeek-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tanod-dev/openapi/tanod-dev-mlpeek-api-openapi.yml
- filename: tanod-dev-pactlint-api-openapi.yml
  format: yaml
  label: tanod-dev Pactlint API
  slug: tanod-dev-pactlint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tanod-dev/openapi/tanod-dev-pactlint-api-openapi.yml
- filename: tanod-dev-pdfpeek-api-openapi.yml
  format: yaml
  label: tanod-dev Pdfpeek API
  slug: tanod-dev-pdfpeek-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tanod-dev/openapi/tanod-dev-pdfpeek-api-openapi.yml
- filename: tanod-dev-sitepeek-api-openapi.yml
  format: yaml
  label: tanod-dev Sitepeek API
  slug: tanod-dev-sitepeek-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tanod-dev/openapi/tanod-dev-sitepeek-api-openapi.yml
- filename: tanod-dev-skypeek-api-openapi.yml
  format: yaml
  label: tanod-dev Skypeek API
  slug: tanod-dev-skypeek-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tanod-dev/openapi/tanod-dev-skypeek-api-openapi.yml
- filename: tanod-dev-toolsniff-api-openapi.yml
  format: yaml
  label: tanod-dev Toolsniff API
  slug: tanod-dev-toolsniff-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tanod-dev/openapi/tanod-dev-toolsniff-api-openapi.yml
- filename: tanod-dev-txpeek-api-openapi.yml
  format: yaml
  label: tanod-dev Txpeek API
  slug: tanod-dev-txpeek-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tanod-dev/openapi/tanod-dev-txpeek-api-openapi.yml
- filename: tanod-dev-utilpeek-api-openapi.yml
  format: yaml
  label: tanod-dev Utilpeek API
  slug: tanod-dev-utilpeek-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tanod-dev/openapi/tanod-dev-utilpeek-api-openapi.yml
- filename: tanod-dev-weatherpeek-api-openapi.yml
  format: yaml
  label: tanod-dev Weatherpeek API
  slug: tanod-dev-weatherpeek-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tanod-dev/openapi/tanod-dev-weatherpeek-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Every request to tanod.dev and our API hosts is logged: time, your IP address, user agent, the requested URL, referrer, response status and size.'
  - category: financial
    text: for paid calls, the payment network, the paying wallet address and the transaction hash
  - category: financial
    text: We store the SHA-256 hash of your key (never the key), its balance, your purchases (amount and the payment's transaction) and your charges (route, amount, time).
  - category: financial
    text: A bank statement holds personal financial data, such as your name, account number, balances and transactions.
  deletion:
    route: email request
    text: To ask what we hold about your IP address or wallet, or to have log entries deleted before the 30 days are up, email [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: security, abuse prevention, debugging and usage statistics
    text: Logs are kept for up to 30 days and used for security, abuse prevention, debugging and usage statistics.
  - purpose: prize payment
    text: keyed hashes of your IP address and its network (one slot per person), only to pay the prize
  - purpose: provide and secure Chrome extension features
    text: We use it only to provide and secure this feature (including abuse prevention, debugging, the free-allowance count and aggregated usage statistics, as described under Server logs); never for advertising or credit decisions; and it is not sold.
  retention:
  - period: up to 30 days
    scope: server logs
    text: Logs are kept for up to 30 days
  - period: 24 hours
    scope: generated file links
    text: we store the generated file (a PDF, image, audio or Office file) for 24 hours behind an unguessable download link, then delete it.
  - period: 30 days
    scope: contract and package scan reports
    text: Contract and package scan reports are kept for 30 days under a random scan ID
  - period: null
    scope: uploaded server tool files
    text: It is processed in a temporary directory, deleted when the job ends, and never logged.
  - period: 60 days after the week ends
    scope: skill quest prize records
    text: delete them 60 days after the week ends
  - period: 30 days
    scope: Tanod Monitor groups
    text: Groups that are never opened and never report for 30 days are deleted with their data.
  rights:
  - right: access and deletion of log entries
    text: To ask what we hold about your IP address or wallet, or to have log entries deleted before the 30 days are up, email [email protected] .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Who else processes data Cloudflare (CDN, security, Turnstile, analytics). The x402 payment facilitator (Coinbase Developer Platform) verifies and settles payments.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tanod-dev
provenance_date: '2026-11-10'
provider_name: tanod-dev
provider_slug: tanod-dev
slug: tanod-dev-privacy-policy
source_date: '2026-11-10'
source_filename: tanod-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tanod.dev/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tanod-dev\naid: tanod-dev\nurl: https://tanod.dev/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Every request to tanod.dev and our API hosts is logged: time, your IP address, user agent, the requested\n    URL, referrer, response status and size.'\n- category: financial\n  text: for paid calls, the payment network, the paying wallet address and the transaction hash\n- category: financial\n  text: We store the SHA-256 hash of your key (never the key), its balance, your purchases (amount and the payment's\n    transaction) and\
  \ your charges (route, amount, time).\n- category: financial\n  text: A bank statement holds personal financial data, such as your name, account number, balances and transactions.\npurposes:\n- purpose: security, abuse prevention, debugging and usage statistics\n  text: Logs are kept for up to 30 days and used for security, abuse prevention, debugging and usage statistics.\n- purpose: prize payment\n  text: keyed hashes of your IP address and its network (one slot per person), only to pay the prize\n- purpose: provide and secure Chrome extension features\n  text: We use it only to provide and secure this feature (including abuse prevention, debugging, the free-allowance\n    count and aggregated usage statistics, as described under Server logs); never for advertising or credit decisions;\n    and it is not sold.\nretention:\n- scope: server logs\n  period: up to 30 days\n  text: Logs are kept for up to 30 days\n- scope: generated file links\n  period: 24 hours\n  text: we store the generated\
  \ file (a PDF, image, audio or Office file) for 24 hours behind an unguessable download\n    link, then delete it.\n- scope: contract and package scan reports\n  period: 30 days\n  text: Contract and package scan reports are kept for 30 days under a random scan ID\n- scope: uploaded server tool files\n  period: null\n  text: It is processed in a temporary directory, deleted when the job ends, and never logged.\n- scope: skill quest prize records\n  period: 60 days after the week ends\n  text: delete them 60 days after the week ends\n- scope: Tanod Monitor groups\n  period: 30 days\n  text: Groups that are never opened and never report for 30 days are deleted with their data.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Who else processes data Cloudflare (CDN, security, Turnstile, analytics). The x402 payment facilitator (Coinbase\n    Developer Platform) verifies and settles payments.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email\
  \ request\n  text: To ask what we hold about your IP address or wallet, or to have log entries deleted before the 30 days are\n    up, email [email protected] .\nrights:\n- right: access and deletion of log entries\n  text: To ask what we hold about your IP address or wallet, or to have log entries deleted before the 30 days are\n    up, email [email protected] .\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/tanod-dev/privacy/tanod-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from tanod-dev's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- MCP
- Tools
- Finance
- Monitoring
---
