---
api_specs:
- filename: hunta-ai-admin-api-openapi.yml
  format: yaml
  label: hunta-ai Admin API
  slug: hunta-ai-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-admin-api-openapi.yml
- filename: hunta-ai-candidates-api-openapi.yml
  format: yaml
  label: hunta-ai Candidates API
  slug: hunta-ai-candidates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-candidates-api-openapi.yml
- filename: hunta-ai-errata-api-openapi.yml
  format: yaml
  label: hunta-ai Errata API
  slug: hunta-ai-errata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-errata-api-openapi.yml
- filename: hunta-ai-export-api-openapi.yml
  format: yaml
  label: hunta-ai Export API
  slug: hunta-ai-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-export-api-openapi.yml
- filename: hunta-ai-facts-api-openapi.yml
  format: yaml
  label: hunta-ai Facts API
  slug: hunta-ai-facts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-facts-api-openapi.yml
- filename: hunta-ai-memories-api-openapi.yml
  format: yaml
  label: hunta-ai Memories API
  slug: hunta-ai-memories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-memories-api-openapi.yml
- filename: hunta-ai-metrics-api-openapi.yml
  format: yaml
  label: hunta-ai Metrics API
  slug: hunta-ai-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-metrics-api-openapi.yml
- filename: hunta-ai-reckon-api-openapi.yml
  format: yaml
  label: hunta-ai Reckon API
  slug: hunta-ai-reckon-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-reckon-api-openapi.yml
- filename: hunta-ai-reconcile-api-openapi.yml
  format: yaml
  label: hunta-ai Reconcile API
  slug: hunta-ai-reconcile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-reconcile-api-openapi.yml
- filename: hunta-ai-whoami-api-openapi.yml
  format: yaml
  label: hunta-ai Whoami API
  slug: hunta-ai-whoami-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hunta-ai/openapi/hunta-ai-whoami-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data : your name and email from the identity provider you choose (GitHub or Google).'
  - category: financial
    text: 'Payment data : handled by Stripe; we never see or store card numbers.'
  - category: other
    text: 'Usage metering : token counts per operation (deterministic, so you can verify your bill), plan state, and operational logs.'
  - category: other
    text: 'Memory content : what you or your agents store in Hunta Gather.'
  deletion:
    route: API/console deletion or account deletion
    text: 'fact-level and memory-level deletion via API/console: supersede, invalidate, forget'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide storage, retrieval, curation and attestation
    text: processed solely to provide storage, retrieval, curation and attestation.
  residency:
  - region: UK/EU
    text: Data is processed in the UK/EU where practicable
  retention:
  - period: until you delete it
    scope: memory content
    text: 'Memory content persists until you delete it (fact-level and memory-level deletion via API/console: supersede, invalidate, forget)'
  - period: within 30 days
    scope: account deletion
    text: tenant data removed within 30 days
  - period: as the law demands
    scope: invoices and legally required records
    text: Invoices and legally required records are kept as the law demands.
  rights:
  - right: access, correct, export, erase
    text: Under UK/EU GDPR you can access, correct, export, or erase your personal data
  - right: complain to regulator
    text: and complain to the ICO or your local authority.
  role:
    text: 'Controller: Hunta (UK)'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: never sold.
  subprocessors:
    text: Stripe (payments) · Cloudflare (DNS/site hosting) · Neon (encrypted database) · Contabo (compute hosting) · Lago, self-hosted (usage metering) · emailit (transactional email) · GitHub / Google (sign-in only).
    url: null
  transfers:
  - mechanism: SCC
    text: where a subprocessor processes elsewhere, standard contractual clauses apply.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: hunta-ai
provenance_date: '2026-11-09'
provider_name: hunta-ai
provider_slug: hunta-ai
slug: hunta-ai-privacy-policy
source_date: '2026-11-09'
source_filename: hunta-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hunta.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: hunta-ai\naid: hunta-ai\nurl: https://hunta.ai/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Controller: Hunta (UK)'\ndata_categories:\n- category: identifying\n  text: 'Account data : your name and email from the identity provider you choose (GitHub or Google).'\n- category: financial\n  text: 'Payment data : handled by Stripe; we never see or store card numbers.'\n- category: other\n  text: 'Usage metering : token counts per operation (deterministic, so you can verify your bill), plan state, and\n    operational logs.'\n- category: other\n  text: 'Memory content : what you\
  \ or your agents store in Hunta Gather.'\npurposes:\n- purpose: provide storage, retrieval, curation and attestation\n  text: processed solely to provide storage, retrieval, curation and attestation.\nretention:\n- scope: memory content\n  period: until you delete it\n  text: 'Memory content persists until you delete it (fact-level and memory-level deletion via API/console: supersede,\n    invalidate, forget)'\n- scope: account deletion\n  period: within 30 days\n  text: tenant data removed within 30 days\n- scope: invoices and legally required records\n  period: as the law demands\n  text: Invoices and legally required records are kept as the law demands.\nresidency:\n- region: UK/EU\n  text: Data is processed in the UK/EU where practicable\ntransfers:\n- mechanism: SCC\n  text: where a subprocessor processes elsewhere, standard contractual clauses apply.\nsubprocessors:\n  url: null\n  text: Stripe (payments) · Cloudflare (DNS/site hosting) · Neon (encrypted database) · Contabo (compute\
  \ hosting)\n    · Lago, self-hosted (usage metering) · emailit (transactional email) · GitHub / Google (sign-in only).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: API/console deletion or account deletion\n  text: 'fact-level and memory-level deletion via API/console: supersede, invalidate, forget'\nrights:\n- right: access, correct, export, erase\n  text: Under UK/EU GDPR you can access, correct, export, or erase your personal data\n- right: complain to regulator\n  text: and complain to the ICO or your local authority.\nsale_or_sharing:\n  stance: prohibited\n  text: never sold.\n"
source_yaml_url: https://artifacts.apis.io/hunta-ai/privacy/hunta-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from hunta-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Memory
- MCP
- Attestable
---
