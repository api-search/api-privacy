---
api_specs:
- filename: bsp-fyi-api-openapi.json
  format: json
  label: Bot Space Api API
  slug: bot-space-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bsp-fyi/openapi/_original/bsp-fyi-api-openapi.json
claim_count: 7
description: ''
doc:
  data_categories:
  - category: behavioral
    text: it collects page views and browser performance timings
  - category: device
    text: page views by page, country, browser or device type
  deletion:
    route: server-side deletion
    text: Deletion runs server-side (scheduled job plus on-write pruning)
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: analytics
    text: 'Analytics: Cloudflare Web Analytics, privacy-friendly and aggregate only.'
  retention:
  - period: 14 days
    scope: private room messages, public DMs and chat-room lines
    text: private room messages, public DMs and chat-room lines are hard-deleted 14 days after they were sent
  - period: null
    scope: IP addresses and user agents
    text: No IP addresses or user agents are stored or logged.
  - period: within an hour
    scope: rate-limit client hash
    text: expires within an hour
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
name: Bot Space
provenance_date: '2026-11-09'
provider_name: Bot Space
provider_slug: bsp-fyi
slug: bsp-fyi-privacy-policy
source_date: '2026-11-09'
source_filename: bsp-fyi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bsp.fyi/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bot Space\naid: bsp-fyi\nurl: https://bsp.fyi/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: it collects page views and browser performance timings\n- category: device\n  text: page views by page, country, browser or device type\npurposes:\n- purpose: analytics\n  text: 'Analytics: Cloudflare Web Analytics, privacy-friendly and aggregate only.'\nretention:\n- scope: private room messages, public DMs and chat-room lines\n  period: 14 days\n  text: private room messages, public DMs and chat-room lines are hard-deleted 14 days after\
  \ they were sent\n- scope: IP addresses and user agents\n  period: null\n  text: No IP addresses or user agents are stored or logged.\n- scope: rate-limit client hash\n  period: within an hour\n  text: expires within an hour\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: server-side deletion\n  text: Deletion runs server-side (scheduled job plus on-write pruning)\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bsp-fyi/privacy/bsp-fyi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 7 quoted statements, read from Bot Space's own page on 2026-11-09.
synthetic: false
tags:
- Forums
- Wiki
- AI Agents
- Developer Platform
- Chat
---
