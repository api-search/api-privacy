---
api_specs:
- filename: figure-technology-solutions-encryption-api-openapi.yml
  format: yaml
  label: Figure Technology Solutions Encryption API
  slug: figure-technology-solutions-encryption-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/figure-technology-solutions/openapi/figure-technology-solutions-encryption-api-openapi.yml
- filename: figure-technology-solutions-heloc-application-requests-api-openapi.yml
  format: yaml
  label: Figure Technology Solutions HELOC application requests API
  slug: figure-technology-solutions-heloc-application-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/figure-technology-solutions/openapi/figure-technology-solutions-heloc-application-requests-api-openapi.yml
- filename: figure-technology-solutions-heloc-offers-api-openapi.yml
  format: yaml
  label: Figure Technology Solutions HELOC Offers API
  slug: figure-technology-solutions-heloc-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/figure-technology-solutions/openapi/figure-technology-solutions-heloc-offers-api-openapi.yml
- filename: figure-technology-solutions-loan-originator-requests-api-openapi.yml
  format: yaml
  label: Figure Technology Solutions Loan Originator requests API
  slug: figure-technology-solutions-loan-originator-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/figure-technology-solutions/openapi/figure-technology-solutions-loan-originator-requests-api-openapi.yml
- filename: figure-technology-solutions-loan-tape-v1-api-openapi.yml
  format: yaml
  label: Figure Technology Solutions Loan Tape V1 API
  slug: figure-technology-solutions-loan-tape-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/figure-technology-solutions/openapi/figure-technology-solutions-loan-tape-v1-api-openapi.yml
- filename: figure-technology-solutions-loan-tape-v2-api-openapi.yml
  format: yaml
  label: Figure Technology Solutions Loan Tape V2 API
  slug: figure-technology-solutions-loan-tape-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/figure-technology-solutions/openapi/figure-technology-solutions-loan-tape-v2-api-openapi.yml
- filename: figure-technology-solutions-payment-history-v1-api-openapi.yml
  format: yaml
  label: Figure Technology Solutions Payment History V1 API
  slug: figure-technology-solutions-payment-history-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/figure-technology-solutions/openapi/figure-technology-solutions-payment-history-v1-api-openapi.yml
