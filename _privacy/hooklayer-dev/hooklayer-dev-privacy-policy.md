---
api_specs:
- filename: hooklayer-dev-openapi-generated.yml
  format: yaml
  label: hooklayer-dev API
  slug: hooklayer-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hooklayer-dev/openapi/_ae-authored/hooklayer-dev-openapi-generated.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: email address and password hash (bcrypt) on signup
  - category: contact
    text: email address and password hash (bcrypt) on signup
  - category: financial
    text: We receive the customer ID, subscription status, and last 4 digits of the card; we never see full card numbers.
  - category: device
    text: They process HTTP requests including IP addresses for delivery.
  - category: behavioral
    text: usage analytics, only after you accept the cookie banner
  - category: other
    text: 'Request inputs : the content you send to each tool (handles, hooks, scripts, URLs, product identifiers, reference samples).'
  deletion:
    route: email support@hooklayer.dev
    text: Deletion request via support@hooklayer.dev removes your account and all associated data within 30 days.
  dpa:
    available: null
    text: Backups are managed by Supabase under their standard data-handling agreement.
    url: null
  purposes:
  - purpose: run requested tool
    text: To run the tool you called (analyze a creator, score a hook, predict virality, etc.) and return the result.
  - purpose: billing credits
    text: To deduct credits from your subscription or pay-as-you-go bucket.
  - purpose: rate limiting
    text: To rate-limit your account against the documented per-tier throughput cap.
  - purpose: product improvement
    text: 'To improve the product: aggregate metrics inform which tools to optimize, which patterns to add to scoring rubrics, etc.'
  residency:
  - region: US
    text: Hooklayer runs on Vercel (US-East) with a Supabase Postgres database hosted in US-East-1 (AWS).
  retention:
  - period: null
    scope: request content
    text: hook text, scripts and reference samples are used to produce your response and are not retained as a separate record of what you submitted.
  - period: 24 hours
    scope: cached analysis results
    text: Cache entries auto-expire after 24 hours.
  - period: 30 days
    scope: account data
    text: Deletion request via support@hooklayer.dev removes your account and all associated data within 30 days.
  - period: indefinitely
    scope: anonymous metrics
    text: 'Anonymous metrics : retained indefinitely; cannot be tied back to your identity.'
  - period: 1 hour
    scope: OAuth tokens
    text: access tokens expire per OAuth spec (default 1 hour).
  rights:
  - right: access
    text: Under GDPR, CCPA, and similar regulations, you have the right to access, correct, port, and delete your data.
  - right: delete
    text: Delete your account and all associated data
  - right: export
    text: Export your data (request via support email)
  - right: revoke API key
    text: Revoke any API key from your dashboard
  role:
    text: 'Data controller: Hooklayer .'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data to anyone. We do not share data with advertisers or data brokers.
  subprocessors:
    text: 'Supabase : our database and authentication provider. They process all account and ledger data on our behalf as a sub-processor.'
    url: null
  transfers:
  - mechanism: other
    text: We do not transfer your account data outside the US except where required by transient CDN delivery (cached static pages on Vercel's global edge network).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: hooklayer-dev
provenance_date: '2026-11-09'
provider_name: hooklayer-dev
provider_slug: hooklayer-dev
slug: hooklayer-dev-privacy-policy
source_date: '2026-11-09'
source_filename: hooklayer-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hooklayer.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: hooklayer-dev\naid: hooklayer-dev\nurl: https://hooklayer.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Data controller: Hooklayer .'\ndata_categories:\n- category: identifying\n  text: email address and password hash (bcrypt) on signup\n- category: contact\n  text: email address and password hash (bcrypt) on signup\n- category: financial\n  text: We receive the customer ID, subscription status, and last 4 digits of the card; we never see full card numbers.\n- category: device\n  text: They process HTTP requests including IP addresses for delivery.\n- category: behavioral\n \
  \ text: usage analytics, only after you accept the cookie banner\n- category: other\n  text: 'Request inputs : the content you send to each tool (handles, hooks, scripts, URLs, product identifiers,\n    reference samples).'\npurposes:\n- purpose: run requested tool\n  text: To run the tool you called (analyze a creator, score a hook, predict virality, etc.) and return the result.\n- purpose: billing credits\n  text: To deduct credits from your subscription or pay-as-you-go bucket.\n- purpose: rate limiting\n  text: To rate-limit your account against the documented per-tier throughput cap.\n- purpose: product improvement\n  text: 'To improve the product: aggregate metrics inform which tools to optimize, which patterns to add to scoring\n    rubrics, etc.'\nretention:\n- scope: request content\n  period: null\n  text: hook text, scripts and reference samples are used to produce your response and are not retained as a separate\n    record of what you submitted.\n- scope: cached analysis results\n\
  \  period: 24 hours\n  text: Cache entries auto-expire after 24 hours.\n- scope: account data\n  period: 30 days\n  text: Deletion request via support@hooklayer.dev removes your account and all associated data within 30 days.\n- scope: anonymous metrics\n  period: indefinitely\n  text: 'Anonymous metrics : retained indefinitely; cannot be tied back to your identity.'\n- scope: OAuth tokens\n  period: 1 hour\n  text: access tokens expire per OAuth spec (default 1 hour).\nresidency:\n- region: US\n  text: Hooklayer runs on Vercel (US-East) with a Supabase Postgres database hosted in US-East-1 (AWS).\ntransfers:\n- mechanism: other\n  text: We do not transfer your account data outside the US except where required by transient CDN delivery (cached\n    static pages on Vercel's global edge network).\nsubprocessors:\n  url: null\n  text: 'Supabase : our database and authentication provider. They process all account and ledger data on our behalf\n    as a sub-processor.'\ndpa:\n  available: null\n\
  \  url: null\n  text: Backups are managed by Supabase under their standard data-handling agreement.\ndeletion:\n  route: email support@hooklayer.dev\n  text: Deletion request via support@hooklayer.dev removes your account and all associated data within 30 days.\nrights:\n- right: access\n  text: Under GDPR, CCPA, and similar regulations, you have the right to access, correct, port, and delete your\n    data.\n- right: delete\n  text: Delete your account and all associated data\n- right: export\n  text: Export your data (request via support email)\n- right: revoke API key\n  text: Revoke any API key from your dashboard\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data to anyone. We do not share data with advertisers or data brokers.\n"
source_yaml_url: https://artifacts.apis.io/hooklayer-dev/privacy/hooklayer-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from hooklayer-dev's own page on 2026-11-09.
synthetic: false
tags:
- MCP
- Artificial Intelligence
- Video
- Marketing
- Analytics
- Content
---
