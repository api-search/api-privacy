---
api_specs:
- filename: loconav-alert-subscriptions-api-openapi.yml
  format: yaml
  label: LocoNav Alert Subscriptions API
  slug: loconav-alert-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-alert-subscriptions-api-openapi.yml
- filename: loconav-alerts-api-openapi.yml
  format: yaml
  label: LocoNav Alerts API
  slug: loconav-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-alerts-api-openapi.yml
- filename: loconav-alerts-subscriptions-api-openapi.yml
  format: yaml
  label: LocoNav Alerts Subscriptions API
  slug: loconav-alerts-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-alerts-subscriptions-api-openapi.yml
- filename: loconav-drivers-api-openapi.yml
  format: yaml
  label: LocoNav Drivers API
  slug: loconav-drivers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-drivers-api-openapi.yml
- filename: loconav-mobilization-api-openapi.yml
  format: yaml
  label: LocoNav Mobilization API
  slug: loconav-mobilization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-mobilization-api-openapi.yml
- filename: loconav-polygon-geofence-api-openapi.yml
  format: yaml
  label: LocoNav Polygon (Geofence) API
  slug: loconav-polygon-geofence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-polygon-geofence-api-openapi.yml
- filename: loconav-trips-api-openapi.yml
  format: yaml
  label: LocoNav Trips API
  slug: loconav-trips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-trips-api-openapi.yml
- filename: loconav-users-api-openapi.yml
  format: yaml
  label: LocoNav Users API
  slug: loconav-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-users-api-openapi.yml
- filename: loconav-vehicles-api-openapi.yml
  format: yaml
  label: LocoNav Vehicles API
  slug: loconav-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-vehicles-api-openapi.yml
- filename: loconav-vehicles-telematics-api-openapi.yml
  format: yaml
  label: LocoNav Vehicles / Telematics API
  slug: loconav-vehicles-telematics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-vehicles-telematics-api-openapi.yml
- filename: loconav-video-telematics-vt-live-stream-api-openapi.yml
  format: yaml
  label: LocoNav Video Telematics VT / Live Stream API
  slug: loconav-video-telematics-vt-live-stream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-video-telematics-vt-live-stream-api-openapi.yml
- filename: loconav-video-telematics-vt-videos-api-openapi.yml
  format: yaml
  label: LocoNav Video Telematics VT / Videos API
  slug: loconav-video-telematics-vt-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loconav/openapi/loconav-video-telematics-vt-videos-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, telephone number, email address, geo-location, address, payment information, certain unique identifiers
  - category: location
    text: geolocation, internet protocol (IP) address
  - category: device
    text: device usage and information, advertising identifiers, browser type, operating system
  - category: behavioral
    text: information about how you engage with us, information about how and when you use our services
  - category: other
    text: face recognition data, photos or videos you choose to take with or upload to the Application
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: validate use and provide services
    text: to validate your use of the Application and or Services
  - purpose: billing and transactions
    text: to complete transactions effectively and bill for Services
  - purpose: customer service
    text: to communicate and for resolving customer service issues
  - purpose: marketing
    text: to promote and market products and services that we consider may be of interest to you and/or may benefit you
  - purpose: legal compliance and fraud prevention
    text: to comply with laws, requests from government bodies or courts, prevent and detect frauds and crimes or to respond to litigation
  - purpose: product improvement and research
    text: to conduct internal assessments, auditing, data analysis, and research to improve our products and services
  retention:
  - period: null
    scope: face recognition data
    text: We automatically purge the face data as soon as the driver exits the system.
  rights:
  - right: access and copy
    text: right to request access and obtain a copy of your personal information
  - right: rectification or erasure
    text: the right to request rectification or erasure
  - right: restrict processing
    text: right to restrict the processing of your personal information
  - right: data portability
    text: right to data portability
  - right: automated decision-making
    text: rights relating to automated decision-making and profiling
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
  - mechanism: SCC
    text: usage of EU Standard Contractual Clauses or compliance with requirements under GDPR
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LocoNav
provenance_date: '2026-11-09'
provider_name: LocoNav
provider_slug: loconav
slug: loconav-privacy-policy
source_date: '2026-11-09'
source_filename: loconav-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://loconav.com/privacypolicy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LocoNav\naid: loconav\nurl: https://loconav.com/privacypolicy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your name, telephone number, email address, geo-location, address, payment information, certain unique identifiers\n- category: location\n  text: geolocation, internet protocol (IP) address\n- category: device\n  text: device usage and information, advertising identifiers, browser type, operating system\n- category: behavioral\n  text: information about how you engage with us, information about how and when you use our services\n\
  - category: other\n  text: face recognition data, photos or videos you choose to take with or upload to the Application\npurposes:\n- purpose: validate use and provide services\n  text: to validate your use of the Application and or Services\n- purpose: billing and transactions\n  text: to complete transactions effectively and bill for Services\n- purpose: customer service\n  text: to communicate and for resolving customer service issues\n- purpose: marketing\n  text: to promote and market products and services that we consider may be of interest to you and/or may benefit\n    you\n- purpose: legal compliance and fraud prevention\n  text: to comply with laws, requests from government bodies or courts, prevent and detect frauds and crimes or\n    to respond to litigation\n- purpose: product improvement and research\n  text: to conduct internal assessments, auditing, data analysis, and research to improve our products and services\nretention:\n- scope: face recognition data\n  period: null\n\
  \  text: We automatically purge the face data as soon as the driver exits the system.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: usage of EU Standard Contractual Clauses or compliance with requirements under GDPR\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access and copy\n  text: right to request access and obtain a copy of your personal information\n- right: rectification or erasure\n  text: the right to request rectification or erasure\n- right: restrict processing\n  text: right to restrict the processing of your personal information\n- right: data portability\n  text: right to data portability\n- right: automated decision-making\n  text: rights relating to automated decision-making and profiling\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/loconav/privacy/loconav-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- rights
summary_line: 18 quoted statements, read from LocoNav's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fleet Management
- Telematics
- GPS Tracking
- Vehicle Tracking
- Transportation
- Logistics
- IoT
- Video Telematics
- Webhook
---
