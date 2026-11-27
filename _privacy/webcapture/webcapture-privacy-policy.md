---
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: API keys are stored only as SHA-256 hashes (you see a short prefix in the dashboard)
  - category: contact
    text: If you sign in with email, we store the address and send a short-lived sign-in code
  - category: identifying
    text: If you sign in with Google, we also store your Google account's email and display name, and a session record so the dashboard remembers you.
  - category: behavioral
    text: per-account monthly usage counts, the webhook URL if you configure one, and a conversion index (the source URL, byte size and timestamp of each render)
  - category: other
    text: 'Rendered PDFs are kept so you can download them, then deleted automatically: 7 days on Free and Pro, 30 days on Scale.'
  deletion:
    route: Erase account control in the dashboard, or email hello@webcapture.io
    text: 'Objection and deletion are both served by the Erase account control: after you type DELETE to confirm, it removes rendered artifacts, the conversion index, usage counts, API keys, queued webhook deliveries, quota notices, every sign-in session, and the account record itself'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Running the service and account
    text: 'Account data is processed to perform the contract you create by signing up: the dashboard, keys, quotas, and billing only work with it.'
  - purpose: Security logging and abuse prevention
    text: Security logging, rate limiting, and the audit trail run under the legitimate-interests lawful basis of abuse and intrusion prevention.
  - purpose: Error monitoring
    text: 'Sentry (error and performance monitoring in production: crash reports with stack traces and coarse request metadata, a sample of request traces, and the same from a signed-in dashboard session.'
  - purpose: Product analytics
    text: 'PostHog (product analytics, EU-hosted: counts events like sign-ups and renders'
  residency:
  - region: Singapore
    text: The URL you submit, the rendered file, and a usage counter live in our single application datastore on our own infrastructure (OVHcloud, in Singapore)
  - region: EU
    text: PostHog (product analytics, EU-hosted
  retention:
  - period: 7 days
    scope: Rendered PDFs and conversion index rows on Free and Pro
    text: 'Rendered files and their index rows are deleted automatically: 7 days on Free and Pro, 30 days on Scale.'
  - period: 30 days
    scope: Rendered PDFs and conversion index rows on Scale
    text: 'Rendered files and their index rows are deleted automatically: 7 days on Free and Pro, 30 days on Scale.'
  - period: null
    scope: Account record
    text: Your account record (the email, display name, tier, and session rows) persists until you erase the account, which the dashboard can do on the spot.
  - period: minutes
    scope: Email sign-in code
    text: The code itself is kept only as a hash and expires in minutes.
  rights:
  - right: access
    text: You have access, correction, portability, objection, and complaint, and most of them are buttons in the dashboard's Account screen rather than an email form.
  - right: portability
    text: Export your data returns one JSON file with the account record, the keys (their settings, never the stored hashes or webhook secrets), the usage counts, and the conversion index
  - right: correction
    text: Correction covers the display name on the same screen.
  - right: complaint
    text: To complain, write to us at the same address, or to the Office of the Privacy Commissioner for Personal Data in Hong Kong.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No advertising.
  subprocessors:
    text: 'Six providers act as pipes for your data: Google (sign-in identity, and Google Analytics page-view and interaction-event measurement on public pages when configured) Resend (one-time codes and account email) Stripe (billing, once live) OVHcloud (hosting, in Singapore) with Cloudflare (network, and the bot check on sign-in and the free tool) Sentry (error and performance monitoring in production'
    url: null
  transfers:
  - mechanism: other
    text: No certification beyond what each vendor itself publishes is claimed here.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: webcapture
provenance_date: '2026-11-10'
provider_name: webcapture
provider_slug: webcapture
slug: webcapture-privacy-policy
source_date: '2026-11-10'
source_filename: webcapture-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://webcapture.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: webcapture\naid: webcapture\nurl: https://webcapture.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: API keys are stored only as SHA-256 hashes (you see a short prefix in the dashboard)\n- category: contact\n  text: If you sign in with email, we store the address and send a short-lived sign-in code\n- category: identifying\n  text: If you sign in with Google, we also store your Google account's email and display name, and a session record\n    so the dashboard remembers you.\n- category: behavioral\n  text: per-account monthly\
  \ usage counts, the webhook URL if you configure one, and a conversion index (the source\n    URL, byte size and timestamp of each render)\n- category: other\n  text: 'Rendered PDFs are kept so you can download them, then deleted automatically: 7 days on Free and Pro, 30\n    days on Scale.'\npurposes:\n- purpose: Running the service and account\n  text: 'Account data is processed to perform the contract you create by signing up: the dashboard, keys, quotas,\n    and billing only work with it.'\n- purpose: Security logging and abuse prevention\n  text: Security logging, rate limiting, and the audit trail run under the legitimate-interests lawful basis of\n    abuse and intrusion prevention.\n- purpose: Error monitoring\n  text: 'Sentry (error and performance monitoring in production: crash reports with stack traces and coarse request\n    metadata, a sample of request traces, and the same from a signed-in dashboard session.'\n- purpose: Product analytics\n  text: 'PostHog (product analytics,\
  \ EU-hosted: counts events like sign-ups and renders'\nretention:\n- scope: Rendered PDFs and conversion index rows on Free and Pro\n  period: 7 days\n  text: 'Rendered files and their index rows are deleted automatically: 7 days on Free and Pro, 30 days on Scale.'\n- scope: Rendered PDFs and conversion index rows on Scale\n  period: 30 days\n  text: 'Rendered files and their index rows are deleted automatically: 7 days on Free and Pro, 30 days on Scale.'\n- scope: Account record\n  period: null\n  text: Your account record (the email, display name, tier, and session rows) persists until you erase the account,\n    which the dashboard can do on the spot.\n- scope: Email sign-in code\n  period: minutes\n  text: The code itself is kept only as a hash and expires in minutes.\nresidency:\n- region: Singapore\n  text: The URL you submit, the rendered file, and a usage counter live in our single application datastore on our\n    own infrastructure (OVHcloud, in Singapore)\n- region: EU\n  text:\
  \ PostHog (product analytics, EU-hosted\ntransfers:\n- mechanism: other\n  text: No certification beyond what each vendor itself publishes is claimed here.\nsubprocessors:\n  url: null\n  text: 'Six providers act as pipes for your data: Google (sign-in identity, and Google Analytics page-view and\n    interaction-event measurement on public pages when configured) Resend (one-time codes and account email) Stripe\n    (billing, once live) OVHcloud (hosting, in Singapore) with Cloudflare (network, and the bot check on sign-in\n    and the free tool) Sentry (error and performance monitoring in production'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Erase account control in the dashboard, or email hello@webcapture.io\n  text: 'Objection and deletion are both served by the Erase account control: after you type DELETE to confirm,\n    it removes rendered artifacts, the conversion index, usage counts, API keys, queued webhook deliveries, quota\n    notices, every sign-in\
  \ session, and the account record itself'\nrights:\n- right: access\n  text: You have access, correction, portability, objection, and complaint, and most of them are buttons in the\n    dashboard's Account screen rather than an email form.\n- right: portability\n  text: Export your data returns one JSON file with the account record, the keys (their settings, never the stored\n    hashes or webhook secrets), the usage counts, and the conversion index\n- right: correction\n  text: Correction covers the display name on the same screen.\n- right: complaint\n  text: To complain, write to us at the same address, or to the Office of the Privacy Commissioner for Personal\n    Data in Hong Kong.\nsale_or_sharing:\n  stance: prohibited\n  text: No advertising.\n"
source_yaml_url: https://artifacts.apis.io/webcapture/privacy/webcapture-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from webcapture's own page on 2026-11-10.
synthetic: false
tags:
- Web Capture
- PDF
- Software-as-a-Service
- Automation
---
