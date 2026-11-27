---
api_specs:
- filename: tuva-health-config-api-openapi.yml
  format: yaml
  label: Tuva Health Config API
  slug: tuva-health-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tuva-health/openapi/tuva-health-config-api-openapi.yml
- filename: tuva-health-data-sources-api-openapi.yml
  format: yaml
  label: Tuva Health Data Sources API
  slug: tuva-health-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tuva-health/openapi/tuva-health-data-sources-api-openapi.yml
- filename: tuva-health-health-check-api-openapi.yml
  format: yaml
  label: Tuva Health Check API
  slug: tuva-health-health-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tuva-health/openapi/tuva-health-health-check-api-openapi.yml
- filename: tuva-health-matches-api-openapi.yml
  format: yaml
  label: Tuva Health Matches API
  slug: tuva-health-matches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tuva-health/openapi/tuva-health-matches-api-openapi.yml
- filename: tuva-health-person-records-api-openapi.yml
  format: yaml
  label: Tuva Health Person Records API
  slug: tuva-health-person-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tuva-health/openapi/tuva-health-person-records-api-openapi.yml
- filename: tuva-health-persons-api-openapi.yml
  format: yaml
  label: Tuva Health Persons API
  slug: tuva-health-persons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tuva-health/openapi/tuva-health-persons-api-openapi.yml
- filename: tuva-health-potential-matches-api-openapi.yml
  format: yaml
  label: Tuva Health Potential Matches API
  slug: tuva-health-potential-matches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tuva-health/openapi/tuva-health-potential-matches-api-openapi.yml
- filename: tuva-health-users-api-openapi.yml
  format: yaml
  label: Tuva Health Users API
  slug: tuva-health-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tuva-health/openapi/tuva-health-users-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: contact
    text: When you contact Tuva, request a demo, or submit a website form, we may collect your name, work email, company, role, and the information you choose to include in your message.
  - category: device
    text: Our hosting and security providers may also process basic technical information such as IP address, browser type, and request logs.
  deletion:
    route: Email hello@tuvahealth.com
    text: You may ask to access, correct, or delete information you submitted by emailing hello@tuvahealth.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Respond to demo requests and questions
    text: Respond to questions and demo requests.
  - purpose: Operate and secure the website
    text: Operate, secure, troubleshoot, and improve the website.
  - purpose: Legal obligations
    text: Meet legal obligations and protect Tuva, its customers, and website visitors.
  retention:
  - period: null
    scope: Website inquiries
    text: We retain website inquiries for as long as reasonably necessary to respond, maintain business records, and meet legal obligations.
  rights:
  - right: Access, correction, deletion
    text: You may ask to access, correct, or delete information you submitted by emailing hello@tuvahealth.com .
  - right: Additional rights by location
    text: Applicable law may provide additional rights based on your location.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Tuva does not sell personal information submitted through this website.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Tuva Health
provenance_date: '2026-11-10'
provider_name: Tuva Health
provider_slug: tuva-health
slug: tuva-health-privacy-policy
source_date: '2026-11-10'
source_filename: tuva-health-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.tuvahealth.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Tuva Health\naid: tuva-health\nurl: https://www.tuvahealth.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: When you contact Tuva, request a demo, or submit a website form, we may collect your name, work email, company,\n    role, and the information you choose to include in your message.\n- category: device\n  text: Our hosting and security providers may also process basic technical information such as IP address, browser\n    type, and request logs.\npurposes:\n- purpose: Respond to demo requests and questions\n  text: Respond\
  \ to questions and demo requests.\n- purpose: Operate and secure the website\n  text: Operate, secure, troubleshoot, and improve the website.\n- purpose: Legal obligations\n  text: Meet legal obligations and protect Tuva, its customers, and website visitors.\nretention:\n- scope: Website inquiries\n  period: null\n  text: We retain website inquiries for as long as reasonably necessary to respond, maintain business records, and\n    meet legal obligations.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@tuvahealth.com\n  text: You may ask to access, correct, or delete information you submitted by emailing hello@tuvahealth.com .\nrights:\n- right: Access, correction, deletion\n  text: You may ask to access, correct, or delete information you submitted by emailing hello@tuvahealth.com .\n- right: Additional rights by location\n  text: Applicable law may provide additional rights based\
  \ on your location.\nsale_or_sharing:\n  stance: prohibited\n  text: Tuva does not sell personal information submitted through this website.\n"
source_yaml_url: https://artifacts.apis.io/tuva-health/privacy/tuva-health-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 10 quoted statements, read from Tuva Health's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- United States
- Health Data
- FHIR
- Interoperability
- Data Analytics
- Data Transformation
- Claims
- Open Source
- dbt
- EMPI
- Patient Matching
---
