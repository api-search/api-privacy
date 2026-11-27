---
api_specs:
- filename: filingfirehose-com-billing-api-openapi.yml
  format: yaml
  label: filingfirehose-com Billing API
  slug: filingfirehose-com-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filingfirehose-com/openapi/filingfirehose-com-billing-api-openapi.yml
- filename: filingfirehose-com-filings-api-openapi.yml
  format: yaml
  label: filingfirehose-com Filings API
  slug: filingfirehose-com-filings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filingfirehose-com/openapi/filingfirehose-com-filings-api-openapi.yml
- filename: filingfirehose-com-meta-api-openapi.yml
  format: yaml
  label: filingfirehose-com Meta API
  slug: filingfirehose-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filingfirehose-com/openapi/filingfirehose-com-meta-api-openapi.yml
- filename: filingfirehose-com-public-api-openapi.yml
  format: yaml
  label: filingfirehose-com Public API
  slug: filingfirehose-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/filingfirehose-com/openapi/filingfirehose-com-public-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: your email address (for account / API key delivery)
  - category: identifying
    text: your IP address (for rate limiting and analytics)
  - category: financial
    text: payment information (handled by Stripe, not stored on our servers)
  - category: behavioral
    text: API request metadata — endpoint, query parameters, response size, timestamp.
  deletion:
    route: email to info@filingfirehose.com
    text: Deletion — delete your account and associated data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account creation and API key delivery
    text: for account creation, API key delivery, service updates (welcome, trial expiry, billing)
  - purpose: rate limiting and analytics
    text: for per-IP rate limiting on the free tier and aggregate analytics
  - purpose: usage-based billing and debugging
    text: Used for usage-based billing on metered tiers and for debugging service issues.
  - purpose: trial abuse prevention
    text: stored to prevent trial abuse (one trial per email address)
  residency:
  - region: United States
    text: Hosting is in U.S. data centers (Fly.io, IAD region).
  retention:
  - period: 90 days after deletion
    scope: account data
    text: Account data — for the lifetime of your account, plus 90 days after deletion
  - period: 90 days
    scope: API request logs
    text: API request logs — 90 days
  - period: 90 days
    scope: pageview / analytics logs
    text: Pageview / analytics logs — 90 days
  - period: 60 days
    scope: email delivery logs
    text: Email delivery logs (welcome, trial, etc.) — 60 days, then deleted
  rights:
  - right: Access
    text: Access — receive a copy of all data we hold about you
  - right: Deletion
    text: Deletion — delete your account and associated data
  - right: Portability
    text: Portability — receive your data in machine-readable format (JSON)
  - right: Correction
    text: Correction — fix inaccurate data we hold about you
  - right: Opt-out
    text: Opt-out — unsubscribe from non-essential emails (one click in any email)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data to third parties.
  subprocessors:
    text: Stripe — payment processing
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: filingfirehose-com
provenance_date: '2026-11-09'
provider_name: filingfirehose-com
provider_slug: filingfirehose-com
slug: filingfirehose-com-privacy-policy
source_date: '2026-11-09'
source_filename: filingfirehose-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://filingfirehose.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: filingfirehose-com\naid: filingfirehose-com\nurl: https://filingfirehose.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: your email address (for account / API key delivery)\n- category: identifying\n  text: your IP address (for rate limiting and analytics)\n- category: financial\n  text: payment information (handled by Stripe, not stored on our servers)\n- category: behavioral\n  text: API request metadata — endpoint, query parameters, response size, timestamp.\npurposes:\n- purpose: account creation and API key delivery\n  text:\
  \ for account creation, API key delivery, service updates (welcome, trial expiry, billing)\n- purpose: rate limiting and analytics\n  text: for per-IP rate limiting on the free tier and aggregate analytics\n- purpose: usage-based billing and debugging\n  text: Used for usage-based billing on metered tiers and for debugging service issues.\n- purpose: trial abuse prevention\n  text: stored to prevent trial abuse (one trial per email address)\nretention:\n- scope: account data\n  period: 90 days after deletion\n  text: Account data — for the lifetime of your account, plus 90 days after deletion\n- scope: API request logs\n  period: 90 days\n  text: API request logs — 90 days\n- scope: pageview / analytics logs\n  period: 90 days\n  text: Pageview / analytics logs — 90 days\n- scope: email delivery logs\n  period: 60 days\n  text: Email delivery logs (welcome, trial, etc.) — 60 days, then deleted\nresidency:\n- region: United States\n  text: Hosting is in U.S. data centers (Fly.io, IAD region).\n\
  transfers: []\nsubprocessors:\n  url: null\n  text: Stripe — payment processing\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to info@filingfirehose.com\n  text: Deletion — delete your account and associated data\nrights:\n- right: Access\n  text: Access — receive a copy of all data we hold about you\n- right: Deletion\n  text: Deletion — delete your account and associated data\n- right: Portability\n  text: Portability — receive your data in machine-readable format (JSON)\n- right: Correction\n  text: Correction — fix inaccurate data we hold about you\n- right: Opt-out\n  text: Opt-out — unsubscribe from non-essential emails (one click in any email)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/filingfirehose-com/privacy/filingfirehose-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from filingfirehose-com's own page on 2026-11-09.
synthetic: false
tags:
- SEC
- EDGAR
- Finance
- Data API
- JSON
---
