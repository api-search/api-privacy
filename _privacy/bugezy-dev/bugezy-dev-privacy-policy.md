---
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Google account email, name and avatar (OAuth scopes: openid , email , profile )'
  - category: location
    text: URL of the active tab and a screenshot of its visible area
  - category: communication
    text: voice recordings and their transcripts
  - category: financial
    text: 'Payment and plan records : ECPay order number, amount, timestamp and plan expiry.'
  - category: device
    text: browser and screen information
  deletion:
    route: delete individual reports in the extension, or email to delete account
    text: delete individual reports at any time, or email us to delete your account and all associated data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: record, store, display and share bug reports
    text: To record, store, display and share your bug reports.
  - purpose: speech-to-text and AI text correction
    text: Speech-to-text (Groq Whisper) and AI text correction/summarisation (Cloudflare Workers AI).
  - purpose: enforce free-plan limits and manage subscriptions
    text: To enforce free-plan limits and manage paid subscriptions.
  - purpose: process payments
    text: To process payments through ECPay.
  - purpose: developer notifications
    text: To notify the developer of key events (new sign-up, new report, code redemption, successful payment) via a Discord webhook; these notifications include your account email.
  retention:
  - period: 7 days
    scope: reports on free plan
    text: reports are kept for 7 days on the free plan and 90 days on paid plans
  - period: 90 days
    scope: reports on paid plans
    text: reports are kept for 7 days on the free plan and 90 days on paid plans (including users with an active promo ticket)
  - period: 90 days
    scope: sign-in sessions
    text: Sign-in sessions expire after 90 days and are then purged automatically.
  rights:
  - right: access and export
    text: 'Access & export : export any report as JSON from the extension.'
  - right: correction
    text: 'Correction : edit the transcript and notes in the editor before uploading.'
  - right: deletion
    text: 'Deletion : delete individual reports at any time, or email us to delete your account and all associated data.'
  - right: withdraw consent
    text: 'Withdraw consent : sign out in the extension, or revoke the app from your Google Account settings.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: We rely on the following processors. Each links to its own privacy policy.
    url: https://bugezy.dev/privacy
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: bugezy-dev
provenance_date: '2026-11-09'
provider_name: bugezy-dev
provider_slug: bugezy-dev
slug: bugezy-dev-privacy-policy
source_date: '2026-11-09'
source_filename: bugezy-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bugezy.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: bugezy-dev\naid: bugezy-dev\nurl: https://bugezy.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Google account email, name and avatar (OAuth scopes: openid , email , profile )'\n- category: location\n  text: URL of the active tab and a screenshot of its visible area\n- category: communication\n  text: voice recordings and their transcripts\n- category: financial\n  text: 'Payment and plan records : ECPay order number, amount, timestamp and plan expiry.'\n- category: device\n  text: browser and screen information\npurposes:\n\
  - purpose: record, store, display and share bug reports\n  text: To record, store, display and share your bug reports.\n- purpose: speech-to-text and AI text correction\n  text: Speech-to-text (Groq Whisper) and AI text correction/summarisation (Cloudflare Workers AI).\n- purpose: enforce free-plan limits and manage subscriptions\n  text: To enforce free-plan limits and manage paid subscriptions.\n- purpose: process payments\n  text: To process payments through ECPay.\n- purpose: developer notifications\n  text: To notify the developer of key events (new sign-up, new report, code redemption, successful payment) via\n    a Discord webhook; these notifications include your account email.\nretention:\n- scope: reports on free plan\n  period: 7 days\n  text: reports are kept for 7 days on the free plan and 90 days on paid plans\n- scope: reports on paid plans\n  period: 90 days\n  text: reports are kept for 7 days on the free plan and 90 days on paid plans (including users with an active promo\n\
  \    ticket)\n- scope: sign-in sessions\n  period: 90 days\n  text: Sign-in sessions expire after 90 days and are then purged automatically.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: https://bugezy.dev/privacy\n  text: We rely on the following processors. Each links to its own privacy policy.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete individual reports in the extension, or email to delete account\n  text: delete individual reports at any time, or email us to delete your account and all associated data.\nrights:\n- right: access and export\n  text: 'Access & export : export any report as JSON from the extension.'\n- right: correction\n  text: 'Correction : edit the transcript and notes in the editor before uploading.'\n- right: deletion\n  text: 'Deletion : delete individual reports at any time, or email us to delete your account and all associated\n    data.'\n- right: withdraw consent\n  text: 'Withdraw consent : sign out in the extension,\
  \ or revoke the app from your Google Account settings.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/bugezy-dev/privacy/bugezy-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from bugezy-dev's own page on 2026-11-09.
synthetic: false
tags:
- Bug Reporting
- Artificial Intelligence
- Developer Tools
- Software-as-a-Service
- Productivity
---
