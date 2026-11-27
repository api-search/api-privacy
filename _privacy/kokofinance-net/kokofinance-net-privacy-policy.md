---
api_specs:
- filename: kokofinance-net-billing-api-openapi.yml
  format: yaml
  label: kokofinance-net Billing API
  slug: kokofinance-net-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kokofinance-net/openapi/kokofinance-net-billing-api-openapi.yml
- filename: kokofinance-net-cards-api-openapi.yml
  format: yaml
  label: kokofinance-net Cards API
  slug: kokofinance-net-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kokofinance-net/openapi/kokofinance-net-cards-api-openapi.yml
- filename: kokofinance-net-developers-api-openapi.yml
  format: yaml
  label: kokofinance-net Developers API
  slug: kokofinance-net-developers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kokofinance-net/openapi/kokofinance-net-developers-api-openapi.yml
- filename: kokofinance-net-intelligence-api-openapi.yml
  format: yaml
  label: kokofinance-net Intelligence API
  slug: kokofinance-net-intelligence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kokofinance-net/openapi/kokofinance-net-intelligence-api-openapi.yml
- filename: kokofinance-net-international-api-openapi.yml
  format: yaml
  label: kokofinance-net International API
  slug: kokofinance-net-international-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kokofinance-net/openapi/kokofinance-net-international-api-openapi.yml
- filename: kokofinance-net-platform-api-openapi.yml
  format: yaml
  label: kokofinance-net Platform API
  slug: kokofinance-net-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kokofinance-net/openapi/kokofinance-net-platform-api-openapi.yml
- filename: kokofinance-net-portfolio-api-openapi.yml
  format: yaml
  label: kokofinance-net Portfolio API
  slug: kokofinance-net-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kokofinance-net/openapi/kokofinance-net-portfolio-api-openapi.yml
- filename: kokofinance-net-reference-api-openapi.yml
  format: yaml
  label: kokofinance-net Reference API
  slug: kokofinance-net-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kokofinance-net/openapi/kokofinance-net-reference-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and email address — from your Google profile
  - category: contact
    text: Name and email address — from your Google profile
  - category: financial
    text: 'Monthly spending estimates — category-level amounts (e.g., "dining: $500/month"), not individual transactions'
  - category: location
    text: State of residence (two-letter code only)
  - category: behavioral
    text: Card searches, comparisons, and calculator usage tied to an anonymized visitor hash
  - category: device
    text: JWT authentication tokens — stored in your browser's localStorage to keep you signed in
  deletion:
    route: Request via email to team@kokofinance.net
    text: Deletion — request deletion of your account and all associated data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authentication and account recovery
    text: Authentication, session management, and account recovery
  - purpose: Personalized card recommendations
    text: Personalized card recommendations, portfolio optimization, and renewal analysis
  - purpose: Usage metering and billing
    text: Usage metering, billing, rate limiting, and debugging
  - purpose: Improving the product
    text: Improving the product, understanding usage patterns, and fixing bugs
  residency:
  - region: US
    text: All stored data resides on GCP (US region)
  retention:
  - period: null
    scope: Account and profile data
    text: Account and profile data — retained as long as your account is active
  - period: null
    scope: Analytics events
    text: Analytics events — retained in aggregate; individual event records are purged periodically
  rights:
  - right: Access
    text: Access — request a copy of the data we hold about you
  - right: Correction
    text: Correction — update or correct your profile information at any time through your account settings
  - right: Deletion
    text: Deletion — request deletion of your account and all associated data
  - right: Portability
    text: Portability — request your data in a machine-readable format
  - right: Opt-out of analytics
    text: Opt-out of analytics — disable Google Analytics via the GA opt-out add-on
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or share your information with advertisers or data brokers
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: kokofinance-net
provenance_date: '2026-11-09'
provider_name: kokofinance-net
provider_slug: kokofinance-net
slug: kokofinance-net-privacy-policy
source_date: '2026-11-09'
source_filename: kokofinance-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://kokofinance.net/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: kokofinance-net\naid: kokofinance-net\nurl: https://kokofinance.net/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name and email address — from your Google profile\n- category: contact\n  text: Name and email address — from your Google profile\n- category: financial\n  text: 'Monthly spending estimates — category-level amounts (e.g., \"dining: $500/month\"), not individual transactions'\n- category: location\n  text: State of residence (two-letter code only)\n- category: behavioral\n  text: Card searches, comparisons, and\
  \ calculator usage tied to an anonymized visitor hash\n- category: device\n  text: JWT authentication tokens — stored in your browser's localStorage to keep you signed in\npurposes:\n- purpose: Authentication and account recovery\n  text: Authentication, session management, and account recovery\n- purpose: Personalized card recommendations\n  text: Personalized card recommendations, portfolio optimization, and renewal analysis\n- purpose: Usage metering and billing\n  text: Usage metering, billing, rate limiting, and debugging\n- purpose: Improving the product\n  text: Improving the product, understanding usage patterns, and fixing bugs\nretention:\n- scope: Account and profile data\n  period: null\n  text: Account and profile data — retained as long as your account is active\n- scope: Analytics events\n  period: null\n  text: Analytics events — retained in aggregate; individual event records are purged periodically\nresidency:\n- region: US\n  text: All stored data resides on GCP (US\
  \ region)\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via email to team@kokofinance.net\n  text: Deletion — request deletion of your account and all associated data\nrights:\n- right: Access\n  text: Access — request a copy of the data we hold about you\n- right: Correction\n  text: Correction — update or correct your profile information at any time through your account settings\n- right: Deletion\n  text: Deletion — request deletion of your account and all associated data\n- right: Portability\n  text: Portability — request your data in a machine-readable format\n- right: Opt-out of analytics\n  text: Opt-out of analytics — disable Google Analytics via the GA opt-out add-on\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or share your information with advertisers or data brokers\n"
source_yaml_url: https://artifacts.apis.io/kokofinance-net/privacy/kokofinance-net-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from kokofinance-net's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Credit Cards
- MCP
---
