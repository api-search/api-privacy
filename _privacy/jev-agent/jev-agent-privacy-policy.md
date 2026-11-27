---
api_specs:
- filename: jev-agent-openapi-generated.yml
  format: yaml
  label: Jev Agent (Jagent) API
  slug: jev-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/jev-agent/openapi/_ae-authored/jev-agent-openapi-generated.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: contact
    text: The row holds your email address, and with Google sign-in also your name and avatar URL.
  - category: behavioral
    text: A log of each call — its time, tool, cost and outcome, never its text.
  - category: financial
    text: Order id, email address, credits and time.
  deletion:
    route: DELETE /api/keys
    text: 'There is an endpoint that removes the two rows that identify you: DELETE /api/keys'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account and usage tracking
    text: To tie keys, credits and purchases to one account, and to show a signed-in visitor their own usage.
  - purpose: sign-in
    text: So you stay signed in.
  - purpose: abuse prevention
    text: A counter of codes asked per address and per IP limits abuse.
  retention:
  - period: Kept until you revoke the key
    scope: email address
    text: Kept until you revoke the key.
  - period: 30 days
    scope: session
    text: 30 days.
  - period: Kept until deleted on request
    scope: call log
    text: Kept until deleted on request.
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
name: Jev Agent (Jagent)
provenance_date: '2026-11-09'
provider_name: Jev Agent (Jagent)
provider_slug: jev-agent
slug: jev-agent-privacy-policy
source_date: '2026-11-09'
source_filename: jev-agent-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://jev-agent.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Jev Agent (Jagent)\naid: jev-agent\nurl: https://jev-agent.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: The row holds your email address, and with Google sign-in also your name and avatar URL.\n- category: behavioral\n  text: A log of each call — its time, tool, cost and outcome, never its text.\n- category: financial\n  text: Order id, email address, credits and time.\npurposes:\n- purpose: account and usage tracking\n  text: To tie keys, credits and purchases to one account, and to show a signed-in visitor their own usage.\n\
  - purpose: sign-in\n  text: So you stay signed in.\n- purpose: abuse prevention\n  text: A counter of codes asked per address and per IP limits abuse.\nretention:\n- scope: email address\n  period: Kept until you revoke the key\n  text: Kept until you revoke the key.\n- scope: session\n  period: 30 days\n  text: 30 days.\n- scope: call log\n  period: Kept until deleted on request\n  text: Kept until deleted on request.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: DELETE /api/keys\n  text: 'There is an endpoint that removes the two rows that identify you: DELETE /api/keys'\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jev-agent/privacy/jev-agent-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 10 quoted statements, read from Jev Agent (Jagent)'s own page on 2026-11-09.
synthetic: false
tags:
- AI API
- Classification
- Token Billing
- Developer Tools
---
