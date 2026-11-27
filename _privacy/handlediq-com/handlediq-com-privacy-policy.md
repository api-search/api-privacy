---
api_specs:
- filename: handlediq-com-booking-status-api-openapi.yml
  format: yaml
  label: handlediq-com Booking Status API
  slug: handlediq-com-booking-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handlediq-com/openapi/handlediq-com-booking-status-api-openapi.yml
- filename: handlediq-com-cancel-booking-api-openapi.yml
  format: yaml
  label: handlediq-com Cancel Booking API
  slug: handlediq-com-cancel-booking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handlediq-com/openapi/handlediq-com-cancel-booking-api-openapi.yml
- filename: handlediq-com-find-help-api-openapi.yml
  format: yaml
  label: handlediq-com Find Help API
  slug: handlediq-com-find-help-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handlediq-com/openapi/handlediq-com-find-help-api-openapi.yml
- filename: handlediq-com-get-quote-api-openapi.yml
  format: yaml
  label: handlediq-com Get Quote API
  slug: handlediq-com-get-quote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handlediq-com/openapi/handlediq-com-get-quote-api-openapi.yml
- filename: handlediq-com-hold-time-api-openapi.yml
  format: yaml
  label: handlediq-com Hold Time API
  slug: handlediq-com-hold-time-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handlediq-com/openapi/handlediq-com-hold-time-api-openapi.yml
- filename: handlediq-com-move-booking-api-openapi.yml
  format: yaml
  label: handlediq-com Move Booking API
  slug: handlediq-com-move-booking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handlediq-com/openapi/handlediq-com-move-booking-api-openapi.yml
- filename: handlediq-com-request-service-api-openapi.yml
  format: yaml
  label: handlediq-com Request Service API
  slug: handlediq-com-request-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handlediq-com/openapi/handlediq-com-request-service-api-openapi.yml
