---
api_specs:
- filename: itsgloria-ai-api-keys-api-openapi.yml
  format: yaml
  label: Gloria API Keys API
  slug: itsgloria-ai-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-api-keys-api-openapi.yml
- filename: itsgloria-ai-articles-api-openapi.yml
  format: yaml
  label: Gloria Articles API
  slug: itsgloria-ai-articles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-articles-api-openapi.yml
- filename: itsgloria-ai-authentication-api-openapi.yml
  format: yaml
  label: Gloria Authentication API
  slug: itsgloria-ai-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-authentication-api-openapi.yml
- filename: itsgloria-ai-bots-api-openapi.yml
  format: yaml
  label: Gloria Bots API
  slug: itsgloria-ai-bots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-bots-api-openapi.yml
- filename: itsgloria-ai-categories-api-openapi.yml
  format: yaml
  label: Gloria Categories API
  slug: itsgloria-ai-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-categories-api-openapi.yml
- filename: itsgloria-ai-health-api-openapi.yml
  format: yaml
  label: Gloria Health API
  slug: itsgloria-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-health-api-openapi.yml
- filename: itsgloria-ai-narratives-api-openapi.yml
  format: yaml
  label: Gloria Narratives API
  slug: itsgloria-ai-narratives-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-narratives-api-openapi.yml
- filename: itsgloria-ai-news-api-openapi.yml
  format: yaml
  label: Gloria News API
  slug: itsgloria-ai-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-news-api-openapi.yml
- filename: itsgloria-ai-recaps-api-openapi.yml
  format: yaml
  label: Gloria Recaps API
  slug: itsgloria-ai-recaps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-recaps-api-openapi.yml
- filename: itsgloria-ai-websocket-api-openapi.yml
  format: yaml
  label: Gloria WebSocket API
  slug: itsgloria-ai-websocket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/itsgloria-ai/openapi/itsgloria-ai-websocket-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Data: Email address, username, password (if registration is required).'
  - category: financial
    text: 'Wallet Address: If provided or linked, your blockchain wallet address may be stored and used for access control, personalization, or token-gated content delivery.'
  - category: device
    text: 'Device & Session Info: IP address, browser type, operating system, screen resolution.'
  - category: behavioral
    text: 'Usage Activity: Saved feeds, clicked topics, starred signals, custom settings.'
  - category: communication
    text: 'Support Communications: When you contact us for assistance or submit feedback.'
  deletion:
    route: email
    text: To exercise your rights, email us at privacy@gloria.ai .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: Provide personalized news experiences via the Terminal, and deliver real-time data feeds across all channels.
  - purpose: Wallet-gated access
    text: Use wallet address to authorize access to specific tiers or content.
  - purpose: Analytics (Terminal only)
    text: Evaluate feature usage and improve user experience.
  - purpose: Security and abuse prevention
    text: Detect and prevent spam, fraud, or DDoS attacks.
  - purpose: Communication
    text: Respond to user support requests or notify you of relevant updates (only via the Terminal).
  retention:
  - period: null
    scope: Terminal data
    text: Terminal Data (e.g., wallet address, preferences, activity logs) is retained as long as your account is active or required for legal/operational purposes.
  - period: short-term
    scope: Feed channels
    text: Feed Channels (API, bots, etc.) maintain only short-term logs for diagnostics and abuse monitoring and are not stored permanently or associated with individuals.
  rights:
  - right: Access or update
    text: Access or update your personal data
  - right: Deletion
    text: Request deletion (right to be forgotten)
  - right: Object or restrict
    text: Object to or restrict processing
  - right: Portability
    text: Request data portability
  - right: Withdraw consent
    text: Withdraw consent at any time
  role:
    text: Gloria AI Ltd ("Gloria," "we," "us," or "our"), a company incorporated in the British Virgin Islands
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Gloria
provenance_date: '2026-11-09'
provider_name: Gloria
provider_slug: itsgloria-ai
slug: itsgloria-ai-privacy-policy
source_date: '2026-11-09'
source_filename: itsgloria-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.itsgloria.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Gloria\naid: itsgloria-ai\nurl: https://www.itsgloria.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Gloria AI Ltd (\"Gloria,\" \"we,\" \"us,\" or \"our\"), a company incorporated in the British Virgin Islands\ndata_categories:\n- category: identifying\n  text: 'Account Data: Email address, username, password (if registration is required).'\n- category: financial\n  text: 'Wallet Address: If provided or linked, your blockchain wallet address may be stored and used for access\n    control, personalization, or token-gated content delivery.'\n- category: device\n  text: 'Device\
  \ & Session Info: IP address, browser type, operating system, screen resolution.'\n- category: behavioral\n  text: 'Usage Activity: Saved feeds, clicked topics, starred signals, custom settings.'\n- category: communication\n  text: 'Support Communications: When you contact us for assistance or submit feedback.'\npurposes:\n- purpose: Service delivery\n  text: Provide personalized news experiences via the Terminal, and deliver real-time data feeds across all channels.\n- purpose: Wallet-gated access\n  text: Use wallet address to authorize access to specific tiers or content.\n- purpose: Analytics (Terminal only)\n  text: Evaluate feature usage and improve user experience.\n- purpose: Security and abuse prevention\n  text: Detect and prevent spam, fraud, or DDoS attacks.\n- purpose: Communication\n  text: Respond to user support requests or notify you of relevant updates (only via the Terminal).\nretention:\n- scope: Terminal data\n  period: null\n  text: Terminal Data (e.g., wallet address,\
  \ preferences, activity logs) is retained as long as your account is\n    active or required for legal/operational purposes.\n- scope: Feed channels\n  period: short-term\n  text: Feed Channels (API, bots, etc.) maintain only short-term logs for diagnostics and abuse monitoring and are\n    not stored permanently or associated with individuals.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email\n  text: To exercise your rights, email us at privacy@gloria.ai .\nrights:\n- right: Access or update\n  text: Access or update your personal data\n- right: Deletion\n  text: Request deletion (right to be forgotten)\n- right: Object or restrict\n  text: Object to or restrict processing\n- right: Portability\n  text: Request data portability\n- right: Withdraw consent\n  text: Withdraw consent at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/itsgloria-ai/privacy/itsgloria-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Gloria's own page on 2026-11-09.
synthetic: false
tags:
- Company
- News
- Cryptocurrency
- Market Intelligence
- Sentiment Analysis
- Prediction Markets
- Artificial Intelligence
- MCP
- x402
- WebSocket
- Agents
---
