---
api_specs:
- filename: datamuse-words-api-openapi.yml
  format: yaml
  label: Datamuse Words API
  slug: datamuse-words-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datamuse/openapi/datamuse-words-api-openapi.yml
- filename: datamuse-pets-api-openapi.yml
  format: yaml
  label: Datamuse Pets API
  slug: datamuse-pets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datamuse/openapi/datamuse-pets-api-openapi.yml
claim_count: 3
description: ''
doc:
  data_categories:
  - category: other
    text: The Datamuse API servers keep a temporary log file of the queries made to the service.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  retention:
  - period: end of the day after the request was made
    scope: query log file
    text: This log file is discarded at the end of the day after the request was made.
  - period: null
    scope: usage data
    text: We save no long-term usage data other than a count of the number of requests broken out by the broad category of the request.
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
name: Datamuse
provenance_date: '2026-11-09'
provider_name: Datamuse
provider_slug: datamuse
slug: datamuse-privacy-policy
source_date: '2026-11-09'
source_filename: datamuse-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.datamuse.com/api/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Datamuse\naid: datamuse\nurl: https://www.datamuse.com/api/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: other\n  text: The Datamuse API servers keep a temporary log file of the queries made to the service.\npurposes: []\nretention:\n- scope: query log file\n  period: end of the day after the request was made\n  text: This log file is discarded at the end of the day after the request was made.\n- scope: usage data\n  period: null\n  text: We save no long-term usage data other than a count of the number of requests broken out by the broad category\n    of\
  \ the request.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/datamuse/privacy/datamuse-privacy-policy.yml
stated_fields:
- data_categories
- retention
summary_line: 3 quoted statements, read from Datamuse's own page on 2026-11-09.
synthetic: false
tags:
- Word Finding
- Lexical Search
- Natural-Language
- Vocabulary
- Synonyms
- Antonyms
- Rhymes
- Phonetics
- Semantic Search
- Reverse Dictionary
- Autocomplete
- Wordplay
- Creative Writing
- Vocabulary Apps
- Word Games
- Linguistics
- Open Source Projects
- Public APIs
---
