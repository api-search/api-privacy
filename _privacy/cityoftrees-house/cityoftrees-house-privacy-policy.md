---
api_specs:
- filename: cityoftrees-house-agent-api-openapi.yml
  format: yaml
  label: City of Trees House Agent API
  slug: cityoftrees-house-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cityoftrees-house/openapi/cityoftrees-house-agent-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: For bookings, we collect contact details, stay dates, guest count, payment method, payment status, and reservation reference.
  - category: device
    text: To run and protect the guest network, we keep a coded device identifier, the device type, and connection times from the network equipment.
  - category: financial
    text: Card, bank, and PayPal credentials are processed by their providers; we do not store full card or bank-account numbers.
  - category: contact
    text: We also send your name, email address, phone number, and stay dates to Truvi, which screens the reservation and provides damage protection.
  - category: behavioral
    text: 'We use PostHog to see how visitors use public pages: which pages they open, what they click, and where they leave.'
  deletion:
    route: Email info@goodreviewsonly.com
    text: Request access or deletion, or opt out of marketing, by emailing info@goodreviewsonly.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: reservations and guest services
    text: To price, hold, confirm, and service reservations; verify guest identity, screen reservations, and arrange damage protection for direct bookings;
  - purpose: email offers
    text: send email offers only after an eligible direct guest separately requests and confirms them;
  - purpose: abuse and fraud prevention
    text: prevent abuse, double-booking, and fraud; and meet tax and legal obligations.
  retention:
  - period: 24 months
    scope: Guest Wi-Fi contact records
    text: Contact records from the earlier Wi-Fi sign-in are deleted automatically within 24 months of the last access request or connection.
  - period: until unsubscribe, deletion request, or when no longer reasonably needed
    scope: Confirmed email subscriptions
    text: Confirmed email subscriptions remain until unsubscribe, deletion request, or when no longer reasonably needed to document and honor the communication choice.
  - period: longer for tax, accounting, dispute, fraud-prevention, or legal obligations
    scope: Booking and payment records
    text: Booking and payment records may be retained longer for tax, accounting, dispute, fraud-prevention, or legal obligations.
  - period: up to 7 days
    scope: Agent API Workers Logs
    text: Cloudflare, which hosts the site, keeps those Workers Logs for up to 7 days.
  - period: 24 hours
    scope: Stored agent quotes
    text: A scheduled job deletes stored quotes 24 hours after they are created.
  rights:
  - right: access, deletion, or marketing opt-out
    text: Request access or deletion, or opt out of marketing, by emailing info@goodreviewsonly.com .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We collect only what is needed and never sell guest data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: City of Trees House
provenance_date: '2026-11-09'
provider_name: City of Trees House
provider_slug: cityoftrees-house
slug: cityoftrees-house-privacy-policy
source_date: '2026-11-09'
source_filename: cityoftrees-house-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cityoftrees.house/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: City of Trees House\naid: cityoftrees-house\nurl: https://cityoftrees.house/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: For bookings, we collect contact details, stay dates, guest count, payment method, payment status, and reservation\n    reference.\n- category: device\n  text: To run and protect the guest network, we keep a coded device identifier, the device type, and connection\n    times from the network equipment.\n- category: financial\n  text: Card, bank, and PayPal credentials are processed by their providers; we do not\
  \ store full card or bank-account\n    numbers.\n- category: contact\n  text: We also send your name, email address, phone number, and stay dates to Truvi, which screens the reservation\n    and provides damage protection.\n- category: behavioral\n  text: 'We use PostHog to see how visitors use public pages: which pages they open, what they click, and where\n    they leave.'\npurposes:\n- purpose: reservations and guest services\n  text: To price, hold, confirm, and service reservations; verify guest identity, screen reservations, and arrange\n    damage protection for direct bookings;\n- purpose: email offers\n  text: send email offers only after an eligible direct guest separately requests and confirms them;\n- purpose: abuse and fraud prevention\n  text: prevent abuse, double-booking, and fraud; and meet tax and legal obligations.\nretention:\n- scope: Guest Wi-Fi contact records\n  period: 24 months\n  text: Contact records from the earlier Wi-Fi sign-in are deleted automatically within\
  \ 24 months of the last access\n    request or connection.\n- scope: Confirmed email subscriptions\n  period: until unsubscribe, deletion request, or when no longer reasonably needed\n  text: Confirmed email subscriptions remain until unsubscribe, deletion request, or when no longer reasonably needed\n    to document and honor the communication choice.\n- scope: Booking and payment records\n  period: longer for tax, accounting, dispute, fraud-prevention, or legal obligations\n  text: Booking and payment records may be retained longer for tax, accounting, dispute, fraud-prevention, or legal\n    obligations.\n- scope: Agent API Workers Logs\n  period: up to 7 days\n  text: Cloudflare, which hosts the site, keeps those Workers Logs for up to 7 days.\n- scope: Stored agent quotes\n  period: 24 hours\n  text: A scheduled job deletes stored quotes 24 hours after they are created.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n\
  \  text: null\ndeletion:\n  route: Email info@goodreviewsonly.com\n  text: Request access or deletion, or opt out of marketing, by emailing info@goodreviewsonly.com .\nrights:\n- right: access, deletion, or marketing opt-out\n  text: Request access or deletion, or opt out of marketing, by emailing info@goodreviewsonly.com .\nsale_or_sharing:\n  stance: prohibited\n  text: We collect only what is needed and never sell guest data.\n"
source_yaml_url: https://artifacts.apis.io/cityoftrees-house/privacy/cityoftrees-house-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from City of Trees House's own page on 2026-11-09.
synthetic: false
tags:
- Vacation Rentals
- West Sacramento
- Family Run
- Hospitality
- Vacation Home
---
