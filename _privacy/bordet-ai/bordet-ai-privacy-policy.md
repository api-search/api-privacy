---
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address and either a hashed password or a Google sign-in identity
  - category: contact
    text: Your email address and Google account identifier only
  - category: communication
    text: 'Room content. Everything that goes into a room: your messages, images you attach or generate, sources you add'
  - category: financial
    text: 'Billing and usage data. For paid use: a Stripe customer identifier, your credit balance and ledger, and per-turn usage records (model, tokens, cost).'
  - category: device
    text: whether you are on a phone, tablet or computer
  - category: location
    text: we also record the country your request comes from (as reported by our hosting provider; we never read or store your IP address for this)
  - category: behavioral
    text: First-party product statistics (which pages and features are used)
  deletion:
    route: Profile → Delete my account
    text: Profile → Delete my account permanently deletes your account, every room you own and everything in them
  dpa:
    available: null
    text: We have data processing terms in place with each processor.
    url: null
  purposes:
  - purpose: Running rooms and generating AI responses
    text: Creating your account, running your rooms, generating AI responses, keeping shared memory and the board in sync, delivering emails about your rooms
  - purpose: Product statistics
    text: First-party product statistics (which pages and features are used)
  - purpose: Marketing emails
    text: Marketing emails
  residency:
  - region: Germany (EU)
    text: Our database and file storage are in Germany and our application runs in Germany.
  retention:
  - period: Until you delete your account
    scope: Account, profile, credentials
    text: Account, profile, credentials Until you delete your account
  - period: Until you delete the room or your account
    scope: Rooms you own
    text: Rooms you own, including messages, sources, artifacts, files, memory and board Until you delete the room or your account
  - period: 30 days of inactivity
    scope: Anonymous sessions and their rooms
    text: Anonymous (no account) sessions and their rooms Deleted after 30 days of inactivity
  - period: six years
    scope: Financial records
    text: financial records for six years after the transaction as required by UK tax law
  - period: 24 months
    scope: First-party product statistics
    text: First-party product statistics 24 months, after which they are deleted
  rights:
  - right: access
    text: access the personal data we hold about you and receive a copy
  - right: correct
    text: correct inaccurate data
  - right: erasure
    text: delete your data ("right to erasure")
  - right: restrict or object
    text: restrict or object to processing based on legitimate interests, including our product statistics
  - right: portability
    text: port your data to another service in a machine-readable format
  - right: withdraw consent
    text: withdraw consent at any time where consent is the basis
  role:
    text: We are the data controller for the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and we do not share it with advertisers.
  subprocessors:
    text: Provider What they do for us Data involved Location Supabase Database, authentication, file storage
    url: null
  transfers:
  - mechanism: adequacy
    text: The UK government has found the EU to provide adequate protection, so those transfers need no further safeguard.
  - mechanism: DPF
    text: we rely on the UK Extension to the EU-US Data Privacy Framework where the provider is certified
  - mechanism: SCC
    text: otherwise on the UK International Data Transfer Addendum to the EU Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bordet
provenance_date: '2026-11-09'
provider_name: Bordet
provider_slug: bordet-ai
slug: bordet-ai-privacy-policy
source_date: '2026-11-09'
source_filename: bordet-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bordet.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bordet\naid: bordet-ai\nurl: https://www.bordet.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the data controller for the personal data described here.\ndata_categories:\n- category: identifying\n  text: Your email address and either a hashed password or a Google sign-in identity\n- category: contact\n  text: Your email address and Google account identifier only\n- category: communication\n  text: 'Room content. Everything that goes into a room: your messages, images you attach or generate, sources you\n    add'\n- category: financial\n  text: 'Billing and usage data. For\
  \ paid use: a Stripe customer identifier, your credit balance and ledger, and\n    per-turn usage records (model, tokens, cost).'\n- category: device\n  text: whether you are on a phone, tablet or computer\n- category: location\n  text: we also record the country your request comes from (as reported by our hosting provider; we never read or\n    store your IP address for this)\n- category: behavioral\n  text: First-party product statistics (which pages and features are used)\npurposes:\n- purpose: Running rooms and generating AI responses\n  text: Creating your account, running your rooms, generating AI responses, keeping shared memory and the board\n    in sync, delivering emails about your rooms\n- purpose: Product statistics\n  text: First-party product statistics (which pages and features are used)\n- purpose: Marketing emails\n  text: Marketing emails\nretention:\n- scope: Account, profile, credentials\n  period: Until you delete your account\n  text: Account, profile, credentials\
  \ Until you delete your account\n- scope: Rooms you own\n  period: Until you delete the room or your account\n  text: Rooms you own, including messages, sources, artifacts, files, memory and board Until you delete the room\n    or your account\n- scope: Anonymous sessions and their rooms\n  period: 30 days of inactivity\n  text: Anonymous (no account) sessions and their rooms Deleted after 30 days of inactivity\n- scope: Financial records\n  period: six years\n  text: financial records for six years after the transaction as required by UK tax law\n- scope: First-party product statistics\n  period: 24 months\n  text: First-party product statistics 24 months, after which they are deleted\nresidency:\n- region: Germany (EU)\n  text: Our database and file storage are in Germany and our application runs in Germany.\ntransfers:\n- mechanism: adequacy\n  text: The UK government has found the EU to provide adequate protection, so those transfers need no further safeguard.\n- mechanism: DPF\n \
  \ text: we rely on the UK Extension to the EU-US Data Privacy Framework where the provider is certified\n- mechanism: SCC\n  text: otherwise on the UK International Data Transfer Addendum to the EU Standard Contractual Clauses\nsubprocessors:\n  url: null\n  text: Provider What they do for us Data involved Location Supabase Database, authentication, file storage\ndpa:\n  available: null\n  url: null\n  text: We have data processing terms in place with each processor.\ndeletion:\n  route: Profile → Delete my account\n  text: Profile → Delete my account permanently deletes your account, every room you own and everything in them\nrights:\n- right: access\n  text: access the personal data we hold about you and receive a copy\n- right: correct\n  text: correct inaccurate data\n- right: erasure\n  text: delete your data (\"right to erasure\")\n- right: restrict or object\n  text: restrict or object to processing based on legitimate interests, including our product statistics\n- right: portability\n\
  \  text: port your data to another service in a machine-readable format\n- right: withdraw consent\n  text: withdraw consent at any time where consent is the basis\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and we do not share it with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/bordet-ai/privacy/bordet-ai-privacy-policy.yml
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
summary_line: 30 quoted statements, read from Bordet's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Collaboration
- Multi-LLM
- Boardroom
- Productivity
- Company
---
