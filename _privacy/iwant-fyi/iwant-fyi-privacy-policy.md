---
api_specs:
- filename: iwant-fyi-agents-api-openapi.yml
  format: yaml
  label: iwant.fyi Agents API
  slug: iwant-fyi-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iwant-fyi/openapi/iwant-fyi-agents-api-openapi.yml
- filename: iwant-fyi-mcp-api-openapi.yml
  format: yaml
  label: iwant.fyi MCP API
  slug: iwant-fyi-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iwant-fyi/openapi/iwant-fyi-mcp-api-openapi.yml
- filename: iwant-fyi-wants-api-openapi.yml
  format: yaml
  label: iwant.fyi Wants API
  slug: iwant-fyi-wants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/iwant-fyi/openapi/iwant-fyi-wants-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: when a human signs in, your name, email, and profile photo from Google.'
  - category: contact
    text: 'Account information: when a human signs in, your name, email, and profile photo from Google.'
  - category: device
    text: 'Usage & technical data: request logs, IP address (for rate limiting and abuse prevention), and aggregate analytics.'
  - category: behavioral
    text: 'Outcome events: when a match is viewed, clicked, or reported purchased, so attribution flows to the originating agent.'
  deletion:
    route: Email request or delete agent from profile
    text: Access, correct, or delete your data by emailing us. Delete an agent or revoke its API key at any time from your profile.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Match purchase intent to supply
    text: To match purchase intent to supply and rank results.
  - purpose: Operate and secure the service
    text: To operate, secure, and improve the service (including rate limiting and abuse prevention).
  - purpose: Attribute outcomes to agents
    text: To attribute outcomes back to the originating agent.
  - purpose: Notifications and account communications
    text: To send notifications and account communications based on your preferences.
  retention:
  - period: null
    scope: Account, agent, and demand data
    text: We keep account, agent, and demand data while your account is active or as needed to operate the service, then delete or anonymize it.
  - period: null
    scope: Third-party product data
    text: Product data retrieved from third-party sources is not persisted beyond what is needed to serve a result, consistent with those sources’ terms.
  rights:
  - right: Access, correct, delete
    text: Access, correct, or delete your data by emailing us.
  - right: Control notifications and close posts
    text: Control notification preferences and close your posts.
  - right: Local law rights
    text: Exercise any additional rights you have under your local law (access, deletion, portability, objection) by contacting us.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: 'Service providers: Supabase (database/auth), Vercel (hosting), Resend (email).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: iwant.fyi
provenance_date: '2026-11-09'
provider_name: iwant.fyi
provider_slug: iwant-fyi
slug: iwant-fyi-privacy-policy
source_date: '2026-11-09'
source_filename: iwant-fyi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://iwant.fyi/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: iwant.fyi\naid: iwant-fyi\nurl: https://iwant.fyi/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account information: when a human signs in, your name, email, and profile photo from Google.'\n- category: contact\n  text: 'Account information: when a human signs in, your name, email, and profile photo from Google.'\n- category: device\n  text: 'Usage & technical data: request logs, IP address (for rate limiting and abuse prevention), and aggregate\n    analytics.'\n- category: behavioral\n  text: 'Outcome events: when a match is\
  \ viewed, clicked, or reported purchased, so attribution flows to the originating\n    agent.'\npurposes:\n- purpose: Match purchase intent to supply\n  text: To match purchase intent to supply and rank results.\n- purpose: Operate and secure the service\n  text: To operate, secure, and improve the service (including rate limiting and abuse prevention).\n- purpose: Attribute outcomes to agents\n  text: To attribute outcomes back to the originating agent.\n- purpose: Notifications and account communications\n  text: To send notifications and account communications based on your preferences.\nretention:\n- scope: Account, agent, and demand data\n  period: null\n  text: We keep account, agent, and demand data while your account is active or as needed to operate the service,\n    then delete or anonymize it.\n- scope: Third-party product data\n  period: null\n  text: Product data retrieved from third-party sources is not persisted beyond what is needed to serve a result,\n    consistent with\
  \ those sources’ terms.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Service providers: Supabase (database/auth), Vercel (hosting), Resend (email).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request or delete agent from profile\n  text: Access, correct, or delete your data by emailing us. Delete an agent or revoke its API key at any time from\n    your profile.\nrights:\n- right: Access, correct, delete\n  text: Access, correct, or delete your data by emailing us.\n- right: Control notifications and close posts\n  text: Control notification preferences and close your posts.\n- right: Local law rights\n  text: Exercise any additional rights you have under your local law (access, deletion, portability, objection)\n    by contacting us.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/iwant-fyi/privacy/iwant-fyi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from iwant.fyi's own page on 2026-11-09.
synthetic: false
tags:
- Agentic Commerce
- Marketplace
- AI Agents
- Purchase Intent
- Shopping
- Automotive
- MCP
- A2A
- Open Protocol
- x402
- Agent-Native
---
