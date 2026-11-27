---
api_specs:
- filename: polycode-co-uk-admin-api-openapi.yml
  format: yaml
  label: Polycode Admin API
  slug: polycode-co-uk-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-admin-api-openapi.yml
- filename: polycode-co-uk-budget-api-openapi.yml
  format: yaml
  label: Polycode Budget API
  slug: polycode-co-uk-budget-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-budget-api-openapi.yml
- filename: polycode-co-uk-chat-api-openapi.yml
  format: yaml
  label: Polycode Chat API
  slug: polycode-co-uk-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-chat-api-openapi.yml
- filename: polycode-co-uk-diverts-api-openapi.yml
  format: yaml
  label: Polycode Diverts API
  slug: polycode-co-uk-diverts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-diverts-api-openapi.yml
- filename: polycode-co-uk-flag-api-openapi.yml
  format: yaml
  label: Polycode Flag API
  slug: polycode-co-uk-flag-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-flag-api-openapi.yml
- filename: polycode-co-uk-graph-api-openapi.yml
  format: yaml
  label: Polycode Graph API
  slug: polycode-co-uk-graph-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-graph-api-openapi.yml
- filename: polycode-co-uk-graphs-api-openapi.yml
  format: yaml
  label: Polycode Graphs API
  slug: polycode-co-uk-graphs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-graphs-api-openapi.yml
- filename: polycode-co-uk-hooks-api-openapi.yml
  format: yaml
  label: Polycode Hooks API
  slug: polycode-co-uk-hooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-hooks-api-openapi.yml
- filename: polycode-co-uk-keys-api-openapi.yml
  format: yaml
  label: Polycode Keys API
  slug: polycode-co-uk-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-keys-api-openapi.yml
- filename: polycode-co-uk-me-api-openapi.yml
  format: yaml
  label: Polycode Me API
  slug: polycode-co-uk-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-me-api-openapi.yml
- filename: polycode-co-uk-openapi-json-api-openapi.yml
  format: yaml
  label: Polycode Openapi.json API
  slug: polycode-co-uk-openapi-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-openapi-json-api-openapi.yml
- filename: polycode-co-uk-project-api-openapi.yml
  format: yaml
  label: Polycode Project API
  slug: polycode-co-uk-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-project-api-openapi.yml
- filename: polycode-co-uk-projects-api-openapi.yml
  format: yaml
  label: Polycode Projects API
  slug: polycode-co-uk-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-projects-api-openapi.yml
- filename: polycode-co-uk-sessions-api-openapi.yml
  format: yaml
  label: Polycode Sessions API
  slug: polycode-co-uk-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-sessions-api-openapi.yml
- filename: polycode-co-uk-status-api-openapi.yml
  format: yaml
  label: Polycode Status API
  slug: polycode-co-uk-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-status-api-openapi.yml
- filename: polycode-co-uk-test-api-openapi.yml
  format: yaml
  label: Polycode Test API
  slug: polycode-co-uk-test-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-test-api-openapi.yml
- filename: polycode-co-uk-usage-api-openapi.yml
  format: yaml
  label: Polycode Usage API
  slug: polycode-co-uk-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-usage-api-openapi.yml
- filename: polycode-co-uk-visitor-api-openapi.yml
  format: yaml
  label: Polycode Visitor API
  slug: polycode-co-uk-visitor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/polycode-co-uk/openapi/polycode-co-uk-visitor-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: Visitors are pseudonymous (a browser session UUID and, optionally, a persistent browser visitor UUID)
  - category: contact
    text: Real contact data — email, phone, financial, government-ID — is still blocked at ingest
  - category: behavioral
    text: 'When a visitor''s message is ingested into the shared memory tree, it passes through: Bedrock Guardrail PII policies'
  deletion:
    route: Email operator with session UUID; admin CLI memory-purge
    text: 'Erasure flow for a session: the admin CLI runs memory-purge on the relevant leaf + descendants and writes an audit# row.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Recognise returning contributor
    text: so the graph can recognise a returning contributor
  - purpose: Operator safety and cost controls
    text: Per-session cap carve-out, synth cap carve-out, ingest cap carve-out — protects the daily heartbeat and PII redaction from a hot session.
  retention:
  - period: indefinitely
    scope: Shared memory tree contributions
    text: we keep contributions indefinitely as part of the shared memory tree, but always in summary form once they're past the per-session window
  rights:
  - right: Access, rectification, erasure
    text: UK GDPR rights of access, rectification, and erasure apply.
  role:
    text: the operator is Polycode Limited (UK), reachable at antony@polycode.co.uk
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: No selling of visitor data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Polycode
provenance_date: '2026-11-10'
provider_name: Polycode
provider_slug: polycode-co-uk
slug: polycode-co-uk-privacy-policy
source_date: '2026-11-10'
source_filename: polycode-co-uk-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://gitlab.com/polycode-projects/marginalia/-/blob/main/_developers/ETHICS.md
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Polycode\naid: polycode-co-uk\nurl: https://gitlab.com/polycode-projects/marginalia/-/blob/main/_developers/ETHICS.md\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: the operator is Polycode Limited (UK), reachable at antony@polycode.co.uk\ndata_categories:\n- category: identifying\n  text: Visitors are pseudonymous (a browser session UUID and, optionally, a persistent browser visitor UUID)\n- category: contact\n  text: Real contact data — email, phone, financial, government-ID — is still blocked at ingest\n- category: behavioral\n  text: 'When a visitor''s message is ingested into the shared\
  \ memory tree, it passes through: Bedrock Guardrail\n    PII policies'\npurposes:\n- purpose: Recognise returning contributor\n  text: so the graph can recognise a returning contributor\n- purpose: Operator safety and cost controls\n  text: Per-session cap carve-out, synth cap carve-out, ingest cap carve-out — protects the daily heartbeat and\n    PII redaction from a hot session.\nretention:\n- scope: Shared memory tree contributions\n  period: indefinitely\n  text: we keep contributions indefinitely as part of the shared memory tree, but always in summary form once they're\n    past the per-session window\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email operator with session UUID; admin CLI memory-purge\n  text: 'Erasure flow for a session: the admin CLI runs memory-purge on the relevant leaf + descendants and writes\n    an audit# row.'\nrights:\n- right: Access, rectification, erasure\n\
  \  text: UK GDPR rights of access, rectification, and erasure apply.\nsale_or_sharing:\n  stance: prohibited\n  text: No selling of visitor data.\n"
source_yaml_url: https://artifacts.apis.io/polycode-co-uk/privacy/polycode-co-uk-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 10 quoted statements, read from Polycode's own page on 2026-11-10.
synthetic: false
tags:
- Chat
- Memory
- Agents
- A2A
- Knowledge Graph
- Research
- Artificial Intelligence
- Open Source
- Consulting
- United Kingdom
---
