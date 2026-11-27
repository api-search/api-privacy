---
api_specs:
- filename: bubblio-dev-agent-keys-api-openapi.yml
  format: yaml
  label: bubblio-dev Agent Keys API
  slug: bubblio-dev-agent-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bubblio-dev/openapi/bubblio-dev-agent-keys-api-openapi.yml
- filename: bubblio-dev-approvals-api-openapi.yml
  format: yaml
  label: bubblio-dev Approvals API
  slug: bubblio-dev-approvals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bubblio-dev/openapi/bubblio-dev-approvals-api-openapi.yml
- filename: bubblio-dev-discovery-api-openapi.yml
  format: yaml
  label: bubblio-dev Discovery API
  slug: bubblio-dev-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bubblio-dev/openapi/bubblio-dev-discovery-api-openapi.yml
- filename: bubblio-dev-mcp-api-openapi.yml
  format: yaml
  label: bubblio-dev MCP API
  slug: bubblio-dev-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bubblio-dev/openapi/bubblio-dev-mcp-api-openapi.yml
- filename: bubblio-dev-platform-push-api-openapi.yml
  format: yaml
  label: bubblio-dev Platform Push API
  slug: bubblio-dev-platform-push-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bubblio-dev/openapi/bubblio-dev-platform-push-api-openapi.yml
- filename: bubblio-dev-platform-sync-api-openapi.yml
  format: yaml
  label: bubblio-dev Platform Sync API
  slug: bubblio-dev-platform-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bubblio-dev/openapi/bubblio-dev-platform-sync-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Your account: email, name, company, and a password we store only as a secure hash — we cannot read it.'
  - category: behavioral
    text: We keep usage records (agent visits, tool calls, quotes and confirms) so you can see the same numbers we do in your dashboard.
  - category: communication
    text: A visiting AI agent's conversation with your door — its questions, the results your own tools return, and for actions it runs, the quote and receipt — persists as a transcript in your dashboard.
  - category: financial
    text: we never see or store card numbers, and never hold the funds ourselves.
  deletion:
    route: Email bubblio@andresio.com to delete sessions or your whole account
    text: Email bubblio@andresio.com to delete sessions or your whole account, and we will.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate the service and dashboard
    text: so you can see the same numbers we do in your dashboard
  - purpose: Language model answers
    text: Anthropic the language model behind ask answers
  - purpose: Search embeddings
    text: Voyage AI search embeddings for knowledge
  - purpose: Payments
    text: Stripe payments
  retention:
  - period: null
    scope: Account data
    text: Account data lives while your account does.
  - period: null
    scope: Transcripts, tool-call records, quote receipts
    text: Transcripts, tool-call records, and quote receipts persist so your dashboard's activity and receipts keep working.
  rights:
  - right: Access, correction, export, deletion
    text: Access, correction, export, deletion — email bubblio@andresio.com and a human reads it.
  role:
    text: we are the controller. For AI agents that knock on a customer's door , the business whose door it is decides why the conversation exists and what happens to it — they are the controller, and we process it on their behalf.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: we do not sell data to anyone.
  subprocessors:
    text: 'Who processes data for us These providers run parts of the service, each only for the purpose listed: Supabase database and file storage Modal API hosting Vercel web hosting and anonymous analytics Stripe payments Anthropic the language model behind ask answers Voyage AI search embeddings for knowledge Resend transactional email'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: bubblio-dev
provenance_date: '2026-11-09'
provider_name: bubblio-dev
provider_slug: bubblio-dev
slug: bubblio-dev-privacy-policy
source_date: '2026-11-09'
source_filename: bubblio-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bubblio.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: bubblio-dev\naid: bubblio-dev\nurl: https://bubblio.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we are the controller. For AI agents that knock on a customer's door , the business whose door it is decides\n    why the conversation exists and what happens to it — they are the controller, and we process it on their behalf.\ndata_categories:\n- category: identifying\n  text: 'Your account: email, name, company, and a password we store only as a secure hash — we cannot read it.'\n- category: behavioral\n  text: We keep usage records (agent visits, tool calls, quotes and confirms) so you\
  \ can see the same numbers we\n    do in your dashboard.\n- category: communication\n  text: A visiting AI agent's conversation with your door — its questions, the results your own tools return, and\n    for actions it runs, the quote and receipt — persists as a transcript in your dashboard.\n- category: financial\n  text: we never see or store card numbers, and never hold the funds ourselves.\npurposes:\n- purpose: Operate the service and dashboard\n  text: so you can see the same numbers we do in your dashboard\n- purpose: Language model answers\n  text: Anthropic the language model behind ask answers\n- purpose: Search embeddings\n  text: Voyage AI search embeddings for knowledge\n- purpose: Payments\n  text: Stripe payments\nretention:\n- scope: Account data\n  period: null\n  text: Account data lives while your account does.\n- scope: Transcripts, tool-call records, quote receipts\n  period: null\n  text: Transcripts, tool-call records, and quote receipts persist so your dashboard's\
  \ activity and receipts keep\n    working.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Who processes data for us These providers run parts of the service, each only for the purpose listed: Supabase\n    database and file storage Modal API hosting Vercel web hosting and anonymous analytics Stripe payments Anthropic\n    the language model behind ask answers Voyage AI search embeddings for knowledge Resend transactional email'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email bubblio@andresio.com to delete sessions or your whole account\n  text: Email bubblio@andresio.com to delete sessions or your whole account, and we will.\nrights:\n- right: Access, correction, export, deletion\n  text: Access, correction, export, deletion — email bubblio@andresio.com and a human reads it.\nsale_or_sharing:\n  stance: prohibited\n  text: we do not sell data to anyone.\n"
source_yaml_url: https://artifacts.apis.io/bubblio-dev/privacy/bubblio-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from bubblio-dev's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Payments
- Automation
- Platform
- Agents
---
