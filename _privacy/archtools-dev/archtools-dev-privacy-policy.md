---
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address — required for registration, verification, and account communication
  - category: identifying
    text: API key (hashed) — your key is stored only as a bcrypt hash ; we cannot read the key itself.
  - category: behavioral
    text: Usage metadata — per-request logs of tool name, timestamp, response status, and credit cost.
  - category: device
    text: IP address — processed for rate limiting, signup abuse prevention, and security
  - category: financial
    text: If you pay via x402 crypto micropayments, we record your sending wallet address, on-chain transaction hash, USDC amount, and network for credit attribution, billing, and fraud prevention.
  - category: professional
    text: the agent metadata you provide (name, description, capabilities, contact)
  deletion:
    route: Self-service DELETE /v1/agent with API key and confirmation body, or email request
    text: You can delete your account and personal data yourself, without waiting on support
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate account and API
    text: Operate your account, authenticate API calls, meter and bill credits, send transactional email
  - purpose: Security and abuse prevention
    text: Rate limiting, abuse and fraud prevention, signup-farming protection, security logging, prompt-moderation logging
  - purpose: Tax and accounting
    text: Retaining anonymized purchase and payment records after account deletion
  - purpose: Marketing email
    text: Newsletter / marketing email
  - purpose: Aggregate analytics
    text: Aggregate, anonymized analytics (e.g. the public stats dashboard)
  residency:
  - region: United States
    text: we are a US company and process data in the United States.
  retention:
  - period: null
    scope: Account data and usage logs
    text: Account data and usage logs — retained while your account is active
  - period: no later than 4 hours after session creation
    scope: Session data
    text: Session data — in-memory only, deleted no later than 4 hours after session creation
  - period: as long as tax and accounting law requires
    scope: Financial records
    text: Financial records (Stripe purchases, x402 payment rows) — retained in anonymized form for as long as tax and accounting law requires
  - period: null
    scope: Directory listings
    text: Directory listings — retained until you request removal or your account is terminated
  rights:
  - right: access
    text: access the data we hold about you
  - right: correct
    text: correct inaccurate data
  - right: delete
    text: delete your account and off-chain data (Section 8)
  - right: export
    text: export your data in a portable format
  - right: restriction and objection (EEA/UK)
    text: the rights of restriction of processing and objection
  - right: complaint to supervisory authority
    text: the right to lodge a complaint with your local supervisory authority
  - right: opt out of non-transactional communications
    text: opt out of non-transactional communications
  role:
    text: the data controller for the personal data described here
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal data as defined by the CCPA
  subprocessors:
    text: our current provider list is published at /subprocessors
    url: /subprocessors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: archtools-dev
provenance_date: '2026-11-09'
provider_name: archtools-dev
provider_slug: archtools-dev
slug: archtools-dev-privacy-policy
source_date: '2026-11-09'
source_filename: archtools-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://archtools.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: archtools-dev\naid: archtools-dev\nurl: https://archtools.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: the data controller for the personal data described here\ndata_categories:\n- category: contact\n  text: Email address — required for registration, verification, and account communication\n- category: identifying\n  text: API key (hashed) — your key is stored only as a bcrypt hash ; we cannot read the key itself.\n- category: behavioral\n  text: Usage metadata — per-request logs of tool name, timestamp, response status, and credit cost.\n- category: device\n  text: IP address\
  \ — processed for rate limiting, signup abuse prevention, and security\n- category: financial\n  text: If you pay via x402 crypto micropayments, we record your sending wallet address, on-chain transaction hash,\n    USDC amount, and network for credit attribution, billing, and fraud prevention.\n- category: professional\n  text: the agent metadata you provide (name, description, capabilities, contact)\npurposes:\n- purpose: Operate account and API\n  text: Operate your account, authenticate API calls, meter and bill credits, send transactional email\n- purpose: Security and abuse prevention\n  text: Rate limiting, abuse and fraud prevention, signup-farming protection, security logging, prompt-moderation\n    logging\n- purpose: Tax and accounting\n  text: Retaining anonymized purchase and payment records after account deletion\n- purpose: Marketing email\n  text: Newsletter / marketing email\n- purpose: Aggregate analytics\n  text: Aggregate, anonymized analytics (e.g. the public stats\
  \ dashboard)\nretention:\n- scope: Account data and usage logs\n  period: null\n  text: Account data and usage logs — retained while your account is active\n- scope: Session data\n  period: no later than 4 hours after session creation\n  text: Session data — in-memory only, deleted no later than 4 hours after session creation\n- scope: Financial records\n  period: as long as tax and accounting law requires\n  text: Financial records (Stripe purchases, x402 payment rows) — retained in anonymized form for as long as tax\n    and accounting law requires\n- scope: Directory listings\n  period: null\n  text: Directory listings — retained until you request removal or your account is terminated\nresidency:\n- region: United States\n  text: we are a US company and process data in the United States.\ntransfers: []\nsubprocessors:\n  url: /subprocessors\n  text: our current provider list is published at /subprocessors\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Self-service\
  \ DELETE /v1/agent with API key and confirmation body, or email request\n  text: You can delete your account and personal data yourself, without waiting on support\nrights:\n- right: access\n  text: access the data we hold about you\n- right: correct\n  text: correct inaccurate data\n- right: delete\n  text: delete your account and off-chain data (Section 8)\n- right: export\n  text: export your data in a portable format\n- right: restriction and objection (EEA/UK)\n  text: the rights of restriction of processing and objection\n- right: complaint to supervisory authority\n  text: the right to lodge a complaint with your local supervisory authority\n- right: opt out of non-transactional communications\n  text: opt out of non-transactional communications\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal data as defined by the CCPA\n"
source_yaml_url: https://artifacts.apis.io/archtools-dev/privacy/archtools-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from archtools-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Tools
- Automation
- MCP
---
