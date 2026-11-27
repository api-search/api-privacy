---
api_specs:
- filename: go1-enrollments-api-openapi.yml
  format: yaml
  label: Go1 Enrollments API
  slug: go1-enrollments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/go1/openapi/go1-enrollments-api-openapi.yml
- filename: go1-learning-objects-api-openapi.yml
  format: yaml
  label: Go1 Learning objects API
  slug: go1-learning-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/go1/openapi/go1-learning-objects-api-openapi.yml
- filename: go1-portals-api-openapi.yml
  format: yaml
  label: Go1 Portals API
  slug: go1-portals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/go1/openapi/go1-portals-api-openapi.yml
- filename: go1-webhooks-api-openapi.yml
  format: yaml
  label: Go1 Webhooks API
  slug: go1-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/go1/openapi/go1-webhooks-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers such as a real name, alias, postal address, unique personal identifier, online identifier, Internet Protocol address, email address, account name
  - category: behavioral
    text: Internet or other electronic network activity information, including, but not limited to, browsing history, search history
  - category: location
    text: Geolocation data including, but not limited to, general location information such as country or region
  - category: professional
    text: Professional or employment-related information including, but not limited to, job title, employer name, employment status
  - category: other
    text: Education information. including, but not limited to, course or programs enrolled, course registration dates and start/completion dates, certificates earned, assessment results/scores
  - category: other
    text: Inferences drawn from any of the information identified in this subdivision to create a profile about a consumer
  deletion:
    route: Data protection request portal at dataprotection.go1.com
    text: by submitting a request through our data protection request portal at dataprotection.go1.com
  dpa:
    available: true
    text: as set out in our Data Processing Addendum
    url: null
  purposes:
  - purpose: Providing products and services
    text: providing our products and services, communicating with you, administering programs
  - purpose: Marketing and promotion
    text: marketing and promotional purposes (which may include targeted advertising)
  - purpose: Analytics and personalization
    text: analytics and personalization, security and fraud prevention, legal obligations, core business functions
  residency:
  - region: United States and Australia
    text: We store and process your personal information on our servers located within the United States and Australia by default
  rights:
  - right: Access
    text: request access to, correction of, or deletion of your personal information
  - right: Opt out of targeted advertising, sale and profiling
    text: opt-out from certain types of processing (e.g., targeted advertising, the sale of personal data, and profiling
  - right: Appeal denied requests
    text: If we deny your request, you may appeal by emailing
  - right: Complaint to regulator
    text: If you would like to lodge a complaint against us, you may contact your local privacy regulator.
  role:
    text: Go1 acts as an independent controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Go1 does not sell your personal information or share personal information for cross-context behavioral advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: we are doing this based on our Internal Data Transfer Agreements
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Go1
provenance_date: '2026-11-09'
provider_name: Go1
provider_slug: go1
slug: go1-privacy-policy
source_date: '2026-11-09'
source_filename: go1-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.go1.com/terms/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Go1\naid: go1\nurl: https://www.go1.com/terms/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Go1 acts as an independent controller.\ndata_categories:\n- category: identifying\n  text: Identifiers such as a real name, alias, postal address, unique personal identifier, online identifier, Internet\n    Protocol address, email address, account name\n- category: behavioral\n  text: Internet or other electronic network activity information, including, but not limited to, browsing history,\n    search history\n- category: location\n  text: Geolocation data including, but not limited to,\
  \ general location information such as country or region\n- category: professional\n  text: Professional or employment-related information including, but not limited to, job title, employer name,\n    employment status\n- category: other\n  text: Education information. including, but not limited to, course or programs enrolled, course registration dates\n    and start/completion dates, certificates earned, assessment results/scores\n- category: other\n  text: Inferences drawn from any of the information identified in this subdivision to create a profile about a\n    consumer\npurposes:\n- purpose: Providing products and services\n  text: providing our products and services, communicating with you, administering programs\n- purpose: Marketing and promotion\n  text: marketing and promotional purposes (which may include targeted advertising)\n- purpose: Analytics and personalization\n  text: analytics and personalization, security and fraud prevention, legal obligations, core business functions\n\
  retention: []\nresidency:\n- region: United States and Australia\n  text: We store and process your personal information on our servers located within the United States and Australia\n    by default\ntransfers:\n- mechanism: other\n  text: we are doing this based on our Internal Data Transfer Agreements\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: as set out in our Data Processing Addendum\ndeletion:\n  route: Data protection request portal at dataprotection.go1.com\n  text: by submitting a request through our data protection request portal at dataprotection.go1.com\nrights:\n- right: Access\n  text: request access to, correction of, or deletion of your personal information\n- right: Opt out of targeted advertising, sale and profiling\n  text: opt-out from certain types of processing (e.g., targeted advertising, the sale of personal data, and profiling\n- right: Appeal denied requests\n  text: If we deny your request, you may appeal by emailing\n\
  - right: Complaint to regulator\n  text: If you would like to lodge a complaint against us, you may contact your local privacy regulator.\nsale_or_sharing:\n  stance: prohibited\n  text: Go1 does not sell your personal information or share personal information for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/go1/privacy/go1-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Go1's own page on 2026-11-09.
synthetic: false
tags:
- Company
- EdTech
- Learning
- E-Learning
- Corporate Training
- Content
- LMS
- Education
- Webhook
---
