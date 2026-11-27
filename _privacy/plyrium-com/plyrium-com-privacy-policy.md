---
api_specs:
- filename: plyrium-com-discovery-api-openapi.yml
  format: yaml
  label: Plyrium Discovery API
  slug: plyrium-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plyrium-com/openapi/plyrium-com-discovery-api-openapi.yml
- filename: plyrium-com-purchase-api-openapi.yml
  format: yaml
  label: Plyrium Purchase API
  slug: plyrium-com-purchase-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plyrium-com/openapi/plyrium-com-purchase-api-openapi.yml
- filename: plyrium-com-verification-api-openapi.yml
  format: yaml
  label: Plyrium Verification API
  slug: plyrium-com-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/plyrium-com/openapi/plyrium-com-verification-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, business name, phone number
  - category: financial
    text: Billing information processed by Stripe - we never store your full credit card number on our systems
  - category: communication
    text: Audio recording of the call (full duplex)
  - category: location
    text: we receive periodic location pings (latitude, longitude, accuracy radius, timestamp)
  - category: device
    text: IP address, browser type, device type, operating system
  - category: behavioral
    text: Pages visited within our application, timestamps, navigation flow
  deletion:
    route: Email privacy@plyrium.com
    text: You may request earlier deletion at any time by emailing privacy@plyrium.com.
  dpa:
    available: true
    text: Each is bound by their own privacy policy and a Data Processing Agreement with us.
    url: null
  purposes:
  - purpose: Deliver the Service
    text: 'Deliver the Service: answer your business phone, publish posts, reply to reviews, respond to leads, generate reports, route appointments to techs'
  - purpose: Billing
    text: 'Bill you accurately: manage your subscription via Stripe, send invoices and receipts, calculate per-call cost'
  - purpose: Improve the Service
    text: 'Improve the Service: via anonymized, aggregated analytics - never individual-level training of public AI models'
  residency:
  - region: United States
    text: Hosted in the United States (us-east-1).
  retention:
  - period: 90 days
    scope: Account and configuration data after cancellation
    text: Account and configuration data are retained for 90 days, then permanently deleted
  - period: 7 years
    scope: Billing records
    text: Billing records (invoices, receipts, Stripe transaction metadata) are retained for 7 years to comply with U.S. tax law
  - period: 90 days
    scope: Call recordings and transcripts after cancellation
    text: Customer leads, posts, reviews, call recordings, transcripts, and summaries are retained for 90 days for your export, then deleted
  - period: 30 days
    scope: Location data
    text: Location data older than 30 days is purged on a rolling cadence unless tied to an active appointment record
  rights:
  - right: Access
    text: 'Access: request a copy of the personal data we hold about you'
  - right: Correction
    text: 'Correction: ask us to fix inaccurate information'
  - right: Deletion
    text: 'Deletion: request deletion of your data ("right to be forgotten")'
  - right: Portability
    text: 'Portability: request your data in a machine-readable format (CSV/JSON exports are available from the dashboard)'
  - right: Objection
    text: 'Object to processing: in certain circumstances, ask us to stop using your data'
  role:
    text: References to "we," "us," and "our" in this Privacy Policy refer to Plyrium.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: 4. Third-Party Sub-Processors
    url: https://www.plyrium.com/privacy
  transfers:
  - mechanism: SCC
    text: Where required, we rely on Standard Contractual Clauses or other approved mechanisms to lawfully transfer data internationally.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Plyrium
provenance_date: '2026-11-10'
provider_name: Plyrium
provider_slug: plyrium-com
slug: plyrium-com-privacy-policy
source_date: '2026-11-10'
source_filename: plyrium-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.plyrium.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Plyrium\naid: plyrium-com\nurl: https://www.plyrium.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: References to \"we,\" \"us,\" and \"our\" in this Privacy Policy refer to Plyrium.\ndata_categories:\n- category: identifying\n  text: Name, email address, business name, phone number\n- category: financial\n  text: Billing information processed by Stripe - we never store your full credit card number on our systems\n- category: communication\n  text: Audio recording of the call (full duplex)\n- category: location\n  text: we receive periodic location pings (latitude, longitude, accuracy\
  \ radius, timestamp)\n- category: device\n  text: IP address, browser type, device type, operating system\n- category: behavioral\n  text: Pages visited within our application, timestamps, navigation flow\npurposes:\n- purpose: Deliver the Service\n  text: 'Deliver the Service: answer your business phone, publish posts, reply to reviews, respond to leads, generate\n    reports, route appointments to techs'\n- purpose: Billing\n  text: 'Bill you accurately: manage your subscription via Stripe, send invoices and receipts, calculate per-call\n    cost'\n- purpose: Improve the Service\n  text: 'Improve the Service: via anonymized, aggregated analytics - never individual-level training of public AI\n    models'\nretention:\n- scope: Account and configuration data after cancellation\n  period: 90 days\n  text: Account and configuration data are retained for 90 days, then permanently deleted\n- scope: Billing records\n  period: 7 years\n  text: Billing records (invoices, receipts, Stripe transaction\
  \ metadata) are retained for 7 years to comply with\n    U.S. tax law\n- scope: Call recordings and transcripts after cancellation\n  period: 90 days\n  text: Customer leads, posts, reviews, call recordings, transcripts, and summaries are retained for 90 days for\n    your export, then deleted\n- scope: Location data\n  period: 30 days\n  text: Location data older than 30 days is purged on a rolling cadence unless tied to an active appointment record\nresidency:\n- region: United States\n  text: Hosted in the United States (us-east-1).\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on Standard Contractual Clauses or other approved mechanisms to lawfully transfer\n    data internationally.\nsubprocessors:\n  url: https://www.plyrium.com/privacy\n  text: 4. Third-Party Sub-Processors\ndpa:\n  available: true\n  url: null\n  text: Each is bound by their own privacy policy and a Data Processing Agreement with us.\ndeletion:\n  route: Email privacy@plyrium.com\n  text: You may\
  \ request earlier deletion at any time by emailing privacy@plyrium.com.\nrights:\n- right: Access\n  text: 'Access: request a copy of the personal data we hold about you'\n- right: Correction\n  text: 'Correction: ask us to fix inaccurate information'\n- right: Deletion\n  text: 'Deletion: request deletion of your data (\"right to be forgotten\")'\n- right: Portability\n  text: 'Portability: request your data in a machine-readable format (CSV/JSON exports are available from the dashboard)'\n- right: Objection\n  text: 'Object to processing: in certain circumstances, ask us to stop using your data'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/plyrium-com/privacy/plyrium-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Plyrium's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Agent Skills
- Supply Chain Security
- Software Provenance
- x402
- Agentic Commerce
- A2A
- MCP
- Field Service Management
- Home Services
---
