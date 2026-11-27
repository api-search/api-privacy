---
api_specs:
- filename: onpay-company-api-openapi.yml
  format: yaml
  label: OnPay Company API
  slug: onpay-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-company-api-openapi.yml
- filename: onpay-deductions-api-openapi.yml
  format: yaml
  label: OnPay Deductions API
  slug: onpay-deductions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-deductions-api-openapi.yml
- filename: onpay-employees-api-openapi.yml
  format: yaml
  label: OnPay Employees API
  slug: onpay-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-employees-api-openapi.yml
- filename: onpay-pay-runs-api-openapi.yml
  format: yaml
  label: OnPay Pay Runs API
  slug: onpay-pay-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-pay-runs-api-openapi.yml
- filename: onpay-reports-api-openapi.yml
  format: yaml
  label: OnPay Reports API
  slug: onpay-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-reports-api-openapi.yml
- filename: onpay-user-api-openapi.yml
  format: yaml
  label: OnPay User API
  slug: onpay-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/onpay/openapi/onpay-user-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personally identifiable information includes, but is not limited to, your name, company name, address, email address and phone number.
  - category: financial
    text: we also collect, store and process your sensitive financial information. This type of information may include your social security number, marital status, bank account information including account numbers, tax information, and company earnings data.
  - category: device
    text: Log Information . When you use our Services or view content provided by the Company we automatically collect and store certain information in our server logs.
  - category: demographic
    text: Demographic Information . “Demographic Information” may be your gender, age, zip code, and interests.
  deletion:
    route: Contact the company to modify, correct, or request deletion of PII
    text: You may modify, correct, change, or request us to delete or update PII that we have collected through the Sites by contacting us via postal mail, e-mail, or telephone
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide products and services
    text: We use your PII to provide you with the Products and Services, administer your inquires and complete your transactions.
  - purpose: Marketing by affiliates and third parties
    text: To offer you products from our affiliates, strategic partners, agents, or from third-party marketers and other unaffiliated parties that we believe may be of interest to you
  - purpose: Fraud protection
    text: To protect against fraud and potential fraud.
  residency:
  - region: United States
    text: This Privacy Policy shall apply strictly to the information collected in the United States.
  rights:
  - right: Access and correction
    text: You may modify, correct, change, or request us to delete or update PII that we have collected through the Sites
  - right: California customer information request
    text: California customers may request further information about our compliance with this law by e-mailing help@onpay.com.
  role:
    text: This Privacy Policy describes how we treat your use of the Sites and when you use our products
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
name: OnPay
provenance_date: '2026-11-10'
provider_name: OnPay
provider_slug: onpay
slug: onpay-privacy-policy
source_date: '2026-11-10'
source_filename: onpay-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://onpay.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: OnPay\naid: onpay\nurl: https://onpay.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This Privacy Policy describes how we treat your use of the Sites and when you use our products\ndata_categories:\n- category: identifying\n  text: Personally identifiable information includes, but is not limited to, your name, company name, address, email\n    address and phone number.\n- category: financial\n  text: we also collect, store and process your sensitive financial information. This type of information may include\n    your social security number, marital status, bank account information\
  \ including account numbers, tax information,\n    and company earnings data.\n- category: device\n  text: Log Information . When you use our Services or view content provided by the Company we automatically collect\n    and store certain information in our server logs.\n- category: demographic\n  text: Demographic Information . “Demographic Information” may be your gender, age, zip code, and interests.\npurposes:\n- purpose: Provide products and services\n  text: We use your PII to provide you with the Products and Services, administer your inquires and complete your\n    transactions.\n- purpose: Marketing by affiliates and third parties\n  text: To offer you products from our affiliates, strategic partners, agents, or from third-party marketers and\n    other unaffiliated parties that we believe may be of interest to you\n- purpose: Fraud protection\n  text: To protect against fraud and potential fraud.\nretention: []\nresidency:\n- region: United States\n  text: This Privacy Policy\
  \ shall apply strictly to the information collected in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact the company to modify, correct, or request deletion of PII\n  text: You may modify, correct, change, or request us to delete or update PII that we have collected through the\n    Sites by contacting us via postal mail, e-mail, or telephone\nrights:\n- right: Access and correction\n  text: You may modify, correct, change, or request us to delete or update PII that we have collected through the\n    Sites\n- right: California customer information request\n  text: California customers may request further information about our compliance with this law by e-mailing help@onpay.com.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/onpay/privacy/onpay-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- residency
- deletion
- rights
summary_line: 12 quoted statements, read from OnPay's own page on 2026-11-10.
synthetic: false
tags:
- Payroll
- Human Resources
- Employee Benefits
- Payroll Tax
- Small Business
- Workforce Management
- Fintech
- Time and Attendance
- retirement-401k
---
