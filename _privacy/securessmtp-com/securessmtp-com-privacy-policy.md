---
api_specs:
- filename: securessmtp-com-openapi-generated.yml
  format: yaml
  label: securessmtp-com API
  slug: securessmtp-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/securessmtp-com/openapi/_ae-authored/securessmtp-com-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data — name, email, password hash (for email/password sign-in), Google account identifiers (for “Sign in with Google”), and optional profile preferences.
  - category: financial
    text: we store only the Stripe customer ID, subscription ID, plan tier, and billing cycle.
  - category: communication
    text: content of emails routed through our relay (subject, body, recipients)
  - category: device
    text: technical metadata (user agent, request timestamps, log identifiers)
  - category: other
    text: the IP addresses of your form submitters
  deletion:
    route: email
    text: To exercise any of these rights, email [email protected] .
  dpa:
    available: true
    text: GDPR DPA available
    url: null
  purposes:
  - purpose: Operate the service
    text: 'Operate the service: route emails through our relay, deliver form submissions, store mail-log entries, render dashboards.'
  - purpose: Billing
    text: Bill you accurately via Stripe.
  - purpose: Abuse detection
    text: 'Detect and prevent abuse: our AI-layered abuse scanning applies content heuristics and Anthropic Claude classification to outbound email before delivery.'
  - purpose: Customer support
    text: Provide customer support.
  residency:
  - region: Germany
    text: Our servers are in Germany, and our other subprocessors are located in the United States and Ireland.
  retention:
  - period: 30 days
    scope: Account data
    text: 'Account data: retained until you delete your account, plus 30 days for backup expiration.'
  - period: 30 days
    scope: Email log entries
    text: 'Email log entries (per relayed message): 30 days on Free, 90 days on Starter, 365 days on Pro, 1,095 days (3 years) on Business and Enterprise.'
  - period: 7 years
    scope: Billing records
    text: 'Billing records: 7 years per UAE tax law (Federal Decree-Law No. 7 of 2017 on Tax Procedures).'
  - period: 12 months
    scope: Audit and security logs
    text: 'Audit logs and security logs: 12 months.'
  rights:
  - right: Access
    text: Access to your personal data.
  - right: Correction
    text: Correction of inaccurate data.
  - right: Deletion
    text: Deletion of your data (subject to legal retention requirements).
  - right: Portability
    text: Portability of your data in a machine-readable format.
  - right: Restriction or objection
    text: Restriction or objection to certain processing.
  - right: Withdraw consent
    text: Withdrawal of consent for any consent-based processing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do NOT sell personal data.
  subprocessors:
    text: SecureSMTP uses the following subprocessors to deliver the service.
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on Standard Contractual Clauses (where required by GDPR) and equivalent safeguards under the UAE PDPL for these transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: securessmtp-com
provenance_date: '2026-11-10'
provider_name: securessmtp-com
provider_slug: securessmtp-com
slug: securessmtp-com-privacy-policy
source_date: '2026-11-10'
source_filename: securessmtp-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://securessmtp.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: securessmtp-com\naid: securessmtp-com\nurl: https://securessmtp.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account data — name, email, password hash (for email/password sign-in), Google account identifiers (for\n    “Sign in with Google”), and optional profile preferences.\n- category: financial\n  text: we store only the Stripe customer ID, subscription ID, plan tier, and billing cycle.\n- category: communication\n  text: content of emails routed through our relay (subject, body, recipients)\n- category: device\n  text:\
  \ technical metadata (user agent, request timestamps, log identifiers)\n- category: other\n  text: the IP addresses of your form submitters\npurposes:\n- purpose: Operate the service\n  text: 'Operate the service: route emails through our relay, deliver form submissions, store mail-log entries,\n    render dashboards.'\n- purpose: Billing\n  text: Bill you accurately via Stripe.\n- purpose: Abuse detection\n  text: 'Detect and prevent abuse: our AI-layered abuse scanning applies content heuristics and Anthropic Claude\n    classification to outbound email before delivery.'\n- purpose: Customer support\n  text: Provide customer support.\nretention:\n- scope: Account data\n  period: 30 days\n  text: 'Account data: retained until you delete your account, plus 30 days for backup expiration.'\n- scope: Email log entries\n  period: 30 days\n  text: 'Email log entries (per relayed message): 30 days on Free, 90 days on Starter, 365 days on Pro, 1,095 days\n    (3 years) on Business and Enterprise.'\n\
  - scope: Billing records\n  period: 7 years\n  text: 'Billing records: 7 years per UAE tax law (Federal Decree-Law No. 7 of 2017 on Tax Procedures).'\n- scope: Audit and security logs\n  period: 12 months\n  text: 'Audit logs and security logs: 12 months.'\nresidency:\n- region: Germany\n  text: Our servers are in Germany, and our other subprocessors are located in the United States and Ireland.\ntransfers:\n- mechanism: SCC\n  text: We rely on Standard Contractual Clauses (where required by GDPR) and equivalent safeguards under the UAE\n    PDPL for these transfers.\nsubprocessors:\n  url: null\n  text: SecureSMTP uses the following subprocessors to deliver the service.\ndpa:\n  available: true\n  url: null\n  text: GDPR DPA available\ndeletion:\n  route: email\n  text: To exercise any of these rights, email [email protected] .\nrights:\n- right: Access\n  text: Access to your personal data.\n- right: Correction\n  text: Correction of inaccurate data.\n- right: Deletion\n  text: Deletion\
  \ of your data (subject to legal retention requirements).\n- right: Portability\n  text: Portability of your data in a machine-readable format.\n- right: Restriction or objection\n  text: Restriction or objection to certain processing.\n- right: Withdraw consent\n  text: Withdrawal of consent for any consent-based processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do NOT sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/securessmtp-com/privacy/securessmtp-com-privacy-policy.yml
stated_fields:
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
summary_line: 25 quoted statements, read from securessmtp-com's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Transactional
- SMTP
- Services
- SecureSMTP
---
