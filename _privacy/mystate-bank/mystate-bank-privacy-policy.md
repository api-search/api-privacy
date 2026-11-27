---
api_specs:
- filename: mystate-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: MyState Bank Banking Account Balances API
  slug: mystate-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystate-bank/openapi/mystate-bank-banking-account-balances-api-openapi.yml
- filename: mystate-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: MyState Bank Banking Account Direct Debits API
  slug: mystate-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystate-bank/openapi/mystate-bank-banking-account-direct-debits-api-openapi.yml
- filename: mystate-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: MyState Bank Banking Account Scheduled Payments API
  slug: mystate-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystate-bank/openapi/mystate-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: mystate-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: MyState Bank Banking Account Transactions API
  slug: mystate-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystate-bank/openapi/mystate-bank-banking-account-transactions-api-openapi.yml
- filename: mystate-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: MyState Bank Banking Accounts API
  slug: mystate-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystate-bank/openapi/mystate-bank-banking-accounts-api-openapi.yml
- filename: mystate-bank-banking-payees-api-openapi.yml
  format: yaml
  label: MyState Bank Banking Payees API
  slug: mystate-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystate-bank/openapi/mystate-bank-banking-payees-api-openapi.yml
- filename: mystate-bank-banking-products-api-openapi.yml
  format: yaml
  label: MyState Bank Banking Products API
  slug: mystate-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mystate-bank/openapi/mystate-bank-banking-products-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Information which identifies you, like your name, address and other contact details and your date of birth
  - category: financial
    text: Information about your financial position, like your income, expenses, savings and assets and any (other) credit arrangements
  - category: professional
    text: Your employment details
  - category: identifying
    text: Your tax file number
  - category: biometric
    text: Biometric information as part of our ID processes.
  - category: location
    text: location information (if enabled on your device)
  - category: device
    text: IP address
  - category: behavioral
    text: What sections of our websites you view and any errors you experience
  deletion:
    route: null
    text: When we no longer require your information (including when we are no longer required by law to keep records relating to you), we will take reasonable steps to destroy or de-identify it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing products and services and managing business
    text: We may use your personal information for the purpose of providing products and services to you and managing our business.
  - purpose: Fraud and scam prevention
    text: This information also helps us improve and maintain the security measures we have in place to identify suspicious account activity and help prevent fraud and scams.
  - purpose: Direct marketing
    text: Direct marketing
  - purpose: Analytics of behaviour
    text: Analytics of your behaviour to provide suitable products and services
  - purpose: Research and development
    text: Research and development
  residency:
  - region: Australia
    text: Endeavouring to keep all data held within Australia
  retention:
  - period: null
    scope: Information no longer required
    text: When we no longer require your information (including when we are no longer required by law to keep records relating to you), we will take reasonable steps to destroy or de-identify it.
  rights:
  - right: Access
    text: You have the right to request access to the information that we hold about you at any time.
  - right: Correction
    text: You also have the right to request information that we hold about you be corrected at any time.
  - right: Opt out of marketing
    text: You may opt out at any time if you no longer wish to receive marketing information
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
    text: We will not directly disclose your personal information overseas, including your credit information.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MyState Bank
provenance_date: '2026-11-10'
provider_name: MyState Bank
provider_slug: mystate-bank
slug: mystate-bank-privacy-policy
source_date: '2026-11-10'
source_filename: mystate-bank-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mystate.com.au/legal/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MyState Bank\naid: mystate-bank\nurl: https://mystate.com.au/legal/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Information which identifies you, like your name, address and other contact details and your date of birth\n- category: financial\n  text: Information about your financial position, like your income, expenses, savings and assets and any (other)\n    credit arrangements\n- category: professional\n  text: Your employment details\n- category: identifying\n  text: Your tax file number\n- category: biometric\n  text:\
  \ Biometric information as part of our ID processes.\n- category: location\n  text: location information (if enabled on your device)\n- category: device\n  text: IP address\n- category: behavioral\n  text: What sections of our websites you view and any errors you experience\npurposes:\n- purpose: Providing products and services and managing business\n  text: We may use your personal information for the purpose of providing products and services to you and managing\n    our business.\n- purpose: Fraud and scam prevention\n  text: This information also helps us improve and maintain the security measures we have in place to identify suspicious\n    account activity and help prevent fraud and scams.\n- purpose: Direct marketing\n  text: Direct marketing\n- purpose: Analytics of behaviour\n  text: Analytics of your behaviour to provide suitable products and services\n- purpose: Research and development\n  text: Research and development\nretention:\n- scope: Information no longer required\n\
  \  period: null\n  text: When we no longer require your information (including when we are no longer required by law to keep records\n    relating to you), we will take reasonable steps to destroy or de-identify it.\nresidency:\n- region: Australia\n  text: Endeavouring to keep all data held within Australia\ntransfers:\n- mechanism: other\n  text: We will not directly disclose your personal information overseas, including your credit information.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: When we no longer require your information (including when we are no longer required by law to keep records\n    relating to you), we will take reasonable steps to destroy or de-identify it.\nrights:\n- right: Access\n  text: You have the right to request access to the information that we hold about you at any time.\n- right: Correction\n  text: You also have the right to request information that we hold about you\
  \ be corrected at any time.\n- right: Opt out of marketing\n  text: You may opt out at any time if you no longer wish to receive marketing information\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mystate-bank/privacy/mystate-bank-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 20 quoted statements, read from MyState Bank's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Data Right
- Consumer Banking
- Australia
- Product Reference Data
---
