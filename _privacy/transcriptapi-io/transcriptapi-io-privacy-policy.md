---
api_specs:
- filename: transcriptapi-io-auth-api-openapi.yml
  format: yaml
  label: transcriptapi-io Auth API
  slug: transcriptapi-io-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptapi-io/openapi/transcriptapi-io-auth-api-openapi.yml
- filename: transcriptapi-io-channels-api-openapi.yml
  format: yaml
  label: transcriptapi-io Channels API
  slug: transcriptapi-io-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptapi-io/openapi/transcriptapi-io-channels-api-openapi.yml
- filename: transcriptapi-io-health-api-openapi.yml
  format: yaml
  label: transcriptapi-io Health API
  slug: transcriptapi-io-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptapi-io/openapi/transcriptapi-io-health-api-openapi.yml
- filename: transcriptapi-io-playlists-api-openapi.yml
  format: yaml
  label: transcriptapi-io Playlists API
  slug: transcriptapi-io-playlists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptapi-io/openapi/transcriptapi-io-playlists-api-openapi.yml
- filename: transcriptapi-io-public-tools-api-openapi.yml
  format: yaml
  label: transcriptapi-io Public tools API
  slug: transcriptapi-io-public-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptapi-io/openapi/transcriptapi-io-public-tools-api-openapi.yml
- filename: transcriptapi-io-search-api-openapi.yml
  format: yaml
  label: transcriptapi-io Search API
  slug: transcriptapi-io-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptapi-io/openapi/transcriptapi-io-search-api-openapi.yml
- filename: transcriptapi-io-transcripts-api-openapi.yml
  format: yaml
  label: transcriptapi-io Transcripts API
  slug: transcriptapi-io-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptapi-io/openapi/transcriptapi-io-transcripts-api-openapi.yml
- filename: transcriptapi-io-webhooks-api-openapi.yml
  format: yaml
  label: transcriptapi-io Webhooks API
  slug: transcriptapi-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptapi-io/openapi/transcriptapi-io-webhooks-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address when you create an account
  - category: behavioral
    text: 'API request logs: endpoint, timestamp, credit cost, status, and what the request was about (video, channel or playlist ID, search query)'
  - category: device
    text: IP address for rate limiting and abuse prevention
  - category: financial
    text: Payment transaction ID when you purchase credits — card details are handled by our payment processor
  deletion:
    route: Contact hello@transcriptapi.io
    text: You have the right to access, correct, export, or delete your data at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate account and process API requests
    text: To operate your account and process API requests
  - purpose: Track and deduct credits
    text: To track and deduct credits
  - purpose: Prevent abuse
    text: To prevent abuse
  - purpose: Transactional emails
    text: To send transactional emails (receipts, password reset)
  - purpose: Legal obligations
    text: To comply with legal obligations
  residency:
  - region: Germany
    text: 'Hetzner (Nuremberg, Germany): API servers and the transcript cache'
  - region: United States
    text: 'Google Firebase (United States): sign-in, account data, credit balances, request logs'
  - region: United States
    text: 'OpenAI (United States): text you have translated or summarised, only when you use those endpoints'
  retention:
  - period: until you delete your account
    scope: Account data
    text: Account data — until you delete your account
  - period: 90 days
    scope: Request logs
    text: Request logs — 90 days
  - period: removed on request
    scope: Transcripts and translations of public videos
    text: Transcripts and translations of public videos — cached by video ID to serve repeat requests, not linked to your account, removed on request
  - period: 7 years
    scope: Payment records
    text: Payment records — 7 years (legal requirement)
  rights:
  - right: Access, correct, export, or delete data
    text: You have the right to access, correct, export, or delete your data at any time.
  - right: Withdraw from purchase (EU consumers)
    text: If you are an EU consumer, you have the right to withdraw from a purchase within 14 days without giving any reason
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: 'These services process it on our behalf:'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: transcriptapi-io
provenance_date: '2026-11-10'
provider_name: transcriptapi-io
provider_slug: transcriptapi-io
slug: transcriptapi-io-privacy-policy
source_date: '2026-11-10'
source_filename: transcriptapi-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://transcriptapi.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: transcriptapi-io\naid: transcriptapi-io\nurl: https://transcriptapi.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email address when you create an account\n- category: behavioral\n  text: 'API request logs: endpoint, timestamp, credit cost, status, and what the request was about (video, channel\n    or playlist ID, search query)'\n- category: device\n  text: IP address for rate limiting and abuse prevention\n- category: financial\n  text: Payment transaction ID when you purchase credits — card details are handled by our payment\
  \ processor\npurposes:\n- purpose: Operate account and process API requests\n  text: To operate your account and process API requests\n- purpose: Track and deduct credits\n  text: To track and deduct credits\n- purpose: Prevent abuse\n  text: To prevent abuse\n- purpose: Transactional emails\n  text: To send transactional emails (receipts, password reset)\n- purpose: Legal obligations\n  text: To comply with legal obligations\nretention:\n- scope: Account data\n  period: until you delete your account\n  text: Account data — until you delete your account\n- scope: Request logs\n  period: 90 days\n  text: Request logs — 90 days\n- scope: Transcripts and translations of public videos\n  period: removed on request\n  text: Transcripts and translations of public videos — cached by video ID to serve repeat requests, not linked\n    to your account, removed on request\n- scope: Payment records\n  period: 7 years\n  text: Payment records — 7 years (legal requirement)\nresidency:\n- region: Germany\n\
  \  text: 'Hetzner (Nuremberg, Germany): API servers and the transcript cache'\n- region: United States\n  text: 'Google Firebase (United States): sign-in, account data, credit balances, request logs'\n- region: United States\n  text: 'OpenAI (United States): text you have translated or summarised, only when you use those endpoints'\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'These services process it on our behalf:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact hello@transcriptapi.io\n  text: You have the right to access, correct, export, or delete your data at any time.\nrights:\n- right: Access, correct, export, or delete data\n  text: You have the right to access, correct, export, or delete your data at any time.\n- right: Withdraw from purchase (EU consumers)\n  text: If you are an EU consumer, you have the right to withdraw from a purchase within 14 days without giving\n    any reason\nsale_or_sharing:\n  stance: prohibited\n  text: We\
  \ do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/transcriptapi-io/privacy/transcriptapi-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from transcriptapi-io's own page on 2026-11-10.
synthetic: false
tags:
- Company
- YouTube
- Transcripts
- Data
---
