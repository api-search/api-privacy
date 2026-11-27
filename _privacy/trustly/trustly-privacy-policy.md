---
api_specs:
- filename: trustly-accounts-api-openapi.yml
  format: yaml
  label: Trustly Group Accounts API
  slug: trustly-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-accounts-api-openapi.yml
- filename: trustly-api-api-openapi.yml
  format: yaml
  label: Trustly Group API
  slug: trustly-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-api-api-openapi.yml
- filename: trustly-countries-api-openapi.yml
  format: yaml
  label: Trustly Group Countries API
  slug: trustly-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-countries-api-openapi.yml
- filename: trustly-customers-api-openapi.yml
  format: yaml
  label: Trustly Group Customers API
  slug: trustly-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-customers-api-openapi.yml
- filename: trustly-identity-api-openapi.yml
  format: yaml
  label: Trustly Group Identity API
  slug: trustly-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-identity-api-openapi.yml
- filename: trustly-networkcheckapi-api-openapi.yml
  format: yaml
  label: Trustly Group Network Check API
  slug: trustly-networkcheckapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-networkcheckapi-api-openapi.yml
- filename: trustly-payments-api-openapi.yml
  format: yaml
  label: Trustly Group Payments API
  slug: trustly-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-payments-api-openapi.yml
- filename: trustly-transactions-api-openapi.yml
  format: yaml
  label: Trustly Group Transactions API
  slug: trustly-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-transactions-api-openapi.yml
- filename: trustly-verifycustomer-api-openapi.yml
  format: yaml
  label: Trustly Group Verify Customer API
  slug: trustly-verifycustomer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-verifycustomer-api-openapi.yml
- filename: trustly-account-data-api-openapi.yml
  format: yaml
  label: Trustly Group Account Data API
  slug: trustly-account-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-account-data-api-openapi.yml
- filename: trustly-dispute-management-api-openapi.yml
  format: yaml
  label: Trustly Group Dispute Management API
  slug: trustly-dispute-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-dispute-management-api-openapi.yml
- filename: trustly-payment-providers-api-openapi.yml
  format: yaml
  label: Trustly Group Payment Providers API
  slug: trustly-payment-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-payment-providers-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: first name, last name, home address (including e.g. flat/house number), telephone number, email address, date of birth
  - category: financial
    text: sending and/or receiving bank, bank account ownership, bank account number, account type, account balance at the time of the payment, transaction history
  - category: device
    text: IP-address, type of device, device identifiers, operating system and browser information
  - category: behavioral
    text: how End-users use our payment service and/or how Website visitors interact with our websites
  - category: communication
    text: information provided by you through channels available on our websites, such as contact forms, payment lookup tool, chat conversations and email correspondence
  - category: health
    text: or information about health or sexual orientation
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the Service
    text: To initiate and process a convenient and secure Pay-into your Merchant.
  - purpose: Legal and regulatory compliance
    text: To fulfil our legal obligations to conduct know your customer checks on you
  - purpose: Business intelligence and development
    text: To perform business intelligence, business development (including testing) and troubleshooting purposes
  - purpose: Fraud prevention and security
    text: To prevent our Service from being used for frauds and/or similar illicit actions.
  retention:
  - period: Five years
    scope: Anti-money laundering data
    text: Five years from when the business relationship with you has terminated, unless anti-money laundering law requires us to store your data longer.
  - period: Seven (7) years
    scope: Bookkeeping data relating to a payment
    text: Seven (7) years from the payment.
  - period: ten (10) years
    scope: Support case records
    text: For ten (10) years from closing the support case.
  rights:
  - right: GDPR data subject rights
    text: fulfilling your rights as a data subject under the GDPR
  role:
    text: are responsible as data controller for the processing of your personal data under this privacy policy.
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
name: Trustly Group
provenance_date: '2026-11-10'
provider_name: Trustly Group
provider_slug: trustly
slug: trustly-privacy-policy
source_date: '2026-11-10'
source_filename: trustly-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.trustly.com/about-us/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Trustly Group\naid: trustly\nurl: https://www.trustly.com/about-us/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: are responsible as data controller for the processing of your personal data under this privacy policy.\ndata_categories:\n- category: identifying\n  text: first name, last name, home address (including e.g. flat/house number), telephone number, email address,\n    date of birth\n- category: financial\n  text: sending and/or receiving bank, bank account ownership, bank account number, account type, account balance\n    at the time of the payment,\
  \ transaction history\n- category: device\n  text: IP-address, type of device, device identifiers, operating system and browser information\n- category: behavioral\n  text: how End-users use our payment service and/or how Website visitors interact with our websites\n- category: communication\n  text: information provided by you through channels available on our websites, such as contact forms, payment lookup\n    tool, chat conversations and email correspondence\n- category: health\n  text: or information about health or sexual orientation\npurposes:\n- purpose: Providing the Service\n  text: To initiate and process a convenient and secure Pay-into your Merchant.\n- purpose: Legal and regulatory compliance\n  text: To fulfil our legal obligations to conduct know your customer checks on you\n- purpose: Business intelligence and development\n  text: To perform business intelligence, business development (including testing) and troubleshooting purposes\n- purpose: Fraud prevention and security\n\
  \  text: To prevent our Service from being used for frauds and/or similar illicit actions.\nretention:\n- scope: Anti-money laundering data\n  period: Five years\n  text: Five years from when the business relationship with you has terminated, unless anti-money laundering law\n    requires us to store your data longer.\n- scope: Bookkeeping data relating to a payment\n  period: Seven (7) years\n  text: Seven (7) years from the payment.\n- scope: Support case records\n  period: ten (10) years\n  text: For ten (10) years from closing the support case.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: GDPR data subject rights\n  text: fulfilling your rights as a data subject under the GDPR\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trustly/privacy/trustly-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- rights
summary_line: 15 quoted statements, read from Trustly Group's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Pay by Bank
- Open Banking
- Account-to-Account
- Payouts
- Direct Debit
- Bank Account Verification
- Identity Verification
- Fintech
- Webhook
- MCP
---
