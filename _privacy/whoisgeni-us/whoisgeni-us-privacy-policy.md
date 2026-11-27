---
api_specs:
- filename: whoisgeni-us-account-api-openapi.yml
  format: yaml
  label: whoisgeni-us Account API
  slug: whoisgeni-us-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-account-api-openapi.yml
- filename: whoisgeni-us-analysis-api-openapi.yml
  format: yaml
  label: whoisgeni-us Analysis API
  slug: whoisgeni-us-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-analysis-api-openapi.yml
- filename: whoisgeni-us-authentication-api-openapi.yml
  format: yaml
  label: whoisgeni-us Authentication API
  slug: whoisgeni-us-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-authentication-api-openapi.yml
- filename: whoisgeni-us-billing-api-openapi.yml
  format: yaml
  label: whoisgeni-us Billing API
  slug: whoisgeni-us-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-billing-api-openapi.yml
- filename: whoisgeni-us-byok-api-openapi.yml
  format: yaml
  label: whoisgeni-us Byok API
  slug: whoisgeni-us-byok-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-byok-api-openapi.yml
- filename: whoisgeni-us-correlation-api-openapi.yml
  format: yaml
  label: whoisgeni-us Correlation API
  slug: whoisgeni-us-correlation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-correlation-api-openapi.yml
- filename: whoisgeni-us-domains-api-openapi.yml
  format: yaml
  label: whoisgeni-us Domains API
  slug: whoisgeni-us-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-domains-api-openapi.yml
- filename: whoisgeni-us-entities-api-openapi.yml
  format: yaml
  label: whoisgeni-us Entities API
  slug: whoisgeni-us-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-entities-api-openapi.yml
- filename: whoisgeni-us-health-api-openapi.yml
  format: yaml
  label: whoisgeni-us Health API
  slug: whoisgeni-us-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-health-api-openapi.yml
- filename: whoisgeni-us-jobs-api-openapi.yml
  format: yaml
  label: whoisgeni-us Jobs API
  slug: whoisgeni-us-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-jobs-api-openapi.yml
- filename: whoisgeni-us-mcp-api-openapi.yml
  format: yaml
  label: whoisgeni-us MCP API
  slug: whoisgeni-us-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-mcp-api-openapi.yml
- filename: whoisgeni-us-schema-templates-api-openapi.yml
  format: yaml
  label: whoisgeni-us Schema Templates API
  slug: whoisgeni-us-schema-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-schema-templates-api-openapi.yml
- filename: whoisgeni-us-webhooks-api-openapi.yml
  format: yaml
  label: whoisgeni-us Webhooks API
  slug: whoisgeni-us-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whoisgeni-us/openapi/whoisgeni-us-webhooks-api-openapi.yml
claim_count: 7
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, we collect your email address.
  - category: behavioral
    text: API queries are logged for rate limiting and billing purposes.
  - category: device
    text: Browser analytics use a device identifier and may use browser storage
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authentication, billing, service communication
    text: Your account information is used for authentication, billing, service communication, and understanding product usage.
  - purpose: product analytics
    text: We use PostHog to understand acquisition, product usage, and credit conversion.
  retention:
  - period: 24 hours for free tier
    scope: domain names submitted for analysis
    text: Domain names submitted for analysis are not stored beyond the cache retention period (typically 24 hours for free tier, configurable for paid tiers).
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We use service providers for these purposes and do not sell or rent your personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: whoisgeni-us
provenance_date: '2026-11-10'
provider_name: whoisgeni-us
provider_slug: whoisgeni-us
slug: whoisgeni-us-privacy-policy
source_date: '2026-11-10'
source_filename: whoisgeni-us-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://whoisgeni.us/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: whoisgeni-us\naid: whoisgeni-us\nurl: https://whoisgeni.us/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account, we collect your email address.\n- category: behavioral\n  text: API queries are logged for rate limiting and billing purposes.\n- category: device\n  text: Browser analytics use a device identifier and may use browser storage\npurposes:\n- purpose: authentication, billing, service communication\n  text: Your account information is used for authentication, billing, service communication, and understanding\
  \ product\n    usage.\n- purpose: product analytics\n  text: We use PostHog to understand acquisition, product usage, and credit conversion.\nretention:\n- scope: domain names submitted for analysis\n  period: 24 hours for free tier\n  text: Domain names submitted for analysis are not stored beyond the cache retention period (typically 24 hours\n    for free tier, configurable for paid tiers).\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We use service providers for these purposes and do not sell or rent your personal data.\n"
source_yaml_url: https://artifacts.apis.io/whoisgeni-us/privacy/whoisgeni-us-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- sale_or_sharing
summary_line: 7 quoted statements, read from whoisgeni-us's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Domain Intelligence
- Security
- Compliance
- Data Enrichment
---
