---
api_specs:
- filename: zopa-account-access-api-openapi.yml
  format: yaml
  label: zopa Account Access API
  slug: zopa-account-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-account-access-api-openapi.yml
- filename: zopa-accounts-api-openapi.yml
  format: yaml
  label: zopa Accounts API
  slug: zopa-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-accounts-api-openapi.yml
- filename: zopa-balances-api-openapi.yml
  format: yaml
  label: zopa Balances API
  slug: zopa-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-balances-api-openapi.yml
- filename: zopa-beneficiaries-api-openapi.yml
  format: yaml
  label: zopa Beneficiaries API
  slug: zopa-beneficiaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-beneficiaries-api-openapi.yml
- filename: zopa-direct-debits-api-openapi.yml
  format: yaml
  label: zopa Direct Debits API
  slug: zopa-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-direct-debits-api-openapi.yml
- filename: zopa-domestic-payments-api-openapi.yml
  format: yaml
  label: zopa Domestic Payments API
  slug: zopa-domestic-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-domestic-payments-api-openapi.yml
- filename: zopa-domestic-standing-orders-api-openapi.yml
  format: yaml
  label: zopa Domestic Standing Orders API
  slug: zopa-domestic-standing-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-domestic-standing-orders-api-openapi.yml
- filename: zopa-offers-api-openapi.yml
  format: yaml
  label: zopa Offers API
  slug: zopa-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-offers-api-openapi.yml
- filename: zopa-parties-api-openapi.yml
  format: yaml
  label: zopa Parties API
  slug: zopa-parties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-parties-api-openapi.yml
- filename: zopa-standing-orders-api-openapi.yml
  format: yaml
  label: zopa Standing Orders API
  slug: zopa-standing-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-standing-orders-api-openapi.yml
- filename: zopa-statements-api-openapi.yml
  format: yaml
  label: zopa Statements API
  slug: zopa-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-statements-api-openapi.yml
- filename: zopa-transactions-api-openapi.yml
  format: yaml
  label: zopa Transactions API
  slug: zopa-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zopa/openapi/zopa-transactions-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name Address Date of birth Telephone numbers Email address Photographic ID (passport, driving licence)
  - category: financial
    text: Bank account details Incomings and outgoings Employment status & benefit details
  - category: location
    text: IP address and geolocation data (used for regional personalisation)
  - category: behavioral
    text: 'Browsing Behaviour: Pages visited on the website, product views and clicks'
  - category: device
    text: 'Device and Browser Information: Device type (desktop, mobile, tablet), browser type and version, operating system information.'
  - category: health
    text: Special category data includes biometric data (physical, physiological or behavioural characteristics about you), health data, criminal convictions, and any religious or political data.
  deletion:
    route: Right to erasure request
    text: You can ask us to erase your personal data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Onboard and serve customers
    text: To onboard and serve you as a customer
  - purpose: Fraud prevention
    text: Prevent or detect attempted fraud, money laundering or other crime in your name
  - purpose: Advertising
    text: To display advertising to you across the web and on social media platforms
  - purpose: Automated decisions
    text: we'll use automated decision-making and profiling to decide whether to offer you a loan or credit card
  retention:
  - period: null
    scope: Customer relationship
    text: We will hold your information for as long as you have a relationship with us
  - period: up to six years
    scope: Fraud risk records
    text: if you're considered to be a fraud or money laundering risk, your information may be held for up to six years.
  rights:
  - right: Access
    text: You can ask for a copy of the personal data we hold about you (and other information relating to it)
  - right: Correction
    text: You can ask us to correct any personal data we hold about you which you believe is inaccurate.
  - right: Erasure
    text: You can ask us to erase your personal data
  - right: Restrict processing
    text: You can ask us to stop using your personal data
  - right: Portability
    text: you can ask us to give you your personal data in a structured, commonly used and machine-readable format or have it transmitted to another data controller.
  - right: Object
    text: You have a right to object whenever we are using personal data on the basis of our legitimate interests
  - right: Withdraw consent
    text: you can withdraw that consent at any time
  role:
    text: Rvvup Ltd acts as a separate and independent data controller in respect of those activities.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: zopa
provenance_date: '2026-11-10'
provider_name: zopa
provider_slug: zopa
slug: zopa-privacy-policy
source_date: '2026-11-10'
source_filename: zopa-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.zopa.com/privacy-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: zopa\naid: zopa\nurl: https://www.zopa.com/privacy-notice\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Rvvup Ltd acts as a separate and independent data controller in respect of those activities.\ndata_categories:\n- category: identifying\n  text: Name Address Date of birth Telephone numbers Email address Photographic ID (passport, driving licence)\n- category: financial\n  text: Bank account details Incomings and outgoings Employment status & benefit details\n- category: location\n  text: IP address and geolocation data (used for regional personalisation)\n- category: behavioral\n  text:\
  \ 'Browsing Behaviour: Pages visited on the website, product views and clicks'\n- category: device\n  text: 'Device and Browser Information: Device type (desktop, mobile, tablet), browser type and version, operating\n    system information.'\n- category: health\n  text: Special category data includes biometric data (physical, physiological or behavioural characteristics about\n    you), health data, criminal convictions, and any religious or political data.\npurposes:\n- purpose: Onboard and serve customers\n  text: To onboard and serve you as a customer\n- purpose: Fraud prevention\n  text: Prevent or detect attempted fraud, money laundering or other crime in your name\n- purpose: Advertising\n  text: To display advertising to you across the web and on social media platforms\n- purpose: Automated decisions\n  text: we'll use automated decision-making and profiling to decide whether to offer you a loan or credit card\nretention:\n- scope: Customer relationship\n  period: null\n  text:\
  \ We will hold your information for as long as you have a relationship with us\n- scope: Fraud risk records\n  period: up to six years\n  text: if you're considered to be a fraud or money laundering risk, your information may be held for up to six\n    years.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Right to erasure request\n  text: You can ask us to erase your personal data\nrights:\n- right: Access\n  text: You can ask for a copy of the personal data we hold about you (and other information relating to it)\n- right: Correction\n  text: You can ask us to correct any personal data we hold about you which you believe is inaccurate.\n- right: Erasure\n  text: You can ask us to erase your personal data\n- right: Restrict processing\n  text: You can ask us to stop using your personal data\n- right: Portability\n  text: you can ask us to give you your personal data in a structured, commonly\
  \ used and machine-readable format\n    or have it transmitted to another data controller.\n- right: Object\n  text: You have a right to object whenever we are using personal data on the basis of our legitimate interests\n- right: Withdraw consent\n  text: you can withdraw that consent at any time\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zopa/privacy/zopa-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 21 quoted statements, read from zopa's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Banking
- Fintech
- Open Banking
- PSD2
- Payments
- Account Information
- Payment Initiation
- FAPI
- United Kingdom
- Digital Bank
- Lending
---
