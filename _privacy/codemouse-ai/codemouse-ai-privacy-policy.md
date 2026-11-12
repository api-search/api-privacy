---
claim_count: 4
description: ''
doc:
  data_categories:
  - category: identifying
    text: GitHub profile, encrypted API keys, usage data, and payment information (via Polar).
  deletion:
    route: workspace deleted after each review
    text: Repositories are cloned into an isolated temporary workspace for the duration of a review and deleted immediately after — we never store your source code.
  dpa:
    available: null
    text: null
    url: null
  retention:
  - period: deleted immediately after
    scope: cloned repositories
    text: Repositories are cloned into an isolated temporary workspace for the duration of a review and deleted immediately after — we never store your source code.
  - period: not retained
    scope: PR diff and files sent to AI providers
    text: are not retained by us.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CodeMouse
provenance_date: '2026-11-09'
provider_name: CodeMouse
provider_slug: codemouse-ai
slug: codemouse-ai-privacy-policy
source_date: '2026-11-09'
source_filename: codemouse-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://codemouse.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CodeMouse\naid: codemouse-ai\nurl: https://codemouse.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: GitHub profile, encrypted API keys, usage data, and payment information (via Polar).\npurposes: []\nretention:\n- scope: cloned repositories\n  period: deleted immediately after\n  text: Repositories are cloned into an isolated temporary workspace for the duration of a review and deleted immediately\n    after — we never store your source code.\n- scope: PR diff and files sent to AI providers\n  period: not retained\n  text: are\
  \ not retained by us.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: workspace deleted after each review\n  text: Repositories are cloned into an isolated temporary workspace for the duration of a review and deleted immediately\n    after — we never store your source code.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/codemouse-ai/privacy/codemouse-ai-privacy-policy.yml
stated_fields:
- data_categories
- retention
- deletion
summary_line: 4 quoted statements, read from CodeMouse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Code Review
- Artificial Intelligence
- GitHub
- Pull Requests
- Developer Tools
- LLM
---
