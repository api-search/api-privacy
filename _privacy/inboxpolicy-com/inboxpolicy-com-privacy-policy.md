---
api_specs:
- filename: inboxpolicy-com-verification-api-openapi.yml
  format: yaml
  label: inboxpolicy-com Verification API
  slug: inboxpolicy-com-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inboxpolicy-com/openapi/inboxpolicy-com-verification-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: contact
    text: Email addresses you submit for verification.
  - category: identifying
    text: 'Account data: your billing email, hashed API keys (we cannot recover raw keys), and a credit ledger.'
  - category: financial
    text: we see only the public payer wallet address, never card numbers or bank details.
  - category: behavioral
    text: 'Analytics: we use Google Analytics 4 with IP anonymization to understand which pages and features people use, so we can improve the product.'
  deletion:
    route: email hello@inboxpolicy.com
    text: 'Request deletion of any address or your account data: hello@inboxpolicy.com .'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run verification
    text: addresses are used to run the verification
  - purpose: billing and abuse prevention
    text: retained in request logs for up to 90 days for billing and abuse prevention.
  - purpose: product analytics
    text: to understand which pages and features people use, so we can improve the product
  residency:
  - region: EU (Sweden)
    text: Servers are located in the EU (Sweden).
  retention:
  - period: 72 hours
    scope: cached addresses
    text: cached for up to 72 hours (so your re-verification is free)
  - period: 90 days
    scope: request logs
    text: retained in request logs for up to 90 days for billing and abuse prevention
  rights:
  - right: deletion
    text: Request deletion of any address or your account data
  - right: access, rectification, erasure (GDPR)
    text: 'EU/UK data subjects: we support access, rectification, and erasure requests under GDPR.'
  role:
    text: 'We act as a processor: addresses are used to run the verification'
    value: processor
  sale_or_sharing:
    stance: conditional
    text: They are never sold, shared with third parties for marketing, or used to build lists.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: inboxpolicy-com
provenance_date: '2026-11-09'
provider_name: inboxpolicy-com
provider_slug: inboxpolicy-com
slug: inboxpolicy-com-privacy-policy
source_date: '2026-11-09'
source_filename: inboxpolicy-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://inboxpolicy.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: inboxpolicy-com\naid: inboxpolicy-com\nurl: https://inboxpolicy.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: 'We act as a processor: addresses are used to run the verification'\ndata_categories:\n- category: contact\n  text: Email addresses you submit for verification.\n- category: identifying\n  text: 'Account data: your billing email, hashed API keys (we cannot recover raw keys), and a credit ledger.'\n- category: financial\n  text: we see only the public payer wallet address, never card numbers or bank details.\n- category: behavioral\n  text: 'Analytics: we use Google Analytics\
  \ 4 with IP anonymization to understand which pages and features people\n    use, so we can improve the product.'\npurposes:\n- purpose: run verification\n  text: addresses are used to run the verification\n- purpose: billing and abuse prevention\n  text: retained in request logs for up to 90 days for billing and abuse prevention.\n- purpose: product analytics\n  text: to understand which pages and features people use, so we can improve the product\nretention:\n- scope: cached addresses\n  period: 72 hours\n  text: cached for up to 72 hours (so your re-verification is free)\n- scope: request logs\n  period: 90 days\n  text: retained in request logs for up to 90 days for billing and abuse prevention\nresidency:\n- region: EU (Sweden)\n  text: Servers are located in the EU (Sweden).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@inboxpolicy.com\n  text: 'Request deletion of any address or your\
  \ account data: hello@inboxpolicy.com .'\nrights:\n- right: deletion\n  text: Request deletion of any address or your account data\n- right: access, rectification, erasure (GDPR)\n  text: 'EU/UK data subjects: we support access, rectification, and erasure requests under GDPR.'\nsale_or_sharing:\n  stance: conditional\n  text: They are never sold, shared with third parties for marketing, or used to build lists.\n"
source_yaml_url: https://artifacts.apis.io/inboxpolicy-com/privacy/inboxpolicy-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from inboxpolicy-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email Verification
- Artificial Intelligence
- Payments
- Pricing
---
