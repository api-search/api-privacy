---
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Authorization tokens: Apps verify platform session tokens to authenticate requests.'
  - category: financial
    text: We do not receive or store card numbers.
  - category: other
    text: Transient media buffers necessary to complete user requests (like zipping documents or routing contracts).
  deletion:
    route: uninstall app or verified shop erasure
    text: Uninstalling the app deletes the shop configuration; reinstall starts from onboarding with nothing restored.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: app stability
    text: Minimal telemetry or error reporting logs to ensure app stability.
  - purpose: grant or revoke access
    text: We receive payment, customer, and subscription identifiers through signed webhooks to grant or revoke access.
  retention:
  - period: 31 days
    scope: CountSafe completed webhook delivery and lifecycle records
    text: completed delivery and lifecycle records are retained for at most 31 days.
  - period: 7 days
    scope: Location Guard webhook delivery receipts
    text: Webhook delivery receipts expire after 7 days.
  - period: 365-day
    scope: Fulfillment Lens reports, history, audit records and webhook receipts
    text: Reports, quantity history, audit records and webhook receipts have a configured 365-day retention.
  - period: 30 days
    scope: Location Guard D1 recovery copies
    text: Cloudflare D1 recovery copies may retain deleted data for up to 30 days
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The services below support our websites and apps.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: cazimedia-com
provenance_date: '2026-11-09'
provider_name: cazimedia-com
provider_slug: cazimedia-com
slug: cazimedia-com-privacy-policy
source_date: '2026-11-09'
source_filename: cazimedia-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cazimedia.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: cazimedia-com\naid: cazimedia-com\nurl: https://cazimedia.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Authorization tokens: Apps verify platform session tokens to authenticate requests.'\n- category: financial\n  text: We do not receive or store card numbers.\n- category: other\n  text: Transient media buffers necessary to complete user requests (like zipping documents or routing contracts).\npurposes:\n- purpose: app stability\n  text: Minimal telemetry or error reporting logs to ensure app stability.\n- purpose: grant\
  \ or revoke access\n  text: We receive payment, customer, and subscription identifiers through signed webhooks to grant or revoke access.\nretention:\n- scope: CountSafe completed webhook delivery and lifecycle records\n  period: 31 days\n  text: completed delivery and lifecycle records are retained for at most 31 days.\n- scope: Location Guard webhook delivery receipts\n  period: 7 days\n  text: Webhook delivery receipts expire after 7 days.\n- scope: Fulfillment Lens reports, history, audit records and webhook receipts\n  period: 365-day\n  text: Reports, quantity history, audit records and webhook receipts have a configured 365-day retention.\n- scope: Location Guard D1 recovery copies\n  period: 30 days\n  text: Cloudflare D1 recovery copies may retain deleted data for up to 30 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: The services below support our websites and apps.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: uninstall app\
  \ or verified shop erasure\n  text: Uninstalling the app deletes the shop configuration; reinstall starts from onboarding with nothing restored.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cazimedia-com/privacy/cazimedia-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
summary_line: 11 quoted statements, read from cazimedia-com's own page on 2026-11-09.
synthetic: false
tags:
- Application
- Integration
- Productivity
- Shopify
- Monday.com
---
