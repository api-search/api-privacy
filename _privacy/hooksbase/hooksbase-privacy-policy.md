---
api_specs:
- filename: hooksbase-openapi-generated.yml
  format: yaml
  label: Hooksbase API
  slug: hooksbase-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hooksbase/openapi/_ae-authored/hooksbase-openapi-generated.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and organization data, such as name, email address, login method, organization membership, project access, session data, and account security events.
  - category: identifying
    text: Authentication data, including password-derived hashes for email login, verification and reset flows, OAuth profile data from Google or GitHub when enabled, and session cookies for the dashboard.
  - category: behavioral
    text: Event data, including webhook payloads, request headers, content type, provider metadata, delivery records, attempt records, responses from configured destinations, replay and DLQ records, idempotency keys, and delivery summaries.
  - category: communication
    text: Email, form, and file ingest data, including parsed email fields, selected headers, form fields, file metadata, and file contents when a paid plan stores uploaded files.
  - category: financial
    text: Billing data, including plan, subscription, checkout, portal, billing account, usage-event, overage, and provider webhook state needed to manage paid projects.
  - category: device
    text: Operational data, including usage metrics, diagnostic logs, rate-limit and quota events, error data, support context, and security or abuse signals.
  deletion:
    route: Contact hello@hooksbase.com for deletion requests
    text: Contact hello@hooksbase.com if you need help with access, correction, export, or deletion requests.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, secure, debug, monitor, and improve
    text: Provide, secure, debug, monitor, and improve Hooksbase.
  - purpose: Authentication and account emails
    text: Authenticate users, authorize organizations and project access, maintain sessions, and send account emails.
  - purpose: Event routing and delivery
    text: Receive inbound events, validate configured provider signatures, route events, apply transforms and Automations, store dispatch snapshots, retry delivery, support replay and DLQ recovery, and send events to configured destinations.
  - purpose: Billing and quotas
    text: Calculate quotas, enforce plan limits, process billing, meter overages when enabled, and prevent billing or infrastructure abuse.
  - purpose: Security and abuse investigation
    text: Investigate security events, abuse, service reliability issues, and violations of the Terms of Use.
  retention:
  - period: null
    scope: Free projects
    text: Free projects currently have shorter delivery-history and payload-retention windows than paid projects.
  - period: null
    scope: Paid and enterprise plans
    text: Paid and enterprise plans can have longer windows and additional file-storage capacity.
  rights:
  - right: Access, correction, export, deletion
    text: Contact hello@hooksbase.com if you need help with access, correction, export, or deletion requests.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Cloudflare provides core infrastructure, including Workers, D1, R2, Queues, Durable Objects, Analytics Engine, routing, and related platform services.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Hooksbase
provenance_date: '2026-11-09'
provider_name: Hooksbase
provider_slug: hooksbase
slug: hooksbase-privacy-policy
source_date: '2026-11-09'
source_filename: hooksbase-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.hooksbase.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Hooksbase\naid: hooksbase\nurl: https://www.hooksbase.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account and organization data, such as name, email address, login method, organization membership, project\n    access, session data, and account security events.\n- category: identifying\n  text: Authentication data, including password-derived hashes for email login, verification and reset flows, OAuth\n    profile data from Google or GitHub when enabled, and session cookies for the dashboard.\n- category: behavioral\n  text:\
  \ Event data, including webhook payloads, request headers, content type, provider metadata, delivery records,\n    attempt records, responses from configured destinations, replay and DLQ records, idempotency keys, and delivery\n    summaries.\n- category: communication\n  text: Email, form, and file ingest data, including parsed email fields, selected headers, form fields, file metadata,\n    and file contents when a paid plan stores uploaded files.\n- category: financial\n  text: Billing data, including plan, subscription, checkout, portal, billing account, usage-event, overage, and\n    provider webhook state needed to manage paid projects.\n- category: device\n  text: Operational data, including usage metrics, diagnostic logs, rate-limit and quota events, error data, support\n    context, and security or abuse signals.\npurposes:\n- purpose: Provide, secure, debug, monitor, and improve\n  text: Provide, secure, debug, monitor, and improve Hooksbase.\n- purpose: Authentication and account\
  \ emails\n  text: Authenticate users, authorize organizations and project access, maintain sessions, and send account emails.\n- purpose: Event routing and delivery\n  text: Receive inbound events, validate configured provider signatures, route events, apply transforms and Automations,\n    store dispatch snapshots, retry delivery, support replay and DLQ recovery, and send events to configured destinations.\n- purpose: Billing and quotas\n  text: Calculate quotas, enforce plan limits, process billing, meter overages when enabled, and prevent billing\n    or infrastructure abuse.\n- purpose: Security and abuse investigation\n  text: Investigate security events, abuse, service reliability issues, and violations of the Terms of Use.\nretention:\n- scope: Free projects\n  period: null\n  text: Free projects currently have shorter delivery-history and payload-retention windows than paid projects.\n- scope: Paid and enterprise plans\n  period: null\n  text: Paid and enterprise plans can have\
  \ longer windows and additional file-storage capacity.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare provides core infrastructure, including Workers, D1, R2, Queues, Durable Objects, Analytics Engine,\n    routing, and related platform services.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact hello@hooksbase.com for deletion requests\n  text: Contact hello@hooksbase.com if you need help with access, correction, export, or deletion requests.\nrights:\n- right: Access, correction, export, deletion\n  text: Contact hello@hooksbase.com if you need help with access, correction, export, or deletion requests.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hooksbase/privacy/hooksbase-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 16 quoted statements, read from Hooksbase's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Event Infrastructure
- Artificial Intelligence
- Webhook
- Automation
- Integration
---
