---
api_specs:
- filename: corsproxy-dev-health-api-openapi.yml
  format: yaml
  label: corsproxy-dev Health API
  slug: corsproxy-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corsproxy-dev/openapi/corsproxy-dev-health-api-openapi.yml
- filename: corsproxy-dev-mcp-api-openapi.yml
  format: yaml
  label: corsproxy-dev MCP API
  slug: corsproxy-dev-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corsproxy-dev/openapi/corsproxy-dev-mcp-api-openapi.yml
- filename: corsproxy-dev-proxy-api-openapi.yml
  format: yaml
  label: corsproxy-dev Proxy API
  slug: corsproxy-dev-proxy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corsproxy-dev/openapi/corsproxy-dev-proxy-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address
  - category: location
    text: Approximate country and the Cloudflare data centre that handled the request
  - category: device
    text: User-Agent header
  - category: behavioral
    text: Daily request counts per user
  deletion:
    route: Account deletion in dashboard
    text: You can delete your account and all associated data
  dpa:
    available: true
    text: Our use of Cloudflare is governed by Cloudflare's Data Processing Addendum (DPA)
    url: https://www.cloudflare.com/trust-hub/
  purposes:
  - purpose: Fraud and security
    text: To detect and prevent fraud
  - purpose: Service operation
    text: To authenticate users and validate API keys
  - purpose: Analytics
    text: To understand usage patterns
  residency:
  - region: Global edge network
    text: Your data may be processed and replicated across Cloudflare's points of presence worldwide, including data centres inside and outside the European Economic Area
  retention:
  - period: 30 days
    scope: Request logs
    text: Request logs are retained for 30 days
  - period: 30 days
    scope: Deleted account data
    text: Your account record, API key records, request logs, and usage totals are kept for 30 days so we can investigate abuse, then permanently deleted
  - period: 30 days after account deletion
    scope: Usage analytics
    text: They are deleted 30 days after account deletion
  rights:
  - right: Access
    text: You can access your account data through the dashboard
  - right: Portability
    text: You can request a copy of your data in machine-readable format
  - right: Erasure
    text: Request erasure of your data
  - right: Opt out of analytics
    text: You can opt out of analytics tracking (except security-critical tracking)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Cloudflare''s sub-processor list and DPA: https://www.cloudflare.com/trust-hub/'
    url: https://www.cloudflare.com/trust-hub/
  transfers:
  - mechanism: SCC
    text: Cloudflare provides EU Standard Contractual Clauses (SCCs) and a UK International Data Transfer Addendum as part of its Data Processing Addendum, which we have accepted.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: corsproxy-dev
provenance_date: '2026-11-09'
provider_name: corsproxy-dev
provider_slug: corsproxy-dev
slug: corsproxy-dev-privacy-policy
source_date: '2026-11-09'
source_filename: corsproxy-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://corsproxy.dev/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: corsproxy-dev\naid: corsproxy-dev\nurl: https://corsproxy.dev/legal/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address\n- category: location\n  text: Approximate country and the Cloudflare data centre that handled the request\n- category: device\n  text: User-Agent header\n- category: behavioral\n  text: Daily request counts per user\npurposes:\n- purpose: Fraud and security\n  text: To detect and prevent fraud\n- purpose: Service operation\n  text: To authenticate users and validate API keys\n- purpose: Analytics\n\
  \  text: To understand usage patterns\nretention:\n- scope: Request logs\n  period: 30 days\n  text: Request logs are retained for 30 days\n- scope: Deleted account data\n  period: 30 days\n  text: Your account record, API key records, request logs, and usage totals are kept for 30 days so we can investigate\n    abuse, then permanently deleted\n- scope: Usage analytics\n  period: 30 days after account deletion\n  text: They are deleted 30 days after account deletion\nresidency:\n- region: Global edge network\n  text: Your data may be processed and replicated across Cloudflare's points of presence worldwide, including data\n    centres inside and outside the European Economic Area\ntransfers:\n- mechanism: SCC\n  text: Cloudflare provides EU Standard Contractual Clauses (SCCs) and a UK International Data Transfer Addendum\n    as part of its Data Processing Addendum, which we have accepted.\nsubprocessors:\n  url: https://www.cloudflare.com/trust-hub/\n  text: 'Cloudflare''s sub-processor\
  \ list and DPA: https://www.cloudflare.com/trust-hub/'\ndpa:\n  available: true\n  url: https://www.cloudflare.com/trust-hub/\n  text: Our use of Cloudflare is governed by Cloudflare's Data Processing Addendum (DPA)\ndeletion:\n  route: Account deletion in dashboard\n  text: You can delete your account and all associated data\nrights:\n- right: Access\n  text: You can access your account data through the dashboard\n- right: Portability\n  text: You can request a copy of your data in machine-readable format\n- right: Erasure\n  text: Request erasure of your data\n- right: Opt out of analytics\n  text: You can opt out of analytics tracking (except security-critical tracking)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/corsproxy-dev/privacy/corsproxy-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 19 quoted statements, read from corsproxy-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- CORS
- Proxy
- Developer Tools
- Open Source
---
