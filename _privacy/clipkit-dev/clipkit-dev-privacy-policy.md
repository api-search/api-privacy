---
api_specs:
- filename: clipkit-dev-openapi-generated.yml
  format: yaml
  label: Clipkit Render API
  slug: clipkit-dev-render-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipkit-dev/openapi/_ae-authored/clipkit-dev-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: name, email, password (hashed), organization, and authentication data when you register or sign in.'
  - category: financial
    text: We do not store full card numbers; we receive limited billing metadata (e.g., last four digits, plan, status).
  - category: location
    text: approximate location derived from IP.
  - category: device
    text: 'Usage & device data: log data, IP address, browser/device info, pages and features used, timestamps, and approximate location derived from IP.'
  - category: communication
    text: 'Communications: messages you send us (support, abuse reports).'
  - category: other
    text: 'Content & assets: the video sources (JSON), uploaded or generated assets (images, screenshots, audio, video), and renders you create with the Service.'
  deletion:
    route: contact support@clipkit.dev
    text: To exercise these rights, contact support@clipkit.dev .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: 'Provide the Service: create accounts, host/render/store/display your content, deliver links and exports.'
  - purpose: Billing
    text: 'Billing: process subscriptions and payments via our payment processor.'
  - purpose: Improve the Service
    text: 'Improve the Service: we use aggregated and de-identified usage data to analyze and improve the Service.'
  - purpose: Safety and moderation
    text: 'Safety & moderation: detect and prevent abuse and enforce our Acceptable Use Policy.'
  - purpose: Marketing
    text: 'Marketing: for free/anonymous tiers, we may feature content per our Terms §4(b); you can opt out.'
  residency:
  - region: United States
    text: We may process information in the United States .
  retention:
  - period: 7 days
    scope: Anonymous content and assets
    text: 'Anonymous content & assets: deleted automatically after 7 days .'
  - period: null
    scope: Account content and assets
    text: 'Account content & assets: retained while your account is active and within your plan''s storage quota; deleted or anonymized after account closure, subject to backups and legal-hold requirements.'
  - period: 12 months
    scope: Logs and security data
    text: 'Logs & security data: retained for 12 months .'
  rights:
  - right: access, correct, delete, port, restrict, object
    text: you may have rights to access, correct, delete, port, restrict, or object to processing of your personal information
  - right: withdraw consent or opt out
    text: to withdraw consent or opt out of certain processing
  - right: complaint to supervisory authority
    text: You may also lodge a complaint with your supervisory authority.
  role:
    text: 'Controller: Clipkit, Inc. ("Clipkit", "we", "us")'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: Supabase — database, storage, authentication
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we use appropriate safeguards (e.g., Standard Contractual Clauses) for cross-border transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Clipkit
provenance_date: '2026-11-09'
provider_name: Clipkit
provider_slug: clipkit-dev
slug: clipkit-dev-privacy-policy
source_date: '2026-11-09'
source_filename: clipkit-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.clipkit.dev/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Clipkit\naid: clipkit-dev\nurl: https://www.clipkit.dev/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Controller: Clipkit, Inc. (\"Clipkit\", \"we\", \"us\")'\ndata_categories:\n- category: identifying\n  text: 'Account information: name, email, password (hashed), organization, and authentication data when you register\n    or sign in.'\n- category: financial\n  text: We do not store full card numbers; we receive limited billing metadata (e.g., last four digits, plan, status).\n- category: location\n  text: approximate location derived from IP.\n- category: device\n  text:\
  \ 'Usage & device data: log data, IP address, browser/device info, pages and features used, timestamps, and\n    approximate location derived from IP.'\n- category: communication\n  text: 'Communications: messages you send us (support, abuse reports).'\n- category: other\n  text: 'Content & assets: the video sources (JSON), uploaded or generated assets (images, screenshots, audio, video),\n    and renders you create with the Service.'\npurposes:\n- purpose: Provide the Service\n  text: 'Provide the Service: create accounts, host/render/store/display your content, deliver links and exports.'\n- purpose: Billing\n  text: 'Billing: process subscriptions and payments via our payment processor.'\n- purpose: Improve the Service\n  text: 'Improve the Service: we use aggregated and de-identified usage data to analyze and improve the Service.'\n- purpose: Safety and moderation\n  text: 'Safety & moderation: detect and prevent abuse and enforce our Acceptable Use Policy.'\n- purpose: Marketing\n\
  \  text: 'Marketing: for free/anonymous tiers, we may feature content per our Terms §4(b); you can opt out.'\nretention:\n- scope: Anonymous content and assets\n  period: 7 days\n  text: 'Anonymous content & assets: deleted automatically after 7 days .'\n- scope: Account content and assets\n  period: null\n  text: 'Account content & assets: retained while your account is active and within your plan''s storage quota;\n    deleted or anonymized after account closure, subject to backups and legal-hold requirements.'\n- scope: Logs and security data\n  period: 12 months\n  text: 'Logs & security data: retained for 12 months .'\nresidency:\n- region: United States\n  text: We may process information in the United States .\ntransfers:\n- mechanism: SCC\n  text: Where required, we use appropriate safeguards (e.g., Standard Contractual Clauses) for cross-border transfers.\nsubprocessors:\n  url: null\n  text: Supabase — database, storage, authentication\ndpa:\n  available: null\n  url: null\n\
  \  text: null\ndeletion:\n  route: contact support@clipkit.dev\n  text: To exercise these rights, contact support@clipkit.dev .\nrights:\n- right: access, correct, delete, port, restrict, object\n  text: you may have rights to access, correct, delete, port, restrict, or object to processing of your personal\n    information\n- right: withdraw consent or opt out\n  text: to withdraw consent or opt out of certain processing\n- right: complaint to supervisory authority\n  text: You may also lodge a complaint with your supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/clipkit-dev/privacy/clipkit-dev-privacy-policy.yml
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
summary_line: 23 quoted statements, read from Clipkit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Video Rendering
- AI Agents
- MCP
- JSON
- Open Source
- Developer Tools
---
