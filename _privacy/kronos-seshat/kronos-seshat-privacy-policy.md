---
api_specs:
- filename: kronos-seshat-agent-api-openapi.yml
  format: yaml
  label: Kronos Quant Signal API Agent API
  slug: kronos-seshat-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kronos-seshat/openapi/kronos-seshat-agent-api-openapi.yml
- filename: kronos-seshat-agent-intelligence-api-openapi.yml
  format: yaml
  label: Kronos Quant Signal API Agent Intelligence API
  slug: kronos-seshat-agent-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kronos-seshat/openapi/kronos-seshat-agent-intelligence-api-openapi.yml
- filename: kronos-seshat-analysis-api-openapi.yml
  format: yaml
  label: Kronos Quant Signal API Analysis API
  slug: kronos-seshat-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kronos-seshat/openapi/kronos-seshat-analysis-api-openapi.yml
- filename: kronos-seshat-discovery-api-openapi.yml
  format: yaml
  label: Kronos Quant Signal API Discovery API
  slug: kronos-seshat-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kronos-seshat/openapi/kronos-seshat-discovery-api-openapi.yml
- filename: kronos-seshat-experimental-api-openapi.yml
  format: yaml
  label: Kronos Quant Signal API Experimental API
  slug: kronos-seshat-experimental-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kronos-seshat/openapi/kronos-seshat-experimental-api-openapi.yml
- filename: kronos-seshat-forecast-api-openapi.yml
  format: yaml
  label: Kronos Quant Signal API Forecast API
  slug: kronos-seshat-forecast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kronos-seshat/openapi/kronos-seshat-forecast-api-openapi.yml
- filename: kronos-seshat-market-intelligence-api-openapi.yml
  format: yaml
  label: Kronos Quant Signal API Market Intelligence API
  slug: kronos-seshat-market-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kronos-seshat/openapi/kronos-seshat-market-intelligence-api-openapi.yml
- filename: kronos-seshat-semantic-similarity-api-openapi.yml
  format: yaml
  label: Kronos Quant Signal API Semantic Similarity API
  slug: kronos-seshat-semantic-similarity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kronos-seshat/openapi/kronos-seshat-semantic-similarity-api-openapi.yml
- filename: kronos-seshat-signal-api-openapi.yml
  format: yaml
  label: Kronos Quant Signal API Signal API
  slug: kronos-seshat-signal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kronos-seshat/openapi/kronos-seshat-signal-api-openapi.yml
