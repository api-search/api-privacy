---
api_specs:
- filename: steamgpt-net-bans-api-openapi.yml
  format: yaml
  label: steamgpt-net Bans API
  slug: steamgpt-net-bans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/steamgpt-net/openapi/steamgpt-net-bans-api-openapi.yml
- filename: steamgpt-net-batch-api-openapi.yml
  format: yaml
  label: steamgpt-net Batch API
  slug: steamgpt-net-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/steamgpt-net/openapi/steamgpt-net-batch-api-openapi.yml
- filename: steamgpt-net-compare-api-openapi.yml
  format: yaml
  label: steamgpt-net Compare API
  slug: steamgpt-net-compare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/steamgpt-net/openapi/steamgpt-net-compare-api-openapi.yml
- filename: steamgpt-net-converter-api-openapi.yml
  format: yaml
  label: steamgpt-net Converter API
  slug: steamgpt-net-converter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/steamgpt-net/openapi/steamgpt-net-converter-api-openapi.yml
- filename: steamgpt-net-faceit-api-openapi.yml
  format: yaml
  label: steamgpt-net Faceit API
  slug: steamgpt-net-faceit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/steamgpt-net/openapi/steamgpt-net-faceit-api-openapi.yml
- filename: steamgpt-net-friends-api-openapi.yml
  format: yaml
  label: steamgpt-net Friends API
  slug: steamgpt-net-friends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/steamgpt-net/openapi/steamgpt-net-friends-api-openapi.yml
- filename: steamgpt-net-identity-api-openapi.yml
  format: yaml
  label: steamgpt-net Identity API
  slug: steamgpt-net-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/steamgpt-net/openapi/steamgpt-net-identity-api-openapi.yml
- filename: steamgpt-net-profile-api-openapi.yml
  format: yaml
  label: steamgpt-net Profile API
  slug: steamgpt-net-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/steamgpt-net/openapi/steamgpt-net-profile-api-openapi.yml
- filename: steamgpt-net-ready-api-openapi.yml
  format: yaml
  label: steamgpt-net Ready API
  slug: steamgpt-net-ready-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/steamgpt-net/openapi/steamgpt-net-ready-api-openapi.yml
- filename: steamgpt-net-summary-api-openapi.yml
  format: yaml
  label: steamgpt-net Summary API
  slug: steamgpt-net-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/steamgpt-net/openapi/steamgpt-net-summary-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: device
    text: 'IP address : used for the fair-use limit of 120 requests per minute.'
  - category: identifying
    text: SteamGPT serves the public subset of Steam profile data as published by Steam (persona name, avatar, profile URL, visibility, creation date, online status, current game, SteamID forms)
  - category: other
    text: a snapshot of the public Steam friend graph
  deletion:
    route: set Steam profile to private, or email request
    text: 'If you are a Steam user and do not want your data served: set your Steam profile to private - SteamGPT then serves only the public subset Steam still exposes, after the next refresh (up to 5 days).'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: fair-use rate limiting
    text: used for the fair-use limit of 120 requests per minute
  retention:
  - period: about 70 seconds
    scope: IP address rate-limit counter
    text: expires about 70 seconds after the last request
  - period: 5 days
    scope: Steam profile snapshots
    text: Profile snapshots are cached for up to 5 days
  rights:
  - right: access, correction, erasure, objection
    text: Rights under the laws of your country (access, correction, erasure, objection) go to the same address.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: SteamGPT adds nothing to this data, does not profile players and does not sell data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: steamgpt-net
provenance_date: '2026-11-10'
provider_name: steamgpt-net
provider_slug: steamgpt-net
slug: steamgpt-net-privacy-policy
source_date: '2026-11-10'
source_filename: steamgpt-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://steamgpt.net/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: steamgpt-net\naid: steamgpt-net\nurl: https://steamgpt.net/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: 'IP address : used for the fair-use limit of 120 requests per minute.'\n- category: identifying\n  text: SteamGPT serves the public subset of Steam profile data as published by Steam (persona name, avatar, profile\n    URL, visibility, creation date, online status, current game, SteamID forms)\n- category: other\n  text: a snapshot of the public Steam friend graph\npurposes:\n- purpose: fair-use rate limiting\n  text: used for the\
  \ fair-use limit of 120 requests per minute\nretention:\n- scope: IP address rate-limit counter\n  period: about 70 seconds\n  text: expires about 70 seconds after the last request\n- scope: Steam profile snapshots\n  period: 5 days\n  text: Profile snapshots are cached for up to 5 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: set Steam profile to private, or email request\n  text: 'If you are a Steam user and do not want your data served: set your Steam profile to private - SteamGPT\n    then serves only the public subset Steam still exposes, after the next refresh (up to 5 days).'\nrights:\n- right: access, correction, erasure, objection\n  text: Rights under the laws of your country (access, correction, erasure, objection) go to the same address.\nsale_or_sharing:\n  stance: prohibited\n  text: SteamGPT adds nothing to this data, does not profile players and does not sell data.\n"
source_yaml_url: https://artifacts.apis.io/steamgpt-net/privacy/steamgpt-net-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 9 quoted statements, read from steamgpt-net's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Gaming
- Steam
---
