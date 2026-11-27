---
api_specs:
- filename: inferindex-dev-mcp.json
  format: json
  label: InferIndex API
  slug: inferindex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inferindex-dev/openapi/inferindex-dev-mcp.json
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: your email address, in clear text
  - category: behavioral
    text: 'For each API request we increment a daily counter made of:'
  - category: location
    text: your approximate country
  - category: device
    text: your browser, operating system and device type
  deletion:
    route: delete your account yourself from your account space
    text: You can delete your account yourself from your account space.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the service
    text: 'We use this data only to run the service: rate limiting, abuse prevention, capacity planning and debugging.'
  - purpose: no advertising or profiling
    text: We do not sell it, and we do not use it for advertising or to build user profiles.
  residency:
  - region: Western Europe
    text: the database (Cloudflare D1) runs in Western Europe
  - region: Eastern North America
    text: encrypted-at-rest database backups (Cloudflare R2) are stored in Eastern North America.
  retention:
  - period: 24 hours
    scope: unverified accounts
    text: An account whose address is never verified is deleted after 24 hours.
  - period: 7 days
    scope: Cloudflare technical logs
    text: Cloudflare technical logs are kept for 7 days, then deleted.
  - period: 90 days
    scope: watch list alerts
    text: Watch list alerts are deleted after 90 days.
  rights:
  - right: access, correct or delete
    text: You can ask to access, correct or delete data about you
  - right: GDPR and LGPD
    text: as provided by the GDPR, the LGPD and similar laws
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell it, and we do not use it for advertising or to build user profiles.
  subprocessors:
    text: Cloudflare hosts the service and processes the data above on our behalf
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: inferindex-dev
provenance_date: '2026-11-09'
provider_name: inferindex-dev
provider_slug: inferindex-dev
slug: inferindex-dev-privacy-policy
source_date: '2026-11-09'
source_filename: inferindex-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://inferindex.dev/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: inferindex-dev\naid: inferindex-dev\nurl: https://inferindex.dev/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: your email address, in clear text\n- category: behavioral\n  text: 'For each API request we increment a daily counter made of:'\n- category: location\n  text: your approximate country\n- category: device\n  text: your browser, operating system and device type\npurposes:\n- purpose: run the service\n  text: 'We use this data only to run the service: rate limiting, abuse prevention, capacity planning and debugging.'\n- purpose:\
  \ no advertising or profiling\n  text: We do not sell it, and we do not use it for advertising or to build user profiles.\nretention:\n- scope: unverified accounts\n  period: 24 hours\n  text: An account whose address is never verified is deleted after 24 hours.\n- scope: Cloudflare technical logs\n  period: 7 days\n  text: Cloudflare technical logs are kept for 7 days, then deleted.\n- scope: watch list alerts\n  period: 90 days\n  text: Watch list alerts are deleted after 90 days.\nresidency:\n- region: Western Europe\n  text: the database (Cloudflare D1) runs in Western Europe\n- region: Eastern North America\n  text: encrypted-at-rest database backups (Cloudflare R2) are stored in Eastern North America.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare hosts the service and processes the data above on our behalf\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete your account yourself from your account space\n  text: You can delete your account\
  \ yourself from your account space.\nrights:\n- right: access, correct or delete\n  text: You can ask to access, correct or delete data about you\n- right: GDPR and LGPD\n  text: as provided by the GDPR, the LGPD and similar laws\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell it, and we do not use it for advertising or to build user profiles.\n"
source_yaml_url: https://artifacts.apis.io/inferindex-dev/privacy/inferindex-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from inferindex-dev's own page on 2026-11-09.
synthetic: false
tags:
- LLM
- Pricing
- Index
- Data
---
