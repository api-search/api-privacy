---
api_specs:
- filename: veezee-io-checkout-api-openapi.yml
  format: yaml
  label: veezee-io Checkout API
  slug: veezee-io-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veezee-io/openapi/veezee-io-checkout-api-openapi.yml
- filename: veezee-io-claim-api-openapi.yml
  format: yaml
  label: veezee-io Claim API
  slug: veezee-io-claim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veezee-io/openapi/veezee-io-claim-api-openapi.yml
- filename: veezee-io-keys-api-openapi.yml
  format: yaml
  label: veezee-io Keys API
  slug: veezee-io-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veezee-io/openapi/veezee-io-keys-api-openapi.yml
- filename: veezee-io-portal-api-openapi.yml
  format: yaml
  label: veezee-io Portal API
  slug: veezee-io-portal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veezee-io/openapi/veezee-io-portal-api-openapi.yml
- filename: veezee-io-recover-api-openapi.yml
  format: yaml
  label: veezee-io Recover API
  slug: veezee-io-recover-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veezee-io/openapi/veezee-io-recover-api-openapi.yml
- filename: veezee-io-reddit-api-openapi.yml
  format: yaml
  label: veezee-io Reddit API
  slug: veezee-io-reddit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veezee-io/openapi/veezee-io-reddit-api-openapi.yml
- filename: veezee-io-rekey-api-openapi.yml
  format: yaml
  label: veezee-io Rekey API
  slug: veezee-io-rekey-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veezee-io/openapi/veezee-io-rekey-api-openapi.yml
- filename: veezee-io-usage-api-openapi.yml
  format: yaml
  label: veezee-io Usage API
  slug: veezee-io-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veezee-io/openapi/veezee-io-usage-api-openapi.yml
- filename: veezee-io-x-api-openapi.yml
  format: yaml
  label: veezee-io X API
  slug: veezee-io-x-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veezee-io/openapi/veezee-io-x-api-openapi.yml
- filename: veezee-io-linked-in-api-openapi.yml
  format: yaml
  label: veezee-io Linked In API
  slug: veezee-io-linked-in-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/veezee-io/openapi/veezee-io-linked-in-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Email : only if you sign in or claim a key.'
  - category: behavioral
    text: 'Free-tier metering : per-IP daily counters that enforce the free budget.'
  - category: communication
    text: Used for sign-in codes, receipts, and the balance alerts you can turn off in the dashboard.
  - category: financial
    text: 'Charge records (the ledger) are kept indefinitely: they are your billing history.'
  deletion:
    route: Email hello@veezee.io
    text: To delete an account and its stored data, email hello@veezee.io .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Sign-in codes, receipts, balance alerts
    text: Used for sign-in codes, receipts, and the balance alerts you can turn off in the dashboard.
  - purpose: Free budget enforcement
    text: 'Free-tier metering : per-IP daily counters that enforce the free budget.'
  - purpose: Page analytics
    text: 'The site uses PostHog (EU-hosted) for page analytics: no session recording, query strings stripped before sending, no advertising cookies.'
  - purpose: Source attribution at signup
    text: it exists so signups can be attributed to a source once, at signup.
  residency:
  - region: EU
    text: The site uses PostHog (EU-hosted) for page analytics
  retention:
  - period: 30 days
    scope: API traffic request and response bodies
    text: 'API traffic : request and response bodies for up to 30 days, size-capped'
  - period: indefinitely
    scope: Charge records (ledger)
    text: 'Charge records (the ledger) are kept indefinitely: they are your billing history.'
  - period: 30 days
    scope: vz_attr cookie
    text: A first-party cookie named vz_attr remembers, for 30 days, which page and source first brought the browser here
  rights:
  - right: Deletion
    text: To delete an account and its stored data, email hello@veezee.io .
  - right: Key revocation or rotation
    text: Revoke or rotate keys anytime in the dashboard .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal data, we don't put personal information in telemetry, and we don't show ads.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: veezee-io
provenance_date: '2026-11-10'
provider_name: veezee-io
provider_slug: veezee-io
slug: veezee-io-privacy-policy
source_date: '2026-11-10'
source_filename: veezee-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://veezee.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: veezee-io\naid: veezee-io\nurl: https://veezee.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Email : only if you sign in or claim a key.'\n- category: behavioral\n  text: 'Free-tier metering : per-IP daily counters that enforce the free budget.'\n- category: communication\n  text: Used for sign-in codes, receipts, and the balance alerts you can turn off in the dashboard.\n- category: financial\n  text: 'Charge records (the ledger) are kept indefinitely: they are your billing history.'\npurposes:\n- purpose: Sign-in codes,\
  \ receipts, balance alerts\n  text: Used for sign-in codes, receipts, and the balance alerts you can turn off in the dashboard.\n- purpose: Free budget enforcement\n  text: 'Free-tier metering : per-IP daily counters that enforce the free budget.'\n- purpose: Page analytics\n  text: 'The site uses PostHog (EU-hosted) for page analytics: no session recording, query strings stripped before\n    sending, no advertising cookies.'\n- purpose: Source attribution at signup\n  text: it exists so signups can be attributed to a source once, at signup.\nretention:\n- scope: API traffic request and response bodies\n  period: 30 days\n  text: 'API traffic : request and response bodies for up to 30 days, size-capped'\n- scope: Charge records (ledger)\n  period: indefinitely\n  text: 'Charge records (the ledger) are kept indefinitely: they are your billing history.'\n- scope: vz_attr cookie\n  period: 30 days\n  text: A first-party cookie named vz_attr remembers, for 30 days, which page and source first\
  \ brought the browser\n    here\nresidency:\n- region: EU\n  text: The site uses PostHog (EU-hosted) for page analytics\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@veezee.io\n  text: To delete an account and its stored data, email hello@veezee.io .\nrights:\n- right: Deletion\n  text: To delete an account and its stored data, email hello@veezee.io .\n- right: Key revocation or rotation\n  text: Revoke or rotate keys anytime in the dashboard .\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal data, we don't put personal information in telemetry, and we don't show ads.\n"
source_yaml_url: https://artifacts.apis.io/veezee-io/privacy/veezee-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from veezee-io's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Data
- Data Enrichment
- Social Media
- Search
---
