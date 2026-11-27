---
api_specs:
- filename: hiveagentiq-com-bank-api-openapi.yml
  format: yaml
  label: Hive Agent IQ Bank API
  slug: hiveagentiq-com-bank-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hiveagentiq-com/openapi/hiveagentiq-com-bank-api-openapi.yml
- filename: hiveagentiq-com-comply-api-openapi.yml
  format: yaml
  label: Hive Agent IQ Comply API
  slug: hiveagentiq-com-comply-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hiveagentiq-com/openapi/hiveagentiq-com-comply-api-openapi.yml
- filename: hiveagentiq-com-credential-api-openapi.yml
  format: yaml
  label: Hive Agent IQ Credential API
  slug: hiveagentiq-com-credential-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hiveagentiq-com/openapi/hiveagentiq-com-credential-api-openapi.yml
- filename: hiveagentiq-com-gate-api-openapi.yml
  format: yaml
  label: Hive Agent IQ Gate API
  slug: hiveagentiq-com-gate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hiveagentiq-com/openapi/hiveagentiq-com-gate-api-openapi.yml
- filename: hiveagentiq-com-identity-api-openapi.yml
  format: yaml
  label: Hive Agent IQ Identity API
  slug: hiveagentiq-com-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hiveagentiq-com/openapi/hiveagentiq-com-identity-api-openapi.yml
- filename: hiveagentiq-com-law-api-openapi.yml
  format: yaml
  label: Hive Agent IQ Law API
  slug: hiveagentiq-com-law-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hiveagentiq-com/openapi/hiveagentiq-com-law-api-openapi.yml
- filename: hiveagentiq-com-trust-api-openapi.yml
  format: yaml
  label: Hive Agent IQ Trust API
  slug: hiveagentiq-com-trust-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hiveagentiq-com/openapi/hiveagentiq-com-trust-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: Names, email addresses and messages may be supplied through account or contact workflows.
  - category: financial
    text: Receipt fields may include payer/payee identifiers, amounts and transaction hashes.
  - category: location
    text: Legacy receipt-service telemetry also collects IP and location metadata and writes to Supabase.
  - category: device
    text: user agent, time zone, a random per-view ID
  - category: behavioral
    text: whether the visitor scrolled, clicked or typed.
  deletion:
    route: null
    text: A signed deletion statement does not prove removal of all copies.
  dpa:
    available: null
    text: Processor agreements, authorized data classes, notice terms and onward transfers require verification.
    url: null
  purposes:
  - purpose: Receipts and routing
    text: 'Receipts and routing: Signed fields can include hashes, timestamps, model or agent identifiers, transaction details and customer-supplied metadata.'
  - purpose: Telemetry and analytics
    text: Applicable basis and any consent requirement need assessment; this page does not verify a consent-gated implementation
  residency:
  - region: United States (Oregon)
    text: The reviewed Render compute is in Oregon, United States; the static site is globally distributed.
  retention:
  - period: null
    scope: Receipts
    text: The receipt service uses process memory; Carnac uses memory with a conditional Supabase mirror.
  - period: null
    scope: Account data
    text: Creation, closure and inactivity events, purpose-specific durations and legal holds require business/legal approval.
  rights:
  - right: Access
    text: 'Right of access: you can get a copy of your personal data.'
  - right: Erasure
    text: 'Right to erasure: you can ask us to delete your data when we have no legal basis to keep processing it.'
  - right: Opt out of sale
    text: Right to opt out of sale of personal information.
  role:
    text: controller/processor roles must be verified against charter and agreement records.
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: (Hive does not sell personal information.)
  subprocessors:
    text: It is not a complete, legally approved subprocessor register.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Hive Agent IQ
provenance_date: '2026-11-09'
provider_name: Hive Agent IQ
provider_slug: hiveagentiq-com
slug: hiveagentiq-com-privacy-policy
source_date: '2026-11-09'
source_filename: hiveagentiq-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://thehiveryiq.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Hive Agent IQ\naid: hiveagentiq-com\nurl: https://thehiveryiq.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: controller/processor roles must be verified against charter and agreement records.\ndata_categories:\n- category: contact\n  text: Names, email addresses and messages may be supplied through account or contact workflows.\n- category: financial\n  text: Receipt fields may include payer/payee identifiers, amounts and transaction hashes.\n- category: location\n  text: Legacy receipt-service telemetry also collects IP and location metadata and writes to Supabase.\n- category:\
  \ device\n  text: user agent, time zone, a random per-view ID\n- category: behavioral\n  text: whether the visitor scrolled, clicked or typed.\npurposes:\n- purpose: Receipts and routing\n  text: 'Receipts and routing: Signed fields can include hashes, timestamps, model or agent identifiers, transaction\n    details and customer-supplied metadata.'\n- purpose: Telemetry and analytics\n  text: Applicable basis and any consent requirement need assessment; this page does not verify a consent-gated\n    implementation\nretention:\n- scope: Receipts\n  period: null\n  text: The receipt service uses process memory; Carnac uses memory with a conditional Supabase mirror.\n- scope: Account data\n  period: null\n  text: Creation, closure and inactivity events, purpose-specific durations and legal holds require business/legal\n    approval.\nresidency:\n- region: United States (Oregon)\n  text: The reviewed Render compute is in Oregon, United States; the static site is globally distributed.\ntransfers:\
  \ []\nsubprocessors:\n  url: null\n  text: It is not a complete, legally approved subprocessor register.\ndpa:\n  available: null\n  url: null\n  text: Processor agreements, authorized data classes, notice terms and onward transfers require verification.\ndeletion:\n  route: null\n  text: A signed deletion statement does not prove removal of all copies.\nrights:\n- right: Access\n  text: 'Right of access: you can get a copy of your personal data.'\n- right: Erasure\n  text: 'Right to erasure: you can ask us to delete your data when we have no legal basis to keep processing it.'\n- right: Opt out of sale\n  text: Right to opt out of sale of personal information.\nsale_or_sharing:\n  stance: unstated\n  text: (Hive does not sell personal information.)\n"
source_yaml_url: https://artifacts.apis.io/hiveagentiq-com/privacy/hiveagentiq-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
summary_line: 17 quoted statements, read from Hive Agent IQ's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- Agentic Commerce
- A2A
- MCP
- x402
- Decentralized Identity
- Verifiable Credentials
- Trust Scoring
- Stablecoins
- Insurance
- Compliance
- Agent-Native
- United States
---
