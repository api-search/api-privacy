---
api_specs:
- filename: europe-pmc-openapi-generated.yml
  format: yaml
  label: Europe PMC API
  slug: europe-pmc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/europe-pmc/openapi/_ae-authored/europe-pmc-openapi-generated.yml
- filename: europe-pmc-europepmc-api-openapi.yml
  format: yaml
  label: Europe PMC Europepmc API
  slug: europe-pmc-europepmc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/europe-pmc/openapi/europe-pmc-europepmc-api-openapi.yml
claim_count: 6
description: ''
doc:
  data_categories:
  - category: behavioral
    text: collection of personal data via web logs and analytics
  - category: identifying
    text: collection of personal data when you set up a Europe PMC user account
  deletion:
    route: browser settings
    text: if you wish to restrict or block the cookies which are set by the Europe PMC website, or indeed any other website, you can do this through your browser settings
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: keep user signed in
    text: used to keep the user signed in to the website
  - purpose: improve the website
    text: used to help us improve the website
  retention:
  - period: one year
    scope: User-UUID cookie
    text: valid for one year
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
name: Europe PMC
provenance_date: '2026-11-09'
provider_name: Europe PMC
provider_slug: europe-pmc
slug: europe-pmc-privacy-policy
source_date: '2026-11-09'
source_filename: europe-pmc-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://europepmc.org/PrivacyNotice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Europe PMC\naid: europe-pmc\nurl: https://europepmc.org/PrivacyNotice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: collection of personal data via web logs and analytics\n- category: identifying\n  text: collection of personal data when you set up a Europe PMC user account\npurposes:\n- purpose: keep user signed in\n  text: used to keep the user signed in to the website\n- purpose: improve the website\n  text: used to help us improve the website\nretention:\n- scope: User-UUID cookie\n  period: one year\n  text: valid for one year\nresidency:\
  \ []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: browser settings\n  text: if you wish to restrict or block the cookies which are set by the Europe PMC website, or indeed any other\n    website, you can do this through your browser settings\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/europe-pmc/privacy/europe-pmc-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 6 quoted statements, read from Europe PMC's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
