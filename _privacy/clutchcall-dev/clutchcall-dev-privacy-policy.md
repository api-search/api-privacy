---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address, name, organisation name, and authentication credentials handled by our identity provider.
  - category: financial
    text: Plan, invoices, and payment processor identifiers. We do not store full card numbers; that data is held by our PCI-compliant payment processor.
  - category: communication
    text: 'Call detail records (CDRs): from-number, to-number, start/stop, disposition, codec, vendor leg, and routing decisions.'
  - category: communication
    text: Call audio and transcripts only when recording is enabled by you for that call
  - category: device
    text: Usage telemetry. Logs, metrics, and traces from the gateway and agent runtime.
  deletion:
    route: Email privacy@clutchcall.dev to exercise rights
    text: To exercise these rights write to privacy@clutchcall.dev .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain, and improve the Service
    text: To provide, maintain, and improve the Service.
  - purpose: Authentication and fraud/abuse detection
    text: To authenticate users, enforce per-tenant access controls, and detect fraud or abuse.
  - purpose: Metering and billing
    text: To meter usage and bill correctly under your plan.
  - purpose: Regulatory compliance
    text: To meet regulatory obligations applicable to telephony providers in India and other markets we serve.
  - purpose: Operational notices and product updates
    text: To communicate operational notices and, with consent, product updates.
  retention:
  - period: null
    scope: Call detail records
    text: CDRs are retained for the period required by applicable telecom regulation, which in India means the records mandated by TRAI / DOT.
  - period: null
    scope: Audio recordings
    text: Audio recordings are retained only for the window you configure per workspace.
  - period: up to 90 days
    scope: Logs and traces
    text: Logs and traces are retained for up to 90 days for operational debugging unless a longer hold is required for an active incident investigation.
  rights:
  - right: access
    text: you may have the right to access, correct, export, or delete personal information we hold about you
  - right: correct
    text: you may have the right to access, correct, export, or delete personal information we hold about you
  - right: export
    text: you may have the right to access, correct, export, or delete personal information we hold about you
  - right: delete
    text: you may have the right to access, correct, export, or delete personal information we hold about you
  - right: object or restrict
    text: to object to or restrict certain processing
  role:
    text: We are the data controller for personal information you provide directly. For data your end-customers route through the Service, you are the controller and we act as a processor on your behalf
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: A current list is available on request.
    url: null
  transfers:
  - mechanism: other
    text: We operate primarily in India and may transfer data to other regions where our infrastructure or sub-processors are located.
  - mechanism: SCC
    text: Where we do, we rely on appropriate safeguards such as standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ClutchCall
provenance_date: '2026-11-09'
provider_name: ClutchCall
provider_slug: clutchcall-dev
slug: clutchcall-dev-privacy-policy
source_date: '2026-11-09'
source_filename: clutchcall-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://clutchcall.dev/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ClutchCall\naid: clutchcall-dev\nurl: https://clutchcall.dev/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the data controller for personal information you provide directly. For data your end-customers route\n    through the Service, you are the controller and we act as a processor on your behalf\ndata_categories:\n- category: contact\n  text: Email address, name, organisation name, and authentication credentials handled by our identity provider.\n- category: financial\n  text: Plan, invoices, and payment processor identifiers. We do not store full card numbers; that data is\
  \ held\n    by our PCI-compliant payment processor.\n- category: communication\n  text: 'Call detail records (CDRs): from-number, to-number, start/stop, disposition, codec, vendor leg, and routing\n    decisions.'\n- category: communication\n  text: Call audio and transcripts only when recording is enabled by you for that call\n- category: device\n  text: Usage telemetry. Logs, metrics, and traces from the gateway and agent runtime.\npurposes:\n- purpose: Provide, maintain, and improve the Service\n  text: To provide, maintain, and improve the Service.\n- purpose: Authentication and fraud/abuse detection\n  text: To authenticate users, enforce per-tenant access controls, and detect fraud or abuse.\n- purpose: Metering and billing\n  text: To meter usage and bill correctly under your plan.\n- purpose: Regulatory compliance\n  text: To meet regulatory obligations applicable to telephony providers in India and other markets we serve.\n- purpose: Operational notices and product updates\n \
  \ text: To communicate operational notices and, with consent, product updates.\nretention:\n- scope: Call detail records\n  period: null\n  text: CDRs are retained for the period required by applicable telecom regulation, which in India means the records\n    mandated by TRAI / DOT.\n- scope: Audio recordings\n  period: null\n  text: Audio recordings are retained only for the window you configure per workspace.\n- scope: Logs and traces\n  period: up to 90 days\n  text: Logs and traces are retained for up to 90 days for operational debugging unless a longer hold is required\n    for an active incident investigation.\nresidency: []\ntransfers:\n- mechanism: other\n  text: We operate primarily in India and may transfer data to other regions where our infrastructure or sub-processors\n    are located.\n- mechanism: SCC\n  text: Where we do, we rely on appropriate safeguards such as standard contractual clauses.\nsubprocessors:\n  url: null\n  text: A current list is available on request.\n\
  dpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@clutchcall.dev to exercise rights\n  text: To exercise these rights write to privacy@clutchcall.dev .\nrights:\n- right: access\n  text: you may have the right to access, correct, export, or delete personal information we hold about you\n- right: correct\n  text: you may have the right to access, correct, export, or delete personal information we hold about you\n- right: export\n  text: you may have the right to access, correct, export, or delete personal information we hold about you\n- right: delete\n  text: you may have the right to access, correct, export, or delete personal information we hold about you\n- right: object or restrict\n  text: to object to or restrict certain processing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/clutchcall-dev/privacy/clutchcall-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from ClutchCall's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Voice AI
- Real-Time Communications
- QUIC
- Telephony
- SIP
- Live Streaming
- Robotics
- AI Inference
- WebTransport
---
