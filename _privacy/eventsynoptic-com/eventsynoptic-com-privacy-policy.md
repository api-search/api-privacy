---
api_specs:
- filename: eventsynoptic-com-openapi-generated.yml
  format: yaml
  label: Event Synoptic API
  slug: eventsynoptic-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eventsynoptic-com/openapi/_ae-authored/eventsynoptic-com-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: we receive and store your account identifier, display name and profile photo URL from that provider
  - category: contact
    text: Google sign-in also gives us your email address.
  - category: contact
    text: If you message our bot on WhatsApp, we receive the phone number you message from
  - category: demographic
    text: first name, last name, date of birth, gender, phone number, email
  - category: behavioral
    text: we record which events you save, which categories and artists you follow, your searches and which listings you open or click
  - category: location
    text: we round your coordinates to roughly a one-mile grid before storing them
  - category: device
    text: your browser's user-agent string and whether it belongs to a known crawler
  deletion:
    route: Email the privacy address from your registered address or message the bot, or delete your account
    text: Email [email protected] from your registered address, or message the bot.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: show events and recommendations
    text: to show you events, prices and recommendations, and to run features you asked for
  - purpose: operate and secure the Service
    text: to operate and secure the Service — including detecting scraping, abuse and outages
  - purpose: aggregate improvement
    text: to understand which pages and categories are useful, in aggregate, so we can improve coverage
  - purpose: affiliate attribution
    text: to attribute clicks to our partners so we can be paid a commission
  - purpose: legal compliance
    text: to comply with legal obligations
  residency:
  - region: Germany
    text: Hetzner — hosts our servers and database, located in Germany.
  retention:
  - period: until you delete your account
    scope: Account profile and saved events
    text: Account profile and saved events — until you delete your account.
  - period: 30 days of inactivity
    scope: Bot sessions
    text: Bot sessions — 30 days of inactivity.
  - period: 60 days
    scope: Reminder and alert bookkeeping
    text: Reminder and alert bookkeeping — 60 days.
  - period: 40 days
    scope: Web page-view logs
    text: Web page-view logs (path, hashed IP, user-agent) — 40 days.
  - period: 180 days
    scope: Price history
    text: Price history — 180 days.
  rights:
  - right: access
    text: you can ask us to show you the personal data we hold about you
  - right: correction
    text: correct it, or delete it
  - right: objection
    text: You may object to processing, request portability, or complain to your local supervisory authority.
  - right: non-discrimination (CCPA)
    text: to not be discriminated against for exercising those rights
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your personal information, and we do not share it for cross-context behavioural advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Event Synoptic
provenance_date: '2026-11-09'
provider_name: Event Synoptic
provider_slug: eventsynoptic-com
slug: eventsynoptic-com-privacy-policy
source_date: '2026-11-09'
source_filename: eventsynoptic-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://eventsynoptic.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Event Synoptic\naid: eventsynoptic-com\nurl: https://eventsynoptic.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we receive and store your account identifier, display name and profile photo URL from that provider\n- category: contact\n  text: Google sign-in also gives us your email address.\n- category: contact\n  text: If you message our bot on WhatsApp, we receive the phone number you message from\n- category: demographic\n  text: first name, last name, date of birth, gender, phone number, email\n- category: behavioral\n\
  \  text: we record which events you save, which categories and artists you follow, your searches and which listings\n    you open or click\n- category: location\n  text: we round your coordinates to roughly a one-mile grid before storing them\n- category: device\n  text: your browser's user-agent string and whether it belongs to a known crawler\npurposes:\n- purpose: show events and recommendations\n  text: to show you events, prices and recommendations, and to run features you asked for\n- purpose: operate and secure the Service\n  text: to operate and secure the Service — including detecting scraping, abuse and outages\n- purpose: aggregate improvement\n  text: to understand which pages and categories are useful, in aggregate, so we can improve coverage\n- purpose: affiliate attribution\n  text: to attribute clicks to our partners so we can be paid a commission\n- purpose: legal compliance\n  text: to comply with legal obligations\nretention:\n- scope: Account profile and saved events\n\
  \  period: until you delete your account\n  text: Account profile and saved events — until you delete your account.\n- scope: Bot sessions\n  period: 30 days of inactivity\n  text: Bot sessions — 30 days of inactivity.\n- scope: Reminder and alert bookkeeping\n  period: 60 days\n  text: Reminder and alert bookkeeping — 60 days.\n- scope: Web page-view logs\n  period: 40 days\n  text: Web page-view logs (path, hashed IP, user-agent) — 40 days.\n- scope: Price history\n  period: 180 days\n  text: Price history — 180 days.\nresidency:\n- region: Germany\n  text: Hetzner — hosts our servers and database, located in Germany.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email the privacy address from your registered address or message the bot, or delete your account\n  text: Email [email protected] from your registered address, or message the bot.\nrights:\n- right: access\n  text: you can ask us to show you\
  \ the personal data we hold about you\n- right: correction\n  text: correct it, or delete it\n- right: objection\n  text: You may object to processing, request portability, or complain to your local supervisory authority.\n- right: non-discrimination (CCPA)\n  text: to not be discriminated against for exercising those rights\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your personal information, and we do not share it for cross-context behavioural advertising.\n"
source_yaml_url: https://artifacts.apis.io/eventsynoptic-com/privacy/eventsynoptic-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Event Synoptic's own page on 2026-11-09.
synthetic: false
tags:
- Event
- Calendar
- Los Angeles
- Entertainment
- Ticketing
---
