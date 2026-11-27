---
api_specs:
- filename: blobpedia-org-analytics-api-openapi.yml
  format: yaml
  label: BLOBPEDIA Analytics API
  slug: blobpedia-org-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blobpedia-org/openapi/blobpedia-org-analytics-api-openapi.yml
- filename: blobpedia-org-cips-api-openapi.yml
  format: yaml
  label: BLOBPEDIA CIPs API
  slug: blobpedia-org-cips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blobpedia-org/openapi/blobpedia-org-cips-api-openapi.yml
- filename: blobpedia-org-discovery-api-openapi.yml
  format: yaml
  label: BLOBPEDIA Discovery API
  slug: blobpedia-org-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blobpedia-org/openapi/blobpedia-org-discovery-api-openapi.yml
- filename: blobpedia-org-discussions-api-openapi.yml
  format: yaml
  label: BLOBPEDIA Discussions API
  slug: blobpedia-org-discussions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blobpedia-org/openapi/blobpedia-org-discussions-api-openapi.yml
- filename: blobpedia-org-documentation-api-openapi.yml
  format: yaml
  label: BLOBPEDIA Documentation API
  slug: blobpedia-org-documentation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blobpedia-org/openapi/blobpedia-org-documentation-api-openapi.yml
- filename: blobpedia-org-github-api-openapi.yml
  format: yaml
  label: BLOBPEDIA GitHub API
  slug: blobpedia-org-github-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blobpedia-org/openapi/blobpedia-org-github-api-openapi.yml
- filename: blobpedia-org-meta-api-openapi.yml
  format: yaml
  label: BLOBPEDIA Meta API
  slug: blobpedia-org-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blobpedia-org/openapi/blobpedia-org-meta-api-openapi.yml
- filename: blobpedia-org-network-api-openapi.yml
  format: yaml
  label: BLOBPEDIA Network API
  slug: blobpedia-org-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blobpedia-org/openapi/blobpedia-org-network-api-openapi.yml
- filename: blobpedia-org-search-api-openapi.yml
  format: yaml
  label: BLOBPEDIA Search API
  slug: blobpedia-org-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blobpedia-org/openapi/blobpedia-org-search-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: contact
    text: your name, email, subject and message.
  - category: identifying
    text: your IP address (so we can act on abuse and rate-limit the form)
  - category: behavioral
    text: the terms you type into search, with the time, the number of results and nothing that identifies you
  deletion:
    route: contact form
    text: You can ask us to show or delete whatever we hold on you from the contact form.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Responding to contact form messages
    text: We email them to ourselves.
  - purpose: Abuse prevention and rate limiting
    text: so we can act on abuse and rate-limit the form
  - purpose: Site statistics
    text: Site statistics come from our own Plausible instance at stats.unitynodes.com, which sets no cookies
  - purpose: Error reporting
    text: errors are reported to our own tracker at errors.unitynodes.com
  retention:
  - period: 180 days
    scope: Search and MCP logs
    text: The search and MCP logs are deleted after 180 days, and only running totals are kept.
  rights:
  - right: Access and deletion
    text: You can ask us to show or delete whatever we hold on you from the contact form.
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
name: BLOBPEDIA
provenance_date: '2026-11-09'
provider_name: BLOBPEDIA
provider_slug: blobpedia-org
slug: blobpedia-org-privacy-policy
source_date: '2026-11-09'
source_filename: blobpedia-org-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://blobpedia.org/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BLOBPEDIA\naid: blobpedia-org\nurl: https://blobpedia.org/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: your name, email, subject and message.\n- category: identifying\n  text: your IP address (so we can act on abuse and rate-limit the form)\n- category: behavioral\n  text: the terms you type into search, with the time, the number of results and nothing that identifies you\npurposes:\n- purpose: Responding to contact form messages\n  text: We email them to ourselves.\n- purpose: Abuse prevention and rate limiting\n  text: so we can\
  \ act on abuse and rate-limit the form\n- purpose: Site statistics\n  text: Site statistics come from our own Plausible instance at stats.unitynodes.com, which sets no cookies\n- purpose: Error reporting\n  text: errors are reported to our own tracker at errors.unitynodes.com\nretention:\n- scope: Search and MCP logs\n  period: 180 days\n  text: The search and MCP logs are deleted after 180 days, and only running totals are kept.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact form\n  text: You can ask us to show or delete whatever we hold on you from the contact form.\nrights:\n- right: Access and deletion\n  text: You can ask us to show or delete whatever we hold on you from the contact form.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/blobpedia-org/privacy/blobpedia-org-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 10 quoted statements, read from BLOBPEDIA's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Celestia
- Knowledge Hub
- Documentation
- Community
- Open Source
---
