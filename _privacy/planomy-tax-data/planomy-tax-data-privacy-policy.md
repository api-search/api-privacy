---
api_specs:
- filename: planomy-tax-data-tax-data-api-openapi.yml
  format: yaml
  label: Planomy Tax Data Tax Data API
  slug: planomy-tax-data-tax-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/planomy-tax-data/openapi/planomy-tax-data-tax-data-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: Supabase stores account information such as your user id, email address, profile fields, entitlement row, and encrypted planner blobs.
  - category: financial
    text: Through Plaid we receive account metadata, balances, and transactions for the accounts you authorize
  - category: behavioral
    text: Supabase may also store operational logs needed to provide and secure the service.
  deletion:
    route: Account deletion in the app, or email to support@planomy.net
    text: Deleting your account cancels any active Stripe subscription server-side and then removes your cloud data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide planning features
    text: used only to power planning features such as comparing your plan against actual activity
  - purpose: payment processing
    text: Stripe processes payments, subscriptions, invoices, taxes, and billing portal sessions.
  retention:
  - period: 35 days
    scope: encrypted backups after deletion
    text: residual copies in encrypted backups expire within 35 days
  - period: 30 days
    scope: deletion requests sent by email
    text: Deletion requests sent by email are honored within 30 days.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal planner data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Planomy Tax Data
provenance_date: '2026-11-10'
provider_name: Planomy Tax Data
provider_slug: planomy-tax-data
slug: planomy-tax-data-privacy-policy
source_date: '2026-11-10'
source_filename: planomy-tax-data-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://planomy.net/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Planomy Tax Data\naid: planomy-tax-data\nurl: https://planomy.net/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Supabase stores account information such as your user id, email address, profile fields, entitlement row,\n    and encrypted planner blobs.\n- category: financial\n  text: Through Plaid we receive account metadata, balances, and transactions for the accounts you authorize\n- category: behavioral\n  text: Supabase may also store operational logs needed to provide and secure the service.\npurposes:\n- purpose: provide\
  \ planning features\n  text: used only to power planning features such as comparing your plan against actual activity\n- purpose: payment processing\n  text: Stripe processes payments, subscriptions, invoices, taxes, and billing portal sessions.\nretention:\n- scope: encrypted backups after deletion\n  period: 35 days\n  text: residual copies in encrypted backups expire within 35 days\n- scope: deletion requests sent by email\n  period: 30 days\n  text: Deletion requests sent by email are honored within 30 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion in the app, or email to support@planomy.net\n  text: Deleting your account cancels any active Stripe subscription server-side and then removes your cloud data\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal planner data.\n"
source_yaml_url: https://artifacts.apis.io/planomy-tax-data/privacy/planomy-tax-data-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 9 quoted statements, read from Planomy Tax Data's own page on 2026-11-10.
synthetic: false
tags:
- Tax
- Finance
- Open Data
- Retirement
- Government
- Personal Finance
- IRS
- Social Security
- Medicare
- JSON
---
