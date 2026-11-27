---
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address — used for authentication, billing, and service communication
  - category: financial
    text: Billing data — subscription plan, Stripe customer ID, and payment status.
  - category: communication
    text: Sender email address (envelope from)
  - category: communication
    text: Recipient email address (envelope to)
  - category: device
    text: API usage counts — we track the number of authenticated API requests per month to enforce plan quotas
  - category: identifying
    text: Identifiers — email address, account ID, IP address (in request logs)
  deletion:
    route: Delete account button in Settings
    text: the "Delete account" button in Settings permanently and irreversibly removes all your data (account, domains, aliases, rules, logs, and auth credentials)
  dpa:
    available: true
    text: Our standard Data Processing Agreement, which incorporates the EU Standard Contractual Clauses for international transfers and the UK Addendum, is incorporated into our Terms of Service by reference and a signed counterpart is available on request
    url: null
  purposes:
  - purpose: Email relay
    text: Email relay — to forward messages and enforce plan limits
  - purpose: Billing
    text: Billing — to manage your subscription via Stripe
  - purpose: Relay logs and dashboards
    text: Relay logs — to power your Live Logs and Analytics dashboard
  - purpose: Advertising or profiling
    text: We do not sell, share, or provide your data to third parties for advertising, profiling, or any purpose unrelated to operating the service.
  residency:
  - region: United States
    text: arc-relay is operated from the United States.
  retention:
  - period: lifetime of your account
    scope: Account data
    text: Account data (email, plan, domains, aliases, rules, API keys, webhooks, DKIM keys) — retained for the lifetime of your account
  - period: between 7 and 365 days
    scope: Relay logs
    text: Relay logs — automatically purged based on your plan, between 7 and 365 days .
  - period: up to 30 days
    scope: Encrypted database backups
    text: Encrypted database backups — retained for up to 30 days for disaster recovery, then permanently deleted
  - period: null
    scope: API usage counters
    text: API usage counters — reset on the 1st of each month; historical counts are not retained
  rights:
  - right: Access
    text: Access — view your data in the dashboard, or download a full export from Settings
  - right: Rectification
    text: Rectification (correct) — update your email aliases, domains, sender rules, and account email at any time through the dashboard
  - right: Erasure
    text: Erasure (delete) — the "Delete account" button in Settings permanently and irreversibly removes all your data
  - right: Portability
    text: Portability (export) — the "Download my data" button in Settings provides a structured JSON export of all account data
  - right: Restriction
    text: Restriction — ask us to limit processing while a dispute is resolved
  - right: Objection
    text: Objection — object to processing based on legitimate interests; we will stop unless we can demonstrate compelling grounds
  role:
    text: We are the data controller for the personal data described in this policy.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, and we do not share personal information for cross-context behavioral advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: The lawful basis for those transfers is the European Commission's Standard Contractual Clauses (SCCs) , which we have entered into with each sub-processor.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ARC-Relay
provenance_date: '2026-11-09'
provider_name: ARC-Relay
provider_slug: arc-relay-com
slug: arc-relay-com-privacy-policy
source_date: '2026-11-09'
source_filename: arc-relay-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://arc-relay.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ARC-Relay\naid: arc-relay-com\nurl: https://arc-relay.com/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the data controller for the personal data described in this policy.\ndata_categories:\n- category: contact\n  text: Email address — used for authentication, billing, and service communication\n- category: financial\n  text: Billing data — subscription plan, Stripe customer ID, and payment status.\n- category: communication\n  text: Sender email address (envelope from)\n- category: communication\n  text: Recipient email address (envelope to)\n- category: device\n  text:\
  \ API usage counts — we track the number of authenticated API requests per month to enforce plan quotas\n- category: identifying\n  text: Identifiers — email address, account ID, IP address (in request logs)\npurposes:\n- purpose: Email relay\n  text: Email relay — to forward messages and enforce plan limits\n- purpose: Billing\n  text: Billing — to manage your subscription via Stripe\n- purpose: Relay logs and dashboards\n  text: Relay logs — to power your Live Logs and Analytics dashboard\n- purpose: Advertising or profiling\n  text: We do not sell, share, or provide your data to third parties for advertising, profiling, or any purpose\n    unrelated to operating the service.\nretention:\n- scope: Account data\n  period: lifetime of your account\n  text: Account data (email, plan, domains, aliases, rules, API keys, webhooks, DKIM keys) — retained for the lifetime\n    of your account\n- scope: Relay logs\n  period: between 7 and 365 days\n  text: Relay logs — automatically purged based\
  \ on your plan, between 7 and 365 days .\n- scope: Encrypted database backups\n  period: up to 30 days\n  text: Encrypted database backups — retained for up to 30 days for disaster recovery, then permanently deleted\n- scope: API usage counters\n  period: null\n  text: API usage counters — reset on the 1st of each month; historical counts are not retained\nresidency:\n- region: United States\n  text: arc-relay is operated from the United States.\ntransfers:\n- mechanism: SCC\n  text: The lawful basis for those transfers is the European Commission's Standard Contractual Clauses (SCCs) ,\n    which we have entered into with each sub-processor.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Our standard Data Processing Agreement, which incorporates the EU Standard Contractual Clauses for international\n    transfers and the UK Addendum, is incorporated into our Terms of Service by reference and a signed counterpart\n    is available on request\n\
  deletion:\n  route: Delete account button in Settings\n  text: the \"Delete account\" button in Settings permanently and irreversibly removes all your data (account, domains,\n    aliases, rules, logs, and auth credentials)\nrights:\n- right: Access\n  text: Access — view your data in the dashboard, or download a full export from Settings\n- right: Rectification\n  text: Rectification (correct) — update your email aliases, domains, sender rules, and account email at any time\n    through the dashboard\n- right: Erasure\n  text: Erasure (delete) — the \"Delete account\" button in Settings permanently and irreversibly removes all your\n    data\n- right: Portability\n  text: Portability (export) — the \"Download my data\" button in Settings provides a structured JSON export of all\n    account data\n- right: Restriction\n  text: Restriction — ask us to limit processing while a dispute is resolved\n- right: Objection\n  text: Objection — object to processing based on legitimate interests;\
  \ we will stop unless we can demonstrate compelling\n    grounds\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, and we do not share personal information for cross-context behavioral\n    advertising.\n"
source_yaml_url: https://artifacts.apis.io/arc-relay-com/privacy/arc-relay-com-privacy-policy.yml
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
summary_line: 26 quoted statements, read from ARC-Relay's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Forwarding
- SRS
- Arc
- Services
---
