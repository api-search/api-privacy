---
api_specs:
- filename: beyond-bank-banking-account-balances-api-openapi.yml
  format: yaml
  label: Beyond Bank Australia Banking Account Balances API
  slug: beyond-bank-banking-account-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-bank/openapi/beyond-bank-banking-account-balances-api-openapi.yml
- filename: beyond-bank-banking-account-direct-debits-api-openapi.yml
  format: yaml
  label: Beyond Bank Australia Banking Account Direct Debits API
  slug: beyond-bank-banking-account-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-bank/openapi/beyond-bank-banking-account-direct-debits-api-openapi.yml
- filename: beyond-bank-banking-account-scheduled-payments-api-openapi.yml
  format: yaml
  label: Beyond Bank Australia Banking Account Scheduled Payments API
  slug: beyond-bank-banking-account-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-bank/openapi/beyond-bank-banking-account-scheduled-payments-api-openapi.yml
- filename: beyond-bank-banking-account-transactions-api-openapi.yml
  format: yaml
  label: Beyond Bank Australia Banking Account Transactions API
  slug: beyond-bank-banking-account-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-bank/openapi/beyond-bank-banking-account-transactions-api-openapi.yml
- filename: beyond-bank-banking-accounts-api-openapi.yml
  format: yaml
  label: Beyond Bank Australia Banking Accounts API
  slug: beyond-bank-banking-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-bank/openapi/beyond-bank-banking-accounts-api-openapi.yml
- filename: beyond-bank-banking-payees-api-openapi.yml
  format: yaml
  label: Beyond Bank Australia Banking Payees API
  slug: beyond-bank-banking-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-bank/openapi/beyond-bank-banking-payees-api-openapi.yml
- filename: beyond-bank-banking-products-api-openapi.yml
  format: yaml
  label: Beyond Bank Australia Banking Products API
  slug: beyond-bank-banking-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-bank/openapi/beyond-bank-banking-products-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: information such as your name, address, date of birth and contact details so we can identify and contact you
  - category: financial
    text: information about your financial position such as your income, savings, expenses, assets and liabilities, employment details, and any (other) credit arrangements
  - category: identifying
    text: your tax residency status, your tax file number (TFN and/or taxpayer identification number (TIN)
  - category: identifying
    text: biometrics including facial and voice biometrics
  - category: behavioral
    text: the pages viewed and any information downloaded
  - category: location
    text: We use your current location to determine the closest bank branch, ATM, access point or other services that we consider may be of benefit to you
  deletion:
    route: null
    text: we take reasonable steps to ensure it is destroyed or de-identified
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: providing products and services and managing our business
    text: We may use your personal information (including credit-related information) for the purpose of providing products and services to you and managing our business.
  - purpose: direct marketing
    text: direct marketing;
  - purpose: research and development
    text: research and development;
  - purpose: collecting overdue payments
    text: collecting overdue payments due under our credit products;
  residency:
  - region: outside Australia
    text: At present our arrangements include providers based in the United States of America and the Netherlands¹.
  retention:
  - period: null
    scope: personal information no longer required
    text: When we no longer require your personal information (including when we are no longer required by law to keep records relating to you), we take reasonable steps to ensure it is destroyed or de-identified.
  - period: for a period of time
    scope: live chat contact details
    text: we will store the email address and phone number (if you have provided it) for a period of time to allow us to contact you outside of the live chat environment
  rights:
  - right: access
    text: You may request access to the personal information (including credit-related information) that we hold about you at any time from our Privacy Officer
  - right: accuracy correction
    text: you can request that we update this information by advising one of our staff or contacting our Privacy Officer
  - right: opt out of marketing
    text: You may opt out at any time if you no longer wish to receive marketing information
  - right: complaint
    text: If you have any questions, concerns or complaints about this Privacy Policy, or our handling of your personal information (including credit-related information), please contact our Privacy Officer
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: However, we will never sell any of your personal information to any other organisation.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Beyond Bank Australia
provenance_date: '2026-11-09'
provider_name: Beyond Bank Australia
provider_slug: beyond-bank
slug: beyond-bank-privacy-policy
source_date: '2026-11-09'
source_filename: beyond-bank-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.beyondbank.com.au/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Beyond Bank Australia\naid: beyond-bank\nurl: https://www.beyondbank.com.au/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: information such as your name, address, date of birth and contact details so we can identify and contact\n    you\n- category: financial\n  text: information about your financial position such as your income, savings, expenses, assets and liabilities,\n    employment details, and any (other) credit arrangements\n- category: identifying\n  text: your tax residency status, your tax file number (TFN and/or taxpayer\
  \ identification number (TIN)\n- category: identifying\n  text: biometrics including facial and voice biometrics\n- category: behavioral\n  text: the pages viewed and any information downloaded\n- category: location\n  text: We use your current location to determine the closest bank branch, ATM, access point or other services that\n    we consider may be of benefit to you\npurposes:\n- purpose: providing products and services and managing our business\n  text: We may use your personal information (including credit-related information) for the purpose of providing\n    products and services to you and managing our business.\n- purpose: direct marketing\n  text: direct marketing;\n- purpose: research and development\n  text: research and development;\n- purpose: collecting overdue payments\n  text: collecting overdue payments due under our credit products;\nretention:\n- scope: personal information no longer required\n  period: null\n  text: When we no longer require your personal information\
  \ (including when we are no longer required by law to\n    keep records relating to you), we take reasonable steps to ensure it is destroyed or de-identified.\n- scope: live chat contact details\n  period: for a period of time\n  text: we will store the email address and phone number (if you have provided it) for a period of time to allow\n    us to contact you outside of the live chat environment\nresidency:\n- region: outside Australia\n  text: At present our arrangements include providers based in the United States of America and the Netherlands¹.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: we take reasonable steps to ensure it is destroyed or de-identified\nrights:\n- right: access\n  text: You may request access to the personal information (including credit-related information) that we hold about\n    you at any time from our Privacy Officer\n- right: accuracy correction\n  text: you\
  \ can request that we update this information by advising one of our staff or contacting our Privacy Officer\n- right: opt out of marketing\n  text: You may opt out at any time if you no longer wish to receive marketing information\n- right: complaint\n  text: If you have any questions, concerns or complaints about this Privacy Policy, or our handling of your personal\n    information (including credit-related information), please contact our Privacy Officer\nsale_or_sharing:\n  stance: prohibited\n  text: However, we will never sell any of your personal information to any other organisation.\n"
source_yaml_url: https://artifacts.apis.io/beyond-bank/privacy/beyond-bank-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Beyond Bank Australia's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Banks
- Open Banking
- CDR
- Consumer Banking
- Australia
- Customer Owned
- Product Reference Data
---
