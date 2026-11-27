---
api_specs:
- filename: zest-authentication-api-openapi.yml
  format: yaml
  label: Zest Authentication API
  slug: zest-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zest/openapi/zest-authentication-api-openapi.yml
- filename: zest-contracts-api-openapi.yml
  format: yaml
  label: Zest Contracts API
  slug: zest-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zest/openapi/zest-contracts-api-openapi.yml
- filename: zest-investors-api-openapi.yml
  format: yaml
  label: Zest Investors API
  slug: zest-investors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zest/openapi/zest-investors-api-openapi.yml
- filename: zest-spv-requests-api-openapi.yml
  format: yaml
  label: Zest SPV Requests API
  slug: zest-spv-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zest/openapi/zest-spv-requests-api-openapi.yml
- filename: zest-subscription-forms-api-openapi.yml
  format: yaml
  label: Zest Subscription Forms API
  slug: zest-subscription-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zest/openapi/zest-subscription-forms-api-openapi.yml
- filename: zest-subscription-fundings-api-openapi.yml
  format: yaml
  label: Zest Subscription Fundings API
  slug: zest-subscription-fundings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zest/openapi/zest-subscription-fundings-api-openapi.yml
- filename: zest-subscriptions-api-openapi.yml
  format: yaml
  label: Zest Subscriptions API
  slug: zest-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zest/openapi/zest-subscriptions-api-openapi.yml
