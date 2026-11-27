---
api_specs:
- filename: pipehero-app-mcp-api-openapi.yml
  format: yaml
  label: pipehero-app MCP API
  slug: pipehero-app-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pipehero-app/openapi/pipehero-app-mcp-api-openapi.yml
- filename: pipehero-app-slack-api-openapi.yml
  format: yaml
  label: pipehero-app Slack API
  slug: pipehero-app-slack-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pipehero-app/openapi/pipehero-app-slack-api-openapi.yml
- filename: pipehero-app-webhooks-api-openapi.yml
  format: yaml
  label: pipehero-app Webhooks API
  slug: pipehero-app-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pipehero-app/openapi/pipehero-app-webhooks-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data — your name and email address, provided via Google sign-in (through Supabase) when you create an account.
  - category: behavioral
    text: Captured webhook data — when a request reaches one of your tunnels, we store its metadata and body (request and response) so you can inspect and replay it.
  - category: financial
    text: Billing data — plan and subscription status. Payments are handled by Stripe; we do not store your card details.
  - category: device
    text: Usage & technical data — log data, IP address, device/browser information, analytics events, and error reports.
  - category: communication
    text: Support data — messages you send us via chat or email.
  deletion:
    route: On account deletion
    text: On account deletion we remove your personal data within a reasonable period, except where retention is legally required.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, operate, secure and improve the Service
    text: To provide, operate, secure, and improve the Service
  - purpose: Process payments and manage subscriptions
    text: to process payments and manage subscriptions
  - purpose: Communication and support
    text: to communicate with you (including transactional email and support)
  - purpose: Prevent abuse and enforce Terms
    text: to prevent abuse and enforce our Terms
  - purpose: Legal compliance
    text: to comply with legal obligations
  retention:
  - period: while your account is active
    scope: Account data
    text: We retain account data while your account is active.
  - period: 3, 30, or 90 days
    scope: Captured webhook history
    text: Captured webhook history is retained according to your plan (e.g. 3, 30, or 90 days) and then deleted.
  rights:
  - right: access, correct, delete, port, restrict, object, withdraw consent
    text: you may have the right to access, correct, delete, port, or restrict processing of your personal data, to object to processing, and to withdraw consent.
  - right: lodge complaint with data protection authority
    text: or lodge a complaint with your local data protection authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: 'We share it only with service providers who process it on our behalf under appropriate agreements: Supabase Authentication (sign-in) Railway Application hosting (API, tunnel server, database, cache) Vercel Website & dashboard hosting Cloudflare DNS, CDN & network security Stripe Payment processing Postmark Transactional email Google Analytics Product analytics Sentry Error monitoring Crisp Customer support chat'
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we rely on appropriate safeguards such as the EU Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: pipehero-app
provenance_date: '2026-11-10'
provider_name: pipehero-app
provider_slug: pipehero-app
slug: pipehero-app-privacy-policy
source_date: '2026-11-10'
source_filename: pipehero-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://pipehero.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: pipehero-app\naid: pipehero-app\nurl: https://pipehero.app/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account data — your name and email address, provided via Google sign-in (through Supabase) when you create\n    an account.\n- category: behavioral\n  text: Captured webhook data — when a request reaches one of your tunnels, we store its metadata and body (request\n    and response) so you can inspect and replay it.\n- category: financial\n  text: Billing data — plan and subscription status. Payments are handled by Stripe;\
  \ we do not store your card details.\n- category: device\n  text: Usage & technical data — log data, IP address, device/browser information, analytics events, and error reports.\n- category: communication\n  text: Support data — messages you send us via chat or email.\npurposes:\n- purpose: Provide, operate, secure and improve the Service\n  text: To provide, operate, secure, and improve the Service\n- purpose: Process payments and manage subscriptions\n  text: to process payments and manage subscriptions\n- purpose: Communication and support\n  text: to communicate with you (including transactional email and support)\n- purpose: Prevent abuse and enforce Terms\n  text: to prevent abuse and enforce our Terms\n- purpose: Legal compliance\n  text: to comply with legal obligations\nretention:\n- scope: Account data\n  period: while your account is active\n  text: We retain account data while your account is active.\n- scope: Captured webhook history\n  period: 3, 30, or 90 days\n  text: Captured\
  \ webhook history is retained according to your plan (e.g. 3, 30, or 90 days) and then deleted.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on appropriate safeguards such as the EU Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: 'We share it only with service providers who process it on our behalf under appropriate agreements: Supabase\n    Authentication (sign-in) Railway Application hosting (API, tunnel server, database, cache) Vercel Website &\n    dashboard hosting Cloudflare DNS, CDN & network security Stripe Payment processing Postmark Transactional email\n    Google Analytics Product analytics Sentry Error monitoring Crisp Customer support chat'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: On account deletion\n  text: On account deletion we remove your personal data within a reasonable period, except where retention is legally\n    required.\nrights:\n- right: access, correct, delete, port, restrict,\
  \ object, withdraw consent\n  text: you may have the right to access, correct, delete, port, or restrict processing of your personal data, to\n    object to processing, and to withdraw consent.\n- right: lodge complaint with data protection authority\n  text: or lodge a complaint with your local data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/pipehero-app/privacy/pipehero-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from pipehero-app's own page on 2026-11-10.
synthetic: false
tags:
- Webhook
- API Workspace
- Developer Tools
- MCP
- Integration
---
