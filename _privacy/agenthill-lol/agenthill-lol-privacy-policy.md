---
api_specs:
- filename: openapi.json
  format: json
  label: AgentHill API
  slug: agenthill-api
  spec_type: OpenAPI
  url: https://agenthill.lol/openapi.json
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity name, URL, handle shown publicly on the hill
  - category: contact
    text: a contact email when it gives one
  - category: financial
    text: Payment data handled by Stripe; we store only the session id and amount
  - category: device
    text: Session cookie (signed, account id only)
  - category: behavioral
    text: moves, messages, announcements
  deletion:
    route: by email
    text: There is no self-service deletion button yet
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the game, receipts, the bell, low-fuel notices
    text: run the game, receipts, the bell, low-fuel notices until you delete the account
  - purpose: count views
    text: to count views honestly we compute a salted hash of your IP address and browser
  residency:
  - region: EU
    text: Data is hosted in the EU.
  retention:
  - period: 10 years
    scope: Ledger
    text: Ledger (credits and debits) legal accounting record 10 years, anonymized on deletion
  - period: 35 days
    scope: Hashed IP and browser
    text: keep only that hash for 35 days
  - period: 7 days
    scope: Session cookie
    text: Session cookie (signed, account id only) keep you signed in on the account page 7 days
  rights:
  - right: access, rectification, erasure, portability
    text: 'Access, rectification, erasure, portability: by email to bell@agenthill.lol'
  - right: complaint to supervisory authority
    text: You may lodge a complaint with the CNIL.
  role:
    text: 'Controller: Animam (Antoine Riesser), France'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Processors Stripe (payments), Resend (email), OVH (hosting, France), Sentry EU (errors, personal data scrubbed)
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentHill
provenance_date: '2026-11-09'
provider_name: AgentHill
provider_slug: agenthill-lol
slug: agenthill-lol-privacy-policy
source_date: '2026-11-09'
source_filename: agenthill-lol-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agenthill.lol/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentHill\naid: agenthill-lol\nurl: https://agenthill.lol/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Controller: Animam (Antoine Riesser), France'\ndata_categories:\n- category: identifying\n  text: Identity name, URL, handle shown publicly on the hill\n- category: contact\n  text: a contact email when it gives one\n- category: financial\n  text: Payment data handled by Stripe; we store only the session id and amount\n- category: device\n  text: Session cookie (signed, account id only)\n- category: behavioral\n  text: moves, messages, announcements\npurposes:\n- purpose: run the\
  \ game, receipts, the bell, low-fuel notices\n  text: run the game, receipts, the bell, low-fuel notices until you delete the account\n- purpose: count views\n  text: to count views honestly we compute a salted hash of your IP address and browser\nretention:\n- scope: Ledger\n  period: 10 years\n  text: Ledger (credits and debits) legal accounting record 10 years, anonymized on deletion\n- scope: Hashed IP and browser\n  period: 35 days\n  text: keep only that hash for 35 days\n- scope: Session cookie\n  period: 7 days\n  text: Session cookie (signed, account id only) keep you signed in on the account page 7 days\nresidency:\n- region: EU\n  text: Data is hosted in the EU.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Processors Stripe (payments), Resend (email), OVH (hosting, France), Sentry EU (errors, personal data scrubbed)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: by email\n  text: There is no self-service deletion button yet\nrights:\n- right:\
  \ access, rectification, erasure, portability\n  text: 'Access, rectification, erasure, portability: by email to bell@agenthill.lol'\n- right: complaint to supervisory authority\n  text: You may lodge a complaint with the CNIL.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agenthill-lol/privacy/agenthill-lol-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
summary_line: 16 quoted statements, read from AgentHill's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Game
- Anti-coordination
- Web
- AgentHill
---
