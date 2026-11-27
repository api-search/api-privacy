---
api_specs:
- filename: safello-account-api-openapi.yml
  format: yaml
  label: Safello Account API
  slug: safello-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/safello/openapi/safello-account-api-openapi.yml
- filename: safello-auth-api-openapi.yml
  format: yaml
  label: Safello Auth API
  slug: safello-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/safello/openapi/safello-auth-api-openapi.yml
- filename: safello-compliance-api-openapi.yml
  format: yaml
  label: Safello Compliance API
  slug: safello-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/safello/openapi/safello-compliance-api-openapi.yml
- filename: safello-market-api-openapi.yml
  format: yaml
  label: Safello Market API
  slug: safello-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/safello/openapi/safello-market-api-openapi.yml
- filename: safello-orders-api-openapi.yml
  format: yaml
  label: Safello Orders API
  slug: safello-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/safello/openapi/safello-orders-api-openapi.yml
- filename: safello-prices-api-openapi.yml
  format: yaml
  label: Safello Prices API
  slug: safello-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/safello/openapi/safello-prices-api-openapi.yml
- filename: safello-wallet-api-openapi.yml
  format: yaml
  label: Safello Wallet API
  slug: safello-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/safello/openapi/safello-wallet-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact and personal information, such as name, email address, home address, social security number and phone number.
  - category: financial
    text: Financial information, such as credit card, bank account numbers, bank account statements and any personal data proofing origin of wealth/funds.
  - category: demographic
    text: Demographic information, such as age, gender and location.
  - category: device
    text: We also process online identifiers such as IP addresses, MAC addresses or similar provided by website visitors.
  - category: behavioral
    text: we also process information about how you interact with our emails. The information collected is opened e-mails and clicks.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: the processing of data will be regulated via a Data Processing Agreement
    url: null
  purposes:
  - purpose: Provide services and execute transactions
    text: To fulfill the terms of the agreement between our customers and Safello, in order to provide the services and execute the processing of transactions on behalf of our customers
  - purpose: Communication and marketing
    text: To communicate with users about their accounts and the services we provide for information and marketing purposes
  - purpose: Improve services
    text: To improve our services and ensure their proper functioning
  retention:
  - period: null
    scope: personal data generally
    text: Safello will retain personal data as long as necessary to fulfill the purpose for which it was collected or as required by law.
  rights:
  - right: access
    text: Receive information about which personal data we process about you (register extract)
  - right: correction
    text: Request correction of incorrect and incomplete information
  - right: deletion or restriction
    text: Request deletion or restriction of processing, unless Safello has to save the data due to the relationship between you and Safello or due to legislation,
  - right: portability
    text: Obtain certain personal data in a machine-readable format and, if technically possible, transfer the personal data to another personal data controller (so-called data portability)
  role:
    text: Safello is the data controller for the personal data we collect and process.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Transfer of personal data to a third country only takes place under the condition that an adequate level of protection exists or that suitable protection measures have been taken.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Safello
provenance_date: '2026-11-10'
provider_name: Safello
provider_slug: safello
slug: safello-privacy-policy
source_date: '2026-11-10'
source_filename: safello-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://safello.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Safello\naid: safello\nurl: https://safello.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Safello is the data controller for the personal data we collect and process.\ndata_categories:\n- category: contact\n  text: Contact and personal information, such as name, email address, home address, social security number and\n    phone number.\n- category: financial\n  text: Financial information, such as credit card, bank account numbers, bank account statements and any personal\n    data proofing origin of wealth/funds.\n- category: demographic\n  text: Demographic information,\
  \ such as age, gender and location.\n- category: device\n  text: We also process online identifiers such as IP addresses, MAC addresses or similar provided by website visitors.\n- category: behavioral\n  text: we also process information about how you interact with our emails. The information collected is opened\n    e-mails and clicks.\npurposes:\n- purpose: Provide services and execute transactions\n  text: To fulfill the terms of the agreement between our customers and Safello, in order to provide the services\n    and execute the processing of transactions on behalf of our customers\n- purpose: Communication and marketing\n  text: To communicate with users about their accounts and the services we provide for information and marketing\n    purposes\n- purpose: Improve services\n  text: To improve our services and ensure their proper functioning\nretention:\n- scope: personal data generally\n  period: null\n  text: Safello will retain personal data as long as necessary to fulfill the\
  \ purpose for which it was collected\n    or as required by law.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Transfer of personal data to a third country only takes place under the condition that an adequate level\n    of protection exists or that suitable protection measures have been taken.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: the processing of data will be regulated via a Data Processing Agreement\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: Receive information about which personal data we process about you (register extract)\n- right: correction\n  text: Request correction of incorrect and incomplete information\n- right: deletion or restriction\n  text: Request deletion or restriction of processing, unless Safello has to save the data due to the relationship\n    between you and Safello or due to legislation,\n- right: portability\n  text: Obtain certain personal data in a machine-readable\
  \ format and, if technically possible, transfer the personal\n    data to another personal data controller (so-called data portability)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/safello/privacy/safello-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- rights
summary_line: 16 quoted statements, read from Safello's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Cryptocurrency
- Bitcoin
- Brokerage
- Payments
- Sweden
- Trading
- KYC
- BankID
- Financial Services
---
