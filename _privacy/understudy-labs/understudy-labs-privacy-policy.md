---
api_specs:
- filename: understudy-labs-capabilities-api-openapi.yml
  format: yaml
  label: Understudy Labs Capabilities API
  slug: understudy-labs-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/understudy-labs/openapi/understudy-labs-capabilities-api-openapi.yml
- filename: understudy-labs-conversations-api-openapi.yml
  format: yaml
  label: Understudy Labs Conversations API
  slug: understudy-labs-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/understudy-labs/openapi/understudy-labs-conversations-api-openapi.yml
- filename: understudy-labs-downloads-api-openapi.yml
  format: yaml
  label: Understudy Labs Downloads API
  slug: understudy-labs-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/understudy-labs/openapi/understudy-labs-downloads-api-openapi.yml
- filename: understudy-labs-feedback-api-openapi.yml
  format: yaml
  label: Understudy Labs Feedback API
  slug: understudy-labs-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/understudy-labs/openapi/understudy-labs-feedback-api-openapi.yml
- filename: understudy-labs-metrics-api-openapi.yml
  format: yaml
  label: Understudy Labs Metrics API
  slug: understudy-labs-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/understudy-labs/openapi/understudy-labs-metrics-api-openapi.yml
- filename: understudy-labs-models-api-openapi.yml
  format: yaml
  label: Understudy Labs Models API
  slug: understudy-labs-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/understudy-labs/openapi/understudy-labs-models-api-openapi.yml
- filename: understudy-labs-residency-api-openapi.yml
  format: yaml
  label: Understudy Labs Residency API
  slug: understudy-labs-residency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/understudy-labs/openapi/understudy-labs-residency-api-openapi.yml
- filename: understudy-labs-runs-api-openapi.yml
  format: yaml
  label: Understudy Labs Runs API
  slug: understudy-labs-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/understudy-labs/openapi/understudy-labs-runs-api-openapi.yml
- filename: understudy-labs-status-api-openapi.yml
  format: yaml
  label: Understudy Labs Status API
  slug: understudy-labs-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/understudy-labs/openapi/understudy-labs-status-api-openapi.yml
- filename: understudy-labs-supervision-api-openapi.yml
  format: yaml
  label: Understudy Labs Supervision API
  slug: understudy-labs-supervision-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/understudy-labs/openapi/understudy-labs-supervision-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Website and contact forms: name, email address, company, message content, and basic request metadata such as IP address, user agent, and timestamp.'
  - category: identifying
    text: if you sign in with Google, we receive the name, email address, and account identifiers Google provides through WorkOS.
  - category: behavioral
    text: 'Gateway: per-request metadata only, such as account, provider, model, timing, status, token counts where available, routing decision, and error metadata.'
  deletion:
    route: email support@understudylabs.com
    text: You can ask us to delete your account data or exported materials you have shared with us by emailing support@understudylabs.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate the service
    text: We use account and request metadata to operate the service, secure accounts, debug reliability issues, enforce usage limits, route traffic, communicate with users, and satisfy legal obligations.
  - purpose: no training on customer content for other customers
    text: We do not use customer prompts, completions, traces, evals, labels, datasets, or model artifacts to train models for other customers.
  - purpose: analytics and sales follow-up
    text: We use analytics and CRM tools to understand interest, improve the product, and prioritize sales follow-up.
  retention:
  - period: null
    scope: account records
    text: We keep account records while your account is active and for a reasonable period afterward for security, billing, audit, and legal reasons.
  - period: null
    scope: gateway metadata
    text: Gateway metadata is retained only as long as needed to operate, debug, secure, and improve the service.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: We use a small number of subprocessors to run the service. WorkOS handles authentication. Cloudflare handles edge networking and may host gateway infrastructure, including Workers and planned KV or D1 storage.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Understudy Labs
provenance_date: '2026-11-10'
provider_name: Understudy Labs
provider_slug: understudy-labs
slug: understudy-labs-privacy-policy
source_date: '2026-11-10'
source_filename: understudy-labs-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://understudylabs.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Understudy Labs\naid: understudy-labs\nurl: https://understudylabs.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Website and contact forms: name, email address, company, message content, and basic request metadata such\n    as IP address, user agent, and timestamp.'\n- category: identifying\n  text: if you sign in with Google, we receive the name, email address, and account identifiers Google provides\n    through WorkOS.\n- category: behavioral\n  text: 'Gateway: per-request metadata only, such as account, provider, model, timing,\
  \ status, token counts where\n    available, routing decision, and error metadata.'\npurposes:\n- purpose: operate the service\n  text: We use account and request metadata to operate the service, secure accounts, debug reliability issues, enforce\n    usage limits, route traffic, communicate with users, and satisfy legal obligations.\n- purpose: no training on customer content for other customers\n  text: We do not use customer prompts, completions, traces, evals, labels, datasets, or model artifacts to train\n    models for other customers.\n- purpose: analytics and sales follow-up\n  text: We use analytics and CRM tools to understand interest, improve the product, and prioritize sales follow-up.\nretention:\n- scope: account records\n  period: null\n  text: We keep account records while your account is active and for a reasonable period afterward for security,\n    billing, audit, and legal reasons.\n- scope: gateway metadata\n  period: null\n  text: Gateway metadata is retained only\
  \ as long as needed to operate, debug, secure, and improve the service.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use a small number of subprocessors to run the service. WorkOS handles authentication. Cloudflare handles\n    edge networking and may host gateway infrastructure, including Workers and planned KV or D1 storage.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@understudylabs.com\n  text: You can ask us to delete your account data or exported materials you have shared with us by emailing support@understudylabs.com.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/understudy-labs/privacy/understudy-labs-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
summary_line: 10 quoted statements, read from Understudy Labs's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- LLM Gateway
- Machine Learning
- Open Source
- Model Routing
- Evaluation
- Fine-Tuning
- AI Infrastructure
- Developer Tools
---
