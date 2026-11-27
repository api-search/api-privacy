---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, hashed password, OAuth provider (GitHub, Google, etc.)
  - category: financial
    text: Billing details (Pro/Enterprise plans) processed by Stripe.
  - category: communication
    text: Email metadata (sender, recipient, subject, timestamp).
  - category: behavioral
    text: we use cookies to monitor usage across our websites
  deletion:
    route: Account deletion
    text: Retained until account deletion with a 30 days grace period.
  dpa:
    available: true
    text: 'Cloudflare: Infrastructure providers ( Cloudflare DPA ). Turso: Database provider ( Turso DPA ).'
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: Provide and maintain the Service (e.g., forwarding emails).
  - purpose: Authenticate accounts and process payments
    text: Authenticate accounts and process payments (Pro/Enterprise).
  - purpose: Investigate abuse or violations
    text: Investigate abuse or violations of our Terms of Service.
  residency:
  - region: EU
    text: Data is processed in the EU (Turso, Cloudflare) and the US (Stripe, GitHub).
  - region: US
    text: Data is processed in the EU (Turso, Cloudflare) and the US (Stripe, GitHub).
  retention:
  - period: 30 days grace period
    scope: Account data
    text: Retained until account deletion with a 30 days grace period.
  - period: 30 days (Free) / 90 days (Pro)
    scope: Email metadata logs
    text: 'Email Metadata Logs: 30 days (Free) / 90 days (Pro).'
  - period: 7 years
    scope: Billing records
    text: 'Billing Records: 7 years (to comply with French tax laws).'
  rights:
  - right: Access
    text: Access to your personal data.
  - right: Correction or deletion
    text: Correction or deletion of inaccurate data.
  - right: Export
    text: Export of your data in a portable format.
  - right: Restriction or objection
    text: Restriction of processing or objection.
  role:
    text: The data controller for the hosted service at app.owlrelay.email is Corentin Thomasset (French micro-entrepreneur)
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell your data .
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: GDPR adequacy decisions (e.g., EU-U.S. Data Privacy Framework).
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: OwlRelay
provenance_date: '2026-11-10'
provider_name: OwlRelay
provider_slug: owlrelay
slug: owlrelay-privacy-policy
source_date: '2026-11-10'
source_filename: owlrelay-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://owlrelay.email/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: OwlRelay\naid: owlrelay\nurl: https://owlrelay.email/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller for the hosted service at app.owlrelay.email is Corentin Thomasset (French micro-entrepreneur)\ndata_categories:\n- category: identifying\n  text: Email address, hashed password, OAuth provider (GitHub, Google, etc.)\n- category: financial\n  text: Billing details (Pro/Enterprise plans) processed by Stripe.\n- category: communication\n  text: Email metadata (sender, recipient, subject, timestamp).\n- category: behavioral\n  text: we use cookies to monitor usage across\
  \ our websites\npurposes:\n- purpose: Provide and maintain the Service\n  text: Provide and maintain the Service (e.g., forwarding emails).\n- purpose: Authenticate accounts and process payments\n  text: Authenticate accounts and process payments (Pro/Enterprise).\n- purpose: Investigate abuse or violations\n  text: Investigate abuse or violations of our Terms of Service.\nretention:\n- scope: Account data\n  period: 30 days grace period\n  text: Retained until account deletion with a 30 days grace period.\n- scope: Email metadata logs\n  period: 30 days (Free) / 90 days (Pro)\n  text: 'Email Metadata Logs: 30 days (Free) / 90 days (Pro).'\n- scope: Billing records\n  period: 7 years\n  text: 'Billing Records: 7 years (to comply with French tax laws).'\nresidency:\n- region: EU\n  text: Data is processed in the EU (Turso, Cloudflare) and the US (Stripe, GitHub).\n- region: US\n  text: Data is processed in the EU (Turso, Cloudflare) and the US (Stripe, GitHub).\ntransfers:\n- mechanism:\
  \ DPF\n  text: GDPR adequacy decisions (e.g., EU-U.S. Data Privacy Framework).\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs).\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: 'Cloudflare: Infrastructure providers ( Cloudflare DPA ). Turso: Database provider ( Turso DPA ).'\ndeletion:\n  route: Account deletion\n  text: Retained until account deletion with a 30 days grace period.\nrights:\n- right: Access\n  text: Access to your personal data.\n- right: Correction or deletion\n  text: Correction or deletion of inaccurate data.\n- right: Export\n  text: Export of your data in a portable format.\n- right: Restriction or objection\n  text: Restriction of processing or objection.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your data .\n"
source_yaml_url: https://artifacts.apis.io/owlrelay/privacy/owlrelay-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from OwlRelay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email
- Webhook
- Open Source
- Automation
---
