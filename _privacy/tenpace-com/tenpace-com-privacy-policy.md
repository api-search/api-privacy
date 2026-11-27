---
api_specs:
- filename: tenpace-com-review-router-setup-api-openapi.yml
  format: yaml
  label: tenpace-com Review Router setup API
  slug: tenpace-com-review-router-setup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tenpace-com/openapi/tenpace-com-review-router-setup-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'GitHub: Username, display name, email address, avatar URL, and organization memberships'
  - category: financial
    text: Stripe processes your payment method and provides us with customer, subscription, invoice, payment status, billing contact, tax, refund, and dispute information needed to operate billing.
  - category: health
    text: we process the information you choose to provide, such as workouts, food and nutrition entries, body measurements, goals, routines, available equipment, dietary preferences, and limitations.
  - category: behavioral
    text: we store a pseudonymous browser identifier, public page path, visit time, campaign tags you arrived with, and the referring site's hostname.
  - category: device
    text: We process technical request information, such as IP address and browser type, when needed to secure and operate the Service.
  - category: communication
    text: Pull request metadata (title, description, author, reviewers, status, labels)
  deletion:
    route: Export or delete Health data from within the product; account deletion
    text: Health users can export or delete their Health data directly from the product
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: To provide and maintain the Service
  - purpose: Process payments and billing
    text: To process trials, subscriptions, cancellations, taxes, invoices, and referral credits
  - purpose: Customer support
    text: To provide customer support
  - purpose: Marketing measurement
    text: To understand which campaigns lead to product entry, activation, paid plans, and recurring product use
  retention:
  - period: as long as your account is active
    scope: Account information
    text: We retain your account information and associated data for as long as your account is active.
  - period: within 30 days after deletion
    scope: Encrypted backup copies of Health data
    text: encrypted backup copies expire within 30 days after deletion.
  - period: null
    scope: Transaction, invoice, tax, credit-ledger, and anti-fraud records
    text: We retain transaction, invoice, tax, credit-ledger, and anti-fraud records for as long as reasonably needed for accounting, legal, dispute, and compliance purposes, even after a subscription or account ends.
  - period: 90 days
    scope: Anonymous first-party marketing visits
    text: Anonymous first-party marketing visits that have not been linked to a product account are deleted after 90 days.
  rights:
  - right: Access
    text: Access the personal information we hold about you
  - right: Correction
    text: Request correction of inaccurate data
  - right: Deletion
    text: Request deletion of your data
  - right: Export
    text: Export your data
  - right: Disconnect integrations
    text: Disconnect third-party integrations (GitHub, Slack, Google) at any time
  - right: Withdraw consent
    text: Withdraw consent for optional product communications at any time
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, trade, or rent your personal information to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tenpace-com
provenance_date: '2026-11-10'
provider_name: tenpace-com
provider_slug: tenpace-com
slug: tenpace-com-privacy-policy
source_date: '2026-11-10'
source_filename: tenpace-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tenpace.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tenpace-com\naid: tenpace-com\nurl: https://tenpace.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'GitHub: Username, display name, email address, avatar URL, and organization memberships'\n- category: financial\n  text: Stripe processes your payment method and provides us with customer, subscription, invoice, payment status,\n    billing contact, tax, refund, and dispute information needed to operate billing.\n- category: health\n  text: we process the information you choose to provide, such as workouts, food and nutrition\
  \ entries, body measurements,\n    goals, routines, available equipment, dietary preferences, and limitations.\n- category: behavioral\n  text: we store a pseudonymous browser identifier, public page path, visit time, campaign tags you arrived with,\n    and the referring site's hostname.\n- category: device\n  text: We process technical request information, such as IP address and browser type, when needed to secure and\n    operate the Service.\n- category: communication\n  text: Pull request metadata (title, description, author, reviewers, status, labels)\npurposes:\n- purpose: Provide and maintain the Service\n  text: To provide and maintain the Service\n- purpose: Process payments and billing\n  text: To process trials, subscriptions, cancellations, taxes, invoices, and referral credits\n- purpose: Customer support\n  text: To provide customer support\n- purpose: Marketing measurement\n  text: To understand which campaigns lead to product entry, activation, paid plans, and recurring\
  \ product use\nretention:\n- scope: Account information\n  period: as long as your account is active\n  text: We retain your account information and associated data for as long as your account is active.\n- scope: Encrypted backup copies of Health data\n  period: within 30 days after deletion\n  text: encrypted backup copies expire within 30 days after deletion.\n- scope: Transaction, invoice, tax, credit-ledger, and anti-fraud records\n  period: null\n  text: We retain transaction, invoice, tax, credit-ledger, and anti-fraud records for as long as reasonably needed\n    for accounting, legal, dispute, and compliance purposes, even after a subscription or account ends.\n- scope: Anonymous first-party marketing visits\n  period: 90 days\n  text: Anonymous first-party marketing visits that have not been linked to a product account are deleted after\n    90 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\n\
  deletion:\n  route: Export or delete Health data from within the product; account deletion\n  text: Health users can export or delete their Health data directly from the product\nrights:\n- right: Access\n  text: Access the personal information we hold about you\n- right: Correction\n  text: Request correction of inaccurate data\n- right: Deletion\n  text: Request deletion of your data\n- right: Export\n  text: Export your data\n- right: Disconnect integrations\n  text: Disconnect third-party integrations (GitHub, Slack, Google) at any time\n- right: Withdraw consent\n  text: Withdraw consent for optional product communications at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, trade, or rent your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/tenpace-com/privacy/tenpace-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from tenpace-com's own page on 2026-11-10.
synthetic: false
tags:
- Health
- Software-as-a-Service
- Productivity
- Workflows
- Integration
- Company
---
