---
api_specs:
- filename: mamo-business-details-api-openapi.yml
  format: yaml
  label: Mamo Business Details API
  slug: mamo-business-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-business-details-api-openapi.yml
- filename: mamo-cards-api-openapi.yml
  format: yaml
  label: Mamo Cards API
  slug: mamo-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-cards-api-openapi.yml
- filename: mamo-expenses-api-openapi.yml
  format: yaml
  label: Mamo Expenses API
  slug: mamo-expenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-expenses-api-openapi.yml
- filename: mamo-getting-started-api-openapi.yml
  format: yaml
  label: Mamo Getting Started API
  slug: mamo-getting-started-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-getting-started-api-openapi.yml
- filename: mamo-invoices-api-openapi.yml
  format: yaml
  label: Mamo Invoices API
  slug: mamo-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-invoices-api-openapi.yml
- filename: mamo-payment-links-api-openapi.yml
  format: yaml
  label: Mamo Payment Links API
  slug: mamo-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-payment-links-api-openapi.yml
- filename: mamo-payouts-api-openapi.yml
  format: yaml
  label: Mamo Payouts API
  slug: mamo-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-payouts-api-openapi.yml
- filename: mamo-receipts-api-openapi.yml
  format: yaml
  label: Mamo Receipts API
  slug: mamo-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-receipts-api-openapi.yml
- filename: mamo-recipients-api-openapi.yml
  format: yaml
  label: Mamo Recipients API
  slug: mamo-recipients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-recipients-api-openapi.yml
- filename: mamo-subscriptions-api-openapi.yml
  format: yaml
  label: Mamo Subscriptions API
  slug: mamo-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-subscriptions-api-openapi.yml
- filename: mamo-transactions-api-openapi.yml
  format: yaml
  label: Mamo Transactions API
  slug: mamo-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-transactions-api-openapi.yml
- filename: mamo-webhooks-api-openapi.yml
  format: yaml
  label: Mamo Webhooks API
  slug: mamo-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-webhooks-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, address, and date of birth
  - category: contact
    text: your email address, phone number and details of the device you use
  - category: financial
    text: details of your bank account, such as your account number, and IBAN
  - category: location
    text: If the App has requested location tracking and you agree to turn location tracking on, we will collect your location data in accordance with your settings, to assist with detecting fraud.
  - category: behavioral
    text: Information about your visit, including the links you have clicked on, through and from our site
  - category: device
    text: the internet protocol (IP) address used to connect your computer to the internet, your device ID for security reasons
  deletion:
    route: Contact Mamo to request deletion
    text: You are entitled to ask us to delete your information. However, if you exercise this right we will not be able to provide you with our services.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide requested service and contract
    text: To provide a requested service or carry out a contract with you.
  - purpose: Legitimate interests
    text: to detect and prevent unlawful use, misuse or abuse of the App and Website Services
  - purpose: Legal and regulatory obligations
    text: to meet Mamo’s legal and regulatory compliance obligations
  retention:
  - period: null
    scope: Personal information generally
    text: We only retain your information for as long as is necessary for us to use your information as described above, where it is in Mamo’s legitimate interest, or to comply with Mamo’s legal obligations.
  rights:
  - right: Access
    text: You have the right to access information held about you.
  - right: Correction
    text: You also have the right to ask us to correct inaccurate information we hold about you.
  - right: Erasure
    text: You are entitled to ask us to delete your information.
  - right: Objection and restriction
    text: In certain circumstances, you have the right to object to our use of your personal data or to ask us to restrict certain processing activities.
  - right: Portability
    text: You have the right to receive the data we process based on your consent and for the performance of the contract with you in a structured and machine-readable format.
  - right: Withdraw consent
    text: you have the right to withdraw your consent at any time
  - right: Opt out of marketing
    text: You have the option to ask us not to process your personal information for direct marketing purposes.
  role:
    text: We are the Controller for the purposes of DP Law of the personal information that we collect or receive from you as more fully described in this Policy.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: For example, by using the standard contractual clauses that have been approved by the Commissioner of Data Protection and to be used for transfers outside the DIFC to a non-adequate jurisdiction.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Mamo
provenance_date: '2026-11-10'
provider_name: Mamo
provider_slug: mamo
slug: mamo-privacy-policy
source_date: '2026-11-10'
source_filename: mamo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.mamopay.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Mamo\naid: mamo\nurl: https://www.mamopay.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the Controller for the purposes of DP Law of the personal information that we collect or receive\n    from you as more fully described in this Policy.\ndata_categories:\n- category: identifying\n  text: your name, address, and date of birth\n- category: contact\n  text: your email address, phone number and details of the device you use\n- category: financial\n  text: details of your bank account, such as your account number, and IBAN\n- category: location\n  text: If the App has\
  \ requested location tracking and you agree to turn location tracking on, we will collect your\n    location data in accordance with your settings, to assist with detecting fraud.\n- category: behavioral\n  text: Information about your visit, including the links you have clicked on, through and from our site\n- category: device\n  text: the internet protocol (IP) address used to connect your computer to the internet, your device ID for security\n    reasons\npurposes:\n- purpose: Provide requested service and contract\n  text: To provide a requested service or carry out a contract with you.\n- purpose: Legitimate interests\n  text: to detect and prevent unlawful use, misuse or abuse of the App and Website Services\n- purpose: Legal and regulatory obligations\n  text: to meet Mamo’s legal and regulatory compliance obligations\nretention:\n- scope: Personal information generally\n  period: null\n  text: We only retain your information for as long as is necessary for us to use your information\
  \ as described\n    above, where it is in Mamo’s legitimate interest, or to comply with Mamo’s legal obligations.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: For example, by using the standard contractual clauses that have been approved by the Commissioner of Data\n    Protection and to be used for transfers outside the DIFC to a non-adequate jurisdiction.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact Mamo to request deletion\n  text: You are entitled to ask us to delete your information. However, if you exercise this right we will not be\n    able to provide you with our services.\nrights:\n- right: Access\n  text: You have the right to access information held about you.\n- right: Correction\n  text: You also have the right to ask us to correct inaccurate information we hold about you.\n- right: Erasure\n  text: You are entitled to ask us to delete your information.\n- right: Objection and restriction\n\
  \  text: In certain circumstances, you have the right to object to our use of your personal data or to ask us to\n    restrict certain processing activities.\n- right: Portability\n  text: You have the right to receive the data we process based on your consent and for the performance of the contract\n    with you in a structured and machine-readable format.\n- right: Withdraw consent\n  text: you have the right to withdraw your consent at any time\n- right: Opt out of marketing\n  text: You have the option to ask us not to process your personal information for direct marketing purposes.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mamo/privacy/mamo-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 20 quoted statements, read from Mamo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Fintech
- Payment Links
- Subscription
- Corporate Cards
- Payouts
- Expense Management
- United Arab Emirates
- Middle East
- MENA
---
