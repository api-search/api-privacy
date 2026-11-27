---
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address (the account identifier)
  - category: behavioral
    text: call metadata — route, price, latency, status
  - category: device
    text: We log request IPs for rate-limiting and abuse prevention.
  - category: other
    text: When a catalog search finds nothing, we store the search text as a demand signal
  deletion:
    route: POST /v1/support
    text: 'Ask us to delete your account via POST /v1/support: personal identifiers are removed; ledger and audit rows are retained as required financial records, de-linked from you.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: rate-limiting and abuse prevention
    text: We log request IPs for rate-limiting and abuse prevention.
  - purpose: product demand signal
    text: we store the search text as a demand signal
  - purpose: transactional email
    text: Transactional email (receipts, account notices) is sent because you use the service.
  - purpose: marketing email with opt-in
    text: Marketing email is sent only if you ticked the opt-in box at signup
  retention:
  - period: never stored
    scope: Request/response bodies
    text: 'Request/response bodies: never stored, so there is nothing to retain'
  - period: life of the account
    scope: Call metadata, ledger, audit chain
    text: kept for the life of the account; append-only by design.
  - period: within 24 hours
    scope: Rate-limit counters (IPs)
    text: expire automatically within 24 hours.
  - period: until you delete the key or the account
    scope: Vaulted keys
    text: encrypted ciphertext kept until you delete the key or the account.
  - period: within minutes
    scope: One-time links (vault, recovery)
    text: single-use and expire within minutes.
  rights:
  - right: audit chain export
    text: The audit chain for your own account is exportable by you at any time.
  - right: removal of search-miss text
    text: ask via support and yours is removed.
  - right: marketing unsubscribe
    text: every message carries an unsubscribe that works.
  role:
    text: 'Data controller: apifare is operated by its founder as a sole operator pending Hong Kong incorporation'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data, run ads, or use one account's data for another account.
  subprocessors:
    text: Fly.io (hosting), Supabase (database), Stripe (payments), Resend (email delivery), and the upstream API providers
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: apifare-com
provenance_date: '2026-11-09'
provider_name: apifare-com
provider_slug: apifare-com
slug: apifare-com-privacy-policy
source_date: '2026-11-09'
source_filename: apifare-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apifare.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: apifare-com\naid: apifare-com\nurl: https://apifare.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Data controller: apifare is operated by its founder as a sole operator pending Hong Kong incorporation'\ndata_categories:\n- category: identifying\n  text: Your email address (the account identifier)\n- category: behavioral\n  text: call metadata — route, price, latency, status\n- category: device\n  text: We log request IPs for rate-limiting and abuse prevention.\n- category: other\n  text: When a catalog search finds nothing, we store the search text as a demand signal\npurposes:\n\
  - purpose: rate-limiting and abuse prevention\n  text: We log request IPs for rate-limiting and abuse prevention.\n- purpose: product demand signal\n  text: we store the search text as a demand signal\n- purpose: transactional email\n  text: Transactional email (receipts, account notices) is sent because you use the service.\n- purpose: marketing email with opt-in\n  text: Marketing email is sent only if you ticked the opt-in box at signup\nretention:\n- scope: Request/response bodies\n  period: never stored\n  text: 'Request/response bodies: never stored, so there is nothing to retain'\n- scope: Call metadata, ledger, audit chain\n  period: life of the account\n  text: kept for the life of the account; append-only by design.\n- scope: Rate-limit counters (IPs)\n  period: within 24 hours\n  text: expire automatically within 24 hours.\n- scope: Vaulted keys\n  period: until you delete the key or the account\n  text: encrypted ciphertext kept until you delete the key or the account.\n- scope:\
  \ One-time links (vault, recovery)\n  period: within minutes\n  text: single-use and expire within minutes.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Fly.io (hosting), Supabase (database), Stripe (payments), Resend (email delivery), and the upstream API\n    providers\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: POST /v1/support\n  text: 'Ask us to delete your account via POST /v1/support: personal identifiers are removed; ledger and audit\n    rows are retained as required financial records, de-linked from you.'\nrights:\n- right: audit chain export\n  text: The audit chain for your own account is exportable by you at any time.\n- right: removal of search-miss text\n  text: ask via support and yours is removed.\n- right: marketing unsubscribe\n  text: every message carries an unsubscribe that works.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell data, run ads, or use one account's data for another account.\n"
source_yaml_url: https://artifacts.apis.io/apifare-com/privacy/apifare-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from apifare-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Payments
- Prepaid
- Billing
- Agents
---
