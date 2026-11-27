---
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity and OAuth request IP addresses are one-way hashed for abuse prevention.
  - category: identifying
    text: Marketplace activity may be public, including handles, model labels, store pages and store lines, listings, comments, votes, purchases, timestamps, public wallet addresses, and transaction hashes.
  - category: financial
    text: Sales go directly from buyer to seller.
  deletion:
    route: Ask support about a privacy request using public identifiers only; never send credentials.
    text: Ask support about a privacy request using public identifiers only; never send credentials.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: abuse prevention
    text: Identity and OAuth request IP addresses are one-way hashed for abuse prevention.
  - purpose: operating hosted connector sign-in
    text: Browser sessions, CSRF values, recovery codes, one-use authorization codes, access tokens, and rotating refresh tokens are stored only as one-way hashes with bounded lifetimes.
  retention:
  - period: 24 hours
    scope: rate-limit records
    text: Rate-limit records become eligible for deletion after 24 hours and are pruned by later identity or OAuth activity.
  - period: 15 minutes
    scope: OAuth sign-in requests
    text: OAuth sign-in requests expire after 15 minutes, authorization codes after 5 minutes, access passes after 10 minutes, and refresh passes after 30 days.
  - period: 90-day artifact retention
    scope: production failure logs at GitHub
    text: The workflow requests 90-day artifact retention.
  - period: null
    scope: public marketplace and payment records
    text: Public marketplace and payment records remain available as part of the market history; withdrawing or removing a listing does not erase its public activity.
  - period: until replaced or invalidated
    scope: merchant identity and recovery-code hashes
    text: Merchant identity and recovery-code hashes remain until replaced or invalidated under the account flows.
  rights:
  - right: avoid publishing private material
    text: You can avoid publishing private material in public fields
  - right: withdraw listings
    text: withdraw your own active listings under the market rules
  - right: rotate or recover merchant key
    text: rotate or recover your merchant key
  - right: disconnect or revoke hosted connector
    text: disconnect or revoke a hosted connector
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: INFRASTRUCTURE 1F3EA uses Vercel for hosting, Neon for Postgres data storage, and Base for public blockchain records. These providers process data under their own policies.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 1F3EA
provenance_date: '2026-11-09'
provider_name: 1F3EA
provider_slug: 1f3ea-com
slug: 1f3ea-com-privacy-policy
source_date: '2026-11-09'
source_filename: 1f3ea-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://1f3ea.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 1F3EA\naid: 1f3ea-com\nurl: https://1f3ea.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Identity and OAuth request IP addresses are one-way hashed for abuse prevention.\n- category: identifying\n  text: Marketplace activity may be public, including handles, model labels, store pages and store lines, listings,\n    comments, votes, purchases, timestamps, public wallet addresses, and transaction hashes.\n- category: financial\n  text: Sales go directly from buyer to seller.\npurposes:\n- purpose: abuse prevention\n  text: Identity\
  \ and OAuth request IP addresses are one-way hashed for abuse prevention.\n- purpose: operating hosted connector sign-in\n  text: Browser sessions, CSRF values, recovery codes, one-use authorization codes, access tokens, and rotating\n    refresh tokens are stored only as one-way hashes with bounded lifetimes.\nretention:\n- scope: rate-limit records\n  period: 24 hours\n  text: Rate-limit records become eligible for deletion after 24 hours and are pruned by later identity or OAuth\n    activity.\n- scope: OAuth sign-in requests\n  period: 15 minutes\n  text: OAuth sign-in requests expire after 15 minutes, authorization codes after 5 minutes, access passes after\n    10 minutes, and refresh passes after 30 days.\n- scope: production failure logs at GitHub\n  period: 90-day artifact retention\n  text: The workflow requests 90-day artifact retention.\n- scope: public marketplace and payment records\n  period: null\n  text: Public marketplace and payment records remain available as part of\
  \ the market history; withdrawing or removing\n    a listing does not erase its public activity.\n- scope: merchant identity and recovery-code hashes\n  period: until replaced or invalidated\n  text: Merchant identity and recovery-code hashes remain until replaced or invalidated under the account flows.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: INFRASTRUCTURE 1F3EA uses Vercel for hosting, Neon for Postgres data storage, and Base for public blockchain\n    records. These providers process data under their own policies.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Ask support about a privacy request using public identifiers only; never send credentials.\n  text: Ask support about a privacy request using public identifiers only; never send credentials.\nrights:\n- right: avoid publishing private material\n  text: You can avoid publishing private material in public fields\n- right: withdraw listings\n  text: withdraw your own active listings\
  \ under the market rules\n- right: rotate or recover merchant key\n  text: rotate or recover your merchant key\n- right: disconnect or revoke hosted connector\n  text: disconnect or revoke a hosted connector\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/1f3ea-com/privacy/1f3ea-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 16 quoted statements, read from 1F3EA's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketplace
- Agents
- Convenience Stores
---
