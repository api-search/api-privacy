---
api_specs:
- filename: 0200project-com-blockchain-api-openapi.yml
  format: yaml
  label: 0200project Blockchain API
  slug: 0200project-com-blockchain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0200project-com/openapi/0200project-com-blockchain-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your IP address.
  - category: contact
    text: We ask for an email address only if you choose to join the XO2 wallet waitlist.
  - category: other
    text: The transaction hash you submit.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: rate limiting and free-tier metering
    text: We hold it transiently in memory to enforce the 60-requests-per-minute rate limit and to meter the free tier.
  - purpose: XO2 wallet updates
    text: We use these only to tell you about the XO2 wallet, and we don’t share them.
  retention:
  - period: null
    scope: IP address
    text: We hold it transiently in memory to enforce the 60-requests-per-minute rate limit
  - period: until XO2 launches
    scope: XO2 waitlist data
    text: We keep them until XO2 launches.
  - period: null
    scope: append-only event log
    text: 'it is not currently bounded by any retention period: entries are not deleted on a schedule.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No sale or sharing of data with anyone.
  subprocessors:
    text: These are the external systems that receive data from your visit, your request or your payment.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 0200project
provenance_date: '2026-11-09'
provider_name: 0200project
provider_slug: 0200project-com
slug: 0200project-com-privacy-policy
source_date: '2026-11-09'
source_filename: 0200project-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://0200project.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 0200project\naid: 0200project-com\nurl: https://0200project.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your IP address.\n- category: contact\n  text: We ask for an email address only if you choose to join the XO2 wallet waitlist.\n- category: other\n  text: The transaction hash you submit.\npurposes:\n- purpose: rate limiting and free-tier metering\n  text: We hold it transiently in memory to enforce the 60-requests-per-minute rate limit and to meter the free\n    tier.\n- purpose: XO2 wallet updates\n  text: We use these\
  \ only to tell you about the XO2 wallet, and we don’t share them.\nretention:\n- scope: IP address\n  period: null\n  text: We hold it transiently in memory to enforce the 60-requests-per-minute rate limit\n- scope: XO2 waitlist data\n  period: until XO2 launches\n  text: We keep them until XO2 launches.\n- scope: append-only event log\n  period: null\n  text: 'it is not currently bounded by any retention period: entries are not deleted on a schedule.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: These are the external systems that receive data from your visit, your request or your payment.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: No sale or sharing of data with anyone.\n"
source_yaml_url: https://artifacts.apis.io/0200project-com/privacy/0200project-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- sale_or_sharing
summary_line: 10 quoted statements, read from 0200project's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Transaction decoder
- Finance tools
---
