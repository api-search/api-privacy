---
api_specs:
- filename: chatterlab-ai-openapi-generated.yml
  format: yaml
  label: ChatterLab API
  slug: chatterlab-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chatterlab-ai/openapi/_ae-authored/chatterlab-ai-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address and sign-in identity, held by our authentication provider
  - category: behavioral
    text: Every message a visitor sends and every answer an agent gives, with the model used, the passages it drew on, a confidence score and any rating the visitor left.
  - category: financial
    text: Card details never reach us; they are handled by our payment provider.
  deletion:
    route: Customer deletes the source, agent, or account; visitors ask the website they were talking to
    text: Knowledge and conversations stay until the customer deletes the source, the agent, or the account
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Carry out the service
    text: We send them to carry out the service you signed up for
  - purpose: Statistics on website with consent
    text: 'Google Analytics to count visits: which pages are read, where visitors come from and roughly where they are.'
  - purpose: Abuse protection
    text: The public chat endpoints are rate-limited per visitor address.
  residency:
  - region: EU
    text: 'Database and files: Neon (Postgres) and Cloudflare R2, both in EU regions with the EU jurisdiction setting on storage.'
  - region: Frankfurt
    text: 'Hosting: Vercel, in Frankfurt.'
  retention:
  - period: 30 days
    scope: Files visitors send
    text: kept for 30 days
  - period: 3 years
    scope: Contact details visitors leave
    text: kept for 3 years
  - period: 7 days
    scope: Webhook payloads
    text: What is sent is kept for 7 days
  - period: 24 months
    scope: Audit trail
    text: kept for 24 months
  - period: null
    scope: Rate-limit hashes
    text: Only a fingerprint of the address is stored, for one day.
  rights:
  - right: access
    text: you can ask what we hold about you
  - right: rectification
    text: have it corrected or deleted
  - right: portability
    text: receive a copy
  - right: objection and restriction
    text: object to or restrict its processing
  - right: complaint
    text: Anyone can also complain to their national data-protection authority.
  role:
    text: The controller for the data described here is SRI Group BV
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Who processes it Hosting: Vercel, in Frankfurt.'
    url: null
  transfers:
  - mechanism: SCC
    text: Its data processing agreement includes the EU Standard Contractual Clauses and an EU-only processing addendum, which we have elected.
  - mechanism: DPF
    text: Resend processes mail in the United States, under the EU-US Data Privacy Framework and standard contractual clauses;
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ChatterLab
provenance_date: '2026-11-09'
provider_name: ChatterLab
provider_slug: chatterlab-ai
slug: chatterlab-ai-privacy-policy
source_date: '2026-11-09'
source_filename: chatterlab-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://chatterlab.ai/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ChatterLab\naid: chatterlab-ai\nurl: https://chatterlab.ai/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: The controller for the data described here is SRI Group BV\ndata_categories:\n- category: identifying\n  text: Your name, email address and sign-in identity, held by our authentication provider\n- category: behavioral\n  text: Every message a visitor sends and every answer an agent gives, with the model used, the passages it drew\n    on, a confidence score and any rating the visitor left.\n- category: financial\n  text: Card details never reach us; they are handled by our payment\
  \ provider.\npurposes:\n- purpose: Carry out the service\n  text: We send them to carry out the service you signed up for\n- purpose: Statistics on website with consent\n  text: 'Google Analytics to count visits: which pages are read, where visitors come from and roughly where they\n    are.'\n- purpose: Abuse protection\n  text: The public chat endpoints are rate-limited per visitor address.\nretention:\n- scope: Files visitors send\n  period: 30 days\n  text: kept for 30 days\n- scope: Contact details visitors leave\n  period: 3 years\n  text: kept for 3 years\n- scope: Webhook payloads\n  period: 7 days\n  text: What is sent is kept for 7 days\n- scope: Audit trail\n  period: 24 months\n  text: kept for 24 months\n- scope: Rate-limit hashes\n  period: null\n  text: Only a fingerprint of the address is stored, for one day.\nresidency:\n- region: EU\n  text: 'Database and files: Neon (Postgres) and Cloudflare R2, both in EU regions with the EU jurisdiction setting\n    on storage.'\n\
  - region: Frankfurt\n  text: 'Hosting: Vercel, in Frankfurt.'\ntransfers:\n- mechanism: SCC\n  text: Its data processing agreement includes the EU Standard Contractual Clauses and an EU-only processing addendum,\n    which we have elected.\n- mechanism: DPF\n  text: Resend processes mail in the United States, under the EU-US Data Privacy Framework and standard contractual\n    clauses;\nsubprocessors:\n  url: null\n  text: 'Who processes it Hosting: Vercel, in Frankfurt.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Customer deletes the source, agent, or account; visitors ask the website they were talking to\n  text: Knowledge and conversations stay until the customer deletes the source, the agent, or the account\nrights:\n- right: access\n  text: you can ask what we hold about you\n- right: rectification\n  text: have it corrected or deleted\n- right: portability\n  text: receive a copy\n- right: objection and restriction\n  text: object to or restrict its\
  \ processing\n- right: complaint\n  text: Anyone can also complain to their national data-protection authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chatterlab-ai/privacy/chatterlab-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 23 quoted statements, read from ChatterLab's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Chatbots
- GDPR
- European
- Software-as-a-Service
- Company
---
