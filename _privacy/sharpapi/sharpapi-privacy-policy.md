---
api_specs:
- filename: sharpapi-account-api-openapi.yml
  format: yaml
  label: SharpAPI Account API
  slug: sharpapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharpapi/openapi/sharpapi-account-api-openapi.yml
- filename: sharpapi-betting-splits-api-openapi.yml
  format: yaml
  label: SharpAPI Betting Splits API
  slug: sharpapi-betting-splits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharpapi/openapi/sharpapi-betting-splits-api-openapi.yml
- filename: sharpapi-deep-links-api-openapi.yml
  format: yaml
  label: SharpAPI Deep Links API
  slug: sharpapi-deep-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharpapi/openapi/sharpapi-deep-links-api-openapi.yml
- filename: sharpapi-events-api-openapi.yml
  format: yaml
  label: SharpAPI Events API
  slug: sharpapi-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharpapi/openapi/sharpapi-events-api-openapi.yml
- filename: sharpapi-futures-api-openapi.yml
  format: yaml
  label: SharpAPI Futures API
  slug: sharpapi-futures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharpapi/openapi/sharpapi-futures-api-openapi.yml
- filename: sharpapi-game-state-api-openapi.yml
  format: yaml
  label: SharpAPI Game State API
  slug: sharpapi-game-state-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharpapi/openapi/sharpapi-game-state-api-openapi.yml
- filename: sharpapi-health-api-openapi.yml
  format: yaml
  label: SharpAPI Health API
  slug: sharpapi-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharpapi/openapi/sharpapi-health-api-openapi.yml
- filename: sharpapi-odds-api-openapi.yml
  format: yaml
  label: SharpAPI Odds API
  slug: sharpapi-odds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharpapi/openapi/sharpapi-odds-api-openapi.yml
- filename: sharpapi-opportunities-api-openapi.yml
  format: yaml
  label: SharpAPI Opportunities API
  slug: sharpapi-opportunities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharpapi/openapi/sharpapi-opportunities-api-openapi.yml
- filename: sharpapi-reference-data-api-openapi.yml
  format: yaml
  label: SharpAPI Reference Data API
  slug: sharpapi-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharpapi/openapi/sharpapi-reference-data-api-openapi.yml
- filename: sharpapi-streaming-api-openapi.yml
  format: yaml
  label: SharpAPI Streaming API
  slug: sharpapi-streaming-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sharpapi/openapi/sharpapi-streaming-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address
  - category: identifying
    text: Name (if provided)
  - category: financial
    text: We receive and store your Stripe customer ID, subscription status, and billing history.
  - category: device
    text: IP addresses (from request headers)
  - category: behavioral
    text: Daily request counts (total, successful, failed, rate-limited)
  - category: communication
    text: If you contact us via email or our in-app chat (powered by Crisp), we retain those communications and any information you provide within them.
  deletion:
    route: Request deletion of your account and associated data by emailing us
    text: Request deletion of your account and associated data by emailing us
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: Provide, operate, and maintain the Service
  - purpose: Process subscriptions and billing
    text: Process subscriptions and billing through Stripe
  - purpose: Fraud and abuse prevention
    text: Detect and prevent fraud, abuse, and security threats (including rate limiting and usage pattern monitoring)
  - purpose: Aggregated analytics
    text: Generate aggregated, anonymized usage analytics
  retention:
  - period: Duration of account + 30 days after deletion
    scope: Account information
    text: Account information Duration of account + 30 days after deletion
  - period: 180 days
    scope: IP addresses
    text: IP addresses 180 days in server access logs, retained as payment-dispute and fraud evidence; also used transiently for bot checks
  - period: 365 days
    scope: Billing-name codes and browser identifiers
    text: Billing-name codes and browser identifiers 365 days (to detect repeated free-trial abuse)
  - period: 30 days
    scope: Stripe webhook records
    text: Stripe webhook records 30 days
  rights:
  - right: Access
    text: Access your personal information via the API (GET /api/v1/account) or by request
  - right: Correct
    text: Correct inaccurate personal data
  - right: Deletion
    text: Request deletion of your account and associated data by emailing us
  - right: Export
    text: Export your usage data in a machine-readable format
  - right: Opt out of non-essential analytics
    text: Opt out of non-essential analytics
  - right: Object
    text: You may object to processing based on legitimate interests.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, trade, or rent your personal information to third parties.
  subprocessors:
    text: 'We share information with the following categories of service providers who process data on our behalf:'
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on standard contractual clauses and service provider commitments to safeguard data transferred outside the EEA.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SharpAPI
provenance_date: '2026-11-10'
provider_name: SharpAPI
provider_slug: sharpapi
slug: sharpapi-privacy-policy
source_date: '2026-11-10'
source_filename: sharpapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sharpapi.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SharpAPI\naid: sharpapi\nurl: https://sharpapi.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email address\n- category: identifying\n  text: Name (if provided)\n- category: financial\n  text: We receive and store your Stripe customer ID, subscription status, and billing history.\n- category: device\n  text: IP addresses (from request headers)\n- category: behavioral\n  text: Daily request counts (total, successful, failed, rate-limited)\n- category: communication\n  text: If you contact us via email or our in-app chat (powered\
  \ by Crisp), we retain those communications and any\n    information you provide within them.\npurposes:\n- purpose: Provide and operate the Service\n  text: Provide, operate, and maintain the Service\n- purpose: Process subscriptions and billing\n  text: Process subscriptions and billing through Stripe\n- purpose: Fraud and abuse prevention\n  text: Detect and prevent fraud, abuse, and security threats (including rate limiting and usage pattern monitoring)\n- purpose: Aggregated analytics\n  text: Generate aggregated, anonymized usage analytics\nretention:\n- scope: Account information\n  period: Duration of account + 30 days after deletion\n  text: Account information Duration of account + 30 days after deletion\n- scope: IP addresses\n  period: 180 days\n  text: IP addresses 180 days in server access logs, retained as payment-dispute and fraud evidence; also used transiently\n    for bot checks\n- scope: Billing-name codes and browser identifiers\n  period: 365 days\n  text: Billing-name\
  \ codes and browser identifiers 365 days (to detect repeated free-trial abuse)\n- scope: Stripe webhook records\n  period: 30 days\n  text: Stripe webhook records 30 days\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: We rely on standard contractual clauses and service provider commitments to safeguard data transferred outside\n    the EEA.\nsubprocessors:\n  url: null\n  text: 'We share information with the following categories of service providers who process data on our behalf:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion of your account and associated data by emailing us\n  text: Request deletion of your account and associated data by emailing us\nrights:\n- right: Access\n  text: Access your personal information via the API (GET /api/v1/account) or by request\n- right: Correct\n  text: Correct inaccurate personal data\n- right: Deletion\n  text: Request deletion of your account and associated data by emailing us\n- right: Export\n\
  \  text: Export your usage data in a machine-readable format\n- right: Opt out of non-essential analytics\n  text: Opt out of non-essential analytics\n- right: Object\n  text: You may object to processing based on legitimate interests.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, trade, or rent your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/sharpapi/privacy/sharpapi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from SharpAPI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sports Betting
- Real-Time Data
- Gambling
---
