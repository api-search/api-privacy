---
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: your Google account ID, a number that identifies your account
  - category: contact
    text: your email address, and whether Google has verified it
  - category: device
    text: your IP address, and your MCP client's user agent
  deletion:
    route: email deletion@adamwanninger.com
    text: 'Ask for deletion: email deletion@adamwanninger.com , and I''ll delete the records linked to your account.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: sign-in and linking tokens to your account
    text: 'Google account ID: linked to the tokens the server gives your MCP client, so the server knows whom they belong to.'
  - purpose: answering tool requests
    text: What you ask a tool for, such as a vehicle number, a route, or a stop name, is used to answer you.
  residency:
  - region: United States
    text: The records below are kept in Google Cloud Firestore, in the United States (Google Cloud's us-east1 region, in South Carolina).
  retention:
  - period: 30 days
    scope: Refresh token
    text: 30 days. Each use replaces it with a new one
  - period: 30 days
    scope: Request logs
    text: Both are kept in Google Cloud Logging for 30 days and then deleted automatically.
  - period: null
    scope: Tool requests
    text: It isn't stored or logged.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Your information isn't sold, used for advertising, or shared with anyone.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: adamwanninger-com
provenance_date: '2026-11-09'
provider_name: adamwanninger-com
provider_slug: adamwanninger-com
slug: adamwanninger-com-privacy-policy
source_date: '2026-11-09'
source_filename: adamwanninger-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://adamwanninger.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: adamwanninger-com\naid: adamwanninger-com\nurl: https://adamwanninger.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your Google account ID, a number that identifies your account\n- category: contact\n  text: your email address, and whether Google has verified it\n- category: device\n  text: your IP address, and your MCP client's user agent\npurposes:\n- purpose: sign-in and linking tokens to your account\n  text: 'Google account ID: linked to the tokens the server gives your MCP client, so the server knows whom they\n   \
  \ belong to.'\n- purpose: answering tool requests\n  text: What you ask a tool for, such as a vehicle number, a route, or a stop name, is used to answer you.\nretention:\n- scope: Refresh token\n  period: 30 days\n  text: 30 days. Each use replaces it with a new one\n- scope: Request logs\n  period: 30 days\n  text: Both are kept in Google Cloud Logging for 30 days and then deleted automatically.\n- scope: Tool requests\n  period: null\n  text: It isn't stored or logged.\nresidency:\n- region: United States\n  text: The records below are kept in Google Cloud Firestore, in the United States (Google Cloud's us-east1 region,\n    in South Carolina).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email deletion@adamwanninger.com\n  text: 'Ask for deletion: email deletion@adamwanninger.com , and I''ll delete the records linked to your account.'\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: Your\
  \ information isn't sold, used for advertising, or shared with anyone.\n"
source_yaml_url: https://artifacts.apis.io/adamwanninger-com/privacy/adamwanninger-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- sale_or_sharing
summary_line: 11 quoted statements, read from adamwanninger-com's own page on 2026-11-09.
synthetic: false
tags:
- MCP
- Transit
- Open Data
- AI Tools
- City-Data
- Company
---
