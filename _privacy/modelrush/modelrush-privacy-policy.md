---
api_specs:
- filename: modelrush-audio-api-openapi.yml
  format: yaml
  label: ModelRush Audio API
  slug: modelrush-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modelrush/openapi/modelrush-audio-api-openapi.yml
- filename: modelrush-discovery-api-openapi.yml
  format: yaml
  label: ModelRush Discovery API
  slug: modelrush-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modelrush/openapi/modelrush-discovery-api-openapi.yml
- filename: modelrush-images-api-openapi.yml
  format: yaml
  label: ModelRush Images API
  slug: modelrush-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modelrush/openapi/modelrush-images-api-openapi.yml
- filename: modelrush-predictions-api-openapi.yml
  format: yaml
  label: ModelRush Predictions API
  slug: modelrush-predictions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modelrush/openapi/modelrush-predictions-api-openapi.yml
- filename: modelrush-uploads-api-openapi.yml
  format: yaml
  label: ModelRush Uploads API
  slug: modelrush-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modelrush/openapi/modelrush-uploads-api-openapi.yml
- filename: modelrush-video-api-openapi.yml
  format: yaml
  label: ModelRush Video API
  slug: modelrush-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modelrush/openapi/modelrush-video-api-openapi.yml
- filename: modelrush-webhooks-api-openapi.yml
  format: yaml
  label: ModelRush Webhooks API
  slug: modelrush-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modelrush/openapi/modelrush-webhooks-api-openapi.yml
- filename: modelrush-chat-completions-api-openapi.yml
  format: yaml
  label: ModelRush Chat Completions API
  slug: modelrush-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modelrush/openapi/modelrush-chat-completions-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account and identity data: name, email, organization, role, and account identifiers returned by identity providers such as Clerk'
  - category: financial
    text: 'Payment and transaction data: plan, billing address, invoices, tax information, and payment status; full card details are generally held by the payment processor'
  - category: device
    text: 'Usage and device data: IP address, browser, device, cookies, page interactions, security signals, and approximate location'
  - category: behavioral
    text: 'API and operational metadata: request_id, time, model, route, tokens or media seconds, latency, errors, cost, and key identifier'
  - category: other
    text: 'Customer Content: prompts, code, files, images, video, audio, reference media, and model outputs'
  - category: communication
    text: 'Support and communications: tickets, email, feedback, and diagnostics you choose to provide'
  deletion:
    route: Verified deletion requests via privacy contact; applied to long-term archive through a manual process
    text: Verified deletion requests are applied to the long-term archive through a manual process, although legal holds, fraud prevention, security events, or disputes can create delays.
  dpa:
    available: true
    text: Organization customers will usually address their end users' requests about Customer Content first, with reasonable ModelRush assistance under a data-processing agreement.
    url: null
  purposes:
  - purpose: Provide services
    text: Authenticate users and provide model calls, routing, async jobs, and downloads
  - purpose: Billing and fraud prevention
    text: Measure usage, manage credits, issue bills, and prevent fraud
  - purpose: Security and support
    text: Secure the platform, troubleshoot requests, provide support, and maintain reliability
  - purpose: Product improvement
    text: Understand product use and improve interfaces, documentation, routing, and performance
  - purpose: Legal compliance
    text: Comply with law, enforce terms, and respond to rights requests
  retention:
  - period: null
    scope: Customer Content
    text: Customer Content follows the period shown in account settings, model details, an order, or the Data Retention Policy
  - period: without automatic expiration
    scope: Prompts and uploads on standard services
    text: prompts and uploads on standard services also enter a private encrypted archive without automatic expiration
  - period: null
    scope: Financial and transaction records
    text: financial and transaction records follow applicable law
  rights:
  - right: Access
    text: Depending on your location, you may have rights to access, correct, delete, export, or restrict personal information
  - right: Correct
    text: Correct profile information or close an account in settings
  - right: Object and withdraw consent
    text: object to certain processing, withdraw consent, and complain to a regulator
  - right: Opt out of marketing
    text: Opt out of non-essential marketing; service and security notices may still be sent
  role:
    text: For prompts, inputs, and outputs submitted by organization customers, ModelRush acts as a service provider or processor following customer instructions. For account administration, security, billing, and product operations, ModelRush acts as a data controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we use standard contractual clauses or other lawful transfer mechanisms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ModelRush
provenance_date: '2026-11-10'
provider_name: ModelRush
provider_slug: modelrush
slug: modelrush-privacy-policy
source_date: '2026-11-10'
source_filename: modelrush-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://modelrush.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ModelRush\naid: modelrush\nurl: https://modelrush.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For prompts, inputs, and outputs submitted by organization customers, ModelRush acts as a service provider\n    or processor following customer instructions. For account administration, security, billing, and product operations,\n    ModelRush acts as a data controller.\ndata_categories:\n- category: identifying\n  text: 'Account and identity data: name, email, organization, role, and account identifiers returned by identity\n    providers such as Clerk'\n- category: financial\n  text: 'Payment\
  \ and transaction data: plan, billing address, invoices, tax information, and payment status; full\n    card details are generally held by the payment processor'\n- category: device\n  text: 'Usage and device data: IP address, browser, device, cookies, page interactions, security signals, and approximate\n    location'\n- category: behavioral\n  text: 'API and operational metadata: request_id, time, model, route, tokens or media seconds, latency, errors,\n    cost, and key identifier'\n- category: other\n  text: 'Customer Content: prompts, code, files, images, video, audio, reference media, and model outputs'\n- category: communication\n  text: 'Support and communications: tickets, email, feedback, and diagnostics you choose to provide'\npurposes:\n- purpose: Provide services\n  text: Authenticate users and provide model calls, routing, async jobs, and downloads\n- purpose: Billing and fraud prevention\n  text: Measure usage, manage credits, issue bills, and prevent fraud\n- purpose: Security\
  \ and support\n  text: Secure the platform, troubleshoot requests, provide support, and maintain reliability\n- purpose: Product improvement\n  text: Understand product use and improve interfaces, documentation, routing, and performance\n- purpose: Legal compliance\n  text: Comply with law, enforce terms, and respond to rights requests\nretention:\n- scope: Customer Content\n  period: null\n  text: Customer Content follows the period shown in account settings, model details, an order, or the Data Retention\n    Policy\n- scope: Prompts and uploads on standard services\n  period: without automatic expiration\n  text: prompts and uploads on standard services also enter a private encrypted archive without automatic expiration\n- scope: Financial and transaction records\n  period: null\n  text: financial and transaction records follow applicable law\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where required, we use standard contractual clauses or other lawful transfer mechanisms.\n\
  subprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Organization customers will usually address their end users' requests about Customer Content first, with\n    reasonable ModelRush assistance under a data-processing agreement.\ndeletion:\n  route: Verified deletion requests via privacy contact; applied to long-term archive through a manual process\n  text: Verified deletion requests are applied to the long-term archive through a manual process, although legal\n    holds, fraud prevention, security events, or disputes can create delays.\nrights:\n- right: Access\n  text: Depending on your location, you may have rights to access, correct, delete, export, or restrict personal\n    information\n- right: Correct\n  text: Correct profile information or close an account in settings\n- right: Object and withdraw consent\n  text: object to certain processing, withdraw consent, and complain to a regulator\n- right: Opt out of marketing\n  text: Opt out of non-essential\
  \ marketing; service and security notices may still be sent\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/modelrush/privacy/modelrush-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from ModelRush's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- Inference
- Multi-Modal
- Model Hosting
- Speech
- Image Generation
---
