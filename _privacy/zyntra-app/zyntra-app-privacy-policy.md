---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account: your email address and, when you sign in with Google or GitHub, the name, profile picture and account identifier that provider passes on.'
  - category: financial
    text: 'Billing: Stripe passes us your customer and subscription identifiers and the status of payments. We never see or store your card details.'
  - category: communication
    text: 'Email content: for every email delivered to your team''s addresses, the sender, recipients, subject, text and HTML body, headers, the links found in it, and its attachments.'
  - category: device
    text: 'Technical: IP addresses and request logs on our servers, needed for security and to diagnose problems.'
  - category: behavioral
    text: 'Analytics: this website (zyntra.app) and the dashboard at app.zyntra.app load Google Tag Manager, which records which pages you open, where you came from, your browser and device, and roughly where you are.'
  deletion:
    route: Delete emails via the API, or write to the contact address to delete your account
    text: You can delete any email earlier through the API.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Running the account and delivering mail
    text: 'Running your account, delivering mail to your inboxes and serving it over the API, the dashboard and the MCP server: performance of our contract with you (Art. 6(1)(b) GDPR).'
  - purpose: Billing and tax records
    text: 'Billing, invoices and tax records: our legal obligations (Art. 6(1)(c)).'
  - purpose: Security and website analytics
    text: 'Security, abuse prevention, service emails about your account, and understanding how the website and the dashboard are used: our legitimate interest in running a secure, working service (Art. 6(1)(f)).'
  residency:
  - region: European Union
    text: The service's database and email content are stored on servers in the European Union.
  retention:
  - period: 1 day
    scope: Email content, temporary inbox
    text: mail to a temporary inbox after 1 day
  - period: 7 days
    scope: Email content, permanent inbox on Free
    text: mail to a permanent inbox after 7 days on Free
  - period: 30 days
    scope: Email content, permanent inbox on Starter
    text: 30 days on Starter
  - period: 90 days
    scope: Email content, permanent inbox on Pro
    text: 90 days on Pro
  - period: null
    scope: Account data
    text: 'Account data: until your account is deleted.'
  - period: as long as tax law requires
    scope: Billing records
    text: 'Billing records: for as long as tax law requires (in Poland, as a rule, five years).'
  rights:
  - right: access
    text: You have the right to access your data and get a copy of it
  - right: rectification or erasure
    text: to have it corrected or erased
  - right: restriction or objection
    text: to restrict or object to its processing
  - right: portability
    text: to move it to another provider
  role:
    text: We are the controller of the account data described below.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: Those transfers rely on the European Commission's adequacy decisions, including the EU–US Data Privacy Framework
  - mechanism: SCC
    text: or on its Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Zyntra
provenance_date: '2026-11-10'
provider_name: Zyntra
provider_slug: zyntra-app
slug: zyntra-app-privacy-policy
source_date: '2026-11-10'
source_filename: zyntra-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://zyntra.app/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Zyntra\naid: zyntra-app\nurl: https://zyntra.app/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller of the account data described below.\ndata_categories:\n- category: contact\n  text: 'Account: your email address and, when you sign in with Google or GitHub, the name, profile picture and\n    account identifier that provider passes on.'\n- category: financial\n  text: 'Billing: Stripe passes us your customer and subscription identifiers and the status of payments. We never\n    see or store your card details.'\n- category: communication\n  text: 'Email content: for\
  \ every email delivered to your team''s addresses, the sender, recipients, subject, text\n    and HTML body, headers, the links found in it, and its attachments.'\n- category: device\n  text: 'Technical: IP addresses and request logs on our servers, needed for security and to diagnose problems.'\n- category: behavioral\n  text: 'Analytics: this website (zyntra.app) and the dashboard at app.zyntra.app load Google Tag Manager, which\n    records which pages you open, where you came from, your browser and device, and roughly where you are.'\npurposes:\n- purpose: Running the account and delivering mail\n  text: 'Running your account, delivering mail to your inboxes and serving it over the API, the dashboard and the\n    MCP server: performance of our contract with you (Art. 6(1)(b) GDPR).'\n- purpose: Billing and tax records\n  text: 'Billing, invoices and tax records: our legal obligations (Art. 6(1)(c)).'\n- purpose: Security and website analytics\n  text: 'Security, abuse prevention, service\
  \ emails about your account, and understanding how the website and the\n    dashboard are used: our legitimate interest in running a secure, working service (Art. 6(1)(f)).'\nretention:\n- scope: Email content, temporary inbox\n  period: 1 day\n  text: mail to a temporary inbox after 1 day\n- scope: Email content, permanent inbox on Free\n  period: 7 days\n  text: mail to a permanent inbox after 7 days on Free\n- scope: Email content, permanent inbox on Starter\n  period: 30 days\n  text: 30 days on Starter\n- scope: Email content, permanent inbox on Pro\n  period: 90 days\n  text: 90 days on Pro\n- scope: Account data\n  period: null\n  text: 'Account data: until your account is deleted.'\n- scope: Billing records\n  period: as long as tax law requires\n  text: 'Billing records: for as long as tax law requires (in Poland, as a rule, five years).'\nresidency:\n- region: European Union\n  text: The service's database and email content are stored on servers in the European Union.\ntransfers:\n\
  - mechanism: adequacy\n  text: Those transfers rely on the European Commission's adequacy decisions, including the EU–US Data Privacy Framework\n- mechanism: SCC\n  text: or on its Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete emails via the API, or write to the contact address to delete your account\n  text: You can delete any email earlier through the API.\nrights:\n- right: access\n  text: You have the right to access your data and get a copy of it\n- right: rectification or erasure\n  text: to have it corrected or erased\n- right: restriction or objection\n  text: to restrict or object to its processing\n- right: portability\n  text: to move it to another provider\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/zyntra-app/privacy/zyntra-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Zyntra's own page on 2026-11-10.
synthetic: false
tags:
- Email Testing
- Automated Tests
- QA
- Password Reset
- Magic Link
---