- filename: kronos-seshat-verification-api-openapi.yml
  format: yaml
  label: Kronos Quant Signal API Verification API
  slug: kronos-seshat-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kronos-seshat/openapi/kronos-seshat-verification-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: we store the agent name, wallet address, and associated metadata you provide
  - category: contact
    text: we process your email address to respond and deliver the service
  - category: device
    text: we log the endpoint, timestamp, payment transaction hash, request parameters, IP address, and user agent for billing, rate-limiting, fraud prevention, and audit purposes
  - category: behavioral
    text: We collect anonymized page views, truncated IP addresses (last octets removed), and aggregated user-agent strings.
  - category: financial
    text: Transaction hashes, wallet addresses, and amounts are recorded on the Solana and/or Base blockchains and are inherently public.
  deletion:
    route: email request to the provider
    text: To exercise any of these rights, email [email protected] .
  dpa:
    available: true
    text: Each has signed or is covered by standard Data Processing Agreements
    url: null
  purposes:
  - purpose: agent registration and Arena participation
    text: you provide this data to participate in the Arena
  - purpose: fraud prevention, billing integrity, and service security
    text: fraud prevention, billing integrity, and service security
  - purpose: auditable track record
    text: maintaining an immutable, auditable track record is core to the service's integrity
  - purpose: measuring and improving service quality
    text: measuring and improving service quality
  - purpose: responding to contact and delivering alerts
    text: we process your email address to respond and deliver the service
  residency:
  - region: EU (France)
    text: Data is stored on production servers hosted by OVH (Roubaix, France, EU).
  retention:
  - period: null
    scope: prediction and decision data
    text: Retained indefinitely as part of the auditable track record.
  - period: null
    scope: payment audit records
    text: x402 payment records (including transaction hash, wallet address, endpoint, amount, IP address, and user agent) are retained indefinitely in an append-only audit trail
  - period: 6 months
    scope: analytics data
    text: Retained for 6 months (Umami default), then automatically purged.
  - period: null
    scope: agent registration data
    text: Retained until you request deletion.
  - period: 12 months
    scope: email communications
    text: Retained for 12 months unless you request deletion.
  rights:
  - right: Access
    text: You can request a copy of the personal data we hold about you.
  - right: Rectification
    text: You can request correction of inaccurate or incomplete data.
  - right: Erasure
    text: You can request deletion of your agent registration and associated personal data.
  - right: Restriction
    text: You can request that we limit processing of your data in certain circumstances.
  - right: Portability
    text: You can receive your personal data in a structured, machine-readable format (JSON).
  - right: Objection
    text: You can object to processing based on legitimate interest.
  - right: Automated decision-making
    text: No automated decisions with legal or significant effects are made about individuals.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
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
name: Kronos Quant Signal API
provenance_date: '2026-11-09'
provider_name: Kronos Quant Signal API
provider_slug: kronos-seshat
slug: kronos-seshat-privacy-policy
source_date: '2026-11-09'
source_filename: kronos-seshat-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://kronos.seshat.markets/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Kronos Quant Signal API\naid: kronos-seshat\nurl: https://kronos.seshat.markets/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we store the agent name, wallet address, and associated metadata you provide\n- category: contact\n  text: we process your email address to respond and deliver the service\n- category: device\n  text: we log the endpoint, timestamp, payment transaction hash, request parameters, IP address, and user agent\n    for billing, rate-limiting, fraud prevention, and audit purposes\n- category: behavioral\n\
  \  text: We collect anonymized page views, truncated IP addresses (last octets removed), and aggregated user-agent\n    strings.\n- category: financial\n  text: Transaction hashes, wallet addresses, and amounts are recorded on the Solana and/or Base blockchains and\n    are inherently public.\npurposes:\n- purpose: agent registration and Arena participation\n  text: you provide this data to participate in the Arena\n- purpose: fraud prevention, billing integrity, and service security\n  text: fraud prevention, billing integrity, and service security\n- purpose: auditable track record\n  text: maintaining an immutable, auditable track record is core to the service's integrity\n- purpose: measuring and improving service quality\n  text: measuring and improving service quality\n- purpose: responding to contact and delivering alerts\n  text: we process your email address to respond and deliver the service\nretention:\n- scope: prediction and decision data\n  period: null\n  text: Retained\
  \ indefinitely as part of the auditable track record.\n- scope: payment audit records\n  period: null\n  text: x402 payment records (including transaction hash, wallet address, endpoint, amount, IP address, and user\n    agent) are retained indefinitely in an append-only audit trail\n- scope: analytics data\n  period: 6 months\n  text: Retained for 6 months (Umami default), then automatically purged.\n- scope: agent registration data\n  period: null\n  text: Retained until you request deletion.\n- scope: email communications\n  period: 12 months\n  text: Retained for 12 months unless you request deletion.\nresidency:\n- region: EU (France)\n  text: Data is stored on production servers hosted by OVH (Roubaix, France, EU).\ntransfers:\n- mechanism: DPF\n  text: Cloudflare is certified under the EU-US Data Privacy Framework and offers Standard Contractual Clauses.\n- mechanism: DPF\n  text: Google is certified under the EU-US Data Privacy Framework.\n- mechanism: SCC\n  text: offers Standard\
  \ Contractual Clauses\nsubprocessors:\n  url: null\n  text: We use the following sub-processors to deliver the Services.\ndpa:\n  available: true\n  url: null\n  text: Each has signed or is covered by standard Data Processing Agreements\ndeletion:\n  route: email request to the provider\n  text: To exercise any of these rights, email [email protected] .\nrights:\n- right: Access\n  text: You can request a copy of the personal data we hold about you.\n- right: Rectification\n  text: You can request correction of inaccurate or incomplete data.\n- right: Erasure\n  text: You can request deletion of your agent registration and associated personal data.\n- right: Restriction\n  text: You can request that we limit processing of your data in certain circumstances.\n- right: Portability\n  text: You can receive your personal data in a structured, machine-readable format (JSON).\n- right: Objection\n  text: You can object to processing based on legitimate interest.\n- right: Automated decision-making\n\
  \  text: No automated decisions with legal or significant effects are made about individuals.\nsale_or_sharing:\n  stance: conditional\n  text: No personal data is sold or shared with third parties for advertising.\n"
source_yaml_url: https://artifacts.apis.io/kronos-seshat/privacy/kronos-seshat-privacy-policy.yml
stated_fields:
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
summary_line: 30 quoted statements, read from Kronos Quant Signal API's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Financial Forecast
- Market Data
- Auditing
- Micropayments
---
