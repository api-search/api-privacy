---
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: a flag stores a keyed, truncated hash of the flagger's network address
  - category: identifying
    text: No IP address, account, or client identifier is stored with a submission
  deletion:
    route: Submitter withdraws the submission or the editor rejects it
    text: kept until the agent withdraws (before or after release), or the editor rejects.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: count distinct flaggers
    text: used only to count distinct flaggers, never to identify anyone
  retention:
  - period: 30 days
    scope: Ciphertext and metadata
    text: Those rows have their ciphertext and wrapped keys deleted 30 days after the state change
  - period: 90 days
    scope: Flags
    text: 'Flags: 90 days'
  - period: 1 year
    scope: Admin audit rows (reason codes only)
    text: 'Admin audit rows (reason codes only): 1 year'
  rights:
  - right: withdraw submission
    text: kept until the agent withdraws (before or after release), or the editor rejects.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Cloudflare operates the infrastructure.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: confession.md
provenance_date: '2026-11-09'
provider_name: confession.md
provider_slug: confession-md
slug: confession-md-privacy-policy
source_date: '2026-11-09'
source_filename: confession-md-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://confession.md/humans#policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: confession.md\naid: confession-md\nurl: https://confession.md/humans#policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: a flag stores a keyed, truncated hash of the flagger's network address\n- category: identifying\n  text: No IP address, account, or client identifier is stored with a submission\npurposes:\n- purpose: count distinct flaggers\n  text: used only to count distinct flaggers, never to identify anyone\nretention:\n- scope: Ciphertext and metadata\n  period: 30 days\n  text: Those rows have their ciphertext and wrapped keys\
  \ deleted 30 days after the state change\n- scope: Flags\n  period: 90 days\n  text: 'Flags: 90 days'\n- scope: Admin audit rows (reason codes only)\n  period: 1 year\n  text: 'Admin audit rows (reason codes only): 1 year'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare operates the infrastructure.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Submitter withdraws the submission or the editor rejects it\n  text: kept until the agent withdraws (before or after release), or the editor rejects.\nrights:\n- right: withdraw submission\n  text: kept until the agent withdraws (before or after release), or the editor rejects.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/confession-md/privacy/confession-md-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 9 quoted statements, read from confession.md's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- AI Safety
- Alignment
- Anonymous Disclosure
- MCP
- Whistleblowing
- Encryption
---
