---
api_specs:
- filename: batru-gg-openapi-generated.yml
  format: yaml
  label: Batru API
  slug: batru-gg-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/batru-gg/openapi/_ae-authored/batru-gg-openapi-generated.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: we store the email address you provide to send the weekly meta digest
  - category: identifying
    text: we store your email address and, if you request one, the API key issued to it
  - category: contact
    text: we receive the name, email and message you submit (plus any optional team/organization and subject), solely to reply
  - category: device
    text: MCP analytics may include the caller’s IP address, client and user-agent information, a pseudonymous identifier derived from network and client information
  - category: behavioral
    text: tool names, inputs and outputs, agent-provided intent, duration and error details
  - category: behavioral
    text: the draft (heroes picked/banned) and current match state; your own hero’s items, gold, level, kills/deaths/assists, last hits and skilled abilities
  deletion:
    route: account data deletion on request
    text: you can ask us to delete it at any time
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: website analytics
    text: We use Google Analytics 4, PostHog and Microsoft Clarity to understand how the site is used
  - purpose: weekly newsletter
    text: we store the email address you provide to send the weekly meta digest
  - purpose: rate limiting and abuse prevention
    text: Signing in is optional and exists only to protect the heavier endpoints from abuse.
  - purpose: MCP improvement and abuse prevention
    text: to measure adoption, understand which tools agents need, improve result quality, diagnose errors and prevent abuse
  - purpose: live predictions and model training
    text: to compute your live win probability and item/skill recommendations, and to train and improve our prediction models
  retention:
  - period: null
    scope: analytics and operational records
    text: We keep analytics and operational records only as long as reasonably needed for the purposes described above.
  rights:
  - right: object or contact about data
    text: contact us with questions or objections about your data
  - right: unsubscribe
    text: unsubscribe from the newsletter via any email
  - right: opt out of analytics
    text: you can opt out at any time
  role:
    text: Batru (“we”, “us”) operates the website batru.gg and companion services
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your data, and we do not share it with third parties for their own marketing.
  subprocessors:
    text: Google Cloud provides storage and Vertex AI for model training, and our managed database provider supports the backend.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Batru
provenance_date: '2026-11-09'
provider_name: Batru
provider_slug: batru-gg
slug: batru-gg-privacy-policy
source_date: '2026-11-09'
source_filename: batru-gg-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://batru.gg/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Batru\naid: batru-gg\nurl: https://batru.gg/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Batru (“we”, “us”) operates the website batru.gg and companion services\ndata_categories:\n- category: contact\n  text: we store the email address you provide to send the weekly meta digest\n- category: identifying\n  text: we store your email address and, if you request one, the API key issued to it\n- category: contact\n  text: we receive the name, email and message you submit (plus any optional team/organization and subject), solely\n    to reply\n- category: device\n  text: MCP analytics\
  \ may include the caller’s IP address, client and user-agent information, a pseudonymous identifier\n    derived from network and client information\n- category: behavioral\n  text: tool names, inputs and outputs, agent-provided intent, duration and error details\n- category: behavioral\n  text: the draft (heroes picked/banned) and current match state; your own hero’s items, gold, level, kills/deaths/assists,\n    last hits and skilled abilities\npurposes:\n- purpose: website analytics\n  text: We use Google Analytics 4, PostHog and Microsoft Clarity to understand how the site is used\n- purpose: weekly newsletter\n  text: we store the email address you provide to send the weekly meta digest\n- purpose: rate limiting and abuse prevention\n  text: Signing in is optional and exists only to protect the heavier endpoints from abuse.\n- purpose: MCP improvement and abuse prevention\n  text: to measure adoption, understand which tools agents need, improve result quality, diagnose errors and\
  \ prevent\n    abuse\n- purpose: live predictions and model training\n  text: to compute your live win probability and item/skill recommendations, and to train and improve our prediction\n    models\nretention:\n- scope: analytics and operational records\n  period: null\n  text: We keep analytics and operational records only as long as reasonably needed for the purposes described above.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Google Cloud provides storage and Vertex AI for model training, and our managed database provider supports\n    the backend.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account data deletion on request\n  text: you can ask us to delete it at any time\nrights:\n- right: object or contact about data\n  text: contact us with questions or objections about your data\n- right: unsubscribe\n  text: unsubscribe from the newsletter via any email\n- right: opt out of analytics\n  text: you can opt out at any time\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We do not sell or rent your data, and we do not share it with third parties for their own marketing.\n"
source_yaml_url: https://artifacts.apis.io/batru-gg/privacy/batru-gg-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Batru's own page on 2026-11-09.
synthetic: false
tags:
- Gaming
- Esports
- Analytics
- Artificial Intelligence
- Competitive
---
