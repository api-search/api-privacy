---
api_specs:
- filename: catalystedgescanner-com-openapi-generated.yml
  format: yaml
  label: Catalyst Edge API
  slug: catalystedgescanner-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/catalystedgescanner-com/openapi/_ae-authored/catalystedgescanner-com-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address — for login, Stripe receipts, and the optional newsletter.
  - category: behavioral
    text: Product analytics (first-party) — an anonymous session identifier, pages viewed, and signup-funnel steps, stored on our own servers.
  - category: financial
    text: Stripe customer ID — billing reference; we never see your card number.
  - category: device
    text: Server logs — IP, User-Agent, request path, timestamp.
  - category: identifying
    text: API key — bcrypt-hashed at rest, rotatable any time.
  deletion:
    route: email
    text: Deletion — request permanent deletion of your account and associated data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authentication
    text: Authentication — to know you are you.
  - purpose: Billing
    text: Billing — to keep your subscription active via Stripe.
  - purpose: Abuse prevention
    text: Abuse prevention — so a single bad actor doesn't degrade the service for everyone else.
  - purpose: Product improvement
    text: Used only to measure and improve the product; never sold or shared.
  residency:
  - region: United States
    text: Our servers are located in the United States (DigitalOcean, NYC region).
  retention:
  - period: 30 days
    scope: Server logs
    text: Server logs — rotated and deleted after 30 days
  - period: 90 days
    scope: Post-cancellation account data
    text: Post-cancellation — retained for 90 days in case of accidental cancellation or audit, then permanently deleted.
  - period: until you unsubscribe
    scope: Newsletter list
    text: Newsletter list — until you unsubscribe.
  - period: 7 days
    scope: Newsletter address after unsubscribe
    text: Unsubscribe purges your address within 7 days.
  rights:
  - right: Access
    text: Access — request a copy of all data we hold on you.
  - right: Deletion
    text: Deletion — request permanent deletion of your account and associated data.
  - right: Export
    text: Export — request a machine-readable export (JSON) of your account data.
  - right: Rectification
    text: Rectification — correct inaccurate data we hold.
  - right: Object / restrict
    text: Object / restrict — limit processing of your data.
  - right: Withdraw consent
    text: Withdraw consent — for the newsletter at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, license, or share your data with anyone for marketing or any other purpose, ever.
  subprocessors:
    text: We use a small, named set of processors for primary operations
    url: null
  transfers:
  - mechanism: SCC
    text: If you are in the EU/EEA or UK, your data is transferred to the US under the Standard Contractual Clauses (SCCs) approved by the European Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Catalyst Edge
provenance_date: '2026-11-09'
provider_name: Catalyst Edge
provider_slug: catalystedgescanner-com
slug: catalystedgescanner-com-privacy-policy
source_date: '2026-11-09'
source_filename: catalystedgescanner-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://catalystedgescanner.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Catalyst Edge\naid: catalystedgescanner-com\nurl: https://catalystedgescanner.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email address — for login, Stripe receipts, and the optional newsletter.\n- category: behavioral\n  text: Product analytics (first-party) — an anonymous session identifier, pages viewed, and signup-funnel steps,\n    stored on our own servers.\n- category: financial\n  text: Stripe customer ID — billing reference; we never see your card number.\n- category: device\n  text: Server logs — IP, User-Agent, request\
  \ path, timestamp.\n- category: identifying\n  text: API key — bcrypt-hashed at rest, rotatable any time.\npurposes:\n- purpose: Authentication\n  text: Authentication — to know you are you.\n- purpose: Billing\n  text: Billing — to keep your subscription active via Stripe.\n- purpose: Abuse prevention\n  text: Abuse prevention — so a single bad actor doesn't degrade the service for everyone else.\n- purpose: Product improvement\n  text: Used only to measure and improve the product; never sold or shared.\nretention:\n- scope: Server logs\n  period: 30 days\n  text: Server logs — rotated and deleted after 30 days\n- scope: Post-cancellation account data\n  period: 90 days\n  text: Post-cancellation — retained for 90 days in case of accidental cancellation or audit, then permanently deleted.\n- scope: Newsletter list\n  period: until you unsubscribe\n  text: Newsletter list — until you unsubscribe.\n- scope: Newsletter address after unsubscribe\n  period: 7 days\n  text: Unsubscribe purges\
  \ your address within 7 days.\nresidency:\n- region: United States\n  text: Our servers are located in the United States (DigitalOcean, NYC region).\ntransfers:\n- mechanism: SCC\n  text: If you are in the EU/EEA or UK, your data is transferred to the US under the Standard Contractual Clauses\n    (SCCs) approved by the European Commission.\nsubprocessors:\n  url: null\n  text: We use a small, named set of processors for primary operations\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email\n  text: Deletion — request permanent deletion of your account and associated data.\nrights:\n- right: Access\n  text: Access — request a copy of all data we hold on you.\n- right: Deletion\n  text: Deletion — request permanent deletion of your account and associated data.\n- right: Export\n  text: Export — request a machine-readable export (JSON) of your account data.\n- right: Rectification\n  text: Rectification — correct inaccurate data we hold.\n- right: Object / restrict\n\
  \  text: Object / restrict — limit processing of your data.\n- right: Withdraw consent\n  text: Withdraw consent — for the newsletter at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, license, or share your data with anyone for marketing or any other purpose, ever.\n"
source_yaml_url: https://artifacts.apis.io/catalystedgescanner-com/privacy/catalystedgescanner-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Catalyst Edge's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- SEC
- Market Data
- Analytics
- Platform
---
