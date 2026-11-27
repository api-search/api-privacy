---
api_specs:
- filename: kymaapi-com-audio-api-openapi.yml
  format: yaml
  label: kymaapi-com Audio API
  slug: kymaapi-com-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-audio-api-openapi.yml
- filename: kymaapi-com-auth-api-openapi.yml
  format: yaml
  label: kymaapi-com Auth API
  slug: kymaapi-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-auth-api-openapi.yml
- filename: kymaapi-com-chat-api-openapi.yml
  format: yaml
  label: kymaapi-com Chat API
  slug: kymaapi-com-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-chat-api-openapi.yml
- filename: kymaapi-com-completions-api-openapi.yml
  format: yaml
  label: kymaapi-com Completions API
  slug: kymaapi-com-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-completions-api-openapi.yml
- filename: kymaapi-com-credits-api-openapi.yml
  format: yaml
  label: kymaapi-com Credits API
  slug: kymaapi-com-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-credits-api-openapi.yml
- filename: kymaapi-com-decisions-api-openapi.yml
  format: yaml
  label: kymaapi-com Decisions API
  slug: kymaapi-com-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-decisions-api-openapi.yml
- filename: kymaapi-com-discovery-api-openapi.yml
  format: yaml
  label: kymaapi-com Discovery API
  slug: kymaapi-com-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-discovery-api-openapi.yml
- filename: kymaapi-com-embeddings-api-openapi.yml
  format: yaml
  label: kymaapi-com Embeddings API
  slug: kymaapi-com-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-embeddings-api-openapi.yml
- filename: kymaapi-com-images-api-openapi.yml
  format: yaml
  label: kymaapi-com Images API
  slug: kymaapi-com-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-images-api-openapi.yml
- filename: kymaapi-com-models-api-openapi.yml
  format: yaml
  label: kymaapi-com Models API
  slug: kymaapi-com-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-models-api-openapi.yml
- filename: kymaapi-com-video-api-openapi.yml
  format: yaml
  label: kymaapi-com Video API
  slug: kymaapi-com-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kymaapi-com/openapi/kymaapi-com-video-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address, optional display name, and a securely hashed password when you create an account.
  - category: contact
    text: we receive your email, name, and Google profile photo URL from Google Sign-In
  - category: behavioral
    text: we log the prompt or message content, the model used, token counts, response time, status code
  - category: device
    text: basic connection metadata (IP address, user agent, source app fingerprint where present)
  - category: financial
    text: We do receive a Stripe customer ID, the last four digits, brand, and country of the card (for fraud screening).
  - category: communication
    text: conversations are saved to your account so you can return to them
  deletion:
    route: Request full account deletion via privacy@kymaapi.com or delete individual chat conversations from the dashboard
    text: Delete — delete a chat conversation from the dashboard, or request full account deletion via privacy@kymaapi.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: route your requests, return Outputs, store generated assets briefly so you can download them
  - purpose: Bill accurately
    text: track tokens, seconds, characters, and image counts for credit deductions
  - purpose: Keep the service safe
    text: detect abuse, fraud, multi-account farming, and Acceptable Use Policy violations
  - purpose: Improve reliability
    text: understand error patterns, latency issues, and which models perform best
  - purpose: Comply with law
    text: respond to legitimate legal process, take-down notices, and statutory reporting obligations
  residency:
  - region: United States
    text: Kyma is operated from the United States.
  retention:
  - period: 90 days
    scope: API request logs (prompts and response content)
    text: 'API request logs (prompts and response content): 90 days, then auto-deleted.'
  - period: 24 hours
    scope: Generated image, video, and audio assets
    text: 'Generated image, video, and audio assets : 24 hours by default. Pass a retain: 30d flag at request time to extend to 30 days.'
  - period: null
    scope: Dashboard chat conversations
    text: 'Dashboard chat conversations : kept until you delete them.'
  - period: indefinitely
    scope: Usage metadata
    text: 'Usage metadata (counts, timing, no content): retained indefinitely for analytics, ranking, and billing reconciliation.'
  - period: up to 12 months after deletion
    scope: Account data
    text: kept while your account is active and for up to 12 months after deletion
  - period: at least one year
    scope: Take-down records
    text: 'Take-down records : kept for at least one year as required by U.S. and E.U. law.'
  rights:
  - right: Access and export
    text: Access and export — request a copy of your account data and request logs.
  - right: Correct
    text: Correct — update your email, display name, billing details from the dashboard.
  - right: Delete
    text: Delete — delete a chat conversation from the dashboard, or request full account deletion via privacy@kymaapi.com .
  - right: Object / restrict
    text: the right to object to certain processing and the right to lodge a complaint with your supervisory authority
  - right: Opt out of sale or share (CCPA/CPRA)
    text: to opt out of any "sale" or "share" of personal information
  role:
    text: Kyma API is a service of Affitor LLC (Wyoming, USA), doing business as Kyma API.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: transfers outside your region rely on Standard Contractual Clauses or other lawful transfer mechanisms with our processors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: kymaapi-com
