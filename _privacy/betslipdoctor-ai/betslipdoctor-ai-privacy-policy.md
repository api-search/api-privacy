---
api_specs:
- filename: betslipdoctor-ai-board-api-openapi.yml
  format: yaml
  label: BetSlip Doctor Board API
  slug: betslipdoctor-ai-board-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betslipdoctor-ai/openapi/betslipdoctor-ai-board-api-openapi.yml
- filename: betslipdoctor-ai-grade-api-openapi.yml
  format: yaml
  label: BetSlip Doctor Grade API
  slug: betslipdoctor-ai-grade-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betslipdoctor-ai/openapi/betslipdoctor-ai-grade-api-openapi.yml
- filename: betslipdoctor-ai-history-api-openapi.yml
  format: yaml
  label: BetSlip Doctor History API
  slug: betslipdoctor-ai-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betslipdoctor-ai/openapi/betslipdoctor-ai-history-api-openapi.yml
- filename: betslipdoctor-ai-reports-api-openapi.yml
  format: yaml
  label: BetSlip Doctor Reports API
  slug: betslipdoctor-ai-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betslipdoctor-ai/openapi/betslipdoctor-ai-reports-api-openapi.yml
- filename: betslipdoctor-ai-slips-api-openapi.yml
  format: yaml
  label: BetSlip Doctor Slips API
  slug: betslipdoctor-ai-slips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betslipdoctor-ai/openapi/betslipdoctor-ai-slips-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: You may enter an email address to create or sign in to the same BSD account on more than one device.
  - category: financial
    text: Once you subscribe, Apple handles billing entirely, we receive your subscription status and an Apple transaction identifier, never your card details and never your Apple Account credentials.
  - category: location
    text: turns it into a U.S. state on your device, and sends only that two-letter state code to us and on to SharpSports.
  - category: behavioral
    text: the events and selections, the odds, the amount at risk, the amount to win, the payout, the net result, and whether each bet won, lost, or pushed.
  - category: device
    text: Before you subscribe, the app creates a random device identifier for preview access.
  - category: communication
    text: An Expo push token if this device registers for remote alerts, so we can deliver scan and settlement updates.
  - category: professional
    text: 'Your bettor profile, if you set one: betting style, risk tolerance, your unit size in dollars, and the sports and sportsbooks you follow.'
  deletion:
    route: in-app Delete Account
    text: 'Deletion: use in-app Delete Account'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the service
    text: we keep what we need to run your Grades, your connected sportsbook history, your posts, and your billing.
  - purpose: train own models
    text: We use your data to train and improve our own models, and this is on by default.
  - purpose: product analytics
    text: so we can see what works and fix what doesn’t
  retention:
  - period: 45 days
    scope: raw operational analysis records
    text: Raw operational analysis records normally expire after 45 days.
  - period: 30 days
    scope: working research material
    text: Working research material from Grades, fetched pages, intermediate model notes, progress events, is pruned on a rolling schedule, normally around 30 days after a scan finishes.
  - period: 400 days
    scope: product events
    text: Product events are kept for up to 400 days, or 90 days for the most frequent kinds, such as screen views and Live browsing.
  - period: 120 days
    scope: aggregate cost and usage telemetry
    text: Aggregate cost and usage telemetry is kept somewhat longer (around 120 days) for accounting.
  - period: null
    scope: imported sportsbook history
    text: Imported sportsbook history is kept while your account exists, so your record and grades stay accurate.
  rights:
  - right: export account activity
    text: 'Export: use Export account activity in the app’s Account screen'
  - right: withdraw AI sharing permission
    text: withdraw your permission any time in Settings → Third-party AI sharing
  - right: turn off model training
    text: Turn it off any time in Settings → Improve the Doctor’s models with my data, or by email.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent personal data
  subprocessors:
    text: 'These are the third parties that can receive data about you, and what each one is for:'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BetSlip Doctor
provenance_date: '2026-11-09'
provider_name: BetSlip Doctor
provider_slug: betslipdoctor-ai
slug: betslipdoctor-ai-privacy-policy
source_date: '2026-11-09'
source_filename: betslipdoctor-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://betslipdoctor.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BetSlip Doctor\naid: betslipdoctor-ai\nurl: https://betslipdoctor.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: You may enter an email address to create or sign in to the same BSD account on more than one device.\n- category: financial\n  text: Once you subscribe, Apple handles billing entirely, we receive your subscription status and an Apple transaction\n    identifier, never your card details and never your Apple Account credentials.\n- category: location\n  text: turns it into a U.S. state on your device, and sends only that\
  \ two-letter state code to us and on to SharpSports.\n- category: behavioral\n  text: the events and selections, the odds, the amount at risk, the amount to win, the payout, the net result,\n    and whether each bet won, lost, or pushed.\n- category: device\n  text: Before you subscribe, the app creates a random device identifier for preview access.\n- category: communication\n  text: An Expo push token if this device registers for remote alerts, so we can deliver scan and settlement updates.\n- category: professional\n  text: 'Your bettor profile, if you set one: betting style, risk tolerance, your unit size in dollars, and the\n    sports and sportsbooks you follow.'\npurposes:\n- purpose: run the service\n  text: we keep what we need to run your Grades, your connected sportsbook history, your posts, and your billing.\n- purpose: train own models\n  text: We use your data to train and improve our own models, and this is on by default.\n- purpose: product analytics\n  text: so we can\
  \ see what works and fix what doesn’t\nretention:\n- scope: raw operational analysis records\n  period: 45 days\n  text: Raw operational analysis records normally expire after 45 days.\n- scope: working research material\n  period: 30 days\n  text: Working research material from Grades, fetched pages, intermediate model notes, progress events, is pruned\n    on a rolling schedule, normally around 30 days after a scan finishes.\n- scope: product events\n  period: 400 days\n  text: Product events are kept for up to 400 days, or 90 days for the most frequent kinds, such as screen views\n    and Live browsing.\n- scope: aggregate cost and usage telemetry\n  period: 120 days\n  text: Aggregate cost and usage telemetry is kept somewhat longer (around 120 days) for accounting.\n- scope: imported sportsbook history\n  period: null\n  text: Imported sportsbook history is kept while your account exists, so your record and grades stay accurate.\nresidency: []\ntransfers: []\nsubprocessors:\n  url:\
  \ null\n  text: 'These are the third parties that can receive data about you, and what each one is for:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: in-app Delete Account\n  text: 'Deletion: use in-app Delete Account'\nrights:\n- right: export account activity\n  text: 'Export: use Export account activity in the app’s Account screen'\n- right: withdraw AI sharing permission\n  text: withdraw your permission any time in Settings → Third-party AI sharing\n- right: turn off model training\n  text: Turn it off any time in Settings → Improve the Doctor’s models with my data, or by email.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal data\n"
source_yaml_url: https://artifacts.apis.io/betslipdoctor-ai/privacy/betslipdoctor-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from BetSlip Doctor's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sports
- Betting
- Analytics
- Mobile
---
