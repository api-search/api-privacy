---
api_specs:
- filename: police-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: Police Bank Banking Account Balances API
  slug: police-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/police-bank/openapi/police-bank-banking-account-balances-api-openapi.yml
- filename: police-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: Police Bank Banking Account Direct Debits API
  slug: police-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/police-bank/openapi/police-bank-banking-account-direct-debits-api-openapi.yml
- filename: police-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: Police Bank Banking Account Scheduled Payments API
  slug: police-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/police-bank/openapi/police-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: police-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: Police Bank Banking Account Transactions API
  slug: police-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/police-bank/openapi/police-bank-banking-account-transactions-api-openapi.yml
- filename: police-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: Police Bank Banking Accounts API
  slug: police-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/police-bank/openapi/police-bank-banking-accounts-api-openapi.yml
- filename: police-bank-banking-payees-api-openapi.yml
  format: yaml
  label: Police Bank Banking Payees API
  slug: police-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/police-bank/openapi/police-bank-banking-payees-api-openapi.yml
- filename: police-bank-banking-products-api-openapi.yml
  format: yaml
  label: Police Bank Banking Products API
  slug: police-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/police-bank/openapi/police-bank-banking-products-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, residential address, date of birth, gender and contact details
  - category: identifying
    text: identification information such as driver’s licence, passport details or Medicare card number
  - category: financial
    text: account transaction history or credit information
  - category: financial
    text: financial position and transaction history and/or credit history
  - category: health
    text: health information
  - category: biometric
    text: biometrics (fingerprints)
  - category: behavioral
    text: details about when and how you interact with us include telephone call recordings, emails or notes on our internal systems
  - category: device
    text: your IP address, location, mobile device and network information
  - category: professional
    text: occupation, place of employment and previous employment details
  deletion:
    route: null
    text: Where permitted by law we will destroy or de-identify information that is no longer needed.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: verify identity
    text: verify your identity in line with applicable Australian laws and regulations
  - purpose: assess credit applications
    text: assess your application for a product or a service, including applications for credit
  - purpose: fraud and crime prevention
    text: minimise risks, identify or investigate fraud and other illegal activities
  - purpose: marketing
    text: inform you about products and services that may be of interest to you and for marketing purposes
  - purpose: legal compliance
    text: comply with our legal obligations and assist government and law enforcement agencies
  retention:
  - period: null
    scope: information no longer needed
    text: Where permitted by law we will destroy or de-identify information that is no longer needed.
  rights:
  - right: access
    text: You can request access to detailed personal and account information that we hold on record, at any time by contacting us on details provided below.
  - right: correction
    text: if the information we hold on file about you is incorrect, incomplete or not current you can request we correct it.
  - right: complaint
    text: If we have given the information to a third party, we can notify them of the correction.
  - right: opt out of direct marketing
    text: You can opt out of receiving direct marketing material at any time
  role:
    text: Police Bank Limited (‘the Bank’) is a member owned bank that provides a range of banking and financial products and services.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We may disclose your information to third parties that are based overseas such as Convera or international banks when processing cross border transactions or telegraphic transfers to other countries.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Police Bank
provenance_date: '2026-11-10'
provider_name: Police Bank
provider_slug: police-bank
slug: police-bank-privacy-policy
source_date: '2026-11-10'
source_filename: police-bank-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.policebank.com.au/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Police Bank\naid: police-bank\nurl: https://www.policebank.com.au/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Police Bank Limited (‘the Bank’) is a member owned bank that provides a range of banking and financial products\n    and services.\ndata_categories:\n- category: identifying\n  text: name, residential address, date of birth, gender and contact details\n- category: identifying\n  text: identification information such as driver’s licence, passport details or Medicare card number\n- category: financial\n  text: account transaction history or credit information\n- category:\
  \ financial\n  text: financial position and transaction history and/or credit history\n- category: health\n  text: health information\n- category: biometric\n  text: biometrics (fingerprints)\n- category: behavioral\n  text: details about when and how you interact with us include telephone call recordings, emails or notes on our\n    internal systems\n- category: device\n  text: your IP address, location, mobile device and network information\n- category: professional\n  text: occupation, place of employment and previous employment details\npurposes:\n- purpose: verify identity\n  text: verify your identity in line with applicable Australian laws and regulations\n- purpose: assess credit applications\n  text: assess your application for a product or a service, including applications for credit\n- purpose: fraud and crime prevention\n  text: minimise risks, identify or investigate fraud and other illegal activities\n- purpose: marketing\n  text: inform you about products and services that\
  \ may be of interest to you and for marketing purposes\n- purpose: legal compliance\n  text: comply with our legal obligations and assist government and law enforcement agencies\nretention:\n- scope: information no longer needed\n  period: null\n  text: Where permitted by law we will destroy or de-identify information that is no longer needed.\nresidency: []\ntransfers:\n- mechanism: other\n  text: We may disclose your information to third parties that are based overseas such as Convera or international\n    banks when processing cross border transactions or telegraphic transfers to other countries.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: Where permitted by law we will destroy or de-identify information that is no longer needed.\nrights:\n- right: access\n  text: You can request access to detailed personal and account information that we hold on record, at any time\n    by contacting us on details\
  \ provided below.\n- right: correction\n  text: if the information we hold on file about you is incorrect, incomplete or not current you can request we\n    correct it.\n- right: complaint\n  text: If we have given the information to a third party, we can notify them of the correction.\n- right: opt out of direct marketing\n  text: You can opt out of receiving direct marketing material at any time\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/police-bank/privacy/police-bank-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 22 quoted statements, read from Police Bank's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Banking
- Australia
- Mutual Bank
- Product Reference Data
---
