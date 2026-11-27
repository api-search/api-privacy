---
api_specs:
- filename: ccpedia-xyz-openapi.yml
  format: yaml
  label: CCPEDIA REST API
  slug: ccpedia-rest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ccpedia-xyz/openapi/ccpedia-xyz-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: your IP address and the time of each request to a form, the chart pane on /vitals or the API
  - category: device
    text: your browser's user-agent string
  - category: behavioral
    text: the page, the referrer, your browser's user-agent string, a session identifier from the ccpedia_sid cookie
  - category: contact
    text: the contact and partnership forms take your name, email and message
  - category: communication
    text: the terms you type into search are logged on their own, with the time, the number of results and nothing that identifies you
  deletion:
    route: contact form
    text: Use the contact form . We'll reply within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: rate limiting
    text: We use it to stop one visitor from overloading the site.
  - purpose: unique visitor counting
    text: so we can count unique visitors per day but cannot recognise you across days
  - purpose: abuse prevention
    text: plus your IP address so we can act on abuse
  - purpose: answering enquiries
    text: We keep the message for as long as we need it to answer you.
  - purpose: search matching
    text: so results can be matched by meaning
  retention:
  - period: 7 days
    scope: rate-limit records
    text: Stored in our SQLite database for up to 7 days, then automatically purged.
  - period: 180 days
    scope: visit and API usage logs
    text: All of these logs are deleted after 180 days, and only running totals are kept.
  - period: one year
    scope: ccpedia_sid cookie
    text: a random identifier that lasts one year
  rights:
  - right: access or deletion
    text: You can ask us to show or delete whatever we hold on you
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell it, share it with advertisers, or hand it to anyone beyond the services named in sections 2 and 3.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CCPEDIA
provenance_date: '2026-11-09'
provider_name: CCPEDIA
provider_slug: ccpedia-xyz
slug: ccpedia-xyz-privacy-policy
source_date: '2026-11-09'
source_filename: ccpedia-xyz-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ccpedia.xyz/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CCPEDIA\naid: ccpedia-xyz\nurl: https://ccpedia.xyz/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your IP address and the time of each request to a form, the chart pane on /vitals or the API\n- category: device\n  text: your browser's user-agent string\n- category: behavioral\n  text: the page, the referrer, your browser's user-agent string, a session identifier from the ccpedia_sid cookie\n- category: contact\n  text: the contact and partnership forms take your name, email and message\n- category: communication\n  text: the terms\
  \ you type into search are logged on their own, with the time, the number of results and nothing\n    that identifies you\npurposes:\n- purpose: rate limiting\n  text: We use it to stop one visitor from overloading the site.\n- purpose: unique visitor counting\n  text: so we can count unique visitors per day but cannot recognise you across days\n- purpose: abuse prevention\n  text: plus your IP address so we can act on abuse\n- purpose: answering enquiries\n  text: We keep the message for as long as we need it to answer you.\n- purpose: search matching\n  text: so results can be matched by meaning\nretention:\n- scope: rate-limit records\n  period: 7 days\n  text: Stored in our SQLite database for up to 7 days, then automatically purged.\n- scope: visit and API usage logs\n  period: 180 days\n  text: All of these logs are deleted after 180 days, and only running totals are kept.\n- scope: ccpedia_sid cookie\n  period: one year\n  text: a random identifier that lasts one year\nresidency:\
  \ []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact form\n  text: Use the contact form . We'll reply within 30 days.\nrights:\n- right: access or deletion\n  text: You can ask us to show or delete whatever we hold on you\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell it, share it with advertisers, or hand it to anyone beyond the services named in sections\n    2 and 3.\n"
source_yaml_url: https://artifacts.apis.io/ccpedia-xyz/privacy/ccpedia-xyz-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from CCPEDIA's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Blockchain
- Knowledge Hub
- Canton Network
- Open Data
---
