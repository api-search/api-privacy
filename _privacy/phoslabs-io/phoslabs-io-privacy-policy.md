---
api_specs:
- filename: phoslabs-io-audit-api-openapi.yml
  format: yaml
  label: Phos Labs Audit API
  slug: phoslabs-io-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phoslabs-io/openapi/phoslabs-io-audit-api-openapi.yml
- filename: phoslabs-io-copy-api-openapi.yml
  format: yaml
  label: Phos Labs Copy API
  slug: phoslabs-io-copy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phoslabs-io/openapi/phoslabs-io-copy-api-openapi.yml
- filename: phoslabs-io-detect-biases-api-openapi.yml
  format: yaml
  label: Phos Labs Detect Biases API
  slug: phoslabs-io-detect-biases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phoslabs-io/openapi/phoslabs-io-detect-biases-api-openapi.yml
- filename: phoslabs-io-diagnose-api-openapi.yml
  format: yaml
  label: Phos Labs Diagnose API
  slug: phoslabs-io-diagnose-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phoslabs-io/openapi/phoslabs-io-diagnose-api-openapi.yml
- filename: phoslabs-io-fix-checkout-api-openapi.yml
  format: yaml
  label: Phos Labs Fix Checkout API
  slug: phoslabs-io-fix-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phoslabs-io/openapi/phoslabs-io-fix-checkout-api-openapi.yml
- filename: phoslabs-io-pricing-api-openapi.yml
  format: yaml
  label: Phos Labs Pricing API
  slug: phoslabs-io-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phoslabs-io/openapi/phoslabs-io-pricing-api-openapi.yml
- filename: phoslabs-io-tools-api-openapi.yml
  format: yaml
  label: Phos Labs Tools API
  slug: phoslabs-io-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phoslabs-io/openapi/phoslabs-io-tools-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: API keys used to authenticate requests
  - category: financial
    text: Billing information collected through Stripe
  - category: device
    text: IP addresses for rate limiting and abuse prevention
  - category: financial
    text: Blockchain wallet addresses when using x402 USDC micropayments
  - category: communication
    text: your comment and our replies
  deletion:
    route: email request to privacy contact
    text: You may request access to, correction of, or deletion of your data at any time by contacting [email protected]
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain, and improve services
    text: Provide, maintain, and improve our services
  - purpose: Process payments and billing
    text: Process payments and manage billing
  - purpose: Enforce rate limits and prevent abuse
    text: Enforce rate limits and prevent abuse
  - purpose: Monitor performance and debug
    text: Monitor service performance and debug issues
  - purpose: Comply with legal obligations
    text: Comply with legal obligations
  - purpose: Avoid answering same comment twice
    text: We use this only so we don't answer the same comment twice.
  retention:
  - period: 30 days
    scope: Usage logs
    text: 'Usage logs: 30 days, then automatically deleted'
  - period: per Stripe's retention policies
    scope: Billing records
    text: 'Billing records: per Stripe''s retention policies'
  - period: duration of your account
    scope: API keys
    text: 'API keys: duration of your account, deleted upon request'
  - period: not stored beyond the rate-limiting window
    scope: IP addresses
    text: 'IP addresses: not stored beyond the rate-limiting window'
  - period: 90 days
    scope: Instagram comment data
    text: We keep it for 90 days, never sell or share it, and delete it sooner on request
  rights:
  - right: access
    text: You may request access to, correction of, or deletion of your data at any time by contacting [email protected]
  - right: correction
    text: You may request access to, correction of, or deletion of your data at any time by contacting [email protected]
  - right: deletion
    text: You may request access to, correction of, or deletion of your data at any time by contacting [email protected]
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or trade your data to any third party.
  subprocessors:
    text: Cloudflare CDN, tunneling, DDoS protection IP addresses, request metadata
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Phos Labs
provenance_date: '2026-11-10'
provider_name: Phos Labs
provider_slug: phoslabs-io
slug: phoslabs-io-privacy-policy
source_date: '2026-11-10'
source_filename: phoslabs-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://phoslabs.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Phos Labs\naid: phoslabs-io\nurl: https://phoslabs.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: API keys used to authenticate requests\n- category: financial\n  text: Billing information collected through Stripe\n- category: device\n  text: IP addresses for rate limiting and abuse prevention\n- category: financial\n  text: Blockchain wallet addresses when using x402 USDC micropayments\n- category: communication\n  text: your comment and our replies\npurposes:\n- purpose: Provide, maintain, and improve services\n  text: Provide,\
  \ maintain, and improve our services\n- purpose: Process payments and billing\n  text: Process payments and manage billing\n- purpose: Enforce rate limits and prevent abuse\n  text: Enforce rate limits and prevent abuse\n- purpose: Monitor performance and debug\n  text: Monitor service performance and debug issues\n- purpose: Comply with legal obligations\n  text: Comply with legal obligations\n- purpose: Avoid answering same comment twice\n  text: We use this only so we don't answer the same comment twice.\nretention:\n- scope: Usage logs\n  period: 30 days\n  text: 'Usage logs: 30 days, then automatically deleted'\n- scope: Billing records\n  period: per Stripe's retention policies\n  text: 'Billing records: per Stripe''s retention policies'\n- scope: API keys\n  period: duration of your account\n  text: 'API keys: duration of your account, deleted upon request'\n- scope: IP addresses\n  period: not stored beyond the rate-limiting window\n  text: 'IP addresses: not stored beyond the\
  \ rate-limiting window'\n- scope: Instagram comment data\n  period: 90 days\n  text: We keep it for 90 days, never sell or share it, and delete it sooner on request\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare CDN, tunneling, DDoS protection IP addresses, request metadata\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to privacy contact\n  text: You may request access to, correction of, or deletion of your data at any time by contacting [email protected]\nrights:\n- right: access\n  text: You may request access to, correction of, or deletion of your data at any time by contacting [email protected]\n- right: correction\n  text: You may request access to, correction of, or deletion of your data at any time by contacting [email protected]\n- right: deletion\n  text: You may request access to, correction of, or deletion of your data at any time by contacting [email protected]\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: We do not sell, rent, or trade your data to any third party.\n"
source_yaml_url: https://artifacts.apis.io/phoslabs-io/privacy/phoslabs-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Phos Labs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Behavioral Science
- Conversion Optimization
- E-Commerce
- Pricing
- Copywriting
- AI Agents
- MCP
- A2A
- Decision Intelligence
- Agentic Commerce
---
