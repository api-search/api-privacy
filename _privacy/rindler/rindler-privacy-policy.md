---
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: we receive your email address, name, profile image (if set on your identity provider), and Clerk user ID
  - category: communication
    text: Messages you send to the chat app, files you upload, and the model's responses.
  - category: behavioral
    text: 'anonymous engagement events on rindler.ai, keyed by a random first-party visitor id (the rin_vid cookie): page views'
  - category: financial
    text: We receive and store only the payer email, Stripe payment, subscription, and event identifiers, the amount and currency
  - category: device
    text: Operational logs (request paths, timings, error fingerprints)
  - category: other
    text: we extract the resulting session cookies, encrypt them with AES-256-GCM, and store the encrypted state in our database
  deletion:
    route: email founders@rindler.ai
    text: Request deletion of your account and the chat history associated with it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: revisit past conversations
    text: so you can revisit past conversations and so the agent can carry context across turns
  - purpose: product understanding
    text: We collect these to understand what is useful.
  - purpose: identity verification
    text: to verify it belongs to you
  retention:
  - period: lifetime of your account
    scope: chat history
    text: Chat history was retained for the lifetime of your account
  - period: until the underlying third-party cookie expires or you revoke the session
    scope: encrypted browser sessions
    text: Encrypted browser sessions are retained until the underlying third-party cookie expires or you revoke the session.
  - period: up to 12 months
    scope: operational telemetry
    text: Operational telemetry (error fingerprints, aggregate counters, and anonymous engagement events) is retained for up to 12 months for reliability work
  rights:
  - right: access
    text: Request a copy of the data we hold about you.
  - right: correction
    text: Request correction of inaccurate data.
  - right: deletion
    text: Request deletion of your account and the chat history associated with it.
  - right: revoke browser session
    text: Revoke any authenticated browser session you set up.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or share consumer personal information, including phone numbers, with any third party or affiliate for marketing, advertising, or lead-generation purposes.
  subprocessors:
    text: The following service providers process data on Rindler's behalf.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Rindler
provenance_date: '2026-11-10'
provider_name: Rindler
provider_slug: rindler
slug: rindler-privacy-policy
source_date: '2026-11-10'
source_filename: rindler-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://rindler.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Rindler\naid: rindler\nurl: https://rindler.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: we receive your email address, name, profile image (if set on your identity provider), and Clerk user ID\n- category: communication\n  text: Messages you send to the chat app, files you upload, and the model's responses.\n- category: behavioral\n  text: 'anonymous engagement events on rindler.ai, keyed by a random first-party visitor id (the rin_vid cookie):\n    page views'\n- category: financial\n  text: We receive and store only the payer\
  \ email, Stripe payment, subscription, and event identifiers, the amount\n    and currency\n- category: device\n  text: Operational logs (request paths, timings, error fingerprints)\n- category: other\n  text: we extract the resulting session cookies, encrypt them with AES-256-GCM, and store the encrypted state in\n    our database\npurposes:\n- purpose: revisit past conversations\n  text: so you can revisit past conversations and so the agent can carry context across turns\n- purpose: product understanding\n  text: We collect these to understand what is useful.\n- purpose: identity verification\n  text: to verify it belongs to you\nretention:\n- scope: chat history\n  period: lifetime of your account\n  text: Chat history was retained for the lifetime of your account\n- scope: encrypted browser sessions\n  period: until the underlying third-party cookie expires or you revoke the session\n  text: Encrypted browser sessions are retained until the underlying third-party cookie expires or\
  \ you revoke the\n    session.\n- scope: operational telemetry\n  period: up to 12 months\n  text: Operational telemetry (error fingerprints, aggregate counters, and anonymous engagement events) is retained\n    for up to 12 months for reliability work\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: The following service providers process data on Rindler's behalf.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email founders@rindler.ai\n  text: Request deletion of your account and the chat history associated with it.\nrights:\n- right: access\n  text: Request a copy of the data we hold about you.\n- right: correction\n  text: Request correction of inaccurate data.\n- right: deletion\n  text: Request deletion of your account and the chat history associated with it.\n- right: revoke browser session\n  text: Revoke any authenticated browser session you set up.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or share consumer\
  \ personal information, including phone numbers, with any third party\n    or affiliate for marketing, advertising, or lead-generation purposes.\n"
source_yaml_url: https://artifacts.apis.io/rindler/privacy/rindler-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Rindler's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- AI Agents
- Browser Automation
- Structured Data
- Website to API
- Agent Tools
- Y Combinator
---
