---
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: name, email address, profile photo (from your authentication provider)'
  - category: financial
    text: 'Billing data: subscription tier, transaction history (payment card details are handled by Stripe and not stored by us)'
  - category: device
    text: 'Device data: device type, screen resolution, timezone'
  - category: location
    text: 'Log data: IP address, browser type, operating system, referring URLs, error logs'
  - category: communication
    text: 'Communications: support emails and feedback you send us'
  deletion:
    route: Account deletion or request via support@fabricate.build
    text: You can also ask us to delete the data at support@fabricate.build .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, operate, and improve the Service
    text: Provide, operate, and improve the Service
  - purpose: Process payments and manage subscriptions
    text: Process payments and manage subscriptions
  - purpose: Detect and prevent fraud and abuse
    text: Detect, investigate, and prevent fraud, security incidents, and abuse
  residency:
  - region: United States
    text: We are based in the United States.
  retention:
  - period: 30 days
    scope: Account data
    text: Retained for the lifetime of your account plus 30 days after deletion to enable account recovery.
  - period: 7 years
    scope: Billing records
    text: Retained for 7 years to comply with financial and tax regulations
  - period: 90 days
    scope: Log data
    text: Retained for up to 90 days for security and debugging purposes.
  - period: 2 years
    scope: Analytics data
    text: Retained in aggregated or anonymized form for up to 2 years.
  - period: 1 year
    scope: Email logs
    text: Retained for up to 1 year for deliverability and compliance verification.
  rights:
  - right: Access
    text: Access and download your account data
  - right: Correct
    text: Correct inaccurate information in your account
  - right: Delete
    text: Delete your account and associated data
  - right: Erasure (GDPR)
    text: 'Erasure: Request deletion of your data ("right to be forgotten")'
  - right: Portability (GDPR)
    text: 'Portability: Receive your data in a structured, machine-readable format'
  - right: Objection (GDPR)
    text: 'Objection: Object to processing based on legitimate interests'
  role:
    text: Fabricate ("we," "us," or "our") provides AI-assisted software generation tooling.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: Vendor Purpose Location Stripe Payment processing and subscription management for Fabricate plans
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) approved by the European Commission for transfers to the USA
  - mechanism: DPF
    text: The EU-U.S. Data Privacy Framework for vendors certified thereunder
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Fabricate
provenance_date: '2026-11-09'
provider_name: Fabricate
provider_slug: fabricate-build
slug: fabricate-build-privacy-policy
source_date: '2026-11-09'
source_filename: fabricate-build-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fabricate.build/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fabricate\naid: fabricate-build\nurl: https://fabricate.build/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Fabricate (\"we,\" \"us,\" or \"our\") provides AI-assisted software generation tooling.\ndata_categories:\n- category: identifying\n  text: 'Account data: name, email address, profile photo (from your authentication provider)'\n- category: financial\n  text: 'Billing data: subscription tier, transaction history (payment card details are handled by Stripe and not\n    stored by us)'\n- category: device\n  text: 'Device data: device type, screen resolution, timezone'\n- category:\
  \ location\n  text: 'Log data: IP address, browser type, operating system, referring URLs, error logs'\n- category: communication\n  text: 'Communications: support emails and feedback you send us'\npurposes:\n- purpose: Provide, operate, and improve the Service\n  text: Provide, operate, and improve the Service\n- purpose: Process payments and manage subscriptions\n  text: Process payments and manage subscriptions\n- purpose: Detect and prevent fraud and abuse\n  text: Detect, investigate, and prevent fraud, security incidents, and abuse\nretention:\n- scope: Account data\n  period: 30 days\n  text: Retained for the lifetime of your account plus 30 days after deletion to enable account recovery.\n- scope: Billing records\n  period: 7 years\n  text: Retained for 7 years to comply with financial and tax regulations\n- scope: Log data\n  period: 90 days\n  text: Retained for up to 90 days for security and debugging purposes.\n- scope: Analytics data\n  period: 2 years\n  text: Retained in\
  \ aggregated or anonymized form for up to 2 years.\n- scope: Email logs\n  period: 1 year\n  text: Retained for up to 1 year for deliverability and compliance verification.\nresidency:\n- region: United States\n  text: We are based in the United States.\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) approved by the European Commission for transfers to the USA\n- mechanism: DPF\n  text: The EU-U.S. Data Privacy Framework for vendors certified thereunder\nsubprocessors:\n  url: null\n  text: Vendor Purpose Location Stripe Payment processing and subscription management for Fabricate plans\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion or request via support@fabricate.build\n  text: You can also ask us to delete the data at support@fabricate.build .\nrights:\n- right: Access\n  text: Access and download your account data\n- right: Correct\n  text: Correct inaccurate information in your account\n- right: Delete\n  text:\
  \ Delete your account and associated data\n- right: Erasure (GDPR)\n  text: 'Erasure: Request deletion of your data (\"right to be forgotten\")'\n- right: Portability (GDPR)\n  text: 'Portability: Receive your data in a structured, machine-readable format'\n- right: Objection (GDPR)\n  text: 'Objection: Object to processing based on legitimate interests'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/fabricate-build/privacy/fabricate-build-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Fabricate's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- No-Code
- App Builder
- Cloudflare
- Web Development
---
