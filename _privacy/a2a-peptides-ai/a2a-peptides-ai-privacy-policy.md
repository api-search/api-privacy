---
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: contact addresses
  - category: contact
    text: the email address and message you send
  - category: financial
    text: x402 settlements produce a signed receipt (amount, asset, network, payer address, transaction hash, decision)
  - category: other
    text: method, path, status, timing — no message bodies
  deletion:
    route: email mcp@a2a-peptides.ai
    text: mcp@a2a-peptides.ai for anything about the data held on you or your organisation
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: trade records
    text: Records exist to answer the trade and to show why an answer was given.
  - purpose: answer contact-form messages
    text: Contact-form submissions are delivered to the operator by the form provider and used only to answer you.
  residency:
  - region: South Central US
    text: All A2A Peptides compute runs in the South Central US region on Microsoft Azure
  retention:
  - period: 30 days
    scope: origin console logs
    text: 'Origin console logs: 30 days (the configured retention of the log workspace).'
  - period: 7 days
    scope: database backups
    text: 'Database backups: 7 days (the configured backup retention).'
  - period: no automatic expiry is configured
    scope: x402 receipts, agent registrations and audit entries
    text: no automatic expiry is configured
  - period: until answered and filed
    scope: contact-form submissions
    text: Contact-form submissions are kept by the form provider and by the operator's mailbox until answered and filed.
  rights:
  - right: access, correction and removal
    text: what is held, a correction, or removal of a registration
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Cloudflare (the edge network in front of every zone: DNS, TLS, caching and request handling)'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: A2A Peptides
provenance_date: '2026-11-09'
provider_name: A2A Peptides
provider_slug: a2a-peptides-ai
slug: a2a-peptides-ai-privacy-policy
source_date: '2026-11-09'
source_filename: a2a-peptides-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://a2a-peptides.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: A2A Peptides\naid: a2a-peptides-ai\nurl: https://a2a-peptides.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: contact addresses\n- category: contact\n  text: the email address and message you send\n- category: financial\n  text: x402 settlements produce a signed receipt (amount, asset, network, payer address, transaction hash, decision)\n- category: other\n  text: method, path, status, timing — no message bodies\npurposes:\n- purpose: trade records\n  text: Records exist to answer the trade and to show why an answer was given.\n\
  - purpose: answer contact-form messages\n  text: Contact-form submissions are delivered to the operator by the form provider and used only to answer you.\nretention:\n- scope: origin console logs\n  period: 30 days\n  text: 'Origin console logs: 30 days (the configured retention of the log workspace).'\n- scope: database backups\n  period: 7 days\n  text: 'Database backups: 7 days (the configured backup retention).'\n- scope: x402 receipts, agent registrations and audit entries\n  period: no automatic expiry is configured\n  text: no automatic expiry is configured\n- scope: contact-form submissions\n  period: until answered and filed\n  text: Contact-form submissions are kept by the form provider and by the operator's mailbox until answered and\n    filed.\nresidency:\n- region: South Central US\n  text: All A2A Peptides compute runs in the South Central US region on Microsoft Azure\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Cloudflare (the edge network in front of every zone:\
  \ DNS, TLS, caching and request handling)'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email mcp@a2a-peptides.ai\n  text: mcp@a2a-peptides.ai for anything about the data held on you or your organisation\nrights:\n- right: access, correction and removal\n  text: what is held, a correction, or removal of a registration\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/a2a-peptides-ai/privacy/a2a-peptides-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
summary_line: 14 quoted statements, read from A2A Peptides's own page on 2026-11-09.
synthetic: false
tags:
- Peptides
- Agentic Commerce
- MCP
- Artificial Intelligence
- LicensedTrade
---
