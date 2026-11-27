---
api_specs:
- filename: agenticfabricationnetwork-ai-agents-api-openapi.yml
  format: yaml
  label: Agentic Fabrication Network Agents API
  slug: agenticfabricationnetwork-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticfabricationnetwork-ai/openapi/agenticfabricationnetwork-ai-agents-api-openapi.yml
- filename: agenticfabricationnetwork-ai-attestations-api-openapi.yml
  format: yaml
  label: Agentic Fabrication Network Attestations API
  slug: agenticfabricationnetwork-ai-attestations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticfabricationnetwork-ai/openapi/agenticfabricationnetwork-ai-attestations-api-openapi.yml
- filename: agenticfabricationnetwork-ai-capabilities-api-openapi.yml
  format: yaml
  label: Agentic Fabrication Network Capabilities API
  slug: agenticfabricationnetwork-ai-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticfabricationnetwork-ai/openapi/agenticfabricationnetwork-ai-capabilities-api-openapi.yml
- filename: agenticfabricationnetwork-ai-checkout-api-openapi.yml
  format: yaml
  label: Agentic Fabrication Network Checkout API
  slug: agenticfabricationnetwork-ai-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticfabricationnetwork-ai/openapi/agenticfabricationnetwork-ai-checkout-api-openapi.yml
- filename: agenticfabricationnetwork-ai-files-api-openapi.yml
  format: yaml
  label: Agentic Fabrication Network Files API
  slug: agenticfabricationnetwork-ai-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticfabricationnetwork-ai/openapi/agenticfabricationnetwork-ai-files-api-openapi.yml
- filename: agenticfabricationnetwork-ai-orders-api-openapi.yml
  format: yaml
  label: Agentic Fabrication Network Orders API
  slug: agenticfabricationnetwork-ai-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticfabricationnetwork-ai/openapi/agenticfabricationnetwork-ai-orders-api-openapi.yml
- filename: agenticfabricationnetwork-ai-parts-api-openapi.yml
  format: yaml
  label: Agentic Fabrication Network Parts API
  slug: agenticfabricationnetwork-ai-parts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticfabricationnetwork-ai/openapi/agenticfabricationnetwork-ai-parts-api-openapi.yml
- filename: agenticfabricationnetwork-ai-quotes-api-openapi.yml
  format: yaml
  label: Agentic Fabrication Network Quotes API
  slug: agenticfabricationnetwork-ai-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticfabricationnetwork-ai/openapi/agenticfabricationnetwork-ai-quotes-api-openapi.yml
- filename: agenticfabricationnetwork-ai-ufp-api-openapi.yml
  format: yaml
  label: Agentic Fabrication Network Ufp API
  slug: agenticfabricationnetwork-ai-ufp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticfabricationnetwork-ai/openapi/agenticfabricationnetwork-ai-ufp-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Order details. When you pay, the payment page collects your name, shipping address, email, and sometimes a phone number
  - category: contact
    text: and sometimes a phone number, and we receive them to fulfill your order.
  - category: location
    text: Your destination ZIP code , if you give it, so prices include shipping to you.
  - category: device
    text: We record which assistant or app made a request (for example, ChatGPT) and its user-agent string.
  - category: behavioral
    text: we may record how pages are used (clicks, page views, and session recordings, with password and card fields masked) to find and fix problems.
  - category: communication
    text: Messages and reviews you send about an order, including your answers to a shop’s questions and the reviews you leave.
  deletion:
    route: Email hello@fabnet.ai to request access, correction, or deletion
    text: You can ask us to access, correct, or delete your personal information by emailing hello@fabnet.ai from the email address on your order.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Get quotes and place orders
    text: To get quotes from fabrication shops, show you offers, and place and track your order.
  - purpose: Order emails
    text: 'To send order emails: confirmation, receipt, status and shipping updates, questions from the shop, refunds, and a request to review your order.'
  - purpose: Improve the network
    text: 'To improve the network: we analyze past quotes and requests to estimate prices and to learn which processes and materials people need.'
  - purpose: Fraud prevention and legal obligations
    text: To prevent fraud and abuse and to meet legal, tax, and accounting obligations.
  residency:
  - region: United States
    text: Where we operate AFN serves customers in the United States, and we store and process data in the United States.
  retention:
  - period: null
    scope: Order records
    text: We keep order records, including contact and shipping details, for as long as we need them to provide the service, handle returns and disputes, and meet legal and tax obligations.
  - period: 90 days
    scope: Raw website event data
    text: Raw event data is deleted after 90 days.
  rights:
  - right: Access, correction, deletion
    text: You can ask us to access, correct, or delete your personal information by emailing hello@fabnet.ai from the email address on your order.
  - right: Response time
    text: We will verify the request and answer within 30 days.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information, and we do not use it for advertising.
  subprocessors:
    text: 'Service providers that run AFN for us: hosting and databases (Fly.io, Neon), file storage (Cloudflare R2), and email delivery (Resend).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agentic Fabrication Network
