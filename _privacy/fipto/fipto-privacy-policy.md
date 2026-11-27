---
api_specs:
- filename: fipto-aisp-pisp-api-openapi.yml
  format: yaml
  label: Fipto AISP/PISP API
  slug: fipto-aisp-pisp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-aisp-pisp-api-openapi.yml
- filename: fipto-assets-api-openapi.yml
  format: yaml
  label: Fipto Assets API
  slug: fipto-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-assets-api-openapi.yml
- filename: fipto-automations-api-openapi.yml
  format: yaml
  label: Fipto Automations API
  slug: fipto-automations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-automations-api-openapi.yml
- filename: fipto-beneficiaries-api-openapi.yml
  format: yaml
  label: Fipto Beneficiaries API
  slug: fipto-beneficiaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-beneficiaries-api-openapi.yml
- filename: fipto-companies-api-openapi.yml
  format: yaml
  label: Fipto Companies API
  slug: fipto-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-companies-api-openapi.yml
- filename: fipto-conversions-api-openapi.yml
  format: yaml
  label: Fipto Conversions API
  slug: fipto-conversions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-conversions-api-openapi.yml
- filename: fipto-internal-transfers-api-openapi.yml
  format: yaml
  label: Fipto Internal Transfers API
  slug: fipto-internal-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-internal-transfers-api-openapi.yml
- filename: fipto-payin-simulation-api-openapi.yml
  format: yaml
  label: Fipto Payin Simulation API
  slug: fipto-payin-simulation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-payin-simulation-api-openapi.yml
- filename: fipto-payment-links-api-openapi.yml
  format: yaml
  label: Fipto Payment links API
  slug: fipto-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-payment-links-api-openapi.yml
- filename: fipto-transactions-api-openapi.yml
  format: yaml
  label: Fipto Transactions API
  slug: fipto-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-transactions-api-openapi.yml
- filename: fipto-travel-rule-api-openapi.yml
  format: yaml
  label: Fipto Travel Rule API
  slug: fipto-travel-rule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-travel-rule-api-openapi.yml
- filename: fipto-wallets-api-openapi.yml
  format: yaml
  label: Fipto Wallets API
  slug: fipto-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fipto/openapi/fipto-wallets-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity Data. Contact Data. Financial Data. Transaction Data. Device Data. Content Data. Profile Data. Usage Data.
  - category: location
    text: Location Data. We also use your IP address which may determine your geolocation for the purposes of fraud monitoring, prevention, detection, and compliance activities.
  - category: communication
    text: Voice / Call recordings.
  deletion:
    route: contact privacy@fipto.com
    text: 'For any request, please contact us by: Email address: privacy@fipto.com'
  dpa:
    available: null
    text: Where processing of personal data is carried out on behalf of the Company, by an external processor, we conclude a separate contract with the processor with respect to such processing.
    url: null
  purposes:
  - purpose: fraud monitoring and compliance
    text: We also use your IP address which may determine your geolocation for the purposes of fraud monitoring, prevention, detection, and compliance activities.
  - purpose: call recording for security and evidence
    text: the call will be recorded for security and evidential purposes.
  - purpose: contract performance
    text: Need to perform a contract
  retention:
  - period: null
    scope: personal data generally
    text: We must retain personal data only for the minimum period necessary for the purposes set out in this Policy. Then, the data shall be canceled.
  - period: null
    scope: call recordings
    text: The recording of calls will be kept for the time necessary for security purposes and the production of evidence.
  rights:
  - right: withdraw consent
    text: you have the right to withdraw that consent at any time.
  - right: access
    text: You have the right to learn if your Personal Information is being processed by us, obtain disclosure regarding certain aspects of the processing, and obtain a copy of your Personal Information undergoing processing.
  - right: rectification
    text: You have the right to verify the accuracy of your information and ask for it to be updated or corrected.
  - right: objection
    text: You have the right to object to the processing of your information if the processing is carried out on a legal basis other than consent.
  - right: restriction
    text: You have the right, under certain circumstances, to restrict the processing of your Personal Information.
  - right: erasure
    text: You have the right, under certain circumstances, to obtain the erasure of your Personal Information from us.
  - right: portability
    text: You have the right to receive your Personal Information that you have provided to us in a structured, commonly used, and machine-readable format
  - right: complain to authority
    text: you have the right to lodge a complaint with your local data protection authority.
  role:
    text: Fipto is the data controller and is responsible for your personal data.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Whenever we transfer your personal data out of the EEA, we ensure a similar degree of protection is afforded to it by ensuring a safeguard is implemented.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fipto
provenance_date: '2026-11-09'
provider_name: Fipto
provider_slug: fipto
slug: fipto-privacy-policy
source_date: '2026-11-09'
source_filename: fipto-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.fipto.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fipto\naid: fipto\nurl: https://www.fipto.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Fipto is the data controller and is responsible for your personal data.\ndata_categories:\n- category: identifying\n  text: Identity Data. Contact Data. Financial Data. Transaction Data. Device Data. Content Data. Profile Data.\n    Usage Data.\n- category: location\n  text: Location Data. We also use your IP address which may determine your geolocation for the purposes of fraud\n    monitoring, prevention, detection, and compliance activities.\n- category: communication\n  text: Voice\
  \ / Call recordings.\npurposes:\n- purpose: fraud monitoring and compliance\n  text: We also use your IP address which may determine your geolocation for the purposes of fraud monitoring, prevention,\n    detection, and compliance activities.\n- purpose: call recording for security and evidence\n  text: the call will be recorded for security and evidential purposes.\n- purpose: contract performance\n  text: Need to perform a contract\nretention:\n- scope: personal data generally\n  period: null\n  text: We must retain personal data only for the minimum period necessary for the purposes set out in this Policy.\n    Then, the data shall be canceled.\n- scope: call recordings\n  period: null\n  text: The recording of calls will be kept for the time necessary for security purposes and the production of evidence.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Whenever we transfer your personal data out of the EEA, we ensure a similar degree of protection is afforded\n    to it by ensuring\
  \ a safeguard is implemented.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Where processing of personal data is carried out on behalf of the Company, by an external processor, we\n    conclude a separate contract with the processor with respect to such processing.\ndeletion:\n  route: contact privacy@fipto.com\n  text: 'For any request, please contact us by: Email address: privacy@fipto.com'\nrights:\n- right: withdraw consent\n  text: you have the right to withdraw that consent at any time.\n- right: access\n  text: You have the right to learn if your Personal Information is being processed by us, obtain disclosure regarding\n    certain aspects of the processing, and obtain a copy of your Personal Information undergoing processing.\n- right: rectification\n  text: You have the right to verify the accuracy of your information and ask for it to be updated or corrected.\n- right: objection\n  text: You have the right to object to the processing\
  \ of your information if the processing is carried out on a\n    legal basis other than consent.\n- right: restriction\n  text: You have the right, under certain circumstances, to restrict the processing of your Personal Information.\n- right: erasure\n  text: You have the right, under certain circumstances, to obtain the erasure of your Personal Information from\n    us.\n- right: portability\n  text: You have the right to receive your Personal Information that you have provided to us in a structured, commonly\n    used, and machine-readable format\n- right: complain to authority\n  text: you have the right to lodge a complaint with your local data protection authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fipto/privacy/fipto-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
summary_line: 20 quoted statements, read from Fipto's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Blockchain
- Payments
- Stablecoins
- Banking
- Treasury
- Cross-Border Payments
- Digital Currency
- Fintech
- Wallets
---
