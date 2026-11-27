---
api_specs:
- filename: billease-be-store-admin-api-api-openapi.yml
  format: yaml
  label: Billease Be Store Admin API
  slug: billease-be-store-admin-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billease/openapi/billease-be-store-admin-api-api-openapi.yml
- filename: billease-be-transactions-api-api-openapi.yml
  format: yaml
  label: Billease Be Transactions API
  slug: billease-be-transactions-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billease/openapi/billease-be-transactions-api-api-openapi.yml
- filename: billease-categories-api-openapi.yml
  format: yaml
  label: Billease Categories API
  slug: billease-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billease/openapi/billease-categories-api-openapi.yml
- filename: billease-products-api-openapi.yml
  format: yaml
  label: Billease Products API
  slug: billease-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billease/openapi/billease-products-api-openapi.yml
- filename: billease-trx-api-openapi.yml
  format: yaml
  label: Billease Trx API
  slug: billease-trx-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billease/openapi/billease-trx-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, address, phone numbers, email address, date of birth, employment and banking and financial details
  - category: biometric
    text: we collect face data — specifically a selfie image and a liveness capture taken via your device camera
  - category: location
    text: Location data (such as mobile device location, time zone setting)
  - category: device
    text: mobile device data (such as SIM, IMEI, or other device identifiers, type of device, device operating system, device settings
  - category: communication
    text: phone data (such as contact lists and metadata, SMS metadata, types and nature of mobile applications found on your mobile device)
  - category: behavioral
    text: mobile app usage data (such as traffic volume, mobile app usage) and telecommunications usage data or “telco usage score”
  deletion:
    route: null
    text: In the event that your personal data are no longer required to be retained, such data will be disposed or discarded in a secure manner
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: identity verification and KYC
    text: to verify your identity, to comply with the KYC, anti-money-laundering, and record-keeping obligations
  - purpose: credit decisions
    text: make, or assist in making, credit decisions about you
  - purpose: fraud prevention
    text: identify, prevent, detect or tackle fraud, money laundering, terrorism and other crimes
  - purpose: AI model training
    text: training and back-testing machine learning algorithms of our third-party service provider’s software
  - purpose: direct marketing
    text: contact you by email, SMS, letter, telephone or in any other way about our products and services, unless you tell us that you prefer not to receive marketing
  retention:
  - period: null
    scope: face data
    text: We retain face data for as long as necessary to fulfill the declared, specified, and legitimate purpose connected to your use of a Billease account
  - period: null
    scope: personal data and records
    text: We will hold your personal data and records for as long as necessary for the fulfillment of the above-stated purposes and uses
  rights:
  - right: withdraw consent
    text: You may withdraw your consent at any time without affecting the lawfulness of processing based on consent prior to its withdrawal
  - right: access
    text: You have the right to reasonable access to your personal data.
  - right: correction or removal
    text: You may also correct or remove any information that you think is inaccurate.
  - right: destruction
    text: You have the right to the destruction of your personal data
  - right: complaint to NPC
    text: You have the right to lodge a complaint with the NPC.
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
name: Billease
provenance_date: '2026-11-09'
provider_name: Billease
provider_slug: billease
slug: billease-privacy-policy
source_date: '2026-11-09'
source_filename: billease-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://billease.ph/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Billease\naid: billease\nurl: https://billease.ph/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your name, address, phone numbers, email address, date of birth, employment and banking and financial details\n- category: biometric\n  text: we collect face data — specifically a selfie image and a liveness capture taken via your device camera\n- category: location\n  text: Location data (such as mobile device location, time zone setting)\n- category: device\n  text: mobile device data (such as SIM, IMEI, or other device identifiers,\
  \ type of device, device operating system,\n    device settings\n- category: communication\n  text: phone data (such as contact lists and metadata, SMS metadata, types and nature of mobile applications found\n    on your mobile device)\n- category: behavioral\n  text: mobile app usage data (such as traffic volume, mobile app usage) and telecommunications usage data or “telco\n    usage score”\npurposes:\n- purpose: identity verification and KYC\n  text: to verify your identity, to comply with the KYC, anti-money-laundering, and record-keeping obligations\n- purpose: credit decisions\n  text: make, or assist in making, credit decisions about you\n- purpose: fraud prevention\n  text: identify, prevent, detect or tackle fraud, money laundering, terrorism and other crimes\n- purpose: AI model training\n  text: training and back-testing machine learning algorithms of our third-party service provider’s software\n- purpose: direct marketing\n  text: contact you by email, SMS, letter, telephone\
  \ or in any other way about our products and services, unless\n    you tell us that you prefer not to receive marketing\nretention:\n- scope: face data\n  period: null\n  text: We retain face data for as long as necessary to fulfill the declared, specified, and legitimate purpose\n    connected to your use of a Billease account\n- scope: personal data and records\n  period: null\n  text: We will hold your personal data and records for as long as necessary for the fulfillment of the above-stated\n    purposes and uses\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: In the event that your personal data are no longer required to be retained, such data will be disposed or\n    discarded in a secure manner\nrights:\n- right: withdraw consent\n  text: You may withdraw your consent at any time without affecting the lawfulness of processing based on consent\n    prior to its withdrawal\n\
  - right: access\n  text: You have the right to reasonable access to your personal data.\n- right: correction or removal\n  text: You may also correct or remove any information that you think is inaccurate.\n- right: destruction\n  text: You have the right to the destruction of your personal data\n- right: complaint to NPC\n  text: You have the right to lodge a complaint with the NPC.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/billease/privacy/billease-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 19 quoted statements, read from Billease's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Buy Now Pay Later
- Philippines
- Loans
---
