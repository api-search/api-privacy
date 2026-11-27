---
api_specs:
- filename: mailkite-dev-openapi-generated.yml
  format: yaml
  label: mailkite-dev API
  slug: mailkite-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailkite-dev/openapi/_ae-authored/mailkite-dev-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data — your email address, password hash (or Google sign-in identifier)
  - category: contact
    text: 'Contacts you add — your address book: contacts you create, import (CSV/vCard), or sync from a connected provider such as Google'
  - category: communication
    text: Email content we process — messages sent to your verified domains (sender, recipients, subject, body, headers, attachments)
  - category: behavioral
    text: Deliverability signals — the sending patterns and delivery outcomes of your outbound mail
  - category: financial
    text: Usage and billing data — domains, message counts and metering, plan, and the Stripe customer/subscription identifiers tied to your account.
  - category: device
    text: Site and product telemetry — a session cookie to keep you signed in, and aggregate analytics about which calls-to-action are clicked.
  deletion:
    route: Delete account or domain in dashboard, or email support
    text: You can access, export, correct, or delete your account data. Deleting a domain removes it and its routes; deleting your account removes your account data and stops processing.
  dpa:
    available: true
    text: we act on your instructions under the terms of our Data Processing Addendum
    url: null
  purposes:
  - purpose: Deliver the product
    text: parse and route inbound mail to your webhook, send your outbound mail, and authenticate your API requests
  - purpose: Optimize deliverability
    text: analyze your sending patterns and delivery signals, including with automated systems and AI, to select the best-performing IP pools and sending infrastructure
  - purpose: Billing
    text: meter usage and charge your plan and any domain registrations through Stripe
  - purpose: Support, security, and abuse prevention
    text: diagnose delivery issues, protect the platform, and enforce our Terms (including anti-spam)
  residency:
  - region: United States
    text: Data is processed on our providers' global infrastructure, which includes the United States; contact us about region requirements for enterprise needs.
  retention:
  - period: null
    scope: Parsed email copy by plan
    text: 7 days on Free, 30 on Pro, 90 on Scale, and 365 on Business
  - period: 7 days
    scope: Inbound attachments
    text: Inbound attachments are deleted after 7 days.
  - period: null
    scope: Account and billing records
    text: We keep account and billing records for as long as your account is active and as required for legal, tax, and accounting purposes.
  rights:
  - right: Access, export, correct, delete
    text: You can access, export, correct, or delete your account data.
  - right: Right to know / access
    text: Right to know / access the specific pieces and categories of personal information we hold about you.
  - right: Right to correct
    text: Right to correct inaccurate personal information.
  - right: Right to lodge complaint
    text: You have the right to lodge a complaint with your local data protection authority.
  - right: Right to non-discrimination
    text: Right to non-discrimination for exercising any of these rights.
  role:
    text: For email we process on your behalf, you are the controller and MailKite is the processor
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information (as those terms are defined by the CCPA), and have not done so in the preceding 12 months.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on Standard Contractual Clauses and, where applicable, the EU-U.S. and UK-U.S. Data Privacy Framework as the transfer mechanism with each subprocessor.
  - mechanism: DPF
    text: the EU-U.S. and UK-U.S. Data Privacy Framework as the transfer mechanism with each subprocessor
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: mailkite-dev
provenance_date: '2026-11-10'
provider_name: mailkite-dev
provider_slug: mailkite-dev
slug: mailkite-dev-privacy-policy
source_date: '2026-11-10'
source_filename: mailkite-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mailkite.dev/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: mailkite-dev\naid: mailkite-dev\nurl: https://mailkite.dev/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For email we process on your behalf, you are the controller and MailKite is the processor\ndata_categories:\n- category: identifying\n  text: Account data — your email address, password hash (or Google sign-in identifier)\n- category: contact\n  text: 'Contacts you add — your address book: contacts you create, import (CSV/vCard), or sync from a connected\n    provider such as Google'\n- category: communication\n  text: Email content we process — messages sent to your verified domains\
  \ (sender, recipients, subject, body, headers,\n    attachments)\n- category: behavioral\n  text: Deliverability signals — the sending patterns and delivery outcomes of your outbound mail\n- category: financial\n  text: Usage and billing data — domains, message counts and metering, plan, and the Stripe customer/subscription\n    identifiers tied to your account.\n- category: device\n  text: Site and product telemetry — a session cookie to keep you signed in, and aggregate analytics about which\n    calls-to-action are clicked.\npurposes:\n- purpose: Deliver the product\n  text: parse and route inbound mail to your webhook, send your outbound mail, and authenticate your API requests\n- purpose: Optimize deliverability\n  text: analyze your sending patterns and delivery signals, including with automated systems and AI, to select the\n    best-performing IP pools and sending infrastructure\n- purpose: Billing\n  text: meter usage and charge your plan and any domain registrations through Stripe\n\
  - purpose: Support, security, and abuse prevention\n  text: diagnose delivery issues, protect the platform, and enforce our Terms (including anti-spam)\nretention:\n- scope: Parsed email copy by plan\n  period: null\n  text: 7 days on Free, 30 on Pro, 90 on Scale, and 365 on Business\n- scope: Inbound attachments\n  period: 7 days\n  text: Inbound attachments are deleted after 7 days.\n- scope: Account and billing records\n  period: null\n  text: We keep account and billing records for as long as your account is active and as required for legal, tax,\n    and accounting purposes.\nresidency:\n- region: United States\n  text: Data is processed on our providers' global infrastructure, which includes the United States; contact us\n    about region requirements for enterprise needs.\ntransfers:\n- mechanism: SCC\n  text: We rely on Standard Contractual Clauses and, where applicable, the EU-U.S. and UK-U.S. Data Privacy Framework\n    as the transfer mechanism with each subprocessor.\n- mechanism:\
  \ DPF\n  text: the EU-U.S. and UK-U.S. Data Privacy Framework as the transfer mechanism with each subprocessor\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: we act on your instructions under the terms of our Data Processing Addendum\ndeletion:\n  route: Delete account or domain in dashboard, or email support\n  text: You can access, export, correct, or delete your account data. Deleting a domain removes it and its routes;\n    deleting your account removes your account data and stops processing.\nrights:\n- right: Access, export, correct, delete\n  text: You can access, export, correct, or delete your account data.\n- right: Right to know / access\n  text: Right to know / access the specific pieces and categories of personal information we hold about you.\n- right: Right to correct\n  text: Right to correct inaccurate personal information.\n- right: Right to lodge complaint\n  text: You have the right to lodge a complaint with your local data\
  \ protection authority.\n- right: Right to non-discrimination\n  text: Right to non-discrimination for exercising any of these rights.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal information (as those terms are defined by the CCPA), and have not done\n    so in the preceding 12 months.\n"
source_yaml_url: https://artifacts.apis.io/mailkite-dev/privacy/mailkite-dev-privacy-policy.yml
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
summary_line: 25 quoted statements, read from mailkite-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email
- Software-as-a-Service
- Communications
---
