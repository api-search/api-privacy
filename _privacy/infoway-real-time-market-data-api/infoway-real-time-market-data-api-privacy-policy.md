---
api_specs:
- filename: infoway-real-time-market-data-api-streaming-asyncapi.yml
  format: yaml
  label: Infoway WebSocket Streaming API
  slug: infoway-websocket-streaming-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/infoway-real-time-market-data-api/asyncapi/infoway-real-time-market-data-api-streaming-asyncapi.yml
- filename: infoway-real-time-market-data-api-common-api-openapi.yml
  format: yaml
  label: Infoway Real-time Market Data API Common API
  slug: infoway-real-time-market-data-api-common-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infoway-real-time-market-data-api/openapi/infoway-real-time-market-data-api-common-api-openapi.yml
- filename: infoway-real-time-market-data-api-crypto-api-openapi.yml
  format: yaml
  label: Infoway Real-time Market Data API Crypto API
  slug: infoway-real-time-market-data-api-crypto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infoway-real-time-market-data-api/openapi/infoway-real-time-market-data-api-crypto-api-openapi.yml
- filename: infoway-real-time-market-data-api-stock-api-openapi.yml
  format: yaml
  label: Infoway Real-time Market Data API Stock API
  slug: infoway-real-time-market-data-api-stock-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infoway-real-time-market-data-api/openapi/infoway-real-time-market-data-api-stock-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: device
    text: Our system may automatically collect technical information such as your IP address, browser type, access time, and pages visited.
  - category: other
    text: The user's Infoway API Key is stored locally using Google Apps Script's PropertiesService.getUserProperties() — a Google-managed, per-user, encrypted key-value store.
  deletion:
    route: Add-on Settings tab, Delete API Key button
    text: In the Settings tab, click Delete API Key .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: website operation and maintenance
    text: This data is used for website operation and maintenance only and does not identify you personally.
  - purpose: improving user experience
    text: Improving user experience
  - purpose: analyzing website traffic
    text: Analyzing website traffic
  - purpose: providing the add-on's core feature
    text: Google user data is used only to provide the add-on's core feature — displaying financial data inside Google Sheets — and for no other purpose.
  retention:
  - period: 60 seconds
    scope: cache data
    text: Automatically expires after 60 seconds (real-time data) or 1 hour (financial data) with no action required from the user.
  - period: until the user removes it
    scope: infoway api key
    text: Retained in PropertiesService.getUserProperties() until the user removes it via the add-on's Settings panel
  rights:
  - right: access
    text: Request a copy of any personal data we hold about you.
  - right: rectification
    text: Request correction of any inaccurate data.
  - right: erasure
    text: Request deletion of your data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Google user data is not shared, sold, rented, or disclosed to any third party.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Infoway Real-time Market Data API
provenance_date: '2026-11-09'
provider_name: Infoway Real-time Market Data API
provider_slug: infoway-real-time-market-data-api
slug: infoway-real-time-market-data-api-privacy-policy
source_date: '2026-11-09'
source_filename: infoway-real-time-market-data-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://infoway.io/en/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Infoway Real-time Market Data API\naid: infoway-real-time-market-data-api\nurl: https://infoway.io/en/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: Our system may automatically collect technical information such as your IP address, browser type, access\n    time, and pages visited.\n- category: other\n  text: The user's Infoway API Key is stored locally using Google Apps Script's PropertiesService.getUserProperties()\n    — a Google-managed, per-user, encrypted key-value store.\npurposes:\n- purpose: website operation and maintenance\n\
  \  text: This data is used for website operation and maintenance only and does not identify you personally.\n- purpose: improving user experience\n  text: Improving user experience\n- purpose: analyzing website traffic\n  text: Analyzing website traffic\n- purpose: providing the add-on's core feature\n  text: Google user data is used only to provide the add-on's core feature — displaying financial data inside Google\n    Sheets — and for no other purpose.\nretention:\n- scope: cache data\n  period: 60 seconds\n  text: Automatically expires after 60 seconds (real-time data) or 1 hour (financial data) with no action required\n    from the user.\n- scope: infoway api key\n  period: until the user removes it\n  text: Retained in PropertiesService.getUserProperties() until the user removes it via the add-on's Settings panel\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Add-on Settings tab, Delete\
  \ API Key button\n  text: In the Settings tab, click Delete API Key .\nrights:\n- right: access\n  text: Request a copy of any personal data we hold about you.\n- right: rectification\n  text: Request correction of any inaccurate data.\n- right: erasure\n  text: Request deletion of your data.\nsale_or_sharing:\n  stance: prohibited\n  text: Google user data is not shared, sold, rented, or disclosed to any third party.\n"
source_yaml_url: https://artifacts.apis.io/infoway-real-time-market-data-api/privacy/infoway-real-time-market-data-api-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from Infoway Real-time Market Data API's own page on 2026-11-09.
synthetic: false
tags:
- stock-api
- forex-api
- crypto-api
- commodities-api
- futures-api
- Market Data
- Real-Time Data
- WebSocket
- Financial Data
- Fintech
- Historical Data
- Real-Time
---
