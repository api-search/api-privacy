---
api_specs:
- filename: altcoinchasershq-app-agent-api-openapi.yml
  format: yaml
  label: Altcoin Chasers HQ Agent API
  slug: altcoinchasershq-app-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/altcoinchasershq-app/openapi/altcoinchasershq-app-agent-api-openapi.yml
- filename: altcoinchasershq-app-member-api-openapi.yml
  format: yaml
  label: Altcoin Chasers HQ Member API
  slug: altcoinchasershq-app-member-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/altcoinchasershq-app/openapi/altcoinchasershq-app-member-api-openapi.yml
- filename: altcoinchasershq-app-x402-api-openapi.yml
  format: yaml
  label: Altcoin Chasers HQ X402 API
  slug: altcoinchasershq-app-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/altcoinchasershq-app/openapi/altcoinchasershq-app-x402-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account identifiers and profile details supplied by login providers
  - category: communication
    text: member-created watchlists, portfolios, preferences, chat messages, and support requests
  - category: device
    text: basic service and security logs
  deletion:
    route: Contact support
    text: Contact support to request account-data deletion or export; some records may need to be retained for legal, security, or billing reasons.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authenticate accounts
    text: To authenticate accounts, operate requested features, personalize research, provide support, secure the service, and meet billing obligations.
  - purpose: AI reply generation
    text: Messages and relevant context may be processed by AI providers to generate replies.
  - purpose: token data queries
    text: Token queries may be sent to market, on-chain, and social-data providers without attaching a member's personal identity.
  - purpose: subscription payments
    text: Stripe processes subscription payments.
  retention:
  - period: null
    scope: account data
    text: Account data is retained while the account is active.
  - period: null
    scope: chat and learning data
    text: Chat and learning data may be summarized over time
  - period: null
    scope: support messages
    text: support messages are kept as needed to respond.
  rights:
  - right: data export
    text: Contact support to request account-data deletion or export
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
name: Altcoin Chasers HQ
provenance_date: '2026-11-09'
provider_name: Altcoin Chasers HQ
provider_slug: altcoinchasershq-app
slug: altcoinchasershq-app-privacy-policy
source_date: '2026-11-09'
source_filename: altcoinchasershq-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://altcoinchasershq.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Altcoin Chasers HQ\naid: altcoinchasershq-app\nurl: https://altcoinchasershq.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account identifiers and profile details supplied by login providers\n- category: communication\n  text: member-created watchlists, portfolios, preferences, chat messages, and support requests\n- category: device\n  text: basic service and security logs\npurposes:\n- purpose: authenticate accounts\n  text: To authenticate accounts, operate requested features, personalize research, provide support, secure\
  \ the\n    service, and meet billing obligations.\n- purpose: AI reply generation\n  text: Messages and relevant context may be processed by AI providers to generate replies.\n- purpose: token data queries\n  text: Token queries may be sent to market, on-chain, and social-data providers without attaching a member's personal\n    identity.\n- purpose: subscription payments\n  text: Stripe processes subscription payments.\nretention:\n- scope: account data\n  period: null\n  text: Account data is retained while the account is active.\n- scope: chat and learning data\n  period: null\n  text: Chat and learning data may be summarized over time\n- scope: support messages\n  period: null\n  text: support messages are kept as needed to respond.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact support\n  text: Contact support to request account-data deletion or export; some records may need\
  \ to be retained for legal,\n    security, or billing reasons.\nrights:\n- right: data export\n  text: Contact support to request account-data deletion or export\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/altcoinchasershq-app/privacy/altcoinchasershq-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 12 quoted statements, read from Altcoin Chasers HQ's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Research
- Artificial Intelligence
- Finance
- Altcoins
---
