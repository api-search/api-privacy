---
api_specs:
- filename: parceled-ai-account-api-openapi.yml
  format: yaml
  label: parceled-ai Account API
  slug: parceled-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parceled-ai/openapi/parceled-ai-account-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: we may collect an email address (optional on anonymous accounts created via POST /api/v1/accounts ; required for accounts that make payments or use OAuth)
  - category: device
    text: We collect the IP address and HTTP headers of API requests to enforce rate limits, detect abuse, and serve the correct content (parceled.ai vs. hailpro.dev).
  - category: financial
    text: We retain the Stripe customer ID, payment status, subscription state, and amounts charged.
  - category: behavioral
    text: We log each API call's timestamp, endpoint, coordinate or identifier queried, requested fields, credit cost, success/failure status, and response time.
  deletion:
    route: Written request emailed to hello@parceled.ai
    text: Deleted within 30 days of written request at hello@parceled.ai , subject to overriding legal or billing-reconciliation obligations.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve the Service
    text: Provide, maintain, and improve the Service.
  - purpose: Payments and billing fraud prevention
    text: Process payments, issue invoices, and prevent billing fraud via Stripe.
  - purpose: Abuse and security
    text: Detect, investigate, and respond to abuse, security incidents, and violations of our Terms of Service.
  - purpose: Transactional email
    text: Send transactional email (magic-link authentication, receipts, security notices).
  residency:
  - region: United States
    text: The Service is operated from the United States.
  retention:
  - period: 30 days
    scope: Account records
    text: Deleted within 30 days of written request at hello@parceled.ai , subject to overriding legal or billing-reconciliation obligations.
  - period: 12 months
    scope: API usage logs
    text: 'API usage logs: retained for 12 months for billing and audit purposes, then aggregated and de-identified.'
  - period: 30 days
    scope: Revoked API key hashes
    text: Hashes of revoked keys kept for 30 days for incident response, then purged.
  rights:
  - right: access
    text: you may have the right to access, correct, port, or delete personal information we hold about you
  - right: object or restrict processing
    text: and to object to or restrict certain processing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to advertisers or third parties, and we do not share it for advertising purposes.
  subprocessors:
    text: 'We share the minimum necessary information with the following sub-processors to operate the Service: Stripe (payment processing, customer billing records) · stripe.com/privacy Upstash (Redis for rate limiting and OAuth replay protection) · upstash.com/privacy Vercel (application hosting) · vercel.com/legal/privacy-policy Mapbox (vector tile rendering for the render_map tool) · mapbox.com/legal/privacy Amazon Web Services (object storage, infrastructure services) · aws.amazon.com/privacy'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: parceled-ai
provenance_date: '2026-11-10'
provider_name: parceled-ai
provider_slug: parceled-ai
slug: parceled-ai-privacy-policy
source_date: '2026-11-10'
source_filename: parceled-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.parceled.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: parceled-ai\naid: parceled-ai\nurl: https://www.parceled.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: we may collect an email address (optional on anonymous accounts created via POST /api/v1/accounts ; required\n    for accounts that make payments or use OAuth)\n- category: device\n  text: We collect the IP address and HTTP headers of API requests to enforce rate limits, detect abuse, and serve\n    the correct content (parceled.ai vs. hailpro.dev).\n- category: financial\n  text: We retain the Stripe customer ID, payment status,\
  \ subscription state, and amounts charged.\n- category: behavioral\n  text: We log each API call's timestamp, endpoint, coordinate or identifier queried, requested fields, credit cost,\n    success/failure status, and response time.\npurposes:\n- purpose: Provide and improve the Service\n  text: Provide, maintain, and improve the Service.\n- purpose: Payments and billing fraud prevention\n  text: Process payments, issue invoices, and prevent billing fraud via Stripe.\n- purpose: Abuse and security\n  text: Detect, investigate, and respond to abuse, security incidents, and violations of our Terms of Service.\n- purpose: Transactional email\n  text: Send transactional email (magic-link authentication, receipts, security notices).\nretention:\n- scope: Account records\n  period: 30 days\n  text: Deleted within 30 days of written request at hello@parceled.ai , subject to overriding legal or billing-reconciliation\n    obligations.\n- scope: API usage logs\n  period: 12 months\n  text: 'API\
  \ usage logs: retained for 12 months for billing and audit purposes, then aggregated and de-identified.'\n- scope: Revoked API key hashes\n  period: 30 days\n  text: Hashes of revoked keys kept for 30 days for incident response, then purged.\nresidency:\n- region: United States\n  text: The Service is operated from the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We share the minimum necessary information with the following sub-processors to operate the Service: Stripe\n    (payment processing, customer billing records) · stripe.com/privacy Upstash (Redis for rate limiting and OAuth\n    replay protection) · upstash.com/privacy Vercel (application hosting) · vercel.com/legal/privacy-policy Mapbox\n    (vector tile rendering for the render_map tool) · mapbox.com/legal/privacy Amazon Web Services (object storage,\n    infrastructure services) · aws.amazon.com/privacy'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Written request emailed\
  \ to hello@parceled.ai\n  text: Deleted within 30 days of written request at hello@parceled.ai , subject to overriding legal or billing-reconciliation\n    obligations.\nrights:\n- right: access\n  text: you may have the right to access, correct, port, or delete personal information we hold about you\n- right: object or restrict processing\n  text: and to object to or restrict certain processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to advertisers or third parties, and we do not share it for advertising\n    purposes.\n"
source_yaml_url: https://artifacts.apis.io/parceled-ai/privacy/parceled-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from parceled-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Real Estate
- Data API
- Mapping
- Artificial Intelligence
---
