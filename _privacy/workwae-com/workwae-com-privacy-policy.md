---
api_specs:
- filename: workwae-com-v1-openapi.json
  format: json
  label: Workwae API V1 API
  slug: workwae-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workwae-com/openapi/_original/workwae-com-v1-openapi.json
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, password (stored only as a salted hash) and sign-in sessions.
  - category: contact
    text: contacts and contact groups, including names, email addresses, phone numbers, addresses, organizations and photos.
  - category: communication
    text: message bodies and attachments, drafts, and send-as identities.
  - category: financial
    text: we receive the subscription and payment status, never your card number.
  - category: location
    text: an approximate location (country, and where available region and city) provided by Cloudflare
  - category: behavioral
    text: we record when a recipient opens the message or follows a link
  - category: device
    text: browser user agent and request headers
  deletion:
    route: console and API
    text: Customers can export or delete their data in the console and API.
  dpa:
    available: true
    text: Data Processing Addendum
    url: null
  purposes:
  - purpose: provide the Service
    text: 'provide the Service: sync, index, search, store and display mail, calendars and contacts; send mail; create, update and cancel meetings'
  - purpose: AI features turned on by a Customer
    text: run optional AI features a Customer has turned on
  - purpose: security and abuse prevention
    text: keep the Service secure, prevent abuse and fraud, and debug failures
  - purpose: billing
    text: bill Customers and enforce plan limits
  residency:
  - region: United States
    text: Data is stored on servers in the United States.
  retention:
  - period: while the account stays connected
    scope: Connected accounts
    text: 'Connected accounts : data is kept while the account stays connected.'
  - period: 90 days
    scope: Tracking events
    text: 'Tracking events : kept 90 days.'
  - period: 365 days
    scope: Audit log
    text: 'Audit log : kept 365 days.'
  - period: up to 35 days
    scope: Backups
    text: 'Backups : encrypted database backups are kept for up to 35 days'
  rights:
  - right: access, correction, export, deletion and portability
    text: you may have the right to know, access, correct, delete or port your information
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information for cross-context behavioral advertising.
  subprocessors:
    text: The current list, with what each provider receives and where, is at workwae.com/subprocessors .
    url: workwae.com/subprocessors
  transfers:
  - mechanism: other
    text: Workwae is based in the United States and processes data there.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: workwae-com
provenance_date: '2026-11-10'
provider_name: workwae-com
provider_slug: workwae-com
slug: workwae-com-privacy-policy
source_date: '2026-11-10'
source_filename: workwae-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://workwae.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: workwae-com\naid: workwae-com\nurl: https://workwae.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email address, password (stored only as a salted hash) and sign-in sessions.\n- category: contact\n  text: contacts and contact groups, including names, email addresses, phone numbers, addresses, organizations and\n    photos.\n- category: communication\n  text: message bodies and attachments, drafts, and send-as identities.\n- category: financial\n  text: we receive the subscription and payment status, never your card number.\n\
  - category: location\n  text: an approximate location (country, and where available region and city) provided by Cloudflare\n- category: behavioral\n  text: we record when a recipient opens the message or follows a link\n- category: device\n  text: browser user agent and request headers\npurposes:\n- purpose: provide the Service\n  text: 'provide the Service: sync, index, search, store and display mail, calendars and contacts; send mail; create,\n    update and cancel meetings'\n- purpose: AI features turned on by a Customer\n  text: run optional AI features a Customer has turned on\n- purpose: security and abuse prevention\n  text: keep the Service secure, prevent abuse and fraud, and debug failures\n- purpose: billing\n  text: bill Customers and enforce plan limits\nretention:\n- scope: Connected accounts\n  period: while the account stays connected\n  text: 'Connected accounts : data is kept while the account stays connected.'\n- scope: Tracking events\n  period: 90 days\n  text: 'Tracking\
  \ events : kept 90 days.'\n- scope: Audit log\n  period: 365 days\n  text: 'Audit log : kept 365 days.'\n- scope: Backups\n  period: up to 35 days\n  text: 'Backups : encrypted database backups are kept for up to 35 days'\nresidency:\n- region: United States\n  text: Data is stored on servers in the United States.\ntransfers:\n- mechanism: other\n  text: Workwae is based in the United States and processes data there.\nsubprocessors:\n  url: workwae.com/subprocessors\n  text: The current list, with what each provider receives and where, is at workwae.com/subprocessors .\ndpa:\n  available: true\n  url: null\n  text: Data Processing Addendum\ndeletion:\n  route: console and API\n  text: Customers can export or delete their data in the console and API.\nrights:\n- right: access, correction, export, deletion and portability\n  text: you may have the right to know, access, correct, delete or port your information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal\
  \ information for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/workwae-com/privacy/workwae-com-privacy-policy.yml
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
summary_line: 22 quoted statements, read from workwae-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Email
- Calendar
- Contacts
- Scheduling
- Artificial Intelligence
---
