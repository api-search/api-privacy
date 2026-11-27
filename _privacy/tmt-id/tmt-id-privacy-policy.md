---
api_specs:
- filename: tmt-id-authenticate-api-openapi.yml
  format: yaml
  label: TMT ID Authenticate API
  slug: tmt-id-authenticate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tmt-id/openapi/tmt-id-authenticate-api-openapi.yml
- filename: tmt-id-http-api-api-openapi.yml
  format: yaml
  label: TMT ID HTTP API
  slug: tmt-id-http-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tmt-id/openapi/tmt-id-http-api-api-openapi.yml
- filename: tmt-id-http-api-v1-3-api-openapi.yml
  format: yaml
  label: TMT ID HTTP API v1.3 API
  slug: tmt-id-http-api-v1-3-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tmt-id/openapi/tmt-id-http-api-v1-3-api-openapi.yml
- filename: tmt-id-http-api-v2-0-api-openapi.yml
  format: yaml
  label: TMT ID HTTP API v2.0 API
  slug: tmt-id-http-api-v2-0-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tmt-id/openapi/tmt-id-http-api-v2-0-api-openapi.yml
- filename: tmt-id-network-biometrics-api-openapi.yml
  format: yaml
  label: TMT ID Network Biometrics API
  slug: tmt-id-network-biometrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tmt-id/openapi/tmt-id-network-biometrics-api-openapi.yml
- filename: tmt-id-service-api-openapi.yml
  format: yaml
  label: TMT ID Service API
  slug: tmt-id-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tmt-id/openapi/tmt-id-service-api-openapi.yml
- filename: tmt-id-standard-api-call-api-openapi.yml
  format: yaml
  label: TMT ID Standard API Call API
  slug: tmt-id-standard-api-call-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tmt-id/openapi/tmt-id-standard-api-call-api-openapi.yml
