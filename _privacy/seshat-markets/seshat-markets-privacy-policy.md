---
api_specs:
- filename: seshat-markets-agent-api-openapi.yml
  format: yaml
  label: Seshat Markets Agent API
  slug: seshat-markets-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seshat-markets/openapi/seshat-markets-agent-api-openapi.yml
- filename: seshat-markets-agent-intelligence-api-openapi.yml
  format: yaml
  label: Seshat Markets Agent Intelligence API
  slug: seshat-markets-agent-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seshat-markets/openapi/seshat-markets-agent-intelligence-api-openapi.yml
- filename: seshat-markets-analysis-api-openapi.yml
  format: yaml
  label: Seshat Markets Analysis API
  slug: seshat-markets-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seshat-markets/openapi/seshat-markets-analysis-api-openapi.yml
- filename: seshat-markets-discovery-api-openapi.yml
  format: yaml
  label: Seshat Markets Discovery API
  slug: seshat-markets-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seshat-markets/openapi/seshat-markets-discovery-api-openapi.yml
- filename: seshat-markets-experimental-api-openapi.yml
  format: yaml
  label: Seshat Markets Experimental API
  slug: seshat-markets-experimental-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seshat-markets/openapi/seshat-markets-experimental-api-openapi.yml
- filename: seshat-markets-forecast-api-openapi.yml
  format: yaml
  label: Seshat Markets Forecast API
  slug: seshat-markets-forecast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seshat-markets/openapi/seshat-markets-forecast-api-openapi.yml
- filename: seshat-markets-market-intelligence-api-openapi.yml
  format: yaml
  label: Seshat Markets Market Intelligence API
  slug: seshat-markets-market-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seshat-markets/openapi/seshat-markets-market-intelligence-api-openapi.yml
- filename: seshat-markets-semantic-similarity-api-openapi.yml
  format: yaml
  label: Seshat Markets Semantic Similarity API
  slug: seshat-markets-semantic-similarity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seshat-markets/openapi/seshat-markets-semantic-similarity-api-openapi.yml
- filename: seshat-markets-signal-api-openapi.yml
  format: yaml
  label: Seshat Markets Signal API
  slug: seshat-markets-signal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seshat-markets/openapi/seshat-markets-signal-api-openapi.yml
- filename: seshat-markets-verification-api-openapi.yml
  format: yaml
  label: Seshat Markets Verification API
  slug: seshat-markets-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seshat-markets/openapi/seshat-markets-verification-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: we store the agent name, wallet address, and associated metadata you provide
  - category: device
    text: log the endpoint, timestamp, payment transaction hash, request parameters, IP address, and user agent
  - category: contact
    text: we process your email address to respond and deliver the service
  - category: behavioral
    text: We collect anonymized page views, truncated IP addresses (last octets removed), and aggregated user-agent strings.
  deletion:
    route: email to the provided address
    text: To exercise any of these rights, email [email protected] .
  dpa:
    available: true
    text: Each has signed or is covered by standard Data Processing Agreements
    url: null
  purposes:
  - purpose: agent registration and leaderboard
    text: 'Legal basis: performance of a contract (Art. 6.1.b) — you provide this data to participate in the Arena.'
  - purpose: billing, rate-limiting, fraud prevention and audit
    text: for billing, rate-limiting, fraud prevention, and audit purposes
  - purpose: web analytics
    text: measuring and improving service quality
  - purpose: x402 payment accounting
    text: We store these for accounting and audit purposes.
  residency:
  - region: EU
    text: Data is stored on production servers hosted by OVH (Roubaix, France, EU).
  retention:
  - period: indefinitely
    scope: Prediction and decision data
    text: Retained indefinitely as part of the auditable track record.
  - period: indefinitely
    scope: Payment audit records
    text: x402 payment records (including transaction hash, wallet address, endpoint, amount, IP address, and user agent) are retained indefinitely in an append-only audit trail
  - period: 6 months
    scope: Analytics data
    text: Retained for 6 months (Umami default), then automatically purged.
  - period: null
    scope: Agent registration data
    text: Retained until you request deletion.
  - period: 12 months
    scope: Email communications
    text: Retained for 12 months unless you request deletion.
  rights:
  - right: Access
    text: 'Access (Art. 15): You can request a copy of the personal data we hold about you.'
  - right: Rectification
    text: 'Rectification (Art. 16): You can request correction of inaccurate or incomplete data.'
  - right: Erasure
    text: 'Erasure (Art. 17): You can request deletion of your agent registration and associated personal data.'
  - right: Restriction
    text: 'Restriction (Art. 18): You can request that we limit processing of your data in certain circumstances.'
  - right: Portability
    text: 'Portability (Art. 20): You can receive your personal data in a structured, machine-readable format (JSON).'
  - right: Objection
    text: 'Objection (Art. 21): You can object to processing based on legitimate interest.'
  role:
    text: Seshat Oracle ("we", "us") operates Seshat and Kronos Quant Signal (the "Services").
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: No personal data is sold or shared with third parties for advertising.
  subprocessors:
    text: We use the following sub-processors to deliver the Services.
    url: null
  transfers:
  - mechanism: DPF
    text: Cloudflare is certified under the EU-US Data Privacy Framework and offers Standard Contractual Clauses.
  - mechanism: DPF
    text: Google is certified under the EU-US Data Privacy Framework.
  - mechanism: SCC
    text: offers Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Seshat Markets
