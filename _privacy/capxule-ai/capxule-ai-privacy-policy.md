---
api_specs:
- filename: capxule-ai-account-api-openapi.yml
  format: yaml
  label: Capxule Account API
  slug: capxule-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capxule-ai/openapi/capxule-ai-account-api-openapi.yml
- filename: capxule-ai-catalog-api-openapi.yml
  format: yaml
  label: Capxule Catalog API
  slug: capxule-ai-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capxule-ai/openapi/capxule-ai-catalog-api-openapi.yml
- filename: capxule-ai-plan-api-openapi.yml
  format: yaml
  label: Capxule Plan API
  slug: capxule-ai-plan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capxule-ai/openapi/capxule-ai-plan-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account we collect your name, email address, and authentication credentials (password hash or Google OAuth token).
  - category: financial
    text: When you make a purchase we collect payment information processed securely through Stripe - we never store your full card number.
  - category: device
    text: basic request data such as your IP address
  - category: communication
    text: your questions and choices for a journey, the name of the assistant, a technical connection identifier
  deletion:
    route: contact hello@capxule.com or account settings
    text: You may request deletion of your account and associated data at any time by contacting us at hello@capxule.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and improve service
    text: We use your information to provide and improve the Capxule service, process transactions, send transactional emails, and maintain account security.
  - purpose: compose answers
    text: It is used on our servers to compose the answers you, or an AI assistant acting for you, ask for.
  - purpose: analytics
    text: We also use Google Analytics to understand how the service is used.
  retention:
  - period: null
    scope: account data and conversations
    text: We retain your account data, conversations and journey progress for as long as your account is active.
  - period: 7 days
    scope: guest sessions
    text: Guest sessions (when you try a journey without an account, on our website or through an AI assistant) expire after 7 days and are then deleted, unless you connect them to an account.
  rights:
  - right: access, correct, export, delete
    text: You can access, correct, export or delete your personal data, and withdraw any consent you have given, by contacting us at hello@capxule.com or through your account settings.
  - right: object or restrict processing, complain to authority
    text: including the right to object to or restrict certain processing and to lodge a complaint with a data protection authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Capxule
provenance_date: '2026-11-09'
provider_name: Capxule
provider_slug: capxule-ai
slug: capxule-ai-privacy-policy
source_date: '2026-11-09'
source_filename: capxule-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://capxule.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Capxule\naid: capxule-ai\nurl: https://capxule.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account we collect your name, email address, and authentication credentials (password\n    hash or Google OAuth token).\n- category: financial\n  text: When you make a purchase we collect payment information processed securely through Stripe - we never store\n    your full card number.\n- category: device\n  text: basic request data such as your IP address\n- category: communication\n  text: your questions and choices\
  \ for a journey, the name of the assistant, a technical connection identifier\npurposes:\n- purpose: provide and improve service\n  text: We use your information to provide and improve the Capxule service, process transactions, send transactional\n    emails, and maintain account security.\n- purpose: compose answers\n  text: It is used on our servers to compose the answers you, or an AI assistant acting for you, ask for.\n- purpose: analytics\n  text: We also use Google Analytics to understand how the service is used.\nretention:\n- scope: account data and conversations\n  period: null\n  text: We retain your account data, conversations and journey progress for as long as your account is active.\n- scope: guest sessions\n  period: 7 days\n  text: Guest sessions (when you try a journey without an account, on our website or through an AI assistant) expire\n    after 7 days and are then deleted, unless you connect them to an account.\nresidency: []\ntransfers: []\nsubprocessors:\n  url:\
  \ null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact hello@capxule.com or account settings\n  text: You may request deletion of your account and associated data at any time by contacting us at hello@capxule.com.\nrights:\n- right: access, correct, export, delete\n  text: You can access, correct, export or delete your personal data, and withdraw any consent you have given, by\n    contacting us at hello@capxule.com or through your account settings.\n- right: object or restrict processing, complain to authority\n  text: including the right to object to or restrict certain processing and to lodge a complaint with a data protection\n    authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/capxule-ai/privacy/capxule-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from Capxule's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Context Marketplace
- Artificial Intelligence
- AI Agents
- MCP
- Education
- Test Preparation
- Knowledge
---
