---
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: Phone number (verified via one-time code)
  - category: identifying
    text: Handle, goals, check-ins, verdicts you cast
  - category: location
    text: Coarse region on a verdict (city/country)
  - category: financial
    text: Order records (item, amount, status)
  - category: communication
    text: Live stream content
  - category: device
    text: Session tokens (hashed)
  deletion:
    route: Close account in Profile or by email
    text: 'Deletion: close your account in Profile or by email'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account identity, login, fraud defense
    text: Account identity, login, fraud/Sybil defense
  - purpose: Regional aggregates
    text: Regional "what works where" aggregates
  - purpose: Purchase history and tax/accounting
    text: Purchase history, verified-buyer status, tax/accounting
  - purpose: Fulfilling orders via Presenter
    text: a Presenter, limited to what's needed to fulfill your order from them (never your logs)
  retention:
  - period: 10 minutes
    scope: One-time passcode records
    text: One-time passcode records Login security 10 minutes
  - period: 30 days
    scope: Session tokens
    text: Session tokens (hashed) Keeping you signed in 30 days
  - period: 24 hours from stream start
    scope: Live stream content
    text: Live stream content The live marketplace 24 hours from stream start
  - period: 7 years
    scope: Order records
    text: Order records (item, amount, status) Purchase history, verified-buyer status, tax/accounting 7 years (financial-record retention)
  - period: 30 days
    scope: Personal data on account deletion
    text: personal data is deleted or de-identified within 30 days, except order records we must retain for legal/accounting purposes
  rights:
  - right: Access / export
    text: 'Access / export: request a copy of your data at privacy@healthai.com'
  - right: Deletion
    text: 'Deletion: close your account in Profile or by email'
  role:
    text: HealthAI ("Clarity," "we," "us")
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information
  subprocessors:
    text: service providers under contract (Cloudflare hosting, Stripe payments, Twilio SMS)
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: healthai-com
provenance_date: '2026-11-09'
provider_name: healthai-com
provider_slug: healthai-com
slug: healthai-com-privacy-policy
source_date: '2026-11-09'
source_filename: healthai-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://app.healthai.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: healthai-com\naid: healthai-com\nurl: https://app.healthai.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: HealthAI (\"Clarity,\" \"we,\" \"us\")\ndata_categories:\n- category: contact\n  text: Phone number (verified via one-time code)\n- category: identifying\n  text: Handle, goals, check-ins, verdicts you cast\n- category: location\n  text: Coarse region on a verdict (city/country)\n- category: financial\n  text: Order records (item, amount, status)\n- category: communication\n  text: Live stream content\n- category: device\n  text: Session tokens (hashed)\npurposes:\n- purpose:\
  \ Account identity, login, fraud defense\n  text: Account identity, login, fraud/Sybil defense\n- purpose: Regional aggregates\n  text: Regional \"what works where\" aggregates\n- purpose: Purchase history and tax/accounting\n  text: Purchase history, verified-buyer status, tax/accounting\n- purpose: Fulfilling orders via Presenter\n  text: a Presenter, limited to what's needed to fulfill your order from them (never your logs)\nretention:\n- scope: One-time passcode records\n  period: 10 minutes\n  text: One-time passcode records Login security 10 minutes\n- scope: Session tokens\n  period: 30 days\n  text: Session tokens (hashed) Keeping you signed in 30 days\n- scope: Live stream content\n  period: 24 hours from stream start\n  text: Live stream content The live marketplace 24 hours from stream start\n- scope: Order records\n  period: 7 years\n  text: Order records (item, amount, status) Purchase history, verified-buyer status, tax/accounting 7 years (financial-record\n    retention)\n\
  - scope: Personal data on account deletion\n  period: 30 days\n  text: personal data is deleted or de-identified within 30 days, except order records we must retain for legal/accounting\n    purposes\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: service providers under contract (Cloudflare hosting, Stripe payments, Twilio SMS)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Close account in Profile or by email\n  text: 'Deletion: close your account in Profile or by email'\nrights:\n- right: Access / export\n  text: 'Access / export: request a copy of your data at privacy@healthai.com'\n- right: Deletion\n  text: 'Deletion: close your account in Profile or by email'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information\n"
source_yaml_url: https://artifacts.apis.io/healthai-com/privacy/healthai-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from healthai-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Artificial Intelligence
- Evidence
- Tools
---