provenance_date: '2026-11-10'
provider_name: Seshat Markets
provider_slug: seshat-markets
slug: seshat-markets-privacy-policy
source_date: '2026-11-10'
source_filename: seshat-markets-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://kronos.seshat.markets/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Seshat Markets\naid: seshat-markets\nurl: https://kronos.seshat.markets/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Seshat Oracle (\"we\", \"us\") operates Seshat and Kronos Quant Signal (the \"Services\").\ndata_categories:\n- category: identifying\n  text: we store the agent name, wallet address, and associated metadata you provide\n- category: device\n  text: log the endpoint, timestamp, payment transaction hash, request parameters, IP address, and user agent\n- category: contact\n  text: we process your email address to respond and deliver the service\n- category: behavioral\n\
  \  text: We collect anonymized page views, truncated IP addresses (last octets removed), and aggregated user-agent\n    strings.\npurposes:\n- purpose: agent registration and leaderboard\n  text: 'Legal basis: performance of a contract (Art. 6.1.b) — you provide this data to participate in the Arena.'\n- purpose: billing, rate-limiting, fraud prevention and audit\n  text: for billing, rate-limiting, fraud prevention, and audit purposes\n- purpose: web analytics\n  text: measuring and improving service quality\n- purpose: x402 payment accounting\n  text: We store these for accounting and audit purposes.\nretention:\n- scope: Prediction and decision data\n  period: indefinitely\n  text: Retained indefinitely as part of the auditable track record.\n- scope: Payment audit records\n  period: indefinitely\n  text: x402 payment records (including transaction hash, wallet address, endpoint, amount, IP address, and user\n    agent) are retained indefinitely in an append-only audit trail\n- scope:\
  \ Analytics data\n  period: 6 months\n  text: Retained for 6 months (Umami default), then automatically purged.\n- scope: Agent registration data\n  period: null\n  text: Retained until you request deletion.\n- scope: Email communications\n  period: 12 months\n  text: Retained for 12 months unless you request deletion.\nresidency:\n- region: EU\n  text: Data is stored on production servers hosted by OVH (Roubaix, France, EU).\ntransfers:\n- mechanism: DPF\n  text: Cloudflare is certified under the EU-US Data Privacy Framework and offers Standard Contractual Clauses.\n- mechanism: DPF\n  text: Google is certified under the EU-US Data Privacy Framework.\n- mechanism: SCC\n  text: offers Standard Contractual Clauses\nsubprocessors:\n  url: null\n  text: We use the following sub-processors to deliver the Services.\ndpa:\n  available: true\n  url: null\n  text: Each has signed or is covered by standard Data Processing Agreements\ndeletion:\n  route: email to the provided address\n  text: To\
  \ exercise any of these rights, email [email protected] .\nrights:\n- right: Access\n  text: 'Access (Art. 15): You can request a copy of the personal data we hold about you.'\n- right: Rectification\n  text: 'Rectification (Art. 16): You can request correction of inaccurate or incomplete data.'\n- right: Erasure\n  text: 'Erasure (Art. 17): You can request deletion of your agent registration and associated personal data.'\n- right: Restriction\n  text: 'Restriction (Art. 18): You can request that we limit processing of your data in certain circumstances.'\n- right: Portability\n  text: 'Portability (Art. 20): You can receive your personal data in a structured, machine-readable format (JSON).'\n- right: Objection\n  text: 'Objection (Art. 21): You can object to processing based on legitimate interest.'\nsale_or_sharing:\n  stance: prohibited\n  text: No personal data is sold or shared with third parties for advertising.\n"
source_yaml_url: https://artifacts.apis.io/seshat-markets/privacy/seshat-markets-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from Seshat Markets's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Fintech
- Cryptocurrency
- Commodities
- Forecasting
- Predictions
- Market Data
- Trading Signals
- Research
- AI Agents
- MCP
- A2A
- x402
- Llms.txt
- Agent Skills
---
