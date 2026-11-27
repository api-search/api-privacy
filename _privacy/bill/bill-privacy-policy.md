---
api_specs:
- filename: bill-webhooks-asyncapi.yml
  format: yaml
  label: BILL v3 API
  slug: v3-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/bill/asyncapi/bill-webhooks-asyncapi.yml
- filename: bill-authentication-api-openapi.yml
  format: yaml
  label: BILL Authentication API
  slug: bill-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-authentication-api-openapi.yml
- filename: bill-bills-api-openapi.yml
  format: yaml
  label: BILL Bills API
  slug: bill-bills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-bills-api-openapi.yml
- filename: bill-customers-api-openapi.yml
  format: yaml
  label: BILL Customers API
  slug: bill-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-customers-api-openapi.yml
- filename: bill-funding-accounts-api-openapi.yml
  format: yaml
  label: BILL Funding Accounts API
  slug: bill-funding-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-funding-accounts-api-openapi.yml
- filename: bill-invoices-api-openapi.yml
  format: yaml
  label: BILL Invoices API
  slug: bill-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-invoices-api-openapi.yml
- filename: bill-organizations-api-openapi.yml
  format: yaml
  label: BILL Organizations API
  slug: bill-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-organizations-api-openapi.yml
- filename: bill-payments-api-openapi.yml
  format: yaml
  label: BILL Payments API
  slug: bill-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-payments-api-openapi.yml
- filename: bill-vendors-api-openapi.yml
  format: yaml
  label: BILL Vendors API
  slug: bill-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-vendors-api-openapi.yml
- filename: bill-webhooks-api-openapi.yml
  format: yaml
  label: BILL Webhooks API
  slug: bill-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-webhooks-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name; billing address; phone number; email; Tax Identification Number or Social Security Number (collectively, “TIN”); date of birth (natural persons); government-issued identification (natural persons)
  - category: financial
    text: bank routing and account information, bank statements and bank transaction history, personal and/or business credit score
  - category: location
    text: Geolocation. We collect the location of the device that You are using to access the Services.
  - category: device
    text: IP address; hardware model; operating system information; unique device identifier and other technical identifiers; app version; browser information
  - category: behavioral
    text: the pages You access and view; any term(s) You search
  deletion:
    route: contact Customer Support or Privacy Team
    text: To request removal of Your information from a blog or community forum, contact Our Customer Support by clicking on Help once You have logged in
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: providing or facilitating the Services
    text: providing or facilitating the Services; improving the Services; maintaining the security of the Services and Our Network; marketing Our products and Services
  - purpose: marketing and advertising
    text: to tailor ads based on Your interests and browsing history
  - purpose: legal compliance
    text: compliance with anti-money laundering and anti-terrorism financing laws, “know your customer” regulations, and OFAC sanctions requirements
  retention:
  - period: null
    scope: general
    text: We will retain Your information as long as it is necessary to comply with Our internal records retention and management policies and procedures and to provide You with the Services or administer Your account
  rights:
  - right: opt out of marketing communications
    text: We will honor any request from You to opt out of receiving marketing communications, including emails and text messages.
  - right: update or correct account information
    text: You can update, change, or correct certain account information and communication preferences at any time by logging into Your account and changing Your account settings.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: The BILL Companies will not sell, lease, rent, or trade Your personal information to any third party for that party’s marketing or promotional purposes, unless You give Your consent.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Your information may be transferred to and maintained on computers located outside of Your state, province, country or other governmental jurisdiction
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BILL
provenance_date: '2026-11-09'
provider_name: BILL
provider_slug: bill
slug: bill-privacy-policy
source_date: '2026-11-09'
source_filename: bill-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bill.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BILL\naid: bill\nurl: https://www.bill.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your name; billing address; phone number; email; Tax Identification Number or Social Security Number (collectively,\n    “TIN”); date of birth (natural persons); government-issued identification (natural persons)\n- category: financial\n  text: bank routing and account information, bank statements and bank transaction history, personal and/or business\n    credit score\n- category: location\n  text: Geolocation. We collect the location of\
  \ the device that You are using to access the Services.\n- category: device\n  text: IP address; hardware model; operating system information; unique device identifier and other technical identifiers;\n    app version; browser information\n- category: behavioral\n  text: the pages You access and view; any term(s) You search\npurposes:\n- purpose: providing or facilitating the Services\n  text: providing or facilitating the Services; improving the Services; maintaining the security of the Services\n    and Our Network; marketing Our products and Services\n- purpose: marketing and advertising\n  text: to tailor ads based on Your interests and browsing history\n- purpose: legal compliance\n  text: compliance with anti-money laundering and anti-terrorism financing laws, “know your customer” regulations,\n    and OFAC sanctions requirements\nretention:\n- scope: general\n  period: null\n  text: We will retain Your information as long as it is necessary to comply with Our internal records retention\n\
  \    and management policies and procedures and to provide You with the Services or administer Your account\nresidency: []\ntransfers:\n- mechanism: other\n  text: Your information may be transferred to and maintained on computers located outside of Your state, province,\n    country or other governmental jurisdiction\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact Customer Support or Privacy Team\n  text: To request removal of Your information from a blog or community forum, contact Our Customer Support by clicking\n    on Help once You have logged in\nrights:\n- right: opt out of marketing communications\n  text: We will honor any request from You to opt out of receiving marketing communications, including emails and\n    text messages.\n- right: update or correct account information\n  text: You can update, change, or correct certain account information and communication preferences at any time\n    by logging\
  \ into Your account and changing Your account settings.\nsale_or_sharing:\n  stance: conditional\n  text: The BILL Companies will not sell, lease, rent, or trade Your personal information to any third party for\n    that party’s marketing or promotional purposes, unless You give Your consent.\n"
source_yaml_url: https://artifacts.apis.io/bill/privacy/bill-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from BILL's own page on 2026-11-09.
synthetic: false
tags:
- Accounts Payable
- Accounts Receivable
- Spend Management
- Expense Management
- Payments
- Bill Pay
- Financial Operations
- Fintech
- Accounting
---
