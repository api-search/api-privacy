---
api_specs:
- filename: 0latency-ai-admin-api-openapi.yml
  format: yaml
  label: 0latency-ai Admin API
  slug: 0latency-ai-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-admin-api-openapi.yml
- filename: 0latency-ai-api-keys-api-openapi.yml
  format: yaml
  label: 0latency-ai Api Keys API
  slug: 0latency-ai-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-api-keys-api-openapi.yml
- filename: 0latency-ai-auth-api-openapi.yml
  format: yaml
  label: 0latency-ai Auth API
  slug: 0latency-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-auth-api-openapi.yml
- filename: 0latency-ai-billing-api-openapi.yml
  format: yaml
  label: 0latency-ai Billing API
  slug: 0latency-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-billing-api-openapi.yml
- filename: 0latency-ai-criteria-api-openapi.yml
  format: yaml
  label: 0latency-ai Criteria API
  slug: 0latency-ai-criteria-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-criteria-api-openapi.yml
- filename: 0latency-ai-dashboard-api-openapi.yml
  format: yaml
  label: 0latency-ai Dashboard API
  slug: 0latency-ai-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-dashboard-api-openapi.yml
- filename: 0latency-ai-extract-api-openapi.yml
  format: yaml
  label: 0latency-ai Extract API
  slug: 0latency-ai-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-extract-api-openapi.yml
- filename: 0latency-ai-graph-api-openapi.yml
  format: yaml
  label: 0latency-ai Graph API
  slug: 0latency-ai-graph-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-graph-api-openapi.yml
- filename: 0latency-ai-health-api-openapi.yml
  format: yaml
  label: 0latency-ai Health API
  slug: 0latency-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-health-api-openapi.yml
- filename: 0latency-ai-memories-api-openapi.yml
  format: yaml
  label: 0latency-ai Memories API
  slug: 0latency-ai-memories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-memories-api-openapi.yml
- filename: 0latency-ai-org-api-openapi.yml
  format: yaml
  label: 0latency-ai Org API
  slug: 0latency-ai-org-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-org-api-openapi.yml
- filename: 0latency-ai-recall-api-openapi.yml
  format: yaml
  label: 0latency-ai Recall API
  slug: 0latency-ai-recall-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-recall-api-openapi.yml
- filename: 0latency-ai-schemas-api-openapi.yml
  format: yaml
  label: 0latency-ai Schemas API
  slug: 0latency-ai-schemas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-schemas-api-openapi.yml
- filename: 0latency-ai-tenant-info-api-openapi.yml
  format: yaml
  label: 0latency-ai Tenant Info API
  slug: 0latency-ai-tenant-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-tenant-info-api-openapi.yml
- filename: 0latency-ai-usage-api-openapi.yml
  format: yaml
  label: 0latency-ai Usage API
  slug: 0latency-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-usage-api-openapi.yml
