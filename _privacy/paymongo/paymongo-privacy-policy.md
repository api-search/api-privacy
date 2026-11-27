---
api_specs:
- filename: paymongo-checkout-sessions-api-openapi.yml
  format: yaml
  label: PayMongo Checkout Sessions API
  slug: paymongo-checkout-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-checkout-sessions-api-openapi.yml
- filename: paymongo-customers-api-openapi.yml
  format: yaml
  label: PayMongo Customers API
  slug: paymongo-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-customers-api-openapi.yml
- filename: paymongo-payment-intents-api-openapi.yml
  format: yaml
  label: PayMongo Payment Intents API
  slug: paymongo-payment-intents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-payment-intents-api-openapi.yml
- filename: paymongo-payment-links-api-openapi.yml
  format: yaml
  label: PayMongo Payment Links API
  slug: paymongo-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-payment-links-api-openapi.yml
- filename: paymongo-payment-methods-api-openapi.yml
  format: yaml
  label: PayMongo Payment Methods API
  slug: paymongo-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-payment-methods-api-openapi.yml
- filename: paymongo-payments-api-openapi.yml
  format: yaml
  label: PayMongo Payments API
  slug: paymongo-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-payments-api-openapi.yml
- filename: paymongo-qr-ph-api-openapi.yml
  format: yaml
  label: PayMongo QR Ph API
  slug: paymongo-qr-ph-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-qr-ph-api-openapi.yml
- filename: paymongo-refunds-api-openapi.yml
  format: yaml
  label: PayMongo Refunds API
  slug: paymongo-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-refunds-api-openapi.yml
- filename: paymongo-sources-api-openapi.yml
  format: yaml
  label: PayMongo Sources API
  slug: paymongo-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-sources-api-openapi.yml
- filename: paymongo-webhooks-api-openapi.yml
  format: yaml
  label: PayMongo Webhooks API
  slug: paymongo-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paymongo/openapi/paymongo-webhooks-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: first and last name, e-mail address, identification cards and government-issued identification including documents containing a photo and signature
  - category: financial
    text: Financial information, including but not limited to credit or debit card numbers or bank account information
  - category: device
    text: Device information, such as a unique device identifier
  - category: location
    text: Location information, such as your IP address or geo-location
  - category: contact
    text: Phone number
  deletion:
    route: Dashboard or email to the address at the end of the policy
    text: You may delete your Account through the Dashboard, or you may email the address provided at the end of this Policy.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: providing and improving products and services
    text: (i) providing and improving our products and services
  - purpose: identity verification and fraud prevention
    text: (ii) identity verification and fraud prevention
  - purpose: marketing and promotion
    text: We may also use your personal information for marketing and promotion.
  retention:
  - period: six (6) months
    scope: after account deletion request
    text: six (6) months after receipt of your request to delete your Account
  - period: twenty-four (24) hours
    scope: CCV/CVV after failed payment
    text: your CCV/CVV will be deleted within twenty-four (24) hours from the time you receive notification that your payment attempt has failed
  rights:
  - right: access
    text: request access to, or correct your personal information held by us
  - right: object to processing
    text: You may also have the right to object to the processing of your personal information held by us
  - right: file complaint
    text: or to file a complaint with the National Privacy Commission
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
name: PayMongo
provenance_date: '2026-11-10'
provider_name: PayMongo
provider_slug: paymongo
slug: paymongo-privacy-policy
source_date: '2026-11-10'
source_filename: paymongo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.paymongo.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PayMongo\naid: paymongo\nurl: https://www.paymongo.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: first and last name, e-mail address, identification cards and government-issued identification including\n    documents containing a photo and signature\n- category: financial\n  text: Financial information, including but not limited to credit or debit card numbers or bank account information\n- category: device\n  text: Device information, such as a unique device identifier\n- category: location\n  text: Location information,\
  \ such as your IP address or geo-location\n- category: contact\n  text: Phone number\npurposes:\n- purpose: providing and improving products and services\n  text: (i) providing and improving our products and services\n- purpose: identity verification and fraud prevention\n  text: (ii) identity verification and fraud prevention\n- purpose: marketing and promotion\n  text: We may also use your personal information for marketing and promotion.\nretention:\n- scope: after account deletion request\n  period: six (6) months\n  text: six (6) months after receipt of your request to delete your Account\n- scope: CCV/CVV after failed payment\n  period: twenty-four (24) hours\n  text: your CCV/CVV will be deleted within twenty-four (24) hours from the time you receive notification that your\n    payment attempt has failed\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Dashboard or email to the address\
  \ at the end of the policy\n  text: You may delete your Account through the Dashboard, or you may email the address provided at the end of this\n    Policy.\nrights:\n- right: access\n  text: request access to, or correct your personal information held by us\n- right: object to processing\n  text: You may also have the right to object to the processing of your personal information held by us\n- right: file complaint\n  text: or to file a complaint with the National Privacy Commission\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/paymongo/privacy/paymongo-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 14 quoted statements, read from PayMongo's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Fintech
- Philippines
- Southeast Asia
- GCash
- Digital Wallet
- Card Payments
---
