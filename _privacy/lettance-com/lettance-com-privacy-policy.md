---
api_specs:
- filename: lettance-com-openapi.json
  format: json
  label: Lettance Public API
  slug: lettance-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lettance-com/openapi/lettance-com-openapi.json
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address, to sign you in and to send reminders and the weekly summary you can turn off.
  - category: other
    text: Property and tenancy details you enter (address, dates, rent, deposit, tenants' names and email addresses) and documents you upload
  - category: financial
    text: Bank CSV files are parsed to let you select rent received; we do not store the file or send it to an AI model.
  - category: device
    text: Vercel, our host, records basic details of each request, such as the time, page, response status, IP address and browser or app type
  deletion:
    route: Settings
    text: You can delete a property or your whole account from Settings.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: rule checks and evidence record
    text: to work out which rules apply and keep your evidence record
  - purpose: sign-in and reminders
    text: Your email address, to sign you in and to send reminders and the weekly summary you can turn off.
  residency:
  - region: London
    text: The app runs in London and the database is in London.
  retention:
  - period: while you have an account
    scope: account data
    text: We keep your account data while you have an account.
  - period: 90 days
    scope: error records
    text: Error records are deleted 90 days after the error last happened.
  - period: 13 months
    scope: assistant use of public rules server
    text: Records of assistant use of the public rules server are deleted after 13 months.
  - period: 30 days
    scope: outgoing document email summaries
    text: for 30 days so failed delivery can be retried or investigated.
  rights:
  - right: access, correction, deletion, objection and restriction
    text: You can ask for a copy of your data, ask us to correct or delete it, object to processing or ask us to restrict it.
  role:
    text: Lettance is operated by Andrew Wilkinson trading as Galleon Labs, responsible for handling the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data or use it for advertising.
  subprocessors:
    text: Vercel (hosting, file storage and the AI gateway), Neon (database) and Resend (sending email, and receiving email sent to a home's address).
    url: null
  transfers:
  - mechanism: other
    text: Those providers, and our file storage and email providers, may process data outside the UK.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: lettance-com
provenance_date: '2026-11-09'
provider_name: lettance-com
provider_slug: lettance-com
slug: lettance-com-privacy-policy
source_date: '2026-11-09'
source_filename: lettance-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://lettance.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: lettance-com\naid: lettance-com\nurl: https://lettance.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Lettance is operated by Andrew Wilkinson trading as Galleon Labs, responsible for handling the personal\n    data described here.\ndata_categories:\n- category: contact\n  text: Your email address, to sign you in and to send reminders and the weekly summary you can turn off.\n- category: other\n  text: Property and tenancy details you enter (address, dates, rent, deposit, tenants' names and email addresses)\n    and documents you upload\n- category: financial\n  text: Bank CSV\
  \ files are parsed to let you select rent received; we do not store the file or send it to an AI\n    model.\n- category: device\n  text: Vercel, our host, records basic details of each request, such as the time, page, response status, IP address\n    and browser or app type\npurposes:\n- purpose: rule checks and evidence record\n  text: to work out which rules apply and keep your evidence record\n- purpose: sign-in and reminders\n  text: Your email address, to sign you in and to send reminders and the weekly summary you can turn off.\nretention:\n- scope: account data\n  period: while you have an account\n  text: We keep your account data while you have an account.\n- scope: error records\n  period: 90 days\n  text: Error records are deleted 90 days after the error last happened.\n- scope: assistant use of public rules server\n  period: 13 months\n  text: Records of assistant use of the public rules server are deleted after 13 months.\n- scope: outgoing document email summaries\n  period:\
  \ 30 days\n  text: for 30 days so failed delivery can be retried or investigated.\nresidency:\n- region: London\n  text: The app runs in London and the database is in London.\ntransfers:\n- mechanism: other\n  text: Those providers, and our file storage and email providers, may process data outside the UK.\nsubprocessors:\n  url: null\n  text: Vercel (hosting, file storage and the AI gateway), Neon (database) and Resend (sending email, and receiving\n    email sent to a home's address).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings\n  text: You can delete a property or your whole account from Settings.\nrights:\n- right: access, correction, deletion, objection and restriction\n  text: You can ask for a copy of your data, ask us to correct or delete it, object to processing or ask us to restrict\n    it.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data or use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/lettance-com/privacy/lettance-com-privacy-policy.yml
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
summary_line: 17 quoted statements, read from lettance-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Leasing
- Subscription
- Automation
---
