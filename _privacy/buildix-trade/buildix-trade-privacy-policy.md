---
api_specs:
- filename: buildix-trade-deep-view-api-openapi.yml
  format: yaml
  label: Buildix Deep View API
  slug: buildix-trade-deep-view-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildix-trade/openapi/buildix-trade-deep-view-api-openapi.yml
- filename: buildix-trade-funding-arb-api-openapi.yml
  format: yaml
  label: Buildix Funding Arb API
  slug: buildix-trade-funding-arb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildix-trade/openapi/buildix-trade-funding-arb-api-openapi.yml
- filename: buildix-trade-pair-api-openapi.yml
  format: yaml
  label: Buildix Pair API
  slug: buildix-trade-pair-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildix-trade/openapi/buildix-trade-pair-api-openapi.yml
- filename: buildix-trade-screener-api-openapi.yml
  format: yaml
  label: Buildix Screener API
  slug: buildix-trade-screener-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildix-trade/openapi/buildix-trade-screener-api-openapi.yml
- filename: buildix-trade-signals-api-openapi.yml
  format: yaml
  label: Buildix Signals API
  slug: buildix-trade-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildix-trade/openapi/buildix-trade-signals-api-openapi.yml
- filename: buildix-trade-smart-money-api-openapi.yml
  format: yaml
  label: Buildix Smart Money API
  slug: buildix-trade-smart-money-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildix-trade/openapi/buildix-trade-smart-money-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: email address, hashed password, display name (optional).'
  - category: financial
    text: 'Subscription data: subscription tier, payment amount, cryptocurrency used, transaction hash.'
  - category: behavioral
    text: 'Usage data: pages visited, features used, deep view count, watchlist symbols, alert configurations.'
  - category: device
    text: 'Technical data: IP address, browser type, device type, operating system.'
  - category: location
    text: 'Wallet address: if provided for portfolio tracking, used read-only to fetch position data from Hyperliquid.'
  deletion:
    route: Email hello@buildix.trade
    text: To exercise any right, email hello@buildix.trade .
  dpa:
    available: true
    text: all with appropriate data processing agreements
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: To provide and maintain the Service.
  - purpose: Process payments and manage subscriptions
    text: To process payments and manage subscriptions.
  - purpose: Transactional emails
    text: To send transactional emails (payment confirmation, account security).
  - purpose: Improve the Service
    text: To improve the Service based on usage patterns.
  - purpose: Abuse detection
    text: To detect and prevent abuse.
  - purpose: Show ads to free plan users
    text: To show ads to users of the free plan who have accepted advertising cookies.
  residency:
  - region: EU/US
    text: 'Supabase (database and authentication): stores account data, usage data, encrypted API keys. Servers in EU/US.'
  - region: Global
    text: 'Vercel (hosting): processes HTTP requests, server logs. Servers globally.'
  retention:
  - period: 30 days
    scope: Account data
    text: deleted within 30 days of account deletion request
  - period: 10 years
    scope: Subscription data
    text: retained for 10 years (Italian tax law obligation)
  - period: 12 months
    scope: Usage data
    text: retained for 12 months, then anonymized
  - period: 90 days
    scope: Technical logs
    text: retained for 90 days
  - period: null
    scope: Exchange/AI API keys
    text: deleted immediately upon your request or account deletion
  rights:
  - right: Access
    text: 'Access: request a copy of your personal data.'
  - right: Rectification
    text: 'Rectification: correct inaccurate data.'
  - right: Erasure
    text: 'Erasure: request deletion of your data ("right to be forgotten").'
  - right: Restriction
    text: 'Restriction: restrict processing in certain circumstances.'
  - right: Portability
    text: 'Portability: receive your data in a structured, machine-readable format.'
  - right: Objection
    text: 'Objection: object to processing based on legitimate interest.'
  - right: Withdraw consent
    text: 'Withdraw consent: for analytics and advertising cookies, at any time via Cookie settings.'
  role:
    text: The data controller is The Buildix Team, contactable at hello@buildix.trade .
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data, we do not build marketing profiles ourselves, and we never show ads to users on a paid plan.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: These transfers are protected by Standard Contractual Clauses (SCCs) approved by the European Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Buildix
provenance_date: '2026-11-09'
provider_name: Buildix
provider_slug: buildix-trade
slug: buildix-trade-privacy-policy
source_date: '2026-11-09'
source_filename: buildix-trade-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.buildix.trade/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Buildix\naid: buildix-trade\nurl: https://www.buildix.trade/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is The Buildix Team, contactable at hello@buildix.trade .\ndata_categories:\n- category: identifying\n  text: 'Account data: email address, hashed password, display name (optional).'\n- category: financial\n  text: 'Subscription data: subscription tier, payment amount, cryptocurrency used, transaction hash.'\n- category: behavioral\n  text: 'Usage data: pages visited, features used, deep view count, watchlist symbols, alert configurations.'\n- category:\
  \ device\n  text: 'Technical data: IP address, browser type, device type, operating system.'\n- category: location\n  text: 'Wallet address: if provided for portfolio tracking, used read-only to fetch position data from Hyperliquid.'\npurposes:\n- purpose: Provide and maintain the Service\n  text: To provide and maintain the Service.\n- purpose: Process payments and manage subscriptions\n  text: To process payments and manage subscriptions.\n- purpose: Transactional emails\n  text: To send transactional emails (payment confirmation, account security).\n- purpose: Improve the Service\n  text: To improve the Service based on usage patterns.\n- purpose: Abuse detection\n  text: To detect and prevent abuse.\n- purpose: Show ads to free plan users\n  text: To show ads to users of the free plan who have accepted advertising cookies.\nretention:\n- scope: Account data\n  period: 30 days\n  text: deleted within 30 days of account deletion request\n- scope: Subscription data\n  period: 10 years\n\
  \  text: retained for 10 years (Italian tax law obligation)\n- scope: Usage data\n  period: 12 months\n  text: retained for 12 months, then anonymized\n- scope: Technical logs\n  period: 90 days\n  text: retained for 90 days\n- scope: Exchange/AI API keys\n  period: null\n  text: deleted immediately upon your request or account deletion\nresidency:\n- region: EU/US\n  text: 'Supabase (database and authentication): stores account data, usage data, encrypted API keys. Servers in\n    EU/US.'\n- region: Global\n  text: 'Vercel (hosting): processes HTTP requests, server logs. Servers globally.'\ntransfers:\n- mechanism: SCC\n  text: These transfers are protected by Standard Contractual Clauses (SCCs) approved by the European Commission.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: all with appropriate data processing agreements\ndeletion:\n  route: Email hello@buildix.trade\n  text: To exercise any right, email hello@buildix.trade .\nrights:\n-\
  \ right: Access\n  text: 'Access: request a copy of your personal data.'\n- right: Rectification\n  text: 'Rectification: correct inaccurate data.'\n- right: Erasure\n  text: 'Erasure: request deletion of your data (\"right to be forgotten\").'\n- right: Restriction\n  text: 'Restriction: restrict processing in certain circumstances.'\n- right: Portability\n  text: 'Portability: receive your data in a structured, machine-readable format.'\n- right: Objection\n  text: 'Objection: object to processing based on legitimate interest.'\n- right: Withdraw consent\n  text: 'Withdraw consent: for analytics and advertising cookies, at any time via Cookie settings.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data, we do not build marketing profiles ourselves, and we never show ads to users on\n    a paid plan.\n"
source_yaml_url: https://artifacts.apis.io/buildix-trade/privacy/buildix-trade-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 30 quoted statements, read from Buildix's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Analytics
- Orderflow
- Artificial Intelligence
---
