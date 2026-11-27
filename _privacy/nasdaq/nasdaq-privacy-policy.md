---
api_specs:
- filename: nasdaq-asyncapi.yml
  format: yaml
  label: Nasdaq Cloud Data Service (NCDS) — Kafka Streams
  slug: nasdaq-cloud-data-service-ncds-kafka-streams
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/nasdaq/asyncapi/nasdaq-asyncapi.yml
- filename: nasdaq-ncds-rest-postman-collection.json
  format: json
  label: Nasdaq Cloud Data Service (NCDS) REST API
  slug: nasdaq-cloud-data-service-ncds-rest-api
  spec_type: Postman
  url: https://artifacts.apis.io/nasdaq/postman/nasdaq-ncds-rest-postman-collection.json
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name (first and last); Email address; Social media username; Telephone number; Mailing address
  - category: financial
    text: Payment data (e.g., bank account or credit card number)
  - category: location
    text: general location information such as city, state or geographic area
  - category: behavioral
    text: Online activity data (such as pages or screens you viewed, how long you spent on a page or screen, the website you visited before browsing to the Service, navigation paths between pages or screens
  - category: device
    text: Device data (such as your computer or mobile device’s operating system type and version, manufacturer and model, browser type
  - category: communication
    text: Communications based on our exchanges with you, including when you contact us
  - category: professional
    text: Career or professional history and educational background
  - category: demographic
    text: Demographic data (such as your city, state, country of residence, postal code, and age)
  deletion:
    route: Account deletion through account portal or by contacting Nasdaq
    text: If you wish to cancel your account, you can do so at any time through your account portal or please contact us
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services and products
    text: Provide you (or your employer/represented company) with our services and products
  - purpose: Security and fraud monitoring
    text: Monitor for security threats and fraud involving the use of our products, services, Sites or physical facilities
  - purpose: Interest-based advertising
    text: We, our service providers and our third-party advertising partners may also Process your Information and details about your interactions
  - purpose: Marketing
    text: Develop, enhance and deliver marketing of our products and services and those of our advertisers, sponsors and partners
  retention:
  - period: null
    scope: General Information
    text: We will retain each category of Information identified above for as long as reasonably necessary to maintain the Sites, to meet legal and accounting obligations
  rights:
  - right: Access
    text: You can request a copy of the Personal Data that we have collected about you during the past 12 months.
  - right: Correction
    text: You can ask us to correct inaccurate Personal Data that we have collected about you.
  - right: Deletion
    text: You can ask us to delete the Personal Data that we have collected from you.
  - right: Opt-out of sale
    text: You may ask us not to “sell” Personal Data we have collected about you to third parties now or in the future.
  - right: Object to processing
    text: You have the right to object to the Processing of your Personal Data based on our legitimate interest.
  - right: Portability
    text: You have the right to receive certain of your Personal Data in a structured, commonly used and machine-readable format
  role:
    text: in our capacity as the controller of your Personal Data
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Except as otherwise described below, we do not sell Personal Data for money; however, like many companies, we use services that help deliver interest-based ads to you.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: the European Commission’s Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Nasdaq
provenance_date: '2026-11-10'
provider_name: Nasdaq
provider_slug: nasdaq
slug: nasdaq-privacy-policy
source_date: '2026-11-10'
source_filename: nasdaq-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.nasdaq.com/privacy-statement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Nasdaq\naid: nasdaq\nurl: https://www.nasdaq.com/privacy-statement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: in our capacity as the controller of your Personal Data\ndata_categories:\n- category: identifying\n  text: Name (first and last); Email address; Social media username; Telephone number; Mailing address\n- category: financial\n  text: Payment data (e.g., bank account or credit card number)\n- category: location\n  text: general location information such as city, state or geographic area\n- category: behavioral\n  text: Online activity data (such as pages or screens\
  \ you viewed, how long you spent on a page or screen, the website\n    you visited before browsing to the Service, navigation paths between pages or screens\n- category: device\n  text: Device data (such as your computer or mobile device’s operating system type and version, manufacturer and\n    model, browser type\n- category: communication\n  text: Communications based on our exchanges with you, including when you contact us\n- category: professional\n  text: Career or professional history and educational background\n- category: demographic\n  text: Demographic data (such as your city, state, country of residence, postal code, and age)\npurposes:\n- purpose: Provide services and products\n  text: Provide you (or your employer/represented company) with our services and products\n- purpose: Security and fraud monitoring\n  text: Monitor for security threats and fraud involving the use of our products, services, Sites or physical facilities\n- purpose: Interest-based advertising\n  text:\
  \ We, our service providers and our third-party advertising partners may also Process your Information and\n    details about your interactions\n- purpose: Marketing\n  text: Develop, enhance and deliver marketing of our products and services and those of our advertisers, sponsors\n    and partners\nretention:\n- scope: General Information\n  period: null\n  text: We will retain each category of Information identified above for as long as reasonably necessary to maintain\n    the Sites, to meet legal and accounting obligations\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: the European Commission’s Standard Contractual Clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion through account portal or by contacting Nasdaq\n  text: If you wish to cancel your account, you can do so at any time through your account portal or please contact\n    us\nrights:\n- right: Access\n  text: You can request a\
  \ copy of the Personal Data that we have collected about you during the past 12 months.\n- right: Correction\n  text: You can ask us to correct inaccurate Personal Data that we have collected about you.\n- right: Deletion\n  text: You can ask us to delete the Personal Data that we have collected from you.\n- right: Opt-out of sale\n  text: You may ask us not to “sell” Personal Data we have collected about you to third parties now or in the future.\n- right: Object to processing\n  text: You have the right to object to the Processing of your Personal Data based on our legitimate interest.\n- right: Portability\n  text: You have the right to receive certain of your Personal Data in a structured, commonly used and machine-readable\n    format\nsale_or_sharing:\n  stance: conditional\n  text: Except as otherwise described below, we do not sell Personal Data for money; however, like many companies,\n    we use services that help deliver interest-based ads to you.\n"
source_yaml_url: https://artifacts.apis.io/nasdaq/privacy/nasdaq-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Nasdaq's own page on 2026-11-10.
synthetic: false
tags:
- Data Marketplace
- Financial Data
- Fortune 1000
- Kafka
- Market Data
- Stock Exchange
- Streaming
- Financial Services
- Capital Markets
- Economics
---
