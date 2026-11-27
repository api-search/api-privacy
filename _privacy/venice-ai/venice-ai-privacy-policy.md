---
api_specs:
- filename: venice-ai-api-keys-api-openapi.yml
  format: yaml
  label: Venice.ai API Keys API
  slug: venice-ai-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-api-keys-api-openapi.yml
- filename: venice-ai-audio-api-openapi.yml
  format: yaml
  label: Venice.ai Audio API
  slug: venice-ai-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-audio-api-openapi.yml
- filename: venice-ai-augment-api-openapi.yml
  format: yaml
  label: Venice.ai Augment API
  slug: venice-ai-augment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-augment-api-openapi.yml
- filename: venice-ai-billing-api-openapi.yml
  format: yaml
  label: Venice.ai Billing API
  slug: venice-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-billing-api-openapi.yml
- filename: venice-ai-characters-api-openapi.yml
  format: yaml
  label: Venice.ai Characters API
  slug: venice-ai-characters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-characters-api-openapi.yml
- filename: venice-ai-crypto-rpc-api-openapi.yml
  format: yaml
  label: Venice.ai Crypto RPC API
  slug: venice-ai-crypto-rpc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-crypto-rpc-api-openapi.yml
- filename: venice-ai-decisions-api-openapi.yml
  format: yaml
  label: Venice.ai Decisions API
  slug: venice-ai-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-decisions-api-openapi.yml
- filename: venice-ai-embeddings-api-openapi.yml
  format: yaml
  label: Venice.ai Embeddings API
  slug: venice-ai-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-embeddings-api-openapi.yml
- filename: venice-ai-image-api-openapi.yml
  format: yaml
  label: Venice.ai Image API
  slug: venice-ai-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-image-api-openapi.yml
- filename: venice-ai-models-api-openapi.yml
  format: yaml
  label: Venice.ai Models API
  slug: venice-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-models-api-openapi.yml
- filename: venice-ai-preview-api-openapi.yml
  format: yaml
  label: Venice.ai Preview API
  slug: venice-ai-preview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-preview-api-openapi.yml
- filename: venice-ai-responses-api-openapi.yml
  format: yaml
  label: Venice.ai Responses API
  slug: venice-ai-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-responses-api-openapi.yml
- filename: venice-ai-speech-api-openapi.yml
  format: yaml
  label: Venice.ai Speech API
  slug: venice-ai-speech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-speech-api-openapi.yml
- filename: venice-ai-transcriptions-api-openapi.yml
  format: yaml
  label: Venice.ai Transcriptions API
  slug: venice-ai-transcriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-transcriptions-api-openapi.yml
- filename: venice-ai-video-api-openapi.yml
  format: yaml
  label: Venice.ai Video API
  slug: venice-ai-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-video-api-openapi.yml
- filename: venice-ai-voices-api-openapi.yml
  format: yaml
  label: Venice.ai Voices API
  slug: venice-ai-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-voices-api-openapi.yml
- filename: venice-ai-x402-api-openapi.yml
  format: yaml
  label: Venice.ai X402 API
  slug: venice-ai-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-x402-api-openapi.yml
- filename: venice-ai-chat-completions-api-openapi.yml
  format: yaml
  label: Venice.ai Chat Completions API
  slug: venice-ai-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-chat-completions-api-openapi.yml
claim_count: 4
description: ''
doc:
  data_categories:
  - category: communication
    text: Your conversation history stays on your device.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  retention:
  - period: null
    scope: proxied requests
    text: Requests are relayed through the proxy without being stored.
  - period: null
    scope: conversation history
    text: Venice never stores it on its servers.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Inference runs inside a hardware-isolated enclave operated by external TEE partners (NEAR AI Cloud and Phala Network).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Venice.ai
provenance_date: '2026-11-10'
provider_name: Venice.ai
provider_slug: venice-ai
slug: venice-ai-privacy-policy
source_date: '2026-11-10'
source_filename: venice-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://venice.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Venice.ai\naid: venice-ai\nurl: https://venice.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: communication\n  text: Your conversation history stays on your device.\npurposes: []\nretention:\n- scope: proxied requests\n  period: null\n  text: Requests are relayed through the proxy without being stored.\n- scope: conversation history\n  period: null\n  text: Venice never stores it on its servers.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Inference runs inside a hardware-isolated enclave operated by external TEE partners\
  \ (NEAR AI Cloud and Phala\n    Network).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/venice-ai/privacy/venice-ai-privacy-policy.yml
stated_fields:
- data_categories
- retention
- subprocessors
summary_line: 4 quoted statements, read from Venice.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- Image Generation
- Video Generation
- Text-to-Speech
- Embeddings
- Privacy
- OpenAI-Compatible
- x402
---
