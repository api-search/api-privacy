---
api_specs:
- filename: bugtape-ai-openapi-generated.yml
  format: yaml
  label: BugTape API
  slug: bugtape-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bugtape-ai/openapi/_ae-authored/bugtape-ai-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: behavioral
    text: 'Session events: DOM mutations, user interactions (clicks, inputs, navigation), console output, and network request metadata (URL, method, status, timing)'
  - category: identifying
    text: 'Account and team info: email, name, organization, roles, team memberships, API keys, notification preferences, and integration configs.'
  - category: contact
    text: the reporter's email if provided
  - category: device
    text: environment (browser, OS, viewport, page URL)
  - category: location
    text: your country (worked out by Cloudflare from your connection)
  deletion:
    route: POST /v1/auth/data-delete/request followed by POST /v1/auth/data-delete/confirm
    text: 'Erasure: POST /v1/auth/data-delete/request followed by POST /v1/auth/data-delete/confirm'
  dpa:
    available: true
    text: If your organisation needs a signed data processing agreement, email hi@bugtape.ai
    url: null
  purposes:
  - purpose: capture bug reports
    text: helps teams capture bug reports with browser context such as session events, console output, network failures, and user-supplied notes
  - purpose: AI-generated bug report artifacts
    text: 'Derived artifacts: an AI-generated title, severity estimate, reproduction steps, and suggested fix based on the captured events.'
  - purpose: product analytics
    text: we also store, for product analytics, your approximate location
  - purpose: reliability
    text: 'Telemetry: request IDs and timing for our own reliability.'
  residency:
  - region: Australia
    text: so report data and the BugTape database stay in Australia
  retention:
  - period: 7 days
    scope: Replay and timeline events (Free plan)
    text: 7 days on Free
  - period: 30 days
    scope: Replay and timeline events (Pro plan)
    text: 30 days on Pro
  - period: until the account is deleted
    scope: Account data
    text: We keep user, org, and team data until the account is deleted.
  - period: 12 months
    scope: Closed or inactive accounts
    text: otherwise after 12 months of inactivity
  - period: 90 days
    scope: Request traces and error logs
    text: Request traces and error logs are kept for up to 90 days
  - period: 400 days
    scope: Page-view records (website analytics)
    text: Page-view records are kept for 400 days.
  - period: 35 days
    scope: Raw page and click events (visit counter)
    text: Raw page and click events are deleted after 35 days
  - period: 400 days
    scope: Visit summaries (visit counter)
    text: visit summaries (the hashed daily key, country, device, campaign tags, pages, time and scroll) are deleted after 400 days
  rights:
  - right: access / export
    text: 'Access / export: POST /v1/auth/data-export (authenticated) returns a JSON blob of every record tied to your account'
  - right: erasure
    text: 'Erasure: POST /v1/auth/data-delete/request followed by POST /v1/auth/data-delete/confirm'
  - right: rectification
    text: 'Rectification: update your profile from the console, or email support.'
  - right: objection / restriction
    text: 'Objection / restriction: email hi@bugtape.ai .'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: We do not sell, rent, or share customer data with advertisers.
  subprocessors:
    text: The full list is on the Trust page
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BugTape
provenance_date: '2026-11-09'
provider_name: BugTape
provider_slug: bugtape-ai
slug: bugtape-ai-privacy-policy
source_date: '2026-11-09'
source_filename: bugtape-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bugtape.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BugTape\naid: bugtape-ai\nurl: https://bugtape.ai/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: 'Session events: DOM mutations, user interactions (clicks, inputs, navigation), console output, and network\n    request metadata (URL, method, status, timing)'\n- category: identifying\n  text: 'Account and team info: email, name, organization, roles, team memberships, API keys, notification preferences,\n    and integration configs.'\n- category: contact\n  text: the reporter's email if provided\n- category: device\n  text: environment\
  \ (browser, OS, viewport, page URL)\n- category: location\n  text: your country (worked out by Cloudflare from your connection)\npurposes:\n- purpose: capture bug reports\n  text: helps teams capture bug reports with browser context such as session events, console output, network failures,\n    and user-supplied notes\n- purpose: AI-generated bug report artifacts\n  text: 'Derived artifacts: an AI-generated title, severity estimate, reproduction steps, and suggested fix based\n    on the captured events.'\n- purpose: product analytics\n  text: we also store, for product analytics, your approximate location\n- purpose: reliability\n  text: 'Telemetry: request IDs and timing for our own reliability.'\nretention:\n- scope: Replay and timeline events (Free plan)\n  period: 7 days\n  text: 7 days on Free\n- scope: Replay and timeline events (Pro plan)\n  period: 30 days\n  text: 30 days on Pro\n- scope: Account data\n  period: until the account is deleted\n  text: We keep user, org, and team\
  \ data until the account is deleted.\n- scope: Closed or inactive accounts\n  period: 12 months\n  text: otherwise after 12 months of inactivity\n- scope: Request traces and error logs\n  period: 90 days\n  text: Request traces and error logs are kept for up to 90 days\n- scope: Page-view records (website analytics)\n  period: 400 days\n  text: Page-view records are kept for 400 days.\n- scope: Raw page and click events (visit counter)\n  period: 35 days\n  text: Raw page and click events are deleted after 35 days\n- scope: Visit summaries (visit counter)\n  period: 400 days\n  text: visit summaries (the hashed daily key, country, device, campaign tags, pages, time and scroll) are deleted\n    after 400 days\nresidency:\n- region: Australia\n  text: so report data and the BugTape database stay in Australia\ntransfers: []\nsubprocessors:\n  url: null\n  text: The full list is on the Trust page\ndpa:\n  available: true\n  url: null\n  text: If your organisation needs a signed data processing\
  \ agreement, email hi@bugtape.ai\ndeletion:\n  route: POST /v1/auth/data-delete/request followed by POST /v1/auth/data-delete/confirm\n  text: 'Erasure: POST /v1/auth/data-delete/request followed by POST /v1/auth/data-delete/confirm'\nrights:\n- right: access / export\n  text: 'Access / export: POST /v1/auth/data-export (authenticated) returns a JSON blob of every record tied to\n    your account'\n- right: erasure\n  text: 'Erasure: POST /v1/auth/data-delete/request followed by POST /v1/auth/data-delete/confirm'\n- right: rectification\n  text: 'Rectification: update your profile from the console, or email support.'\n- right: objection / restriction\n  text: 'Objection / restriction: email hi@bugtape.ai .'\nsale_or_sharing:\n  stance: unstated\n  text: We do not sell, rent, or share customer data with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/bugtape-ai/privacy/bugtape-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
summary_line: 25 quoted statements, read from BugTape's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Error Tracking
- AI Agents
- Developer Tools
- Software-as-a-Service
---
