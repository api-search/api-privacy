---
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifying information about the account owner(s), including name, email address, phone number, date of birth, and address information
  - category: financial
    text: Balance information, including current and available Financial Account balance
  - category: financial
    text: Payroll account information, including employer details, employment description, W2 and tax related information, income amount and dates paid, and amounts withheld for taxes, benefits, and insurance
  - category: financial
    text: Transaction information, including merchant, amount, date, payee, type, quantity, price, location, involved securities, and a memo or description of the transaction
  - category: identifying
    text: authentication information, such as credentials, username, password, security questions and responses, Personal Identification Numbers (PINs), multi-factor authentication responses, security tokens
  deletion:
    route: Application informs Sophtron via API when automated retrieval is no longer needed
    text: When the Financial Account Owner indicates they no longer need the automated records retrieval the Application uses the API to inform Sophtron. Sophtron then deletes the retrieved records and the credentials immediately.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: retrieving and storing records requested by the account owner
    text: Sophtron does not use the financial records retrieved or the credentials provided, for any purpose other than retrieving and storing the records requested by the Financial Account Owner.
  - purpose: improving service
    text: Sophtron keeps records of any difficulties in retrieving data from various financial institutions and what requests need to be made to retrieve various financial records for the purpose of improving Sophtron's service.
  residency:
  - region: United States
    text: Sophtron is a US Company and all data it stores is located in Amazon Web Services (AWS) data centers located in the US.
  retention:
  - period: immediately
    scope: records and credentials after automation is disabled
    text: Sophtron then deletes the retrieved records and the credentials immediately.
  - period: 11 months
    scope: records when owner does not reconfirm
    text: If the Financial Account Owner does not reconfirm the need for automated record retrieval every 11 months by presenting Sophtron with valid account credentials Sophtron deletes all records and credentials.
  role:
    text: null
    value: unstated
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
name: Sophtron
provenance_date: '2026-11-10'
provider_name: Sophtron
provider_slug: sophtron
slug: sophtron-privacy-policy
source_date: '2026-11-10'
source_filename: sophtron-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sophtron.com/home/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Sophtron\naid: sophtron\nurl: https://sophtron.com/home/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Identifying information about the account owner(s), including name, email address, phone number, date of\n    birth, and address information\n- category: financial\n  text: Balance information, including current and available Financial Account balance\n- category: financial\n  text: Payroll account information, including employer details, employment description, W2 and tax related information,\n    income amount and dates paid,\
  \ and amounts withheld for taxes, benefits, and insurance\n- category: financial\n  text: Transaction information, including merchant, amount, date, payee, type, quantity, price, location, involved\n    securities, and a memo or description of the transaction\n- category: identifying\n  text: authentication information, such as credentials, username, password, security questions and responses, Personal\n    Identification Numbers (PINs), multi-factor authentication responses, security tokens\npurposes:\n- purpose: retrieving and storing records requested by the account owner\n  text: Sophtron does not use the financial records retrieved or the credentials provided, for any purpose other\n    than retrieving and storing the records requested by the Financial Account Owner.\n- purpose: improving service\n  text: Sophtron keeps records of any difficulties in retrieving data from various financial institutions and what\n    requests need to be made to retrieve various financial records for\
  \ the purpose of improving Sophtron's service.\nretention:\n- scope: records and credentials after automation is disabled\n  period: immediately\n  text: Sophtron then deletes the retrieved records and the credentials immediately.\n- scope: records when owner does not reconfirm\n  period: 11 months\n  text: If the Financial Account Owner does not reconfirm the need for automated record retrieval every 11 months\n    by presenting Sophtron with valid account credentials Sophtron deletes all records and credentials.\nresidency:\n- region: United States\n  text: Sophtron is a US Company and all data it stores is located in Amazon Web Services (AWS) data centers located\n    in the US.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Application informs Sophtron via API when automated retrieval is no longer needed\n  text: When the Financial Account Owner indicates they no longer need the automated records retrieval\
  \ the Application\n    uses the API to inform Sophtron. Sophtron then deletes the retrieved records and the credentials immediately.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sophtron/privacy/sophtron-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
summary_line: 11 quoted statements, read from Sophtron's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Data Aggregation
- Banking
- Financial Services
---
