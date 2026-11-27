---
api_specs:
- filename: tradingview-account-api-openapi.yml
  format: yaml
  label: TradingView Account API
  slug: tradingview-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-account-api-openapi.yml
- filename: tradingview-authorization-api-openapi.yml
  format: yaml
  label: TradingView Authorization API
  slug: tradingview-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-authorization-api-openapi.yml
- filename: tradingview-broker-configuration-api-openapi.yml
  format: yaml
  label: TradingView Broker Configuration API
  slug: tradingview-broker-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-broker-configuration-api-openapi.yml
- filename: tradingview-data-integration-api-openapi.yml
  format: yaml
  label: TradingView Data Integration API
  slug: tradingview-data-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-data-integration-api-openapi.yml
- filename: tradingview-data-permissions-api-openapi.yml
  format: yaml
  label: TradingView Data Permissions API
  slug: tradingview-data-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-data-permissions-api-openapi.yml
- filename: tradingview-market-data-api-openapi.yml
  format: yaml
  label: TradingView Market Data API
  slug: tradingview-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-market-data-api-openapi.yml
- filename: tradingview-trading-api-openapi.yml
  format: yaml
  label: TradingView Trading API
  slug: tradingview-trading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradingview/openapi/tradingview-trading-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: your username, email address; your account information with one of the following social Internet services
  - category: contact
    text: if you want to buy a subscription, we will need your first name, last name and postal address
  - category: financial
    text: our third party payment processor will also process information about your payment card and bank account information or payment account information
  - category: device
    text: IP address of the device (from which we can also infer the country you are connecting from), device type, operating system, application and browser version
  - category: behavioral
    text: website, and application interaction events
  - category: communication
    text: We also process any personal data you choose to give when corresponding with us by phone, email, or otherwise visiting and interacting with this Website
  deletion:
    route: Settings or request to delete account
    text: You may refuse to use our Website and/or application and may ask us to delete your account in the Settings .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide services and account access
    text: We use personal data in various ways that are necessary to provide the services you intend to use
  - purpose: analytics and improvement
    text: We use this information to analyze and improve the work of our services and applications
  - purpose: advertising and remarketing
    text: We display advertising on the Website and may use remarketing and tracking features.
  - purpose: fraud and spam prevention
    text: We collect this information to prevent spam and abuse of our services.
  residency:
  - region: United States, European Union, and other destinations
    text: The information collected through Services will be stored on servers located in the United States, European Union, and other destinations (including outside the EEA)
  retention:
  - period: until you decide to delete your account (upon request)
    scope: account data
    text: We will keep your personal data (1) until you decide to delete your account (upon request)
  - period: extending up to 10 years
    scope: legal and financial records
    text: The duration of retention for each type of data will comply with specific legal requirements, extending up to 10 years.
  - period: 1 year
    scope: AI monitoring and logging records
    text: Monitoring and logging records containing prompts and outputs are kept for 1 year and then deleted.
  - period: 30 days
    scope: account deletion
    text: Your account will be deleted after 30 days.
  rights:
  - right: access
    text: we will confirm whether or not we are processing your personal data and if so, we will provide you with a copy of that personal data
  - right: rectification
    text: You have the right to have inaccurate personal data rectified or completed if it is incomplete.
  - right: objection
    text: ask us to stop processing your personal data at any time, and we will do so.
  - right: restriction
    text: You may ask us to restrict or 'block' the processing of your personal data in certain circumstances
  - right: portability
    text: You have the right to obtain your personal data from us
  - right: deletion
    text: You have the right to refuse to use our Services and may ask us to delete or remove your personal data in certain circumstances.
  - right: withdraw consent
    text: you have the right to withdraw that consent at any time.
  role:
    text: TradingView is the data controller responsible for your personal data
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Separately, we do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: we will take the necessary steps to ensure your information receives an adequate level of security protection where it is processed
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TradingView
provenance_date: '2026-11-10'
provider_name: TradingView
provider_slug: tradingview
slug: tradingview-privacy-policy
source_date: '2026-11-10'
source_filename: tradingview-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.tradingview.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TradingView\naid: tradingview\nurl: https://www.tradingview.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: TradingView is the data controller responsible for your personal data\ndata_categories:\n- category: identifying\n  text: your username, email address; your account information with one of the following social Internet services\n- category: contact\n  text: if you want to buy a subscription, we will need your first name, last name and postal address\n- category: financial\n  text: our third party payment processor will also process information about your payment card\
  \ and bank account\n    information or payment account information\n- category: device\n  text: IP address of the device (from which we can also infer the country you are connecting from), device type,\n    operating system, application and browser version\n- category: behavioral\n  text: website, and application interaction events\n- category: communication\n  text: We also process any personal data you choose to give when corresponding with us by phone, email, or otherwise\n    visiting and interacting with this Website\npurposes:\n- purpose: provide services and account access\n  text: We use personal data in various ways that are necessary to provide the services you intend to use\n- purpose: analytics and improvement\n  text: We use this information to analyze and improve the work of our services and applications\n- purpose: advertising and remarketing\n  text: We display advertising on the Website and may use remarketing and tracking features.\n- purpose: fraud and spam prevention\n\
  \  text: We collect this information to prevent spam and abuse of our services.\nretention:\n- scope: account data\n  period: until you decide to delete your account (upon request)\n  text: We will keep your personal data (1) until you decide to delete your account (upon request)\n- scope: legal and financial records\n  period: extending up to 10 years\n  text: The duration of retention for each type of data will comply with specific legal requirements, extending\n    up to 10 years.\n- scope: AI monitoring and logging records\n  period: 1 year\n  text: Monitoring and logging records containing prompts and outputs are kept for 1 year and then deleted.\n- scope: account deletion\n  period: 30 days\n  text: Your account will be deleted after 30 days.\nresidency:\n- region: United States, European Union, and other destinations\n  text: The information collected through Services will be stored on servers located in the United States, European\n    Union, and other destinations (including outside\
  \ the EEA)\ntransfers:\n- mechanism: other\n  text: we will take the necessary steps to ensure your information receives an adequate level of security protection\n    where it is processed\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings or request to delete account\n  text: You may refuse to use our Website and/or application and may ask us to delete your account in the Settings\n    .\nrights:\n- right: access\n  text: we will confirm whether or not we are processing your personal data and if so, we will provide you with\n    a copy of that personal data\n- right: rectification\n  text: You have the right to have inaccurate personal data rectified or completed if it is incomplete.\n- right: objection\n  text: ask us to stop processing your personal data at any time, and we will do so.\n- right: restriction\n  text: You may ask us to restrict or 'block' the processing of your personal data in certain circumstances\n\
  - right: portability\n  text: You have the right to obtain your personal data from us\n- right: deletion\n  text: You have the right to refuse to use our Services and may ask us to delete or remove your personal data in\n    certain circumstances.\n- right: withdraw consent\n  text: you have the right to withdraw that consent at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: Separately, we do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/tradingview/privacy/tradingview-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from TradingView's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Charts
- Charting Library
- Financial Data
- Market Data
- Widgets
- Trading
- Fintech
- Embeddable Components
---
