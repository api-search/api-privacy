---
api_specs:
- filename: answerline-dev-async-api-openapi.yml
  format: yaml
  label: answerline-dev Async API
  slug: answerline-dev-async-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answerline-dev/openapi/answerline-dev-async-api-openapi.yml
- filename: answerline-dev-countries-api-openapi.yml
  format: yaml
  label: answerline-dev Countries API
  slug: answerline-dev-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answerline-dev/openapi/answerline-dev-countries-api-openapi.yml
- filename: answerline-dev-credits-api-openapi.yml
  format: yaml
  label: answerline-dev Credits API
  slug: answerline-dev-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answerline-dev/openapi/answerline-dev-credits-api-openapi.yml
- filename: answerline-dev-monitor-api-openapi.yml
  format: yaml
  label: answerline-dev Monitor API
  slug: answerline-dev-monitor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answerline-dev/openapi/answerline-dev-monitor-api-openapi.yml
- filename: answerline-dev-states-api-openapi.yml
  format: yaml
  label: answerline-dev States API
  slug: answerline-dev-states-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/answerline-dev/openapi/answerline-dev-states-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account data: email address, sign-in method (email link or Google), team and account membership, roles, and the names you give API keys.'
  - category: financial
    text: 'Billing data: USD balance, top-ups and auto top-up settings, balance ledger, tier, invoices and payment history.'
  - category: location
    text: 'API usage metadata: timestamps, engine, country/geo parameter, request status, amounts reserved and charged, request ids, and per-day usage rollups.'
  - category: communication
    text: 'Support correspondence: emails and messages you send us.'
  - category: device
    text: a random device identifier stored in a cookie, used to check that a sign-in link is opened on the device that asked for it
  - category: behavioral
    text: 'Security and audit records: sign-in events with client IP, key creation and revocation, membership changes and other account actions, kept in an audit log'
  deletion:
    route: Delete your account in the dashboard (type your email address under Delete account)
    text: To delete your user, type your email address exactly under Delete account .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: To provide the service , running your requests, storing results for retrieval, delivering webhooks, managing your account and keys (performance of a contract, GDPR Art. 6(1)(b)).
  - purpose: Billing
    text: To bill you , metering usage, charging your balance, invoicing, and meeting tax and accounting obligations
  - purpose: Affiliate program
    text: To run the affiliate program , attributing sign-ups to referral links, recording commissions and paying them to your payout email
  - purpose: Security
    text: To keep the service secure , abuse prevention, rate limiting, audit logging, detecting compromised keys (legitimate interest, Art. 6(1)(f)).
  - purpose: Support and reliability
    text: To support you and improve reliability , answering requests, diagnosing failures, monitoring capacity (legitimate interest, Art. 6(1)(f)).
  residency:
  - region: EU
    text: Hetzner , server hosting in the EU.
  retention:
  - period: 4 days
    scope: Request payloads and results
    text: Request payloads and results (task records, result files, raw responses and HTML snapshots) are kept for 4 days after the request and deleted within 6 days of it
  - period: 30 days
    scope: Database backups
    text: Backups are kept for 7 days on our server and for 30 days in offsite storage, then deleted.
  - period: 30 days
    scope: Sessions
    text: Sessions expire 30 days (720 hours) after sign-in, or earlier when you sign out
  - period: 400 days
    scope: Audit log events
    text: Audit log events are deleted 400 days after they happened.
  - period: 7 days
    scope: Webhook deliveries
    text: Webhook deliveries are deleted 7 days after they were delivered
  - period: 400 days
    scope: Deleted user mailbox hash
    text: The hash of a deleted user's mailbox is deleted 400 days after the deletion.
  - period: null
    scope: Billing and accounting records
    text: Billing and accounting records (balance ledger, referral commissions, invoices and payment records) are kept for the period required by Hungarian and EU accounting and tax law.
  rights:
  - right: access, rectification, erasure, restriction, portability, objection
    text: Under the GDPR you can request access, rectification, erasure, restriction, portability and object to processing based on legitimate interest.
  - right: withdraw consent
    text: You can withdraw consent where processing relies on it.
  - right: lodge complaint
    text: You also have the right to lodge a complaint with the Hungarian National Authority for Data Protection and Freedom of Information (NAIH) or your local supervisory authority.
  role:
    text: Controller for the data we collect to run your account and our business
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Subprocessors and service providers Data collection providers , which run requests against the engines on our behalf and return the answers
    url: null
  transfers:
  - mechanism: adequacy
    text: Where a recipient is outside the EU/EEA, transfers are covered by adequacy decisions or standard contractual clauses.
  - mechanism: SCC
    text: Where a recipient is outside the EU/EEA, transfers are covered by adequacy decisions or standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: answerline-dev