- filename: 0latency-ai-webhooks-api-openapi.yml
  format: yaml
  label: 0latency-ai Webhooks API
  slug: 0latency-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0latency-ai/openapi/0latency-ai-webhooks-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Email address, API keys, and authentication credentials'
  - category: behavioral
    text: 'Usage Data: API call logs, query patterns, memory access patterns, and performance metrics'
  - category: device
    text: 'Technical Data: IP addresses, request headers, and system metadata for security and debugging purposes'
  - category: other
    text: 'Memory Data: Content you store via our API, including conversation histories, facts, preferences, and other structured data submitted by your AI agents'
  deletion:
    route: API or dashboard, or delete entire account
    text: 'Delete: Remove individual memories ( DELETE /memories/:id ) or delete your entire account'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: To power the memory API and provide instant context availability for your AI agents
  - purpose: Service improvement
    text: To optimize performance, fix bugs, and develop new features
  - purpose: Security
    text: To detect fraud, prevent abuse, and protect our infrastructure
  - purpose: Support
    text: To respond to your questions and troubleshoot issues
  - purpose: Billing
    text: To process payments and manage your subscription
  residency:
  - region: United States
    text: Your data is stored in the United States.
  retention:
  - period: null
    scope: Memory data
    text: Retained until you delete it via the API or dashboard, or until account termination
  - period: null
    scope: Account data
    text: Retained for the duration of your account plus 30 days after termination
  - period: 90 days
    scope: Usage logs
    text: Retained for 90 days for debugging and security purposes
  - period: 7 years
    scope: Billing records
    text: Retained for 7 years as required by law
  rights:
  - right: Access
    text: 'Access: View all your stored memories via the API ( GET /memories ) or dashboard'
  - right: Export
    text: 'Export: Download your data in JSON format via the API'
  - right: Delete
    text: 'Delete: Remove individual memories ( DELETE /memories/:id ) or delete your entire account'
  - right: Rectification
    text: 'Rectification: Update or correct your account information'
  - right: Portability
    text: 'Portability: Export your data in a machine-readable format'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: 'Service Providers: DigitalOcean (hosting), Stripe (payments) — all bound by strict data protection agreements'
    url: null
  transfers:
  - mechanism: other
    text: We ensure appropriate safeguards are in place for international transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 0latency-ai
provenance_date: '2026-11-09'
provider_name: 0latency-ai
provider_slug: 0latency-ai
slug: 0latency-ai-privacy-policy
source_date: '2026-11-09'
source_filename: 0latency-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://0latency.ai/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 0latency-ai\naid: 0latency-ai\nurl: https://0latency.ai/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Information: Email address, API keys, and authentication credentials'\n- category: behavioral\n  text: 'Usage Data: API call logs, query patterns, memory access patterns, and performance metrics'\n- category: device\n  text: 'Technical Data: IP addresses, request headers, and system metadata for security and debugging purposes'\n- category: other\n  text: 'Memory Data: Content you store via our API, including conversation\
  \ histories, facts, preferences, and other\n    structured data submitted by your AI agents'\npurposes:\n- purpose: Service delivery\n  text: To power the memory API and provide instant context availability for your AI agents\n- purpose: Service improvement\n  text: To optimize performance, fix bugs, and develop new features\n- purpose: Security\n  text: To detect fraud, prevent abuse, and protect our infrastructure\n- purpose: Support\n  text: To respond to your questions and troubleshoot issues\n- purpose: Billing\n  text: To process payments and manage your subscription\nretention:\n- scope: Memory data\n  period: null\n  text: Retained until you delete it via the API or dashboard, or until account termination\n- scope: Account data\n  period: null\n  text: Retained for the duration of your account plus 30 days after termination\n- scope: Usage logs\n  period: 90 days\n  text: Retained for 90 days for debugging and security purposes\n- scope: Billing records\n  period: 7 years\n  text:\
  \ Retained for 7 years as required by law\nresidency:\n- region: United States\n  text: Your data is stored in the United States.\ntransfers:\n- mechanism: other\n  text: We ensure appropriate safeguards are in place for international transfers.\nsubprocessors:\n  url: null\n  text: 'Service Providers: DigitalOcean (hosting), Stripe (payments) — all bound by strict data protection agreements'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: API or dashboard, or delete entire account\n  text: 'Delete: Remove individual memories ( DELETE /memories/:id ) or delete your entire account'\nrights:\n- right: Access\n  text: 'Access: View all your stored memories via the API ( GET /memories ) or dashboard'\n- right: Export\n  text: 'Export: Download your data in JSON format via the API'\n- right: Delete\n  text: 'Delete: Remove individual memories ( DELETE /memories/:id ) or delete your entire account'\n- right: Rectification\n  text: 'Rectification: Update or correct your\
  \ account information'\n- right: Portability\n  text: 'Portability: Export your data in a machine-readable format'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/0latency-ai/privacy/0latency-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from 0latency-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Memory
- Agents
- Platform
---
