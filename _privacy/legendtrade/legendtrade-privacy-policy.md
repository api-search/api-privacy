---
api_specs:
- filename: legendtrade-ws-asyncapi.yml
  format: yaml
  label: Legend WebSocket API
  slug: websocket
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/legendtrade/asyncapi/legendtrade-ws-asyncapi.yml
- filename: legendtrade-health-api-openapi.yml
  format: yaml
  label: LegendTrade Health API
  slug: legendtrade-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/legendtrade/openapi/legendtrade-health-api-openapi.yml
- filename: legendtrade-info-api-openapi.yml
  format: yaml
  label: LegendTrade Info API
  slug: legendtrade-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/legendtrade/openapi/legendtrade-info-api-openapi.yml
- filename: legendtrade-market-data-api-openapi.yml
  format: yaml
  label: LegendTrade Market Data API
  slug: legendtrade-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/legendtrade/openapi/legendtrade-market-data-api-openapi.yml
- filename: legendtrade-wallets-api-openapi.yml
  format: yaml
  label: LegendTrade Wallets API
  slug: legendtrade-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/legendtrade/openapi/legendtrade-wallets-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers such as name, display name, username, date of birth, residential address, password, email address, telephone number
  - category: device
    text: 'Device and Browser Information: IP address, device type, operating system, browser type and version, screen resolution, device identifiers (e.g., advertising identifiers, UDID)'
  - category: location
    text: 'Location Data: Approximate geographic location inferred from IP address.'
  - category: behavioral
    text: 'Usage Data: Pages and features accessed, clickstream data, session duration, frequency and timing of visits, navigation paths, referring and exit URLs, and interaction patterns with Platform features.'
  - category: financial
    text: Token balances and asset holdings visible through on-chain queries (to the extent necessary for Platform functionality).
  - category: communication
    text: Any information the User provides when raising queries, reporting issues, or submitting feedback regarding the Platform, which may include the content of the User’s communications
  deletion:
    route: Email team@legend.trade
    text: The User may request the deletion of personal information by contacting us at team@legend.trade . The Company will consider each request and may comply with such requests at its discretion.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Platform operation and service delivery
    text: Registering, authenticating, and managing User accounts;
  - purpose: Security, fraud prevention and compliance
    text: Detecting, investigating, and preventing fraudulent activity, market manipulation, and other violations of the Terms of Service;
  - purpose: Analytics and platform improvement
    text: Analyzing Platform usage patterns, feature engagement, and User behavior to improve Platform design, functionality, and user experience;
  - purpose: Marketing communications
    text: Send promotional and marketing communications, where the User has provided consent or where otherwise permitted by Applicable Data Protection Law;
  retention:
  - period: null
    scope: Personal Data generally
    text: The Company keeps Personal Data only for as long as necessary for the purposes described in this Policy, including to meet legal, regulatory, tax, and accounting requirements.
  rights:
  - right: access
    text: access the Personal Data the Company holds about the User and get a copy of it
  - right: rectification
    text: rectify inaccurate or incomplete Personal Data
  - right: erasure
    text: erase Personal Data
  - right: restriction
    text: restrict the processing of Personal Data
  - right: objection
    text: object to processing based on legitimate interests, and object at any time to processing for direct marketing
  - right: portability
    text: receive Personal Data in a structured, commonly used, and machine-readable format and transmit it to another controller (data portability)
  - right: withdraw consent
    text: withdraw consent at any time, where processing is based on consent
  role:
    text: Many Labs Inc. is the controller of Personal Data processed through the Platform for the purposes of the EU General Data Protection Regulation
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: The Company does not sell Personal Data to third parties within the meaning of Applicable Data Protection Law.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: the Company relies on the European Commission's Standard Contractual Clauses, the UK International Data Transfer Agreement or Addendum
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LegendTrade
provenance_date: '2026-11-09'
provider_name: LegendTrade
provider_slug: legendtrade
slug: legendtrade-privacy-policy
source_date: '2026-11-09'
source_filename: legendtrade-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.legend.trade/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LegendTrade\naid: legendtrade\nurl: https://www.legend.trade/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Many Labs Inc. is the controller of Personal Data processed through the Platform for the purposes of the\n    EU General Data Protection Regulation\ndata_categories:\n- category: identifying\n  text: Identifiers such as name, display name, username, date of birth, residential address, password, email address,\n    telephone number\n- category: device\n  text: 'Device and Browser Information: IP address, device type, operating system, browser type and version, screen\n    resolution,\
  \ device identifiers (e.g., advertising identifiers, UDID)'\n- category: location\n  text: 'Location Data: Approximate geographic location inferred from IP address.'\n- category: behavioral\n  text: 'Usage Data: Pages and features accessed, clickstream data, session duration, frequency and timing of visits,\n    navigation paths, referring and exit URLs, and interaction patterns with Platform features.'\n- category: financial\n  text: Token balances and asset holdings visible through on-chain queries (to the extent necessary for Platform\n    functionality).\n- category: communication\n  text: Any information the User provides when raising queries, reporting issues, or submitting feedback regarding\n    the Platform, which may include the content of the User’s communications\npurposes:\n- purpose: Platform operation and service delivery\n  text: Registering, authenticating, and managing User accounts;\n- purpose: Security, fraud prevention and compliance\n  text: Detecting, investigating,\
  \ and preventing fraudulent activity, market manipulation, and other violations\n    of the Terms of Service;\n- purpose: Analytics and platform improvement\n  text: Analyzing Platform usage patterns, feature engagement, and User behavior to improve Platform design, functionality,\n    and user experience;\n- purpose: Marketing communications\n  text: Send promotional and marketing communications, where the User has provided consent or where otherwise permitted\n    by Applicable Data Protection Law;\nretention:\n- scope: Personal Data generally\n  period: null\n  text: The Company keeps Personal Data only for as long as necessary for the purposes described in this Policy,\n    including to meet legal, regulatory, tax, and accounting requirements.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: the Company relies on the European Commission's Standard Contractual Clauses, the UK International Data\n    Transfer Agreement or Addendum\nsubprocessors:\n  url: null\n  text: null\ndpa:\n\
  \  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email team@legend.trade\n  text: The User may request the deletion of personal information by contacting us at team@legend.trade . The Company\n    will consider each request and may comply with such requests at its discretion.\nrights:\n- right: access\n  text: access the Personal Data the Company holds about the User and get a copy of it\n- right: rectification\n  text: rectify inaccurate or incomplete Personal Data\n- right: erasure\n  text: erase Personal Data\n- right: restriction\n  text: restrict the processing of Personal Data\n- right: objection\n  text: object to processing based on legitimate interests, and object at any time to processing for direct marketing\n- right: portability\n  text: receive Personal Data in a structured, commonly used, and machine-readable format and transmit it to another\n    controller (data portability)\n- right: withdraw consent\n  text: withdraw consent at any time, where processing\
  \ is based on consent\nsale_or_sharing:\n  stance: prohibited\n  text: The Company does not sell Personal Data to third parties within the meaning of Applicable Data Protection\n    Law.\n"
source_yaml_url: https://artifacts.apis.io/legendtrade/privacy/legendtrade-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from LegendTrade's own page on 2026-11-09.
synthetic: false
tags:
- Company
- DeFi
- Trading
- Cryptocurrency
- Perpetual Futures
- Social Trading
- Copy Trading
- Market Data
- Hyperliquid
- WebSocket
- Real-Time
---
