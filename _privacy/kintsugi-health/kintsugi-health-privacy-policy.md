---
api_specs:
- filename: kintsugi-health-feedback-api-openapi.yml
  format: yaml
  label: Kintsugi Health Feedback API
  slug: kintsugi-health-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kintsugi-health/openapi/kintsugi-health-feedback-api-openapi.yml
- filename: kintsugi-health-initiate-api-openapi.yml
  format: yaml
  label: Kintsugi Health Initiate API
  slug: kintsugi-health-initiate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kintsugi-health/openapi/kintsugi-health-initiate-api-openapi.yml
- filename: kintsugi-health-kintsugi-health-api-api-openapi.yml
  format: yaml
  label: Kintsugi Health Kintsugi Health API
  slug: kintsugi-health-kintsugi-health-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kintsugi-health/openapi/kintsugi-health-kintsugi-health-api-api-openapi.yml
- filename: kintsugi-health-predict-api-openapi.yml
  format: yaml
  label: Kintsugi Health Predict API
  slug: kintsugi-health-predict-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kintsugi-health/openapi/kintsugi-health-predict-api-openapi.yml
- filename: kintsugi-health-prediction-api-openapi.yml
  format: yaml
  label: Kintsugi Health Prediction API
  slug: kintsugi-health-prediction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kintsugi-health/openapi/kintsugi-health-prediction-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact data , such as your first and last name, salutation, email address, and phone number.
  - category: demographic
    text: Demographic data , such as your city, state, country of residence, gender and age.
  - category: identifying
    text: Profile data , such as the username and password that you may set to establish an online account on the Service, date of birth, biographical details, photograph or picture
  - category: communication
    text: Communications data based on our exchanges with you, including when you contact us through the Service, social media, or otherwise.
  - category: health
    text: You may also decide to provide us with sensitive information, such as information about your political beliefs, mental health, sexual orientation, ethnic or racial origin, religious or philosophical beliefs.
  - category: biometric
    text: Voice recordings and other user-generated content , such as recorded voice journals
  - category: device
    text: Device data , such as your computer or mobile device’s operating system type and version, manufacturer and model, browser type
  - category: location
    text: general location information such as city, state or geographic area.
  - category: behavioral
    text: Online activity data , such as pages or screens you viewed, how long you spent on a page or screen
  deletion:
    route: Delete content through account or request account closure via account settings or contact us
    text: If you wish to request to close your account, please do so through your account settings or contact us .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery and operations
    text: 'We may use your personal information, including your Voice Data, to: provide, operate and improve the Service and our business; provide insights and other analyses regarding your emotional state'
  - purpose: Service improvement, research and development
    text: We may use your personal information (including Voice Data) to improve our services and for research and development purposes
  - purpose: Marketing and advertising
    text: We, our service providers and our third-party analytics partners may collect and use your personal information for marketing and advertising purposes
  - purpose: Compliance and protection
    text: comply with applicable laws, lawful requests, and legal process
  - purpose: Aggregated or de-identified data
    text: We may create aggregated, de-identified and/or anonymized data from your personal information and other individuals whose personal information we collect.
  residency:
  - region: United States
    text: Your information, including Personal Data, will be transferred to — and maintained in the United States
  retention:
  - period: null
    scope: Voice Data while account active
    text: we retain such data only for the length of time you maintain your account with us on the App
  - period: 30 days
    scope: Voice Data after account inactivity
    text: in the event your account remains inactive for one year, we will delete your Voice Data from the account within 30 days of such one-year period.
  rights:
  - right: Access
    text: Your right of access - You have the right to ask us for copies of your personal Information.
  - right: Rectification
    text: Your right to rectification - You have the right to ask us to rectify information you think is inaccurate.
  - right: Erasure
    text: Your right to erasure - You have the right to ask us to erase your personal Information in certain circumstances.
  - right: Portability
    text: Your right to data portability - You have the right to ask that we transfer the information you gave us to another organization, or to you, in certain circumstances.
  - right: Object
    text: Your right to object to processing - You have the right to object to the processing of your personal information in certain circumstances.
  - right: Withdraw consent
    text: Your right to withdraw consent - You have the right to withdraw your consent at any time where we rely on your consent to process your personal information.
  role:
    text: Kintsugi is the controller in respect of the processing of your personal information covered by this Privacy Policy for purposes of European data protection legislation
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We will not share your Voice Data or other data regarding your mental wellness (such as responses to our wellness surveys) with advertising partners.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: We may transfer your personal information to countries or territories whose laws have been deemed to provide an adequate level of protection for personal information by the European Commission or UK Government
  - mechanism: other
    text: we may use specific appropriate safeguards, which are designed to give personal information effectively the same protection it has in Europe – for example, standard-form contracts approved by relevant authorise for this purpose
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Kintsugi Health
provenance_date: '2026-11-09'
provider_name: Kintsugi Health
provider_slug: kintsugi-health
slug: kintsugi-health-privacy-policy
source_date: '2026-11-09'
source_filename: kintsugi-health-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.kintsugihealth.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Kintsugi Health\naid: kintsugi-health\nurl: https://www.kintsugihealth.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Kintsugi is the controller in respect of the processing of your personal information covered by this Privacy\n    Policy for purposes of European data protection legislation\ndata_categories:\n- category: contact\n  text: Contact data , such as your first and last name, salutation, email address, and phone number.\n- category: demographic\n  text: Demographic data , such as your city, state, country of residence, gender and age.\n- category: identifying\n  text:\
  \ Profile data , such as the username and password that you may set to establish an online account on the\n    Service, date of birth, biographical details, photograph or picture\n- category: communication\n  text: Communications data based on our exchanges with you, including when you contact us through the Service,\n    social media, or otherwise.\n- category: health\n  text: You may also decide to provide us with sensitive information, such as information about your political beliefs,\n    mental health, sexual orientation, ethnic or racial origin, religious or philosophical beliefs.\n- category: biometric\n  text: Voice recordings and other user-generated content , such as recorded voice journals\n- category: device\n  text: Device data , such as your computer or mobile device’s operating system type and version, manufacturer and\n    model, browser type\n- category: location\n  text: general location information such as city, state or geographic area.\n- category: behavioral\n  text:\
  \ Online activity data , such as pages or screens you viewed, how long you spent on a page or screen\npurposes:\n- purpose: Service delivery and operations\n  text: 'We may use your personal information, including your Voice Data, to: provide, operate and improve the Service\n    and our business; provide insights and other analyses regarding your emotional state'\n- purpose: Service improvement, research and development\n  text: We may use your personal information (including Voice Data) to improve our services and for research and\n    development purposes\n- purpose: Marketing and advertising\n  text: We, our service providers and our third-party analytics partners may collect and use your personal information\n    for marketing and advertising purposes\n- purpose: Compliance and protection\n  text: comply with applicable laws, lawful requests, and legal process\n- purpose: Aggregated or de-identified data\n  text: We may create aggregated, de-identified and/or anonymized data from\
  \ your personal information and other\n    individuals whose personal information we collect.\nretention:\n- scope: Voice Data while account active\n  period: null\n  text: we retain such data only for the length of time you maintain your account with us on the App\n- scope: Voice Data after account inactivity\n  period: 30 days\n  text: in the event your account remains inactive for one year, we will delete your Voice Data from the account\n    within 30 days of such one-year period.\nresidency:\n- region: United States\n  text: Your information, including Personal Data, will be transferred to — and maintained in the United States\ntransfers:\n- mechanism: adequacy\n  text: We may transfer your personal information to countries or territories whose laws have been deemed to provide\n    an adequate level of protection for personal information by the European Commission or UK Government\n- mechanism: other\n  text: we may use specific appropriate safeguards, which are designed to give personal\
  \ information effectively\n    the same protection it has in Europe – for example, standard-form contracts approved by relevant authorise for\n    this purpose\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete content through account or request account closure via account settings or contact us\n  text: If you wish to request to close your account, please do so through your account settings or contact us .\nrights:\n- right: Access\n  text: Your right of access - You have the right to ask us for copies of your personal Information.\n- right: Rectification\n  text: Your right to rectification - You have the right to ask us to rectify information you think is inaccurate.\n- right: Erasure\n  text: Your right to erasure - You have the right to ask us to erase your personal Information in certain circumstances.\n- right: Portability\n  text: Your right to data portability - You have the right to ask that we transfer the\
  \ information you gave us\n    to another organization, or to you, in certain circumstances.\n- right: Object\n  text: Your right to object to processing - You have the right to object to the processing of your personal information\n    in certain circumstances.\n- right: Withdraw consent\n  text: Your right to withdraw consent - You have the right to withdraw your consent at any time where we rely on\n    your consent to process your personal information.\nsale_or_sharing:\n  stance: conditional\n  text: We will not share your Voice Data or other data regarding your mental wellness (such as responses to our\n    wellness surveys) with advertising partners.\n"
source_yaml_url: https://artifacts.apis.io/kintsugi-health/privacy/kintsugi-health-privacy-policy.yml
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
summary_line: 28 quoted statements, read from Kintsugi Health's own page on 2026-11-09.
synthetic: false
tags:
- Health Tech
- Artificial Intelligence
- Voice Analytics
- Mental Health
- Digital Health
---
