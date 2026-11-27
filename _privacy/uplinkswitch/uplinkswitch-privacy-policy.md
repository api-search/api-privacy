---
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account details from checkout: the email address and the amount paid, as our payment processor reports them.'
  - category: device
    text: 'Where your first visit came from: the referring site, the link''s campaign tags and the page you landed on, saved with your account when your first sign-in creates it'
  - category: communication
    text: 'One usage record per request: request id, model, host, mode, token counts by class, the source of those counts, and the charge.'
  - category: financial
    text: 'The ledger of balance changes: top-ups, charges, refunds and disputes.'
  deletion:
    route: Email hello@uplinkswitch.com
    text: Write to hello@uplinkswitch.com to have one removed from the vault.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Route and bill API requests
    text: 'SHA-256 fingerprints, never the text: of each request and response, so a signed receipt can show what was billed'
  - purpose: Safety classification
    text: OpenAI's moderation API classifies each new message and media prompt for safety
  - purpose: Website measurement
    text: Google Analytics (Google LLC) measures visits to the public pages of uplinkswitch.ai.
  retention:
  - period: null
    scope: Account keys
    text: Keys and provider keys are kept while the account is open.
  - period: null
    scope: Usage records and ledger
    text: Usage records and ledger entries are kept as accounting records after it closes.
  - period: 7 days
    scope: Request bodies with replay
    text: unless you turn on replay for a key, which keeps that key's request bodies for 7 days
  - period: 7 days
    scope: Large system prompt fingerprints
    text: of large system prompts, kept 7 days, to find prompts many accounts send and cache them for everyone
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Every model on the Models page, Claude, GPT and Gemini as well as the open-weight models, is served by third-party model hosting providers under contract with UplinkSwitch.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: UplinkSwitch
provenance_date: '2026-11-10'
provider_name: UplinkSwitch
provider_slug: uplinkswitch
slug: uplinkswitch-privacy-policy
source_date: '2026-11-10'
source_filename: uplinkswitch-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://uplinkswitch.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: UplinkSwitch\naid: uplinkswitch\nurl: https://uplinkswitch.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account details from checkout: the email address and the amount paid, as our payment processor reports\n    them.'\n- category: device\n  text: 'Where your first visit came from: the referring site, the link''s campaign tags and the page you landed\n    on, saved with your account when your first sign-in creates it'\n- category: communication\n  text: 'One usage record per request: request id, model, host, mode, token counts\
  \ by class, the source of those\n    counts, and the charge.'\n- category: financial\n  text: 'The ledger of balance changes: top-ups, charges, refunds and disputes.'\npurposes:\n- purpose: Route and bill API requests\n  text: 'SHA-256 fingerprints, never the text: of each request and response, so a signed receipt can show what was\n    billed'\n- purpose: Safety classification\n  text: OpenAI's moderation API classifies each new message and media prompt for safety\n- purpose: Website measurement\n  text: Google Analytics (Google LLC) measures visits to the public pages of uplinkswitch.ai.\nretention:\n- scope: Account keys\n  period: null\n  text: Keys and provider keys are kept while the account is open.\n- scope: Usage records and ledger\n  period: null\n  text: Usage records and ledger entries are kept as accounting records after it closes.\n- scope: Request bodies with replay\n  period: 7 days\n  text: unless you turn on replay for a key, which keeps that key's request bodies for\
  \ 7 days\n- scope: Large system prompt fingerprints\n  period: 7 days\n  text: of large system prompts, kept 7 days, to find prompts many accounts send and cache them for everyone\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Every model on the Models page, Claude, GPT and Gemini as well as the open-weight models, is served by third-party\n    model hosting providers under contract with UplinkSwitch.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@uplinkswitch.com\n  text: Write to hello@uplinkswitch.com to have one removed from the vault.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/uplinkswitch/privacy/uplinkswitch-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
summary_line: 13 quoted statements, read from UplinkSwitch's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- Gateways
- Reseller
- Platform
---
