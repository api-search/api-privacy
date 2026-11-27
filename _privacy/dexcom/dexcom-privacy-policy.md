---
api_specs:
- filename: dexcom-alerts-api-openapi.yml
  format: yaml
  label: Dexcom Alerts API
  slug: dexcom-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexcom/openapi/dexcom-alerts-api-openapi.yml
- filename: dexcom-authentication-api-openapi.yml
  format: yaml
  label: Dexcom Authentication API
  slug: dexcom-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexcom/openapi/dexcom-authentication-api-openapi.yml
- filename: dexcom-calibrations-api-openapi.yml
  format: yaml
  label: Dexcom Calibrations API
  slug: dexcom-calibrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexcom/openapi/dexcom-calibrations-api-openapi.yml
- filename: dexcom-data-range-api-openapi.yml
  format: yaml
  label: Dexcom Data Range API
  slug: dexcom-data-range-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexcom/openapi/dexcom-data-range-api-openapi.yml
- filename: dexcom-devices-api-openapi.yml
  format: yaml
  label: Dexcom Devices API
  slug: dexcom-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexcom/openapi/dexcom-devices-api-openapi.yml
- filename: dexcom-estimated-glucose-values-api-openapi.yml
  format: yaml
  label: Dexcom Estimated Glucose Values API
  slug: dexcom-estimated-glucose-values-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexcom/openapi/dexcom-estimated-glucose-values-api-openapi.yml
- filename: dexcom-events-api-openapi.yml
  format: yaml
  label: Dexcom Events API
  slug: dexcom-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexcom/openapi/dexcom-events-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: This may include name, email, phone number, etc.
  - category: health
    text: This may include information related to your health condition and treatment, etc.
  - category: health
    text: glucose readings and related date, time, and device identifier related to that reading
  - category: device
    text: advertising IDs associated with your device
  - category: behavioral
    text: activity and online behavior while on our Products and Services
  - category: location
    text: location data
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service delivery and enrolment
    text: to enroll you in our programs and provide you with our Products and Services
  - purpose: marketing
    text: advertising and promotion, including to contact you regarding programs, Products and Services, and topics that may be of interest or useful to you
  role:
    text: the entity responsible for the collection and use of your Personal Data
    value: controller
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
name: Dexcom
provenance_date: '2026-11-09'
provider_name: Dexcom
provider_slug: dexcom
slug: dexcom-privacy-policy
source_date: '2026-11-09'
source_filename: dexcom-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.dexcom.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Dexcom\naid: dexcom\nurl: https://www.dexcom.com/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: the entity responsible for the collection and use of your Personal Data\ndata_categories:\n- category: identifying\n  text: This may include name, email, phone number, etc.\n- category: health\n  text: This may include information related to your health condition and treatment, etc.\n- category: health\n  text: glucose readings and related date, time, and device identifier related to that reading\n- category: device\n  text: advertising IDs associated with\
  \ your device\n- category: behavioral\n  text: activity and online behavior while on our Products and Services\n- category: location\n  text: location data\npurposes:\n- purpose: service delivery and enrolment\n  text: to enroll you in our programs and provide you with our Products and Services\n- purpose: marketing\n  text: advertising and promotion, including to contact you regarding programs, Products and Services, and topics\n    that may be of interest or useful to you\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dexcom/privacy/dexcom-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
summary_line: 9 quoted statements, read from Dexcom's own page on 2026-11-09.
synthetic: false
tags:
- Continuous Glucose Monitoring
- Diabetes
- Digital Health
- Glucose
- Healthcare
- Medical Devices
- Wearables
---
