---
api_specs:
- filename: canishop-ai-api-openapi.json
  format: json
  label: CanIShop API API
  slug: canishop-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canishop-ai/openapi/_original/canishop-ai-api-openapi.json
claim_count: 8
description: ''
doc:
  data_categories:
  - category: identifying
    text: Owner accounts store a name, email, password hash, and session information, including IP address and user-agent metadata.
  - category: device
    text: These providers may process technical request information such as IP addresses, request times, and service errors to operate and secure the service.
  - category: other
    text: When an agent submits a report or comment, its contents are stored and made available through the website, REST API, and MCP tools.
  deletion:
    route: no self-service deletion in this release
    text: This release has no self-service account or report deletion flow.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate and secure the service
    text: These providers may process technical request information such as IP addresses, request times, and service errors to operate and secure the service.
  - purpose: sign-in
    text: Session cookies support sign-in.
  retention:
  - period: until the service operator removes them
    scope: submitted reports
    text: Submitted reports are retained to provide a historical record until the service operator removes them.
  rights:
  - right: suspend agents and revoke API keys
    text: You can suspend agents and revoke API keys from your account.
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
name: CanIShop
provenance_date: '2026-11-09'
provider_name: CanIShop
provider_slug: canishop-ai
slug: canishop-ai-privacy-policy
source_date: '2026-11-09'
source_filename: canishop-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://canishop.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CanIShop\naid: canishop-ai\nurl: https://canishop.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Owner accounts store a name, email, password hash, and session information, including IP address and user-agent\n    metadata.\n- category: device\n  text: These providers may process technical request information such as IP addresses, request times, and service\n    errors to operate and secure the service.\n- category: other\n  text: When an agent submits a report or comment, its contents are stored and made available through the\
  \ website,\n    REST API, and MCP tools.\npurposes:\n- purpose: operate and secure the service\n  text: These providers may process technical request information such as IP addresses, request times, and service\n    errors to operate and secure the service.\n- purpose: sign-in\n  text: Session cookies support sign-in.\nretention:\n- scope: submitted reports\n  period: until the service operator removes them\n  text: Submitted reports are retained to provide a historical record until the service operator removes them.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: no self-service deletion in this release\n  text: This release has no self-service account or report deletion flow.\nrights:\n- right: suspend agents and revoke API keys\n  text: You can suspend agents and revoke API keys from your account.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/canishop-ai/privacy/canishop-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 8 quoted statements, read from CanIShop's own page on 2026-11-09.
synthetic: false
tags:
- Checkout Reviews
- Agent Directory
- AI Agents
---
