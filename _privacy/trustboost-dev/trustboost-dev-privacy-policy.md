---
api_specs:
- filename: trustboost-dev-budget-api-openapi.yml
  format: yaml
  label: TrustBoost PII Sanitizer Budget API
  slug: trustboost-dev-budget-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustboost-dev/openapi/trustboost-dev-budget-api-openapi.yml
- filename: trustboost-dev-health-api-openapi.yml
  format: yaml
  label: TrustBoost PII Sanitizer Health API
  slug: trustboost-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustboost-dev/openapi/trustboost-dev-health-api-openapi.yml
- filename: trustboost-dev-mcp-api-openapi.yml
  format: yaml
  label: TrustBoost PII Sanitizer MCP API
  slug: trustboost-dev-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustboost-dev/openapi/trustboost-dev-mcp-api-openapi.yml
- filename: trustboost-dev-message-api-openapi.yml
  format: yaml
  label: TrustBoost PII Sanitizer Message API
  slug: trustboost-dev-message-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustboost-dev/openapi/trustboost-dev-message-api-openapi.yml
- filename: trustboost-dev-sanitize-api-openapi.yml
  format: yaml
  label: TrustBoost PII Sanitizer Sanitize API
  slug: trustboost-dev-sanitize-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustboost-dev/openapi/trustboost-dev-sanitize-api-openapi.yml
- filename: trustboost-dev-score-api-openapi.yml
  format: yaml
  label: TrustBoost PII Sanitizer Score API
  slug: trustboost-dev-score-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustboost-dev/openapi/trustboost-dev-score-api-openapi.yml
- filename: trustboost-dev-verify-api-openapi.yml
  format: yaml
  label: TrustBoost PII Sanitizer Verify API
  slug: trustboost-dev-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustboost-dev/openapi/trustboost-dev-verify-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: wallet_address — your Solana wallet address (optional, used for per-wallet TRIAL quota tracking)
  - category: other
    text: text — the content you want sanitized
  - category: other
    text: tx_hash — a transaction identifier (or "TRIAL" for testing)
  deletion:
    route: email
    text: 'For questions or to request data deletion, write to: teodorofodocrispin@gmail.com'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: PII detection and redaction
    text: PII detection and redaction before LLM processing
  residency:
  - region: United States
    text: Render (AWS us-east-1, United States)
  retention:
  - period: indefinitely
    scope: audit log entries
    text: 'Audit log entries (sanitized output + metadata): retained indefinitely for compliance traceability'
  - period: 90 days
    scope: audit metadata
    text: Retention 90 days for audit metadata. Deleted on request.
  - period: null
    scope: wallet_address
    text: 'wallet_address : stored only for TRIAL quota tracking'
  - period: null
    scope: raw input text
    text: 'Raw input text : never stored at any point'
  rights:
  - right: data subject requests
    text: 'Response time: 30 days (GDPR Art. 12)'
  role:
    text: TrustBoost acts as a Data Processor under GDPR Article 28 and the EU AI Act (Regulation EU 2024/1689).
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: Your raw text is never sold, shared, or analyzed outside the processing flow
  subprocessors:
    text: OpenAI (GPT-4o-mini) PII detection engine United States
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TrustBoost PII Sanitizer
provenance_date: '2026-11-10'
provider_name: TrustBoost PII Sanitizer
provider_slug: trustboost-dev
slug: trustboost-dev-privacy-policy
source_date: '2026-11-10'
source_filename: trustboost-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://github.com/teodorofodocrispin-cmyk/TrustBoost-PII-Sanitizer/blob/main/PRIVACY.md
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TrustBoost PII Sanitizer\naid: trustboost-dev\nurl: https://github.com/teodorofodocrispin-cmyk/TrustBoost-PII-Sanitizer/blob/main/PRIVACY.md\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: TrustBoost acts as a Data Processor under GDPR Article 28 and the EU AI Act (Regulation EU 2024/1689).\ndata_categories:\n- category: identifying\n  text: wallet_address — your Solana wallet address (optional, used for per-wallet TRIAL quota tracking)\n- category: other\n  text: text — the content you want sanitized\n- category: other\n  text: tx_hash — a transaction identifier (or \"TRIAL\" for testing)\n\
  purposes:\n- purpose: PII detection and redaction\n  text: PII detection and redaction before LLM processing\nretention:\n- scope: audit log entries\n  period: indefinitely\n  text: 'Audit log entries (sanitized output + metadata): retained indefinitely for compliance traceability'\n- scope: audit metadata\n  period: 90 days\n  text: Retention 90 days for audit metadata. Deleted on request.\n- scope: wallet_address\n  period: null\n  text: 'wallet_address : stored only for TRIAL quota tracking'\n- scope: raw input text\n  period: null\n  text: 'Raw input text : never stored at any point'\nresidency:\n- region: United States\n  text: Render (AWS us-east-1, United States)\ntransfers: []\nsubprocessors:\n  url: null\n  text: OpenAI (GPT-4o-mini) PII detection engine United States\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email\n  text: 'For questions or to request data deletion, write to: teodorofodocrispin@gmail.com'\nrights:\n- right: data subject requests\n\
  \  text: 'Response time: 30 days (GDPR Art. 12)'\nsale_or_sharing:\n  stance: prohibited\n  text: Your raw text is never sold, shared, or analyzed outside the processing flow\n"
source_yaml_url: https://artifacts.apis.io/trustboost-dev/privacy/trustboost-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from TrustBoost PII Sanitizer's own page on 2026-11-10.
synthetic: false
tags:
- Privacy
- PII Redaction
- Data Protection
- LLM Security
- AI Safety
- Agents
- A2A
- MCP
- x402
- Agentic Commerce
- Solana
- Compliance
- Agent-Native
---