provenance_date: '2026-11-09'
provider_name: answerline-dev
provider_slug: answerline-dev
slug: answerline-dev-privacy-policy
source_date: '2026-11-09'
source_filename: answerline-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://answerline.dev/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: answerline-dev\naid: answerline-dev\nurl: https://answerline.dev/legal/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Controller for the data we collect to run your account and our business\ndata_categories:\n- category: contact\n  text: 'Account data: email address, sign-in method (email link or Google), team and account membership, roles,\n    and the names you give API keys.'\n- category: financial\n  text: 'Billing data: USD balance, top-ups and auto top-up settings, balance ledger, tier, invoices and payment\n    history.'\n- category: location\n  text: 'API usage metadata: timestamps,\
  \ engine, country/geo parameter, request status, amounts reserved and charged,\n    request ids, and per-day usage rollups.'\n- category: communication\n  text: 'Support correspondence: emails and messages you send us.'\n- category: device\n  text: a random device identifier stored in a cookie, used to check that a sign-in link is opened on the device\n    that asked for it\n- category: behavioral\n  text: 'Security and audit records: sign-in events with client IP, key creation and revocation, membership changes\n    and other account actions, kept in an audit log'\npurposes:\n- purpose: Provide the service\n  text: To provide the service , running your requests, storing results for retrieval, delivering webhooks, managing\n    your account and keys (performance of a contract, GDPR Art. 6(1)(b)).\n- purpose: Billing\n  text: To bill you , metering usage, charging your balance, invoicing, and meeting tax and accounting obligations\n- purpose: Affiliate program\n  text: To run the affiliate\
  \ program , attributing sign-ups to referral links, recording commissions and paying\n    them to your payout email\n- purpose: Security\n  text: To keep the service secure , abuse prevention, rate limiting, audit logging, detecting compromised keys\n    (legitimate interest, Art. 6(1)(f)).\n- purpose: Support and reliability\n  text: To support you and improve reliability , answering requests, diagnosing failures, monitoring capacity (legitimate\n    interest, Art. 6(1)(f)).\nretention:\n- scope: Request payloads and results\n  period: 4 days\n  text: Request payloads and results (task records, result files, raw responses and HTML snapshots) are kept for\n    4 days after the request and deleted within 6 days of it\n- scope: Database backups\n  period: 30 days\n  text: Backups are kept for 7 days on our server and for 30 days in offsite storage, then deleted.\n- scope: Sessions\n  period: 30 days\n  text: Sessions expire 30 days (720 hours) after sign-in, or earlier when you sign out\n\
  - scope: Audit log events\n  period: 400 days\n  text: Audit log events are deleted 400 days after they happened.\n- scope: Webhook deliveries\n  period: 7 days\n  text: Webhook deliveries are deleted 7 days after they were delivered\n- scope: Deleted user mailbox hash\n  period: 400 days\n  text: The hash of a deleted user's mailbox is deleted 400 days after the deletion.\n- scope: Billing and accounting records\n  period: null\n  text: Billing and accounting records (balance ledger, referral commissions, invoices and payment records) are\n    kept for the period required by Hungarian and EU accounting and tax law.\nresidency:\n- region: EU\n  text: Hetzner , server hosting in the EU.\ntransfers:\n- mechanism: adequacy\n  text: Where a recipient is outside the EU/EEA, transfers are covered by adequacy decisions or standard contractual\n    clauses.\n- mechanism: SCC\n  text: Where a recipient is outside the EU/EEA, transfers are covered by adequacy decisions or standard contractual\n\
  \    clauses.\nsubprocessors:\n  url: null\n  text: Subprocessors and service providers Data collection providers , which run requests against the engines on\n    our behalf and return the answers\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account in the dashboard (type your email address under Delete account)\n  text: To delete your user, type your email address exactly under Delete account .\nrights:\n- right: access, rectification, erasure, restriction, portability, objection\n  text: Under the GDPR you can request access, rectification, erasure, restriction, portability and object to processing\n    based on legitimate interest.\n- right: withdraw consent\n  text: You can withdraw consent where processing relies on it.\n- right: lodge complaint\n  text: You also have the right to lodge a complaint with the Hungarian National Authority for Data Protection and\n    Freedom of Information (NAIH) or your local supervisory authority.\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/answerline-dev/privacy/answerline-dev-privacy-policy.yml
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
summary_line: 28 quoted statements, read from answerline-dev's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Visibility
- Marketing
- Analytics
---
