---
api_specs:
- filename: siftingio-asyncapi.yaml
  format: yaml
  label: SiftingIO Live Stream
  slug: siftingio-live-stream
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/siftingio/asyncapi/siftingio-asyncapi.yaml
- filename: siftingio-commodities-api-openapi.yml
  format: yaml
  label: SiftingIO Commodities API
  slug: siftingio-commodities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-commodities-api-openapi.yml
- filename: siftingio-convert-api-openapi.yml
  format: yaml
  label: SiftingIO Convert API
  slug: siftingio-convert-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-convert-api-openapi.yml
- filename: siftingio-crypto-api-openapi.yml
  format: yaml
  label: SiftingIO Crypto API
  slug: siftingio-crypto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-crypto-api-openapi.yml
- filename: siftingio-dex-api-openapi.yml
  format: yaml
  label: SiftingIO DEX API
  slug: siftingio-dex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-dex-api-openapi.yml
- filename: siftingio-filers-api-openapi.yml
  format: yaml
  label: SiftingIO Filers API
  slug: siftingio-filers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-filers-api-openapi.yml
- filename: siftingio-forex-api-openapi.yml
  format: yaml
  label: SiftingIO Forex API
  slug: siftingio-forex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-forex-api-openapi.yml
- filename: siftingio-live-api-openapi.yml
  format: yaml
  label: SiftingIO Live API
  slug: siftingio-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-live-api-openapi.yml
- filename: siftingio-markets-api-openapi.yml
  format: yaml
  label: SiftingIO Markets API
  slug: siftingio-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-markets-api-openapi.yml
- filename: siftingio-signals-api-openapi.yml
  format: yaml
  label: SiftingIO Signals API
  slug: siftingio-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-signals-api-openapi.yml
- filename: siftingio-stocks-api-openapi.yml
  format: yaml
  label: SiftingIO Stocks API
  slug: siftingio-stocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-stocks-api-openapi.yml
- filename: siftingio-economic-calendar-api-openapi.yml
  format: yaml
  label: SiftingIO Economic Calendar API
  slug: siftingio-economic-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftingio/openapi/siftingio-economic-calendar-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'account details: email address, name, password (stored as a salted hash)'
  - category: contact
    text: 'organization details: company name, billing address, VAT/tax identifier, technical contact'
  - category: financial
    text: 'payment details: billing name, billing address, country, and the last four digits of your card.'
  - category: communication
    text: 'communications: support tickets, sales inquiries, survey responses, feedback, content of emails you send us'
  - category: device
    text: 'device and connection: IP address, derived approximate location (country/region only), browser user-agent string, operating system, referring URL, language'
  - category: behavioral
    text: 'usage and telemetry: API endpoint, asset/symbol requested, response status, latency, error rates, request volume, plan tier, throttle events'
  deletion:
    route: Email privacy@sifting.io or use the dashboard's account-deletion tools where available.
    text: use the dashboard’s account-deletion tools where available.
  dpa:
    available: null
    text: 'Security disclosures and DPA requests: security@sifting.io'
    url: null
  purposes:
  - purpose: Provide the Service
    text: Create and maintain your account, authenticate API requests, deliver market data, calculate usage, enforce rate limits and license scope, provide dashboards, and offer customer support.
  - purpose: Billing and collections
    text: Process payments, invoices, refunds, taxes, and dunning; detect and prevent payment fraud and chargeback abuse.
  - purpose: Security and abuse prevention
    text: Detect and block unauthorized access, credential leaks, scraping, key sharing, denial-of-service activity, and other abuse; investigate security incidents.
  - purpose: Communicate with you
    text: Send transactional emails (account, billing, security, incident notices), respond to inquiries
  residency:
  - region: United Kingdom
    text: our primary production environment is hosted in the United Kingdom (AWS eu-west-2, London region).
  retention:
  - period: 36 months
    scope: Account profile and configuration
    text: deleted (or anonymized) within 90 days of account deletion or after 36 months of continuous inactivity, whichever is sooner.
  - period: 12 months
    scope: API access and usage logs
    text: Up to 12 months for operational, security, and abuse- prevention purposes
  - period: 24 months
    scope: Security and audit logs
    text: Up to 24 months.
  - period: 7 years
    scope: Billing records, invoices, and tax data
    text: generally 7 years from the end of the relevant fiscal year.
  - period: 36 months
    scope: Support and sales communications
    text: Up to 36 months after last contact.
  rights:
  - right: access
    text: access the personal data we hold about you
  - right: rectification
    text: request rectification of inaccurate or incomplete data
  - right: erasure
    text: request erasure of your data (“right to be forgotten”)
  - right: portability
    text: request portability of data you provided to us
  - right: objection
    text: restrict or object to certain processing
  - right: deletion (California)
    text: request deletion of personal information we collected from you
  role:
    text: SaltingIO is the controller of personal data processed in connection with the Service.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information for monetary consideration, and we do not “share” it for cross-context behavioral advertising as those terms are defined under the CCPA/CPRA.
  subprocessors:
    text: A current list of sub-processors is available on request to privacy@sifting.io .
    url: null
  transfers:
  - mechanism: SCC
    text: European Commission Standard Contractual Clauses and the UK International Data Transfer Addendum
  - mechanism: adequacy
    text: adequacy decisions where applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SiftingIO