provenance_date: '2026-11-09'
provider_name: Agentic Fabrication Network
provider_slug: agenticfabricationnetwork-ai
slug: agenticfabricationnetwork-ai-privacy-policy
source_date: '2026-11-09'
source_filename: agenticfabricationnetwork-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agenticfabricationnetwork.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agentic Fabrication Network\naid: agenticfabricationnetwork-ai\nurl: https://agenticfabricationnetwork.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Order details. When you pay, the payment page collects your name, shipping address, email, and sometimes\n    a phone number\n- category: contact\n  text: and sometimes a phone number, and we receive them to fulfill your order.\n- category: location\n  text: Your destination ZIP code , if you give it, so prices include shipping to you.\n- category: device\n  text: We record which\
  \ assistant or app made a request (for example, ChatGPT) and its user-agent string.\n- category: behavioral\n  text: we may record how pages are used (clicks, page views, and session recordings, with password and card fields\n    masked) to find and fix problems.\n- category: communication\n  text: Messages and reviews you send about an order, including your answers to a shop’s questions and the reviews\n    you leave.\npurposes:\n- purpose: Get quotes and place orders\n  text: To get quotes from fabrication shops, show you offers, and place and track your order.\n- purpose: Order emails\n  text: 'To send order emails: confirmation, receipt, status and shipping updates, questions from the shop, refunds,\n    and a request to review your order.'\n- purpose: Improve the network\n  text: 'To improve the network: we analyze past quotes and requests to estimate prices and to learn which processes\n    and materials people need.'\n- purpose: Fraud prevention and legal obligations\n  text: To\
  \ prevent fraud and abuse and to meet legal, tax, and accounting obligations.\nretention:\n- scope: Order records\n  period: null\n  text: We keep order records, including contact and shipping details, for as long as we need them to provide the\n    service, handle returns and disputes, and meet legal and tax obligations.\n- scope: Raw website event data\n  period: 90 days\n  text: Raw event data is deleted after 90 days.\nresidency:\n- region: United States\n  text: Where we operate AFN serves customers in the United States, and we store and process data in the United\n    States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Service providers that run AFN for us: hosting and databases (Fly.io, Neon), file storage (Cloudflare R2),\n    and email delivery (Resend).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@fabnet.ai to request access, correction, or deletion\n  text: You can ask us to access, correct, or delete your personal information\
  \ by emailing hello@fabnet.ai from\n    the email address on your order.\nrights:\n- right: Access, correction, deletion\n  text: You can ask us to access, correct, or delete your personal information by emailing hello@fabnet.ai from\n    the email address on your order.\n- right: Response time\n  text: We will verify the request and answer within 30 days.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information, and we do not use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/agenticfabricationnetwork-ai/privacy/agenticfabricationnetwork-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Agentic Fabrication Network's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Manufacturing
- Fabrication
- Marketplace
- Procurement
---
