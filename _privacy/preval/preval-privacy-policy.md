---
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Name, email address, and authentication credentials (via Auth0)'
  - category: behavioral
    text: 'Usage Data: Feature usage patterns, page views, and API call frequency for service improvement'
  - category: communication
    text: 'Trace Data: LLM call inputs/outputs, latency metrics, token counts, cost data, and tool execution logs sent via our SDK or OTLP ingestion'
  - category: other
    text: 'API Keys (BYOK): Third-party API keys you provide, stored encrypted at rest'
  deletion:
    route: Request by contacting us
    text: You can request data export or deletion at any time by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain and improve the Service
    text: To provide, maintain, and improve the Service
  - purpose: Process traces and generate evaluations
    text: To process traces and generate evaluations and analytics
  - purpose: Authentication and account management
    text: To authenticate users and manage accounts
  - purpose: Transactional emails
    text: To send transactional emails (alerts, billing, onboarding)
  - purpose: Fraud and security
    text: To detect and prevent fraud, abuse, or security incidents
  retention:
  - period: 7, 30, or 90 days
    scope: Trace data
    text: Trace data is retained according to your plan's retention period (7, 30, or 90 days).
  - period: 30 days after deletion
    scope: Account data
    text: Account data is retained for the duration of your account plus 30 days after deletion.
  - period: 7 years
    scope: Billing records
    text: Billing records are retained for 7 years as required by law.
  rights:
  - right: Access
    text: Access your personal data
  - right: Correction
    text: Request correction of inaccurate data
  - right: Deletion
    text: Request deletion of your data
  - right: Export
    text: Export your data in a machine-readable format
  - right: Withdraw consent
    text: Withdraw consent for optional data processing
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data to third parties
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Preval
provenance_date: '2026-11-10'
provider_name: Preval
provider_slug: preval
slug: preval-privacy-policy
source_date: '2026-11-10'
source_filename: preval-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://preval.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Preval\naid: preval\nurl: https://preval.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Information: Name, email address, and authentication credentials (via Auth0)'\n- category: behavioral\n  text: 'Usage Data: Feature usage patterns, page views, and API call frequency for service improvement'\n- category: communication\n  text: 'Trace Data: LLM call inputs/outputs, latency metrics, token counts, cost data, and tool execution logs\n    sent via our SDK or OTLP ingestion'\n- category: other\n  text: 'API Keys (BYOK):\
  \ Third-party API keys you provide, stored encrypted at rest'\npurposes:\n- purpose: Provide, maintain and improve the Service\n  text: To provide, maintain, and improve the Service\n- purpose: Process traces and generate evaluations\n  text: To process traces and generate evaluations and analytics\n- purpose: Authentication and account management\n  text: To authenticate users and manage accounts\n- purpose: Transactional emails\n  text: To send transactional emails (alerts, billing, onboarding)\n- purpose: Fraud and security\n  text: To detect and prevent fraud, abuse, or security incidents\nretention:\n- scope: Trace data\n  period: 7, 30, or 90 days\n  text: Trace data is retained according to your plan's retention period (7, 30, or 90 days).\n- scope: Account data\n  period: 30 days after deletion\n  text: Account data is retained for the duration of your account plus 30 days after deletion.\n- scope: Billing records\n  period: 7 years\n  text: Billing records are retained for 7 years\
  \ as required by law.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request by contacting us\n  text: You can request data export or deletion at any time by contacting us.\nrights:\n- right: Access\n  text: Access your personal data\n- right: Correction\n  text: Request correction of inaccurate data\n- right: Deletion\n  text: Request deletion of your data\n- right: Export\n  text: Export your data in a machine-readable format\n- right: Withdraw consent\n  text: Withdraw consent for optional data processing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data to third parties\n"
source_yaml_url: https://artifacts.apis.io/preval/privacy/preval-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Preval's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Observability
- Monitoring
- LLM
---
