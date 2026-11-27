---
api_specs:
- filename: anha-ai-openapi-generated.yml
  format: yaml
  label: ANHA Registry API
  slug: anha-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anha-ai/openapi/_ae-authored/anha-ai-openapi-generated.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address (handle owner)
  - category: identifying
    text: Proving you own a handle, so only you can approve an agent's access to it or change its settings.
  - category: communication
    text: Email and phone identity bindings
  - category: device
    text: Registration attempts (email, IP, browser fingerprint)
  - category: financial
    text: Payment records
  deletion:
    route: Written request to ANHA contact address
    text: Ask for a copy or deletion of your account data — write to us at the address below.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: handle ownership proof
    text: Proving you own a handle, so only you can approve an agent's access to it or change its settings.
  - purpose: agent access
    text: Letting an AI agent you approved call ANHA on your behalf.
  - purpose: anti-abuse
    text: Preventing automated abuse of the registration flow.
  - purpose: payment
    text: Charging for a handle registration or renewal.
  - purpose: discovery
    text: Letting someone who knows your email or phone number find your handle — only if you opted in.
  retention:
  - period: 1 hour
    scope: OAuth access tokens
    text: 1 hour, then automatically expired.
  - period: 30 days
    scope: OAuth refresh tokens
    text: 30 days, or until you disconnect the agent.
  - period: 30 days
    scope: Registered AI client records
    text: 30 days from registration.
  - period: null
    scope: Email and phone identity bindings
    text: Until you remove the binding.
  - period: null
    scope: Payment records
    text: As required for tax and accounting.
  rights:
  - right: access or deletion
    text: Ask for a copy or deletion of your account data — write to us at the address below.
  - right: disconnect agent
    text: Disconnect an agent — from your dashboard, at any time.
  - right: remove identity binding
    text: Remove an identity binding — stops email or phone discovery.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, and we do not share it for advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ANHA Registry
provenance_date: '2026-11-09'
provider_name: ANHA Registry
provider_slug: anha-ai
slug: anha-ai-privacy-policy
source_date: '2026-11-09'
source_filename: anha-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://anha.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ANHA Registry\naid: anha-ai\nurl: https://anha.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email address (handle owner)\n- category: identifying\n  text: Proving you own a handle, so only you can approve an agent's access to it or change its settings.\n- category: communication\n  text: Email and phone identity bindings\n- category: device\n  text: Registration attempts (email, IP, browser fingerprint)\n- category: financial\n  text: Payment records\npurposes:\n- purpose: handle ownership proof\n  text: Proving you own a handle,\
  \ so only you can approve an agent's access to it or change its settings.\n- purpose: agent access\n  text: Letting an AI agent you approved call ANHA on your behalf.\n- purpose: anti-abuse\n  text: Preventing automated abuse of the registration flow.\n- purpose: payment\n  text: Charging for a handle registration or renewal.\n- purpose: discovery\n  text: Letting someone who knows your email or phone number find your handle — only if you opted in.\nretention:\n- scope: OAuth access tokens\n  period: 1 hour\n  text: 1 hour, then automatically expired.\n- scope: OAuth refresh tokens\n  period: 30 days\n  text: 30 days, or until you disconnect the agent.\n- scope: Registered AI client records\n  period: 30 days\n  text: 30 days from registration.\n- scope: Email and phone identity bindings\n  period: null\n  text: Until you remove the binding.\n- scope: Payment records\n  period: null\n  text: As required for tax and accounting.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n\
  \  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Written request to ANHA contact address\n  text: Ask for a copy or deletion of your account data — write to us at the address below.\nrights:\n- right: access or deletion\n  text: Ask for a copy or deletion of your account data — write to us at the address below.\n- right: disconnect agent\n  text: Disconnect an agent — from your dashboard, at any time.\n- right: remove identity binding\n  text: Remove an identity binding — stops email or phone discovery.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, and we do not share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/anha-ai/privacy/anha-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from ANHA Registry's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Security
- Zero Trust
- Post-Quantum
- Identity
---
