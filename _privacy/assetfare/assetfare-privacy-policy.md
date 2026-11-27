---
api_specs:
- filename: assetfare-capabilities-api-openapi.yml
  format: yaml
  label: AssetFare Capabilities API
  slug: assetfare-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assetfare/openapi/assetfare-capabilities-api-openapi.yml
- filename: assetfare-prepare-api-openapi.yml
  format: yaml
  label: AssetFare Prepare API
  slug: assetfare-prepare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assetfare/openapi/assetfare-prepare-api-openapi.yml
- filename: assetfare-quote-api-openapi.yml
  format: yaml
  label: AssetFare Quote API
  slug: assetfare-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assetfare/openapi/assetfare-quote-api-openapi.yml
- filename: assetfare-session-api-openapi.yml
  format: yaml
  label: AssetFare Session API
  slug: assetfare-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assetfare/openapi/assetfare-session-api-openapi.yml
- filename: assetfare-status-api-openapi.yml
  format: yaml
  label: AssetFare Status API
  slug: assetfare-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assetfare/openapi/assetfare-status-api-openapi.yml
- filename: assetfare-auth-api-openapi.yml
  format: yaml
  label: AssetFare Auth API
  slug: assetfare-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assetfare/openapi/assetfare-auth-api-openapi.yml
- filename: assetfare-route-selection-api-openapi.yml
  format: yaml
  label: AssetFare Route Selection API
  slug: assetfare-route-selection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assetfare/openapi/assetfare-route-selection-api-openapi.yml
- filename: assetfare-well-known-api-openapi.yml
  format: yaml
  label: AssetFare .well Known API
  slug: assetfare-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assetfare/openapi/assetfare-well-known-api-openapi.yml
- filename: assetfare-app-store-api-openapi.yml
  format: yaml
  label: AssetFare App Store API
  slug: assetfare-app-store-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assetfare/openapi/assetfare-app-store-api-openapi.yml
- filename: assetfare-events-api-openapi.yml
  format: yaml
  label: AssetFare Events API
  slug: assetfare-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assetfare/openapi/assetfare-events-api-openapi.yml
- filename: assetfare-google-play-api-openapi.yml
  format: yaml
  label: AssetFare Google Play API
  slug: assetfare-google-play-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assetfare/openapi/assetfare-google-play-api-openapi.yml
- filename: assetfare-jobs-api-openapi.yml
  format: yaml
  label: AssetFare Jobs API
  slug: assetfare-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/assetfare/openapi/assetfare-jobs-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: AssetFare stores caller-supplied public wallet addresses
  - category: device
    text: hashed user-agent values where supplied
  - category: financial
    text: transaction hashes, workflow state, route decisions, timestamps, and fee data
  deletion:
    route: none stated
    text: No automatic deletion schedule is currently promised.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: session records and operations
    text: Session records prevent duplicate execution, verify receipts, provide recovery guidance, apply limits, investigate operational failures, and improve route quality.
  - purpose: security, availability, and rate limiting
    text: The API reverse proxy and hosting providers process IP addresses and request metadata for security, availability, and rate limiting.
  retention:
  - period: rotate daily with up to ten rotations
    scope: API proxy logs
    text: API proxy logs normally rotate daily with up to ten rotations.
  - period: no automatic deletion schedule
    scope: quote, authentication, session, receipt, and aggregate telemetry records
    text: No automatic deletion schedule is currently promised.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: AssetFare does not sell these records.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AssetFare
provenance_date: '2026-11-09'
provider_name: AssetFare
provider_slug: assetfare
slug: assetfare-privacy-policy
source_date: '2026-11-09'
source_filename: assetfare-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://assetfare.dev/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AssetFare\naid: assetfare\nurl: https://assetfare.dev/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: AssetFare stores caller-supplied public wallet addresses\n- category: device\n  text: hashed user-agent values where supplied\n- category: financial\n  text: transaction hashes, workflow state, route decisions, timestamps, and fee data\npurposes:\n- purpose: session records and operations\n  text: Session records prevent duplicate execution, verify receipts, provide recovery guidance, apply limits, investigate\n    operational\
  \ failures, and improve route quality.\n- purpose: security, availability, and rate limiting\n  text: The API reverse proxy and hosting providers process IP addresses and request metadata for security, availability,\n    and rate limiting.\nretention:\n- scope: API proxy logs\n  period: rotate daily with up to ten rotations\n  text: API proxy logs normally rotate daily with up to ten rotations.\n- scope: quote, authentication, session, receipt, and aggregate telemetry records\n  period: no automatic deletion schedule\n  text: No automatic deletion schedule is currently promised.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: none stated\n  text: No automatic deletion schedule is currently promised.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: AssetFare does not sell these records.\n"
source_yaml_url: https://artifacts.apis.io/assetfare/privacy/assetfare-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 9 quoted statements, read from AssetFare's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Asset Transfer
- Bridge
- Cross-Chain
- Non-Custodial
- Cryptocurrency
- Solana
- Base
- Arbitrum
- Robinhood Chain
- Optimism
- Ethereum
- OpenAPI
- MCP
- Agent Skills
---
