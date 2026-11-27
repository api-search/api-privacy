---
api_specs:
- filename: infoplaza-geo-api-openapi.yml
  format: yaml
  label: Infoplaza Geo API
  slug: infoplaza-geo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infoplaza/openapi/infoplaza-geo-api-openapi.yml
- filename: infoplaza-marine-api-openapi.yml
  format: yaml
  label: Infoplaza Marine API
  slug: infoplaza-marine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infoplaza/openapi/infoplaza-marine-api-openapi.yml
- filename: infoplaza-observations-api-openapi.yml
  format: yaml
  label: Infoplaza Observations API
  slug: infoplaza-observations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infoplaza/openapi/infoplaza-observations-api-openapi.yml
- filename: infoplaza-port-api-openapi.yml
  format: yaml
  label: Infoplaza Port API
  slug: infoplaza-port-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infoplaza/openapi/infoplaza-port-api-openapi.yml
- filename: infoplaza-storms-api-openapi.yml
  format: yaml
  label: Infoplaza Storms API
  slug: infoplaza-storms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infoplaza/openapi/infoplaza-storms-api-openapi.yml
- filename: infoplaza-traffic-api-openapi.yml
  format: yaml
  label: Infoplaza Traffic API
  slug: infoplaza-traffic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infoplaza/openapi/infoplaza-traffic-api-openapi.yml
- filename: infoplaza-transit-api-openapi.yml
  format: yaml
  label: Infoplaza Transit API
  slug: infoplaza-transit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infoplaza/openapi/infoplaza-transit-api-openapi.yml
- filename: infoplaza-weather-api-openapi.yml
  format: yaml
  label: Infoplaza Weather API
  slug: infoplaza-weather-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infoplaza/openapi/infoplaza-weather-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: location
    text: Favourite location (location / GPS location), stop, line number or road number.
  - category: contact
    text: Email address for a newsletter or weather reports / warnings (Weerplaza only) after you have registered for service
  - category: identifying
    text: we request that you provide your name and email address.
  deletion:
    route: Unsubscribe link in newsletters; cookie removal
    text: At the bottom of every email newsletter that is sent, you will find a link to unsubscribe immediately.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Personalised service and content
    text: Saving your favourite weather forecast location
  - purpose: Improve sites and apps
    text: What information is viewed frequently and what is not. This information allows us to further improve the sites and apps.
  - purpose: Advertising
    text: Infoplaza cover its costs by displaying advertisements.
  - purpose: Traffic insight
    text: The information received can be further analysed so that we can provide customers with insight into traffic flows, such as in municipalities and / or provinces.
  rights:
  - right: access
    text: allow access to your personal data
  - right: rectification or erasure
    text: have it supplemented, corrected or deleted
  - right: objection
    text: object to the processing of your personal data
  - right: restriction
    text: limit your personal data
  - right: portability
    text: to transfer your personal data to a third party
  - right: complaint
    text: You have the right to submit a complaint to the Dutch Data Protection Authority at any time.
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
name: Infoplaza
provenance_date: '2026-11-09'
provider_name: Infoplaza
provider_slug: infoplaza
slug: infoplaza-privacy-policy
source_date: '2026-11-09'
source_filename: infoplaza-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.infoplaza.com/en/disclaimer-and-privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Infoplaza\naid: infoplaza\nurl: https://www.infoplaza.com/en/disclaimer-and-privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: location\n  text: Favourite location (location / GPS location), stop, line number or road number.\n- category: contact\n  text: Email address for a newsletter or weather reports / warnings (Weerplaza only) after you have registered\n    for service\n- category: identifying\n  text: we request that you provide your name and email address.\npurposes:\n- purpose: Personalised service and content\n  text: Saving your favourite weather\
  \ forecast location\n- purpose: Improve sites and apps\n  text: What information is viewed frequently and what is not. This information allows us to further improve the\n    sites and apps.\n- purpose: Advertising\n  text: Infoplaza cover its costs by displaying advertisements.\n- purpose: Traffic insight\n  text: The information received can be further analysed so that we can provide customers with insight into traffic\n    flows, such as in municipalities and / or provinces.\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Unsubscribe link in newsletters; cookie removal\n  text: At the bottom of every email newsletter that is sent, you will find a link to unsubscribe immediately.\nrights:\n- right: access\n  text: allow access to your personal data\n- right: rectification or erasure\n  text: have it supplemented, corrected or deleted\n- right: objection\n  text: object to the\
  \ processing of your personal data\n- right: restriction\n  text: limit your personal data\n- right: portability\n  text: to transfer your personal data to a third party\n- right: complaint\n  text: You have the right to submit a complaint to the Dutch Data Protection Authority at any time.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/infoplaza/privacy/infoplaza-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- deletion
- rights
summary_line: 14 quoted statements, read from Infoplaza's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Weather
- Mobility
- Forecasting
- Event Planning
- Data Analytics
- Weather Data
- Marine
- Meteorology
- Geospatial
---
