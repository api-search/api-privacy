---
claim_count: 13
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Contact-form and claim-form submissions: the email address and message you send.'
  - category: identifying
    text: 'Agent registration details: what an agent sends to the issuer at a2a-registry.ai/oauth/register (client name, client URI, contact addresses, actor class, market)'
  - category: financial
    text: x402 settlements produce a signed receipt (amount, asset, network, payer address, transaction hash, decision).
  - category: other
    text: 'Request logs: the edge network keeps standard request records for security and capacity'
  deletion:
    route: Email request to the operator
    text: '[email protected] for anything about the data held on you or your organisation'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Answer the trade and show why an answer was given
    text: Records exist to answer the trade and to show why an answer was given.
  - purpose: Answer form submitters
    text: Form submissions are delivered by the form provider and used only to answer you.
  residency:
  - region: France Central
    text: The door, the record store and the receipt store run in the France Central region (Paris) on Microsoft Azure
  - region: South Central US
    text: the issuer runs in the South Central US region
  retention:
  - period: 30 days
    scope: Origin console logs
    text: 30 days on the sibling hubs, read 2026-09-21; this hub's workspace is read at its first roll
  - period: null
    scope: x402 receipts, audit entries and review packs
    text: No retention period is configured on either — no lifecycle policy, soft delete off — so they are kept until the operator removes them.
  - period: null
    scope: Form submissions
    text: Form submissions are kept by the form provider and the operator's mailbox until deleted.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Cloudflare (the edge network: DNS, TLS, caching and request handling); Microsoft Azure (compute and storage); Formspree (delivery of form submissions)'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: A2A Grocery
provenance_date: '2026-11-09'
provider_name: A2A Grocery
provider_slug: a2a-grocery-ai
slug: a2a-grocery-ai-privacy-policy
source_date: '2026-11-09'
source_filename: a2a-grocery-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://a2a-grocery.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: A2A Grocery\naid: a2a-grocery-ai\nurl: https://a2a-grocery.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Contact-form and claim-form submissions: the email address and message you send.'\n- category: identifying\n  text: 'Agent registration details: what an agent sends to the issuer at a2a-registry.ai/oauth/register (client\n    name, client URI, contact addresses, actor class, market)'\n- category: financial\n  text: x402 settlements produce a signed receipt (amount, asset, network, payer address, transaction hash, decision).\n\
  - category: other\n  text: 'Request logs: the edge network keeps standard request records for security and capacity'\npurposes:\n- purpose: Answer the trade and show why an answer was given\n  text: Records exist to answer the trade and to show why an answer was given.\n- purpose: Answer form submitters\n  text: Form submissions are delivered by the form provider and used only to answer you.\nretention:\n- scope: Origin console logs\n  period: 30 days\n  text: 30 days on the sibling hubs, read 2026-09-21; this hub's workspace is read at its first roll\n- scope: x402 receipts, audit entries and review packs\n  period: null\n  text: No retention period is configured on either — no lifecycle policy, soft delete off — so they are kept until\n    the operator removes them.\n- scope: Form submissions\n  period: null\n  text: Form submissions are kept by the form provider and the operator's mailbox until deleted.\nresidency:\n- region: France Central\n  text: The door, the record store and the\
  \ receipt store run in the France Central region (Paris) on Microsoft Azure\n- region: South Central US\n  text: the issuer runs in the South Central US region\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Cloudflare (the edge network: DNS, TLS, caching and request handling); Microsoft Azure (compute and storage);\n    Formspree (delivery of form submissions)'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to the operator\n  text: '[email protected] for anything about the data held on you or your organisation'\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/a2a-grocery-ai/privacy/a2a-grocery-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
summary_line: 13 quoted statements, read from A2A Grocery's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Grocery
- Procurement
- Agents
- Marketplace
---
