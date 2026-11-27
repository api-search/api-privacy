---
api_specs:
- filename: synlake-ai-auth-api-openapi.yml
  format: yaml
  label: synlake-ai Auth API
  slug: synlake-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synlake-ai/openapi/synlake-ai-auth-api-openapi.yml
- filename: synlake-ai-billing-api-openapi.yml
  format: yaml
  label: synlake-ai Billing API
  slug: synlake-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synlake-ai/openapi/synlake-ai-billing-api-openapi.yml
- filename: synlake-ai-catalog-api-openapi.yml
  format: yaml
  label: synlake-ai Catalog API
  slug: synlake-ai-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synlake-ai/openapi/synlake-ai-catalog-api-openapi.yml
- filename: synlake-ai-execution-api-openapi.yml
  format: yaml
  label: synlake-ai Execution API
  slug: synlake-ai-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synlake-ai/openapi/synlake-ai-execution-api-openapi.yml
- filename: synlake-ai-infrastructure-api-openapi.yml
  format: yaml
  label: synlake-ai Infrastructure API
  slug: synlake-ai-infrastructure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synlake-ai/openapi/synlake-ai-infrastructure-api-openapi.yml
- filename: synlake-ai-system-api-openapi.yml
  format: yaml
  label: synlake-ai System API
  slug: synlake-ai-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/synlake-ai/openapi/synlake-ai-system-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: contact
    text: When you register for an API key, we collect your email address.
  - category: behavioral
    text: When you use the Synlake API, we log request metadata (endpoint, timestamp, response time, provider queried) for billing and audit purposes.
  - category: financial
    text: Stripe collects and processes your payment information under their own privacy policy.
  deletion:
    route: email hello@synlake.ai
    text: You may request deletion of your account and associated data at any time by emailing hello@synlake.ai . We will process deletion requests within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: API key delivery and service updates
    text: We use your email to deliver your API key and communicate service updates.
  - purpose: billing, rate limiting, abuse prevention, service improvement
    text: Request logs are used for billing, rate limiting, abuse prevention, and service improvement.
  retention:
  - period: 90 days
    scope: request logs
    text: We retain request logs for 90 days for billing purposes.
  rights:
  - right: deletion
    text: You may request deletion of your account and associated data at any time by emailing hello@synlake.ai .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: synlake-ai
provenance_date: '2026-11-10'
provider_name: synlake-ai
provider_slug: synlake-ai
slug: synlake-ai-privacy-policy
source_date: '2026-11-10'
source_filename: synlake-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://synlake.ai/legal/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: synlake-ai\naid: synlake-ai\nurl: https://synlake.ai/legal/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: When you register for an API key, we collect your email address.\n- category: behavioral\n  text: When you use the Synlake API, we log request metadata (endpoint, timestamp, response time, provider queried)\n    for billing and audit purposes.\n- category: financial\n  text: Stripe collects and processes your payment information under their own privacy policy.\npurposes:\n- purpose: API key delivery and service updates\n \
  \ text: We use your email to deliver your API key and communicate service updates.\n- purpose: billing, rate limiting, abuse prevention, service improvement\n  text: Request logs are used for billing, rate limiting, abuse prevention, and service improvement.\nretention:\n- scope: request logs\n  period: 90 days\n  text: We retain request logs for 90 days for billing purposes.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@synlake.ai\n  text: You may request deletion of your account and associated data at any time by emailing hello@synlake.ai .\n    We will process deletion requests within 30 days.\nrights:\n- right: deletion\n  text: You may request deletion of your account and associated data at any time by emailing hello@synlake.ai .\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/synlake-ai/privacy/synlake-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 9 quoted statements, read from synlake-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Infrastructure
- AI Agents
- Cloud
- Terraform
---
