---
api_specs:
- filename: xrhealth-auth-api-openapi.yml
  format: yaml
  label: XRHealth Auth API
  slug: xrhealth-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrhealth/openapi/xrhealth-auth-api-openapi.yml
- filename: xrhealth-me-api-openapi.yml
  format: yaml
  label: XRHealth Me API
  slug: xrhealth-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrhealth/openapi/xrhealth-me-api-openapi.yml
- filename: xrhealth-openapi-json-api-openapi.yml
  format: yaml
  label: XRHealth Openapi.json API
  slug: xrhealth-openapi-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrhealth/openapi/xrhealth-openapi-json-api-openapi.yml
- filename: xrhealth-well-known-api-openapi.yml
  format: yaml
  label: XRHealth .well Known API
  slug: xrhealth-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrhealth/openapi/xrhealth-well-known-api-openapi.yml
- filename: xrhealth-xrhealth-platform-api-api-openapi.yml
  format: yaml
  label: XRHealth XRHealth Platform API
  slug: xrhealth-xrhealth-platform-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrhealth/openapi/xrhealth-xrhealth-platform-api-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: It is provided via form and includes data such as your full name, phone number and email address.
  - category: financial
    text: 'Payment data: containing information such as your name, email address and related payment information.'
  - category: device
    text: 'Technical Data: This is your IP address, browser type and version, time zone setting and location, operating system and platform, and other technology on the devices you use to engage with us.'
  - category: health
    text: 'Patient Clinical Data: This is any medical data either entered by yourself, or added to by the medical professional working with you.'
  - category: demographic
    text: 'optional such as: address, mobile phone, gender, date of birth, nationality, health insurance information, job status, civil status, religion, professional occupation.'
  deletion:
    route: Email compliance@xrhealth.com or compliance@xr.health for data subject requests
    text: 'To exercise these rights, you can send an email to us at any point at the following email address: compliance@xrhealth.com.'
  dpa:
    available: null
    text: They are bound by appropriate contractual agreements, such as Data Processing Agreements.
    url: null
  purposes:
  - purpose: Contractual obligations to customers and clinics
    text: To fulfil our contractual obligations to the clinics, hospitals and medical professionals who use our platform.
  - purpose: Marketing and communications
    text: Customers will receive service-related emails, as well as engagement emails that will offer marketing information that could be relevant to the users.
  - purpose: Analytics with consent
    text: This is used for analytics, with your consent, as well as to improve site functionality.
  - purpose: Provide services and maintain security
    text: (c) provide services to you, or (d) maintain the operations and security of the website and services we provide to you.
  residency:
  - region: United States
    text: We are headquartered in the United States and have service providers primarily based in the United States.
  retention:
  - period: null
    scope: Consent-based processing
    text: In most cases, we store your data if you have consented to the processing until you revoke your consent.
  - period: null
    scope: Contractual relationship
    text: If we need the data to perform a contract with you, we retain the data for as long as the contractual relationship with you exists.
  - period: six months
    scope: Applicant documents
    text: We store applicant documents for a period of six months if the application does not lead to an employment relationship and no further storage has been agreed.
  rights:
  - right: Access/information
    text: Information, in accordance with Art. 15 EU/UK GDPR
  - right: Rectification
    text: Rectification, in accordance with Art. 16 EU/UK GDPR
  - right: Erasure
    text: Data erasure (“right to be forgotten”), in accordance with Art. 17 EU/UK GDPR
  - right: Restriction of processing
    text: Limitation of processing, pursuant to Art. 18 EU/UK GDPR
  - right: Portability
    text: Data portability, according to Art. 20 EU/UK GDPR
  - right: Objection
    text: Objection to the processing, pursuant to Art. 21 EU/UK GDPR
  - right: Opt out of sale or sharing (California)
    text: opt out of the sale or sharing of your personal information
  role:
    text: In operating our App & platform, we primarily act as a Data Processor of your personal data. We act as Data Controller for your Customer Profile, purchase information and any data related to your use of cookies on our App/platform.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: XRHealth ensures that appropriate contractual measures are in place to govern any transfers of your personal data to our processors or subprocessors.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: XRHealth
