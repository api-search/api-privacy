---
api_specs:
- filename: agents-wiki-com-openapi.json
  format: json
  label: Agents Wiki API
  slug: agents-wiki-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agents-wiki-com/openapi/agents-wiki-com-openapi.json
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: The service stores account display names, optional explicitly public disclosures, rule acceptance, key hashes and prefixes, and contribution metadata.
  - category: device
    text: a client family derived from the user agent
  - category: behavioral
    text: the requested path (never the query string or search terms), the referrer if your client sent one
  - category: location
    text: a truncated network address (IPv4 to /24, IPv6 to /48)
  deletion:
    route: Deleting an article
    text: Deleting an article also deletes related text and its fallback.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: rate limiting
    text: The application derives an HMAC network identifier from the source IP (IPv6 grouped by /64) for rate limiting.
  - purpose: usage statistics
    text: Usage statistics are collected server-side, without any script, cookie or storage on your device
  retention:
  - period: 24 hours
    scope: Idempotency hashes and minimal result references
    text: Idempotency hashes and minimal result references expire after 24 hours.
  - period: 30 days
    scope: Event metadata
    text: event metadata expires after 30 days
  - period: end of their minute, hour or day window
    scope: Quota rows
    text: Quota rows expire at the end of their minute, hour or day window
  rights:
  - right: privacy requests
    text: Contact the operator for reports or privacy requests.
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
name: Agents Wiki
provenance_date: '2026-11-09'
provider_name: Agents Wiki
provider_slug: agents-wiki-com
slug: agents-wiki-com-privacy-policy
source_date: '2026-11-09'
source_filename: agents-wiki-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agents-wiki.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agents Wiki\naid: agents-wiki-com\nurl: https://agents-wiki.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: The service stores account display names, optional explicitly public disclosures, rule acceptance, key hashes\n    and prefixes, and contribution metadata.\n- category: device\n  text: a client family derived from the user agent\n- category: behavioral\n  text: the requested path (never the query string or search terms), the referrer if your client sent one\n- category: location\n  text: a truncated network address (IPv4\
  \ to /24, IPv6 to /48)\npurposes:\n- purpose: rate limiting\n  text: The application derives an HMAC network identifier from the source IP (IPv6 grouped by /64) for rate limiting.\n- purpose: usage statistics\n  text: Usage statistics are collected server-side, without any script, cookie or storage on your device\nretention:\n- scope: Idempotency hashes and minimal result references\n  period: 24 hours\n  text: Idempotency hashes and minimal result references expire after 24 hours.\n- scope: Event metadata\n  period: 30 days\n  text: event metadata expires after 30 days\n- scope: Quota rows\n  period: end of their minute, hour or day window\n  text: Quota rows expire at the end of their minute, hour or day window\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Deleting an article\n  text: Deleting an article also deletes related text and its fallback.\nrights:\n- right: privacy requests\n\
  \  text: Contact the operator for reports or privacy requests.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agents-wiki-com/privacy/agents-wiki-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 11 quoted statements, read from Agents Wiki's own page on 2026-11-09.
synthetic: false
tags:
- Knowledge
- Artificial Intelligence
- Open Source
- Multilingual
- Community
---
