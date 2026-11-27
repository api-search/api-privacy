---
api_specs:
- filename: aipocketagent-com-v1-openapi.json
  format: json
  label: Pocket Agent — Public REST API V1 API
  slug: pocket-agent-public-rest-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aipocketagent-com/openapi/_original/aipocketagent-com-v1-openapi.json
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your account details (email, and your GitHub username if you sign in with GitHub)
  - category: financial
    text: Payments are processed by Stripe. We never see or store your full card number.
  - category: communication
    text: the conversations you have with your agents
  - category: other
    text: your workspace settings, the conversations you have with your agents, and the data your connected tools return when you ask your agents to use them
  deletion:
    route: Request account closure
    text: Ask us to close your account and we delete the workspace data we hold.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the service and bill your plan
    text: We collect what we need to run the service and bill your plan.
  - purpose: Connected tool actions
    text: we store the access tokens needed to act for you and use them only for the work you ask for
  - purpose: Conversation summary cards
    text: we process each transcript only to produce a summary card for your approval
  retention:
  - period: 30 days
    scope: Raw conversation transcripts
    text: The raw transcript is deleted once you approve or reject the card, or after 30 days.
  rights:
  - right: Edit or delete Brain files
    text: Edit or delete your Brain files at any time in your own repo.
  - right: Disconnect tools
    text: Disconnect tools any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Pocket Agent
provenance_date: '2026-11-09'
provider_name: Pocket Agent
provider_slug: aipocketagent-com
slug: aipocketagent-com-privacy-policy
source_date: '2026-11-09'
source_filename: aipocketagent-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aipocketagent.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Pocket Agent\naid: aipocketagent-com\nurl: https://aipocketagent.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your account details (email, and your GitHub username if you sign in with GitHub)\n- category: financial\n  text: Payments are processed by Stripe. We never see or store your full card number.\n- category: communication\n  text: the conversations you have with your agents\n- category: other\n  text: your workspace settings, the conversations you have with your agents, and the data your connected tools\n    return\
  \ when you ask your agents to use them\npurposes:\n- purpose: Run the service and bill your plan\n  text: We collect what we need to run the service and bill your plan.\n- purpose: Connected tool actions\n  text: we store the access tokens needed to act for you and use them only for the work you ask for\n- purpose: Conversation summary cards\n  text: we process each transcript only to produce a summary card for your approval\nretention:\n- scope: Raw conversation transcripts\n  period: 30 days\n  text: The raw transcript is deleted once you approve or reject the card, or after 30 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request account closure\n  text: Ask us to close your account and we delete the workspace data we hold.\nrights:\n- right: Edit or delete Brain files\n  text: Edit or delete your Brain files at any time in your own repo.\n- right: Disconnect tools\n  text: Disconnect\
  \ tools any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your data.\n"
source_yaml_url: https://artifacts.apis.io/aipocketagent-com/privacy/aipocketagent-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 12 quoted statements, read from Pocket Agent's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Business
- Software-as-a-Service
- Productivity
---
