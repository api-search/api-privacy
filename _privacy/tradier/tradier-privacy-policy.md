---
api_specs:
- filename: tradier-asyncapi.yml
  format: yaml
  label: Tradier Streaming API
  slug: streaming-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/tradier/asyncapi/tradier-asyncapi.yml
- filename: tradier-accounts-api-openapi.yml
  format: yaml
  label: Tradier Accounts API
  slug: tradier-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradier/openapi/tradier-accounts-api-openapi.yml
- filename: tradier-market-data-api-openapi.yml
  format: yaml
  label: Tradier Market Data API
  slug: tradier-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradier/openapi/tradier-market-data-api-openapi.yml
- filename: tradier-options-api-openapi.yml
  format: yaml
  label: Tradier Options API
  slug: tradier-options-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradier/openapi/tradier-options-api-openapi.yml
- filename: tradier-streaming-api-openapi.yml
  format: yaml
  label: Tradier Streaming API
  slug: tradier-streaming-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradier/openapi/tradier-streaming-api-openapi.yml
- filename: tradier-trading-api-openapi.yml
  format: yaml
  label: Tradier Trading API
  slug: tradier-trading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradier/openapi/tradier-trading-api-openapi.yml
- filename: tradier-user-api-openapi.yml
  format: yaml
  label: Tradier User API
  slug: tradier-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradier/openapi/tradier-user-api-openapi.yml
- filename: tradier-watchlists-api-openapi.yml
  format: yaml
  label: Tradier Watchlists API
  slug: tradier-watchlists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tradier/openapi/tradier-watchlists-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: Such information may include your name, mailing address, email address, home phone number, mobile phone number, Social Security number, date of birth, and/or your employer's name and address.
  - category: financial
    text: the Company may also collect, but is not limited to, your approximate annual income and net worth
  - category: demographic
    text: 'Additional demographic information Tradier may collect includes, but is not limited to, the following: gender, education, occupation, trade experience, and investment objectives.'
  - category: behavioral
    text: The Company may disclose customer information from its database and admin systems to help the Company analyze and identify the needs of its customer base.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account servicing and transactions
    text: The information the Company gathers is necessary to communicate with you about your account, to process transactions for you, and to comply with federal and state laws, including tax and anti-money laundering laws.
  - purpose: marketing
    text: The Company uses cookies for marketing purposes, to collect information about customers' identities as they interact with the website and trading platform, and to manage personalized settings on the website.
  - purpose: suitability assessment
    text: Federal law requires Tradier to assess your suitability for trading in a margin account.
  - purpose: product development
    text: The Company may also use demographic information on its customers provided by other third parties in order to develop new products, support new lines of business, and establish new services for customers.
  retention:
  - period: null
    scope: broker-dealer records
    text: Customers should be aware that there are published regulatory requirements that request that customer information be retained and accessible by broker-dealers for a specified period of time after an account is closed.
  rights:
  - right: review, change or correct PII
    text: You can review, change, or correct any of your PII at any time.
  - right: opt out of marketing emails
    text: If you opt-opt of marketing emails regarding news about new products and services, Tradier will always honor your request.
  - right: limit cookies
    text: Customers may generally disable the cookie feature on their browser without affecting their ability to use Tradier's website
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: the Company does not sell, license, lease or otherwise disclose your personal information to any third party for any reason other than the purposes described below
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Tradier
provenance_date: '2026-11-10'
provider_name: Tradier
provider_slug: tradier
slug: tradier-privacy-policy
source_date: '2026-11-10'
source_filename: tradier-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tradier.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Tradier\naid: tradier\nurl: https://tradier.com/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Such information may include your name, mailing address, email address, home phone number, mobile phone\n    number, Social Security number, date of birth, and/or your employer's name and address.\n- category: financial\n  text: the Company may also collect, but is not limited to, your approximate annual income and net worth\n- category: demographic\n  text: 'Additional demographic information Tradier may collect includes,\
  \ but is not limited to, the following:\n    gender, education, occupation, trade experience, and investment objectives.'\n- category: behavioral\n  text: The Company may disclose customer information from its database and admin systems to help the Company analyze\n    and identify the needs of its customer base.\npurposes:\n- purpose: account servicing and transactions\n  text: The information the Company gathers is necessary to communicate with you about your account, to process\n    transactions for you, and to comply with federal and state laws, including tax and anti-money laundering laws.\n- purpose: marketing\n  text: The Company uses cookies for marketing purposes, to collect information about customers' identities as they\n    interact with the website and trading platform, and to manage personalized settings on the website.\n- purpose: suitability assessment\n  text: Federal law requires Tradier to assess your suitability for trading in a margin account.\n- purpose: product development\n\
  \  text: The Company may also use demographic information on its customers provided by other third parties in order\n    to develop new products, support new lines of business, and establish new services for customers.\nretention:\n- scope: broker-dealer records\n  period: null\n  text: Customers should be aware that there are published regulatory requirements that request that customer information\n    be retained and accessible by broker-dealers for a specified period of time after an account is closed.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: review, change or correct PII\n  text: You can review, change, or correct any of your PII at any time.\n- right: opt out of marketing emails\n  text: If you opt-opt of marketing emails regarding news about new products and services, Tradier will always honor\n    your request.\n- right: limit cookies\n \
  \ text: Customers may generally disable the cookie feature on their browser without affecting their ability to use\n    Tradier's website\nsale_or_sharing:\n  stance: prohibited\n  text: the Company does not sell, license, lease or otherwise disclose your personal information to any third party\n    for any reason other than the purposes described below\n"
source_yaml_url: https://artifacts.apis.io/tradier/privacy/tradier-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from Tradier's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Trading
- Stocks
- Options
- Brokerage
- Streaming
- Real-Time
- Investing
- Financial Services
---
