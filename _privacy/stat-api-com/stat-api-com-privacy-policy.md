---
api_specs:
- filename: stat-api-com-dfs-api-openapi.yml
  format: yaml
  label: stat-api-com DFS API
  slug: stat-api-com-dfs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stat-api-com/openapi/stat-api-com-dfs-api-openapi.yml
- filename: stat-api-com-mlb-api-openapi.yml
  format: yaml
  label: stat-api-com MLB API
  slug: stat-api-com-mlb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stat-api-com/openapi/stat-api-com-mlb-api-openapi.yml
- filename: stat-api-com-nba-api-openapi.yml
  format: yaml
  label: stat-api-com NBA API
  slug: stat-api-com-nba-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stat-api-com/openapi/stat-api-com-nba-api-openapi.yml
- filename: stat-api-com-nfl-api-openapi.yml
  format: yaml
  label: stat-api-com NFL API
  slug: stat-api-com-nfl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stat-api-com/openapi/stat-api-com-nfl-api-openapi.yml
- filename: stat-api-com-nhl-api-openapi.yml
  format: yaml
  label: stat-api-com NHL API
  slug: stat-api-com-nhl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stat-api-com/openapi/stat-api-com-nhl-api-openapi.yml
- filename: stat-api-com-pga-api-openapi.yml
  format: yaml
  label: stat-api-com PGA API
  slug: stat-api-com-pga-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stat-api-com/openapi/stat-api-com-pga-api-openapi.yml
- filename: stat-api-com-reference-api-openapi.yml
  format: yaml
  label: stat-api-com Reference API
  slug: stat-api-com-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stat-api-com/openapi/stat-api-com-reference-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name and email address, provided when you sign in (currently via Google OAuth)
  - category: financial
    text: We store a customer and subscription identifier and your plan, but we do not store full payment-card numbers
  - category: device
    text: request metadata such as endpoints called, timestamps, IP address, user-agent, rate-limit counters, and error logs
  - category: behavioral
    text: we use Google Analytics to record the pages you view, the time you spend on each page, the links you click
  - category: communication
    text: messages you send us for support and any details you submit through the enterprise inquiry form
  deletion:
    route: account closure or email request
    text: When you close your account we delete or anonymize your account information
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and authenticate the Service
    text: We use information to provide and authenticate the Service
  - purpose: billing
    text: process billing
  - purpose: security and fraud prevention
    text: maintain security and prevent fraud or abuse
  - purpose: measurement of pages and campaigns
    text: measure which pages and campaigns bring visitors and accounts
  residency:
  - region: United States
    text: We process information in the United States.
  retention:
  - period: 14 months
    scope: website analytics data
    text: Google Analytics keeps website analytics data for 14 months.
  - period: while your account is active
    scope: account information
    text: We retain account information while your account is active
  - period: as long as required by law
    scope: billing records
    text: billing records for as long as required by law
  rights:
  - right: access, correct, delete, port
    text: you may have rights to access, correct, delete, or port your account information
  - right: opt out of sale or sharing
    text: the right to know, delete, correct, and opt out of sale or sharing
  - right: object or restrict processing
    text: to object to or restrict certain processing
  role:
    text: The controller responsible for your information is Verum Technologies LLC
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: Cloudflare (hosting and content delivery), and our infrastructure providers
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we rely on an appropriate transfer mechanism such as the Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: stat-api-com
provenance_date: '2026-11-10'
provider_name: stat-api-com
provider_slug: stat-api-com
slug: stat-api-com-privacy-policy
source_date: '2026-11-10'
source_filename: stat-api-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://stat-api.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: stat-api-com\naid: stat-api-com\nurl: https://stat-api.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller responsible for your information is Verum Technologies LLC\ndata_categories:\n- category: identifying\n  text: your name and email address, provided when you sign in (currently via Google OAuth)\n- category: financial\n  text: We store a customer and subscription identifier and your plan, but we do not store full payment-card numbers\n- category: device\n  text: request metadata such as endpoints called, timestamps, IP address, user-agent, rate-limit counters, and\n\
  \    error logs\n- category: behavioral\n  text: we use Google Analytics to record the pages you view, the time you spend on each page, the links you click\n- category: communication\n  text: messages you send us for support and any details you submit through the enterprise inquiry form\npurposes:\n- purpose: provide and authenticate the Service\n  text: We use information to provide and authenticate the Service\n- purpose: billing\n  text: process billing\n- purpose: security and fraud prevention\n  text: maintain security and prevent fraud or abuse\n- purpose: measurement of pages and campaigns\n  text: measure which pages and campaigns bring visitors and accounts\nretention:\n- scope: website analytics data\n  period: 14 months\n  text: Google Analytics keeps website analytics data for 14 months.\n- scope: account information\n  period: while your account is active\n  text: We retain account information while your account is active\n- scope: billing records\n  period: as long as required\
  \ by law\n  text: billing records for as long as required by law\nresidency:\n- region: United States\n  text: We process information in the United States.\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on an appropriate transfer mechanism such as the Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: Cloudflare (hosting and content delivery), and our infrastructure providers\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account closure or email request\n  text: When you close your account we delete or anonymize your account information\nrights:\n- right: access, correct, delete, port\n  text: you may have rights to access, correct, delete, or port your account information\n- right: opt out of sale or sharing\n  text: the right to know, delete, correct, and opt out of sale or sharing\n- right: object or restrict processing\n  text: to object to or restrict certain processing\nsale_or_sharing:\n  stance: prohibited\n  text: We\
  \ do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/stat-api-com/privacy/stat-api-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from stat-api-com's own page on 2026-11-10.
synthetic: false
tags:
- Sports
- Data
- DFS
- Fantasy
---
