---
api_specs:
- filename: placementapi-com-account-api-openapi.yml
  format: yaml
  label: placementapi-com Account API
  slug: placementapi-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placementapi-com/openapi/placementapi-com-account-api-openapi.yml
- filename: placementapi-com-catalogue-api-openapi.yml
  format: yaml
  label: placementapi-com Catalogue API
  slug: placementapi-com-catalogue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placementapi-com/openapi/placementapi-com-catalogue-api-openapi.yml
- filename: placementapi-com-checkout-api-openapi.yml
  format: yaml
  label: placementapi-com Checkout API
  slug: placementapi-com-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placementapi-com/openapi/placementapi-com-checkout-api-openapi.yml
- filename: placementapi-com-comparison-api-openapi.yml
  format: yaml
  label: placementapi-com Comparison API
  slug: placementapi-com-comparison-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placementapi-com/openapi/placementapi-com-comparison-api-openapi.yml
- filename: placementapi-com-content-api-openapi.yml
  format: yaml
  label: placementapi-com Content API
  slug: placementapi-com-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placementapi-com/openapi/placementapi-com-content-api-openapi.yml
- filename: placementapi-com-meta-api-openapi.yml
  format: yaml
  label: placementapi-com Meta API
  slug: placementapi-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placementapi-com/openapi/placementapi-com-meta-api-openapi.yml
- filename: placementapi-com-orders-api-openapi.yml
  format: yaml
  label: placementapi-com Orders API
  slug: placementapi-com-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placementapi-com/openapi/placementapi-com-orders-api-openapi.yml
- filename: placementapi-com-planning-api-openapi.yml
  format: yaml
  label: placementapi-com Planning API
  slug: placementapi-com-planning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placementapi-com/openapi/placementapi-com-planning-api-openapi.yml
- filename: placementapi-com-research-api-openapi.yml
  format: yaml
  label: placementapi-com Research API
  slug: placementapi-com-research-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placementapi-com/openapi/placementapi-com-research-api-openapi.yml
- filename: placementapi-com-search-console-api-openapi.yml
  format: yaml
  label: placementapi-com Search Console API
  slug: placementapi-com-search-console-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placementapi-com/openapi/placementapi-com-search-console-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address. It is how you sign in; there is no password to store.
  - category: financial
    text: Your orders and ledger. What you bought, the target URLs and anchor text you supplied, what it cost, and every credit movement.
  - category: behavioral
    text: API usage counts. Requests and rows returned per key, to enforce rate limits and allowances.
  - category: other
    text: API keys. Stored as a SHA-256 hash with a short non-secret prefix so you can recognise which key is which.
  - category: other
    text: pull your search performance rows (page, query, clicks, impressions, position) each night into tables that belong to your account alone
  deletion:
    route: email hello@placementapi.com
    text: Email hello@placementapi.com and we will respond within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the service
    text: 'To run the service you asked for: authenticating you, placing and tracking your orders, keeping your balance correct, enforcing spend caps and rate limits, and meeting our tax and accounting obligations.'
  retention:
  - period: seven years
    scope: Orders and ledger entries
    text: Orders and ledger entries are kept for seven years, because they are financial records.
  - period: within days
    scope: Session and sign-in tokens
    text: Session and sign-in tokens expire within days.
  - period: null
    scope: Google Search Console data
    text: Disconnecting revokes our access at Google and deletes every row we held.
  rights:
  - right: access
    text: ask us for a copy of what we hold about you
  - right: correction
    text: ask us to correct it
  - right: deletion
    text: ask us to delete it
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data
  subprocessors:
    text: 'Processors we rely on: Stripe (payments), Neon (database), Vercel (hosting), Resend (transactional email)'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: placementapi-com
provenance_date: '2026-11-10'
provider_name: placementapi-com
provider_slug: placementapi-com
slug: placementapi-com-privacy-policy
source_date: '2026-11-10'
source_filename: placementapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://placementapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: placementapi-com\naid: placementapi-com\nurl: https://placementapi.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Your email address. It is how you sign in; there is no password to store.\n- category: financial\n  text: Your orders and ledger. What you bought, the target URLs and anchor text you supplied, what it cost, and\n    every credit movement.\n- category: behavioral\n  text: API usage counts. Requests and rows returned per key, to enforce rate limits and allowances.\n- category: other\n  text: API keys. Stored as a SHA-256\
  \ hash with a short non-secret prefix so you can recognise which key is which.\n- category: other\n  text: pull your search performance rows (page, query, clicks, impressions, position) each night into tables that\n    belong to your account alone\npurposes:\n- purpose: Run the service\n  text: 'To run the service you asked for: authenticating you, placing and tracking your orders, keeping your balance\n    correct, enforcing spend caps and rate limits, and meeting our tax and accounting obligations.'\nretention:\n- scope: Orders and ledger entries\n  period: seven years\n  text: Orders and ledger entries are kept for seven years, because they are financial records.\n- scope: Session and sign-in tokens\n  period: within days\n  text: Session and sign-in tokens expire within days.\n- scope: Google Search Console data\n  period: null\n  text: Disconnecting revokes our access at Google and deletes every row we held.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Processors\
  \ we rely on: Stripe (payments), Neon (database), Vercel (hosting), Resend (transactional email)'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@placementapi.com\n  text: Email hello@placementapi.com and we will respond within 30 days.\nrights:\n- right: access\n  text: ask us for a copy of what we hold about you\n- right: correction\n  text: ask us to correct it\n- right: deletion\n  text: ask us to delete it\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data\n"
source_yaml_url: https://artifacts.apis.io/placementapi-com/privacy/placementapi-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from placementapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- SEO
- Marketing
- Backlinks
- Automation
- Technology
---
