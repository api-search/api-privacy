---
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (via Supabase Auth — email or Google OAuth)
  - category: financial
    text: Subscription tier and payment method
  - category: financial
    text: transaction signature and wallet address (verified on-chain via Solana)
  - category: contact
    text: Telegram chat ID, Discord webhook URL, SMS phone number
  - category: device
    text: Your DrainBrain API key (stored locally in chrome.storage.local)
  - category: behavioral
    text: Token mint addresses extracted from DEX pages you visit
  - category: device
    text: HMAC-hashed IP addresses (not stored in plaintext) for rate limiting
  deletion:
    route: Settings page or DELETE /api/account/delete; or email j@rugslayer.com
    text: 'Delete your account — Settings page or DELETE /api/account/delete. This cascades: cancels Stripe subscription, deletes all database records, clears Redis cache, and removes your auth account'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Generate risk scores
    text: Generate risk scores for requested token scans
  - purpose: Improve risk score
    text: Measure and improve the risk score using aggregated, anonymized scan data and token outcomes
  - purpose: Rate limiting and abuse prevention
    text: Enforce rate limits and prevent abuse
  - purpose: Subscription payments
    text: Process subscription payments
  - purpose: Alerts
    text: Send alerts via your configured notification channels
  residency:
  - region: US East
    text: Supabase — database and authentication (US East region)
  - region: Ashburn, VA
    text: Hetzner Cloud — hosting and serverless functions (Ashburn, VA)
  retention:
  - period: 90 days
    scope: Scan history
    text: 'Scan history: 90 days, then automatically deleted'
  - period: 90 days
    scope: Read alerts
    text: 'Read alerts: 90 days, then automatically deleted'
  - period: 1 year
    scope: Accuracy logs
    text: 'Accuracy logs: 1 year, then automatically deleted'
  - period: 5-minute TTL
    scope: Extension local cache
    text: 'Extension local cache: 5-minute TTL, automatically cleared'
  rights:
  - right: Deletion
    text: Delete your account — Settings page or DELETE /api/account/delete.
  - right: Export
    text: Export your data — contact j@rugslayer.com for a data export
  - right: Revoke API keys
    text: Revoke API keys — via the DrainBrain dashboard or API
  - right: Disconnect wallet
    text: Disconnect wallet — via Settings page
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: rugslayer-com
provenance_date: '2026-11-10'
provider_name: rugslayer-com
provider_slug: rugslayer-com
slug: rugslayer-com-privacy-policy
source_date: '2026-11-10'
source_filename: rugslayer-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://rugslayer.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: rugslayer-com\naid: rugslayer-com\nurl: https://rugslayer.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address (via Supabase Auth — email or Google OAuth)\n- category: financial\n  text: Subscription tier and payment method\n- category: financial\n  text: transaction signature and wallet address (verified on-chain via Solana)\n- category: contact\n  text: Telegram chat ID, Discord webhook URL, SMS phone number\n- category: device\n  text: Your DrainBrain API key (stored locally in chrome.storage.local)\n- category:\
  \ behavioral\n  text: Token mint addresses extracted from DEX pages you visit\n- category: device\n  text: HMAC-hashed IP addresses (not stored in plaintext) for rate limiting\npurposes:\n- purpose: Generate risk scores\n  text: Generate risk scores for requested token scans\n- purpose: Improve risk score\n  text: Measure and improve the risk score using aggregated, anonymized scan data and token outcomes\n- purpose: Rate limiting and abuse prevention\n  text: Enforce rate limits and prevent abuse\n- purpose: Subscription payments\n  text: Process subscription payments\n- purpose: Alerts\n  text: Send alerts via your configured notification channels\nretention:\n- scope: Scan history\n  period: 90 days\n  text: 'Scan history: 90 days, then automatically deleted'\n- scope: Read alerts\n  period: 90 days\n  text: 'Read alerts: 90 days, then automatically deleted'\n- scope: Accuracy logs\n  period: 1 year\n  text: 'Accuracy logs: 1 year, then automatically deleted'\n- scope: Extension local\
  \ cache\n  period: 5-minute TTL\n  text: 'Extension local cache: 5-minute TTL, automatically cleared'\nresidency:\n- region: US East\n  text: Supabase — database and authentication (US East region)\n- region: Ashburn, VA\n  text: Hetzner Cloud — hosting and serverless functions (Ashburn, VA)\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings page or DELETE /api/account/delete; or email j@rugslayer.com\n  text: 'Delete your account — Settings page or DELETE /api/account/delete. This cascades: cancels Stripe subscription,\n    deletes all database records, clears Redis cache, and removes your auth account'\nrights:\n- right: Deletion\n  text: Delete your account — Settings page or DELETE /api/account/delete.\n- right: Export\n  text: Export your data — contact j@rugslayer.com for a data export\n- right: Revoke API keys\n  text: Revoke API keys — via the DrainBrain dashboard or API\n- right: Disconnect\
  \ wallet\n  text: Disconnect wallet — via Settings page\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rugslayer-com/privacy/rugslayer-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 23 quoted statements, read from rugslayer-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Solana
- Security
- Cryptocurrency
- Risk-Scanner
---
