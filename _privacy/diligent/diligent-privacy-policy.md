---
api_specs:
- filename: diligent-cdd-api-openapi.yml
  format: yaml
  label: Diligent CDD API
  slug: diligent-cdd-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-cdd-api-openapi.yml
- filename: diligent-company-api-openapi.yml
  format: yaml
  label: Diligent Company API
  slug: diligent-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-company-api-openapi.yml
- filename: diligent-instant-screening-experimental-api-openapi.yml
  format: yaml
  label: Diligent Instant Screening (experimental) API
  slug: diligent-instant-screening-experimental-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-instant-screening-experimental-api-openapi.yml
- filename: diligent-monitorings-api-openapi.yml
  format: yaml
  label: Diligent Monitorings API
  slug: diligent-monitorings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-monitorings-api-openapi.yml
- filename: diligent-name-screening-api-openapi.yml
  format: yaml
  label: Diligent Name Screening API
  slug: diligent-name-screening-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-name-screening-api-openapi.yml
- filename: diligent-webhooks-api-openapi.yml
  format: yaml
  label: Diligent Webhooks API
  slug: diligent-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diligent/openapi/diligent-webhooks-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: names email addresses business names business addresses
  - category: device
    text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device you use to access the Services.
  - category: location
    text: Location Data. We collect location data such as information about your device's location, which can be either precise or imprecise.
  - category: behavioral
    text: information about your activity in the Services (such as the date/time stamps associated with your usage, pages and files viewed, searches, and other actions you take
  deletion:
    route: contact support@godiligent.ai
    text: Upon your request to terminate your account, we will deactivate or delete your account and information from our active databases.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide, improve, and administer Services
    text: We process your information to provide, improve, and administer our Services, communicate with you, for security and fraud prevention, and to comply with law.
  - purpose: account creation and authentication
    text: To facilitate account creation and authentication and otherwise manage user accounts.
  - purpose: internal analytics and reporting
    text: This information is primarily needed to maintain the security and operation of our Services, and for our internal analytics and reporting purposes.
  retention:
  - period: twelve (12) months
    scope: post-termination of user account
    text: No purpose in this notice will require us keeping your personal information for longer than twelve (12) months past the termination of the user's account.
  rights:
  - right: access
    text: the right (i) to request access and obtain a copy of your personal information
  - right: rectification or erasure
    text: (ii) to request rectification or erasure
  - right: restriction of processing
    text: (iii) to restrict the processing of your personal information
  - right: data portability
    text: (vi) if applicable, to data portability
  - right: object to automated decision-making
    text: (vii) not to be subject to automated decision-making
  - right: withdraw consent
    text: You can withdraw your consent at any time.
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
name: Diligent
provenance_date: '2026-11-09'
provider_name: Diligent
provider_slug: diligent
slug: diligent-privacy-policy
source_date: '2026-11-09'
source_filename: diligent-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.godiligent.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Diligent\naid: diligent\nurl: https://www.godiligent.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: names email addresses business names business addresses\n- category: device\n  text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device\n    you use to access the Services.\n- category: location\n  text: Location Data. We collect location data such as information about your device's location, which can be either\n    precise or imprecise.\n- category: behavioral\n\
  \  text: information about your activity in the Services (such as the date/time stamps associated with your usage,\n    pages and files viewed, searches, and other actions you take\npurposes:\n- purpose: provide, improve, and administer Services\n  text: We process your information to provide, improve, and administer our Services, communicate with you, for\n    security and fraud prevention, and to comply with law.\n- purpose: account creation and authentication\n  text: To facilitate account creation and authentication and otherwise manage user accounts.\n- purpose: internal analytics and reporting\n  text: This information is primarily needed to maintain the security and operation of our Services, and for our\n    internal analytics and reporting purposes.\nretention:\n- scope: post-termination of user account\n  period: twelve (12) months\n  text: No purpose in this notice will require us keeping your personal information for longer than twelve (12)\n    months past the termination\
  \ of the user's account.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact support@godiligent.ai\n  text: Upon your request to terminate your account, we will deactivate or delete your account and information from\n    our active databases.\nrights:\n- right: access\n  text: the right (i) to request access and obtain a copy of your personal information\n- right: rectification or erasure\n  text: (ii) to request rectification or erasure\n- right: restriction of processing\n  text: (iii) to restrict the processing of your personal information\n- right: data portability\n  text: (vi) if applicable, to data portability\n- right: object to automated decision-making\n  text: (vii) not to be subject to automated decision-making\n- right: withdraw consent\n  text: You can withdraw your consent at any time.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/diligent/privacy/diligent-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 15 quoted statements, read from Diligent's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compliance
- RegTech
- KYC
- AML
- Financial Crime
- Due Diligence
- Screening
- Sanctions
- Monitoring
- Artificial Intelligence
- Fintech
- Webhook
---
