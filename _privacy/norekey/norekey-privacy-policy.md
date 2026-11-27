---
api_specs:
- filename: norekey-api-openapi.json
  format: json
  label: NoRekey API API
  slug: norekey-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/norekey/openapi/_original/norekey-api-openapi.json
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data — your name, email address and password (hashed), plus team names and membership.
  - category: financial
    text: Documents — the statement PDFs you upload and the transaction data extracted from them.
  - category: financial
    text: Billing data — handled by Stripe. We store your plan, invoice metadata and your card's brand and last four digits, never the full number.
  - category: device
    text: Operational data — page counts, conversion status, server logs and error reports used to run and secure the service.
  - category: behavioral
    text: Referral data — aggregate article readership and visits to the converter.
  deletion:
    route: In-app deletion of conversions, teams and account, or email support@norekey.com
    text: 'Much of this you can do directly in the app: retention is under your control, and you can delete conversions, teams and your account yourself.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing the service
    text: Providing the service — your account, converting statements, your history and exports, billing, and account emails such as verification, receipts and usage summaries.
  - purpose: Security and reliability
    text: Keeping the service secure and working — server logs, error monitoring and abuse prevention.
  - purpose: Referral analytics
    text: Understanding how people find us — referral and readership data.
  - purpose: Accounting records
    text: 'Keeping invoices and accounting records — Lawful basis: our legal obligations under UK tax law.'
  residency:
  - region: United Kingdom
    text: Our servers and file storage are in London.
  retention:
  - period: immediately after processing
    scope: Source PDFs
    text: Source PDFs — deleted from our storage immediately after processing.
  - period: 30 minutes, 1 hour (default), 24 hours, 7 days or 30 days
    scope: Extracted rows and exports
    text: 'Extracted rows and exports — deleted on your team''s retention setting: 30 minutes, 1 hour (default), 24 hours, 7 days or 30 days.'
  - period: 24 hours
    scope: Guest conversions
    text: Guest conversions expire within 24 hours.
  - period: 7 days
    scope: Server logs
    text: Server logs — kept for up to 7 days.
  - period: 90 days
    scope: Error and performance reports
    text: Error and performance reports are kept by Laravel Nightwatch for up to 90 days.
  - period: 45 days
    scope: Emails
    text: Emails — Postmark, which delivers our emails, keeps their content and delivery records for 45 days.
  - period: 7 days
    scope: Backups
    text: Backups — database backups are kept for 7 days, so deleted data can remain in a backup for up to 7 days before it is overwritten.
  - period: normally six years
    scope: Invoices and accounting records
    text: Account data — kept while your account exists and deleted when you delete it, except invoices and accounting records, which we keep for as long as UK tax law requires (normally six years).
  rights:
  - right: Access
    text: Under UK GDPR you can ask for a copy of your personal data
  - right: Rectification and erasure
    text: have it corrected or deleted
  - right: Restriction and objection
    text: restrict or object to how we use it
  - right: Portability
    text: take your data elsewhere
  - right: Complaint
    text: You can also complain to the Information Commissioner's Office (ico.org.uk).
  role:
    text: NoRekey is the controller for your account, billing and service data.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We never sell personal data and never share it for advertising.
  subprocessors:
    text: 'We share data only with the processors needed to run NoRekey, under data processing agreements: Laravel Cloud — application hosting and databases, in London.'
    url: null
  transfers:
  - mechanism: other
    text: the UK–US data bridge where the provider is certified, or the UK International Data Transfer Addendum to the EU standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: NoRekey
provenance_date: '2026-11-10'
provider_name: NoRekey
provider_slug: norekey
slug: norekey-privacy-policy
source_date: '2026-11-10'
source_filename: norekey-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://norekey.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: NoRekey\naid: norekey\nurl: https://norekey.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: NoRekey is the controller for your account, billing and service data.\ndata_categories:\n- category: identifying\n  text: Account data — your name, email address and password (hashed), plus team names and membership.\n- category: financial\n  text: Documents — the statement PDFs you upload and the transaction data extracted from them.\n- category: financial\n  text: Billing data — handled by Stripe. We store your plan, invoice metadata and your card's brand and last four\n    digits, never the\
  \ full number.\n- category: device\n  text: Operational data — page counts, conversion status, server logs and error reports used to run and secure\n    the service.\n- category: behavioral\n  text: Referral data — aggregate article readership and visits to the converter.\npurposes:\n- purpose: Providing the service\n  text: Providing the service — your account, converting statements, your history and exports, billing, and account\n    emails such as verification, receipts and usage summaries.\n- purpose: Security and reliability\n  text: Keeping the service secure and working — server logs, error monitoring and abuse prevention.\n- purpose: Referral analytics\n  text: Understanding how people find us — referral and readership data.\n- purpose: Accounting records\n  text: 'Keeping invoices and accounting records — Lawful basis: our legal obligations under UK tax law.'\nretention:\n- scope: Source PDFs\n  period: immediately after processing\n  text: Source PDFs — deleted from our storage\
  \ immediately after processing.\n- scope: Extracted rows and exports\n  period: 30 minutes, 1 hour (default), 24 hours, 7 days or 30 days\n  text: 'Extracted rows and exports — deleted on your team''s retention setting: 30 minutes, 1 hour (default), 24\n    hours, 7 days or 30 days.'\n- scope: Guest conversions\n  period: 24 hours\n  text: Guest conversions expire within 24 hours.\n- scope: Server logs\n  period: 7 days\n  text: Server logs — kept for up to 7 days.\n- scope: Error and performance reports\n  period: 90 days\n  text: Error and performance reports are kept by Laravel Nightwatch for up to 90 days.\n- scope: Emails\n  period: 45 days\n  text: Emails — Postmark, which delivers our emails, keeps their content and delivery records for 45 days.\n- scope: Backups\n  period: 7 days\n  text: Backups — database backups are kept for 7 days, so deleted data can remain in a backup for up to 7 days\n    before it is overwritten.\n- scope: Invoices and accounting records\n  period: normally\
  \ six years\n  text: Account data — kept while your account exists and deleted when you delete it, except invoices and accounting\n    records, which we keep for as long as UK tax law requires (normally six years).\nresidency:\n- region: United Kingdom\n  text: Our servers and file storage are in London.\ntransfers:\n- mechanism: other\n  text: the UK–US data bridge where the provider is certified, or the UK International Data Transfer Addendum to\n    the EU standard contractual clauses.\nsubprocessors:\n  url: null\n  text: 'We share data only with the processors needed to run NoRekey, under data processing agreements: Laravel\n    Cloud — application hosting and databases, in London.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: In-app deletion of conversions, teams and account, or email support@norekey.com\n  text: 'Much of this you can do directly in the app: retention is under your control, and you can delete conversions,\n    teams and your account yourself.'\n\
  rights:\n- right: Access\n  text: Under UK GDPR you can ask for a copy of your personal data\n- right: Rectification and erasure\n  text: have it corrected or deleted\n- right: Restriction and objection\n  text: restrict or object to how we use it\n- right: Portability\n  text: take your data elsewhere\n- right: Complaint\n  text: You can also complain to the Information Commissioner's Office (ico.org.uk).\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell personal data and never share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/norekey/privacy/norekey-privacy-policy.yml
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
summary_line: 28 quoted statements, read from NoRekey's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Data Conversion
- Software-as-a-Service
- Banking
---
