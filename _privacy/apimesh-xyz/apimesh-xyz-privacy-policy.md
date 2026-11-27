---
api_specs:
- filename: apimesh-xyz-apimesh-api-openapi.yml
  format: yaml
  label: APIMesh API Mesh API
  slug: apimesh-xyz-apimesh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apimesh-xyz/openapi/apimesh-xyz-apimesh-api-openapi.yml
- filename: apimesh-xyz-health-api-openapi.yml
  format: yaml
  label: APIMesh Health API
  slug: apimesh-xyz-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apimesh-xyz/openapi/apimesh-xyz-health-api-openapi.yml
- filename: apimesh-xyz-preview-api-openapi.yml
  format: yaml
  label: APIMesh Preview API
  slug: apimesh-xyz-preview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apimesh-xyz/openapi/apimesh-xyz-preview-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (for account login and communication)
  - category: contact
    text: Email address (for account login and communication)
  - category: device
    text: IP addresses (for rate limiting and abuse prevention, not tracking)
  - category: financial
    text: Stripe customer ID (links your account to your payment history)
  - category: behavioral
    text: 'API request logs: timestamps, endpoints called, response times'
  deletion:
    route: account deletion request
    text: 'After account deletion request: all data deleted within 30 days'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account authentication
    text: 'Your data is used for: account authentication, API access authorization, usage analytics (aggregate, not individual tracking), abuse prevention, and billing reconciliation.'
  - purpose: payment processing
    text: Stripe processes payments.
  - purpose: transactional email
    text: Resend delivers transactional emails (verification codes, password resets).
  residency:
  - region: Hetzner servers
    text: Data is stored on Hetzner servers.
  retention:
  - period: while your account is active
    scope: account data
    text: 'Account data: retained while your account is active'
  - period: 90 days
    scope: API request logs
    text: 'API request logs: retained for 90 days'
  - period: 30 days
    scope: after account deletion request
    text: 'After account deletion request: all data deleted within 30 days'
  rights:
  - right: access
    text: Access your personal data
  - right: rectify
    text: Rectify inaccurate data
  - right: erase
    text: Erase your data ("right to be forgotten")
  - right: portability
    text: Port your data to another service
  - right: restrict processing
    text: Restrict processing of your data
  - right: object
    text: Object to processing of your data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your data or use tracking cookies
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on standard contractual clauses where applicable.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: APIMesh
provenance_date: '2026-11-09'
provider_name: APIMesh
provider_slug: apimesh-xyz
slug: apimesh-xyz-privacy-policy
source_date: '2026-11-09'
source_filename: apimesh-xyz-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apimesh.xyz/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: APIMesh\naid: apimesh-xyz\nurl: https://apimesh.xyz/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address (for account login and communication)\n- category: contact\n  text: Email address (for account login and communication)\n- category: device\n  text: IP addresses (for rate limiting and abuse prevention, not tracking)\n- category: financial\n  text: Stripe customer ID (links your account to your payment history)\n- category: behavioral\n  text: 'API request logs: timestamps, endpoints called, response times'\npurposes:\n\
  - purpose: account authentication\n  text: 'Your data is used for: account authentication, API access authorization, usage analytics (aggregate, not\n    individual tracking), abuse prevention, and billing reconciliation.'\n- purpose: payment processing\n  text: Stripe processes payments.\n- purpose: transactional email\n  text: Resend delivers transactional emails (verification codes, password resets).\nretention:\n- scope: account data\n  period: while your account is active\n  text: 'Account data: retained while your account is active'\n- scope: API request logs\n  period: 90 days\n  text: 'API request logs: retained for 90 days'\n- scope: after account deletion request\n  period: 30 days\n  text: 'After account deletion request: all data deleted within 30 days'\nresidency:\n- region: Hetzner servers\n  text: Data is stored on Hetzner servers.\ntransfers:\n- mechanism: SCC\n  text: We rely on standard contractual clauses where applicable.\nsubprocessors:\n  url: null\n  text: null\n\
  dpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion request\n  text: 'After account deletion request: all data deleted within 30 days'\nrights:\n- right: access\n  text: Access your personal data\n- right: rectify\n  text: Rectify inaccurate data\n- right: erase\n  text: Erase your data (\"right to be forgotten\")\n- right: portability\n  text: Port your data to another service\n- right: restrict processing\n  text: Restrict processing of your data\n- right: object\n  text: Object to processing of your data\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your data or use tracking cookies\n"
source_yaml_url: https://artifacts.apis.io/apimesh-xyz/privacy/apimesh-xyz-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from APIMesh's own page on 2026-11-09.
synthetic: false
tags:
- Web Analysis
- SEO
- Web Security
- Email Verification
- Developer Tools
- Micropayments
- x402
- MCP
- Agent-Native
- Webhook
- AI Coding Agents
- Open Source
- A2A
---
