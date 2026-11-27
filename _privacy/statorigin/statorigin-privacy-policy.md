---
api_specs:
- filename: statorigin-indicators-api-openapi.yml
  format: yaml
  label: StatOrigin Indicators API
  slug: statorigin-indicators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statorigin/openapi/statorigin-indicators-api-openapi.yml
- filename: statorigin-industries-api-openapi.yml
  format: yaml
  label: StatOrigin Industries API
  slug: statorigin-industries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statorigin/openapi/statorigin-industries-api-openapi.yml
- filename: statorigin-regions-api-openapi.yml
  format: yaml
  label: StatOrigin Regions API
  slug: statorigin-regions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statorigin/openapi/statorigin-regions-api-openapi.yml
- filename: statorigin-search-api-openapi.yml
  format: yaml
  label: StatOrigin Search API
  slug: statorigin-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statorigin/openapi/statorigin-search-api-openapi.yml
- filename: statorigin-sources-api-openapi.yml
  format: yaml
  label: StatOrigin Sources API
  slug: statorigin-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statorigin/openapi/statorigin-sources-api-openapi.yml
- filename: statorigin-statistics-api-openapi.yml
  format: yaml
  label: StatOrigin Statistics API
  slug: statorigin-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/statorigin/openapi/statorigin-statistics-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: The corrections form stores the message you send and the page it refers to.
  - category: contact
    text: An email address is optional and is used only if you ask for a reply.
  - category: device
    text: The counter key is a hash of the network address and the UTC date.
  - category: behavioral
    text: Google Analytics 4 (measurement id G-EGJDZZJSJS , property “StatOrigin”). It sets a first-party _ga cookie.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Rate limiting
    text: Anonymous API calls and MCP calls are counted so one network cannot crowd out everyone else.
  - purpose: Correction checking
    text: Reports are kept so the correction itself can be checked later.
  - purpose: Measurement
    text: 'Pages may load two measurement tags: Cloudflare Web Analytics, when it is configured.'
  retention:
  - period: the next UTC day
    scope: Rate limit counter
    text: the counter expires the next UTC day.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: StatOrigin
provenance_date: '2026-11-10'
provider_name: StatOrigin
provider_slug: statorigin
slug: statorigin-privacy-policy
source_date: '2026-11-10'
source_filename: statorigin-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://statorigin.org/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: StatOrigin\naid: statorigin\nurl: https://statorigin.org/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: The corrections form stores the message you send and the page it refers to.\n- category: contact\n  text: An email address is optional and is used only if you ask for a reply.\n- category: device\n  text: The counter key is a hash of the network address and the UTC date.\n- category: behavioral\n  text: Google Analytics 4 (measurement id G-EGJDZZJSJS , property “StatOrigin”). It sets a first-party _ga cookie.\npurposes:\n- purpose:\
  \ Rate limiting\n  text: Anonymous API calls and MCP calls are counted so one network cannot crowd out everyone else.\n- purpose: Correction checking\n  text: Reports are kept so the correction itself can be checked later.\n- purpose: Measurement\n  text: 'Pages may load two measurement tags: Cloudflare Web Analytics, when it is configured.'\nretention:\n- scope: Rate limit counter\n  period: the next UTC day\n  text: the counter expires the next UTC day.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/statorigin/privacy/statorigin-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- sale_or_sharing
summary_line: 9 quoted statements, read from StatOrigin's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Statistics
- OpenAPI
- Free
---
