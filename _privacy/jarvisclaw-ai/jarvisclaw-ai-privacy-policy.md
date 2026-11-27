---
api_specs:
- filename: jarvisclaw-ai-a2a-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai A2a API
  slug: jarvisclaw-ai-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-a2a-api-openapi.yml
- filename: jarvisclaw-ai-audio-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai Audio API
  slug: jarvisclaw-ai-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-audio-api-openapi.yml
- filename: jarvisclaw-ai-completions-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai Completions API
  slug: jarvisclaw-ai-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-completions-api-openapi.yml
- filename: jarvisclaw-ai-edits-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai Edits API
  slug: jarvisclaw-ai-edits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-edits-api-openapi.yml
- filename: jarvisclaw-ai-embeddings-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai Embeddings API
  slug: jarvisclaw-ai-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-embeddings-api-openapi.yml
- filename: jarvisclaw-ai-images-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai Images API
  slug: jarvisclaw-ai-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-images-api-openapi.yml
- filename: jarvisclaw-ai-intent-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai Intent API
  slug: jarvisclaw-ai-intent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-intent-api-openapi.yml
- filename: jarvisclaw-ai-marketplace-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai Marketplace API
  slug: jarvisclaw-ai-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-marketplace-api-openapi.yml
- filename: jarvisclaw-ai-messages-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai Messages API
  slug: jarvisclaw-ai-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-messages-api-openapi.yml
- filename: jarvisclaw-ai-moderations-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai Moderations API
  slug: jarvisclaw-ai-moderations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-moderations-api-openapi.yml
- filename: jarvisclaw-ai-prompt-coach-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai Prompt Coach API
  slug: jarvisclaw-ai-prompt-coach-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-prompt-coach-api-openapi.yml
- filename: jarvisclaw-ai-realtime-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai Realtime API
  slug: jarvisclaw-ai-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-realtime-api-openapi.yml
- filename: jarvisclaw-ai-rerank-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai Rerank API
  slug: jarvisclaw-ai-rerank-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-rerank-api-openapi.yml
- filename: jarvisclaw-ai-responses-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai Responses API
  slug: jarvisclaw-ai-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-responses-api-openapi.yml
- filename: jarvisclaw-ai-search-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai Search API
  slug: jarvisclaw-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-search-api-openapi.yml
- filename: jarvisclaw-ai-videos-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai Videos API
  slug: jarvisclaw-ai-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-videos-api-openapi.yml
- filename: jarvisclaw-ai-chat-completions-api-openapi.yml
  format: yaml
  label: jarvisclaw-ai Chat Completions API
  slug: jarvisclaw-ai-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jarvisclaw-ai/openapi/jarvisclaw-ai-chat-completions-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (for account recovery and notifications)
  - category: identifying
    text: Username and hashed password
  - category: identifying
    text: OAuth identifiers (if using third-party login such as Google or GitHub)
  - category: financial
    text: 'For traditional payments: transaction records and payment method metadata'
  - category: financial
    text: 'For on-chain payments: wallet address and transaction hash (already public on-chain)'
  - category: behavioral
    text: Basic analytics (page views, referrers) via privacy-respecting tools
  - category: device
    text: Model name, token counts, timestamps, and response status
  deletion:
    route: Request deletion of your account and associated data
    text: Request deletion of your account and associated data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Billing
    text: 'Billing : Calculate usage costs and process payments'
  - purpose: Service operation
    text: 'Service operation : Route requests, handle errors, maintain uptime'
  - purpose: Security
    text: 'Security : Detect abuse, prevent fraud, enforce rate limits'
  - purpose: Communication
    text: 'Communication : Send service notifications (outage alerts, billing notices)'
  retention:
  - period: 90 days
    scope: Request metadata
    text: Retained for 90 days, then automatically deleted
  - period: null
    scope: Prompts/completions
    text: Prompts or completions beyond the duration of a single request
  - period: Until account deletion
    scope: Account information
    text: Account information | Until account deletion
  - period: As required by law
    scope: Payment records
    text: Payment records | As required by law
  rights:
  - right: Access
    text: Access your personal data
  - right: Deletion
    text: Request deletion of your account and associated data
  - right: Export
    text: Export your usage data
  - right: Opt out of non-essential communications
    text: Opt out of non-essential communications
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or share your prompts and completions with any third party.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: jarvisclaw-ai
provenance_date: '2026-11-09'
provider_name: jarvisclaw-ai
provider_slug: jarvisclaw-ai
slug: jarvisclaw-ai-privacy-policy
source_date: '2026-11-09'
source_filename: jarvisclaw-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://jarvisclaw.ai/en/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: jarvisclaw-ai\naid: jarvisclaw-ai\nurl: https://jarvisclaw.ai/en/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address (for account recovery and notifications)\n- category: identifying\n  text: Username and hashed password\n- category: identifying\n  text: OAuth identifiers (if using third-party login such as Google or GitHub)\n- category: financial\n  text: 'For traditional payments: transaction records and payment method metadata'\n- category: financial\n  text: 'For on-chain payments: wallet address and transaction\
  \ hash (already public on-chain)'\n- category: behavioral\n  text: Basic analytics (page views, referrers) via privacy-respecting tools\n- category: device\n  text: Model name, token counts, timestamps, and response status\npurposes:\n- purpose: Billing\n  text: 'Billing : Calculate usage costs and process payments'\n- purpose: Service operation\n  text: 'Service operation : Route requests, handle errors, maintain uptime'\n- purpose: Security\n  text: 'Security : Detect abuse, prevent fraud, enforce rate limits'\n- purpose: Communication\n  text: 'Communication : Send service notifications (outage alerts, billing notices)'\nretention:\n- scope: Request metadata\n  period: 90 days\n  text: Retained for 90 days, then automatically deleted\n- scope: Prompts/completions\n  period: null\n  text: Prompts or completions beyond the duration of a single request\n- scope: Account information\n  period: Until account deletion\n  text: Account information | Until account deletion\n- scope: Payment\
  \ records\n  period: As required by law\n  text: Payment records | As required by law\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion of your account and associated data\n  text: Request deletion of your account and associated data\nrights:\n- right: Access\n  text: Access your personal data\n- right: Deletion\n  text: Request deletion of your account and associated data\n- right: Export\n  text: Export your usage data\n- right: Opt out of non-essential communications\n  text: Opt out of non-essential communications\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or share your prompts and completions with any third party.\n"
source_yaml_url: https://artifacts.apis.io/jarvisclaw-ai/privacy/jarvisclaw-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from jarvisclaw-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Payments
- Infrastructure
- Marketplace
---
