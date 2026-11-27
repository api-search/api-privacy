---
api_specs:
- filename: postman_collection.quickstreamapi.json
  format: json
  label: Westpac QuickStream REST API
  slug: westpac-quickstream-rest-api
  spec_type: Postman
  url: https://quickstream.westpac.com.au/docs/downloads/postman_collection.quickstreamapi.json
- filename: westpac-banking-account-balances-api-openapi.yml
  format: yaml
  label: Westpac Banking Corporation Banking Account Balances API
  slug: westpac-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/westpac/openapi/westpac-banking-account-balances-api-openapi.yml
- filename: westpac-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: Westpac Banking Corporation Banking Account Direct Debits API
  slug: westpac-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/westpac/openapi/westpac-banking-account-direct-debits-api-openapi.yml
- filename: westpac-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: Westpac Banking Corporation Banking Account Scheduled Payments API
  slug: westpac-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/westpac/openapi/westpac-banking-account-scheduled-payments-api-openapi.yml
- filename: westpac-banking-account-transactions-api-openapi.yml
  format: yaml
  label: Westpac Banking Corporation Banking Account Transactions API
  slug: westpac-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/westpac/openapi/westpac-banking-account-transactions-api-openapi.yml
- filename: westpac-banking-accounts-api-openapi.yml
  format: yaml
  label: Westpac Banking Corporation Banking Accounts API
  slug: westpac-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/westpac/openapi/westpac-banking-accounts-api-openapi.yml
- filename: westpac-banking-payees-api-openapi.yml
  format: yaml
  label: Westpac Banking Corporation Banking Payees API
  slug: westpac-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/westpac/openapi/westpac-banking-payees-api-openapi.yml
- filename: westpac-banking-products-api-openapi.yml
  format: yaml
  label: Westpac Banking Corporation Banking Products API
  slug: westpac-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/westpac/openapi/westpac-banking-products-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: Your name, date of birth, gender, signature, mailing and residential address details, telephone numbers, email addresses
  - category: identifying
    text: Government issued identification (copies) and identifiers
  - category: financial
    text: Transactional information Records of transactions you make using our products and services.
  - category: location
    text: geographical information, information about the device used to visit our website
  - category: behavioral
    text: Pages viewed and browsing behaviour on our websites and applications
  - category: device
    text: such as device IDs and IP addresses
  - category: health
    text: sensitive information about your health, medical history, racial or ethnic origin
  - category: biometric
    text: biometric data (to verify your identity and authorise transactions
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide products and services
    text: Provide you with and manage the products, services and programs you have with us directly or with the support of our Business Partners
  - purpose: Security and fraud prevention
    text: Prevent, detect, report, investigate, disrupt and respond to suspicious, fraudulent, criminal or other activity
  - purpose: Legal and regulatory compliance
    text: Comply with our legislative and regulatory requirements (both in Australia and overseas)
  - purpose: Direct marketing
    text: We will use your personal information to offer you products and services we believe may be of interest and value to you.
  rights:
  - right: Access and correction
    text: It also explains how you can access and correct the personal information we hold about you
  - right: Opt out of credit pre-screening
    text: You have the right to request that the credit reporting bodies do not use your credit-related information for this purpose.
  - right: Opt out of direct marketing
    text: If you do not want to receive direct marketing offers from us, you can manage your marketing preferences in your internet banking profile
  role:
    text: Westpac Banking Corporation and its Australian related body corporates (the Westpac Group, we, us, our ) collect your personal information to provide you with products and services
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
name: Westpac
provenance_date: '2026-11-10'
provider_name: Westpac
provider_slug: westpac
slug: westpac-privacy-policy
source_date: '2026-11-10'
source_filename: westpac-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.westpac.com.au/privacy/privacy-statement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Westpac\naid: westpac\nurl: https://www.westpac.com.au/privacy/privacy-statement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: Westpac Banking Corporation and its Australian related body corporates (the Westpac Group, we, us, our )\n    collect your personal information to provide you with products and services\ndata_categories:\n- category: contact\n  text: Your name, date of birth, gender, signature, mailing and residential address details, telephone numbers,\n    email addresses\n- category: identifying\n  text: Government issued identification (copies) and identifiers\n\
  - category: financial\n  text: Transactional information Records of transactions you make using our products and services.\n- category: location\n  text: geographical information, information about the device used to visit our website\n- category: behavioral\n  text: Pages viewed and browsing behaviour on our websites and applications\n- category: device\n  text: such as device IDs and IP addresses\n- category: health\n  text: sensitive information about your health, medical history, racial or ethnic origin\n- category: biometric\n  text: biometric data (to verify your identity and authorise transactions\npurposes:\n- purpose: Provide products and services\n  text: Provide you with and manage the products, services and programs you have with us directly or with the support\n    of our Business Partners\n- purpose: Security and fraud prevention\n  text: Prevent, detect, report, investigate, disrupt and respond to suspicious, fraudulent, criminal or other activity\n- purpose: Legal and regulatory\
  \ compliance\n  text: Comply with our legislative and regulatory requirements (both in Australia and overseas)\n- purpose: Direct marketing\n  text: We will use your personal information to offer you products and services we believe may be of interest and\n    value to you.\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access and correction\n  text: It also explains how you can access and correct the personal information we hold about you\n- right: Opt out of credit pre-screening\n  text: You have the right to request that the credit reporting bodies do not use your credit-related information\n    for this purpose.\n- right: Opt out of direct marketing\n  text: If you do not want to receive direct marketing offers from us, you can manage your marketing preferences\n    in your internet banking profile\nsale_or_sharing:\n  stance: unstated\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/westpac/privacy/westpac-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- rights
summary_line: 16 quoted statements, read from Westpac's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Banking
- Australia
- Product Reference Data
- ADI
---
