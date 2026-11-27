---
api_specs:
- filename: snaplab-dev-account-api-openapi.yml
  format: yaml
  label: snaplab-dev Account API
  slug: snaplab-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snaplab-dev/openapi/snaplab-dev-account-api-openapi.yml
- filename: snaplab-dev-billing-api-openapi.yml
  format: yaml
  label: snaplab-dev Billing API
  slug: snaplab-dev-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snaplab-dev/openapi/snaplab-dev-billing-api-openapi.yml
- filename: snaplab-dev-captures-api-openapi.yml
  format: yaml
  label: snaplab-dev Captures API
  slug: snaplab-dev-captures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snaplab-dev/openapi/snaplab-dev-captures-api-openapi.yml
- filename: snaplab-dev-free-tools-api-openapi.yml
  format: yaml
  label: snaplab-dev Free tools API
  slug: snaplab-dev-free-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snaplab-dev/openapi/snaplab-dev-free-tools-api-openapi.yml
- filename: snaplab-dev-rendering-api-openapi.yml
  format: yaml
  label: snaplab-dev Rendering API
  slug: snaplab-dev-rendering-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snaplab-dev/openapi/snaplab-dev-rendering-api-openapi.yml
- filename: snaplab-dev-system-api-openapi.yml
  format: yaml
  label: snaplab-dev System API
  slug: snaplab-dev-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snaplab-dev/openapi/snaplab-dev-system-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address Account identity, password reset, billing receipts, occasional service notices
  - category: identifying
    text: Password hash Logging in. The password itself is never stored or logged
  - category: device
    text: API key hash and prefix Authenticating requests and showing you which key is which
  - category: location
    text: 'Free tool usage: IP address and a daily counter'
  - category: behavioral
    text: 'Render log: hostname rendered, duration, byte size, cache flag, status, error code, timestamp'
  - category: financial
    text: Stripe customer and subscription ids Linking your account to your subscription
  deletion:
    route: Delete account from dashboard, or email snaplab.dev for deletion outside the app
    text: delete your account outright — which removes your user record, keys, sessions, captures and usage rows.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account identity and login
    text: we keep an email address so you can log in
  - purpose: Request authentication
    text: a hashed key so requests can be authenticated
  - purpose: Quota enforcement
    text: Enforcing your plan quota and showing usage on the dashboard
  - purpose: Debugging and abuse detection
    text: Debugging failures, spotting abuse, usage reporting
  - purpose: Rate-limiting free tools
    text: Rate-limiting the free tools at twenty renders a day
  retention:
  - period: Until you delete your account
    scope: Email address and account data
    text: Until you delete your account
  - period: 30 days
    scope: Render log
    text: 30 days , then deleted
  - period: 24 hours
    scope: Render cache
    text: It exists so identical requests inside 24 hours are instant and free.
  - period: Until you delete them
    scope: Captures and hosted files
    text: Captures stay until you delete them
  - period: The current day
    scope: Free-tool usage counter
    text: The current day
  rights:
  - right: Access
    text: To request a copy of your data, or deletion outside the app, email snaplab.dev
  - right: Correction
    text: correct your email address there
  - right: Deletion
    text: delete your account outright
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Your data is not sold, rented, or handed to data brokers or advertisers, under any circumstances.
  subprocessors:
    text: Stripe — payments and subscription management. Receives your email address and payment details. Our hosting provider — runs the server the service lives on. Google Fonts — serves the two webfonts these public pages use.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: snaplab-dev
provenance_date: '2026-11-10'
provider_name: snaplab-dev
provider_slug: snaplab-dev
slug: snaplab-dev-privacy-policy
source_date: '2026-11-10'
source_filename: snaplab-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://snaplab.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: snaplab-dev\naid: snaplab-dev\nurl: https://snaplab.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address Account identity, password reset, billing receipts, occasional service notices\n- category: identifying\n  text: Password hash Logging in. The password itself is never stored or logged\n- category: device\n  text: API key hash and prefix Authenticating requests and showing you which key is which\n- category: location\n  text: 'Free tool usage: IP address and a daily counter'\n- category: behavioral\n  text: 'Render\
  \ log: hostname rendered, duration, byte size, cache flag, status, error code, timestamp'\n- category: financial\n  text: Stripe customer and subscription ids Linking your account to your subscription\npurposes:\n- purpose: Account identity and login\n  text: we keep an email address so you can log in\n- purpose: Request authentication\n  text: a hashed key so requests can be authenticated\n- purpose: Quota enforcement\n  text: Enforcing your plan quota and showing usage on the dashboard\n- purpose: Debugging and abuse detection\n  text: Debugging failures, spotting abuse, usage reporting\n- purpose: Rate-limiting free tools\n  text: Rate-limiting the free tools at twenty renders a day\nretention:\n- scope: Email address and account data\n  period: Until you delete your account\n  text: Until you delete your account\n- scope: Render log\n  period: 30 days\n  text: 30 days , then deleted\n- scope: Render cache\n  period: 24 hours\n  text: It exists so identical requests inside 24 hours\
  \ are instant and free.\n- scope: Captures and hosted files\n  period: Until you delete them\n  text: Captures stay until you delete them\n- scope: Free-tool usage counter\n  period: The current day\n  text: The current day\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Stripe — payments and subscription management. Receives your email address and payment details. Our hosting\n    provider — runs the server the service lives on. Google Fonts — serves the two webfonts these public pages use.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account from dashboard, or email snaplab.dev for deletion outside the app\n  text: delete your account outright — which removes your user record, keys, sessions, captures and usage rows.\nrights:\n- right: Access\n  text: To request a copy of your data, or deletion outside the app, email snaplab.dev\n- right: Correction\n  text: correct your email address there\n- right: Deletion\n  text: delete your\
  \ account outright\nsale_or_sharing:\n  stance: prohibited\n  text: Your data is not sold, rented, or handed to data brokers or advertisers, under any circumstances.\n"
source_yaml_url: https://artifacts.apis.io/snaplab-dev/privacy/snaplab-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from snaplab-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Screenshots
- PDF
- OpenGraph
---
