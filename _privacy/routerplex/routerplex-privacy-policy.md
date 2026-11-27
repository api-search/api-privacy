---
api_specs:
- filename: routerplex-images-api-openapi.yml
  format: yaml
  label: RouterPlex Images API
  slug: routerplex-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routerplex/openapi/routerplex-images-api-openapi.yml
- filename: routerplex-messages-api-openapi.yml
  format: yaml
  label: RouterPlex Messages API
  slug: routerplex-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routerplex/openapi/routerplex-messages-api-openapi.yml
- filename: routerplex-models-api-openapi.yml
  format: yaml
  label: RouterPlex Models API
  slug: routerplex-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routerplex/openapi/routerplex-models-api-openapi.yml
- filename: routerplex-responses-api-openapi.yml
  format: yaml
  label: RouterPlex Responses API
  slug: routerplex-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routerplex/openapi/routerplex-responses-api-openapi.yml
- filename: routerplex-chat-completions-api-openapi.yml
  format: yaml
  label: RouterPlex Chat Completions API
  slug: routerplex-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routerplex/openapi/routerplex-chat-completions-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data — email address, first and last name, a salted hash of your password (never the password itself)
  - category: financial
    text: Payment records — top-up amount, payment method, status, and a payment reference from the processor.
  - category: behavioral
    text: Usage metadata — per-request logs with timestamp, model, token counts, cost, and the API key used.
  - category: communication
    text: Customer.io — sends our marketing email (newsletters and product updates).
  deletion:
    route: Email request or delete account
    text: You can request a copy of your data, or deletion of your account and data, by emailing us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Billing and dashboard analytics
    text: This powers your dashboard analytics and billing.
  - purpose: Routing requests to the selected model
    text: for the sole purpose of routing it to the model you selected and returning the response to you.
  - purpose: Measurement after consent
    text: With your consent, we also load PostHog, Google Analytics, Google Ads conversion measurement, Reddit Pixel, Paved, and Affonso to measure signups, checkout starts, and completed payments.
  residency:
  - region: United States
    text: PostHog — receives product analytics, funnel events, and masked session replays only when you consent; processed in the United States.
  retention:
  - period: null
    scope: Prompt and response content
    text: Prompt and response content is not retained — see section 02, it is not stored in the first place.
  - period: at least 1 day and no more than 365 days
    scope: Abliterated model requests
    text: Stored requests are kept for at least 1 day and no more than 365 days, and are then deleted.
  - period: within 30 days
    scope: Account deletion
    text: If you delete your account, we delete or anonymize your personal data within 30 days, except records we are legally required to keep
  rights:
  - right: Access and update
    text: You can access and update your account data from the dashboard.
  - right: Copy or deletion
    text: You can request a copy of your data, or deletion of your account and data, by emailing us.
  - right: Restrict or object
    text: you may also have rights to restrict or object to processing and to lodge a complaint with a supervisory authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data or share prompt content with analytics or advertising measurement providers.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: RouterPlex
provenance_date: '2026-11-10'
provider_name: RouterPlex
provider_slug: routerplex
slug: routerplex-privacy-policy
source_date: '2026-11-10'
source_filename: routerplex-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://routerplex.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: RouterPlex\naid: routerplex\nurl: https://routerplex.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account data — email address, first and last name, a salted hash of your password (never the password itself)\n- category: financial\n  text: Payment records — top-up amount, payment method, status, and a payment reference from the processor.\n- category: behavioral\n  text: Usage metadata — per-request logs with timestamp, model, token counts, cost, and the API key used.\n- category: communication\n  text: Customer.io — sends\
  \ our marketing email (newsletters and product updates).\npurposes:\n- purpose: Billing and dashboard analytics\n  text: This powers your dashboard analytics and billing.\n- purpose: Routing requests to the selected model\n  text: for the sole purpose of routing it to the model you selected and returning the response to you.\n- purpose: Measurement after consent\n  text: With your consent, we also load PostHog, Google Analytics, Google Ads conversion measurement, Reddit Pixel,\n    Paved, and Affonso to measure signups, checkout starts, and completed payments.\nretention:\n- scope: Prompt and response content\n  period: null\n  text: Prompt and response content is not retained — see section 02, it is not stored in the first place.\n- scope: Abliterated model requests\n  period: at least 1 day and no more than 365 days\n  text: Stored requests are kept for at least 1 day and no more than 365 days, and are then deleted.\n- scope: Account deletion\n  period: within 30 days\n  text: If you\
  \ delete your account, we delete or anonymize your personal data within 30 days, except records we\n    are legally required to keep\nresidency:\n- region: United States\n  text: PostHog — receives product analytics, funnel events, and masked session replays only when you consent; processed\n    in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request or delete account\n  text: You can request a copy of your data, or deletion of your account and data, by emailing us.\nrights:\n- right: Access and update\n  text: You can access and update your account data from the dashboard.\n- right: Copy or deletion\n  text: You can request a copy of your data, or deletion of your account and data, by emailing us.\n- right: Restrict or object\n  text: you may also have rights to restrict or object to processing and to lodge a complaint with a supervisory\n    authority.\nsale_or_sharing:\n  stance:\
  \ prohibited\n  text: We do not sell personal data or share prompt content with analytics or advertising measurement providers.\n"
source_yaml_url: https://artifacts.apis.io/routerplex/privacy/routerplex-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from RouterPlex's own page on 2026-11-10.
synthetic: false
tags:
- LLM
- Artificial Intelligence
- AI Gateway
- Inference
- Model Router
- OpenAI-Compatible
- Anthropic Compatible
- Claude
- GPT
- Gemini
- API Gateway
- Agent Infrastructure
- Developer Tools
- MCP
- LLMOps
---
