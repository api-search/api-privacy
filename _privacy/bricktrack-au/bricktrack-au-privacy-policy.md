---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information (name, email address)
  - category: contact
    text: Account information (name, email address)
  - category: behavioral
    text: When analytics is on, PostHog records the pages you visit and your setup steps, along with the text of any button or link you click, linked to your account once you sign in.
  - category: location
    text: We use the country our host, Vercel, gives us for your IP address only to pick this default, and we don't store it.
  - category: device
    text: Your IP address and browser details
  - category: financial
    text: Stripe payment records are anonymised at T+30 days and fully deleted at T+120 days
  - category: communication
    text: Account events recorded by our servers
  deletion:
    route: Delete Account page in Settings; hard-delete after 30-day grace period
    text: After the grace period expires, your database records, uploaded documents, and storage objects that remain owned only by your account are permanently deleted.
  dpa:
    available: true
    text: each bound by a Data Processing Agreement or equivalent contractual terms.
    url: null
  purposes:
  - purpose: Provide and improve services
    text: Provide and improve our services
  - purpose: Customer support
    text: Provide customer support
  - purpose: Service notifications
    text: Send service-related notifications
  - purpose: Ad measurement
    text: Measure which of our ads lead to sign-ups, where analytics is on for you (see section 6)
  residency:
  - region: Australia
    text: Your portfolio records and documents are stored on secure servers located in Australia.
  retention:
  - period: null
    scope: Account data
    text: After you request account deletion, a 30-day grace period applies during which you may cancel the request.
  - period: T+120 days
    scope: Stripe records
    text: fully deleted at T+120 days via automated cron.
  - period: 90 days
    scope: Resend transactional send records
    text: transactional send records retained for 90 days then deleted.
  - period: 7 days
    scope: Ad click reference
    text: for up to 7 days on your device ( bt_ad_click )
  rights:
  - right: Access
    text: Access your personal data
  - right: Correct
    text: Correct inaccurate data
  - right: Delete
    text: Delete your account and data
  - right: Export
    text: Export your data as a structured archive, at any time and on every plan, from the Delete Account page in Settings
  role:
    text: “We” and “us” mean that company.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: Some supporting services process limited data offshore; each one is listed in the sub-processor table below, with the region it operates in where the provider publishes one.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BrickTrack
provenance_date: '2026-11-09'
provider_name: BrickTrack
provider_slug: bricktrack-au
slug: bricktrack-au-privacy-policy
source_date: '2026-11-09'
source_filename: bricktrack-au-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bricktrack.au/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BrickTrack\naid: bricktrack-au\nurl: https://www.bricktrack.au/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: “We” and “us” mean that company.\ndata_categories:\n- category: identifying\n  text: Account information (name, email address)\n- category: contact\n  text: Account information (name, email address)\n- category: behavioral\n  text: When analytics is on, PostHog records the pages you visit and your setup steps, along with the text of any\n    button or link you click, linked to your account once you sign in.\n- category: location\n  text: We use the country our host, Vercel,\
  \ gives us for your IP address only to pick this default, and we don't\n    store it.\n- category: device\n  text: Your IP address and browser details\n- category: financial\n  text: Stripe payment records are anonymised at T+30 days and fully deleted at T+120 days\n- category: communication\n  text: Account events recorded by our servers\npurposes:\n- purpose: Provide and improve services\n  text: Provide and improve our services\n- purpose: Customer support\n  text: Provide customer support\n- purpose: Service notifications\n  text: Send service-related notifications\n- purpose: Ad measurement\n  text: Measure which of our ads lead to sign-ups, where analytics is on for you (see section 6)\nretention:\n- scope: Account data\n  period: null\n  text: After you request account deletion, a 30-day grace period applies during which you may cancel the request.\n- scope: Stripe records\n  period: T+120 days\n  text: fully deleted at T+120 days via automated cron.\n- scope: Resend transactional\
  \ send records\n  period: 90 days\n  text: transactional send records retained for 90 days then deleted.\n- scope: Ad click reference\n  period: 7 days\n  text: for up to 7 days on your device ( bt_ad_click )\nresidency:\n- region: Australia\n  text: Your portfolio records and documents are stored on secure servers located in Australia.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Some supporting services process limited data offshore; each one is listed in the sub-processor table below,\n    with the region it operates in where the provider publishes one.\ndpa:\n  available: true\n  url: null\n  text: each bound by a Data Processing Agreement or equivalent contractual terms.\ndeletion:\n  route: Delete Account page in Settings; hard-delete after 30-day grace period\n  text: After the grace period expires, your database records, uploaded documents, and storage objects that remain\n    owned only by your account are permanently deleted.\nrights:\n- right: Access\n  text: Access\
  \ your personal data\n- right: Correct\n  text: Correct inaccurate data\n- right: Delete\n  text: Delete your account and data\n- right: Export\n  text: Export your data as a structured archive, at any time and on every plan, from the Delete Account page in\n    Settings\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/bricktrack-au/privacy/bricktrack-au-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from BrickTrack's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Property Management
- Investment
- Software-as-a-Service
---
