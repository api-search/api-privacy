---
api_specs:
- filename: astro-agent-dev-finance-api-openapi.yml
  format: yaml
  label: astro-agent-dev Finance API
  slug: astro-agent-dev-finance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astro-agent-dev/openapi/astro-agent-dev-finance-api-openapi.yml
- filename: astro-agent-dev-free-api-openapi.yml
  format: yaml
  label: astro-agent-dev Free API
  slug: astro-agent-dev-free-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astro-agent-dev/openapi/astro-agent-dev-free-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: location
    text: 'Requests contain birth or event data: a date and time, and usually geographic coordinates and a time zone.'
  - category: identifying
    text: The key is a salted SHA-256 hash of your IP address (not the IP itself).
  - category: financial
    text: A payment is a signed blockchain transaction.
  deletion:
    route: Email aidatatools@proton.me to have a free-call counter linked to your wallet address removed
    text: To have a free-call counter linked to your wallet address removed, or for any privacy question, write to aidatatools@proton.me .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Compute chart result
    text: This data is used only to compute the result of that request and is returned to you in the response.
  - purpose: Free-call allowance
    text: To give each caller its first free calls, we keep a counter per caller in a key-value store.
  - purpose: Rate limiting
    text: A per-minute request count, keyed by the same salted hash, is kept for 2 minutes.
  - purpose: Replay protection
    text: Machine Payments Protocol (MPP) payment references are kept for 7 days so that one payment cannot be used twice.
  residency:
  - region: United States
    text: The service runs on Vercel (hosting) and Upstash (key-value store), in the United States.
  retention:
  - period: null
    scope: Request bodies
    text: We do not store request bodies, and the service does not log them.
  - period: do not expire
    scope: Free-call counters
    text: These counters do not expire.
  - period: 40 days
    scope: Daily free-call totals
    text: We also keep daily totals of free calls, with no caller identity, for 40 days.
  - period: 2 minutes
    scope: Rate limiting counts
    text: A per-minute request count, keyed by the same salted hash, is kept for 2 minutes.
  - period: 7 days
    scope: MPP payment references
    text: Machine Payments Protocol (MPP) payment references are kept for 7 days so that one payment cannot be used twice.
  rights:
  - right: Access or deletion of birth data
    text: We keep no birth data, so there is no birth data to access or delete.
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
name: astro-agent-dev
provenance_date: '2026-11-09'
provider_name: astro-agent-dev
provider_slug: astro-agent-dev
slug: astro-agent-dev-privacy-policy
source_date: '2026-11-09'
source_filename: astro-agent-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://astro-agent.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: astro-agent-dev\naid: astro-agent-dev\nurl: https://astro-agent.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: location\n  text: 'Requests contain birth or event data: a date and time, and usually geographic coordinates and a time zone.'\n- category: identifying\n  text: The key is a salted SHA-256 hash of your IP address (not the IP itself).\n- category: financial\n  text: A payment is a signed blockchain transaction.\npurposes:\n- purpose: Compute chart result\n  text: This data is used only to compute the result of that request and is returned\
  \ to you in the response.\n- purpose: Free-call allowance\n  text: To give each caller its first free calls, we keep a counter per caller in a key-value store.\n- purpose: Rate limiting\n  text: A per-minute request count, keyed by the same salted hash, is kept for 2 minutes.\n- purpose: Replay protection\n  text: Machine Payments Protocol (MPP) payment references are kept for 7 days so that one payment cannot be used\n    twice.\nretention:\n- scope: Request bodies\n  period: null\n  text: We do not store request bodies, and the service does not log them.\n- scope: Free-call counters\n  period: do not expire\n  text: These counters do not expire.\n- scope: Daily free-call totals\n  period: 40 days\n  text: We also keep daily totals of free calls, with no caller identity, for 40 days.\n- scope: Rate limiting counts\n  period: 2 minutes\n  text: A per-minute request count, keyed by the same salted hash, is kept for 2 minutes.\n- scope: MPP payment references\n  period: 7 days\n  text: Machine\
  \ Payments Protocol (MPP) payment references are kept for 7 days so that one payment cannot be used\n    twice.\nresidency:\n- region: United States\n  text: The service runs on Vercel (hosting) and Upstash (key-value store), in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email aidatatools@proton.me to have a free-call counter linked to your wallet address removed\n  text: To have a free-call counter linked to your wallet address removed, or for any privacy question, write to\n    aidatatools@proton.me .\nrights:\n- right: Access or deletion of birth data\n  text: We keep no birth data, so there is no birth data to access or delete.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/astro-agent-dev/privacy/astro-agent-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 15 quoted statements, read from astro-agent-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AstroFinance
- Astrology
- Market Data
---
