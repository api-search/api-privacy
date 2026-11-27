---
api_specs:
- filename: aaly-io-openapi-generated.yml
  format: yaml
  label: Aaly API
  slug: aaly-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aaly-io/openapi/_ae-authored/aaly-io-openapi-generated.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your name, email address, and authentication credentials
  - category: device
    text: IP addresses, timestamps, device/browser metadata, and error or debugging logs
  - category: financial
    text: billing details (such as name, billing address, and card details) are collected and processed by our payment processor
  - category: behavioral
    text: API requests, MCP tool calls, dashboard actions
  deletion:
    route: email security@aaly.io
    text: You can request deletion at any time — see Contact below.
  dpa:
    available: true
    text: a Data Processing Addendum on request
    url: null
  purposes:
  - purpose: operate platform
    text: To operate and provide the platform — provisioning and running the backends and APIs generated from your schema
  - purpose: security and debugging
    text: For security, debugging, and reliability — detecting abuse, rate limiting, diagnosing incidents, and maintaining uptime.
  - purpose: communications
    text: To communicate with you — service updates, security notices, and, if you opt in, product updates.
  retention:
  - period: null
    scope: account and project data
    text: We retain account and project data for as long as your account is active.
  - period: 30 days
    scope: deleted project data
    text: If you delete a project, its schema, configuration, and associated backend data are deleted within 30 days
  - period: up to 12 months
    scope: operational logs
    text: Operational logs are retained for a limited period (typically up to 12 months)
  rights:
  - right: access, correct, export, delete
    text: you may have the right to access, correct, export, or delete the personal data we hold about you
  - right: object or restrict
    text: to object to or restrict some of our processing
  role:
    text: Where applicable law treats you as the data controller for your end users' information and AALY as a processor or service provider, our processing of it is governed by the AALY Terms of Service
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell this data, use it for advertising, or use it to train our own or third-party AI models.
  subprocessors:
    text: 'We rely on a limited set of infrastructure and service providers to run AALY: Amazon Web Services (AWS).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Aaly
provenance_date: '2026-11-09'
provider_name: Aaly
provider_slug: aaly-io
slug: aaly-io-privacy-policy
source_date: '2026-11-09'
source_filename: aaly-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aaly.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Aaly\naid: aaly-io\nurl: https://aaly.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Where applicable law treats you as the data controller for your end users' information and AALY as a processor\n    or service provider, our processing of it is governed by the AALY Terms of Service\ndata_categories:\n- category: identifying\n  text: we collect your name, email address, and authentication credentials\n- category: device\n  text: IP addresses, timestamps, device/browser metadata, and error or debugging logs\n- category: financial\n  text: billing details (such as name, billing address,\
  \ and card details) are collected and processed by our payment\n    processor\n- category: behavioral\n  text: API requests, MCP tool calls, dashboard actions\npurposes:\n- purpose: operate platform\n  text: To operate and provide the platform — provisioning and running the backends and APIs generated from your\n    schema\n- purpose: security and debugging\n  text: For security, debugging, and reliability — detecting abuse, rate limiting, diagnosing incidents, and maintaining\n    uptime.\n- purpose: communications\n  text: To communicate with you — service updates, security notices, and, if you opt in, product updates.\nretention:\n- scope: account and project data\n  period: null\n  text: We retain account and project data for as long as your account is active.\n- scope: deleted project data\n  period: 30 days\n  text: If you delete a project, its schema, configuration, and associated backend data are deleted within 30 days\n- scope: operational logs\n  period: up to 12 months\n  text:\
  \ Operational logs are retained for a limited period (typically up to 12 months)\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We rely on a limited set of infrastructure and service providers to run AALY: Amazon Web Services (AWS).'\ndpa:\n  available: true\n  url: null\n  text: a Data Processing Addendum on request\ndeletion:\n  route: email security@aaly.io\n  text: You can request deletion at any time — see Contact below.\nrights:\n- right: access, correct, export, delete\n  text: you may have the right to access, correct, export, or delete the personal data we hold about you\n- right: object or restrict\n  text: to object to or restrict some of our processing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell this data, use it for advertising, or use it to train our own or third-party AI models.\n"
source_yaml_url: https://artifacts.apis.io/aaly-io/privacy/aaly-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Aaly's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Backend
- Multi-Tenant
- Software-as-a-Service
- Platform
---