- filename: handlediq-com-verify-record-api-openapi.yml
  format: yaml
  label: handlediq-com Verify Record API
  slug: handlediq-com-verify-record-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/handlediq-com/openapi/handlediq-com-verify-record-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, work email and role.
  - category: contact
    text: Names, phone numbers, email addresses and service addresses.
  - category: financial
    text: 'What the shop enters for its own work: jobs, schedules, price book, estimates, invoices, payments recorded, costs, expenses, payroll preparation files and team chat.'
  - category: location
    text: A technician’s location while they share it during a working day
  - category: device
    text: a trusted-device marker if emailed sign-in codes are on
  - category: communication
    text: Texts and emails exchanged with the shop, and written transcripts of calls answered by HandledIQ’s receptionist when the caller agrees.
  - category: other
    text: Keys and permissions for services the owner connects
  deletion:
    route: Passports & export
    text: 'can close the shop from Passports & export: 7 days later it closes, and within 30 days its records are deleted'
  dpa:
    available: true
    text: Data Processing terms
    url: https://app.handlediq.com/legal/data-processing
  purposes:
  - purpose: Run HandledIQ for the shop
    text: 'To run HandledIQ for the shop: keep its records, show its schedule, prepare and send its messages, take its payments through Stripe, and connect the services it chose.'
  - purpose: Account security and support
    text: To keep accounts secure, find and fix problems, and answer support requests.
  - purpose: Legal obligations
    text: To meet legal obligations and enforce our terms.
  residency:
  - region: Virginia, United States
    text: HandledIQ’s app and database run on a server in Virginia
  - region: United States
    text: A standby copy runs on a computer HandledIQ operates in the United States.
  retention:
  - period: while the shop’s account is open
    scope: Shop records
    text: Shop records are kept while the shop’s account is open
  - period: 30 days
    scope: Technician positions
    text: 'Technician positions: 30 days.'
  - period: one day
    scope: Sign-in attempt addresses
    text: 'Sign-in attempt addresses: one day.'
  - period: 12 hours
    scope: Sign-in sessions
    text: Sign-in sessions end after 12 hours, or 30 minutes without use.
  - period: null
    scope: Closed shop records
    text: we delete its records except what the law requires us to keep
  - period: null
    scope: Encrypted backups
    text: Deleted records can remain in encrypted backups until those backups are replaced.
  rights:
  - right: access, correct, delete, copy
    text: Depending on where you live, you may have rights to access, correct, delete or get a copy of your information
  role:
    text: HandledIQ decides how this is used, as this policy says.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information. We do not share it for anyone else’s advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Some subprocessors may process data in other countries under their own safeguards
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: handlediq-com
provenance_date: '2026-11-09'
provider_name: handlediq-com
provider_slug: handlediq-com
slug: handlediq-com-privacy-policy
source_date: '2026-11-09'
source_filename: handlediq-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://app.handlediq.com/legal/privacy.md
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: handlediq-com\naid: handlediq-com\nurl: https://app.handlediq.com/legal/privacy.md\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: HandledIQ decides how this is used, as this policy says.\ndata_categories:\n- category: identifying\n  text: Name, work email and role.\n- category: contact\n  text: Names, phone numbers, email addresses and service addresses.\n- category: financial\n  text: 'What the shop enters for its own work: jobs, schedules, price book, estimates, invoices, payments recorded,\n    costs, expenses, payroll preparation files and team chat.'\n- category: location\n  text: A technician’s\
  \ location while they share it during a working day\n- category: device\n  text: a trusted-device marker if emailed sign-in codes are on\n- category: communication\n  text: Texts and emails exchanged with the shop, and written transcripts of calls answered by HandledIQ’s receptionist\n    when the caller agrees.\n- category: other\n  text: Keys and permissions for services the owner connects\npurposes:\n- purpose: Run HandledIQ for the shop\n  text: 'To run HandledIQ for the shop: keep its records, show its schedule, prepare and send its messages, take\n    its payments through Stripe, and connect the services it chose.'\n- purpose: Account security and support\n  text: To keep accounts secure, find and fix problems, and answer support requests.\n- purpose: Legal obligations\n  text: To meet legal obligations and enforce our terms.\nretention:\n- scope: Shop records\n  period: while the shop’s account is open\n  text: Shop records are kept while the shop’s account is open\n- scope: Technician\
  \ positions\n  period: 30 days\n  text: 'Technician positions: 30 days.'\n- scope: Sign-in attempt addresses\n  period: one day\n  text: 'Sign-in attempt addresses: one day.'\n- scope: Sign-in sessions\n  period: 12 hours\n  text: Sign-in sessions end after 12 hours, or 30 minutes without use.\n- scope: Closed shop records\n  period: null\n  text: we delete its records except what the law requires us to keep\n- scope: Encrypted backups\n  period: null\n  text: Deleted records can remain in encrypted backups until those backups are replaced.\nresidency:\n- region: Virginia, United States\n  text: HandledIQ’s app and database run on a server in Virginia\n- region: United States\n  text: A standby copy runs on a computer HandledIQ operates in the United States.\ntransfers:\n- mechanism: other\n  text: Some subprocessors may process data in other countries under their own safeguards\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: https://app.handlediq.com/legal/data-processing\n\
  \  text: Data Processing terms\ndeletion:\n  route: Passports & export\n  text: 'can close the shop from Passports & export: 7 days later it closes, and within 30 days its records are\n    deleted'\nrights:\n- right: access, correct, delete, copy\n  text: Depending on where you live, you may have rights to access, correct, delete or get a copy of your information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information. We do not share it for anyone else’s advertising.\n"
source_yaml_url: https://artifacts.apis.io/handlediq-com/privacy/handlediq-com-privacy-policy.yml
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
summary_line: 24 quoted statements, read from handlediq-com's own page on 2026-11-09.
synthetic: false
tags:
- Field Service Management
- Software-as-a-Service
- Home Services
- Scheduling
- Payments
- Artificial Intelligence
---
