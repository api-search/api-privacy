---
api_specs:
- filename: zotgpt-embeddings-api-openapi.yml
  format: yaml
  label: ZotGPT (UC Irvine) Embeddings API
  slug: zotgpt-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zotgpt/openapi/zotgpt-embeddings-api-openapi.yml
- filename: zotgpt-chat-completions-api-openapi.yml
  format: yaml
  label: ZotGPT (UC Irvine) Chat Completions API
  slug: zotgpt-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zotgpt/openapi/zotgpt-chat-completions-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'User Identity: UCI credentials for authentication and access control'
  - category: other
    text: 'User Prompts: Questions and requests submitted to AI services'
  - category: other
    text: 'Uploaded Files: Documents and files shared with AI services'
  - category: other
    text: 'AI Responses: Generated responses and conversation history'
  - category: device
    text: 'Session Cookies: For maintaining secure login sessions'
  - category: behavioral
    text: 'Service Usage: Which features and services you use'
  deletion:
    route: manual deletion by user or data removal request
    text: Manual deletion available anytime
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authentication and access control
    text: UCI credentials for authentication and access control
  retention:
  - period: 12 months
    scope: user data
    text: Automatic deletion after 12 months
  rights:
  - right: access conversation history
    text: View your conversation history
  - right: deletion of conversations
    text: Delete individual conversations
  - right: data removal request
    text: Request data removal
  - right: download data
    text: Download your data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not share your data without explicit consent, except in limited circumstances
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ZotGPT (UC Irvine)
provenance_date: '2026-11-10'
provider_name: ZotGPT (UC Irvine)
provider_slug: zotgpt
slug: zotgpt-privacy-policy
source_date: '2026-11-10'
source_filename: zotgpt-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://zotgpt.uci.edu/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ZotGPT (UC Irvine)\naid: zotgpt\nurl: https://zotgpt.uci.edu/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'User Identity: UCI credentials for authentication and access control'\n- category: other\n  text: 'User Prompts: Questions and requests submitted to AI services'\n- category: other\n  text: 'Uploaded Files: Documents and files shared with AI services'\n- category: other\n  text: 'AI Responses: Generated responses and conversation history'\n- category: device\n  text: 'Session Cookies: For maintaining secure login sessions'\n\
  - category: behavioral\n  text: 'Service Usage: Which features and services you use'\npurposes:\n- purpose: Authentication and access control\n  text: UCI credentials for authentication and access control\nretention:\n- scope: user data\n  period: 12 months\n  text: Automatic deletion after 12 months\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: manual deletion by user or data removal request\n  text: Manual deletion available anytime\nrights:\n- right: access conversation history\n  text: View your conversation history\n- right: deletion of conversations\n  text: Delete individual conversations\n- right: data removal request\n  text: Request data removal\n- right: download data\n  text: Download your data\nsale_or_sharing:\n  stance: conditional\n  text: We do not share your data without explicit consent, except in limited circumstances\n"
source_yaml_url: https://artifacts.apis.io/zotgpt/privacy/zotgpt-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from ZotGPT (UC Irvine)'s own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Generative AI
- LLM
- AI Gateway
- Higher Education
- University
- Education
- Multi-Cloud
- Multi-Model
- Chat Completions
- Embeddings
- Model Routing
- RAG
- Identity
- United States
- California
- Identity Federation
---
