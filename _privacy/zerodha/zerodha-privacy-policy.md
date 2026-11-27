---
api_specs:
- filename: zerodha-alerts-api-openapi.yml
  format: yaml
  label: Zerodha Alerts API
  slug: zerodha-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-alerts-api-openapi.yml
- filename: zerodha-gtt-api-openapi.yml
  format: yaml
  label: Zerodha Gtt API
  slug: zerodha-gtt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-gtt-api-openapi.yml
- filename: zerodha-orders-api-openapi.yml
  format: yaml
  label: Zerodha Orders API
  slug: zerodha-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-orders-api-openapi.yml
- filename: zerodha-portfolio-api-openapi.yml
  format: yaml
  label: Zerodha Portfolio API
  slug: zerodha-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-portfolio-api-openapi.yml
- filename: zerodha-session-api-openapi.yml
  format: yaml
  label: Zerodha Session API
  slug: zerodha-session-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-session-api-openapi.yml
- filename: zerodha-trades-api-openapi.yml
  format: yaml
  label: Zerodha Trades API
  slug: zerodha-trades-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-trades-api-openapi.yml
- filename: zerodha-user-api-openapi.yml
  format: yaml
  label: Zerodha User API
  slug: zerodha-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerodha/openapi/zerodha-user-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, contact number, gender, date of birth, residence and employment addresses
  - category: financial
    text: Bank account or credit card or debit card or other payment instrument details
  - category: identifying
    text: scans/copies of document proofs of address & identity such as Photograph, PAN, passport, drivers license, Aadhaar (voluntarily)
  - category: device
    text: IP (internet protocol) addresses, browser types, the name of your ISP (internet service provider)
  - category: behavioral
    text: which pages/URLs do You click on the Zerodha website / mobile application, and the amount of time spent on each
  - category: behavioral
    text: profiling information (age, gender, income etc)
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: identity verification and KYC/AML
    text: identity verification and background checking for account opening as per KYC & AML Rules
  - purpose: personalised services and updates
    text: personalising services offered to you, keeping you updated of our products and services relevant to you
  - purpose: legal and regulatory purposes
    text: for any legal and regulatory / audit purposes
  - purpose: fraud prevention
    text: To prevent, detect, investigate and prosecute fraud and alleged fraud, money laundering and other crimes
  - purpose: service improvement
    text: to evaluate, develop or improve our services
  retention:
  - period: null
    scope: information collected for account opening
    text: We would save such information as required by the law, and as directed by the regulators along with such intermediaries regulated by them
  rights:
  - right: deletion or correction
    text: You may request your data be deleted or corrected
  - right: access
    text: You may request for access of any data that has been stored by Zerodha for providing You services
  - right: portability
    text: You may request storable & readable data to be transferred to another party
  role:
    text: Zerodha shall process any personal data we collect from you in accordance with Data Protection Legislation and the provisions of this Policy.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Under no circumstances will we sell or rent your personal information to anyone, for any reason, at any time.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Zerodha
provenance_date: '2026-11-10'
provider_name: Zerodha
provider_slug: zerodha
slug: zerodha-privacy-policy
source_date: '2026-11-10'
source_filename: zerodha-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://zerodha.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Zerodha\naid: zerodha\nurl: https://zerodha.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Zerodha shall process any personal data we collect from you in accordance with Data Protection Legislation\n    and the provisions of this Policy.\ndata_categories:\n- category: identifying\n  text: name, contact number, gender, date of birth, residence and employment addresses\n- category: financial\n  text: Bank account or credit card or debit card or other payment instrument details\n- category: identifying\n  text: scans/copies of document proofs of address & identity such as\
  \ Photograph, PAN, passport, drivers license,\n    Aadhaar (voluntarily)\n- category: device\n  text: IP (internet protocol) addresses, browser types, the name of your ISP (internet service provider)\n- category: behavioral\n  text: which pages/URLs do You click on the Zerodha website / mobile application, and the amount of time spent\n    on each\n- category: behavioral\n  text: profiling information (age, gender, income etc)\npurposes:\n- purpose: identity verification and KYC/AML\n  text: identity verification and background checking for account opening as per KYC & AML Rules\n- purpose: personalised services and updates\n  text: personalising services offered to you, keeping you updated of our products and services relevant to you\n- purpose: legal and regulatory purposes\n  text: for any legal and regulatory / audit purposes\n- purpose: fraud prevention\n  text: To prevent, detect, investigate and prosecute fraud and alleged fraud, money laundering and other crimes\n- purpose: service\
  \ improvement\n  text: to evaluate, develop or improve our services\nretention:\n- scope: information collected for account opening\n  period: null\n  text: We would save such information as required by the law, and as directed by the regulators along with such\n    intermediaries regulated by them\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: deletion or correction\n  text: You may request your data be deleted or corrected\n- right: access\n  text: You may request for access of any data that has been stored by Zerodha for providing You services\n- right: portability\n  text: You may request storable & readable data to be transferred to another party\nsale_or_sharing:\n  stance: prohibited\n  text: Under no circumstances will we sell or rent your personal information to anyone, for any reason, at any\n    time.\n"
source_yaml_url: https://artifacts.apis.io/zerodha/privacy/zerodha-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Zerodha's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Trading
- Fintech
---
