---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Account email (only if you sign in) — used for passwordless sign-in
  - category: identifying
    text: Passkey credentials (only if you enrol one) — if you choose a passkey for sign-in, we store its public key and a signature counter, bound to your account.
  - category: financial
    text: Billing data (only if you open Checkout or use Pro)
  - category: device
    text: Connection-time data (such as IP address) is processed transiently at the edge for rate limiting
  - category: behavioral
    text: Product analytics (cookieless, server-side) — to understand which pages bring people to AI Commander
  - category: communication
    text: Files you transfer — when you use the file-transfer feature to copy a file off one of your machines
  deletion:
    route: contact
    text: To exercise any of these — or to delete your account — contact
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Running the service
    text: Running the service — registering agents, routing commands to the right machine by session code
  - purpose: Sign-in and account features
    text: Sign-in & account features — delivering magic-link emails and keeping you signed in.
  - purpose: Abuse prevention
    text: Abuse prevention — per-IP and per-email rate limiting, an optional bot gate (Cloudflare Turnstile) on the OAuth page
  - purpose: Product analytics
    text: Product analytics — the cookieless Google Analytics 4 events described in section 2
  - purpose: Providing Pro and administering payments
    text: Providing Pro and administering payments — opening Stripe Checkout/Portal, reconciling subscription state
  residency:
  - region: EU (Mailgun email delivery)
    text: AI Commander uses Mailgun's EU region
  retention:
  - period: not retained at all
    scope: Commands and output
    text: Commands and output — not retained at all (see section 2).
  - period: 7 days
    scope: Error diagnostics
    text: Error diagnostics — 7 days in Cloudflare Workers Logs, then deleted by Cloudflare.
  - period: 30 days
    scope: Failed sign-in diagnostics
    text: Failed sign-in diagnostics — entries are excluded from reads after 30 days.
  - period: 180 days
    scope: Usage counters
    text: Usage counters — 180 days, then purged by the same hourly cleanup job.
  - period: 24 hours
    scope: Transferred files
    text: Transferred files — access ends 24 hours after creation, downloaded or not.
  - period: 2 months
    scope: Product analytics
    text: Google Analytics keeps event-level data for 2 months
  rights:
  - right: access
    text: you have the right to access your personal data, rectify inaccurate data, erase it, restrict or object to processing, and data portability.
  - right: complaint to supervisory authority
    text: You also have the right to lodge a complaint with a supervisory authority
  role:
    text: the controller for the processing described here
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, and we do not use your data to build advertising profiles.
  subprocessors:
    text: AI Commander relies on the following infrastructure and external services, each for a narrow, defined purpose
    url: null
  transfers:
  - mechanism: DPF
    text: Google may process this data in the United States, where Google LLC participates in the EU–US Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AI Commander
provenance_date: '2026-11-09'
provider_name: AI Commander
provider_slug: aicommander-dev
slug: aicommander-dev-privacy-policy
source_date: '2026-11-09'
source_filename: aicommander-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aicommander.dev/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AI Commander\naid: aicommander-dev\nurl: https://aicommander.dev/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: the controller for the processing described here\ndata_categories:\n- category: contact\n  text: Account email (only if you sign in) — used for passwordless sign-in\n- category: identifying\n  text: Passkey credentials (only if you enrol one) — if you choose a passkey for sign-in, we store its public key\n    and a signature counter, bound to your account.\n- category: financial\n  text: Billing data (only if you open Checkout or use Pro)\n- category: device\n  text: Connection-time\
  \ data (such as IP address) is processed transiently at the edge for rate limiting\n- category: behavioral\n  text: Product analytics (cookieless, server-side) — to understand which pages bring people to AI Commander\n- category: communication\n  text: Files you transfer — when you use the file-transfer feature to copy a file off one of your machines\npurposes:\n- purpose: Running the service\n  text: Running the service — registering agents, routing commands to the right machine by session code\n- purpose: Sign-in and account features\n  text: Sign-in & account features — delivering magic-link emails and keeping you signed in.\n- purpose: Abuse prevention\n  text: Abuse prevention — per-IP and per-email rate limiting, an optional bot gate (Cloudflare Turnstile) on the\n    OAuth page\n- purpose: Product analytics\n  text: Product analytics — the cookieless Google Analytics 4 events described in section 2\n- purpose: Providing Pro and administering payments\n  text: Providing Pro and administering\
  \ payments — opening Stripe Checkout/Portal, reconciling subscription state\nretention:\n- scope: Commands and output\n  period: not retained at all\n  text: Commands and output — not retained at all (see section 2).\n- scope: Error diagnostics\n  period: 7 days\n  text: Error diagnostics — 7 days in Cloudflare Workers Logs, then deleted by Cloudflare.\n- scope: Failed sign-in diagnostics\n  period: 30 days\n  text: Failed sign-in diagnostics — entries are excluded from reads after 30 days.\n- scope: Usage counters\n  period: 180 days\n  text: Usage counters — 180 days, then purged by the same hourly cleanup job.\n- scope: Transferred files\n  period: 24 hours\n  text: Transferred files — access ends 24 hours after creation, downloaded or not.\n- scope: Product analytics\n  period: 2 months\n  text: Google Analytics keeps event-level data for 2 months\nresidency:\n- region: EU (Mailgun email delivery)\n  text: AI Commander uses Mailgun's EU region\ntransfers:\n- mechanism: DPF\n  text:\
  \ Google may process this data in the United States, where Google LLC participates in the EU–US Data Privacy\n    Framework.\nsubprocessors:\n  url: null\n  text: AI Commander relies on the following infrastructure and external services, each for a narrow, defined purpose\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact\n  text: To exercise any of these — or to delete your account — contact\nrights:\n- right: access\n  text: you have the right to access your personal data, rectify inaccurate data, erase it, restrict or object to\n    processing, and data portability.\n- right: complaint to supervisory authority\n  text: You also have the right to lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, and we do not use your data to build advertising profiles.\n"
source_yaml_url: https://artifacts.apis.io/aicommander-dev/privacy/aicommander-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from AI Commander's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- RemoteShell
- Machine Learning
- Automation
- Cloud
---
