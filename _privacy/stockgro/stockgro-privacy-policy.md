---
api_specs:
- filename: stockgro-health-api-openapi.yml
  format: yaml
  label: StockGro Health API
  slug: stockgro-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stockgro/openapi/stockgro-health-api-openapi.yml
- filename: stockgro-process-api-openapi.yml
  format: yaml
  label: StockGro Process API
  slug: stockgro-process-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stockgro/openapi/stockgro-process-api-openapi.yml
- filename: stockgro-tradeview-intraday-model-api-api-openapi.yml
  format: yaml
  label: StockGro TradeView Intraday Model API
  slug: stockgro-tradeview-intraday-model-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stockgro/openapi/stockgro-tradeview-intraday-model-api-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Username
  - category: contact
    text: Mobile number
  - category: contact
    text: Access to Contact List
  - category: device
    text: User's IP address
  - category: identifying
    text: Date of birth
  - category: financial
    text: Sensitive Personal Information (“SPI”) from you on StockGro. SPI means such personal information which consists of passwords or financial information
  deletion:
    route: In-app account deletion via Profile > Edit > Delete My Account
    text: Scroll to the bottom of the page and click Delete My Account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate and provide services
    text: StockGro must receive or collect some information to operate, provide, improve, understand, customize, support, and market our Services
  - purpose: Fraud prevention and security
    text: prevent fraud and to ensure the safety and security of Users
  - purpose: Advertising statistics
    text: to measure traffic within the Portal and let advertisers know the geographic locations from where StockGro's visitors come
  - purpose: Marketing with commercial partners
    text: StockGro may share information as provided by you and data concerning your usage of the Services on the Portal with its commercial partners for the purpose of facilitating user engagement, for marketing and promotional purposes and other related purposes.
  residency:
  - region: India
    text: your information may be used in or transferred to countries other than India and you specifically consent to same
  retention:
  - period: 28 days
    scope: Deleted account restore window
    text: For up to 28 days, it is still possible to restore your Account if it was accidentally deleted.
  - period: null
    scope: Personal information after deletion
    text: After 28 days, we begin the process of deleting your personal information from our systems, unless
  rights:
  - right: Review, correct, update or modify information
    text: you may also review, correct, update or modify your information and user preferences by logging into your Profile page on StockGro.
  - right: Request account deletion
    text: Users are entitled to request StockGro to delete their User accounts and their personal information by following the below steps
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: StockGro may share information as provided by you and data concerning your usage of the Services on the Portal with its commercial partners for the purpose of facilitating user engagement, for marketing and promotional purposes and other related purposes.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: StockGro
provenance_date: '2026-11-10'
provider_name: StockGro
provider_slug: stockgro
slug: stockgro-privacy-policy
source_date: '2026-11-10'
source_filename: stockgro-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.stockgro.club/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: StockGro\naid: stockgro\nurl: https://www.stockgro.club/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Username\n- category: contact\n  text: Mobile number\n- category: contact\n  text: Access to Contact List\n- category: device\n  text: User's IP address\n- category: identifying\n  text: Date of birth\n- category: financial\n  text: Sensitive Personal Information (“SPI”) from you on StockGro. SPI means such personal information which consists\n    of passwords or financial information\npurposes:\n- purpose: Operate and provide\
  \ services\n  text: StockGro must receive or collect some information to operate, provide, improve, understand, customize, support,\n    and market our Services\n- purpose: Fraud prevention and security\n  text: prevent fraud and to ensure the safety and security of Users\n- purpose: Advertising statistics\n  text: to measure traffic within the Portal and let advertisers know the geographic locations from where StockGro's\n    visitors come\n- purpose: Marketing with commercial partners\n  text: StockGro may share information as provided by you and data concerning your usage of the Services on the\n    Portal with its commercial partners for the purpose of facilitating user engagement, for marketing and promotional\n    purposes and other related purposes.\nretention:\n- scope: Deleted account restore window\n  period: 28 days\n  text: For up to 28 days, it is still possible to restore your Account if it was accidentally deleted.\n- scope: Personal information after deletion\n  period:\
  \ null\n  text: After 28 days, we begin the process of deleting your personal information from our systems, unless\nresidency:\n- region: India\n  text: your information may be used in or transferred to countries other than India and you specifically consent\n    to same\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: In-app account deletion via Profile > Edit > Delete My Account\n  text: Scroll to the bottom of the page and click Delete My Account.\nrights:\n- right: Review, correct, update or modify information\n  text: you may also review, correct, update or modify your information and user preferences by logging into your\n    Profile page on StockGro.\n- right: Request account deletion\n  text: Users are entitled to request StockGro to delete their User accounts and their personal information by following\n    the below steps\nsale_or_sharing:\n  stance: conditional\n  text: StockGro may share information\
  \ as provided by you and data concerning your usage of the Services on the\n    Portal with its commercial partners for the purpose of facilitating user engagement, for marketing and promotional\n    purposes and other related purposes.\n"
source_yaml_url: https://artifacts.apis.io/stockgro/privacy/stockgro-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from StockGro's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Stock Market
- Investing
- Market Data
- Financial Education
- Fintech
- India
- Advisory
- Social Investing
---