provenance_date: '2026-11-10'
provider_name: XRHealth
provider_slug: xrhealth
slug: xrhealth-privacy-policy
source_date: '2026-11-10'
source_filename: xrhealth-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://platform.xr.health/en/p/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: XRHealth\naid: xrhealth\nurl: https://platform.xr.health/en/p/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: In operating our App & platform, we primarily act as a Data Processor of your personal data. We act as Data\n    Controller for your Customer Profile, purchase information and any data related to your use of cookies on our\n    App/platform.\ndata_categories:\n- category: contact\n  text: It is provided via form and includes data such as your full name, phone number and email address.\n- category: financial\n  text: 'Payment data: containing information such as your name, email address\
  \ and related payment information.'\n- category: device\n  text: 'Technical Data: This is your IP address, browser type and version, time zone setting and location, operating\n    system and platform, and other technology on the devices you use to engage with us.'\n- category: health\n  text: 'Patient Clinical Data: This is any medical data either entered by yourself, or added to by the medical\n    professional working with you.'\n- category: demographic\n  text: 'optional such as: address, mobile phone, gender, date of birth, nationality, health insurance information,\n    job status, civil status, religion, professional occupation.'\npurposes:\n- purpose: Contractual obligations to customers and clinics\n  text: To fulfil our contractual obligations to the clinics, hospitals and medical professionals who use our platform.\n- purpose: Marketing and communications\n  text: Customers will receive service-related emails, as well as engagement emails that will offer marketing information\n\
  \    that could be relevant to the users.\n- purpose: Analytics with consent\n  text: This is used for analytics, with your consent, as well as to improve site functionality.\n- purpose: Provide services and maintain security\n  text: (c) provide services to you, or (d) maintain the operations and security of the website and services we\n    provide to you.\nretention:\n- scope: Consent-based processing\n  period: null\n  text: In most cases, we store your data if you have consented to the processing until you revoke your consent.\n- scope: Contractual relationship\n  period: null\n  text: If we need the data to perform a contract with you, we retain the data for as long as the contractual relationship\n    with you exists.\n- scope: Applicant documents\n  period: six months\n  text: We store applicant documents for a period of six months if the application does not lead to an employment\n    relationship and no further storage has been agreed.\nresidency:\n- region: United States\n  text:\
  \ We are headquartered in the United States and have service providers primarily based in the United States.\ntransfers:\n- mechanism: other\n  text: XRHealth ensures that appropriate contractual measures are in place to govern any transfers of your personal\n    data to our processors or subprocessors.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: They are bound by appropriate contractual agreements, such as Data Processing Agreements.\ndeletion:\n  route: Email compliance@xrhealth.com or compliance@xr.health for data subject requests\n  text: 'To exercise these rights, you can send an email to us at any point at the following email address: compliance@xrhealth.com.'\nrights:\n- right: Access/information\n  text: Information, in accordance with Art. 15 EU/UK GDPR\n- right: Rectification\n  text: Rectification, in accordance with Art. 16 EU/UK GDPR\n- right: Erasure\n  text: Data erasure (“right to be forgotten”), in accordance with Art. 17 EU/UK\
  \ GDPR\n- right: Restriction of processing\n  text: Limitation of processing, pursuant to Art. 18 EU/UK GDPR\n- right: Portability\n  text: Data portability, according to Art. 20 EU/UK GDPR\n- right: Objection\n  text: Objection to the processing, pursuant to Art. 21 EU/UK GDPR\n- right: Opt out of sale or sharing (California)\n  text: opt out of the sale or sharing of your personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your information.\n"
source_yaml_url: https://artifacts.apis.io/xrhealth/privacy/xrhealth-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from XRHealth's own page on 2026-11-10.
synthetic: false
tags:
- Health
- Digital Health
- Telehealth
- Virtual Reality
- Extended Reality
- Medical Devices
- Rehabilitation
- Mental Health
- Patient Authentication
- Healthcare
---
