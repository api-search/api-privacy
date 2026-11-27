---
api_specs:
- filename: transcript1-com-openapi.json
  format: json
  label: Transcript1 API
  slug: transcript1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcript1-com/openapi/transcript1-com-openapi.json
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account details: your email and name.'
  - category: identifying
    text: 'Sign-in identifiers: if you sign in with Google or Microsoft, the identifier that provider gives us for your account.'
  - category: communication
    text: 'Submitted media: links, uploaded files, live audio and browser-buffered audio submitted for transcription.'
  - category: behavioral
    text: 'Transcripts and translations: the text, timestamps, speaker labels and languages we produce for you.'
  - category: device
    text: 'Operational records: request IPs, paths and query parameters, timing, errors, session identifiers and usage counters used to run and troubleshoot the service.'
  - category: financial
    text: 'Usage and billing ledger: the minutes each transcription used, refunds, plan changes and top-ups.'
  deletion:
    route: Delete a transcript in the dashboard or API, or write to the privacy contact for a broader request
    text: You can also delete a transcript yourself with the dashboard or the API.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Translation
    text: 'Translation: when you enable translation, transcript text and nearby text for context are sent through our translation service to the providers described below.'
  - purpose: Payments
    text: Stripe Payments and subscriptions
  - purpose: Analytics
    text: Google Analytics Counts visits and page views on public pages
  retention:
  - period: 24 hours
    scope: Uploaded media and browser-buffered chunks
    text: scheduled for deletion 24 hours after the transcription reaches a final status (completed, failed or canceled).
  - period: 24 hours
    scope: Incomplete uploads
    text: Incomplete uploads abandoned for 24 hours are canceled and scheduled for cleanup.
  - period: null
    scope: Finalized live lines
    text: Finalized lines, including completed line translations, are temporarily stored in our database to support reconnection, even when saving is off.
  - period: two-minute reconnect window
    scope: Disconnected live sessions
    text: Disconnected sessions normally end after a two-minute reconnect window, checked by periodic cleanup.
  - period: null
    scope: Saved transcripts, translations and groups
    text: 'Saved transcripts, translations and groups: remain available until you delete them.'
  - period: null
    scope: Account, operational, usage and billing records
    text: We do not specify a fixed automatic deletion period for them here.
  - period: null
    scope: Local subtitle cache in browser
    text: There is no time-based expiry for these local records.
  rights:
  - right: Access, correction, export, deletion and objection
    text: Depending on where you live, you may ask to see, correct, export or delete your personal data, or to object to how it is used.
  role:
    text: transcript1.com, part of the one1.dev group ("we", "us"), decides how the personal data described here is used.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Who helps us process it Provider What it does Stripe Payments and subscriptions Soniox or Speechmatics Speech-to-text for file, link, buffered-audio and live transcription.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: transcript1-com
provenance_date: '2026-11-10'
provider_name: transcript1-com
provider_slug: transcript1-com
slug: transcript1-com-privacy-policy
source_date: '2026-11-10'
source_filename: transcript1-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://transcript1.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: transcript1-com\naid: transcript1-com\nurl: https://transcript1.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: transcript1.com, part of the one1.dev group (\"we\", \"us\"), decides how the personal data described here is\n    used.\ndata_categories:\n- category: identifying\n  text: 'Account details: your email and name.'\n- category: identifying\n  text: 'Sign-in identifiers: if you sign in with Google or Microsoft, the identifier that provider gives us for\n    your account.'\n- category: communication\n  text: 'Submitted media: links, uploaded files, live audio and browser-buffered\
  \ audio submitted for transcription.'\n- category: behavioral\n  text: 'Transcripts and translations: the text, timestamps, speaker labels and languages we produce for you.'\n- category: device\n  text: 'Operational records: request IPs, paths and query parameters, timing, errors, session identifiers and usage\n    counters used to run and troubleshoot the service.'\n- category: financial\n  text: 'Usage and billing ledger: the minutes each transcription used, refunds, plan changes and top-ups.'\npurposes:\n- purpose: Translation\n  text: 'Translation: when you enable translation, transcript text and nearby text for context are sent through\n    our translation service to the providers described below.'\n- purpose: Payments\n  text: Stripe Payments and subscriptions\n- purpose: Analytics\n  text: Google Analytics Counts visits and page views on public pages\nretention:\n- scope: Uploaded media and browser-buffered chunks\n  period: 24 hours\n  text: scheduled for deletion 24 hours after\
  \ the transcription reaches a final status (completed, failed or canceled).\n- scope: Incomplete uploads\n  period: 24 hours\n  text: Incomplete uploads abandoned for 24 hours are canceled and scheduled for cleanup.\n- scope: Finalized live lines\n  period: null\n  text: Finalized lines, including completed line translations, are temporarily stored in our database to support\n    reconnection, even when saving is off.\n- scope: Disconnected live sessions\n  period: two-minute reconnect window\n  text: Disconnected sessions normally end after a two-minute reconnect window, checked by periodic cleanup.\n- scope: Saved transcripts, translations and groups\n  period: null\n  text: 'Saved transcripts, translations and groups: remain available until you delete them.'\n- scope: Account, operational, usage and billing records\n  period: null\n  text: We do not specify a fixed automatic deletion period for them here.\n- scope: Local subtitle cache in browser\n  period: null\n  text: There is no\
  \ time-based expiry for these local records.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Who helps us process it Provider What it does Stripe Payments and subscriptions Soniox or Speechmatics Speech-to-text\n    for file, link, buffered-audio and live transcription.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete a transcript in the dashboard or API, or write to the privacy contact for a broader request\n  text: You can also delete a transcript yourself with the dashboard or the API.\nrights:\n- right: Access, correction, export, deletion and objection\n  text: Depending on where you live, you may ask to see, correct, export or delete your personal data, or to object\n    to how it is used.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/transcript1-com/privacy/transcript1-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 20 quoted statements, read from transcript1-com's own page on 2026-11-10.
synthetic: false
tags:
- Audio
- Video
- Transcription
- MCP
---
