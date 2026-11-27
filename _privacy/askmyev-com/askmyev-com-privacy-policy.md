---
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: your email address (we prefill the one from your Tesla account) and plan details
  - category: location
    text: 'Location (off by default): fetched live only when your AI app asks, after you turn it on. We don''t store coordinates'
  - category: device
    text: 'Vehicle data needed to answer you: battery, range, charging state, charge limit, odometer, tire pressures, temperatures, software version, vehicle status and Tesla alerts.'
  - category: financial
    text: 'Billing: handled by Stripe. We get your Stripe customer and subscription IDs, plan, status and payment dates, never your full card number.'
  - category: behavioral
    text: 'Website and setup statistics: Cloudflare Web Analytics counts visits without cookies.'
  - category: communication
    text: 'Support: whatever you send us.'
  deletion:
    route: Delete your account on your Account page
    text: Delete your account on your Account page (see how deletion works ).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: 'Only to provide the Service: answering what you ask through your AI app, running commands you ask for, safety limits and unusual-activity warnings, billing, preventing trial abuse and fraud, support, fixing problems, required service emails, and meeting legal obligations.'
  - purpose: Aggregated stats
    text: We use aggregated stats that don't identify you, your car or a precise location to improve the Service.
  residency:
  - region: United States
    text: We and our providers process and store data in the United States.
  retention:
  - period: 30 days
    scope: Car history
    text: 'Car history: free trial 30 days; monthly plan 12 months rolling; annual plan while subscribed; after you cancel, 90 days, then deleted.'
  - period: up to 2 years
    scope: Setup statistics
    text: 'Setup statistics: up to 2 years (your account ID is removed if you delete your account).'
  - period: 1 year
    scope: Command and location-lookup logs
    text: 'Command and location-lookup logs: 1 year, for safety, fraud and legal reasons, even after account deletion.'
  - period: at least 3 years
    scope: Consent and subscription records
    text: 'Consent and subscription records: at least 3 years, as the law requires.'
  rights:
  - right: access
    text: You can ask to access, correct, delete, restrict or export your data, or object to processing, by emailing support@askmyev.com
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell or share your personal information for money or for cross-context behavioral advertising, and we don't use it for ads.
  subprocessors:
    text: 'Service providers who process data for us under contract and only to provide the Service: Tesla (car data and commands), Cloudflare (hosting, database, analytics), Fly.io (receiving live car updates), Resend (email) and Stripe (payments).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AskMyEV
provenance_date: '2026-11-09'
provider_name: AskMyEV
provider_slug: askmyev-com
slug: askmyev-com-privacy-policy
source_date: '2026-11-09'
source_filename: askmyev-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://askmyev.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AskMyEV\naid: askmyev-com\nurl: https://askmyev.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your email address (we prefill the one from your Tesla account) and plan details\n- category: location\n  text: 'Location (off by default): fetched live only when your AI app asks, after you turn it on. We don''t store\n    coordinates'\n- category: device\n  text: 'Vehicle data needed to answer you: battery, range, charging state, charge limit, odometer, tire pressures,\n    temperatures, software version, vehicle status and Tesla\
  \ alerts.'\n- category: financial\n  text: 'Billing: handled by Stripe. We get your Stripe customer and subscription IDs, plan, status and payment\n    dates, never your full card number.'\n- category: behavioral\n  text: 'Website and setup statistics: Cloudflare Web Analytics counts visits without cookies.'\n- category: communication\n  text: 'Support: whatever you send us.'\npurposes:\n- purpose: Provide the Service\n  text: 'Only to provide the Service: answering what you ask through your AI app, running commands you ask for,\n    safety limits and unusual-activity warnings, billing, preventing trial abuse and fraud, support, fixing problems,\n    required service emails, and meeting legal obligations.'\n- purpose: Aggregated stats\n  text: We use aggregated stats that don't identify you, your car or a precise location to improve the Service.\nretention:\n- scope: Car history\n  period: 30 days\n  text: 'Car history: free trial 30 days; monthly plan 12 months rolling; annual plan while\
  \ subscribed; after you\n    cancel, 90 days, then deleted.'\n- scope: Setup statistics\n  period: up to 2 years\n  text: 'Setup statistics: up to 2 years (your account ID is removed if you delete your account).'\n- scope: Command and location-lookup logs\n  period: 1 year\n  text: 'Command and location-lookup logs: 1 year, for safety, fraud and legal reasons, even after account deletion.'\n- scope: Consent and subscription records\n  period: at least 3 years\n  text: 'Consent and subscription records: at least 3 years, as the law requires.'\nresidency:\n- region: United States\n  text: We and our providers process and store data in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Service providers who process data for us under contract and only to provide the Service: Tesla (car data\n    and commands), Cloudflare (hosting, database, analytics), Fly.io (receiving live car updates), Resend (email)\n    and Stripe (payments).'\ndpa:\n  available: null\n  url: null\n\
  \  text: null\ndeletion:\n  route: Delete your account on your Account page\n  text: Delete your account on your Account page (see how deletion works ).\nrights:\n- right: access\n  text: You can ask to access, correct, delete, restrict or export your data, or object to processing, by emailing\n    support@askmyev.com\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell or share your personal information for money or for cross-context behavioral advertising,\n    and we don't use it for ads.\n"
source_yaml_url: https://artifacts.apis.io/askmyev-com/privacy/askmyev-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from AskMyEV's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Tesla
- Automotive
- Assistant
---
