---
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Username - A unique identifier you choose
  - category: contact
    text: Email address - If you add an email address to your account for account recovery and password resets
  - category: contact
    text: Phone number - Only if you enable the phone call notification feature (verified via SMS/call)
  - category: financial
    text: Stripe customer ID Subscription status and billing period
  - category: device
    text: Web push subscriptions - If you enable browser notifications, we store your browser's push subscription endpoint to deliver notifications.
  - category: location
    text: IP addresses - Used for rate limiting to prevent abuse.
  - category: communication
    text: 'Message content - Messages you publish are temporarily cached on our servers (default: 12 hours)'
  deletion:
    route: Account settings in the web app, or contact us
    text: To delete your account, use the account settings in the web app or contact us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account recovery and notifications
    text: for use with the email notification feature
  - purpose: Rate limiting to prevent abuse
    text: Used for rate limiting to prevent abuse.
  - purpose: Message delivery
    text: to support message polling and to overcome client network disruptions
  - purpose: Payment processing
    text: for billing purposes via Stripe
  retention:
  - period: 12 hours
    scope: Messages
    text: 'Messages you publish are temporarily cached on our servers (default: 12 hours)'
  - period: 3 hours
    scope: Attachments
    text: 'File attachments are temporarily stored (default: 3 hours) and then automatically deleted.'
  - period: Until you delete your account
    scope: User accounts
    text: User accounts Until you delete your account
  - period: 60 days of inactivity, then automatically removed
    scope: Web push subscriptions
    text: Web push subscriptions 60 days of inactivity, then automatically removed
  rights:
  - right: Access
    text: Access - View your account information and data
  - right: Delete
    text: Delete - Delete your account and associated data via the web app
  - right: Export
    text: Export - Your messages are available via the API while cached
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: we will never monetize or sell your information
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ntfy
provenance_date: '2026-11-10'
provider_name: ntfy
provider_slug: ntfy
slug: ntfy-privacy-policy
source_date: '2026-11-10'
source_filename: ntfy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://docs.ntfy.sh/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ntfy\naid: ntfy\nurl: https://docs.ntfy.sh/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Username - A unique identifier you choose\n- category: contact\n  text: Email address - If you add an email address to your account for account recovery and password resets\n- category: contact\n  text: Phone number - Only if you enable the phone call notification feature (verified via SMS/call)\n- category: financial\n  text: Stripe customer ID Subscription status and billing period\n- category: device\n  text: Web push subscriptions - If\
  \ you enable browser notifications, we store your browser's push subscription\n    endpoint to deliver notifications.\n- category: location\n  text: IP addresses - Used for rate limiting to prevent abuse.\n- category: communication\n  text: 'Message content - Messages you publish are temporarily cached on our servers (default: 12 hours)'\npurposes:\n- purpose: Account recovery and notifications\n  text: for use with the email notification feature\n- purpose: Rate limiting to prevent abuse\n  text: Used for rate limiting to prevent abuse.\n- purpose: Message delivery\n  text: to support message polling and to overcome client network disruptions\n- purpose: Payment processing\n  text: for billing purposes via Stripe\nretention:\n- scope: Messages\n  period: 12 hours\n  text: 'Messages you publish are temporarily cached on our servers (default: 12 hours)'\n- scope: Attachments\n  period: 3 hours\n  text: 'File attachments are temporarily stored (default: 3 hours) and then automatically deleted.'\n\
  - scope: User accounts\n  period: Until you delete your account\n  text: User accounts Until you delete your account\n- scope: Web push subscriptions\n  period: 60 days of inactivity, then automatically removed\n  text: Web push subscriptions 60 days of inactivity, then automatically removed\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings in the web app, or contact us\n  text: To delete your account, use the account settings in the web app or contact us.\nrights:\n- right: Access\n  text: Access - View your account information and data\n- right: Delete\n  text: Delete - Delete your account and associated data via the web app\n- right: Export\n  text: Export - Your messages are available via the API while cached\nsale_or_sharing:\n  stance: prohibited\n  text: we will never monetize or sell your information\n"
source_yaml_url: https://artifacts.apis.io/ntfy/privacy/ntfy-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from ntfy's own page on 2026-11-10.
synthetic: false
tags:
- Notification
- Open Source
- Self-Hosted
- Pub/Sub
---
