---
api_specs:
- filename: photon-agent-discovery-api-openapi.yml
  format: yaml
  label: Photon Agent discovery API
  slug: photon-agent-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/photon/openapi/photon-agent-discovery-api-openapi.yml
- filename: photon-newsletter-api-openapi.yml
  format: yaml
  label: Photon Newsletter API
  slug: photon-newsletter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/photon/openapi/photon-newsletter-api-openapi.yml
- filename: photon-onboarding-api-openapi.yml
  format: yaml
  label: Photon Onboarding API
  slug: photon-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/photon/openapi/photon-onboarding-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: Your telephone number Your address Your email address
  - category: identifying
    text: Your name
  - category: professional
    text: National Provider Identifier (NPI) State medical licenses
  - category: identifying
    text: Drivers License, Passport, or other identification
  - category: financial
    text: We do not collect or store such financial information and we are not responsible for the collection or storage of such information by third parties.
  - category: device
    text: Your browser type and operating system
  - category: location
    text: Geolocation information
  - category: behavioral
    text: Pages you view and links you click on within the Services
  deletion:
    route: account settings or email support
    text: If you wish to access, update, correct or delete any Personal Information in our possession that you have previously submitted via the Services, you may log into your account and make updates.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: measure usage and analytics
    text: to measure usage of the Services, to analyze the effectiveness of our Services, to conduct research
  - purpose: marketing and advertising
    text: to market and advertise the Services, including through promotional e-mail messages
  - purpose: targeted advertising
    text: We may also use this information to offer you targeted advertising in order to personalize your experience
  - purpose: support and notices
    text: to provide support for the Services and respond to requests and inquiries
  residency:
  - region: United States
    text: the Services are directed towards users who reside in the United States
  retention:
  - period: null
    scope: personal information
    text: We strive to keep your information only as long as we need it for legitimate business purposes and as permitted by applicable legal requirements.
  - period: null
    scope: data after account closure
    text: If you close your account, we will retain certain data for analytical purposes and recordkeeping integrity, as well as to prevent fraud
  rights:
  - right: access, correction and deletion
    text: If you wish to access, update, correct or delete any Personal Information in our possession
  - right: opt out of marketing communications
    text: If you do not want us to send you marketing or promotional communications, you can opt-out by clicking the “unsubscribe” link
  - right: complaint
    text: If you believe your privacy rights have been violated, you may file a complaint with our Privacy Officer or with the Secretary of the U.S. Department of Health and Human Services.
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
  - mechanism: other
    text: By using the Services, you consent to the collection, storage, processing, and transfer of your information in and to the United States, or other countries and territories
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Photon
provenance_date: '2026-11-10'
provider_name: Photon
provider_slug: photon
slug: photon-privacy-policy
source_date: '2026-11-10'
source_filename: photon-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://photonhealth.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Photon\naid: photon\nurl: https://photonhealth.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Your telephone number Your address Your email address\n- category: identifying\n  text: Your name\n- category: professional\n  text: National Provider Identifier (NPI) State medical licenses\n- category: identifying\n  text: Drivers License, Passport, or other identification\n- category: financial\n  text: We do not collect or store such financial information and we are not responsible for the collection or storage\n    of such information\
  \ by third parties.\n- category: device\n  text: Your browser type and operating system\n- category: location\n  text: Geolocation information\n- category: behavioral\n  text: Pages you view and links you click on within the Services\npurposes:\n- purpose: measure usage and analytics\n  text: to measure usage of the Services, to analyze the effectiveness of our Services, to conduct research\n- purpose: marketing and advertising\n  text: to market and advertise the Services, including through promotional e-mail messages\n- purpose: targeted advertising\n  text: We may also use this information to offer you targeted advertising in order to personalize your experience\n- purpose: support and notices\n  text: to provide support for the Services and respond to requests and inquiries\nretention:\n- scope: personal information\n  period: null\n  text: We strive to keep your information only as long as we need it for legitimate business purposes and as permitted\n    by applicable legal requirements.\n\
  - scope: data after account closure\n  period: null\n  text: If you close your account, we will retain certain data for analytical purposes and recordkeeping integrity,\n    as well as to prevent fraud\nresidency:\n- region: United States\n  text: the Services are directed towards users who reside in the United States\ntransfers:\n- mechanism: other\n  text: By using the Services, you consent to the collection, storage, processing, and transfer of your information\n    in and to the United States, or other countries and territories\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account settings or email support\n  text: If you wish to access, update, correct or delete any Personal Information in our possession that you have\n    previously submitted via the Services, you may log into your account and make updates.\nrights:\n- right: access, correction and deletion\n  text: If you wish to access, update, correct or delete\
  \ any Personal Information in our possession\n- right: opt out of marketing communications\n  text: If you do not want us to send you marketing or promotional communications, you can opt-out by clicking the\n    “unsubscribe” link\n- right: complaint\n  text: If you believe your privacy rights have been violated, you may file a complaint with our Privacy Officer\n    or with the Secretary of the U.S. Department of Health and Human Services.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/photon/privacy/photon-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 20 quoted statements, read from Photon's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- United States
- e-Prescribing
- Pharmacy
- Prescription Routing
- GraphQL
- Clinical API
- Digital Health
- Benefit Check
- OAuth
- Authentication
---
