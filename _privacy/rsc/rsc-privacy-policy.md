---
api_specs:
- filename: rsc-filter-api-openapi.yml
  format: yaml
  label: RSC Filter API
  slug: rsc-filter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rsc/openapi/rsc-filter-api-openapi.yml
- filename: rsc-lookups-api-openapi.yml
  format: yaml
  label: RSC Lookups API
  slug: rsc-lookups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rsc/openapi/rsc-lookups-api-openapi.yml
- filename: rsc-records-api-openapi.yml
  format: yaml
  label: RSC Records API
  slug: rsc-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rsc/openapi/rsc-records-api-openapi.yml
- filename: rsc-tools-api-openapi.yml
  format: yaml
  label: RSC Tools API
  slug: rsc-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rsc/openapi/rsc-tools-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Information that you provide to us such as your name, address, date of birth, telephone number, email address, payment information
  - category: device
    text: Information about any device you have used to access our services (such as your browser or IP address).
  - category: behavioral
    text: Information from social media activity (such as likes, shares and tweets) when you interact with us on social media
  - category: biometric
    text: Images and videos taken with consent that we may use in printed material or on our websites
  deletion:
    route: Request deletion by contacting the RSC
    text: No personal data will be kept any longer than necessary in order to fulfil the purpose it was collected for, and if you ask us to, it will be deleted
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide products, activities and services
    text: We need to use your personal information to make our products, activities, and services available to you.
  - purpose: Marketing
    text: We use your personal data to provide you with information and news about our products, activities, and services by email, phone, post, and online advertising.
  - purpose: Safety and security
    text: We use personal information to help provide safe and secure environments for our business to be conducted in and for our staff to work in.
  - purpose: Analytics and profiling
    text: We use your personal information for statistical analysis and to help us understand more about our customers.
  residency:
  - region: UK
    text: the information you provide to us may be transferred to countries outside the UK.
  retention:
  - period: 60 days
    scope: CCTV recordings
    text: We store recordings for a period of 60 days, after which time they are automatically deleted.
  - period: up to six years
    scope: Downloaded CCTV recordings
    text: We may retain recordings that are downloaded for these purposes for a period of up to six years to take into account the statutory limitation periods
  - period: null
    scope: General personal information
    text: We maintain an Information Retention Schedule for all our processing activities.
  rights:
  - right: Access
    text: the right to access a copy of the personal information we hold about you
  - right: Correction
    text: the right to correction of inaccurate personal information we hold about you
  - right: Restriction
    text: the right to restrict our use of your personal information
  - right: Erasure
    text: the right to be forgotten
  - right: Portability
    text: the right of data portability
  - right: Object
    text: the right to object to our use of your personal information
  - right: Complain
    text: You also have the right to lodge a complaint with the Information Commissioner's Office.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We will never pass your personal details to anyone outside the RSC for them to use for their own marketing purposes unless you have previously provided us with your informed and specific consent
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: RSC
provenance_date: '2026-11-10'
provider_name: RSC
provider_slug: rsc
slug: rsc-privacy-policy
source_date: '2026-11-10'
source_filename: rsc-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.rsc.org/help-and-legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: RSC\naid: rsc\nurl: https://www.rsc.org/help-and-legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Information that you provide to us such as your name, address, date of birth, telephone number, email address,\n    payment information\n- category: device\n  text: Information about any device you have used to access our services (such as your browser or IP address).\n- category: behavioral\n  text: Information from social media activity (such as likes, shares and tweets) when you interact with us on social\n    media\n- category:\
  \ biometric\n  text: Images and videos taken with consent that we may use in printed material or on our websites\npurposes:\n- purpose: Provide products, activities and services\n  text: We need to use your personal information to make our products, activities, and services available to you.\n- purpose: Marketing\n  text: We use your personal data to provide you with information and news about our products, activities, and services\n    by email, phone, post, and online advertising.\n- purpose: Safety and security\n  text: We use personal information to help provide safe and secure environments for our business to be conducted\n    in and for our staff to work in.\n- purpose: Analytics and profiling\n  text: We use your personal information for statistical analysis and to help us understand more about our customers.\nretention:\n- scope: CCTV recordings\n  period: 60 days\n  text: We store recordings for a period of 60 days, after which time they are automatically deleted.\n- scope: Downloaded\
  \ CCTV recordings\n  period: up to six years\n  text: We may retain recordings that are downloaded for these purposes for a period of up to six years to take\n    into account the statutory limitation periods\n- scope: General personal information\n  period: null\n  text: We maintain an Information Retention Schedule for all our processing activities.\nresidency:\n- region: UK\n  text: the information you provide to us may be transferred to countries outside the UK.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion by contacting the RSC\n  text: No personal data will be kept any longer than necessary in order to fulfil the purpose it was collected\n    for, and if you ask us to, it will be deleted\nrights:\n- right: Access\n  text: the right to access a copy of the personal information we hold about you\n- right: Correction\n  text: the right to correction of inaccurate personal information\
  \ we hold about you\n- right: Restriction\n  text: the right to restrict our use of your personal information\n- right: Erasure\n  text: the right to be forgotten\n- right: Portability\n  text: the right of data portability\n- right: Object\n  text: the right to object to our use of your personal information\n- right: Complain\n  text: You also have the right to lodge a complaint with the Information Commissioner's Office.\nsale_or_sharing:\n  stance: conditional\n  text: We will never pass your personal details to anyone outside the RSC for them to use for their own marketing\n    purposes unless you have previously provided us with your informed and specific consent\n"
source_yaml_url: https://artifacts.apis.io/rsc/privacy/rsc-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from RSC's own page on 2026-11-10.
synthetic: false
tags:
- Chemistry
- Cheminformatics
- Chemical Data
- Science
---
