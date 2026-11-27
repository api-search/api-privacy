---
api_specs:
- filename: brewmypdf-com-openapi-generated.yml
  format: yaml
  label: BrewMyPDF API
  slug: brewmypdf-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brewmypdf-com/openapi/_ae-authored/brewmypdf-com-openapi-generated.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, password (hashed)
  - category: device
    text: IP address, User-Agent
  - category: financial
    text: Billing details
  - category: communication
    text: Support messages — the reply address, subject and body you write, plus your account and plan if you were signed in
  - category: behavioral
    text: Usage records (counts, sizes, timestamps)
  deletion:
    route: Delete your account from Settings
    text: Erasure — delete your account from Settings; this removes your data from our database and object storage, and we confirm when it is done.
  dpa:
    available: true
    text: as set out in the DPA
    url: https://brewmypdf.com/legal/dpa
  purposes:
  - purpose: Create and secure your account
    text: Create and secure your account
  - purpose: Authenticate API requests
    text: Authenticate API requests
  - purpose: Security and abuse prevention
    text: Security, abuse prevention, audit records
  - purpose: Enforce plan limits and billing
    text: Enforce plan limits and bill correctly
  residency:
  - region: United States and elsewhere
    text: the Service runs on Cloudflare's global network, and we and our providers are located in the United States and elsewhere
  retention:
  - period: 7-day schedule
    scope: Generated output
    text: The stored file is deleted on a 7-day schedule
  - period: null
    scope: Request payloads for successful renders
    text: Not stored — deleted as soon as rendering finishes
  - period: 24 hours
    scope: Request payloads for failed renders
    text: 24 hours , so that you can re-run them, then deleted
  - period: null
    scope: Templates and account data
    text: For as long as your account exists
  - period: 30 days
    scope: Audit logs
    text: 30 days in the console. After that a record moves to our internal archive, where it is kept for at most 730 days and then deleted.
  - period: 14 months
    scope: Google Analytics data
    text: 14 months each, then deleted
  - period: 180 days
    scope: Support messages
    text: 180 days , then deleted automatically.
  rights:
  - right: Access
    text: Access — view your data in the console
  - right: Portability
    text: Portability — export templates and settings as JSON from Settings
  - right: Erasure
    text: Erasure — delete your account from Settings
  - right: Restriction or objection
    text: Restriction or objection — write to us
  - right: Correction
    text: you have the rights to know, delete, and correct personal information
  role:
    text: Controller
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information
  subprocessors:
    text: They are listed, with their role and what they process, on our Subprocessors page.
    url: https://brewmypdf.com/legal/subprocessors
  transfers:
  - mechanism: SCC
    text: we rely on the European Commission's Standard Contractual Clauses and, for the UK, the ICO Addendum, as set out in the DPA
  - mechanism: DPF
    text: Google's Standard Contractual Clauses and Data Privacy Framework certification for the transfer
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BrewMyPDF
provenance_date: '2026-11-09'
provider_name: BrewMyPDF
provider_slug: brewmypdf-com
slug: brewmypdf-com-privacy-policy
source_date: '2026-11-09'
source_filename: brewmypdf-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://brewmypdf.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BrewMyPDF\naid: brewmypdf-com\nurl: https://brewmypdf.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Controller\ndata_categories:\n- category: identifying\n  text: Email address, password (hashed)\n- category: device\n  text: IP address, User-Agent\n- category: financial\n  text: Billing details\n- category: communication\n  text: Support messages — the reply address, subject and body you write, plus your account and plan if you were\n    signed in\n- category: behavioral\n  text: Usage records (counts, sizes, timestamps)\npurposes:\n- purpose: Create and secure your account\n\
  \  text: Create and secure your account\n- purpose: Authenticate API requests\n  text: Authenticate API requests\n- purpose: Security and abuse prevention\n  text: Security, abuse prevention, audit records\n- purpose: Enforce plan limits and billing\n  text: Enforce plan limits and bill correctly\nretention:\n- scope: Generated output\n  period: 7-day schedule\n  text: The stored file is deleted on a 7-day schedule\n- scope: Request payloads for successful renders\n  period: null\n  text: Not stored — deleted as soon as rendering finishes\n- scope: Request payloads for failed renders\n  period: 24 hours\n  text: 24 hours , so that you can re-run them, then deleted\n- scope: Templates and account data\n  period: null\n  text: For as long as your account exists\n- scope: Audit logs\n  period: 30 days\n  text: 30 days in the console. After that a record moves to our internal archive, where it is kept for at most\n    730 days and then deleted.\n- scope: Google Analytics data\n  period: 14\
  \ months\n  text: 14 months each, then deleted\n- scope: Support messages\n  period: 180 days\n  text: 180 days , then deleted automatically.\nresidency:\n- region: United States and elsewhere\n  text: the Service runs on Cloudflare's global network, and we and our providers are located in the United States\n    and elsewhere\ntransfers:\n- mechanism: SCC\n  text: we rely on the European Commission's Standard Contractual Clauses and, for the UK, the ICO Addendum, as\n    set out in the DPA\n- mechanism: DPF\n  text: Google's Standard Contractual Clauses and Data Privacy Framework certification for the transfer\nsubprocessors:\n  url: https://brewmypdf.com/legal/subprocessors\n  text: They are listed, with their role and what they process, on our Subprocessors page.\ndpa:\n  available: true\n  url: https://brewmypdf.com/legal/dpa\n  text: as set out in the DPA\ndeletion:\n  route: Delete your account from Settings\n  text: Erasure — delete your account from Settings; this removes your data\
  \ from our database and object storage,\n    and we confirm when it is done.\nrights:\n- right: Access\n  text: Access — view your data in the console\n- right: Portability\n  text: Portability — export templates and settings as JSON from Settings\n- right: Erasure\n  text: Erasure — delete your account from Settings\n- right: Restriction or objection\n  text: Restriction or objection — write to us\n- right: Correction\n  text: you have the rights to know, delete, and correct personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal information\n"
source_yaml_url: https://artifacts.apis.io/brewmypdf-com/privacy/brewmypdf-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from BrewMyPDF's own page on 2026-11-09.
synthetic: false
tags:
- PDF Generation
- Visual Editor
- Templates
- MCP
- Embeddings
---
