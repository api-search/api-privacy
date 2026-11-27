---
api_specs:
- filename: toneperfect-assessment-api-openapi.yml
  format: yaml
  label: TonePerfect (Pronunciation Assessment API) Assessment API
  slug: toneperfect-assessment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toneperfect/openapi/toneperfect-assessment-api-openapi.yml
- filename: toneperfect-capabilities-api-openapi.yml
  format: yaml
  label: TonePerfect (Pronunciation Assessment API) Capabilities API
  slug: toneperfect-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toneperfect/openapi/toneperfect-capabilities-api-openapi.yml
- filename: toneperfect-utilities-api-openapi.yml
  format: yaml
  label: TonePerfect (Pronunciation Assessment API) Utilities API
  slug: toneperfect-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toneperfect/openapi/toneperfect-utilities-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address and name; a password hash or, with Google sign-in, the identifier Firebase Authentication returns.
  - category: financial
    text: Stripe holds card details.
  - category: behavioral
    text: page path, referring site, campaign tags, browser user agent and a random visitor identifier kept in your browser's local storage
  - category: communication
    text: 'Usage records kept for billing and support: time, locale, audio duration, credits, status, latency and error code of each request.'
  deletion:
    route: dashboard request after reauthentication
    text: Use Account data in the dashboard to export your data or request account deletion after reauthentication.
  dpa:
    available: true
    text: Business customers who need a data processing agreement should contact us before sending personal data.
    url: null
  purposes:
  - purpose: Scoring audio
    text: Recordings are decoded and scored in memory on our server
  - purpose: Idempotent retries
    text: so that a retry returns the same answer instead of charging twice
  - purpose: Billing and support
    text: Usage records kept for billing and support
  - purpose: Acquisition analytics
    text: to understand acquisition
  residency:
  - region: Germany
    text: Nuremberg, Germany
  - region: USA / Ireland
    text: USA / Ireland
  - region: USA / EU
    text: USA / EU
  retention:
  - period: null
    scope: Audio and reference text
    text: discarded when the response is sent
  - period: 24 hours
    scope: Results
    text: Results (scores, the words of your reference text, timings) are kept for 24 hours under your Idempotency-Key
  - period: 90 days
    scope: Refused requests
    text: Refused requests (for example 402 or 429) are kept for 90 days
  - period: while you have an account
    scope: Account and billing records
    text: account and billing records are kept while you have an account.
  - period: 14 days
    scope: Sign-in sessions
    text: Sign-in sessions last 14 days.
  rights:
  - right: export
    text: Use Account data in the dashboard to export your data or request account deletion after reauthentication.
  - right: deletion
    text: request account deletion after reauthentication
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Who processes data for us
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TonePerfect (Pronunciation Assessment API)
provenance_date: '2026-11-10'
provider_name: TonePerfect (Pronunciation Assessment API)
provider_slug: toneperfect
slug: toneperfect-privacy-policy
source_date: '2026-11-10'
source_filename: toneperfect-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://api.toneperfect.app/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TonePerfect (Pronunciation Assessment API)\naid: toneperfect\nurl: https://api.toneperfect.app/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address and name; a password hash or, with Google sign-in, the identifier Firebase Authentication\n    returns.\n- category: financial\n  text: Stripe holds card details.\n- category: behavioral\n  text: page path, referring site, campaign tags, browser user agent and a random visitor identifier kept in your\n    browser's local storage\n- category: communication\n  text: 'Usage records\
  \ kept for billing and support: time, locale, audio duration, credits, status, latency and\n    error code of each request.'\npurposes:\n- purpose: Scoring audio\n  text: Recordings are decoded and scored in memory on our server\n- purpose: Idempotent retries\n  text: so that a retry returns the same answer instead of charging twice\n- purpose: Billing and support\n  text: Usage records kept for billing and support\n- purpose: Acquisition analytics\n  text: to understand acquisition\nretention:\n- scope: Audio and reference text\n  period: null\n  text: discarded when the response is sent\n- scope: Results\n  period: 24 hours\n  text: Results (scores, the words of your reference text, timings) are kept for 24 hours under your Idempotency-Key\n- scope: Refused requests\n  period: 90 days\n  text: Refused requests (for example 402 or 429) are kept for 90 days\n- scope: Account and billing records\n  period: while you have an account\n  text: account and billing records are kept while you\
  \ have an account.\n- scope: Sign-in sessions\n  period: 14 days\n  text: Sign-in sessions last 14 days.\nresidency:\n- region: Germany\n  text: Nuremberg, Germany\n- region: USA / Ireland\n  text: USA / Ireland\n- region: USA / EU\n  text: USA / EU\ntransfers: []\nsubprocessors:\n  url: null\n  text: Who processes data for us\ndpa:\n  available: true\n  url: null\n  text: Business customers who need a data processing agreement should contact us before sending personal data.\ndeletion:\n  route: dashboard request after reauthentication\n  text: Use Account data in the dashboard to export your data or request account deletion after reauthentication.\nrights:\n- right: export\n  text: Use Account data in the dashboard to export your data or request account deletion after reauthentication.\n- right: deletion\n  text: request account deletion after reauthentication\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/toneperfect/privacy/toneperfect-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
summary_line: 21 quoted statements, read from TonePerfect (Pronunciation Assessment API)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Speech
- Language Learning
- Pronunciation
---
