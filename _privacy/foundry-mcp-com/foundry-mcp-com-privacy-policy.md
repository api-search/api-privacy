---
api_specs:
- filename: foundry-mcp-com-public-api-openapi.yml
  format: yaml
  label: foundry-mcp-com Public API
  slug: foundry-mcp-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/foundry-mcp-com/openapi/foundry-mcp-com-public-api-openapi.yml
- filename: foundry-mcp-com-tier-adventurer-api-openapi.yml
  format: yaml
  label: foundry-mcp-com Tier Adventurer API
  slug: foundry-mcp-com-tier-adventurer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/foundry-mcp-com/openapi/foundry-mcp-com-tier-adventurer-api-openapi.yml
- filename: foundry-mcp-com-tier-dm-api-openapi.yml
  format: yaml
  label: foundry-mcp-com Tier Dm API
  slug: foundry-mcp-com-tier-dm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/foundry-mcp-com/openapi/foundry-mcp-com-tier-dm-api-openapi.yml
- filename: foundry-mcp-com-tier-free-api-openapi.yml
  format: yaml
  label: foundry-mcp-com Tier Free API
  slug: foundry-mcp-com-tier-free-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/foundry-mcp-com/openapi/foundry-mcp-com-tier-free-api-openapi.yml
- filename: foundry-mcp-com-tier-guest-api-openapi.yml
  format: yaml
  label: foundry-mcp-com Tier Guest API
  slug: foundry-mcp-com-tier-guest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/foundry-mcp-com/openapi/foundry-mcp-com-tier-guest-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: we receive your email address , name , and Patreon membership status
  - category: identifying
    text: Patreon user ID — to sync subscription status via webhooks
  - category: identifying
    text: API key — a unique identifier for your account
  deletion:
    route: contact the provider or revoke API key
    text: You can request deletion of your account data by contacting us. Revoking your API key removes all stored information.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: create API key and determine subscription tier
    text: We use this to create your API key and determine your subscription tier.
  - purpose: account identification
    text: Email — for account identification
  - purpose: sync subscription status
    text: Patreon user ID — to sync subscription status via webhooks
  retention:
  - period: null
    scope: Patreon access tokens
    text: We do not store your Patreon access tokens. They are used once during OAuth and immediately discarded.
  - period: null
    scope: World data
    text: It is never written to disk and is deleted when your connection closes or the server restarts.
  - period: 7 days
    scope: Code-mode debug script text and call list
    text: the script text and the list of calls it made are kept for 7 days so the operator can diagnose a failure you report, then deleted.
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
name: foundry-mcp-com
provenance_date: '2026-11-09'
provider_name: foundry-mcp-com
provider_slug: foundry-mcp-com
slug: foundry-mcp-com-privacy-policy
source_date: '2026-11-09'
source_filename: foundry-mcp-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://foundry-mcp.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: foundry-mcp-com\naid: foundry-mcp-com\nurl: https://foundry-mcp.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we receive your email address , name , and Patreon membership status\n- category: identifying\n  text: Patreon user ID — to sync subscription status via webhooks\n- category: identifying\n  text: API key — a unique identifier for your account\npurposes:\n- purpose: create API key and determine subscription tier\n  text: We use this to create your API key and determine your subscription tier.\n- purpose: account identification\n\
  \  text: Email — for account identification\n- purpose: sync subscription status\n  text: Patreon user ID — to sync subscription status via webhooks\nretention:\n- scope: Patreon access tokens\n  period: null\n  text: We do not store your Patreon access tokens. They are used once during OAuth and immediately discarded.\n- scope: World data\n  period: null\n  text: It is never written to disk and is deleted when your connection closes or the server restarts.\n- scope: Code-mode debug script text and call list\n  period: 7 days\n  text: the script text and the list of calls it made are kept for 7 days so the operator can diagnose a failure\n    you report, then deleted.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact the provider or revoke API key\n  text: You can request deletion of your account data by contacting us. Revoking your API key removes all stored\n    information.\nrights:\
  \ []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/foundry-mcp-com/privacy/foundry-mcp-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 10 quoted statements, read from foundry-mcp-com's own page on 2026-11-09.
synthetic: false
tags:
- FoundryVTT
- MCP
- Artificial Intelligence
- Gaming
- Automation
---
