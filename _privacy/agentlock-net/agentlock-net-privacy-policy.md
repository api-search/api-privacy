---
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Email addresses and billing details for service access.'
  - category: other
    text: 'Agent Metadata: Public keys and agent configurations.'
  - category: other
    text: 'Vault Data: Encrypted credentials stored using multi-layer envelope encryption.'
  - category: behavioral
    text: 'Usage Logs: Timestamps and sanitized action summaries for the audit trail.'
  - category: device
    text: the device model and the operating system, together with your user ID if you are signed in
  - category: behavioral
    text: PostHog additionally records clicks and other interactions with our interface, aggregated heatmaps, browser error reports, performance measurements and session recordings that replay how a page was used
  deletion:
    route: request to support team
    text: Upon request for account deletion, we will scrub all encrypted secrets and personal identifiers within thirty (30) days, except where retention is required by law.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service delivery
    text: We collect only the data necessary to provide the Service.
  - purpose: product analytics
    text: PostHog for product analytics and session recording.
  - purpose: advertising measurement
    text: we use Google Ads cookies to measure the effectiveness of our advertising campaigns and to deliver relevant advertisements.
  - purpose: crash reporting
    text: 'Sentry: Crash and error reports for the mobile app, and error reports from the servers behind agentlock.net.'
  - purpose: aggregate site usage
    text: to understand aggregate site usage (page views, referrers, country, device and browser type, page performance)
  residency:
  - region: European Union (Frankfurt, Germany)
    text: PostHog runs on its EU Cloud in Frankfurt, Germany
  - region: European Union (Frankfurt, Germany)
    text: Sentry stores this data in its European region (Frankfurt, Germany)
  retention:
  - period: as long as your account is active
    scope: account data
    text: We retain account data as long as your account is active.
  - period: null
    scope: timeline logs
    text: Timeline logs are kept for a period sufficient to support the UndoLayer functionality (depends on the subscription and settings).
  - period: thirty (30) days
    scope: deletion request
    text: Upon request for account deletion, we will scrub all encrypted secrets and personal identifiers within thirty (30) days, except where retention is required by law.
  rights:
  - right: access
    text: You have the right to access, rectify, or erase your personal data.
  - right: rectification
    text: You have the right to access, rectify, or erase your personal data.
  - right: erasure
    text: You have the right to access, rectify, or erase your personal data.
  - right: objection
    text: You may also object to certain processing activities or request data portability.
  - right: portability
    text: You may also object to certain processing activities or request data portability.
  - right: withdraw consent
    text: You may withdraw your consent at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: We share data only with trusted subprocessors necessary for service delivery, such as database providers (Supabase), cloud infrastructure hosts, analytics/advertising providers (Google LLC) and PostHog for product analytics and session recording.
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on Standard Contractual Clauses for this provider.
  - mechanism: DPF
    text: All transfers outside the EEA are protected by Standard Contractual Clauses or the EU-US Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentLock
provenance_date: '2026-11-09'
provider_name: AgentLock
provider_slug: agentlock-net
slug: agentlock-net-privacy-policy
source_date: '2026-11-09'
source_filename: agentlock-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentlock.net/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentLock\naid: agentlock-net\nurl: https://agentlock.net/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Information: Email addresses and billing details for service access.'\n- category: other\n  text: 'Agent Metadata: Public keys and agent configurations.'\n- category: other\n  text: 'Vault Data: Encrypted credentials stored using multi-layer envelope encryption.'\n- category: behavioral\n  text: 'Usage Logs: Timestamps and sanitized action summaries for the audit trail.'\n- category: device\n  text: the\
  \ device model and the operating system, together with your user ID if you are signed in\n- category: behavioral\n  text: PostHog additionally records clicks and other interactions with our interface, aggregated heatmaps, browser\n    error reports, performance measurements and session recordings that replay how a page was used\npurposes:\n- purpose: service delivery\n  text: We collect only the data necessary to provide the Service.\n- purpose: product analytics\n  text: PostHog for product analytics and session recording.\n- purpose: advertising measurement\n  text: we use Google Ads cookies to measure the effectiveness of our advertising campaigns and to deliver relevant\n    advertisements.\n- purpose: crash reporting\n  text: 'Sentry: Crash and error reports for the mobile app, and error reports from the servers behind agentlock.net.'\n- purpose: aggregate site usage\n  text: to understand aggregate site usage (page views, referrers, country, device and browser type, page performance)\n\
  retention:\n- scope: account data\n  period: as long as your account is active\n  text: We retain account data as long as your account is active.\n- scope: timeline logs\n  period: null\n  text: Timeline logs are kept for a period sufficient to support the UndoLayer functionality (depends on the subscription\n    and settings).\n- scope: deletion request\n  period: thirty (30) days\n  text: Upon request for account deletion, we will scrub all encrypted secrets and personal identifiers within thirty\n    (30) days, except where retention is required by law.\nresidency:\n- region: European Union (Frankfurt, Germany)\n  text: PostHog runs on its EU Cloud in Frankfurt, Germany\n- region: European Union (Frankfurt, Germany)\n  text: Sentry stores this data in its European region (Frankfurt, Germany)\ntransfers:\n- mechanism: SCC\n  text: we rely on Standard Contractual Clauses for this provider.\n- mechanism: DPF\n  text: All transfers outside the EEA are protected by Standard Contractual Clauses\
  \ or the EU-US Data Privacy Framework.\nsubprocessors:\n  url: null\n  text: We share data only with trusted subprocessors necessary for service delivery, such as database providers\n    (Supabase), cloud infrastructure hosts, analytics/advertising providers (Google LLC) and PostHog for product\n    analytics and session recording.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request to support team\n  text: Upon request for account deletion, we will scrub all encrypted secrets and personal identifiers within thirty\n    (30) days, except where retention is required by law.\nrights:\n- right: access\n  text: You have the right to access, rectify, or erase your personal data.\n- right: rectification\n  text: You have the right to access, rectify, or erase your personal data.\n- right: erasure\n  text: You have the right to access, rectify, or erase your personal data.\n- right: objection\n  text: You may also object to certain processing activities or request\
  \ data portability.\n- right: portability\n  text: You may also object to certain processing activities or request data portability.\n- right: withdraw consent\n  text: You may withdraw your consent at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/agentlock-net/privacy/agentlock-net-privacy-policy.yml
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
summary_line: 27 quoted statements, read from AgentLock's own page on 2026-11-09.
synthetic: false
tags:
- AI Security
- Zero Trust
- API Gateway
- Agent Management
- Audit Trail
- Mobile approvals
---
