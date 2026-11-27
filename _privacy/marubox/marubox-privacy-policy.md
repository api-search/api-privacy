---
api_specs:
- filename: marubox-account-api-openapi.yml
  format: yaml
  label: Business Box Account API
  slug: marubox-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marubox/openapi/marubox-account-api-openapi.yml
- filename: marubox-bookings-api-openapi.yml
  format: yaml
  label: Business Box Bookings API
  slug: marubox-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marubox/openapi/marubox-bookings-api-openapi.yml
- filename: marubox-event-types-api-openapi.yml
  format: yaml
  label: Business Box Event types API
  slug: marubox-event-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marubox/openapi/marubox-event-types-api-openapi.yml
- filename: marubox-invites-api-openapi.yml
  format: yaml
  label: Business Box Invites API
  slug: marubox-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marubox/openapi/marubox-invites-api-openapi.yml
- filename: marubox-webhooks-api-openapi.yml
  format: yaml
  label: Business Box Webhooks API
  slug: marubox-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marubox/openapi/marubox-webhooks-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, email address, profile picture and the provider's account identifier
  - category: contact
    text: name, email address, optional phone number, answers to the questions you ask, any note they add
  - category: financial
    text: the amount, currency, status, the Stripe identifiers and the receipt link
  - category: location
    text: your IP address, your browser's user agent, your sign-in sessions
  - category: behavioral
    text: an audit log of security-relevant actions such as signing in, connecting a calendar or changing billing
  - category: communication
    text: the list of calendars in that account, the busy periods we use to work out your free slots
  deletion:
    route: delete account from Settings page
    text: You can delete your account, and with it your data, from the Settings page.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: show available times and manage bookings
    text: We use this data to show your available times, to create and update calendar events for bookings, to send confirmations, reminders, receipts and service notices
  - purpose: subscription payment
    text: to take your subscription payment
  - purpose: security and abuse investigation
    text: to keep the service secure and to investigate abuse, and to meet our legal obligations
  residency:
  - region: Japan
    text: The service's database runs on our own server in Japan
  retention:
  - period: null
    scope: sign-in sessions
    text: Sign-in sessions expire after thirty days of inactivity and ninety days in all cases.
  - period: until you delete your account
    scope: bookings and payment records
    text: Bookings and their payment records are kept as your business record until you delete your account.
  - period: within minutes
    scope: short-lived sign-in records
    text: The short-lived records used during sign-in expire within minutes
  rights:
  - right: access and correction
    text: You can see and correct most of your data in the app at any time.
  - right: deletion
    text: You can delete your account, and with it your data, from the Settings page.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and we do not share it for anyone else's marketing.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Google, Microsoft and Stripe are international providers and may process data outside that region under their own safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Business Box
provenance_date: '2026-11-10'
provider_name: Business Box
provider_slug: marubox
slug: marubox-privacy-policy
source_date: '2026-11-10'
source_filename: marubox-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://marubox.jp/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Business Box\naid: marubox\nurl: https://marubox.jp/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your name, email address, profile picture and the provider's account identifier\n- category: contact\n  text: name, email address, optional phone number, answers to the questions you ask, any note they add\n- category: financial\n  text: the amount, currency, status, the Stripe identifiers and the receipt link\n- category: location\n  text: your IP address, your browser's user agent, your sign-in sessions\n- category: behavioral\n\
  \  text: an audit log of security-relevant actions such as signing in, connecting a calendar or changing billing\n- category: communication\n  text: the list of calendars in that account, the busy periods we use to work out your free slots\npurposes:\n- purpose: show available times and manage bookings\n  text: We use this data to show your available times, to create and update calendar events for bookings, to send\n    confirmations, reminders, receipts and service notices\n- purpose: subscription payment\n  text: to take your subscription payment\n- purpose: security and abuse investigation\n  text: to keep the service secure and to investigate abuse, and to meet our legal obligations\nretention:\n- scope: sign-in sessions\n  period: null\n  text: Sign-in sessions expire after thirty days of inactivity and ninety days in all cases.\n- scope: bookings and payment records\n  period: until you delete your account\n  text: Bookings and their payment records are kept as your business record\
  \ until you delete your account.\n- scope: short-lived sign-in records\n  period: within minutes\n  text: The short-lived records used during sign-in expire within minutes\nresidency:\n- region: Japan\n  text: The service's database runs on our own server in Japan\ntransfers:\n- mechanism: other\n  text: Google, Microsoft and Stripe are international providers and may process data outside that region under\n    their own safeguards.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete account from Settings page\n  text: You can delete your account, and with it your data, from the Settings page.\nrights:\n- right: access and correction\n  text: You can see and correct most of your data in the app at any time.\n- right: deletion\n  text: You can delete your account, and with it your data, from the Settings page.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and we do not share it for anyone\
  \ else's marketing.\n"
source_yaml_url: https://artifacts.apis.io/marubox/privacy/marubox-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Business Box's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Booking
- Payments
- Calendar
- Japan
---
