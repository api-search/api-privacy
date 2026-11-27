---
api_specs:
- filename: bitsound-com-releases-api-openapi.yml
  format: yaml
  label: Bitsound Releases API
  slug: bitsound-com-releases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitsound-com/openapi/bitsound-com-releases-api-openapi.yml
claim_count: 33
description: ''
doc:
  data_categories:
  - category: identifying
    text: For an account we need your email address. Optional are a display name, your country and your settings.
  - category: financial
    text: For a top-up and for purchases we process the amount, time, purchased tracks and releases, VAT, your country and the receipts.
  - category: location
    text: We determine the location (city and country) only at the moment of the email from the IP address, with a database on our own server.
  - category: behavioral
    text: When you are signed in, we store which track you listened to, when, for how long and from where (for example release page or radio)
  - category: identifying
    text: 'ID : We store the photo of your ID encrypted (AES-256), only an admin can view it for the review.'
  deletion:
    route: 'Account settings: delete account in settings'
    text: You can delete your account yourself in the settings.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account and sign-in
    text: 'Bitsound has no passwords: you sign in with a code we send you by email, or with a passkey.'
  - purpose: Audience measurement
    text: we count page views and plays ourselves, without any third-party service, without cookies and without entries in your browser's local storage.
  - purpose: Payments and accounting
    text: We generally keep receipts, invoices, credit notes and bookings for seven years from the end of the calendar year (§ 132 BAO).
  - purpose: Artist verification and payout
    text: Anyone who sells music must verify themselves.
  - purpose: Checking uploaded music
    text: 'The purpose is checking rights. Legal basis: our legitimate interest in preventing infringements (Art. 6(1)(f) GDPR).'
  residency:
  - region: Germany
    text: The servers used for operation and the music and image storage are located in Germany.
  retention:
  - period: 90 days
    scope: Listening events
    text: We automatically delete listening events after 90 days.
  - period: 30 days
    scope: Audience measurement events
    text: We delete the individual events after 30 days.
  - period: null
    scope: Sign-in codes
    text: Sign-in codes are only valid for a short time and are deleted one day after they expire.
  - period: at most 30 days
    scope: Sessions
    text: 'Sessions : While you are signed in, we store a session with the user agent, for at most 30 days.'
  - period: 30 days
    scope: Application error and job logs
    text: These logs are deleted after 30 days at the latest
  - period: null
    scope: ID image
    text: We delete it as soon as a decision on your verification has been made. If it has not been reviewed by then, we delete it after 30 days at the latest
  - period: 14 days
    scope: Local database backups
    text: Local database backups are kept for at most 14 days.
  - period: seven years
    scope: Receipts and invoices
    text: We generally keep receipts, invoices, credit notes and bookings for seven years from the end of the calendar year (§ 132 BAO).
  rights:
  - right: access
    text: You have the right of access (Art. 15 GDPR)
  - right: rectification
    text: rectification (Art. 16)
  - right: erasure
    text: erasure (Art. 17)
  - right: restriction of processing
    text: restriction of processing (Art. 18)
  - right: data portability
    text: data portability (Art. 20)
  - right: object
    text: and to object (Art. 21)
  - right: withdraw consent
    text: You can withdraw consent at any time (Art. 7(3)).
  - right: complaint
    text: You can lodge a complaint with the data protection authority
  role:
    text: Controller Dr. Peter Mayer Sole proprietor, trading as Bitsound
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Bitsound uses Hetzner Online GmbH, Industriestr. 25, 91710 Gunzenhausen, Germany, as hosting processor.
    url: null
  transfers:
  - mechanism: SCC
    text: The transfer is based on the European Commission's standard contractual clauses (Art. 46(2)(c) GDPR).
  - mechanism: DPF
    text: including the EU-US Data Privacy Framework for certified recipients, or standard contractual clauses are used.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bitsound
