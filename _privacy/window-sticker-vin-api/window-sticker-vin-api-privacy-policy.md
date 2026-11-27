---
api_specs:
- filename: window-sticker-vin-api-sticker-api-openapi.yml
  format: yaml
  label: Window Sticker VIN API Sticker API
  slug: window-sticker-vin-api-sticker-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/window-sticker-vin-api/openapi/window-sticker-vin-api-sticker-api-openapi.yml
- filename: window-sticker-vin-api-vin-api-openapi.yml
  format: yaml
  label: Window Sticker VIN API Vin API
  slug: window-sticker-vin-api-vin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/window-sticker-vin-api/openapi/window-sticker-vin-api-vin-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: behavioral
    text: It records page views and clicks against a random ID kept in a cookie and in local storage.
  - category: device
    text: Whatever string it sends is stored in the database by day and route
  deletion:
    route: Email contact@windowsticker.org
    text: Write to contact@windowsticker.org to have it deleted.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Send emailed sticker
    text: 'send one email: the sticker, or a note that it never came.'
  - purpose: Vehicle watch alerts
    text: Spec watch emails you when a used car with the factory options you picked is listed.
  - purpose: Usage counting and analytics
    text: 'Database tables keep daily tallies: lookups by make and result, which site sent each visitor, and the page each visit started on.'
  retention:
  - period: up to 14 days
    scope: Emailed sticker address
    text: we keep your address next to that one VIN for up to 14 days
  - period: 7 days
    scope: Unconfirmed watch
    text: An unconfirmed watch is deleted after 7 days
  rights:
  - right: Erasure of feedback and VIN data
    text: Write to contact@windowsticker.org to have it deleted.
  - right: Removal from occasional updates list
    text: To be removed, write to contact@windowsticker.org .
  - right: Stop watch
    text: Every email except the notice that a watch was stopped has a stop link, and stopping deletes the watch rather than pausing it.
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
name: Window Sticker VIN API
provenance_date: '2026-11-10'
provider_name: Window Sticker VIN API
provider_slug: window-sticker-vin-api
slug: window-sticker-vin-api-privacy-policy
source_date: '2026-11-10'
source_filename: window-sticker-vin-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://windowsticker.org/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Window Sticker VIN API\naid: window-sticker-vin-api\nurl: https://windowsticker.org/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: It records page views and clicks against a random ID kept in a cookie and in local storage.\n- category: device\n  text: Whatever string it sends is stored in the database by day and route\npurposes:\n- purpose: Send emailed sticker\n  text: 'send one email: the sticker, or a note that it never came.'\n- purpose: Vehicle watch alerts\n  text: Spec watch emails you when a used car with the factory options\
  \ you picked is listed.\n- purpose: Usage counting and analytics\n  text: 'Database tables keep daily tallies: lookups by make and result, which site sent each visitor, and the page\n    each visit started on.'\nretention:\n- scope: Emailed sticker address\n  period: up to 14 days\n  text: we keep your address next to that one VIN for up to 14 days\n- scope: Unconfirmed watch\n  period: 7 days\n  text: An unconfirmed watch is deleted after 7 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email contact@windowsticker.org\n  text: Write to contact@windowsticker.org to have it deleted.\nrights:\n- right: Erasure of feedback and VIN data\n  text: Write to contact@windowsticker.org to have it deleted.\n- right: Removal from occasional updates list\n  text: To be removed, write to contact@windowsticker.org .\n- right: Stop watch\n  text: Every email except the notice that a watch was stopped\
  \ has a stop link, and stopping deletes the watch rather\n    than pausing it.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/window-sticker-vin-api/privacy/window-sticker-vin-api-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 11 quoted statements, read from Window Sticker VIN API's own page on 2026-11-10.
synthetic: false
tags:
- Automotive
- Vehicle Data
- VIN Decoding
- Monroney
- Window sticker
- Government open data
- Auto Retail
- Dealer tooling
---