provenance_date: '2026-11-10'
provider_name: SiftingIO
provider_slug: siftingio
slug: siftingio-privacy-policy
source_date: '2026-11-10'
source_filename: siftingio-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sifting.io/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SiftingIO\naid: siftingio\nurl: https://sifting.io/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: SaltingIO is the controller of personal data processed in connection with the Service.\ndata_categories:\n- category: identifying\n  text: 'account details: email address, name, password (stored as a salted hash)'\n- category: contact\n  text: 'organization details: company name, billing address, VAT/tax identifier, technical contact'\n- category: financial\n  text: 'payment details: billing name, billing address, country, and the last four digits of your card.'\n- category:\
  \ communication\n  text: 'communications: support tickets, sales inquiries, survey responses, feedback, content of emails you send\n    us'\n- category: device\n  text: 'device and connection: IP address, derived approximate location (country/region only), browser user-agent\n    string, operating system, referring URL, language'\n- category: behavioral\n  text: 'usage and telemetry: API endpoint, asset/symbol requested, response status, latency, error rates, request\n    volume, plan tier, throttle events'\npurposes:\n- purpose: Provide the Service\n  text: Create and maintain your account, authenticate API requests, deliver market data, calculate usage, enforce\n    rate limits and license scope, provide dashboards, and offer customer support.\n- purpose: Billing and collections\n  text: Process payments, invoices, refunds, taxes, and dunning; detect and prevent payment fraud and chargeback\n    abuse.\n- purpose: Security and abuse prevention\n  text: Detect and block unauthorized access,\
  \ credential leaks, scraping, key sharing, denial-of-service activity,\n    and other abuse; investigate security incidents.\n- purpose: Communicate with you\n  text: Send transactional emails (account, billing, security, incident notices), respond to inquiries\nretention:\n- scope: Account profile and configuration\n  period: 36 months\n  text: deleted (or anonymized) within 90 days of account deletion or after 36 months of continuous inactivity,\n    whichever is sooner.\n- scope: API access and usage logs\n  period: 12 months\n  text: Up to 12 months for operational, security, and abuse- prevention purposes\n- scope: Security and audit logs\n  period: 24 months\n  text: Up to 24 months.\n- scope: Billing records, invoices, and tax data\n  period: 7 years\n  text: generally 7 years from the end of the relevant fiscal year.\n- scope: Support and sales communications\n  period: 36 months\n  text: Up to 36 months after last contact.\nresidency:\n- region: United Kingdom\n  text: our primary\
  \ production environment is hosted in the United Kingdom (AWS eu-west-2, London region).\ntransfers:\n- mechanism: SCC\n  text: European Commission Standard Contractual Clauses and the UK International Data Transfer Addendum\n- mechanism: adequacy\n  text: adequacy decisions where applicable\nsubprocessors:\n  url: null\n  text: A current list of sub-processors is available on request to privacy@sifting.io .\ndpa:\n  available: null\n  url: null\n  text: 'Security disclosures and DPA requests: security@sifting.io'\ndeletion:\n  route: Email privacy@sifting.io or use the dashboard's account-deletion tools where available.\n  text: use the dashboard’s account-deletion tools where available.\nrights:\n- right: access\n  text: access the personal data we hold about you\n- right: rectification\n  text: request rectification of inaccurate or incomplete data\n- right: erasure\n  text: request erasure of your data (“right to be forgotten”)\n- right: portability\n  text: request portability of\
  \ data you provided to us\n- right: objection\n  text: restrict or object to certain processing\n- right: deletion (California)\n  text: request deletion of personal information we collected from you\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information for monetary consideration, and we do not “share” it for cross-context\n    behavioral advertising as those terms are defined under the CCPA/CPRA.\n"
source_yaml_url: https://artifacts.apis.io/siftingio/privacy/siftingio-privacy-policy.yml
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
summary_line: 29 quoted statements, read from SiftingIO's own page on 2026-11-10.
synthetic: false
tags:
- Financial market data
- Stocks/equities
- Foreign Exchange
- Cryptocurrency
- DeFi/on-chain
- Commodities
- SEC Filings
- XBRL
- Fundamentals
- Fintech
- Quant/trading infrastructure
- Real-Time Streaming
- WebSocket
- FIX
- Financial Data
- Market Data
- Stocks
- DeFi
- Real-Time
- REST API
- MCP Server
- Agent-Native
---
