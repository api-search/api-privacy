---
api_specs:
- filename: transcriptout-com-openapi-generated.yml
  format: yaml
  label: transcriptout-com API
  slug: transcriptout-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptout-com/openapi/_ae-authored/transcriptout-com-openapi-generated.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Signing in with Google gives us your name, email address, profile picture URL and a user id.
  - category: contact
    text: Signing in with a one-time link emailed to you gives us the address and a user id, and nothing else.
  - category: other
    text: We store only its SHA-256 hash, together with a label you choose and its creation date.
  - category: behavioral
    text: 'Every API call is logged: timestamp, endpoint, HTTP method, status code, credits charged, how long it took, a request id, and the resource you asked about, whether a video, channel or playlist id or a search query.'
  - category: financial
    text: a ledger of every grant, charge and refund.
  - category: location
    text: an approximate location derived from the IP address, device and browser
  - category: device
    text: with an approximate location, device and browser derived from the request itself
  deletion:
    route: Settings → Delete account
    text: Settings → Delete account removes your account, its API keys, its credit ledger, its request log and its usage counters.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account identification and contact
    text: Either way we use it to identify your account, address you in the interface and contact you about the service.
  - purpose: usage logs and charge explanation
    text: This is what the Logs page shows you, and it is what lets us answer
  - purpose: site analytics
    text: Google Analytics tells us which pages people read and where they arrive from
  - purpose: service availability and abuse investigation
    text: to keep the service available and to investigate abuse
  residency:
  - region: outside your country
    text: Google processes it under its own terms and may store it outside your country.
  - region: United States
    text: They process this under their own terms and operate from the United States.
  retention:
  - period: while your account exists
    scope: account data, key hashes and credit ledger
    text: Account data, key hashes and the credit ledger are kept while your account exists.
  - period: 30 days
    scope: request logs
    text: Request logs (the per-call rows the Logs page shows, including the video ids and search queries in them) are deleted after 30 days.
  - period: '90'
    scope: daily usage counters
    text: The daily usage counters built from them survive 90.
  - period: ninety days
    scope: referrer note in browser
    text: it expires after ninety days
  rights:
  - right: access
    text: See it. Your profile, balance, keys and full request history are visible in the dashboard at any time.
  - right: rectification
    text: Correct it. If you signed in with Google, your name and picture come from there, and changing them there changes them here.
  - right: erasure
    text: Delete it. Settings → Delete account removes your account, its API keys, its credit ledger, its request log and its usage counters.
  - right: portability
    text: Export it. Ask at the same address and we will send you what we hold in a machine-readable form.
  - right: objection, restriction and complaint
    text: Depending on where you live you may also have the right to object to processing, to restrict it, or to complain to a data protection authority.
  role:
    text: Where data protection law gives you a right against a controller, that is who you exercise it against.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, and we do not share it with anyone for their own marketing.
  subprocessors:
    text: 'We keep the list of processors short, and it is:'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: transcriptout-com
provenance_date: '2026-11-10'
provider_name: transcriptout-com
provider_slug: transcriptout-com
slug: transcriptout-com-privacy-policy
source_date: '2026-11-10'
source_filename: transcriptout-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://transcriptout.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: transcriptout-com\naid: transcriptout-com\nurl: https://transcriptout.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Where data protection law gives you a right against a controller, that is who you exercise it against.\ndata_categories:\n- category: identifying\n  text: Signing in with Google gives us your name, email address, profile picture URL and a user id.\n- category: contact\n  text: Signing in with a one-time link emailed to you gives us the address and a user id, and nothing else.\n- category: other\n  text: We store only its SHA-256 hash, together with a label you choose\
  \ and its creation date.\n- category: behavioral\n  text: 'Every API call is logged: timestamp, endpoint, HTTP method, status code, credits charged, how long it took,\n    a request id, and the resource you asked about, whether a video, channel or playlist id or a search query.'\n- category: financial\n  text: a ledger of every grant, charge and refund.\n- category: location\n  text: an approximate location derived from the IP address, device and browser\n- category: device\n  text: with an approximate location, device and browser derived from the request itself\npurposes:\n- purpose: account identification and contact\n  text: Either way we use it to identify your account, address you in the interface and contact you about the service.\n- purpose: usage logs and charge explanation\n  text: This is what the Logs page shows you, and it is what lets us answer\n- purpose: site analytics\n  text: Google Analytics tells us which pages people read and where they arrive from\n- purpose: service\
  \ availability and abuse investigation\n  text: to keep the service available and to investigate abuse\nretention:\n- scope: account data, key hashes and credit ledger\n  period: while your account exists\n  text: Account data, key hashes and the credit ledger are kept while your account exists.\n- scope: request logs\n  period: 30 days\n  text: Request logs (the per-call rows the Logs page shows, including the video ids and search queries in them)\n    are deleted after 30 days.\n- scope: daily usage counters\n  period: '90'\n  text: The daily usage counters built from them survive 90.\n- scope: referrer note in browser\n  period: ninety days\n  text: it expires after ninety days\nresidency:\n- region: outside your country\n  text: Google processes it under its own terms and may store it outside your country.\n- region: United States\n  text: They process this under their own terms and operate from the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We keep the list\
  \ of processors short, and it is:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings → Delete account\n  text: Settings → Delete account removes your account, its API keys, its credit ledger, its request log and its\n    usage counters.\nrights:\n- right: access\n  text: See it. Your profile, balance, keys and full request history are visible in the dashboard at any time.\n- right: rectification\n  text: Correct it. If you signed in with Google, your name and picture come from there, and changing them there\n    changes them here.\n- right: erasure\n  text: Delete it. Settings → Delete account removes your account, its API keys, its credit ledger, its request\n    log and its usage counters.\n- right: portability\n  text: Export it. Ask at the same address and we will send you what we hold in a machine-readable form.\n- right: objection, restriction and complaint\n  text: Depending on where you live you may also have the right to object to processing, to\
  \ restrict it, or to complain\n    to a data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, and we do not share it with anyone for their own marketing.\n"
source_yaml_url: https://artifacts.apis.io/transcriptout-com/privacy/transcriptout-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from transcriptout-com's own page on 2026-11-10.
synthetic: false
tags:
- YouTube
- Transcripts
- Bulk
- MCP
---
