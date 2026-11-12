---
api_specs:
- filename: contrie-com-account-api-openapi.yml
  format: yaml
  label: Contrie Account API
  slug: contrie-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-account-api-openapi.yml
- filename: contrie-com-evidence-api-openapi.yml
  format: yaml
  label: Contrie Evidence API
  slug: contrie-com-evidence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-evidence-api-openapi.yml
- filename: contrie-com-extract-api-openapi.yml
  format: yaml
  label: Contrie Extract API
  slug: contrie-com-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-extract-api-openapi.yml
- filename: contrie-com-health-api-openapi.yml
  format: yaml
  label: Contrie Health API
  slug: contrie-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-health-api-openapi.yml
- filename: contrie-com-mcp-api-openapi.yml
  format: yaml
  label: Contrie MCP API
  slug: contrie-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-mcp-api-openapi.yml
- filename: contrie-com-monitors-api-openapi.yml
  format: yaml
  label: Contrie Monitors API
  slug: contrie-com-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-monitors-api-openapi.yml
- filename: contrie-com-scrape-api-openapi.yml
  format: yaml
  label: Contrie Scrape API
  slug: contrie-com-scrape-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-scrape-api-openapi.yml
- filename: contrie-com-search-api-openapi.yml
  format: yaml
  label: Contrie Search API
  slug: contrie-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-search-api-openapi.yml
- filename: contrie-com-verification-api-openapi.yml
  format: yaml
  label: Contrie Verification API
  slug: contrie-com-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-verification-api-openapi.yml
- filename: contrie-com-verify-api-openapi.yml
  format: yaml
  label: Contrie Verify API
  slug: contrie-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/contrie-com/openapi/contrie-com-verify-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: we collect your name and email address via our authentication provider (Clerk)
  - category: other
    text: we log the URLs you extract, usage counts, and performance metrics
  deletion:
    route: Dashboard settings
    text: From dashboard settings you can delete your Contrie product data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and improve service
    text: We use your information to provide and improve the Contrie service, track API usage against your plan limits, and communicate important service updates.
  retention:
  - period: 90 days on the Free plan or 1 year on paid plans
    scope: Extraction diagnostics
    text: Extraction diagnostics expire after 90 days on the Free plan or 1 year on paid plans, based on the plan when the request began.
  - period: 7 days
    scope: Snapshot verification content
    text: Snapshot verification content stops being available after 7 days.
  - period: 30 days
    scope: Hashed request identities
    text: Its content-free hashed request identities expire after 30 days so retries can be recognized without retaining the submitted page content.
  rights:
  - right: delete product data
    text: you can delete your Contrie product data
  - right: export product data
    text: or download a copy of it (the same scoped export as the API)
  - right: response time
    text: we will respond to data requests within 30 days
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to third parties.
  subprocessors:
    text: 'We use the following third-party services:'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Contrie
provenance_date: '2026-11-09'
provider_name: Contrie
provider_slug: contrie-com
slug: contrie-com-privacy-policy
source_date: '2026-11-09'
source_filename: contrie-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.contrie.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Contrie\naid: contrie-com\nurl: https://www.contrie.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: we collect your name and email address via our authentication provider (Clerk)\n- category: other\n  text: we log the URLs you extract, usage counts, and performance metrics\npurposes:\n- purpose: provide and improve service\n  text: We use your information to provide and improve the Contrie service, track API usage against your plan limits,\n    and communicate important service updates.\nretention:\n- scope: Extraction diagnostics\n\
  \  period: 90 days on the Free plan or 1 year on paid plans\n  text: Extraction diagnostics expire after 90 days on the Free plan or 1 year on paid plans, based on the plan\n    when the request began.\n- scope: Snapshot verification content\n  period: 7 days\n  text: Snapshot verification content stops being available after 7 days.\n- scope: Hashed request identities\n  period: 30 days\n  text: Its content-free hashed request identities expire after 30 days so retries can be recognized without retaining\n    the submitted page content.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We use the following third-party services:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Dashboard settings\n  text: From dashboard settings you can delete your Contrie product data\nrights:\n- right: delete product data\n  text: you can delete your Contrie product data\n- right: export product data\n  text: or download a copy of it (the same scoped export as\
  \ the API)\n- right: response time\n  text: we will respond to data requests within 30 days\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/contrie-com/privacy/contrie-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 12 quoted statements, read from Contrie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web Scraping
- Data Extraction
- AI Agents
- MCP
- Structured Data
- Markdown
---
