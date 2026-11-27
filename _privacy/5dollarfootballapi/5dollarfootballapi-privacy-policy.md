---
api_specs:
- filename: 5dollarfootballapi-bookmakers-api-openapi.yml
  format: yaml
  label: 5DollarFootballAPI Bookmakers API
  slug: 5dollarfootballapi-bookmakers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/5dollarfootballapi/openapi/5dollarfootballapi-bookmakers-api-openapi.yml
- filename: 5dollarfootballapi-countries-api-openapi.yml
  format: yaml
  label: 5DollarFootballAPI Countries API
  slug: 5dollarfootballapi-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/5dollarfootballapi/openapi/5dollarfootballapi-countries-api-openapi.yml
- filename: 5dollarfootballapi-fixtures-api-openapi.yml
  format: yaml
  label: 5DollarFootballAPI Fixtures API
  slug: 5dollarfootballapi-fixtures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/5dollarfootballapi/openapi/5dollarfootballapi-fixtures-api-openapi.yml
- filename: 5dollarfootballapi-leagues-api-openapi.yml
  format: yaml
  label: 5DollarFootballAPI Leagues API
  slug: 5dollarfootballapi-leagues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/5dollarfootballapi/openapi/5dollarfootballapi-leagues-api-openapi.yml
- filename: 5dollarfootballapi-standings-api-openapi.yml
  format: yaml
  label: 5DollarFootballAPI Standings API
  slug: 5dollarfootballapi-standings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/5dollarfootballapi/openapi/5dollarfootballapi-standings-api-openapi.yml
- filename: 5dollarfootballapi-status-api-openapi.yml
  format: yaml
  label: 5DollarFootballAPI Status API
  slug: 5dollarfootballapi-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/5dollarfootballapi/openapi/5dollarfootballapi-status-api-openapi.yml
- filename: 5dollarfootballapi-teams-api-openapi.yml
  format: yaml
  label: 5DollarFootballAPI Teams API
  slug: 5dollarfootballapi-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/5dollarfootballapi/openapi/5dollarfootballapi-teams-api-openapi.yml
- filename: 5dollarfootballapi-bookmakers-api-openapi.yml
  format: yaml
  label: 5DollarFootballAPI Bookmakers API
  slug: 5dollarfootballapi-bookmakers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/5dollarfootballapi/openapi/5dollarfootballapi-bookmakers-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your name and email, to create and secure your account.'
  - category: financial
    text: Stripe processes the payment and holds your card details — we never see or store them.
  - category: behavioral
    text: 'Site analytics: page paths, referral domain, campaign tags, country and broad device type, tied to a random browser identifier.'
  deletion:
    route: Delete account from account settings
    text: You can delete your account (and its keys and usage records) at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and security
    text: to create and secure your account
  - purpose: Power dashboard and enforce quotas
    text: aggregate request counts per key, to power your dashboard and enforce quotas
  - purpose: Subscription plan tracking
    text: We keep the Stripe customer and subscription identifiers, and your invoices, so we know which plan your account is on.
  - purpose: Understand signup and purchase sources
    text: so we can understand which pages and sources lead to signup and purchase
  retention:
  - period: 400 days
    scope: Page journeys
    text: page journeys are retained for no more than 400 days
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 5DollarFootballAPI
provenance_date: '2026-11-09'
provider_name: 5DollarFootballAPI
provider_slug: 5dollarfootballapi
slug: 5dollarfootballapi-privacy-policy
source_date: '2026-11-09'
source_filename: 5dollarfootballapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://5dollarfootballapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 5DollarFootballAPI\naid: 5dollarfootballapi\nurl: https://5dollarfootballapi.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account data: your name and email, to create and secure your account.'\n- category: financial\n  text: Stripe processes the payment and holds your card details — we never see or store them.\n- category: behavioral\n  text: 'Site analytics: page paths, referral domain, campaign tags, country and broad device type, tied to a random\n    browser identifier.'\npurposes:\n- purpose: Account creation and security\n\
  \  text: to create and secure your account\n- purpose: Power dashboard and enforce quotas\n  text: aggregate request counts per key, to power your dashboard and enforce quotas\n- purpose: Subscription plan tracking\n  text: We keep the Stripe customer and subscription identifiers, and your invoices, so we know which plan your\n    account is on.\n- purpose: Understand signup and purchase sources\n  text: so we can understand which pages and sources lead to signup and purchase\nretention:\n- scope: Page journeys\n  period: 400 days\n  text: page journeys are retained for no more than 400 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account from account settings\n  text: You can delete your account (and its keys and usage records) at any time.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/5dollarfootballapi/privacy/5dollarfootballapi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 10 quoted statements, read from 5DollarFootballAPI's own page on 2026-11-09.
synthetic: false
tags:
- Football
- Soccer
- Sports
- Sports Data
- Live Scores
- Fixtures
- Standings
- Statistics
- Odds
- Bookmakers
---
