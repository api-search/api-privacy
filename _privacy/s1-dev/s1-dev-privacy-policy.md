---
api_specs:
- filename: s1-dev-account-api-openapi.yml
  format: yaml
  label: Search1API Account API
  slug: s1-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s1-dev/openapi/s1-dev-account-api-openapi.yml
- filename: s1-dev-crawl-api-openapi.yml
  format: yaml
  label: Search1API Crawl API
  slug: s1-dev-crawl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s1-dev/openapi/s1-dev-crawl-api-openapi.yml
- filename: s1-dev-feedback-api-openapi.yml
  format: yaml
  label: Search1API Feedback API
  slug: s1-dev-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s1-dev/openapi/s1-dev-feedback-api-openapi.yml
- filename: s1-dev-screenshot-api-openapi.yml
  format: yaml
  label: Search1API Screenshot API
  slug: s1-dev-screenshot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s1-dev/openapi/s1-dev-screenshot-api-openapi.yml
- filename: s1-dev-search-api-openapi.yml
  format: yaml
  label: Search1API Search API
  slug: s1-dev-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s1-dev/openapi/s1-dev-search-api-openapi.yml
- filename: s1-dev-system-api-openapi.yml
  format: yaml
  label: Search1API System API
  slug: s1-dev-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/s1-dev/openapi/s1-dev-system-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: Depending on how you use Search1API, the service may process account and contact information, authentication and billing records
  - category: device
    text: IP address, browser or client information, and cookies needed for authentication, preferences, analytics, and service operation.
  - category: behavioral
    text: search queries, URLs submitted for retrieval, request parameters, returned source content, timestamps, response status, latency, diagnostics, security events
  - category: financial
    text: Payment-card details are handled by the payment provider rather than stored directly by Search1API.
  deletion:
    route: email request
    text: Privacy questions or requests can be sent to sys@search1api.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service operation and authentication
    text: Information is used to authenticate and authorize access, perform requested search and retrieval work
  - purpose: acquisition measurement
    text: We save campaign tags, landing paths and referring-site origins to understand acquisition
  retention:
  - period: 90 days
    scope: browser attribution data
    text: Browser attribution expires after 90 days.
  - period: null
    scope: records for security, billing, fraud, disputes, legal compliance
    text: Search1API may verify identity and may retain records required for security, billing, fraud prevention, disputes, or legal compliance.
  rights:
  - right: access, correction, deletion, restriction
    text: request access, correction, deletion, or restriction where applicable
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Search1API does not sell or rent personal information.
  subprocessors:
    text: Search queries, submitted URLs, and related parameters may be sent to search, crawling, network, hosting, identity, analytics, email, support, or payment providers when their services are needed to fulfill the request.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Search1API
provenance_date: '2026-11-10'
provider_name: Search1API
provider_slug: s1-dev
slug: s1-dev-privacy-policy
source_date: '2026-11-10'
source_filename: s1-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://s1.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Search1API\naid: s1-dev\nurl: https://s1.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Depending on how you use Search1API, the service may process account and contact information, authentication\n    and billing records\n- category: device\n  text: IP address, browser or client information, and cookies needed for authentication, preferences, analytics,\n    and service operation.\n- category: behavioral\n  text: search queries, URLs submitted for retrieval, request parameters, returned source content, timestamps, response\n \
  \   status, latency, diagnostics, security events\n- category: financial\n  text: Payment-card details are handled by the payment provider rather than stored directly by Search1API.\npurposes:\n- purpose: service operation and authentication\n  text: Information is used to authenticate and authorize access, perform requested search and retrieval work\n- purpose: acquisition measurement\n  text: We save campaign tags, landing paths and referring-site origins to understand acquisition\nretention:\n- scope: browser attribution data\n  period: 90 days\n  text: Browser attribution expires after 90 days.\n- scope: records for security, billing, fraud, disputes, legal compliance\n  period: null\n  text: Search1API may verify identity and may retain records required for security, billing, fraud prevention,\n    disputes, or legal compliance.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Search queries, submitted URLs, and related parameters may be sent to search, crawling,\
  \ network, hosting,\n    identity, analytics, email, support, or payment providers when their services are needed to fulfill the request.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: Privacy questions or requests can be sent to sys@search1api.com.\nrights:\n- right: access, correction, deletion, restriction\n  text: request access, correction, deletion, or restriction where applicable\nsale_or_sharing:\n  stance: prohibited\n  text: Search1API does not sell or rent personal information.\n"
source_yaml_url: https://artifacts.apis.io/s1-dev/privacy/s1-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 12 quoted statements, read from Search1API's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Search
- Web Search
- Crawling
- Web Scraping
- News
- AI Agents
- MCP
- Agent Tools
- Data Extraction
- Screenshots
---
