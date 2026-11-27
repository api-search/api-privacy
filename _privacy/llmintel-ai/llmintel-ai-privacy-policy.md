---
api_specs:
- filename: llmintel-ai-compare-api-openapi.yml
  format: yaml
  label: llmintel-ai Compare API
  slug: llmintel-ai-compare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmintel-ai/openapi/llmintel-ai-compare-api-openapi.yml
- filename: llmintel-ai-events-api-openapi.yml
  format: yaml
  label: llmintel-ai Events API
  slug: llmintel-ai-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmintel-ai/openapi/llmintel-ai-events-api-openapi.yml
- filename: llmintel-ai-models-api-openapi.yml
  format: yaml
  label: llmintel-ai Models API
  slug: llmintel-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmintel-ai/openapi/llmintel-ai-models-api-openapi.yml
- filename: llmintel-ai-status-api-openapi.yml
  format: yaml
  label: llmintel-ai Status API
  slug: llmintel-ai-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmintel-ai/openapi/llmintel-ai-status-api-openapi.yml
- filename: llmintel-ai-telemetry-api-openapi.yml
  format: yaml
  label: llmintel-ai Telemetry API
  slug: llmintel-ai-telemetry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmintel-ai/openapi/llmintel-ai-telemetry-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your email address, name, and authentication credentials
  - category: financial
    text: Stripe processes payment information (we do not store credit card details)
  - category: device
    text: We temporarily store hashed IP addresses for rate limiting (pruned after each minute window)
  - category: behavioral
    text: Model identifiers (e.g., "gpt-4o", "claude-sonnet-5.5") Token counts (input and output) Timestamps Optional environment tags
  deletion:
    route: Account deletion
    text: After account deletion, personal data is removed within 30 days, except where required by law.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide model lifecycle tracking and cost analytics
    text: Provide model lifecycle tracking and cost analytics
  - purpose: Send deprecation notifications
    text: Send notifications about model deprecations and retirements
  - purpose: Process payments and manage subscriptions
    text: Process payments and manage subscriptions
  - purpose: Improve services
    text: Improve our services and develop new features
  residency:
  - region: United States
    text: Our services are hosted in the United States.
  retention:
  - period: null
    scope: Account and telemetry data
    text: Account and telemetry data are retained while your account is active.
  - period: 1-13 months
    scope: Historical telemetry
    text: Historical telemetry is retained according to your plan (1-13 months).
  - period: each minute window
    scope: Hashed IP addresses
    text: pruned after each minute window
  rights:
  - right: Access
    text: Access your personal data
  - right: Correction
    text: Correct inaccurate data
  - right: Deletion
    text: Request deletion of your data
  - right: Export
    text: Export your data
  - right: Opt out of marketing
    text: Opt out of marketing communications
  - right: Complaint
    text: Lodge a complaint with a supervisory authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: llmintel-ai
provenance_date: '2026-11-09'
provider_name: llmintel-ai
provider_slug: llmintel-ai
slug: llmintel-ai-privacy-policy
source_date: '2026-11-09'
source_filename: llmintel-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://llmintel.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: llmintel-ai\naid: llmintel-ai\nurl: https://llmintel.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we collect your email address, name, and authentication credentials\n- category: financial\n  text: Stripe processes payment information (we do not store credit card details)\n- category: device\n  text: We temporarily store hashed IP addresses for rate limiting (pruned after each minute window)\n- category: behavioral\n  text: Model identifiers (e.g., \"gpt-4o\", \"claude-sonnet-5.5\") Token counts (input and output) Timestamps\
  \ Optional\n    environment tags\npurposes:\n- purpose: Provide model lifecycle tracking and cost analytics\n  text: Provide model lifecycle tracking and cost analytics\n- purpose: Send deprecation notifications\n  text: Send notifications about model deprecations and retirements\n- purpose: Process payments and manage subscriptions\n  text: Process payments and manage subscriptions\n- purpose: Improve services\n  text: Improve our services and develop new features\nretention:\n- scope: Account and telemetry data\n  period: null\n  text: Account and telemetry data are retained while your account is active.\n- scope: Historical telemetry\n  period: 1-13 months\n  text: Historical telemetry is retained according to your plan (1-13 months).\n- scope: Hashed IP addresses\n  period: each minute window\n  text: pruned after each minute window\nresidency:\n- region: United States\n  text: Our services are hosted in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\n\
  dpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion\n  text: After account deletion, personal data is removed within 30 days, except where required by law.\nrights:\n- right: Access\n  text: Access your personal data\n- right: Correction\n  text: Correct inaccurate data\n- right: Deletion\n  text: Request deletion of your data\n- right: Export\n  text: Export your data\n- right: Opt out of marketing\n  text: Opt out of marketing communications\n- right: Complaint\n  text: Lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/llmintel-ai/privacy/llmintel-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 19 quoted statements, read from llmintel-ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Cost
- Observability
- Telemetry
- Generative AI
---
