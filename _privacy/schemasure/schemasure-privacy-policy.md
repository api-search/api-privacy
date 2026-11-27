---
api_specs:
- filename: schemasure-health-api-openapi.yml
  format: yaml
  label: SchemaSure Health API
  slug: schemasure-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/schemasure/openapi/schemasure-health-api-openapi.yml
- filename: schemasure-image-extraction-x402-v2-api-openapi.yml
  format: yaml
  label: SchemaSure Image extraction · x402 V2 API
  slug: schemasure-image-extraction-x402-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/schemasure/openapi/schemasure-image-extraction-x402-v2-api-openapi.yml
- filename: schemasure-legacy-v1-evaluation-api-api-openapi.yml
  format: yaml
  label: SchemaSure Legacy V1 evaluation API
  slug: schemasure-legacy-v1-evaluation-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/schemasure/openapi/schemasure-legacy-v1-evaluation-api-api-openapi.yml
- filename: schemasure-primary-x402-v2-api-api-openapi.yml
  format: yaml
  label: SchemaSure Primary x402 V2 API
  slug: schemasure-primary-x402-v2-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/schemasure/openapi/schemasure-primary-x402-v2-api-api-openapi.yml
- filename: schemasure-business-time-api-openapi.yml
  format: yaml
  label: SchemaSure Business Time API
  slug: schemasure-business-time-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/schemasure/openapi/schemasure-business-time-api-openapi.yml
- filename: schemasure-chain-api-openapi.yml
  format: yaml
  label: SchemaSure Chain API
  slug: schemasure-chain-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/schemasure/openapi/schemasure-chain-api-openapi.yml
- filename: schemasure-guard-api-openapi.yml
  format: yaml
  label: SchemaSure Guard API
  slug: schemasure-guard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/schemasure/openapi/schemasure-guard-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: behavioral
    text: Text, HTML, image bytes, JSON Schemas, and extracted output are processed transiently to fulfill the request
  - category: financial
    text: payment state, and payer address
  - category: device
    text: timestamps, request identifiers, API version, success/error code, latency
  deletion:
    route: null
    text: Because there is no stored request-content copy, there is nothing to delete after completion.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Fulfill request
    text: Text, HTML, image bytes, JSON Schemas, and extracted output are processed transiently to fulfill the request and are not persisted by SchemaSure in production.
  - purpose: Perform extraction
    text: Request content is transmitted over TLS to Google AI API solely to perform extraction.
  - purpose: Reliability and commercial events
    text: We keep non-content reliability and commercial events for up to 365 days
  retention:
  - period: null
    scope: Request content
    text: Raw request content is not logged, sampled, or retained in production.
  - period: 365 days
    scope: Operational metrics
    text: We keep non-content reliability and commercial events for up to 365 days
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SchemaSure
provenance_date: '2026-11-10'
provider_name: SchemaSure
provider_slug: schemasure
slug: schemasure-privacy-policy
source_date: '2026-11-10'
source_filename: schemasure-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://schemasure.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SchemaSure\naid: schemasure\nurl: https://schemasure.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: Text, HTML, image bytes, JSON Schemas, and extracted output are processed transiently to fulfill the request\n- category: financial\n  text: payment state, and payer address\n- category: device\n  text: timestamps, request identifiers, API version, success/error code, latency\npurposes:\n- purpose: Fulfill request\n  text: Text, HTML, image bytes, JSON Schemas, and extracted output are processed transiently to fulfill the request\n\
  \    and are not persisted by SchemaSure in production.\n- purpose: Perform extraction\n  text: Request content is transmitted over TLS to Google AI API solely to perform extraction.\n- purpose: Reliability and commercial events\n  text: We keep non-content reliability and commercial events for up to 365 days\nretention:\n- scope: Request content\n  period: null\n  text: Raw request content is not logged, sampled, or retained in production.\n- scope: Operational metrics\n  period: 365 days\n  text: We keep non-content reliability and commercial events for up to 365 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: Because there is no stored request-content copy, there is nothing to delete after completion.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/schemasure/privacy/schemasure-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 10 quoted statements, read from SchemaSure's own page on 2026-11-10.
synthetic: false
tags:
- Structured Data Extraction
- text-to-JSON
- JSON Schema
- Document Parsing
- Data Cleaning
- LLM Tooling
- AI Agents
- x402-micropayments
- Agent-Native
- A2A
- MCP
---
