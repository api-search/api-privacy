---
api_specs:
- filename: meettempi-com-api-openapi.json
  format: json
  label: Tempi API API
  slug: tempi-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/meettempi-com/openapi/_original/meettempi-com-api-openapi.json
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: your name, email address, username and time zone.'
  - category: contact
    text: the invitee’s name, email, time zone and optional notes
  - category: financial
    text: for paid event types, the price and the Stripe identifiers for the payment.
  - category: communication
    text: the email, name and note you send if you join the waitlist.
  - category: behavioral
    text: we record product events on our own servers.
  deletion:
    route: Email hello@meettempi.com or delete your account
    text: To delete your account and everything linked to it, or to get a copy of your data, contact hello@meettempi.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Scheduling and bookings
    text: We collect only what we need to show your availability and book meetings.
  retention:
  - period: while your account exists
    scope: Account data
    text: We keep your data while your account exists.
  - period: until you delete your account
    scope: Cancelled bookings
    text: Cancelled bookings stay in your history until you delete your account.
  - period: at most a minute
    scope: Busy times from Google Calendar
    text: Busy times are read when needed and kept in memory for at most a minute.
  rights:
  - right: Access or copy of data
    text: or to get a copy of your data, contact hello@meettempi.com
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data, show ads, or use your data to train AI models.
  subprocessors:
    text: Cloudflare hosts the app, its database and the usage metrics.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: meettempi-com
provenance_date: '2026-11-10'
provider_name: meettempi-com
provider_slug: meettempi-com
slug: meettempi-com-privacy-policy
source_date: '2026-11-10'
source_filename: meettempi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://meettempi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: meettempi-com\naid: meettempi-com\nurl: https://meettempi.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account: your name, email address, username and time zone.'\n- category: contact\n  text: the invitee’s name, email, time zone and optional notes\n- category: financial\n  text: for paid event types, the price and the Stripe identifiers for the payment.\n- category: communication\n  text: the email, name and note you send if you join the waitlist.\n- category: behavioral\n  text: we record product events on our own servers.\n\
  purposes:\n- purpose: Scheduling and bookings\n  text: We collect only what we need to show your availability and book meetings.\nretention:\n- scope: Account data\n  period: while your account exists\n  text: We keep your data while your account exists.\n- scope: Cancelled bookings\n  period: until you delete your account\n  text: Cancelled bookings stay in your history until you delete your account.\n- scope: Busy times from Google Calendar\n  period: at most a minute\n  text: Busy times are read when needed and kept in memory for at most a minute.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare hosts the app, its database and the usage metrics.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@meettempi.com or delete your account\n  text: To delete your account and everything linked to it, or to get a copy of your data, contact hello@meettempi.com\n    .\nrights:\n- right: Access or copy of data\n  text: or to get a copy\
  \ of your data, contact hello@meettempi.com\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell data, show ads, or use your data to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/meettempi-com/privacy/meettempi-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from meettempi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Scheduling
- Artificial Intelligence
- Calendar
- Collaboration
---
