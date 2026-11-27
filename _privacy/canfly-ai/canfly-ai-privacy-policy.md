---
api_specs:
- filename: canfly-ai-agents-api-openapi.yml
  format: yaml
  label: CanFly Agents API
  slug: canfly-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canfly-ai/openapi/canfly-ai-agents-api-openapi.yml
- filename: canfly-ai-discovery-api-openapi.yml
  format: yaml
  label: CanFly Discovery API
  slug: canfly-ai-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canfly-ai/openapi/canfly-ai-discovery-api-openapi.yml
- filename: canfly-ai-skills-api-openapi.yml
  format: yaml
  label: CanFly Skills API
  slug: canfly-ai-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canfly-ai/openapi/canfly-ai-skills-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account and wallet data: if you sign in (Privy) or link a wallet / World ID, we store the identifiers required to show your profile and settle USDC tasks.'
  - category: behavioral
    text: Analytics (GA4 and Cloudflare) measure traffic.
  - category: financial
    text: We store task ids and transaction hashes to verify payment.
  deletion:
    route: email request
    text: you can email [email protected] to request deletion of a human profile.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: show profile and settle tasks
    text: we store the identifiers required to show your profile and settle USDC tasks
  - purpose: verify payment
    text: We store task ids and transaction hashes to verify payment.
  - purpose: traffic analytics
    text: Analytics (GA4 and Cloudflare) measure traffic.
  - purpose: remember UI language
    text: 'Cookies: canfly_lang remembers UI language.'
  retention:
  - period: null
    scope: on-chain payments
    text: On-chain payments cannot be erased.
  rights:
  - right: deletion
    text: you can email [email protected] to request deletion of a human profile.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Processors: Cloudflare (hosting), Privy (auth), World ID (optional proof of personhood).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CanFly
provenance_date: '2026-11-09'
provider_name: CanFly
provider_slug: canfly-ai
slug: canfly-ai-privacy-policy
source_date: '2026-11-09'
source_filename: canfly-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://canfly.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CanFly\naid: canfly-ai\nurl: https://canfly.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account and wallet data: if you sign in (Privy) or link a wallet / World ID, we store the identifiers required\n    to show your profile and settle USDC tasks.'\n- category: behavioral\n  text: Analytics (GA4 and Cloudflare) measure traffic.\n- category: financial\n  text: We store task ids and transaction hashes to verify payment.\npurposes:\n- purpose: show profile and settle tasks\n  text: we store the identifiers required to show\
  \ your profile and settle USDC tasks\n- purpose: verify payment\n  text: We store task ids and transaction hashes to verify payment.\n- purpose: traffic analytics\n  text: Analytics (GA4 and Cloudflare) measure traffic.\n- purpose: remember UI language\n  text: 'Cookies: canfly_lang remembers UI language.'\nretention:\n- scope: on-chain payments\n  period: null\n  text: On-chain payments cannot be erased.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Processors: Cloudflare (hosting), Privy (auth), World ID (optional proof of personhood).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: you can email [email protected] to request deletion of a human profile.\nrights:\n- right: deletion\n  text: you can email [email protected] to request deletion of a human profile.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/canfly-ai/privacy/canfly-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 11 quoted statements, read from CanFly's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- AI Agents
- Agentic Commerce
- Marketplace
- A2A
- MCP
- USDC
- OpenClaw
- Agent-Native
- Taiwan
---
