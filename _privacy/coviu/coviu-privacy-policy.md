---
api_specs:
- filename: coviu-auth-api-openapi.yml
  format: yaml
  label: Coviu Auth API
  slug: coviu-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-auth-api-openapi.yml
- filename: coviu-collections-api-openapi.yml
  format: yaml
  label: Coviu Collections API
  slug: coviu-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-collections-api-openapi.yml
- filename: coviu-participants-api-openapi.yml
  format: yaml
  label: Coviu Participants API
  slug: coviu-participants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-participants-api-openapi.yml
- filename: coviu-sessions-api-openapi.yml
  format: yaml
  label: Coviu Sessions API
  slug: coviu-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-sessions-api-openapi.yml
- filename: coviu-waiting-area-api-openapi.yml
  format: yaml
  label: Coviu Waiting Area API
  slug: coviu-waiting-area-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-waiting-area-api-openapi.yml
- filename: coviu-webhook-requests-api-openapi.yml
  format: yaml
  label: Coviu Webhook Requests API
  slug: coviu-webhook-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coviu/openapi/coviu-webhook-requests-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity Data including your name, age, profession, and photographic identification.
  - category: contact
    text: Contact Data including your telephone number, address, and email.
  - category: financial
    text: Financial Data including bank account and payment card details (through our third-party payment processor, who stores such information and we do not have access to that information).
  - category: location
    text: 'We do not seek to specifically collect or identify your location but location data may be available via your IP address for the following purposes: for security and safety; and to prevent and detect fraud.'
  - category: behavioral
    text: Technical and Usage Data when you access any of our websites or platforms, details about your internet protocol (IP) address, login data, browser session and geolocation data, statistics on page views and sessions
  - category: health
    text: health information about you which is configured by your health provider each time you use the platform (for example, Medicare details, medications, allergies, family health history, and potential risk factors) but is not retained by the platform
  - category: biometric
    text: Sensitive information may include information relating to your racial or ethnic origin, political opinions, religion, trade union or other professional associations or memberships, philosophical beliefs, sexual orientation or practices, criminal records, health information, or biometric information.
  - category: communication
    text: subject to your prior consent, a recording of your health session each time you use the platform, such recording retained by the platform
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide software access and login
    text: to enable you to access and use our software, including to provide you with a login
  - purpose: Analytics, market research and business development
    text: for analytics, market research, and business development, including to operate and improve our business, associated applications, and associated social media platforms
  - purpose: Advertising and marketing
    text: for advertising and marketing, including to send you promotional information about our events and experiences
  - purpose: Legal obligations
    text: to comply with our legal obligations or if otherwise required or authorized by law.
  - purpose: AI transcription and summarization
    text: if you consent to use of Coviu Assist, to record your consultations and produce file notes for your health professional
  residency:
  - region: United States
    text: For clients located in the United States, we generally store personal information in the United States.
  rights:
  - right: Access
    text: You may request access to the personal information that we hold about you.
  - right: Correction
    text: If you believe that any information we hold about you is inaccurate, out of date, incomplete, irrelevant, or misleading, please contact us using the details below.
  - right: Object to direct marketing / unsubscribe
    text: To object to processing for direct marketing or to unsubscribe from our email database or opt out of communications (including marketing communications), please contact us using the details below
  - right: Complaint
    text: If you wish to make a complaint, please contact us using the details below and provide us with full details of the complaint.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: our hosting provider (as at the date of this policy - AWS), our product analysis adviser (as at the date of this policy - PostHog)
    url: null
  transfers:
  - mechanism: other
    text: Where we transfer personal information internationally, we will take appropriate steps so that any such transfer is subject to suitable safeguards as required by applicable law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Coviu
provenance_date: '2026-11-09'
provider_name: Coviu
provider_slug: coviu
slug: coviu-privacy-policy
source_date: '2026-11-09'
source_filename: coviu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.coviu.com/en-us/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Coviu\naid: coviu\nurl: https://www.coviu.com/en-us/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Identity Data including your name, age, profession, and photographic identification.\n- category: contact\n  text: Contact Data including your telephone number, address, and email.\n- category: financial\n  text: Financial Data including bank account and payment card details (through our third-party payment processor,\n    who stores such information and we do not have access to that information).\n- category: location\n  text:\
  \ 'We do not seek to specifically collect or identify your location but location data may be available via\n    your IP address for the following purposes: for security and safety; and to prevent and detect fraud.'\n- category: behavioral\n  text: Technical and Usage Data when you access any of our websites or platforms, details about your internet protocol\n    (IP) address, login data, browser session and geolocation data, statistics on page views and sessions\n- category: health\n  text: health information about you which is configured by your health provider each time you use the platform\n    (for example, Medicare details, medications, allergies, family health history, and potential risk factors) but\n    is not retained by the platform\n- category: biometric\n  text: Sensitive information may include information relating to your racial or ethnic origin, political opinions,\n    religion, trade union or other professional associations or memberships, philosophical beliefs, sexual\
  \ orientation\n    or practices, criminal records, health information, or biometric information.\n- category: communication\n  text: subject to your prior consent, a recording of your health session each time you use the platform, such recording\n    retained by the platform\npurposes:\n- purpose: Provide software access and login\n  text: to enable you to access and use our software, including to provide you with a login\n- purpose: Analytics, market research and business development\n  text: for analytics, market research, and business development, including to operate and improve our business,\n    associated applications, and associated social media platforms\n- purpose: Advertising and marketing\n  text: for advertising and marketing, including to send you promotional information about our events and experiences\n- purpose: Legal obligations\n  text: to comply with our legal obligations or if otherwise required or authorized by law.\n- purpose: AI transcription and summarization\n\
  \  text: if you consent to use of Coviu Assist, to record your consultations and produce file notes for your health\n    professional\nretention: []\nresidency:\n- region: United States\n  text: For clients located in the United States, we generally store personal information in the United States.\ntransfers:\n- mechanism: other\n  text: Where we transfer personal information internationally, we will take appropriate steps so that any such\n    transfer is subject to suitable safeguards as required by applicable law.\nsubprocessors:\n  url: null\n  text: our hosting provider (as at the date of this policy - AWS), our product analysis adviser (as at the date\n    of this policy - PostHog)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: You may request access to the personal information that we hold about you.\n- right: Correction\n  text: If you believe that any information we hold about you is inaccurate, out\
  \ of date, incomplete, irrelevant,\n    or misleading, please contact us using the details below.\n- right: Object to direct marketing / unsubscribe\n  text: To object to processing for direct marketing or to unsubscribe from our email database or opt out of communications\n    (including marketing communications), please contact us using the details below\n- right: Complaint\n  text: If you wish to make a complaint, please contact us using the details below and provide us with full details\n    of the complaint.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coviu/privacy/coviu-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- residency
- transfers
- subprocessors
- rights
summary_line: 20 quoted statements, read from Coviu's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Telehealth
- Australia
- Virtual Care
- Video
- WebRTC
- Appointments
- Remote Monitoring
- REST
---