provenance_date: '2026-11-09'
provider_name: Bitsound
provider_slug: bitsound-com
slug: bitsound-com-privacy-policy
source_date: '2026-11-09'
source_filename: bitsound-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bitsound.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bitsound\naid: bitsound-com\nurl: https://bitsound.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Controller Dr. Peter Mayer Sole proprietor, trading as Bitsound\ndata_categories:\n- category: identifying\n  text: For an account we need your email address. Optional are a display name, your country and your settings.\n- category: financial\n  text: For a top-up and for purchases we process the amount, time, purchased tracks and releases, VAT, your country\n    and the receipts.\n- category: location\n  text: We determine the location (city and country) only at the moment of the\
  \ email from the IP address, with a\n    database on our own server.\n- category: behavioral\n  text: When you are signed in, we store which track you listened to, when, for how long and from where (for example\n    release page or radio)\n- category: identifying\n  text: 'ID : We store the photo of your ID encrypted (AES-256), only an admin can view it for the review.'\npurposes:\n- purpose: Account and sign-in\n  text: 'Bitsound has no passwords: you sign in with a code we send you by email, or with a passkey.'\n- purpose: Audience measurement\n  text: we count page views and plays ourselves, without any third-party service, without cookies and without entries\n    in your browser's local storage.\n- purpose: Payments and accounting\n  text: We generally keep receipts, invoices, credit notes and bookings for seven years from the end of the calendar\n    year (§ 132 BAO).\n- purpose: Artist verification and payout\n  text: Anyone who sells music must verify themselves.\n- purpose: Checking\
  \ uploaded music\n  text: 'The purpose is checking rights. Legal basis: our legitimate interest in preventing infringements (Art.\n    6(1)(f) GDPR).'\nretention:\n- scope: Listening events\n  period: 90 days\n  text: We automatically delete listening events after 90 days.\n- scope: Audience measurement events\n  period: 30 days\n  text: We delete the individual events after 30 days.\n- scope: Sign-in codes\n  period: null\n  text: Sign-in codes are only valid for a short time and are deleted one day after they expire.\n- scope: Sessions\n  period: at most 30 days\n  text: 'Sessions : While you are signed in, we store a session with the user agent, for at most 30 days.'\n- scope: Application error and job logs\n  period: 30 days\n  text: These logs are deleted after 30 days at the latest\n- scope: ID image\n  period: null\n  text: We delete it as soon as a decision on your verification has been made. If it has not been reviewed by then,\n    we delete it after 30 days at the latest\n-\
  \ scope: Local database backups\n  period: 14 days\n  text: Local database backups are kept for at most 14 days.\n- scope: Receipts and invoices\n  period: seven years\n  text: We generally keep receipts, invoices, credit notes and bookings for seven years from the end of the calendar\n    year (§ 132 BAO).\nresidency:\n- region: Germany\n  text: The servers used for operation and the music and image storage are located in Germany.\ntransfers:\n- mechanism: SCC\n  text: The transfer is based on the European Commission's standard contractual clauses (Art. 46(2)(c) GDPR).\n- mechanism: DPF\n  text: including the EU-US Data Privacy Framework for certified recipients, or standard contractual clauses are\n    used.\nsubprocessors:\n  url: null\n  text: Bitsound uses Hetzner Online GmbH, Industriestr. 25, 91710 Gunzenhausen, Germany, as hosting processor.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: 'Account settings: delete account in settings'\n  text: You can delete\
  \ your account yourself in the settings.\nrights:\n- right: access\n  text: You have the right of access (Art. 15 GDPR)\n- right: rectification\n  text: rectification (Art. 16)\n- right: erasure\n  text: erasure (Art. 17)\n- right: restriction of processing\n  text: restriction of processing (Art. 18)\n- right: data portability\n  text: data portability (Art. 20)\n- right: object\n  text: and to object (Art. 21)\n- right: withdraw consent\n  text: You can withdraw consent at any time (Art. 7(3)).\n- right: complaint\n  text: You can lodge a complaint with the data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/bitsound-com/privacy/bitsound-com-privacy-policy.yml
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
summary_line: 33 quoted statements, read from Bitsound's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
