---
api_specs:
- filename: outworx-openapi-generated.yml
  format: yaml
  label: Outworx API
  slug: outworx-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/outworx/openapi/_ae-authored/outworx-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and avatar if you sign in with GitHub or Google
  - category: contact
    text: Email address (required for sign-in via magic link)
  - category: financial
    text: Stripe customer ID if you subscribe to a paid plan (Stripe handles all card details; we never see them)
  - category: behavioral
    text: Page views (path, referrer, country, browser family, OS, device type)
  - category: communication
    text: Chat messages (both the visitor's questions and our AI's responses)
  - category: device
    text: Visitor hash — a one-way hash of IP + user agent, used to approximate “unique visitors.”
  deletion:
    route: Settings page for account holders; email info@outworx.io for other requests
    text: Account holders can delete their account directly from the Settings page.
  dpa:
    available: true
    text: we'll share our most current version plus a Data Processing Agreement where appropriate
    url: null
  purposes:
  - purpose: Provide the service
    text: Provide the features you signed up for
  - purpose: Billing and payments
    text: Bill you and process payments (via Stripe)
  - purpose: Abuse prevention
    text: Detect and prevent abuse
  - purpose: Transactional email
    text: Send transactional emails (magic link, billing, quota warnings, account alerts)
  residency:
  - region: United States
    text: Our infrastructure runs in US data centers.
  retention:
  - period: while your account is active, plus up to 30 days after deletion
    scope: Account data
    text: 'Account data: while your account is active, plus up to 30 days after deletion.'
  - period: 7 days on Free, 30 days on Pro, 360 days on Business
    scope: Chat sessions and messages
    text: 'Chat sessions and messages: retained per the project owner''s plan — 7 days on Free, 30 days on Pro, 360 days on Business — then auto-archived daily by a scheduled job.'
  - period: up to 12 months
    scope: Page view analytics
    text: 'Page view analytics: retained for up to 12 months.'
  rights:
  - right: Access
    text: Access the data we hold about you
  - right: Correct
    text: Correct inaccurate data
  - right: Delete
    text: Delete your data (right to be forgotten)
  - right: Export
    text: Export your data in a portable format
  - right: Object
    text: Object to certain processing
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your data.
  subprocessors:
    text: 'To run the service we rely on a small set of trusted third parties:'
    url: null
  transfers:
  - mechanism: SCC
    text: We use standard contractual clauses and provider-specific safeguards where required by law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Outworx
provenance_date: '2026-11-10'
provider_name: Outworx
provider_slug: outworx
slug: outworx-privacy-policy
source_date: '2026-11-10'
source_filename: outworx-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://docs.outworx.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Outworx\naid: outworx\nurl: https://docs.outworx.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name and avatar if you sign in with GitHub or Google\n- category: contact\n  text: Email address (required for sign-in via magic link)\n- category: financial\n  text: Stripe customer ID if you subscribe to a paid plan (Stripe handles all card details; we never see them)\n- category: behavioral\n  text: Page views (path, referrer, country, browser family, OS, device type)\n- category: communication\n  text: Chat messages (both the\
  \ visitor's questions and our AI's responses)\n- category: device\n  text: Visitor hash — a one-way hash of IP + user agent, used to approximate “unique visitors.”\npurposes:\n- purpose: Provide the service\n  text: Provide the features you signed up for\n- purpose: Billing and payments\n  text: Bill you and process payments (via Stripe)\n- purpose: Abuse prevention\n  text: Detect and prevent abuse\n- purpose: Transactional email\n  text: Send transactional emails (magic link, billing, quota warnings, account alerts)\nretention:\n- scope: Account data\n  period: while your account is active, plus up to 30 days after deletion\n  text: 'Account data: while your account is active, plus up to 30 days after deletion.'\n- scope: Chat sessions and messages\n  period: 7 days on Free, 30 days on Pro, 360 days on Business\n  text: 'Chat sessions and messages: retained per the project owner''s plan — 7 days on Free, 30 days on Pro, 360\n    days on Business — then auto-archived daily by a scheduled\
  \ job.'\n- scope: Page view analytics\n  period: up to 12 months\n  text: 'Page view analytics: retained for up to 12 months.'\nresidency:\n- region: United States\n  text: Our infrastructure runs in US data centers.\ntransfers:\n- mechanism: SCC\n  text: We use standard contractual clauses and provider-specific safeguards where required by law.\nsubprocessors:\n  url: null\n  text: 'To run the service we rely on a small set of trusted third parties:'\ndpa:\n  available: true\n  url: null\n  text: we'll share our most current version plus a Data Processing Agreement where appropriate\ndeletion:\n  route: Settings page for account holders; email info@outworx.io for other requests\n  text: Account holders can delete their account directly from the Settings page.\nrights:\n- right: Access\n  text: Access the data we hold about you\n- right: Correct\n  text: Correct inaccurate data\n- right: Delete\n  text: Delete your data (right to be forgotten)\n- right: Export\n  text: Export your data\
  \ in a portable format\n- right: Object\n  text: Object to certain processing\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your data.\n"
source_yaml_url: https://artifacts.apis.io/outworx/privacy/outworx-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Outworx's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Outsourcing
- B2B SaaS
- Consulting
- Technology
---