provenance_date: '2026-11-09'
provider_name: kymaapi-com
provider_slug: kymaapi-com
slug: kymaapi-com-privacy-policy
source_date: '2026-11-09'
source_filename: kymaapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://kymaapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: kymaapi-com\naid: kymaapi-com\nurl: https://kymaapi.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Kyma API is a service of Affitor LLC (Wyoming, USA), doing business as Kyma API.\ndata_categories:\n- category: identifying\n  text: Your email address, optional display name, and a securely hashed password when you create an account.\n- category: contact\n  text: we receive your email, name, and Google profile photo URL from Google Sign-In\n- category: behavioral\n  text: we log the prompt or message content, the model used, token counts, response time, status code\n- category: device\n\
  \  text: basic connection metadata (IP address, user agent, source app fingerprint where present)\n- category: financial\n  text: We do receive a Stripe customer ID, the last four digits, brand, and country of the card (for fraud screening).\n- category: communication\n  text: conversations are saved to your account so you can return to them\npurposes:\n- purpose: Provide the service\n  text: route your requests, return Outputs, store generated assets briefly so you can download them\n- purpose: Bill accurately\n  text: track tokens, seconds, characters, and image counts for credit deductions\n- purpose: Keep the service safe\n  text: detect abuse, fraud, multi-account farming, and Acceptable Use Policy violations\n- purpose: Improve reliability\n  text: understand error patterns, latency issues, and which models perform best\n- purpose: Comply with law\n  text: respond to legitimate legal process, take-down notices, and statutory reporting obligations\nretention:\n- scope: API request\
  \ logs (prompts and response content)\n  period: 90 days\n  text: 'API request logs (prompts and response content): 90 days, then auto-deleted.'\n- scope: Generated image, video, and audio assets\n  period: 24 hours\n  text: 'Generated image, video, and audio assets : 24 hours by default. Pass a retain: 30d flag at request time\n    to extend to 30 days.'\n- scope: Dashboard chat conversations\n  period: null\n  text: 'Dashboard chat conversations : kept until you delete them.'\n- scope: Usage metadata\n  period: indefinitely\n  text: 'Usage metadata (counts, timing, no content): retained indefinitely for analytics, ranking, and billing\n    reconciliation.'\n- scope: Account data\n  period: up to 12 months after deletion\n  text: kept while your account is active and for up to 12 months after deletion\n- scope: Take-down records\n  period: at least one year\n  text: 'Take-down records : kept for at least one year as required by U.S. and E.U. law.'\nresidency:\n- region: United States\n\
  \  text: Kyma is operated from the United States.\ntransfers:\n- mechanism: SCC\n  text: transfers outside your region rely on Standard Contractual Clauses or other lawful transfer mechanisms with\n    our processors\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request full account deletion via privacy@kymaapi.com or delete individual chat conversations from the\n    dashboard\n  text: Delete — delete a chat conversation from the dashboard, or request full account deletion via privacy@kymaapi.com\n    .\nrights:\n- right: Access and export\n  text: Access and export — request a copy of your account data and request logs.\n- right: Correct\n  text: Correct — update your email, display name, billing details from the dashboard.\n- right: Delete\n  text: Delete — delete a chat conversation from the dashboard, or request full account deletion via privacy@kymaapi.com\n    .\n- right: Object / restrict\n  text: the right to\
  \ object to certain processing and the right to lodge a complaint with your supervisory authority\n- right: Opt out of sale or share (CCPA/CPRA)\n  text: to opt out of any \"sale\" or \"share\" of personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/kymaapi-com/privacy/kymaapi-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from kymaapi-com's own page on 2026-11-09.
synthetic: false
tags:
- LLM
- API Gateway
- Artificial Intelligence
- Machine Learning
- Developer Tools
---
