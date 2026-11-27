---
api_specs:
- filename: sipi-agents-api-openapi.yml
  format: yaml
  label: GitDealFlow Agents API
  slug: sipi-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sipi/openapi/sipi-agents-api-openapi.yml
- filename: sipi-approvals-api-openapi.yml
  format: yaml
  label: GitDealFlow Approvals API
  slug: sipi-approvals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sipi/openapi/sipi-approvals-api-openapi.yml
- filename: sipi-budget-api-openapi.yml
  format: yaml
  label: GitDealFlow Budget API
  slug: sipi-budget-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sipi/openapi/sipi-budget-api-openapi.yml
- filename: sipi-evaluate-api-openapi.yml
  format: yaml
  label: GitDealFlow Evaluate API
  slug: sipi-evaluate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sipi/openapi/sipi-evaluate-api-openapi.yml
- filename: sipi-rules-api-openapi.yml
  format: yaml
  label: GitDealFlow Rules API
  slug: sipi-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sipi/openapi/sipi-rules-api-openapi.yml
- filename: sipi-system-api-openapi.yml
  format: yaml
  label: GitDealFlow System API
  slug: sipi-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sipi/openapi/sipi-system-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: financial
    text: we process the transaction metadata you send (amount, merchant, category, timestamps)
  - category: contact
    text: we store your email and billing status (via Stripe)
  - category: professional
    text: we store the company, work email, website, stack, spend range, and risk description you submit
  deletion:
    route: email
    text: To request export or deletion of your data, email sales@sipiteno.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: apply rules and write audit record
    text: to apply your rules and write an audit record
  - purpose: product analytics
    text: we load PostHog (EU region) for anonymous product analytics
  - purpose: evaluate pilot applications
    text: review pilot applications
  residency:
  - region: EU
    text: we load PostHog (EU region) for anonymous product analytics
  retention:
  - period: null
    scope: audit logs
    text: Audit logs are retained for your account's configured window.
  - period: null
    scope: pilot applications
    text: Pilot applications are retained while we evaluate or discuss the engagement and then for normal business recordkeeping.
  rights:
  - right: export
    text: To request export or deletion of your data, email sales@sipiteno.com .
  - right: deletion
    text: To request export or deletion of your data, email sales@sipiteno.com .
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
name: GitDealFlow
provenance_date: '2026-11-10'
provider_name: GitDealFlow
provider_slug: sipi
slug: sipi-privacy-policy
source_date: '2026-11-10'
source_filename: sipi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sipi.bot/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: GitDealFlow\naid: sipi\nurl: https://sipi.bot/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: financial\n  text: we process the transaction metadata you send (amount, merchant, category, timestamps)\n- category: contact\n  text: we store your email and billing status (via Stripe)\n- category: professional\n  text: we store the company, work email, website, stack, spend range, and risk description you submit\npurposes:\n- purpose: apply rules and write audit record\n  text: to apply your rules and write an audit record\n- purpose: product analytics\n\
  \  text: we load PostHog (EU region) for anonymous product analytics\n- purpose: evaluate pilot applications\n  text: review pilot applications\nretention:\n- scope: audit logs\n  period: null\n  text: Audit logs are retained for your account's configured window.\n- scope: pilot applications\n  period: null\n  text: Pilot applications are retained while we evaluate or discuss the engagement and then for normal business\n    recordkeeping.\nresidency:\n- region: EU\n  text: we load PostHog (EU region) for anonymous product analytics\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email\n  text: To request export or deletion of your data, email sales@sipiteno.com .\nrights:\n- right: export\n  text: To request export or deletion of your data, email sales@sipiteno.com .\n- right: deletion\n  text: To request export or deletion of your data, email sales@sipiteno.com .\nsale_or_sharing:\n  stance: unstated\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/sipi/privacy/sipi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 12 quoted statements, read from GitDealFlow's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Finance
- Security
- Automation
- Software-as-a-Service
---
