---
api_specs:
- filename: twitr-sh-accounts-api-openapi.yml
  format: yaml
  label: twitr-sh Accounts API
  slug: twitr-sh-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitr-sh/openapi/twitr-sh-accounts-api-openapi.yml
- filename: twitr-sh-creator-api-openapi.yml
  format: yaml
  label: twitr-sh Creator API
  slug: twitr-sh-creator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitr-sh/openapi/twitr-sh-creator-api-openapi.yml
- filename: twitr-sh-intelligence-api-openapi.yml
  format: yaml
  label: twitr-sh Intelligence API
  slug: twitr-sh-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitr-sh/openapi/twitr-sh-intelligence-api-openapi.yml
- filename: twitr-sh-monitors-api-openapi.yml
  format: yaml
  label: twitr-sh Monitors API
  slug: twitr-sh-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitr-sh/openapi/twitr-sh-monitors-api-openapi.yml
- filename: twitr-sh-search-api-openapi.yml
  format: yaml
  label: twitr-sh Search API
  slug: twitr-sh-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitr-sh/openapi/twitr-sh-search-api-openapi.yml
- filename: twitr-sh-snapshots-api-openapi.yml
  format: yaml
  label: twitr-sh Snapshots API
  slug: twitr-sh-snapshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitr-sh/openapi/twitr-sh-snapshots-api-openapi.yml
- filename: twitr-sh-social-api-openapi.yml
  format: yaml
  label: twitr-sh Social API
  slug: twitr-sh-social-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitr-sh/openapi/twitr-sh-social-api-openapi.yml
- filename: twitr-sh-webhooks-api-openapi.yml
  format: yaml
  label: twitr-sh Webhooks API
  slug: twitr-sh-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twitr-sh/openapi/twitr-sh-webhooks-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your wallet address is your identifier — a pseudonymous public key.
  - category: identifying
    text: which handle belongs to which wallet, so ownership can be re-checked on every write
  - category: financial
    text: per-wallet run history (which tool ran, when, for how much — visible to you in the dashboard)
  deletion:
    route: Disconnect X accounts via DELETE /api/x-accounts/{handle}, delete monitors and webhooks, or email support@twitr.sh for deletion requests
    text: 'Disconnect X accounts ( DELETE /api/x-accounts/{handle} ), delete monitors and webhooks, at any time — each is free and wallet-signed. For anything else, including data questions or deletion requests: support@twitr.sh .'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: serving requests
    text: We do not use your queries or your connected account's data for anything other than serving your requests.
  - purpose: audit own usage
    text: These exist so you can retrieve what you paid for and audit your own usage.
  retention:
  - period: ~24 hours
    scope: monitor events
    text: monitor events (up to 500 per monitor, retained ~24 hours)
  - period: about 7 days
    scope: extraction snapshots and media download links
    text: extraction snapshots and media download links (available about 7 days)
  - period: about 7 days
    scope: webhook delivery logs
    text: webhook delivery logs (about 7 days)
  - period: about 10 minutes
    scope: idempotency replay entries
    text: idempotency replay entries (about 10 minutes)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No advertising, no analytics resale, no selling or renting of any data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: twitr-sh
provenance_date: '2026-11-10'
provider_name: twitr-sh
provider_slug: twitr-sh
slug: twitr-sh-privacy-policy
source_date: '2026-11-10'
source_filename: twitr-sh-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://twitr.sh/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: twitr-sh\naid: twitr-sh\nurl: https://twitr.sh/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your wallet address is your identifier — a pseudonymous public key.\n- category: identifying\n  text: which handle belongs to which wallet, so ownership can be re-checked on every write\n- category: financial\n  text: per-wallet run history (which tool ran, when, for how much — visible to you in the dashboard)\npurposes:\n- purpose: serving requests\n  text: We do not use your queries or your connected account's data for anything other\
  \ than serving your requests.\n- purpose: audit own usage\n  text: These exist so you can retrieve what you paid for and audit your own usage.\nretention:\n- scope: monitor events\n  period: ~24 hours\n  text: monitor events (up to 500 per monitor, retained ~24 hours)\n- scope: extraction snapshots and media download links\n  period: about 7 days\n  text: extraction snapshots and media download links (available about 7 days)\n- scope: webhook delivery logs\n  period: about 7 days\n  text: webhook delivery logs (about 7 days)\n- scope: idempotency replay entries\n  period: about 10 minutes\n  text: idempotency replay entries (about 10 minutes)\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Disconnect X accounts via DELETE /api/x-accounts/{handle}, delete monitors and webhooks, or email support@twitr.sh\n    for deletion requests\n  text: 'Disconnect X accounts ( DELETE /api/x-accounts/{handle}\
  \ ), delete monitors and webhooks, at any time —\n    each is free and wallet-signed. For anything else, including data questions or deletion requests: support@twitr.sh\n    .'\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: No advertising, no analytics resale, no selling or renting of any data.\n"
source_yaml_url: https://artifacts.apis.io/twitr-sh/privacy/twitr-sh-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 11 quoted statements, read from twitr-sh's own page on 2026-11-10.
synthetic: false
tags:
- Company
- X
- Twitter
- Pay-per-call
- Artificial Intelligence
---
