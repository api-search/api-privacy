---
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'API keys: we store only a cryptographic hash of your key, never the key itself.'
  - category: device
    text: 'IP addresses: used for rate limiting and trial-abuse limits; where stored, they are kept only as one-way SHA-256 hashes.'
  - category: financial
    text: 'Payments: handled entirely by Stripe. We do not receive or store card numbers.'
  - category: contact
    text: Stripe shares with us the payment status and the details you give at checkout (such as email)
  deletion:
    route: email support
    text: You can ask us to access or delete information associated with your key at support@parcelapi.net .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: billing and abuse prevention
    text: 'Usage logs: for each request we record the key''s client ID, endpoint, time, records returned and credits charged, for billing and abuse prevention.'
  - purpose: process purchases, refunds and support
    text: which we use only to process your purchase, refunds and support.
  retention:
  - period: null
    scope: usage and payment records
    text: Usage and payment records are kept as long as needed for billing, tax and legal purposes.
  rights:
  - right: access and deletion
    text: You can ask us to access or delete information associated with your key at support@parcelapi.net .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: we do not sell your information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: parcelapi-net
provenance_date: '2026-11-10'
provider_name: parcelapi-net
provider_slug: parcelapi-net
slug: parcelapi-net-privacy-policy
source_date: '2026-11-10'
source_filename: parcelapi-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://parcelapi.net/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: parcelapi-net\naid: parcelapi-net\nurl: https://parcelapi.net/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'API keys: we store only a cryptographic hash of your key, never the key itself.'\n- category: device\n  text: 'IP addresses: used for rate limiting and trial-abuse limits; where stored, they are kept only as one-way\n    SHA-256 hashes.'\n- category: financial\n  text: 'Payments: handled entirely by Stripe. We do not receive or store card numbers.'\n- category: contact\n  text: Stripe shares with us the payment status and\
  \ the details you give at checkout (such as email)\npurposes:\n- purpose: billing and abuse prevention\n  text: 'Usage logs: for each request we record the key''s client ID, endpoint, time, records returned and credits\n    charged, for billing and abuse prevention.'\n- purpose: process purchases, refunds and support\n  text: which we use only to process your purchase, refunds and support.\nretention:\n- scope: usage and payment records\n  period: null\n  text: Usage and payment records are kept as long as needed for billing, tax and legal purposes.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support\n  text: You can ask us to access or delete information associated with your key at support@parcelapi.net .\nrights:\n- right: access and deletion\n  text: You can ask us to access or delete information associated with your key at support@parcelapi.net .\nsale_or_sharing:\n  stance:\
  \ prohibited\n  text: we do not sell your information.\n"
source_yaml_url: https://artifacts.apis.io/parcelapi-net/privacy/parcelapi-net-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 10 quoted statements, read from parcelapi-net's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Data
- US
---
