---
api_specs:
- filename: searlo-tech-account-api-openapi.yml
  format: yaml
  label: searlo-tech Account API
  slug: searlo-tech-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searlo-tech/openapi/searlo-tech-account-api-openapi.yml
- filename: searlo-tech-ai-answers-api-openapi.yml
  format: yaml
  label: searlo-tech AI Answers API
  slug: searlo-tech-ai-answers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searlo-tech/openapi/searlo-tech-ai-answers-api-openapi.yml
- filename: searlo-tech-async-api-openapi.yml
  format: yaml
  label: searlo-tech Async API
  slug: searlo-tech-async-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searlo-tech/openapi/searlo-tech-async-api-openapi.yml
- filename: searlo-tech-domain-api-openapi.yml
  format: yaml
  label: searlo-tech Domain API
  slug: searlo-tech-domain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searlo-tech/openapi/searlo-tech-domain-api-openapi.yml
- filename: searlo-tech-rankings-api-openapi.yml
  format: yaml
  label: searlo-tech Rankings API
  slug: searlo-tech-rankings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searlo-tech/openapi/searlo-tech-rankings-api-openapi.yml
- filename: searlo-tech-search-api-openapi.yml
  format: yaml
  label: searlo-tech Search API
  slug: searlo-tech-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searlo-tech/openapi/searlo-tech-search-api-openapi.yml
- filename: searlo-tech-serp-api-openapi.yml
  format: yaml
  label: searlo-tech SERP API
  slug: searlo-tech-serp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searlo-tech/openapi/searlo-tech-serp-api-openapi.yml
- filename: searlo-tech-tools-api-openapi.yml
  format: yaml
  label: searlo-tech Tools API
  slug: searlo-tech-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searlo-tech/openapi/searlo-tech-tools-api-openapi.yml
- filename: searlo-tech-web-data-api-openapi.yml
  format: yaml
  label: searlo-tech Web Data API
  slug: searlo-tech-web-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searlo-tech/openapi/searlo-tech-web-data-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, we collect your email address, name, and payment information (processed securely by Paddle).
  - category: behavioral
    text: We collect API usage data including search queries, request timestamps, response times, and error logs to improve our services and provide analytics.
  - category: device
    text: We collect IP addresses, browser type, device information, and cookies for security and service optimization.
  deletion:
    route: Request deletion or delete search-history entries
    text: You can request deletion of your data at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain, and improve services
    text: Provide, maintain, and improve our services
  - purpose: Process transactions
    text: Process transactions and send related information
  - purpose: Fraud detection and prevention
    text: Detect, investigate, and prevent fraudulent activities
  residency:
  - region: European Union
    text: All service data is stored exclusively in the European Union.
  retention:
  - period: 90 days
    scope: Search query history
    text: Search query history is retained for a maximum of 90 days and then automatically purged by a daily job.
  - period: a few hours
    scope: Search result sets
    text: Search result sets are cached transiently only (a few hours) and are not retained long-term.
  rights:
  - right: Access
    text: Access your personal data
  - right: Correct
    text: Correct inaccurate data
  - right: Deletion
    text: Request deletion of your data
  - right: Export
    text: Export your data in a portable format
  - right: Opt out of marketing
    text: Opt out of marketing communications
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: No data is transferred to or stored in regions outside the EU, except as required for payment processing (Paddle, UK/EU) and CDN edge caching (Cloudflare, transient only).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: searlo-tech
provenance_date: '2026-11-10'
provider_name: searlo-tech
provider_slug: searlo-tech
slug: searlo-tech-privacy-policy
source_date: '2026-11-10'
source_filename: searlo-tech-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://searlo.tech/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: searlo-tech\naid: searlo-tech\nurl: https://searlo.tech/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account, we collect your email address, name, and payment information (processed securely\n    by Paddle).\n- category: behavioral\n  text: We collect API usage data including search queries, request timestamps, response times, and error logs to\n    improve our services and provide analytics.\n- category: device\n  text: We collect IP addresses, browser type, device information, and cookies for security and\
  \ service optimization.\npurposes:\n- purpose: Provide, maintain, and improve services\n  text: Provide, maintain, and improve our services\n- purpose: Process transactions\n  text: Process transactions and send related information\n- purpose: Fraud detection and prevention\n  text: Detect, investigate, and prevent fraudulent activities\nretention:\n- scope: Search query history\n  period: 90 days\n  text: Search query history is retained for a maximum of 90 days and then automatically purged by a daily job.\n- scope: Search result sets\n  period: a few hours\n  text: Search result sets are cached transiently only (a few hours) and are not retained long-term.\nresidency:\n- region: European Union\n  text: All service data is stored exclusively in the European Union.\ntransfers:\n- mechanism: other\n  text: No data is transferred to or stored in regions outside the EU, except as required for payment processing\n    (Paddle, UK/EU) and CDN edge caching (Cloudflare, transient only).\nsubprocessors:\n\
  \  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion or delete search-history entries\n  text: You can request deletion of your data at any time.\nrights:\n- right: Access\n  text: Access your personal data\n- right: Correct\n  text: Correct inaccurate data\n- right: Deletion\n  text: Request deletion of your data\n- right: Export\n  text: Export your data in a portable format\n- right: Opt out of marketing\n  text: Opt out of marketing communications\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/searlo-tech/privacy/searlo-tech-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from searlo-tech's own page on 2026-11-10.
synthetic: false
tags:
- Search
- SERP
- Artificial Intelligence
- Data
---
