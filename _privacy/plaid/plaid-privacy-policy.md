---
api_specs:
- filename: plaid-plaid-api-openapi.yml
  format: yaml
  label: Plaid API
  slug: plaid-plaid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plaid/openapi/plaid-plaid-api-openapi.yml
- filename: plaid-account-information-api-openapi.yml
  format: yaml
  label: Plaid Account Information API
  slug: plaid-account-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plaid/openapi/plaid-account-information-api-openapi.yml
- filename: plaid-account-statements-api-openapi.yml
  format: yaml
  label: Plaid Account Statements API
  slug: plaid-account-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plaid/openapi/plaid-account-statements-api-openapi.yml
- filename: plaid-account-transactions-api-openapi.yml
  format: yaml
  label: Plaid Account Transactions API
  slug: plaid-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plaid/openapi/plaid-account-transactions-api-openapi.yml
- filename: plaid-asset-transfer-networks-information-api-openapi.yml
  format: yaml
  label: Plaid Asset Transfer Networks Information API
  slug: plaid-asset-transfer-networks-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plaid/openapi/plaid-asset-transfer-networks-information-api-openapi.yml
- filename: plaid-payment-networks-information-api-openapi.yml
  format: yaml
  label: Plaid Payment Networks Information API
  slug: plaid-payment-networks-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plaid/openapi/plaid-payment-networks-information-api-openapi.yml
- filename: plaid-personal-information-api-openapi.yml
  format: yaml
  label: Plaid Personal Information API
  slug: plaid-personal-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plaid/openapi/plaid-personal-information-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: identifiers like name, email address, date of birth, Social Security number, and phone number
  - category: financial
    text: Data about account transactions, including amount, date, payee, type, quantity, price, location, involved securities, and a description of the transaction
  - category: location
    text: timezone setting and location, device location
  - category: device
    text: hardware model and operating system
  - category: biometric
    text: Data collected in this context may be considered biometric data in some states or countries.
  deletion:
    route: Plaid Portal or online form
    text: the Plaid Portal provides you with controls to terminate the connection between apps and your financial accounts and delete associated data stored in Plaid’s systems.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services
    text: To operate, provide, service, assess, process, and maintain our products and services
  - purpose: Develop new services
    text: 'Develop New Services: To develop new products, features, technologies and services that benefit you and the apps you use, including to develop, train, test, and deploy artificial intelligence'
  - purpose: Fraud prevention and identity verification
    text: To verify your identity and help protect you, developers, our partners, Plaid, and others from and prevent actual or potential fraud
  - purpose: Develop insights
    text: To develop insights based on the data we've collected about you.
  residency:
  - region: United States
    text: store data in AWS regions located in the United States
  retention:
  - period: null
    scope: Data after developer removes connection
    text: If a developer removes your connection from their app to your data, Plaid’s systems are designed to automatically delete your personal data, subject to certain exceptions where we may still retain your information.
  - period: three years
    scope: Biometric data for Illinois and Texas residents
    text: Your data will be stored no longer than three years, unless otherwise required by law.
  rights:
  - right: Access
    text: Access data collected about you
  - right: Erasure or restriction
    text: Request, under certain circumstances, that we erase or restrict the processing of your data
  - right: Objection
    text: Object to our processing of your data under certain conditions provided by law
  - right: Withdraw consent
    text: Where processing of your data is based on consent, withdraw that consent
  role:
    text: Depending on which product or service you and your developer are using, Plaid may be the controller or the processor of the data collected under the relevant data protection law.
    value: both
  sale_or_sharing:
    stance: conditional
    text: We only share your personal financial data with third parties to power the services you requested, when you consent, and/or to protect against actual or potential fraud, unauthorized transactions, claims, other liabilities, malicious activity, and other privacy and security-related concerns.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: including standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Plaid
provenance_date: '2026-11-10'
provider_name: Plaid
provider_slug: plaid
slug: plaid-privacy-policy
source_date: '2026-11-10'
source_filename: plaid-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://plaid.com/legal/#privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Plaid\naid: plaid\nurl: https://plaid.com/legal/#privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: Depending on which product or service you and your developer are using, Plaid may be the controller or the\n    processor of the data collected under the relevant data protection law.\ndata_categories:\n- category: identifying\n  text: identifiers like name, email address, date of birth, Social Security number, and phone number\n- category: financial\n  text: Data about account transactions, including amount, date, payee, type, quantity, price, location, involved\n  \
  \  securities, and a description of the transaction\n- category: location\n  text: timezone setting and location, device location\n- category: device\n  text: hardware model and operating system\n- category: biometric\n  text: Data collected in this context may be considered biometric data in some states or countries.\npurposes:\n- purpose: Provide services\n  text: To operate, provide, service, assess, process, and maintain our products and services\n- purpose: Develop new services\n  text: 'Develop New Services: To develop new products, features, technologies and services that benefit you and\n    the apps you use, including to develop, train, test, and deploy artificial intelligence'\n- purpose: Fraud prevention and identity verification\n  text: To verify your identity and help protect you, developers, our partners, Plaid, and others from and prevent\n    actual or potential fraud\n- purpose: Develop insights\n  text: To develop insights based on the data we've collected about you.\n\
  retention:\n- scope: Data after developer removes connection\n  period: null\n  text: If a developer removes your connection from their app to your data, Plaid’s systems are designed to automatically\n    delete your personal data, subject to certain exceptions where we may still retain your information.\n- scope: Biometric data for Illinois and Texas residents\n  period: three years\n  text: Your data will be stored no longer than three years, unless otherwise required by law.\nresidency:\n- region: United States\n  text: store data in AWS regions located in the United States\ntransfers:\n- mechanism: SCC\n  text: including standard contractual clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Plaid Portal or online form\n  text: the Plaid Portal provides you with controls to terminate the connection between apps and your financial\n    accounts and delete associated data stored in Plaid’s systems.\nrights:\n- right:\
  \ Access\n  text: Access data collected about you\n- right: Erasure or restriction\n  text: Request, under certain circumstances, that we erase or restrict the processing of your data\n- right: Objection\n  text: Object to our processing of your data under certain conditions provided by law\n- right: Withdraw consent\n  text: Where processing of your data is based on consent, withdraw that consent\nsale_or_sharing:\n  stance: conditional\n  text: We only share your personal financial data with third parties to power the services you requested, when\n    you consent, and/or to protect against actual or potential fraud, unauthorized transactions, claims, other liabilities,\n    malicious activity, and other privacy and security-related concerns.\n"
source_yaml_url: https://artifacts.apis.io/plaid/privacy/plaid-privacy-policy.yml
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
summary_line: 20 quoted statements, read from Plaid's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Fintech
- Open Banking
- Bank Accounts
- Data Aggregation
- Payments
- United States
---
