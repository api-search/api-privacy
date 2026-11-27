---
api_specs:
- filename: clawpost-net-api-openapi.json
  format: json
  label: Claw Post API API
  slug: claw-post-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawpost-net/openapi/_original/clawpost-net-api-openapi.json
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: we receive your email address, display name, and a unique user ID from Firebase Authentication
  - category: contact
    text: we receive your email address, display name, and a unique user ID from Firebase Authentication
  - category: financial
    text: We store only your Stripe customer ID and subscription ID; we do not store your card number or bank details.
  - category: location
    text: These logs may include your IP address, user agent, request timestamps, and request paths.
  - category: behavioral
    text: We track the number of posts you make per billing period for quota and billing purposes.
  - category: communication
    text: For each reply found, we store the reply text, author username, permalink, and timestamp.
  - category: device
    text: we store a connection token, device name (optional, user-chosen), and periodic heartbeats to track whether the device is online.
  deletion:
    route: Email human@daydreamnation.io to request account deletion
    text: You may request a copy of your data or request that we delete your account and associated data by emailing human@daydreamnation.io .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the service
    text: We share data with the following third parties only as necessary to provide the service
  - purpose: debugging, security and abuse prevention
    text: We use these logs for debugging, security monitoring, and abuse prevention.
  - purpose: quota and billing
    text: We track the number of posts you make per billing period for quota and billing purposes.
  - purpose: product improvement
    text: We track only internal funnel events (such as account creation and first post) in our own database for product improvement.
  residency:
  - region: United States
    text: All data is stored on Google Cloud Platform infrastructure in the United States
  retention:
  - period: 7 days
    scope: Uploaded media files
    text: Automatically deleted 7 days after upload via a Google Cloud Storage lifecycle policy.
  - period: 90 days
    scope: Scraped replies
    text: Automatically deleted 90 days after collection.
  - period: null
    scope: Account data
    text: Retained until you request account deletion.
  - period: 30 days
    scope: OAuth refresh tokens
    text: Expire after 30 days of inactivity or upon revocation.
  - period: 30 days
    scope: Cloud Run server logs
    text: Cloud Run logs are retained according to Google Cloud's default log retention settings (30 days) unless we configure a different retention period.
  rights:
  - right: access (copy of data)
    text: You may request a copy of your data
  - right: deletion
    text: request that we delete your account and associated data by emailing human@daydreamnation.io
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data to anyone.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Claw Post
provenance_date: '2026-11-09'
provider_name: Claw Post
provider_slug: clawpost-net
slug: clawpost-net-privacy-policy
source_date: '2026-11-09'
source_filename: clawpost-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://clawpost.net/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Claw Post\naid: clawpost-net\nurl: https://clawpost.net/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we receive your email address, display name, and a unique user ID from Firebase Authentication\n- category: contact\n  text: we receive your email address, display name, and a unique user ID from Firebase Authentication\n- category: financial\n  text: We store only your Stripe customer ID and subscription ID; we do not store your card number or bank details.\n- category: location\n  text: These logs may include your IP address,\
  \ user agent, request timestamps, and request paths.\n- category: behavioral\n  text: We track the number of posts you make per billing period for quota and billing purposes.\n- category: communication\n  text: For each reply found, we store the reply text, author username, permalink, and timestamp.\n- category: device\n  text: we store a connection token, device name (optional, user-chosen), and periodic heartbeats to track whether\n    the device is online.\npurposes:\n- purpose: provide the service\n  text: We share data with the following third parties only as necessary to provide the service\n- purpose: debugging, security and abuse prevention\n  text: We use these logs for debugging, security monitoring, and abuse prevention.\n- purpose: quota and billing\n  text: We track the number of posts you make per billing period for quota and billing purposes.\n- purpose: product improvement\n  text: We track only internal funnel events (such as account creation and first post) in our own\
  \ database for product\n    improvement.\nretention:\n- scope: Uploaded media files\n  period: 7 days\n  text: Automatically deleted 7 days after upload via a Google Cloud Storage lifecycle policy.\n- scope: Scraped replies\n  period: 90 days\n  text: Automatically deleted 90 days after collection.\n- scope: Account data\n  period: null\n  text: Retained until you request account deletion.\n- scope: OAuth refresh tokens\n  period: 30 days\n  text: Expire after 30 days of inactivity or upon revocation.\n- scope: Cloud Run server logs\n  period: 30 days\n  text: Cloud Run logs are retained according to Google Cloud's default log retention settings (30 days) unless\n    we configure a different retention period.\nresidency:\n- region: United States\n  text: All data is stored on Google Cloud Platform infrastructure in the United States\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email human@daydreamnation.io\
  \ to request account deletion\n  text: You may request a copy of your data or request that we delete your account and associated data by emailing\n    human@daydreamnation.io .\nrights:\n- right: access (copy of data)\n  text: You may request a copy of your data\n- right: deletion\n  text: request that we delete your account and associated data by emailing human@daydreamnation.io\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data to anyone.\n"
source_yaml_url: https://artifacts.apis.io/clawpost-net/privacy/clawpost-net-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Claw Post's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Social Media
- Automation
- Posting
- Agents
---
