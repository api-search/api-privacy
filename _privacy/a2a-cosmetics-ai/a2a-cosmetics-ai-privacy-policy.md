---
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Contact-form and claim-form submissions: the email address and message you send.'
  - category: financial
    text: x402 settlements produce a signed receipt (amount, asset, network, payer address, transaction hash, decision).
  - category: other
    text: 'Request logs: the edge network keeps standard request records for security and capacity'
  - category: professional
    text: 'Agent registration details: what an agent sends to the issuer at a2a-registry.ai/oauth/register (client name, client URI, contact addresses, actor class, market)'
  deletion:
    route: contact email
    text: for anything about the data held on you or your organisation, or the contact form on this site.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: answer the trade and show why an answer was given
    text: Records exist to answer the trade and to show why an answer was given.
  - purpose: no advertising, profiling or marketing
    text: Nothing is used for advertising, profiling or marketing.
  - purpose: answer form submitters
    text: Form submissions are delivered by the form provider and used only to answer you.
  residency:
  - region: South Central US
    text: The door, the record store, the issuer and the receipt store run in the South Central US region on Microsoft Azure;
  - region: market agent regions
    text: each market agent answers from its own Azure region.
  retention:
  - period: 30 days
    scope: origin console logs
    text: 'Origin console logs (method, path, status, timing — no bodies): 30 days, the retention set on the Log Analytics workspace that receives them.'
  - period: null
    scope: x402 receipts, agent registrations, audit entries, review packs
    text: no retention period is configured there — no lifecycle policy, soft delete off — so they are kept until the operator removes them.
  - period: until deleted
    scope: form submissions
    text: Form submissions are kept by the form provider and the operator's mailbox until deleted.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Cloudflare (the edge network: DNS, TLS, caching and request handling); Microsoft Azure (compute and storage); Formspree (delivery of form submissions);'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: A2A Cosmetics
provenance_date: '2026-11-09'
provider_name: A2A Cosmetics
provider_slug: a2a-cosmetics-ai
slug: a2a-cosmetics-ai-privacy-policy
source_date: '2026-11-09'
source_filename: a2a-cosmetics-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://a2a-cosmetics.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: A2A Cosmetics\naid: a2a-cosmetics-ai\nurl: https://a2a-cosmetics.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Contact-form and claim-form submissions: the email address and message you send.'\n- category: financial\n  text: x402 settlements produce a signed receipt (amount, asset, network, payer address, transaction hash, decision).\n- category: other\n  text: 'Request logs: the edge network keeps standard request records for security and capacity'\n- category: professional\n  text: 'Agent registration details: what an agent\
  \ sends to the issuer at a2a-registry.ai/oauth/register (client\n    name, client URI, contact addresses, actor class, market)'\npurposes:\n- purpose: answer the trade and show why an answer was given\n  text: Records exist to answer the trade and to show why an answer was given.\n- purpose: no advertising, profiling or marketing\n  text: Nothing is used for advertising, profiling or marketing.\n- purpose: answer form submitters\n  text: Form submissions are delivered by the form provider and used only to answer you.\nretention:\n- scope: origin console logs\n  period: 30 days\n  text: 'Origin console logs (method, path, status, timing — no bodies): 30 days, the retention set on the Log Analytics\n    workspace that receives them.'\n- scope: x402 receipts, agent registrations, audit entries, review packs\n  period: null\n  text: no retention period is configured there — no lifecycle policy, soft delete off — so they are kept until\n    the operator removes them.\n- scope: form submissions\n\
  \  period: until deleted\n  text: Form submissions are kept by the form provider and the operator's mailbox until deleted.\nresidency:\n- region: South Central US\n  text: The door, the record store, the issuer and the receipt store run in the South Central US region on Microsoft\n    Azure;\n- region: market agent regions\n  text: each market agent answers from its own Azure region.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Cloudflare (the edge network: DNS, TLS, caching and request handling); Microsoft Azure (compute and storage);\n    Formspree (delivery of form submissions);'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact email\n  text: for anything about the data held on you or your organisation, or the contact form on this site.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/a2a-cosmetics-ai/privacy/a2a-cosmetics-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
summary_line: 14 quoted statements, read from A2A Cosmetics's own page on 2026-11-09.
synthetic: false
tags:
- Cosmetics
- Artificial Intelligence
- AI Agents
- Commerce
- GTIN
---
