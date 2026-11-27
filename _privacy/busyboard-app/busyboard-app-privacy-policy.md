---
api_specs:
- filename: busyboard-app-api-openapi.yml
  format: yaml
  label: BusyBoard API API
  slug: busyboard-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/busyboard-app/openapi/_original/busyboard-app-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address
  - category: identifying
    text: Unique user ID
  - category: device
    text: Rate limiting IP address, user ID (via Upstash Redis)
  - category: financial
    text: We store your Stripe customer ID, subscription ID, and current plan.
  - category: behavioral
    text: PostHog — product analytics (page views, feature usage) and session replay to understand how users interact with the app
  - category: other
    text: 'What we store from your synced events: only the start and end times, an all-day flag, and your RSVP status.'
  deletion:
    route: account settings
    text: Delete your account (and associated data) via your account settings.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Calendar sync and availability display
    text: Calendar sync and availability display
  - purpose: Payment processing
    text: If you subscribe, Stripe processes your payment.
  - purpose: Error and bug detection
    text: In production, Sentry collects error traces and a 10% sample of performance data to help us fix bugs.
  - purpose: Analytics with consent
    text: 'With your explicit consent, we use the following analytics services:'
  retention:
  - period: while your account is active
    scope: Account data
    text: Data is retained while your account is active.
  - period: typically 90 days
    scope: Sentry error data
    text: Sentry retains error data per their default retention settings (typically 90 days).
  rights:
  - right: Access
    text: Request a summary of the data we hold about you.
  - right: Correction
    text: Update your name, email, or profile in your account settings.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not use your data for advertising, sell it to third parties, or use your calendar data for any purpose beyond displaying availability within the Service.
  subprocessors:
    text: With third-party service providers
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BusyBoard
provenance_date: '2026-11-09'
provider_name: BusyBoard
provider_slug: busyboard-app
slug: busyboard-app-privacy-policy
source_date: '2026-11-09'
source_filename: busyboard-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://busyboard.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BusyBoard\naid: busyboard-app\nurl: https://busyboard.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address\n- category: identifying\n  text: Unique user ID\n- category: device\n  text: Rate limiting IP address, user ID (via Upstash Redis)\n- category: financial\n  text: We store your Stripe customer ID, subscription ID, and current plan.\n- category: behavioral\n  text: PostHog — product analytics (page views, feature usage) and session replay to understand how users interact\n    with the app\n- category: other\n \
  \ text: 'What we store from your synced events: only the start and end times, an all-day flag, and your RSVP status.'\npurposes:\n- purpose: Calendar sync and availability display\n  text: Calendar sync and availability display\n- purpose: Payment processing\n  text: If you subscribe, Stripe processes your payment.\n- purpose: Error and bug detection\n  text: In production, Sentry collects error traces and a 10% sample of performance data to help us fix bugs.\n- purpose: Analytics with consent\n  text: 'With your explicit consent, we use the following analytics services:'\nretention:\n- scope: Account data\n  period: while your account is active\n  text: Data is retained while your account is active.\n- scope: Sentry error data\n  period: typically 90 days\n  text: Sentry retains error data per their default retention settings (typically 90 days).\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: With third-party service providers\ndpa:\n  available: null\n  url: null\n\
  \  text: null\ndeletion:\n  route: account settings\n  text: Delete your account (and associated data) via your account settings.\nrights:\n- right: Access\n  text: Request a summary of the data we hold about you.\n- right: Correction\n  text: Update your name, email, or profile in your account settings.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not use your data for advertising, sell it to third parties, or use your calendar data for any purpose\n    beyond displaying availability within the Service.\n"
source_yaml_url: https://artifacts.apis.io/busyboard-app/privacy/busyboard-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from BusyBoard's own page on 2026-11-09.
synthetic: false
tags:
- Scheduling
- Calendar
- Privacy
- Free
- Software-as-a-Service
---
