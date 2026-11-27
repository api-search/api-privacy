---
api_specs:
- filename: ubank-banking-account-balances-api-openapi.yml
  format: yaml
  label: ubank Banking Account Balances API
  slug: ubank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubank/openapi/ubank-banking-account-balances-api-openapi.yml
- filename: ubank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: ubank Banking Account Direct Debits API
  slug: ubank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubank/openapi/ubank-banking-account-direct-debits-api-openapi.yml
- filename: ubank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: ubank Banking Account Scheduled Payments API
  slug: ubank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubank/openapi/ubank-banking-account-scheduled-payments-api-openapi.yml
- filename: ubank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: ubank Banking Account Transactions API
  slug: ubank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubank/openapi/ubank-banking-account-transactions-api-openapi.yml
- filename: ubank-banking-accounts-api-openapi.yml
  format: yaml
  label: ubank Banking Accounts API
  slug: ubank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubank/openapi/ubank-banking-accounts-api-openapi.yml
- filename: ubank-banking-payees-api-openapi.yml
  format: yaml
  label: ubank Banking Payees API
  slug: ubank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubank/openapi/ubank-banking-payees-api-openapi.yml
- filename: ubank-banking-products-api-openapi.yml
  format: yaml
  label: ubank Banking Products API
  slug: ubank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ubank/openapi/ubank-banking-products-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: your identification information such as your name, address, date of birth, contact details
  - category: financial
    text: your financial and transaction information
  - category: location
    text: your location and device information, IP address
  - category: health
    text: health and biometric information, for example video footage or photographs of your face where permitted
  - category: device
    text: information about how you interact with our app, website and the device you use to access them
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: confirm identity
    text: confirm your identity
  - purpose: marketing
    text: tell you about products or services (including those of third parties or related companies) that we think you might be interested in, unless you opt-out
  - purpose: fraud prevention
    text: help prevent fraud or identify theft
  - purpose: AI training
    text: training AI models
  retention:
  - period: five years
    scope: credit reporting information
    text: Your credit report will usually only contain information from the past five years.
  - period: null
    scope: personal information no longer needed
    text: If we no longer need your information, we will take reasonable steps to destroy or de-identify it.
  rights:
  - right: access
    text: How you can access your information
  - right: correction
    text: How you can correct your information
  - right: complaint to OAIC
    text: you may complain to the Office of the Australian Information Commissioner (OAIC)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We may share your personal information with contracted service providers and other organisations with overseas operations
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ubank
provenance_date: '2026-11-10'
provider_name: ubank
provider_slug: ubank
slug: ubank-privacy-policy
source_date: '2026-11-10'
source_filename: ubank-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.ubank.com.au/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ubank\naid: ubank\nurl: https://www.ubank.com.au/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your identification information such as your name, address, date of birth, contact details\n- category: financial\n  text: your financial and transaction information\n- category: location\n  text: your location and device information, IP address\n- category: health\n  text: health and biometric information, for example video footage or photographs of your face where permitted\n- category: device\n  text: information about how you interact\
  \ with our app, website and the device you use to access them\npurposes:\n- purpose: confirm identity\n  text: confirm your identity\n- purpose: marketing\n  text: tell you about products or services (including those of third parties or related companies) that we think\n    you might be interested in, unless you opt-out\n- purpose: fraud prevention\n  text: help prevent fraud or identify theft\n- purpose: AI training\n  text: training AI models\nretention:\n- scope: credit reporting information\n  period: five years\n  text: Your credit report will usually only contain information from the past five years.\n- scope: personal information no longer needed\n  period: null\n  text: If we no longer need your information, we will take reasonable steps to destroy or de-identify it.\nresidency: []\ntransfers:\n- mechanism: other\n  text: We may share your personal information with contracted service providers and other organisations with overseas\n    operations\nsubprocessors:\n  url: null\n\
  \  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: How you can access your information\n- right: correction\n  text: How you can correct your information\n- right: complaint to OAIC\n  text: you may complain to the Office of the Australian Information Commissioner (OAIC)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ubank/privacy/ubank-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- rights
summary_line: 15 quoted statements, read from ubank's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Banks
- Banking
- Open Banking
- CDR
- Consumer Data Right
- Product Reference Data
- Digital Bank
- Consumer Banking
- Australia
---
