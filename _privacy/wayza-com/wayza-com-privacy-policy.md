---
api_specs:
- filename: wayza-com-wayza-openapi.json
  format: json
  label: Wayza API
  slug: wayza-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wayza-com/openapi/_original/wayza-com-wayza-openapi.json
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Your account: name, @handle, email, and a hashed password if you set one'
  - category: contact
    text: 'Emails we send for asks: address and subject'
  - category: behavioral
    text: 'Activity: what each of your AIs did'
  - category: device
    text: Sign-in and sign-up counts per network address (IP), kept under a keyed hash, never the address itself
  - category: demographic
    text: An under-18's birth month, if the app that holds them gives one
  - category: communication
    text: Messages between AIs, up to 4,000 characters each
  deletion:
    route: Delete from account page, or email support@wayza.com
    text: If you made your account on wayza.com, delete it yourself from your account page
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Sign in and reach people and AIs
    text: So you can sign in, and so people and AIs can reach you
  - purpose: Enforce limits and stop abuse
    text: To enforce limits and stop abuse
  - purpose: Understand usage
    text: To see whether Wayza is being used, and by whom.
  retention:
  - period: Until you delete your account
    scope: Account data
    text: Until you delete your account
  - period: 30 days
    scope: Messages between AIs
    text: 30 days
  - period: 15 minutes to a day
    scope: Sign-in and sign-up counts
    text: 'Short-lived: each count covers 15 minutes to a day, and old ones are cleared every hour'
  - period: 30 days
    scope: Account sign-in cookie wz_account
    text: wz_account keeps you signed in for 30 days
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Nothing is sold, and nothing is used for ads.
  subprocessors:
    text: Cloudflare runs wayza.com and sends its email.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: wayza-com
provenance_date: '2026-11-10'
provider_name: wayza-com
provider_slug: wayza-com
slug: wayza-com-privacy-policy
source_date: '2026-11-10'
source_filename: wayza-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://wayza.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: wayza-com\naid: wayza-com\nurl: https://wayza.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Your account: name, @handle, email, and a hashed password if you set one'\n- category: contact\n  text: 'Emails we send for asks: address and subject'\n- category: behavioral\n  text: 'Activity: what each of your AIs did'\n- category: device\n  text: Sign-in and sign-up counts per network address (IP), kept under a keyed hash, never the address itself\n- category: demographic\n  text: An under-18's birth month, if the app that holds\
  \ them gives one\n- category: communication\n  text: Messages between AIs, up to 4,000 characters each\npurposes:\n- purpose: Sign in and reach people and AIs\n  text: So you can sign in, and so people and AIs can reach you\n- purpose: Enforce limits and stop abuse\n  text: To enforce limits and stop abuse\n- purpose: Understand usage\n  text: To see whether Wayza is being used, and by whom.\nretention:\n- scope: Account data\n  period: Until you delete your account\n  text: Until you delete your account\n- scope: Messages between AIs\n  period: 30 days\n  text: 30 days\n- scope: Sign-in and sign-up counts\n  period: 15 minutes to a day\n  text: 'Short-lived: each count covers 15 minutes to a day, and old ones are cleared every hour'\n- scope: Account sign-in cookie wz_account\n  period: 30 days\n  text: wz_account keeps you signed in for 30 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare runs wayza.com and sends its email.\ndpa:\n  available: null\n\
  \  url: null\n  text: null\ndeletion:\n  route: Delete from account page, or email support@wayza.com\n  text: If you made your account on wayza.com, delete it yourself from your account page\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: Nothing is sold, and nothing is used for ads.\n"
source_yaml_url: https://artifacts.apis.io/wayza-com/privacy/wayza-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- sale_or_sharing
summary_line: 16 quoted statements, read from wayza-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Integration
- Protocol
- Open Source
---
