---
api_specs:
- filename: genlogs-alerts-api-openapi.yml
  format: yaml
  label: GenLogs Alerts API
  slug: genlogs-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genlogs/openapi/genlogs-alerts-api-openapi.yml
- filename: genlogs-auth-api-openapi.yml
  format: yaml
  label: GenLogs Auth API
  slug: genlogs-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genlogs/openapi/genlogs-auth-api-openapi.yml
- filename: genlogs-carrier-api-openapi.yml
  format: yaml
  label: GenLogs Carrier API
  slug: genlogs-carrier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genlogs/openapi/genlogs-carrier-api-openapi.yml
- filename: genlogs-carrier-vetting-api-openapi.yml
  format: yaml
  label: GenLogs Carrier Vetting API
  slug: genlogs-carrier-vetting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genlogs/openapi/genlogs-carrier-vetting-api-openapi.yml
- filename: genlogs-compliance-rules-api-openapi.yml
  format: yaml
  label: GenLogs Compliance Rules API
  slug: genlogs-compliance-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genlogs/openapi/genlogs-compliance-rules-api-openapi.yml
- filename: genlogs-facilities-api-openapi.yml
  format: yaml
  label: GenLogs Facilities API
  slug: genlogs-facilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genlogs/openapi/genlogs-facilities-api-openapi.yml
- filename: genlogs-mismatch-alerts-api-openapi.yml
  format: yaml
  label: GenLogs Mismatch alerts API
  slug: genlogs-mismatch-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genlogs/openapi/genlogs-mismatch-alerts-api-openapi.yml
- filename: genlogs-onboarded-carriers-api-openapi.yml
  format: yaml
  label: GenLogs Onboarded Carriers API
  slug: genlogs-onboarded-carriers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genlogs/openapi/genlogs-onboarded-carriers-api-openapi.yml
- filename: genlogs-shipper-api-openapi.yml
  format: yaml
  label: GenLogs Shipper API
  slug: genlogs-shipper-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genlogs/openapi/genlogs-shipper-api-openapi.yml
- filename: genlogs-webhook-alerts-api-openapi.yml
  format: yaml
  label: GenLogs Webhook Alerts API
  slug: genlogs-webhook-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/genlogs/openapi/genlogs-webhook-alerts-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: Business contact information, such as full name, business address, email address and phone number
  - category: identifying
    text: Account credentials, such as username and password
  - category: financial
    text: Financial information, including information used to pay for access to the Service, such as credit card, bank account and wire transfer information, and insurance policy information
  - category: location
    text: Precise geolocation, if you enable location sharing with us through your device
  - category: device
    text: a user’s browser, operating system and device information, IP address and approximate geolocation
  - category: other
    text: Audio, electronic, visual, thermal or similar information, such as audio or video recordings and images captured by our sensors and cameras.
  deletion:
    route: null
    text: If we learn we have collected personal information directly from a child under 16 years of age, we will delete that data as quickly as possible.
  dpa:
    available: true
    text: Data Processing Addendum
    url: null
  purposes:
  - purpose: Provide the Service
    text: Provide the Service, including maintain the Service, enable customers and users to access and use the Service
  - purpose: Market the Service
    text: Market the Service, for example, we process and share limited categories of personal information
  - purpose: Improve the Service
    text: Improve the Service, for example, we process and share limited categories of personal information for our internal research and development purposes
  - purpose: Meet legal and compliance requirements
    text: Meet legal and compliance requirements, including to perform audits, monitoring and reporting
  residency:
  - region: United States
    text: We operate from the United States and the personal information we collect or receive is stored and processed in the United States
  retention:
  - period: null
    scope: Personal information generally
    text: We retain personal information for as long as we deem to be necessary or advisable for our business purposes described above (such as providing the Service).
  - period: life of the Service
    scope: ALPR information for commercial motor vehicles
    text: that information is generally retained for the life of the Service rather than on a fixed schedule
  rights:
  - right: Opt out of marketing communications
    text: You may request that we no longer send marketing communications to you. To opt out please send an email to support@genlogs.io .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: You consent to the transfer of personal information to the United States or any other country in which we, our affiliates or vendors maintain facilities.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: GenLogs
provenance_date: '2026-11-09'
provider_name: GenLogs
provider_slug: genlogs
slug: genlogs-privacy-policy
source_date: '2026-11-09'
source_filename: genlogs-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.genlogs.io/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: GenLogs\naid: genlogs\nurl: https://www.genlogs.io/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Business contact information, such as full name, business address, email address and phone number\n- category: identifying\n  text: Account credentials, such as username and password\n- category: financial\n  text: Financial information, including information used to pay for access to the Service, such as credit card,\n    bank account and wire transfer information, and insurance policy information\n- category: location\n  text:\
  \ Precise geolocation, if you enable location sharing with us through your device\n- category: device\n  text: a user’s browser, operating system and device information, IP address and approximate geolocation\n- category: other\n  text: Audio, electronic, visual, thermal or similar information, such as audio or video recordings and images\n    captured by our sensors and cameras.\npurposes:\n- purpose: Provide the Service\n  text: Provide the Service, including maintain the Service, enable customers and users to access and use the Service\n- purpose: Market the Service\n  text: Market the Service, for example, we process and share limited categories of personal information\n- purpose: Improve the Service\n  text: Improve the Service, for example, we process and share limited categories of personal information for our\n    internal research and development purposes\n- purpose: Meet legal and compliance requirements\n  text: Meet legal and compliance requirements, including to perform audits,\
  \ monitoring and reporting\nretention:\n- scope: Personal information generally\n  period: null\n  text: We retain personal information for as long as we deem to be necessary or advisable for our business purposes\n    described above (such as providing the Service).\n- scope: ALPR information for commercial motor vehicles\n  period: life of the Service\n  text: that information is generally retained for the life of the Service rather than on a fixed schedule\nresidency:\n- region: United States\n  text: We operate from the United States and the personal information we collect or receive is stored and processed\n    in the United States\ntransfers:\n- mechanism: other\n  text: You consent to the transfer of personal information to the United States or any other country in which we,\n    our affiliates or vendors maintain facilities.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Data Processing Addendum\ndeletion:\n  route: null\n  text: If we\
  \ learn we have collected personal information directly from a child under 16 years of age, we will\n    delete that data as quickly as possible.\nrights:\n- right: Opt out of marketing communications\n  text: You may request that we no longer send marketing communications to you. To opt out please send an email\n    to support@genlogs.io .\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/genlogs/privacy/genlogs-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from GenLogs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Freight
- Trucking
- Supply Chain
- Carrier Intelligence
- Fleet Management
- Transportation
- Insurance
- Fraud Prevention
- Webhook
- Geospatial
---
