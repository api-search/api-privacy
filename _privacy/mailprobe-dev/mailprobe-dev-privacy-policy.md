---
api_specs:
- filename: mailprobe-dev-account-api-openapi.yml
  format: yaml
  label: mailprobe-dev Account API
  slug: mailprobe-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailprobe-dev/openapi/mailprobe-dev-account-api-openapi.yml
- filename: mailprobe-dev-verification-api-openapi.yml
  format: yaml
  label: mailprobe-dev Verification API
  slug: mailprobe-dev-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailprobe-dev/openapi/mailprobe-dev-verification-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address — for authentication (magic link login)
  - category: identifying
    text: IP address at registration — for anti-abuse (max 3 accounts per IP)
  - category: device
    text: API keys — stored as a SHA-256 hash only (we cannot read your keys)
  - category: financial
    text: Credit balance and purchase history
  - category: communication
    text: 'Server logs: standard web server logs, not shared or exploited'
  deletion:
    route: Settings → Delete account in your account
    text: 'Deletion is self-service and immediate : Settings → Delete account in your account.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authentication
    text: We use a single httpOnly session cookie (mp_session) for authentication.
  - purpose: anti-abuse
    text: IP address at registration — for anti-abuse (max 3 accounts per IP)
  - purpose: service quality monitoring
    text: This data is used exclusively for internal monitoring and has no commercial purpose.
  - purpose: payment processing
    text: Stripe — payment processing. Stripe handles all card data.
  retention:
  - period: as long as your account exists
    scope: Account data
    text: 'Account data: kept as long as your account exists'
  - period: null
    scope: API verification data
    text: 'API verification data: not stored, processed in real time only'
  - period: 24 hours after the batch finishes
    scope: Batch lists and results
    text: 'Batch lists and results: deleted 24 hours after the batch finishes'
  - period: up to 90 days
    scope: Operational metrics
    text: 'Operational metrics: aggregated technical logs (no email addresses), up to 90 days'
  rights:
  - right: access
    text: You have the right to access, rectify, or delete your personal data.
  - right: rectification
    text: 'Rectification is self-service : Settings → Email address in your account.'
  - right: deletion
    text: 'Deletion is self-service and immediate : Settings → Delete account in your account.'
  role:
    text: Data Controller Iris Digital , SIREN 524 317 872, France
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Nothing is kept beyond that window, resold, or used to build a list.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: mailprobe-dev
provenance_date: '2026-11-10'
provider_name: mailprobe-dev
provider_slug: mailprobe-dev
slug: mailprobe-dev-privacy-policy
source_date: '2026-11-10'
source_filename: mailprobe-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mailprobe.dev/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: mailprobe-dev\naid: mailprobe-dev\nurl: https://mailprobe.dev/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Data Controller Iris Digital , SIREN 524 317 872, France\ndata_categories:\n- category: contact\n  text: Email address — for authentication (magic link login)\n- category: identifying\n  text: IP address at registration — for anti-abuse (max 3 accounts per IP)\n- category: device\n  text: API keys — stored as a SHA-256 hash only (we cannot read your keys)\n- category: financial\n  text: Credit balance and purchase history\n- category: communication\n  text: 'Server logs: standard\
  \ web server logs, not shared or exploited'\npurposes:\n- purpose: authentication\n  text: We use a single httpOnly session cookie (mp_session) for authentication.\n- purpose: anti-abuse\n  text: IP address at registration — for anti-abuse (max 3 accounts per IP)\n- purpose: service quality monitoring\n  text: This data is used exclusively for internal monitoring and has no commercial purpose.\n- purpose: payment processing\n  text: Stripe — payment processing. Stripe handles all card data.\nretention:\n- scope: Account data\n  period: as long as your account exists\n  text: 'Account data: kept as long as your account exists'\n- scope: API verification data\n  period: null\n  text: 'API verification data: not stored, processed in real time only'\n- scope: Batch lists and results\n  period: 24 hours after the batch finishes\n  text: 'Batch lists and results: deleted 24 hours after the batch finishes'\n- scope: Operational metrics\n  period: up to 90 days\n  text: 'Operational metrics: aggregated\
  \ technical logs (no email addresses), up to 90 days'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings → Delete account in your account\n  text: 'Deletion is self-service and immediate : Settings → Delete account in your account.'\nrights:\n- right: access\n  text: You have the right to access, rectify, or delete your personal data.\n- right: rectification\n  text: 'Rectification is self-service : Settings → Email address in your account.'\n- right: deletion\n  text: 'Deletion is self-service and immediate : Settings → Delete account in your account.'\nsale_or_sharing:\n  stance: conditional\n  text: Nothing is kept beyond that window, resold, or used to build a list.\n"
source_yaml_url: https://artifacts.apis.io/mailprobe-dev/privacy/mailprobe-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from mailprobe-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email Verification
- Real-Time
- Developer Tools
---