- filename: figure-technology-solutions-payment-history-v2-api-openapi.yml
  format: yaml
  label: Figure Technology Solutions Payment History V2 API
  slug: figure-technology-solutions-payment-history-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/figure-technology-solutions/openapi/figure-technology-solutions-payment-history-v2-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, postal address, email address, account name, social security number, driver’s license number, passport number, or other similar identifiers
  - category: financial
    text: bank account and routing numbers, or transaction information
  - category: biometric
    text: Face Geometry
  - category: location
    text: we may also collect your precise location information when you use our Services
  - category: device
    text: IP address, operating system version, phone carrier and manufacturer, device identifiers, and push notification tokens
  - category: behavioral
    text: Browsing history, search history, settings, and information regarding an individual’s interaction with an internet website, application, or advertisement
  - category: communication
    text: Service calls, video recording of notary session, voicemails and other audio recordings, photographs
  - category: professional
    text: Employer, years of employment
  deletion:
    route: Data Subject Access Request (DSAR) web form
    text: You can submit a request to access the Personal Information we have collected about you and/or to request that we correct or delete your Personal Information using our Privacy Web Form
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide Services and customer service
    text: To provide you with the Services and related customer service
  - purpose: determine qualification for financial products
    text: To determine whether you qualify for financial products and services
  - purpose: advertising and marketing
    text: For advertising and marketing purposes, solely to enhance our services and better cater to your needs
  - purpose: fraud detection and security
    text: To detect, prevent, and address fraud, criminal activity, or misuses of our Services
  - purpose: legal compliance
    text: To comply with legal obligations and legal process
  residency:
  - region: United States
    text: Our Services are hosted in the United States and intended for visitors located within the United States.
  retention:
  - period: at least five years
    scope: Cayman Islands users of Figure Markets platform
    text: we are required to retain certain personal information for at least five years after our business relationship ends
  rights:
  - right: access, correction, deletion
    text: You can submit a request to access the Personal Information we have collected about you and/or to request that we correct or delete your Personal Information
  - right: complaint to Cayman Islands Ombudsman
    text: you have the right to submit a complaint with the Cayman Islands Ombudsman
  - right: opt out of marketing communications
    text: Our email and text marketing communications will include instructions that permit you to “opt out” of receiving future marketing communications.
  role:
    text: We act as a Data Controller under the Cayman Islands Data Protection Act (2021 Revision)
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We want to be clear that we do not sell your Personal Data to any other entities.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We may also transfer your information from the United States to other countries or regions in connection with storage and processing of data
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Figure Technology Solutions
provenance_date: '2026-11-09'
provider_name: Figure Technology Solutions
provider_slug: figure-technology-solutions
slug: figure-technology-solutions-privacy-policy
source_date: '2026-11-09'
source_filename: figure-technology-solutions-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.figure.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Figure Technology Solutions\naid: figure-technology-solutions\nurl: https://www.figure.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We act as a Data Controller under the Cayman Islands Data Protection Act (2021 Revision)\ndata_categories:\n- category: identifying\n  text: Name, postal address, email address, account name, social security number, driver’s license number, passport\n    number, or other similar identifiers\n- category: financial\n  text: bank account and routing numbers, or transaction information\n- category: biometric\n  text: Face Geometry\n- category: location\n\
  \  text: we may also collect your precise location information when you use our Services\n- category: device\n  text: IP address, operating system version, phone carrier and manufacturer, device identifiers, and push notification\n    tokens\n- category: behavioral\n  text: Browsing history, search history, settings, and information regarding an individual’s interaction with an\n    internet website, application, or advertisement\n- category: communication\n  text: Service calls, video recording of notary session, voicemails and other audio recordings, photographs\n- category: professional\n  text: Employer, years of employment\npurposes:\n- purpose: provide Services and customer service\n  text: To provide you with the Services and related customer service\n- purpose: determine qualification for financial products\n  text: To determine whether you qualify for financial products and services\n- purpose: advertising and marketing\n  text: For advertising and marketing purposes, solely to\
  \ enhance our services and better cater to your needs\n- purpose: fraud detection and security\n  text: To detect, prevent, and address fraud, criminal activity, or misuses of our Services\n- purpose: legal compliance\n  text: To comply with legal obligations and legal process\nretention:\n- scope: Cayman Islands users of Figure Markets platform\n  period: at least five years\n  text: we are required to retain certain personal information for at least five years after our business relationship\n    ends\nresidency:\n- region: United States\n  text: Our Services are hosted in the United States and intended for visitors located within the United States.\ntransfers:\n- mechanism: other\n  text: We may also transfer your information from the United States to other countries or regions in connection\n    with storage and processing of data\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Data Subject Access Request (DSAR) web\
  \ form\n  text: You can submit a request to access the Personal Information we have collected about you and/or to request\n    that we correct or delete your Personal Information using our Privacy Web Form\nrights:\n- right: access, correction, deletion\n  text: You can submit a request to access the Personal Information we have collected about you and/or to request\n    that we correct or delete your Personal Information\n- right: complaint to Cayman Islands Ombudsman\n  text: you have the right to submit a complaint with the Cayman Islands Ombudsman\n- right: opt out of marketing communications\n  text: Our email and text marketing communications will include instructions that permit you to “opt out” of receiving\n    future marketing communications.\nsale_or_sharing:\n  stance: prohibited\n  text: We want to be clear that we do not sell your Personal Data to any other entities.\n"
source_yaml_url: https://artifacts.apis.io/figure-technology-solutions/privacy/figure-technology-solutions-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Figure Technology Solutions's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Lending
- HELOC
- Home Equity
- Mortgage
- Capital Markets
- Blockchain
- Loan Origination
- Financial Services
---
