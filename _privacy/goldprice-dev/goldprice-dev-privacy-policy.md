---
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information. Email address, chosen tier, Stripe customer identifier, and API key metadata (prefix + usage timestamps, never plaintext keys, those are hashed on receipt).
  - category: financial
    text: We receive only billing address, tax identifier (if provided), last four digits of the payment method for reference, and transaction status.
  - category: device
    text: Website analytics. Minimal technical metadata (IP address, user agent, referrer) via our CDN and error-tracking providers.
  - category: behavioral
    text: Signup attribution. When you first visit, we record the campaign parameters and referring URL present in your browser
  - category: communication
    text: Support data. Messages you send to support@goldprice.dev including content, subject, attachments, and metadata.
  deletion:
    route: Dashboard Settings > Delete account, or email support@goldprice.dev
    text: As a signed-in account owner, you can delete your account in dashboard Settings by selecting Delete account and typing the confirmation phrase, or request deletion by email at support@goldprice.dev . Deletion is unavailable while a paid plan is active.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate and maintain the Service
    text: Operate and maintain the Service (authentication, rate limiting, billing reconciliation)
  - purpose: Transactional communications
    text: Send transactional communications (receipts, invoices, dunning, account notifications)
  - purpose: Support and documentation
    text: Respond to support inquiries and improve our documentation
  - purpose: Abuse detection and security
    text: Detect abuse, enforce rate limits, and investigate security incidents
  - purpose: Marketing with opt-in
    text: Send marketing communications only after explicit opt-in (unsubscribe in every message)
  - purpose: Legal compliance
    text: Comply with legal obligations (tax, law-enforcement requests with valid process)
  retention:
  - period: 90 days after closure
    scope: Account data
    text: 'Account data (email, Stripe identifiers, API key metadata): for the duration of your account plus 90 days after closure'
  - period: 18 months
    scope: Support tickets
    text: 'Support tickets : 18 months from the date of the last message in the thread, then auto-purged.'
  - period: 90 days
    scope: API request metadata
    text: 'API request metadata : 90 days in identifiable form, aggregated-anonymous thereafter for capacity planning.'
  - period: 7 years
    scope: Billing records
    text: 'Billing records : retained per tax law requirements in applicable jurisdictions (typically 7 years).'
  rights:
  - right: Access
    text: Access the personal information we hold about you
  - right: Correct
    text: Correct inaccurate or incomplete information
  - right: Delete
    text: Delete your personal information, subject to legal retention requirements
  - right: Export
    text: Export your information in a machine-readable format
  - right: Object
    text: Object to processing based on legitimate interests
  - right: Restrict
    text: Restrict processing while a dispute is resolved
  - right: Withdraw consent for marketing
    text: Withdraw consent for marketing communications (use the unsubscribe link in any marketing email)
  role:
    text: 'This Privacy Policy describes how Nusantara Ventures, LLC ("we", "us", "our"), a Delaware limited liability company with registered office at 1401 Pennsylvania Ave STE 105 #1776, Wilmington, DE 19806, United States, handles personal information'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information. We do not share personal information with advertisers.
  subprocessors:
    text: The current list is maintained at /privacy/subprocessors and updated when subprocessors change.
    url: /privacy/subprocessors
  transfers:
  - mechanism: SCC
    text: For EU/UK data transfers to US-based subprocessors, we rely on Standard Contractual Clauses and the subprocessor's own adequacy mechanisms (e.g., Data Privacy Framework certification where applicable).
  - mechanism: DPF
    text: Data Privacy Framework certification where applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: goldprice-dev
provenance_date: '2026-11-09'
provider_name: goldprice-dev
provider_slug: goldprice-dev
slug: goldprice-dev-privacy-policy
source_date: '2026-11-09'
source_filename: goldprice-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://goldprice.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: goldprice-dev\naid: goldprice-dev\nurl: https://goldprice.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'This Privacy Policy describes how Nusantara Ventures, LLC (\"we\", \"us\", \"our\"), a Delaware limited liability\n    company with registered office at 1401 Pennsylvania Ave STE 105 #1776, Wilmington, DE 19806, United States,\n    handles personal information'\ndata_categories:\n- category: identifying\n  text: Account information. Email address, chosen tier, Stripe customer identifier, and API key metadata (prefix\n    + usage timestamps, never plaintext keys, those are hashed\
  \ on receipt).\n- category: financial\n  text: We receive only billing address, tax identifier (if provided), last four digits of the payment method for\n    reference, and transaction status.\n- category: device\n  text: Website analytics. Minimal technical metadata (IP address, user agent, referrer) via our CDN and error-tracking\n    providers.\n- category: behavioral\n  text: Signup attribution. When you first visit, we record the campaign parameters and referring URL present in\n    your browser\n- category: communication\n  text: Support data. Messages you send to support@goldprice.dev including content, subject, attachments, and metadata.\npurposes:\n- purpose: Operate and maintain the Service\n  text: Operate and maintain the Service (authentication, rate limiting, billing reconciliation)\n- purpose: Transactional communications\n  text: Send transactional communications (receipts, invoices, dunning, account notifications)\n- purpose: Support and documentation\n  text: Respond\
  \ to support inquiries and improve our documentation\n- purpose: Abuse detection and security\n  text: Detect abuse, enforce rate limits, and investigate security incidents\n- purpose: Marketing with opt-in\n  text: Send marketing communications only after explicit opt-in (unsubscribe in every message)\n- purpose: Legal compliance\n  text: Comply with legal obligations (tax, law-enforcement requests with valid process)\nretention:\n- scope: Account data\n  period: 90 days after closure\n  text: 'Account data (email, Stripe identifiers, API key metadata): for the duration of your account plus 90 days\n    after closure'\n- scope: Support tickets\n  period: 18 months\n  text: 'Support tickets : 18 months from the date of the last message in the thread, then auto-purged.'\n- scope: API request metadata\n  period: 90 days\n  text: 'API request metadata : 90 days in identifiable form, aggregated-anonymous thereafter for capacity planning.'\n- scope: Billing records\n  period: 7 years\n  text:\
  \ 'Billing records : retained per tax law requirements in applicable jurisdictions (typically 7 years).'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: For EU/UK data transfers to US-based subprocessors, we rely on Standard Contractual Clauses and the subprocessor's\n    own adequacy mechanisms (e.g., Data Privacy Framework certification where applicable).\n- mechanism: DPF\n  text: Data Privacy Framework certification where applicable\nsubprocessors:\n  url: /privacy/subprocessors\n  text: The current list is maintained at /privacy/subprocessors and updated when subprocessors change.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Dashboard Settings > Delete account, or email support@goldprice.dev\n  text: As a signed-in account owner, you can delete your account in dashboard Settings by selecting Delete account\n    and typing the confirmation phrase, or request deletion by email at support@goldprice.dev . Deletion is unavailable\n    while a paid plan\
  \ is active.\nrights:\n- right: Access\n  text: Access the personal information we hold about you\n- right: Correct\n  text: Correct inaccurate or incomplete information\n- right: Delete\n  text: Delete your personal information, subject to legal retention requirements\n- right: Export\n  text: Export your information in a machine-readable format\n- right: Object\n  text: Object to processing based on legitimate interests\n- right: Restrict\n  text: Restrict processing while a dispute is resolved\n- right: Withdraw consent for marketing\n  text: Withdraw consent for marketing communications (use the unsubscribe link in any marketing email)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information. We do not share personal information with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/goldprice-dev/privacy/goldprice-dev-privacy-policy.yml
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
summary_line: 28 quoted statements, read from goldprice-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Commodities
- Data
---
