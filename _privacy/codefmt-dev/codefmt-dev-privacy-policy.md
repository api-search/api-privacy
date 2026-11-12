---
api_specs:
- filename: codefmt-dev-ask-api-openapi.yml
  format: yaml
  label: codefmt Ask API
  slug: codefmt-dev-ask-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codefmt-dev/openapi/codefmt-dev-ask-api-openapi.yml
- filename: codefmt-dev-format-api-openapi.yml
  format: yaml
  label: codefmt Format API
  slug: codefmt-dev-format-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codefmt-dev/openapi/codefmt-dev-format-api-openapi.yml
- filename: codefmt-dev-health-api-openapi.yml
  format: yaml
  label: codefmt Health API
  slug: codefmt-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codefmt-dev/openapi/codefmt-dev-health-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: behavioral
    text: 'requests to the api and agent endpoints (format, mcp, a2a, ask, llms.txt) are counted in aggregate through umami: endpoint, platform, and outcome only'
  - category: device
    text: the /api/format endpoint reads the ip address that vercel attaches to each request ( x-real-ip ) and holds it in a short-lived in-memory counter for up to 60 seconds
  - category: other
    text: submitted code and queries are processed in memory and never stored or sent to analytics
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: format code
    text: when you format code using the browser extension, your code is sent over https to codefmt.dev/api/format for processing
  - purpose: rate limiting
    text: to enforce per-ip rate limits
  - purpose: error monitoring
    text: sentry only gets error reports, including uncaught errors and unhandled promise rejections
  - purpose: anonymous analytics
    text: umami records anonymous, aggregated page views and events with no cookies, no cross-site tracking, and no personal data
  retention:
  - period: null
    scope: submitted code
    text: the code is never persisted to any database, never written to long-term storage, never logged, and never shared with third parties
  - period: null
    scope: temporary file
    text: is deleted before the api response returns, regardless of whether formatting succeeded or failed
  - period: up to 60 seconds
    scope: ip address counter
    text: holds it in a short-lived in-memory counter for up to 60 seconds
  - period: null
    scope: rate-limit log lines
    text: these log lines roll off with vercel's default log retention
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: codefmt does not sell or share anyone's personal data, for any visitor
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: codefmt
provenance_date: '2026-11-09'
provider_name: codefmt
provider_slug: codefmt-dev
slug: codefmt-dev-privacy-policy
source_date: '2026-11-09'
source_filename: codefmt-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://codefmt.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: codefmt\naid: codefmt-dev\nurl: https://codefmt.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: 'requests to the api and agent endpoints (format, mcp, a2a, ask, llms.txt) are counted in aggregate through\n    umami: endpoint, platform, and outcome only'\n- category: device\n  text: the /api/format endpoint reads the ip address that vercel attaches to each request ( x-real-ip ) and holds\n    it in a short-lived in-memory counter for up to 60 seconds\n- category: other\n  text: submitted code and queries are processed in memory\
  \ and never stored or sent to analytics\npurposes:\n- purpose: format code\n  text: when you format code using the browser extension, your code is sent over https to codefmt.dev/api/format\n    for processing\n- purpose: rate limiting\n  text: to enforce per-ip rate limits\n- purpose: error monitoring\n  text: sentry only gets error reports, including uncaught errors and unhandled promise rejections\n- purpose: anonymous analytics\n  text: umami records anonymous, aggregated page views and events with no cookies, no cross-site tracking, and no\n    personal data\nretention:\n- scope: submitted code\n  period: null\n  text: the code is never persisted to any database, never written to long-term storage, never logged, and never\n    shared with third parties\n- scope: temporary file\n  period: null\n  text: is deleted before the api response returns, regardless of whether formatting succeeded or failed\n- scope: ip address counter\n  period: up to 60 seconds\n  text: holds it in a short-lived\
  \ in-memory counter for up to 60 seconds\n- scope: rate-limit log lines\n  period: null\n  text: these log lines roll off with vercel's default log retention\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: codefmt does not sell or share anyone's personal data, for any visitor\n"
source_yaml_url: https://artifacts.apis.io/codefmt-dev/privacy/codefmt-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- sale_or_sharing
summary_line: 12 quoted statements, read from codefmt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Code Formatting
- Linting
- HubL
- HubSpot
- Zapier
- n8n
- Automation
- Developer Tools
- MCP
---
