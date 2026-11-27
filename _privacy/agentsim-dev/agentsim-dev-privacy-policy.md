---
api_specs:
- filename: agentsim-dev-agents-api-openapi.yml
  format: yaml
  label: AgentSIM Agents API
  slug: agentsim-dev-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentsim-dev/openapi/agentsim-dev-agents-api-openapi.yml
- filename: agentsim-dev-browser-access-api-openapi.yml
  format: yaml
  label: AgentSIM Browser Access API
  slug: agentsim-dev-browser-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentsim-dev/openapi/agentsim-dev-browser-access-api-openapi.yml
- filename: agentsim-dev-sessions-api-openapi.yml
  format: yaml
  label: AgentSIM Sessions API
  slug: agentsim-dev-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentsim-dev/openapi/agentsim-dev-sessions-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data, including your name, email address, and authentication records
  - category: financial
    text: Billing records processed with Stripe; AgentSIM does not store full card details
  - category: behavioral
    text: Usage and session data, including requests, counts, timestamps, outcomes, and agent identifiers
  - category: communication
    text: Challenge data needed to operate a session, which may include phone numbers, message content, one-time codes, delivery metadata, and verdicts
  - category: communication
    text: Support messages and product feedback you send us
  - category: device
    text: Security and access data such as IP address, browser type, referring URL, and server logs
  deletion:
    route: email request
    text: To make a request, email contact@agentsim.dev
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, secure, and troubleshoot the service
    text: Provide, secure, and troubleshoot the service
  - purpose: Run requested challenges
    text: Run requested challenges and return their outcomes
  - purpose: Process payments and transactional messages
    text: Process payments and send transactional messages
  - purpose: Improve the product with consent
    text: Improve the product when you consent to optional browser analytics
  - purpose: Legal obligations and disputes
    text: Meet legal obligations and resolve disputes
  retention:
  - period: up to 90 days
    scope: API request logs
    text: API request logs are retained for up to 90 days.
  - period: null
    scope: Account data
    text: We retain account data while your account is active.
  - period: 30 days
    scope: Personal data after account deletion
    text: we aim to remove personal data within 30 days unless continued retention is required or permitted by law
  rights:
  - right: access, correct, delete, restrict, or copy
    text: you may have rights to access, correct, delete, restrict, or receive a copy of your personal data
  - right: withdraw analytics consent
    text: You can withdraw analytics consent at any time without affecting earlier processing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: 'We use service providers for specific parts of AgentSIM:'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentSIM
provenance_date: '2026-11-09'
provider_name: AgentSIM
provider_slug: agentsim-dev
slug: agentsim-dev-privacy-policy
source_date: '2026-11-09'
source_filename: agentsim-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentsim.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentSIM\naid: agentsim-dev\nurl: https://agentsim.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account data, including your name, email address, and authentication records\n- category: financial\n  text: Billing records processed with Stripe; AgentSIM does not store full card details\n- category: behavioral\n  text: Usage and session data, including requests, counts, timestamps, outcomes, and agent identifiers\n- category: communication\n  text: Challenge data needed to operate a session, which may include phone numbers,\
  \ message content, one-time codes,\n    delivery metadata, and verdicts\n- category: communication\n  text: Support messages and product feedback you send us\n- category: device\n  text: Security and access data such as IP address, browser type, referring URL, and server logs\npurposes:\n- purpose: Provide, secure, and troubleshoot the service\n  text: Provide, secure, and troubleshoot the service\n- purpose: Run requested challenges\n  text: Run requested challenges and return their outcomes\n- purpose: Process payments and transactional messages\n  text: Process payments and send transactional messages\n- purpose: Improve the product with consent\n  text: Improve the product when you consent to optional browser analytics\n- purpose: Legal obligations and disputes\n  text: Meet legal obligations and resolve disputes\nretention:\n- scope: API request logs\n  period: up to 90 days\n  text: API request logs are retained for up to 90 days.\n- scope: Account data\n  period: null\n  text: We\
  \ retain account data while your account is active.\n- scope: Personal data after account deletion\n  period: 30 days\n  text: we aim to remove personal data within 30 days unless continued retention is required or permitted by law\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We use service providers for specific parts of AgentSIM:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: To make a request, email contact@agentsim.dev\nrights:\n- right: access, correct, delete, restrict, or copy\n  text: you may have rights to access, correct, delete, restrict, or receive a copy of your personal data\n- right: withdraw analytics consent\n  text: You can withdraw analytics consent at any time without affecting earlier processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/agentsim-dev/privacy/agentsim-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from AgentSIM's own page on 2026-11-09.
synthetic: false
tags:
- AgentSIM
- Authentication
- Identity
- Security
---
