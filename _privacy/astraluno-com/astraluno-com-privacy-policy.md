---
api_specs:
- filename: astraluno-com-chart-api-openapi.yml
  format: yaml
  label: Astraluno Chart API
  slug: astraluno-com-chart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraluno-com/openapi/astraluno-com-chart-api-openapi.yml
- filename: astraluno-com-ingresses-api-openapi.yml
  format: yaml
  label: Astraluno Ingresses API
  slug: astraluno-com-ingresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraluno-com/openapi/astraluno-com-ingresses-api-openapi.yml
- filename: astraluno-com-lunations-api-openapi.yml
  format: yaml
  label: Astraluno Lunations API
  slug: astraluno-com-lunations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraluno-com/openapi/astraluno-com-lunations-api-openapi.yml
- filename: astraluno-com-openapi-json-api-openapi.yml
  format: yaml
  label: Astraluno Openapi.json API
  slug: astraluno-com-openapi-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraluno-com/openapi/astraluno-com-openapi-json-api-openapi.yml
- filename: astraluno-com-places-api-openapi.yml
  format: yaml
  label: Astraluno Places API
  slug: astraluno-com-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraluno-com/openapi/astraluno-com-places-api-openapi.yml
- filename: astraluno-com-readings-api-openapi.yml
  format: yaml
  label: Astraluno Readings API
  slug: astraluno-com-readings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraluno-com/openapi/astraluno-com-readings-api-openapi.yml
- filename: astraluno-com-retrogrades-api-openapi.yml
  format: yaml
  label: Astraluno Retrogrades API
  slug: astraluno-com-retrogrades-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraluno-com/openapi/astraluno-com-retrogrades-api-openapi.yml
- filename: astraluno-com-sky-api-openapi.yml
  format: yaml
  label: Astraluno Sky API
  slug: astraluno-com-sky-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraluno-com/openapi/astraluno-com-sky-api-openapi.yml
- filename: astraluno-com-sun-sign-api-openapi.yml
  format: yaml
  label: Astraluno Sun Sign API
  slug: astraluno-com-sun-sign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraluno-com/openapi/astraluno-com-sun-sign-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: Birth date, birth time, selected place and optional display name are processed in your browser.
  - category: location
    text: The server receives the city search query and language in order to search our GeoNames database.
  - category: device
    text: Your network address is handled transiently for connection and rate limiting, with a one-minute in-memory bucket.
  - category: behavioral
    text: We count supported actions by day, page path and small categories such as calculator type or birth-time precision.
  deletion:
    route: Forget my data control in the app
    text: “Forget my data” removes the guest chart and reveal flag immediately.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Calculate chart result
    text: the server processes the birth inputs transiently to calculate the result.
  - purpose: Place search
    text: The server receives the city search query and language in order to search our GeoNames database.
  - purpose: Connection and rate limiting
    text: Your network address is handled transiently for connection and rate limiting
  - purpose: Anonymous daily counts
    text: We count supported actions by day, page path and small categories such as calculator type or birth-time precision.
  retention:
  - period: 24-hour expiry
    scope: Guest charts in localStorage
    text: Guest charts, including the selected place, are stored in localStorage on this device with a 24-hour expiry.
  - period: one-minute
    scope: Network address
    text: with a one-minute in-memory bucket.
  - period: 400 days
    scope: Anonymous aggregates
    text: Aggregates are retained for 400 days; they cannot measure unique users or individual return visits.
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
name: Astraluno
provenance_date: '2026-11-09'
provider_name: Astraluno
provider_slug: astraluno-com
slug: astraluno-com-privacy-policy
source_date: '2026-11-09'
source_filename: astraluno-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://astraluno.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Astraluno\naid: astraluno-com\nurl: https://astraluno.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Birth date, birth time, selected place and optional display name are processed in your browser.\n- category: location\n  text: The server receives the city search query and language in order to search our GeoNames database.\n- category: device\n  text: Your network address is handled transiently for connection and rate limiting, with a one-minute in-memory\n    bucket.\n- category: behavioral\n  text: We count supported actions\
  \ by day, page path and small categories such as calculator type or birth-time\n    precision.\npurposes:\n- purpose: Calculate chart result\n  text: the server processes the birth inputs transiently to calculate the result.\n- purpose: Place search\n  text: The server receives the city search query and language in order to search our GeoNames database.\n- purpose: Connection and rate limiting\n  text: Your network address is handled transiently for connection and rate limiting\n- purpose: Anonymous daily counts\n  text: We count supported actions by day, page path and small categories such as calculator type or birth-time\n    precision.\nretention:\n- scope: Guest charts in localStorage\n  period: 24-hour expiry\n  text: Guest charts, including the selected place, are stored in localStorage on this device with a 24-hour expiry.\n- scope: Network address\n  period: one-minute\n  text: with a one-minute in-memory bucket.\n- scope: Anonymous aggregates\n  period: 400 days\n  text: Aggregates\
  \ are retained for 400 days; they cannot measure unique users or individual return visits.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Forget my data control in the app\n  text: “Forget my data” removes the guest chart and reveal flag immediately.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/astraluno-com/privacy/astraluno-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 12 quoted statements, read from Astraluno's own page on 2026-11-09.
synthetic: false
tags:
- Astrology
- BirthChart
- Horoscope
---
