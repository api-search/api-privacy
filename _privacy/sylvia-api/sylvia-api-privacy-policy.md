---
api_specs:
- filename: sylvia-api-live-api-openapi.yml
  format: yaml
  label: Sylvia API Live API
  slug: sylvia-api-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sylvia-api/openapi/sylvia-api-live-api-openapi.yml
- filename: sylvia-api-subreddits-api-openapi.yml
  format: yaml
  label: Sylvia API Subreddits API
  slug: sylvia-api-subreddits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sylvia-api/openapi/sylvia-api-subreddits-api-openapi.yml
- filename: sylvia-api-users-api-openapi.yml
  format: yaml
  label: Sylvia API Users API
  slug: sylvia-api-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sylvia-api/openapi/sylvia-api-users-api-openapi.yml
- filename: sylvia-api-account-api-openapi.yml
  format: yaml
  label: Sylvia API Account API
  slug: sylvia-api-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sylvia-api/openapi/sylvia-api-account-api-openapi.yml
- filename: sylvia-api-billing-api-openapi.yml
  format: yaml
  label: Sylvia API Billing API
  slug: sylvia-api-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sylvia-api/openapi/sylvia-api-billing-api-openapi.yml
- filename: sylvia-api-discovery-api-openapi.yml
  format: yaml
  label: Sylvia API Discovery API
  slug: sylvia-api-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sylvia-api/openapi/sylvia-api-discovery-api-openapi.yml
- filename: sylvia-api-domains-api-openapi.yml
  format: yaml
  label: Sylvia API Domains API
  slug: sylvia-api-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sylvia-api/openapi/sylvia-api-domains-api-openapi.yml
- filename: sylvia-api-health-api-openapi.yml
  format: yaml
  label: Sylvia API Health API
  slug: sylvia-api-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sylvia-api/openapi/sylvia-api-health-api-openapi.yml
- filename: sylvia-api-keys-api-openapi.yml
  format: yaml
  label: Sylvia API Keys API
  slug: sylvia-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sylvia-api/openapi/sylvia-api-keys-api-openapi.yml
- filename: sylvia-api-posts-comments-api-openapi.yml
  format: yaml
  label: Sylvia API Posts & Comments API
  slug: sylvia-api-posts-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sylvia-api/openapi/sylvia-api-posts-comments-api-openapi.yml
- filename: sylvia-api-search-api-openapi.yml
  format: yaml
  label: Sylvia API Search API
  slug: sylvia-api-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sylvia-api/openapi/sylvia-api-search-api-openapi.yml
- filename: sylvia-api-templates-api-openapi.yml
  format: yaml
  label: Sylvia API Templates API
  slug: sylvia-api-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sylvia-api/openapi/sylvia-api-templates-api-openapi.yml
- filename: sylvia-api-comments-api-openapi.yml
  format: yaml
  label: Sylvia API Comments API
  slug: sylvia-api-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sylvia-api/openapi/sylvia-api-comments-api-openapi.yml
- filename: sylvia-api-datasets-api-openapi.yml
  format: yaml
  label: Sylvia API Datasets API
  slug: sylvia-api-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sylvia-api/openapi/sylvia-api-datasets-api-openapi.yml
- filename: sylvia-api-posts-api-openapi.yml
  format: yaml
  label: Sylvia API Posts API
  slug: sylvia-api-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sylvia-api/openapi/sylvia-api-posts-api-openapi.yml
- filename: sylvia-api-usage-api-openapi.yml
  format: yaml
  label: Sylvia API Usage API
  slug: sylvia-api-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sylvia-api/openapi/sylvia-api-usage-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: your email address
  - category: identifying
    text: We issue an account token and, when you create one, an API key.
  - category: behavioral
    text: We record request counts and timestamps per key.
  - category: financial
    text: We store your balance. We do not store your wallet address.
  - category: device
    text: We log standard technical data. That includes your IP address, browser type, and request times.
  deletion:
    route: Email request to delete account
    text: Ask us to delete your account and its data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authentication
    text: First, we authenticate you.
  - purpose: billing
    text: Second, we bill you. We charge per successful request, and we need your usage records to do that.
  - purpose: abuse prevention
    text: Third, we stop abuse. We watch for spam, scraping at abusive scale, and attacks on our service.
  - purpose: legal compliance
    text: Fourth, we comply with the law. We answer valid legal requests when we must.
  residency:
  - region: European Union and United States
    text: We process data mostly in the European Union and the United States.
  retention:
  - period: null
    scope: account data
    text: We keep account data while your account is active.
  - period: null
    scope: request history
    text: Request history lives in memory only and is not archived.
  rights:
  - right: access
    text: Access. Ask for a copy of the data we hold about you.
  - right: correct
    text: Correct. Fix data that is wrong or incomplete.
  - right: delete
    text: Delete. Ask us to delete your account and its data.
  - right: export
    text: Export. Get your data in a common machine-readable format.
  - right: object
    text: Object. Object to processing that relies on legitimate interest.
  role:
    text: Data controller. We control the account data you give us.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data. We do not share it for marketing.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: When data moves between regions, we use standard safeguards such as Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Sylvia API
provenance_date: '2026-11-10'
provider_name: Sylvia API
provider_slug: sylvia-api
slug: sylvia-api-privacy-policy
source_date: '2026-11-10'
source_filename: sylvia-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sylvia-api.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Sylvia API\naid: sylvia-api\nurl: https://sylvia-api.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Data controller. We control the account data you give us.\ndata_categories:\n- category: contact\n  text: your email address\n- category: identifying\n  text: We issue an account token and, when you create one, an API key.\n- category: behavioral\n  text: We record request counts and timestamps per key.\n- category: financial\n  text: We store your balance. We do not store your wallet address.\n- category: device\n  text: We log standard technical data. That includes your IP address,\
  \ browser type, and request times.\npurposes:\n- purpose: authentication\n  text: First, we authenticate you.\n- purpose: billing\n  text: Second, we bill you. We charge per successful request, and we need your usage records to do that.\n- purpose: abuse prevention\n  text: Third, we stop abuse. We watch for spam, scraping at abusive scale, and attacks on our service.\n- purpose: legal compliance\n  text: Fourth, we comply with the law. We answer valid legal requests when we must.\nretention:\n- scope: account data\n  period: null\n  text: We keep account data while your account is active.\n- scope: request history\n  period: null\n  text: Request history lives in memory only and is not archived.\nresidency:\n- region: European Union and United States\n  text: We process data mostly in the European Union and the United States.\ntransfers:\n- mechanism: SCC\n  text: When data moves between regions, we use standard safeguards such as Standard Contractual Clauses.\nsubprocessors:\n  url:\
  \ null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to delete account\n  text: Ask us to delete your account and its data.\nrights:\n- right: access\n  text: Access. Ask for a copy of the data we hold about you.\n- right: correct\n  text: Correct. Fix data that is wrong or incomplete.\n- right: delete\n  text: Delete. Ask us to delete your account and its data.\n- right: export\n  text: Export. Get your data in a common machine-readable format.\n- right: object\n  text: Object. Object to processing that relies on legitimate interest.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data. We do not share it for marketing.\n"
source_yaml_url: https://artifacts.apis.io/sylvia-api/privacy/sylvia-api-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Sylvia API's own page on 2026-11-10.
synthetic: false
tags:
- Reddit
- Social
- Data
- Search
- Comments
- Research
- Content
- Datasets
- A2A
---
