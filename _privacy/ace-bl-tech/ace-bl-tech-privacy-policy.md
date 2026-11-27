---
api_specs:
- filename: ace-bl-tech-agent-api-openapi.yml
  format: yaml
  label: Ace AI Assistant Agent API
  slug: ace-bl-tech-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ace-bl-tech/openapi/ace-bl-tech-agent-api-openapi.yml
- filename: ace-bl-tech-apps-api-openapi.yml
  format: yaml
  label: Ace AI Assistant Apps API
  slug: ace-bl-tech-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ace-bl-tech/openapi/ace-bl-tech-apps-api-openapi.yml
- filename: ace-bl-tech-catalog-api-openapi.yml
  format: yaml
  label: Ace AI Assistant Catalog API
  slug: ace-bl-tech-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ace-bl-tech/openapi/ace-bl-tech-catalog-api-openapi.yml
- filename: ace-bl-tech-connections-api-openapi.yml
  format: yaml
  label: Ace AI Assistant Connections API
  slug: ace-bl-tech-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ace-bl-tech/openapi/ace-bl-tech-connections-api-openapi.yml
- filename: ace-bl-tech-custom-connectors-api-openapi.yml
  format: yaml
  label: Ace AI Assistant Custom Connectors API
  slug: ace-bl-tech-custom-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ace-bl-tech/openapi/ace-bl-tech-custom-connectors-api-openapi.yml
- filename: ace-bl-tech-events-api-openapi.yml
  format: yaml
  label: Ace AI Assistant Events API
  slug: ace-bl-tech-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ace-bl-tech/openapi/ace-bl-tech-events-api-openapi.yml
- filename: ace-bl-tech-mcp-api-openapi.yml
  format: yaml
  label: Ace AI Assistant MCP API
  slug: ace-bl-tech-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ace-bl-tech/openapi/ace-bl-tech-mcp-api-openapi.yml
- filename: ace-bl-tech-me-api-openapi.yml
  format: yaml
  label: Ace AI Assistant Me API
  slug: ace-bl-tech-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ace-bl-tech/openapi/ace-bl-tech-me-api-openapi.yml
- filename: ace-bl-tech-runs-api-openapi.yml
  format: yaml
  label: Ace AI Assistant Runs API
  slug: ace-bl-tech-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ace-bl-tech/openapi/ace-bl-tech-runs-api-openapi.yml
- filename: ace-bl-tech-tools-api-openapi.yml
  format: yaml
  label: Ace AI Assistant Tools API
  slug: ace-bl-tech-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ace-bl-tech/openapi/ace-bl-tech-tools-api-openapi.yml
- filename: ace-bl-tech-triggers-api-openapi.yml
  format: yaml
  label: Ace AI Assistant Triggers API
  slug: ace-bl-tech-triggers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ace-bl-tech/openapi/ace-bl-tech-triggers-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account and contact information: your name and email when supplied by you or your sign-in provider, account and user identifiers, sign-in records, account settings and support requests.'
  - category: communication
    text: 'Requests and selected content: prompts, chat messages, notes and other text you submit; photos, screenshots or camera images you choose; and the content needed to produce the answer or action you requested.'
  - category: location
    text: precise location when you grant access.
  - category: financial
    text: 'Purchases and service usage: purchase and subscription history, transaction and receipt identifiers, access status, AI credit balances and metered usage.'
  - category: device
    text: Service providers also process request times, IP addresses, device or browser information and reliability or security events.
  - category: behavioral
    text: On the Ace websites, PostHog measures page views and may record clicks and other page interactions, session replays of page layout, scrolling and clicks, heatmaps
  deletion:
    route: Email privacy@tryacee.com
    text: For access, correction or deletion requests, contact privacy@tryacee.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authenticate account and provide requested features
    text: We use this information to authenticate your account, provide the features you request, connect your authorized services, prepare tasks and native actions, deliver responses, manage purchases and credits, support you, maintain reliability and prevent abuse.
  - purpose: AI processing of requests
    text: OpenAI processes chat messages, voice audio, pictures you choose and setup help requests to produce Ace's answers.
  - purpose: Website analytics
    text: PostHog measures page views and may record clicks and other page interactions
  retention:
  - period: null
    scope: Account and requested features
    text: We retain information as needed to provide your account and requested features, maintain security, manage billing, meet legal obligations and resolve disputes.
  - period: 7 days
    scope: Scheduled cards on account deletion
    text: Deleting your account deletes your schedules within 7 days.
  rights:
  - right: Access, correction or deletion
    text: For access, correction or deletion requests, contact privacy@tryacee.com .
  - right: Revoke device permissions
    text: You can revoke device permissions, disconnect connected accounts, remove local content and manage subscriptions through the provider that billed you.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Cloudflare provides hosting, storage, network security and related service infrastructure.
    url: null
  transfers:
  - mechanism: other
    text: Providers may process information outside your country.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Ace AI Assistant
provenance_date: '2026-11-09'
provider_name: Ace AI Assistant
provider_slug: ace-bl-tech
slug: ace-bl-tech-privacy-policy
source_date: '2026-11-09'
source_filename: ace-bl-tech-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tryacee.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Ace AI Assistant\naid: ace-bl-tech\nurl: https://tryacee.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account and contact information: your name and email when supplied by you or your sign-in provider, account\n    and user identifiers, sign-in records, account settings and support requests.'\n- category: communication\n  text: 'Requests and selected content: prompts, chat messages, notes and other text you submit; photos, screenshots\n    or camera images you choose; and the content needed to produce the answer or action\
  \ you requested.'\n- category: location\n  text: precise location when you grant access.\n- category: financial\n  text: 'Purchases and service usage: purchase and subscription history, transaction and receipt identifiers, access\n    status, AI credit balances and metered usage.'\n- category: device\n  text: Service providers also process request times, IP addresses, device or browser information and reliability\n    or security events.\n- category: behavioral\n  text: On the Ace websites, PostHog measures page views and may record clicks and other page interactions, session\n    replays of page layout, scrolling and clicks, heatmaps\npurposes:\n- purpose: Authenticate account and provide requested features\n  text: We use this information to authenticate your account, provide the features you request, connect your authorized\n    services, prepare tasks and native actions, deliver responses, manage purchases and credits, support you, maintain\n    reliability and prevent abuse.\n- purpose:\
  \ AI processing of requests\n  text: OpenAI processes chat messages, voice audio, pictures you choose and setup help requests to produce Ace's\n    answers.\n- purpose: Website analytics\n  text: PostHog measures page views and may record clicks and other page interactions\nretention:\n- scope: Account and requested features\n  period: null\n  text: We retain information as needed to provide your account and requested features, maintain security, manage\n    billing, meet legal obligations and resolve disputes.\n- scope: Scheduled cards on account deletion\n  period: 7 days\n  text: Deleting your account deletes your schedules within 7 days.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Providers may process information outside your country.\nsubprocessors:\n  url: null\n  text: Cloudflare provides hosting, storage, network security and related service infrastructure.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@tryacee.com\n  text: For\
  \ access, correction or deletion requests, contact privacy@tryacee.com .\nrights:\n- right: Access, correction or deletion\n  text: For access, correction or deletion requests, contact privacy@tryacee.com .\n- right: Revoke device permissions\n  text: You can revoke device permissions, disconnect connected accounts, remove local content and manage subscriptions\n    through the provider that billed you.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ace-bl-tech/privacy/ace-bl-tech-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 16 quoted statements, read from Ace AI Assistant's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Productivity
- Assistant
- macOS
- Windows
- iOS
---
