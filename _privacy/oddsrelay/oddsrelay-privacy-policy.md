---
api_specs:
- filename: oddsrelay-account-api-openapi.yml
  format: yaml
  label: OddsRelay Account API
  slug: oddsrelay-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oddsrelay/openapi/oddsrelay-account-api-openapi.yml
- filename: oddsrelay-discovery-api-openapi.yml
  format: yaml
  label: OddsRelay Discovery API
  slug: oddsrelay-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oddsrelay/openapi/oddsrelay-discovery-api-openapi.yml
- filename: oddsrelay-odds-api-openapi.yml
  format: yaml
  label: OddsRelay Odds API
  slug: oddsrelay-odds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oddsrelay/openapi/oddsrelay-odds-api-openapi.yml
- filename: oddsrelay-service-api-openapi.yml
  format: yaml
  label: OddsRelay Service API
  slug: oddsrelay-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/oddsrelay/openapi/oddsrelay-service-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Signup details : email address, what you will use the data for and whether it is for business or personal use, your region, your product-news choice'
  - category: contact
    text: 'Billing details : billing name and address, country, a business name if you give one, card country, the country you connected from, payment and invoice records'
  - category: device
    text: 'API usage records : API key identifier, IP address, browser or app name, product and region requested, the filters you sent, time, status, response size, and tokens charged'
  - category: behavioral
    text: 'Website analytics : pages viewed, aggregate usage'
  - category: financial
    text: 'Affiliates'' details : if you join our affiliate programme, your name, email address, payout details (bank account or PayPal)'
  deletion:
    route: Email hello@oddsrelay.io
    text: To exercise any of these, email hello@oddsrelay.io.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and security
    text: To create your account and keep a record of your acceptance (performance of a contract; legitimate interest in keeping proof that you accepted our terms)
  - purpose: Payment and tax
    text: To take payment, apply consumer rights, and meet our accounting and tax obligations (performance of a contract; legal obligation)
  - purpose: API operation and monitoring
    text: To run, secure, and monitor the Service, prevent abuse, count tokens, and show your team its usage (legitimate interest; performance of a contract)
  - purpose: Business outreach
    text: To offer OddsRelay to businesses and sellers who could use it (legitimate interest)
  residency:
  - region: UK
    text: Supabase Accounts, sign-in, team members, signup answers, enquiries, and feedback sent from the dashboard UK (London).
  - region: EU (France)
    text: 'OVH Servers for the API: API keys, usage records, and request logs EU (France)'
  retention:
  - period: 90 days
    scope: API request log
    text: 'API request log: time, key, product, the filters you sent, status, size, tokens charged, IP address, browser or app name 90 days, plus up to 35 days in backups'
  - period: 6 years
    scope: Invoices and payment records
    text: Invoices and payment records 6 years
  - period: 30 days
    scope: Outreach contacts found but never contacted
    text: Outreach contacts we found but never contacted 30 days from when we found them
  rights:
  - right: access
    text: access a copy of your personal data
  - right: rectification
    text: have inaccurate data corrected
  - right: erasure
    text: have data erased
  - right: restriction
    text: restrict processing
  - right: portability
    text: receive certain data in a portable format
  - right: object
    text: Where we rely on legitimate interests, you can object at any time by emailing hello@oddsrelay.io.
  role:
    text: We are the data controller for the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: We use these service providers ("processors") to run OddsRelay. They process personal data only on our instructions
    url: null
  transfers:
  - mechanism: other
    text: we rely on appropriate safeguards, such as the UK International Data Transfer Agreement or Addendum, or UK-recognised adequacy
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: OddsRelay
provenance_date: '2026-11-10'
provider_name: OddsRelay
provider_slug: oddsrelay
slug: oddsrelay-privacy-policy
source_date: '2026-11-10'
source_filename: oddsrelay-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://oddsrelay.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: OddsRelay\naid: oddsrelay\nurl: https://oddsrelay.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the data controller for the personal data described here.\ndata_categories:\n- category: identifying\n  text: 'Signup details : email address, what you will use the data for and whether it is for business or personal\n    use, your region, your product-news choice'\n- category: contact\n  text: 'Billing details : billing name and address, country, a business name if you give one, card country, the\n    country you connected from, payment and invoice records'\n- category: device\n\
  \  text: 'API usage records : API key identifier, IP address, browser or app name, product and region requested,\n    the filters you sent, time, status, response size, and tokens charged'\n- category: behavioral\n  text: 'Website analytics : pages viewed, aggregate usage'\n- category: financial\n  text: 'Affiliates'' details : if you join our affiliate programme, your name, email address, payout details (bank\n    account or PayPal)'\npurposes:\n- purpose: Account creation and security\n  text: To create your account and keep a record of your acceptance (performance of a contract; legitimate interest\n    in keeping proof that you accepted our terms)\n- purpose: Payment and tax\n  text: To take payment, apply consumer rights, and meet our accounting and tax obligations (performance of a contract;\n    legal obligation)\n- purpose: API operation and monitoring\n  text: To run, secure, and monitor the Service, prevent abuse, count tokens, and show your team its usage (legitimate\n    interest;\
  \ performance of a contract)\n- purpose: Business outreach\n  text: To offer OddsRelay to businesses and sellers who could use it (legitimate interest)\nretention:\n- scope: API request log\n  period: 90 days\n  text: 'API request log: time, key, product, the filters you sent, status, size, tokens charged, IP address, browser\n    or app name 90 days, plus up to 35 days in backups'\n- scope: Invoices and payment records\n  period: 6 years\n  text: Invoices and payment records 6 years\n- scope: Outreach contacts found but never contacted\n  period: 30 days\n  text: Outreach contacts we found but never contacted 30 days from when we found them\nresidency:\n- region: UK\n  text: Supabase Accounts, sign-in, team members, signup answers, enquiries, and feedback sent from the dashboard\n    UK (London).\n- region: EU (France)\n  text: 'OVH Servers for the API: API keys, usage records, and request logs EU (France)'\ntransfers:\n- mechanism: other\n  text: we rely on appropriate safeguards, such\
  \ as the UK International Data Transfer Agreement or Addendum, or\n    UK-recognised adequacy\nsubprocessors:\n  url: null\n  text: We use these service providers (\"processors\") to run OddsRelay. They process personal data only on our instructions\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@oddsrelay.io\n  text: To exercise any of these, email hello@oddsrelay.io.\nrights:\n- right: access\n  text: access a copy of your personal data\n- right: rectification\n  text: have inaccurate data corrected\n- right: erasure\n  text: have data erased\n- right: restriction\n  text: restrict processing\n- right: portability\n  text: receive certain data in a portable format\n- right: object\n  text: Where we rely on legitimate interests, you can object at any time by emailing hello@oddsrelay.io.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/oddsrelay/privacy/oddsrelay-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from OddsRelay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sports Betting
- Odds
- Sports Data
- Matched Betting
- Data Feed
---
