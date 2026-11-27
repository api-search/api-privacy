---
api_specs:
- filename: clover-charges-api-openapi.yml
  format: yaml
  label: Clover CHARGES API
  slug: clover-charges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-charges-api-openapi.yml
- filename: clover-checkout-api-openapi.yml
  format: yaml
  label: Clover CHECKOUT API
  slug: clover-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-checkout-api-openapi.yml
- filename: clover-customers-api-openapi.yml
  format: yaml
  label: Clover CUSTOMERS API
  slug: clover-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-customers-api-openapi.yml
- filename: clover-employees-api-openapi.yml
  format: yaml
  label: Clover EMPLOYEES API
  slug: clover-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-employees-api-openapi.yml
- filename: clover-inventory-api-openapi.yml
  format: yaml
  label: Clover INVENTORY API
  slug: clover-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-inventory-api-openapi.yml
- filename: clover-orders-api-openapi.yml
  format: yaml
  label: Clover ORDERS API
  slug: clover-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-orders-api-openapi.yml
- filename: clover-payments-api-openapi.yml
  format: yaml
  label: Clover PAYMENTS API
  slug: clover-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-payments-api-openapi.yml
- filename: clover-refunds-api-openapi.yml
  format: yaml
  label: Clover REFUNDS API
  slug: clover-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-refunds-api-openapi.yml
- filename: clover-tokens-api-openapi.yml
  format: yaml
  label: Clover TOKENS API
  slug: clover-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clover/openapi/clover-tokens-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: financial
    text: Information about transactions includes the payment card used, name associated with the payment card, electronic signature, name and location of the merchant at which the transaction occurred
  - category: biometric
    text: we (or our vendor) may collect biometric information, such as faceprint or palmprint, for the purpose of enabling and completing payment using biometric information
  - category: location
    text: If you consent to the Clover App accessing your location information, we will collect information about your precise location in accordance with your device settings.
  - category: health
    text: In some circumstances, we may collect information that may reveal health or medical information, such as when we process transactions at health or medical facilities or pharmacies.
  - category: behavioral
    text: information about your use of and actions on or in our websites or mobile applications, such as pages or screens you accessed
  deletion:
    route: Contact Clover directly to request modification or deletion of information
    text: You may contact us directly to request access to, or modification or deletion of, your information.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing products and services
    text: Fulfilling a payment or return transaction initiated by you
  - purpose: Marketing
    text: Where required by law, we will get your express opt-in consent before we share your personal data with any company outside the Fiserv group for marketing purposes.
  - purpose: Research and development
    text: 'We use the information we collect for our own research and development purposes, which include: Developing or improving our products and services'
  - purpose: Checking for fraud and risk
    text: Checking for fraud or money laundering and/or managing either our or merchants’ risk
  retention:
  - period: null
    scope: Personal data generally
    text: we will retain your personal data for as long as is necessary for the purposes identified in this Privacy Notice, including to provide our Services, to comply with legal obligations
  rights:
  - right: Access
    text: You are entitled to ask us if we are processing your personal data and, if so, for a copy of the personal data we hold about you
  - right: Correction
    text: If any personal data we hold about you is incomplete or inaccurate, you can require us to correct it
  - right: Erasure
    text: This enables you to ask us to delete or remove personal data where there is no good reason for us continuing to process it.
  - right: Object
    text: You also have the right to object where we are processing your personal data for direct marketing purposes.
  - right: Withdraw consent
    text: Where our reason for processing is based on your consent, you may withdraw that consent at any time.
  role:
    text: Clover Network, LLC is the controller of your personal data for purposes of European and UK data protection law.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: You have the right to opt-out of our sale or sharing of your Personal Information using our opt-out tool located in the bottom right-hand corner of your screen.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: A contract approved by the European Commission (called “Standard Contractual Clauses”)
  - mechanism: BCR
    text: the transfer will be based on our EU or UK Binding Corporate Rules
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Clover
provenance_date: '2026-11-09'
provider_name: Clover
provider_slug: clover
slug: clover-privacy-policy
source_date: '2026-11-09'
source_filename: clover-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.clover.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Clover\naid: clover\nurl: https://www.clover.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: Clover Network, LLC is the controller of your personal data for purposes of European and UK data protection\n    law.\ndata_categories:\n- category: financial\n  text: Information about transactions includes the payment card used, name associated with the payment card, electronic\n    signature, name and location of the merchant at which the transaction occurred\n- category: biometric\n  text: we (or our vendor) may collect biometric information, such as faceprint\
  \ or palmprint, for the purpose of\n    enabling and completing payment using biometric information\n- category: location\n  text: If you consent to the Clover App accessing your location information, we will collect information about\n    your precise location in accordance with your device settings.\n- category: health\n  text: In some circumstances, we may collect information that may reveal health or medical information, such as\n    when we process transactions at health or medical facilities or pharmacies.\n- category: behavioral\n  text: information about your use of and actions on or in our websites or mobile applications, such as pages or\n    screens you accessed\npurposes:\n- purpose: Providing products and services\n  text: Fulfilling a payment or return transaction initiated by you\n- purpose: Marketing\n  text: Where required by law, we will get your express opt-in consent before we share your personal data with any\n    company outside the Fiserv group for marketing purposes.\n\
  - purpose: Research and development\n  text: 'We use the information we collect for our own research and development purposes, which include: Developing\n    or improving our products and services'\n- purpose: Checking for fraud and risk\n  text: Checking for fraud or money laundering and/or managing either our or merchants’ risk\nretention:\n- scope: Personal data generally\n  period: null\n  text: we will retain your personal data for as long as is necessary for the purposes identified in this Privacy\n    Notice, including to provide our Services, to comply with legal obligations\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: A contract approved by the European Commission (called “Standard Contractual Clauses”)\n- mechanism: BCR\n  text: the transfer will be based on our EU or UK Binding Corporate Rules\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact Clover directly to request modification or deletion\
  \ of information\n  text: You may contact us directly to request access to, or modification or deletion of, your information.\nrights:\n- right: Access\n  text: You are entitled to ask us if we are processing your personal data and, if so, for a copy of the personal\n    data we hold about you\n- right: Correction\n  text: If any personal data we hold about you is incomplete or inaccurate, you can require us to correct it\n- right: Erasure\n  text: This enables you to ask us to delete or remove personal data where there is no good reason for us continuing\n    to process it.\n- right: Object\n  text: You also have the right to object where we are processing your personal data for direct marketing purposes.\n- right: Withdraw consent\n  text: Where our reason for processing is based on your consent, you may withdraw that consent at any time.\nsale_or_sharing:\n  stance: conditional\n  text: You have the right to opt-out of our sale or sharing of your Personal Information using our opt-out\
  \ tool\n    located in the bottom right-hand corner of your screen.\n"
source_yaml_url: https://artifacts.apis.io/clover/privacy/clover-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Clover's own page on 2026-11-09.
synthetic: false
tags:
- Restaurant
- Point-of-Sale
- Payments
- Retail
- Small Business
- Hardware
---
