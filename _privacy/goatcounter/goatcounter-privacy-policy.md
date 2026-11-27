---
api_specs:
- filename: goatcounter-exports-api-openapi.yml
  format: yaml
  label: GoatCounter Exports API
  slug: goatcounter-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-exports-api-openapi.yml
- filename: goatcounter-pageviews-api-openapi.yml
  format: yaml
  label: GoatCounter Pageviews API
  slug: goatcounter-pageviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-pageviews-api-openapi.yml
- filename: goatcounter-paths-api-openapi.yml
  format: yaml
  label: GoatCounter Paths API
  slug: goatcounter-paths-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-paths-api-openapi.yml
- filename: goatcounter-sites-api-openapi.yml
  format: yaml
  label: GoatCounter Sites API
  slug: goatcounter-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-sites-api-openapi.yml
- filename: goatcounter-statistics-api-openapi.yml
  format: yaml
  label: GoatCounter Statistics API
  slug: goatcounter-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-statistics-api-openapi.yml
- filename: goatcounter-users-api-openapi.yml
  format: yaml
  label: GoatCounter Users API
  slug: goatcounter-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-users-api-openapi.yml
- filename: goatcounter-count-api-openapi.yml
  format: yaml
  label: GoatCounter Count API
  slug: goatcounter-count-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-count-api-openapi.yml
- filename: goatcounter-export-api-openapi.yml
  format: yaml
  label: GoatCounter Export API
  slug: goatcounter-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-export-api-openapi.yml
- filename: goatcounter-stats-api-openapi.yml
  format: yaml
  label: GoatCounter Stats API
  slug: goatcounter-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/goatcounter/openapi/goatcounter-stats-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: device
    text: Browsers, based on headers sent by the browser (e.g. Firefox 139 , Chrome 102 )
  - category: device
    text: Systems, based on headers sent by the browser (e.g. Windows 11 , macOS 15.2 ).
  - category: location
    text: Locations, based on IP address (e.g. Indonesia , Canada ).
  - category: other
    text: Languages (e.g. English , Klingon ).
  - category: device
    text: Screen widths (e.g. 768 , 1920 ).
  deletion:
    route: Settings → Delete Account
    text: You can remove all data from the site settings ( Settings → Delete Account ), which will permanently delete all data.
  dpa:
    available: null
    text: null
    url: null
  residency:
  - region: Finland and Germany
    text: Data is stored on servers at Hetzner Online GmbH in Finland and Germany.
  retention:
  - period: 8 hours
    scope: repeat-visit session mapping
    text: GoatCounter stores the site name + IP + User-Agent in memory for up to 8 hours.
  - period: 30 days
    scope: backups
    text: Some data may be retained in backups for up to 30 days.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No information is shared with third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: GoatCounter
provenance_date: '2026-11-09'
provider_name: GoatCounter
provider_slug: goatcounter
slug: goatcounter-privacy-policy
source_date: '2026-11-09'
source_filename: goatcounter-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.goatcounter.com/help/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: GoatCounter\naid: goatcounter\nurl: https://www.goatcounter.com/help/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: Browsers, based on headers sent by the browser (e.g. Firefox 139 , Chrome 102 )\n- category: device\n  text: Systems, based on headers sent by the browser (e.g. Windows 11 , macOS 15.2 ).\n- category: location\n  text: Locations, based on IP address (e.g. Indonesia , Canada ).\n- category: other\n  text: Languages (e.g. English , Klingon ).\n- category: device\n  text: Screen widths (e.g. 768 , 1920 ).\npurposes: []\n\
  retention:\n- scope: repeat-visit session mapping\n  period: 8 hours\n  text: GoatCounter stores the site name + IP + User-Agent in memory for up to 8 hours.\n- scope: backups\n  period: 30 days\n  text: Some data may be retained in backups for up to 30 days.\nresidency:\n- region: Finland and Germany\n  text: Data is stored on servers at Hetzner Online GmbH in Finland and Germany.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings → Delete Account\n  text: You can remove all data from the site settings ( Settings → Delete Account ), which will permanently delete\n    all data.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: No information is shared with third parties.\n"
source_yaml_url: https://artifacts.apis.io/goatcounter/privacy/goatcounter-privacy-policy.yml
stated_fields:
- data_categories
- retention
- residency
- deletion
- sale_or_sharing
summary_line: 10 quoted statements, read from GoatCounter's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Page Views
- Privacy
- Statistics
- Web Analytics
- Open Source
- Self-Hosted
- Event
- Data Export
- Developer Tools
---