- filename: zest-system-api-openapi.yml
  format: yaml
  label: Zest System API
  slug: zest-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zest/openapi/zest-system-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personal data relating to identification (e.g. full name, date of birth, residence address, email address, mobile number, passport, national identity card, visa details, photo, tax number).
  - category: biometric
    text: Special categories of personal data (biometric verification data, where required for identity verification, fraud prevention, liveness detection and onboarding checks).
  - category: financial
    text: Other personal data (e.g. sources of wealth, banking relationships).
  - category: device
    text: device information including, but not limited to, name and type of operating system
  - category: location
    text: Information we collect automatically When you visit our Site and use our Platform we automatically collect the information sent to us by your computer, mobile phone or other device.
  - category: behavioral
    text: Google Analytics that collect, monitor and analyse information about demographics and navigational behaviour.
  - category: professional
    text: Employment details (e.g. employer name, employment address, employment details).
  deletion:
    route: contact us
    text: When your personal data is no longer necessary for the purpose for which it was originally collected, we will delete it, or we will store your information in an aggregated and anonymized format
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: verify identity and onboarding
    text: verify your identity, and assess whether we can accept you as a customer
  - purpose: account administration
    text: create and maintain your account and to allow you to access and use our Platform
  - purpose: AI-assisted verification and fraud detection
    text: improve and develop our products and services, including the AI-assisted tools and systems we use to verify the information and details you provide
  - purpose: legal compliance
    text: to comply with any applicable legal obligations (such as in relation to onboarding users)
  residency:
  - region: outside DIFC, ADGM and Cayman Islands
    text: The personal data that we collect from you may be transferred to, and stored at/processed in countries outside the DIFC, ADGM and/or the Cayman Islands.
  retention:
  - period: six years
    scope: AML-collected personal data
    text: where we have collected your personal data as required by anti-money laundering legislation, including for identification, screening and reporting, we will retain that personal data for six years after the termination of our relationship with you
  - period: ten years
    scope: most other cases
    text: in most other cases, we will retain your personal data for a period of ten years after the termination of our contractual or other relationship with you
  rights:
  - right: Access
    text: 'Access: You have the right to access personal data we hold about you, how we use it, and who we share it with.'
  - right: Rectification
    text: 'Rectification: You have the right to correct any of your personal data we hold that is inaccurate.'
  - right: Objection
    text: 'Objection: You have the right to object to our processing of your personal data.'
  - right: Restriction of processing
    text: 'Restriction of processing: You have the right to require us to stop processing the personal data we hold about you in certain circumstances and with certain exceptions.'
  - right: Portability
    text: 'Portability: You have the right to receive a copy of the personal data we hold about you and to request that we transfer it to a third party'
  - right: Erasure
    text: 'Erasure: In certain circumstance, you have the right to delete the personal data we hold about you.'
  - right: Withdrawal of consent
    text: 'Withdrawal of consent: Where we rely on consent to process your personal data, you have the right to withdraw this consent at any time.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: the relevant model contracts for the transfer of personal data to third countries (i.e., the standard contractual clauses) (the "Model Clauses")
  - mechanism: adequacy
    text: unless the data transfer is to a country that has been determined by the DIFC or ADGM data protection regulator (as applicable), to provide an adequate level of protection
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Zest
provenance_date: '2026-11-10'
provider_name: Zest
provider_slug: zest
slug: zest-privacy-policy
source_date: '2026-11-10'
source_filename: zest-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://app.zestequity.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Zest\naid: zest\nurl: https://app.zestequity.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Personal data relating to identification (e.g. full name, date of birth, residence address, email address,\n    mobile number, passport, national identity card, visa details, photo, tax number).\n- category: biometric\n  text: Special categories of personal data (biometric verification data, where required for identity verification,\n    fraud prevention, liveness detection and onboarding checks).\n- category: financial\n  text:\
  \ Other personal data (e.g. sources of wealth, banking relationships).\n- category: device\n  text: device information including, but not limited to, name and type of operating system\n- category: location\n  text: Information we collect automatically When you visit our Site and use our Platform we automatically collect\n    the information sent to us by your computer, mobile phone or other device.\n- category: behavioral\n  text: Google Analytics that collect, monitor and analyse information about demographics and navigational behaviour.\n- category: professional\n  text: Employment details (e.g. employer name, employment address, employment details).\npurposes:\n- purpose: verify identity and onboarding\n  text: verify your identity, and assess whether we can accept you as a customer\n- purpose: account administration\n  text: create and maintain your account and to allow you to access and use our Platform\n- purpose: AI-assisted verification and fraud detection\n  text: improve and\
  \ develop our products and services, including the AI-assisted tools and systems we use to verify\n    the information and details you provide\n- purpose: legal compliance\n  text: to comply with any applicable legal obligations (such as in relation to onboarding users)\nretention:\n- scope: AML-collected personal data\n  period: six years\n  text: where we have collected your personal data as required by anti-money laundering legislation, including for\n    identification, screening and reporting, we will retain that personal data for six years after the termination\n    of our relationship with you\n- scope: most other cases\n  period: ten years\n  text: in most other cases, we will retain your personal data for a period of ten years after the termination of\n    our contractual or other relationship with you\nresidency:\n- region: outside DIFC, ADGM and Cayman Islands\n  text: The personal data that we collect from you may be transferred to, and stored at/processed in countries outside\n\
  \    the DIFC, ADGM and/or the Cayman Islands.\ntransfers:\n- mechanism: SCC\n  text: the relevant model contracts for the transfer of personal data to third countries (i.e., the standard contractual\n    clauses) (the \"Model Clauses\")\n- mechanism: adequacy\n  text: unless the data transfer is to a country that has been determined by the DIFC or ADGM data protection regulator\n    (as applicable), to provide an adequate level of protection\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact us\n  text: When your personal data is no longer necessary for the purpose for which it was originally collected, we\n    will delete it, or we will store your information in an aggregated and anonymized format\nrights:\n- right: Access\n  text: 'Access: You have the right to access personal data we hold about you, how we use it, and who we share it\n    with.'\n- right: Rectification\n  text: 'Rectification: You have the right\
  \ to correct any of your personal data we hold that is inaccurate.'\n- right: Objection\n  text: 'Objection: You have the right to object to our processing of your personal data.'\n- right: Restriction of processing\n  text: 'Restriction of processing: You have the right to require us to stop processing the personal data we hold\n    about you in certain circumstances and with certain exceptions.'\n- right: Portability\n  text: 'Portability: You have the right to receive a copy of the personal data we hold about you and to request\n    that we transfer it to a third party'\n- right: Erasure\n  text: 'Erasure: In certain circumstance, you have the right to delete the personal data we hold about you.'\n- right: Withdrawal of consent\n  text: 'Withdrawal of consent: Where we rely on consent to process your personal data, you have the right to withdraw\n    this consent at any time.'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zest/privacy/zest-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 24 quoted statements, read from Zest's own page on 2026-11-10.
synthetic: false
tags:
- Company
- SPV
- Private Markets
- Fintech
- Equity
- Investor
- Escrow
- SPaaS
- MENA
---
