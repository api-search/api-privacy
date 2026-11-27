---
api_specs:
- filename: auditae-app-billing-api-openapi.yml
  format: yaml
  label: AuditAE Billing API
  slug: auditae-app-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auditae-app/openapi/auditae-app-billing-api-openapi.yml
- filename: auditae-app-citations-api-openapi.yml
  format: yaml
  label: AuditAE Citations API
  slug: auditae-app-citations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auditae-app/openapi/auditae-app-citations-api-openapi.yml
- filename: auditae-app-schema-api-openapi.yml
  format: yaml
  label: AuditAE Schema API
  slug: auditae-app-schema-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auditae-app/openapi/auditae-app-schema-api-openapi.yml
- filename: auditae-app-technical-api-openapi.yml
  format: yaml
  label: AuditAE Technical API
  slug: auditae-app-technical-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/auditae-app/openapi/auditae-app-technical-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address, and sign-in details, handled by our authentication provider (Clerk)
  - category: financial
    text: We keep your Stripe customer ID, a saved-card reference if you turn on auto-refill, your auto-refill settings, and a record of each purchase and each billable action (amount, date, and what it was for).
  - category: behavioral
    text: Analytics and advertising cookies stay off unless you accept them
  - category: location
    text: approximate location derived from IP address
  - category: communication
    text: Your messages to the in-app assistant and its replies, files or designs you upload to it
  - category: device
    text: Server logs (IP address, browser, pages and API endpoints requested, errors, and times)
  deletion:
    route: Email support@auditae.app or request deletion of account
    text: deleted within 30 days after you ask us to delete your account
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the Service
    text: 'To provide the Service you asked for: run audits and checks, operate AEBOT, act on connected accounts at your direction, send reports, and keep your workspace working (performance of our contract with you).'
  - purpose: billing and legal obligations
    text: To bill you , keep accounting records, and meet tax and legal obligations (contract and legal obligation).
  - purpose: security
    text: 'To keep the Service secure : detect bots, enforce rate limits and free-tier limits, prevent fraud and abuse, and debug problems'
  residency:
  - region: United States
    text: AuditAE is based in the United States, and we and our service providers process data in the United States and other countries.
  retention:
  - period: as long as your account is open
    scope: Account data, content, and history
    text: 'Account data, content, and history : for as long as your account is open, and deleted within 30 days after you ask us to delete your account, except as below.'
  - period: generally up to 7 years
    scope: Billing and payment records
    text: 'Billing and payment records : for as long as tax and accounting laws require (generally up to 7 years), even after your account is deleted.'
  - period: 180 days
    scope: AI assistant, agent, and API call log
    text: 'AI assistant, agent, and API call log : 180 days.'
  rights:
  - right: access, correct, export, delete
    text: Everyone can ask us to access, correct, export, or delete their personal data
  - right: unsubscribe from marketing emails
    text: can unsubscribe from marketing emails, change cookie choices, disconnect connected accounts, and delete AEBOT notes
  - right: object or restrict processing (EEA, UK, Swiss)
    text: EEA, UK, and Swiss residents also have the right to object to or restrict processing based on legitimate interests
  - right: opt out of sale or sharing (US states)
    text: to opt out of its “sale” or “sharing” for cross-context behavioral advertising and of targeted advertising
  - right: complain to data protection authority
    text: and to complain to their local data protection authority
  role:
    text: AuditAE LLC, a Georgia limited liability company (Georgia control no. 26219000) (“AuditAE,” “we,” “us”), which is the data controller for the personal data described here, except where we process data for customers as described in section 9.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell your personal information.
  subprocessors:
    text: 'Service providers that process data for us under contract, only to provide their service: Clerk: sign-in and account management Stripe: payments, saved cards, receipts, and agent payments Supabase: our database'
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards, including the European Commission’s Standard Contractual Clauses and our providers’ data processing terms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AuditAE
provenance_date: '2026-11-09'
provider_name: AuditAE
provider_slug: auditae-app
slug: auditae-app-privacy-policy
source_date: '2026-11-09'
source_filename: auditae-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://auditae.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AuditAE\naid: auditae-app\nurl: https://auditae.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: AuditAE LLC, a Georgia limited liability company (Georgia control no. 26219000) (“AuditAE,” “we,” “us”),\n    which is the data controller for the personal data described here, except where we process data for customers\n    as described in section 9.\ndata_categories:\n- category: identifying\n  text: Your name, email address, and sign-in details, handled by our authentication provider (Clerk)\n- category: financial\n  text: We keep your Stripe customer ID, a saved-card reference if\
  \ you turn on auto-refill, your auto-refill settings,\n    and a record of each purchase and each billable action (amount, date, and what it was for).\n- category: behavioral\n  text: Analytics and advertising cookies stay off unless you accept them\n- category: location\n  text: approximate location derived from IP address\n- category: communication\n  text: Your messages to the in-app assistant and its replies, files or designs you upload to it\n- category: device\n  text: Server logs (IP address, browser, pages and API endpoints requested, errors, and times)\npurposes:\n- purpose: provide the Service\n  text: 'To provide the Service you asked for: run audits and checks, operate AEBOT, act on connected accounts at\n    your direction, send reports, and keep your workspace working (performance of our contract with you).'\n- purpose: billing and legal obligations\n  text: To bill you , keep accounting records, and meet tax and legal obligations (contract and legal obligation).\n- purpose:\
  \ security\n  text: 'To keep the Service secure : detect bots, enforce rate limits and free-tier limits, prevent fraud and abuse,\n    and debug problems'\nretention:\n- scope: Account data, content, and history\n  period: as long as your account is open\n  text: 'Account data, content, and history : for as long as your account is open, and deleted within 30 days after\n    you ask us to delete your account, except as below.'\n- scope: Billing and payment records\n  period: generally up to 7 years\n  text: 'Billing and payment records : for as long as tax and accounting laws require (generally up to 7 years),\n    even after your account is deleted.'\n- scope: AI assistant, agent, and API call log\n  period: 180 days\n  text: 'AI assistant, agent, and API call log : 180 days.'\nresidency:\n- region: United States\n  text: AuditAE is based in the United States, and we and our service providers process data in the United States\n    and other countries.\ntransfers:\n- mechanism: SCC\n  text:\
  \ we rely on appropriate safeguards, including the European Commission’s Standard Contractual Clauses and\n    our providers’ data processing terms.\nsubprocessors:\n  url: null\n  text: 'Service providers that process data for us under contract, only to provide their service: Clerk: sign-in\n    and account management Stripe: payments, saved cards, receipts, and agent payments Supabase: our database'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@auditae.app or request deletion of account\n  text: deleted within 30 days after you ask us to delete your account\nrights:\n- right: access, correct, export, delete\n  text: Everyone can ask us to access, correct, export, or delete their personal data\n- right: unsubscribe from marketing emails\n  text: can unsubscribe from marketing emails, change cookie choices, disconnect connected accounts, and delete\n    AEBOT notes\n- right: object or restrict processing (EEA, UK, Swiss)\n  text: EEA, UK, and Swiss\
  \ residents also have the right to object to or restrict processing based on legitimate\n    interests\n- right: opt out of sale or sharing (US states)\n  text: to opt out of its “sale” or “sharing” for cross-context behavioral advertising and of targeted advertising\n- right: complain to data protection authority\n  text: and to complain to their local data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/auditae-app/privacy/auditae-app-privacy-policy.yml
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
summary_line: 23 quoted statements, read from AuditAE's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- SEO
- Marketing
- Software-as-a-Service
- Visibility
---
