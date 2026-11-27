---
api_specs:
- filename: agentdomainsearch-com-api-openapi.json
  format: json
  label: Agent Domain Search Api API
  slug: agent-domain-search-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentdomainsearch-com/openapi/_original/agentdomainsearch-com-api-openapi.json
claim_count: 7
description: ''
doc:
  data_categories:
  - category: identifying
    text: We store Ethereum addresses (derived from your wallet's public key) as identity.
  - category: contact
    text: Registrant contact info (name, email, address) is collected as required by ICANN and stored at our upstream registrar.
  - category: device
    text: We log HTTP requests (method, path, timestamp, IP) for operational purposes.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operational logging
    text: We log HTTP requests (method, path, timestamp, IP) for operational purposes.
  - purpose: ICANN compliance
    text: Registrant contact info (name, email, address) is collected as required by ICANN and stored at our upstream registrar.
  retention:
  - period: 30 days
    scope: HTTP request logs
    text: Logs are retained for 30 days and are not sold or shared.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share this data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agent Domain Search
provenance_date: '2026-11-09'
provider_name: Agent Domain Search
provider_slug: agentdomainsearch-com
slug: agentdomainsearch-com-privacy-policy
source_date: '2026-11-09'
source_filename: agentdomainsearch-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentdomainsearch.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agent Domain Search\naid: agentdomainsearch-com\nurl: https://agentdomainsearch.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We store Ethereum addresses (derived from your wallet's public key) as identity.\n- category: contact\n  text: Registrant contact info (name, email, address) is collected as required by ICANN and stored at our upstream\n    registrar.\n- category: device\n  text: We log HTTP requests (method, path, timestamp, IP) for operational purposes.\npurposes:\n- purpose: operational logging\n  text: We log HTTP\
  \ requests (method, path, timestamp, IP) for operational purposes.\n- purpose: ICANN compliance\n  text: Registrant contact info (name, email, address) is collected as required by ICANN and stored at our upstream\n    registrar.\nretention:\n- scope: HTTP request logs\n  period: 30 days\n  text: Logs are retained for 30 days and are not sold or shared.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share this data.\n"
source_yaml_url: https://artifacts.apis.io/agentdomainsearch-com/privacy/agentdomainsearch-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- sale_or_sharing
summary_line: 7 quoted statements, read from Agent Domain Search's own page on 2026-11-09.
synthetic: false
tags:
- Domain Registration
- DNS Management
---
