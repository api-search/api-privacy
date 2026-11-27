---
api_specs:
- filename: jodo-webhooks-asyncapi.yml
  format: yaml
  label: Jodo Webhooks
  slug: jodo-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/jodo/asyncapi/jodo-webhooks-asyncapi.yml
- filename: jodo-configuration-api-openapi.yml
  format: yaml
  label: Jodo Configuration API
  slug: jodo-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jodo/openapi/jodo-configuration-api-openapi.yml
- filename: jodo-flex-api-openapi.yml
  format: yaml
  label: Jodo Flex API
  slug: jodo-flex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jodo/openapi/jodo-flex-api-openapi.yml
- filename: jodo-pay-api-openapi.yml
  format: yaml
  label: Jodo Pay API
  slug: jodo-pay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jodo/openapi/jodo-pay-api-openapi.yml
- filename: jodo-students-api-openapi.yml
  format: yaml
  label: Jodo Students API
  slug: jodo-students-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jodo/openapi/jodo-students-api-openapi.yml
- filename: jodo-users-api-openapi.yml
  format: yaml
  label: Jodo Users API
  slug: jodo-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jodo/openapi/jodo-users-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Contact information, such as your name, address, phone, email, and other similar information.
  - category: financial
    text: Financial information, such as your full bank account number if you choose to use it with the Jodo Services.
  - category: location
    text: Jodo also collects your Location coordinates through GPS to provide you better & prompt customer service.
  - category: biometric
    text: Biometric information to verify your unique Aadhar number.
  - category: device
    text: Web Browser Information from your device when you use the Jodo Services such as your IP address, the type of device you use, your device identifier, your operating system version
  - category: communication
    text: Your audio shall be recorded for regulatory purpose.
  deletion:
    route: Email support request to close account
    text: If you wish to close your account or request that we no longer use your information to provide you the Jodo Services, contact us at support@jodopay.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services and process transactions
    text: Provide the Jodo Services to you.
  - purpose: Fraud prevention
    text: Identify, prevent, and report potentially prohibited, fraudulent, or illegal activities.
  - purpose: Customer support
    text: Provide customer support and resolve disputes.
  - purpose: Marketing
    text: Provide you with news, offers, and information about the Jodo Services based on your communications preferences.
  retention:
  - period: as long as your account is active
    scope: Account information
    text: We will retain your information for as long as your account is active or as needed to provide you the Jodo Services.
  rights:
  - right: Withdraw consent
    text: You have the right to withdraw your consent to the processing of your personal data at any time.
  - right: Update or correct information
    text: If your personal information changes, you can update or correct it in your account settings
  - right: Unsubscribe from promotional emails
    text: click on the unsubscribe link at the bottom of any promotional email that we send you
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: Other than as stated in this Privacy Policy, Jodo does not disclose or sell any of your personal information to third parties without your consent.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Jodo
provenance_date: '2026-11-09'
provider_name: Jodo
provider_slug: jodo
slug: jodo-privacy-policy
source_date: '2026-11-09'
source_filename: jodo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.jodo.in/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Jodo\naid: jodo\nurl: https://www.jodo.in/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Contact information, such as your name, address, phone, email, and other similar information.\n- category: financial\n  text: Financial information, such as your full bank account number if you choose to use it with the Jodo Services.\n- category: location\n  text: Jodo also collects your Location coordinates through GPS to provide you better & prompt customer service.\n- category: biometric\n  text: Biometric information to verify\
  \ your unique Aadhar number.\n- category: device\n  text: Web Browser Information from your device when you use the Jodo Services such as your IP address, the type\n    of device you use, your device identifier, your operating system version\n- category: communication\n  text: Your audio shall be recorded for regulatory purpose.\npurposes:\n- purpose: Provide services and process transactions\n  text: Provide the Jodo Services to you.\n- purpose: Fraud prevention\n  text: Identify, prevent, and report potentially prohibited, fraudulent, or illegal activities.\n- purpose: Customer support\n  text: Provide customer support and resolve disputes.\n- purpose: Marketing\n  text: Provide you with news, offers, and information about the Jodo Services based on your communications preferences.\nretention:\n- scope: Account information\n  period: as long as your account is active\n  text: We will retain your information for as long as your account is active or as needed to provide you the Jodo\n\
  \    Services.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support request to close account\n  text: If you wish to close your account or request that we no longer use your information to provide you the Jodo\n    Services, contact us at support@jodopay.com .\nrights:\n- right: Withdraw consent\n  text: You have the right to withdraw your consent to the processing of your personal data at any time.\n- right: Update or correct information\n  text: If your personal information changes, you can update or correct it in your account settings\n- right: Unsubscribe from promotional emails\n  text: click on the unsubscribe link at the bottom of any promotional email that we send you\nsale_or_sharing:\n  stance: conditional\n  text: Other than as stated in this Privacy Policy, Jodo does not disclose or sell any of your personal information\n    to third parties without your consent.\n"
source_yaml_url: https://artifacts.apis.io/jodo/privacy/jodo-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Jodo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Education
- Fintech
- Fee Collection
- Lending
- India
- Webhook
- ERP Integration
- Financial Services
---