- filename: tmt-id-v2-deprecated-api-openapi.yml
  format: yaml
  label: TMT ID v2 (deprecated) API
  slug: tmt-id-v2-deprecated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tmt-id/openapi/tmt-id-v2-deprecated-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'the personal data you give us may include: name and address; e-mail address; username, password; IP address; phone numbers; credit card details; occupation; and date of birth.'
  - category: financial
    text: We may have access to your financial information, such as your billing address, bank account details and payment history
  - category: device
    text: your device’s manufacturer and model, IP address, browser type and version, time zone setting, browser plug-in types and versions, operating system, web browser, platform, mobile carrier, and your ISP.
  - category: behavioral
    text: We may collect details of your visits to our Website (including, but not limited to, traffic data, location data, weblogs and other communication data).
  deletion:
    route: request to delete personal data
    text: In some circumstances you can ask us to delete your personal data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: dealing with inquiries and requests
    text: dealing with your inquiries and requests, including contacting you where necessary
  - purpose: fraud prevention and identity verification for business clients
    text: identification verification services on behalf of our business clients (by checking such personal data against third party databases).
  - purpose: marketing communications
    text: to send you marketing communications, for instance, to contact you from time to time regarding things you have told us you want to hear about
  residency:
  - region: outside the EEA
    text: The data that we collect from you may be transferred to, and stored at, a destination outside the European Economic Area (“EEA”).
  retention:
  - period: six (6) years
    scope: basic customer information
    text: by law we have to keep basic information about our customers (including contact, identity, financial and transaction data) typically for six (6) years after they cease being customers for tax purposes.
  - period: null
    scope: real-time API data
    text: For most of our products and services, we do not retain the personal information transmitted to us in real-time by our business clients.
  rights:
  - right: access
    text: request access to your personal data (commonly known as a “data subject access request”);
  - right: correction
    text: request correction of the personal data that we hold about you;
  - right: erasure
    text: request erasure of your personal data.
  - right: objection
    text: object to processing of your personal data where we are relying on a legitimate interest
  - right: restriction
    text: request restriction of processing of your personal data.
  - right: portability
    text: request the transfer of your personal data to you or to a third party.
  - right: withdraw consent
    text: withdraw consent at any time where we are relying on consent to process your personal data.
  role:
    text: For the purpose of the Data Protection Legislation, the data controller is TMT Analysis Limited.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or otherwise provide your personal data to third parties unless you consent to this or it is necessary to provide you with our services or as described in this Privacy Notice.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: in most cases we use approved ‘Standard Contractual Clauses’ approved by the European Commission and a risk assessment
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TMT ID
provenance_date: '2026-11-10'
provider_name: TMT ID
provider_slug: tmt-id
slug: tmt-id-privacy-policy
source_date: '2026-11-10'
source_filename: tmt-id-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tmtid.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TMT ID\naid: tmt-id\nurl: https://tmtid.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: For the purpose of the Data Protection Legislation, the data controller is TMT Analysis Limited.\ndata_categories:\n- category: identifying\n  text: 'the personal data you give us may include: name and address; e-mail address; username, password; IP address;\n    phone numbers; credit card details; occupation; and date of birth.'\n- category: financial\n  text: We may have access to your financial information, such as your billing address, bank account details and\n    payment history\n\
  - category: device\n  text: your device’s manufacturer and model, IP address, browser type and version, time zone setting, browser plug-in\n    types and versions, operating system, web browser, platform, mobile carrier, and your ISP.\n- category: behavioral\n  text: We may collect details of your visits to our Website (including, but not limited to, traffic data, location\n    data, weblogs and other communication data).\npurposes:\n- purpose: dealing with inquiries and requests\n  text: dealing with your inquiries and requests, including contacting you where necessary\n- purpose: fraud prevention and identity verification for business clients\n  text: identification verification services on behalf of our business clients (by checking such personal data against\n    third party databases).\n- purpose: marketing communications\n  text: to send you marketing communications, for instance, to contact you from time to time regarding things you\n    have told us you want to hear about\nretention:\n\
  - scope: basic customer information\n  period: six (6) years\n  text: by law we have to keep basic information about our customers (including contact, identity, financial and\n    transaction data) typically for six (6) years after they cease being customers for tax purposes.\n- scope: real-time API data\n  period: null\n  text: For most of our products and services, we do not retain the personal information transmitted to us in real-time\n    by our business clients.\nresidency:\n- region: outside the EEA\n  text: The data that we collect from you may be transferred to, and stored at, a destination outside the European\n    Economic Area (“EEA”).\ntransfers:\n- mechanism: SCC\n  text: in most cases we use approved ‘Standard Contractual Clauses’ approved by the European Commission and a risk\n    assessment\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request to delete personal data\n  text: In some circumstances you\
  \ can ask us to delete your personal data.\nrights:\n- right: access\n  text: request access to your personal data (commonly known as a “data subject access request”);\n- right: correction\n  text: request correction of the personal data that we hold about you;\n- right: erasure\n  text: request erasure of your personal data.\n- right: objection\n  text: object to processing of your personal data where we are relying on a legitimate interest\n- right: restriction\n  text: request restriction of processing of your personal data.\n- right: portability\n  text: request the transfer of your personal data to you or to a third party.\n- right: withdraw consent\n  text: withdraw consent at any time where we are relying on consent to process your personal data.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or otherwise provide your personal data to third parties unless you consent to this\n    or it is necessary to provide you with our services or as described in this\
  \ Privacy Notice.\n"
source_yaml_url: https://artifacts.apis.io/tmt-id/privacy/tmt-id-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from TMT ID's own page on 2026-11-10.
synthetic: false
tags:
- Telecommunications
- United Kingdom
- Identity Verification
- Mobile Identity
- SIM Swap
- Fraud Prevention
- Number Intelligence
- Silent Network Authentication
- GSMA Open Gateway
- Network APIs
- ENUM
- KYC
---
