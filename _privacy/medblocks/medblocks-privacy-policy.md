---
api_specs:
- filename: medblocks-certificates-api-openapi.yml
  format: yaml
  label: Medblocks Certificates API
  slug: medblocks-certificates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-certificates-api-openapi.yml
- filename: medblocks-connections-api-openapi.yml
  format: yaml
  label: Medblocks Connections API
  slug: medblocks-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-connections-api-openapi.yml
- filename: medblocks-events-api-openapi.yml
  format: yaml
  label: Medblocks Events API
  slug: medblocks-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-events-api-openapi.yml
- filename: medblocks-feeds-api-openapi.yml
  format: yaml
  label: Medblocks Feeds API
  slug: medblocks-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-feeds-api-openapi.yml
- filename: medblocks-health-api-openapi.yml
  format: yaml
  label: Medblocks Health API
  slug: medblocks-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-health-api-openapi.yml
- filename: medblocks-launch-contexts-api-openapi.yml
  format: yaml
  label: Medblocks Launch Contexts API
  slug: medblocks-launch-contexts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-launch-contexts-api-openapi.yml
- filename: medblocks-patient-sessions-api-openapi.yml
  format: yaml
  label: Medblocks Patient Sessions API
  slug: medblocks-patient-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-patient-sessions-api-openapi.yml
- filename: medblocks-patients-api-openapi.yml
  format: yaml
  label: Medblocks Patients API
  slug: medblocks-patients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-patients-api-openapi.yml
- filename: medblocks-webhooks-api-openapi.yml
  format: yaml
  label: Medblocks Webhooks API
  slug: medblocks-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medblocks/openapi/medblocks-webhooks-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: you may provide your name, email address, age, username, password, and other registration details
  - category: financial
    text: credit card information for purchases
  - category: device
    text: The Application may automatically collect the type of device used, a unique device ID, your IP address, your operating system and browser type
  - category: health
    text: Heart rate, resting heart rate, heart rate variability, and oxygen saturation
  - category: health
    text: Medicare Parts A, B, and D claims data from the Centers for Medicare & Medicaid Services (CMS), which may include claims for hospital and inpatient services (Part A)
  - category: location
    text: This Application does not collect precise real-time location information about your device.
  deletion:
    route: Delete your data page, Delete Account option in the app, or privacy@medblocks.com
    text: 'You may request permanent deletion of your Medicare data at any time: On the Delete your data page'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate and improve the Application
    text: We may use this information to operate and improve the Application and to contact you periodically with important information, notices, or marketing promotions.
  - purpose: core health service functionality
    text: Health data is used solely to provide the core functionality of the service
  - purpose: provide Medicare data at your direction
    text: We use your Medicare data only to provide it, at your direction, to the organization that is providing services to you
  residency:
  - region: United States
    text: Processing may involve collecting, storing, using, or disclosing information in the United States, regardless of your country of residence.
  retention:
  - period: up to 24 months
    scope: automatically collected data
    text: Automatically collected data is retained for up to 24 months and then stored in aggregate form.
  - period: within 7 days
    scope: Medicare data
    text: your Medicare data is permanently deleted from our servers within 7 days, except for any limited information we are required to retain by law.
  - period: null
    scope: health data
    text: Health data is retained on Medblocks servers for as long as your account remains active and you maintain an active connection with Medblocks Platform.
  rights:
  - right: access copy of data
    text: You may request a copy of the data we hold about you, including your health data including Medicare data, by contacting privacy@medblocks.com .
  - right: opt out of data collection or marketing emails
    text: request to opt out of data collection or marketing emails by emailing privacy@medblocks.com
  - right: disconnect Medicare account
    text: You may disconnect your Medicare account from Medblocks at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: we do not sell or rent it, or transfer it to third parties for advertising or marketing purposes
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Medblocks
provenance_date: '2026-11-10'
provider_name: Medblocks
provider_slug: medblocks
slug: medblocks-privacy-policy
source_date: '2026-11-10'
source_filename: medblocks-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://medblocks.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Medblocks\naid: medblocks\nurl: https://medblocks.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: you may provide your name, email address, age, username, password, and other registration details\n- category: financial\n  text: credit card information for purchases\n- category: device\n  text: The Application may automatically collect the type of device used, a unique device ID, your IP address,\n    your operating system and browser type\n- category: health\n  text: Heart rate, resting heart rate, heart rate variability,\
  \ and oxygen saturation\n- category: health\n  text: Medicare Parts A, B, and D claims data from the Centers for Medicare & Medicaid Services (CMS), which may\n    include claims for hospital and inpatient services (Part A)\n- category: location\n  text: This Application does not collect precise real-time location information about your device.\npurposes:\n- purpose: operate and improve the Application\n  text: We may use this information to operate and improve the Application and to contact you periodically with\n    important information, notices, or marketing promotions.\n- purpose: core health service functionality\n  text: Health data is used solely to provide the core functionality of the service\n- purpose: provide Medicare data at your direction\n  text: We use your Medicare data only to provide it, at your direction, to the organization that is providing services\n    to you\nretention:\n- scope: automatically collected data\n  period: up to 24 months\n  text: Automatically collected\
  \ data is retained for up to 24 months and then stored in aggregate form.\n- scope: Medicare data\n  period: within 7 days\n  text: your Medicare data is permanently deleted from our servers within 7 days, except for any limited information\n    we are required to retain by law.\n- scope: health data\n  period: null\n  text: Health data is retained on Medblocks servers for as long as your account remains active and you maintain\n    an active connection with Medblocks Platform.\nresidency:\n- region: United States\n  text: Processing may involve collecting, storing, using, or disclosing information in the United States, regardless\n    of your country of residence.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your data page, Delete Account option in the app, or privacy@medblocks.com\n  text: 'You may request permanent deletion of your Medicare data at any time: On the Delete your data page'\nrights:\n\
  - right: access copy of data\n  text: You may request a copy of the data we hold about you, including your health data including Medicare data,\n    by contacting privacy@medblocks.com .\n- right: opt out of data collection or marketing emails\n  text: request to opt out of data collection or marketing emails by emailing privacy@medblocks.com\n- right: disconnect Medicare account\n  text: You may disconnect your Medicare account from Medblocks at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: we do not sell or rent it, or transfer it to third parties for advertising or marketing purposes\n"
source_yaml_url: https://artifacts.apis.io/medblocks/privacy/medblocks-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Medblocks's own page on 2026-11-10.
synthetic: false
tags:
- Health
- Healthcare
- FHIR
- openEHR
- Interoperability
- Electronic Health Records
- Patient Access
- Health Data
- SMART on FHIR
- Webhook
- MCP
- Company
---
