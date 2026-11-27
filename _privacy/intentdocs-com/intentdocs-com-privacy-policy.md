---
api_specs:
- filename: intentdocs-com-cli-api-openapi.yml
  format: yaml
  label: intentdocs-com CLI API
  slug: intentdocs-com-cli-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intentdocs-com/openapi/intentdocs-com-cli-api-openapi.yml
- filename: intentdocs-com-mcp-api-openapi.yml
  format: yaml
  label: intentdocs-com MCP API
  slug: intentdocs-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intentdocs-com/openapi/intentdocs-com-mcp-api-openapi.yml
- filename: intentdocs-com-oauth-api-openapi.yml
  format: yaml
  label: intentdocs-com OAuth API
  slug: intentdocs-com-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intentdocs-com/openapi/intentdocs-com-oauth-api-openapi.yml
- filename: intentdocs-com-sync-api-openapi.yml
  format: yaml
  label: intentdocs-com Sync API
  slug: intentdocs-com-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/intentdocs-com/openapi/intentdocs-com-sync-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your email address and any profile information you provide (name, username)
  - category: behavioral
    text: we use PostHog analytics to collect information about how the platform is used — pages visited, features used, session duration — and session recordings of your visit
  - category: financial
    text: We store your Stripe customer ID and subscription status but never have access to your card details.
  - category: communication
    text: If you subscribe to our newsletter, we store your email address via Resend.
  - category: other
    text: Your product ideas, blueprints, story maps, and associated content that you create on the platform.
  deletion:
    route: Settings → Account
    text: Erasure — delete your account and all associated data at any time from Settings → Account
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and improve service
    text: To provide and improve the intentdocs.com service
  - purpose: process payments
    text: To process payments and manage your subscription
  - purpose: transactional emails
    text: To send transactional emails (account notifications, receipts)
  - purpose: newsletter
    text: To send the newsletter, if you have subscribed (you can unsubscribe at any time)
  - purpose: aggregate usage analytics
    text: To understand aggregate usage patterns and improve the product (analytics, with consent only)
  residency:
  - region: EU
    text: Recordings are stored by PostHog on EU servers
  - region: EU
    text: Supabase — database (hosted in EU)
  retention:
  - period: as long as your account is active
    scope: account and project data
    text: 'Account and project data: retained for as long as your account is active. Deleted immediately when you delete your account.'
  - period: 7 years
    scope: payment records
    text: 'Payment records: retained for 7 years as required by UK tax law (HMRC)'
  - period: 2 years
    scope: analytics data
    text: 'Analytics data: retained per PostHog''s retention policy (2 years)'
  - period: null
    scope: session recordings
    text: 'Session recordings: retained per PostHog''s session replay retention policy (a much shorter window than analytics events), then deleted automatically'
  rights:
  - right: access
    text: Access the data we hold about you
  - right: rectification
    text: Rectify inaccurate data
  - right: erasure
    text: Erasure — delete your account and all associated data at any time from Settings → Account
  - right: restrict processing
    text: Restrict processing
  - right: portability
    text: Data portability
  - right: object
    text: Object to processing based on legitimate interests
  role:
    text: intentdocs.com is operated by IntentDocs Limited
    value: controller
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
name: intentdocs-com
provenance_date: '2026-11-09'
provider_name: intentdocs-com
provider_slug: intentdocs-com
slug: intentdocs-com-privacy-policy
source_date: '2026-11-09'
source_filename: intentdocs-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.intentdocs.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: intentdocs-com\naid: intentdocs-com\nurl: https://www.intentdocs.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: intentdocs.com is operated by IntentDocs Limited\ndata_categories:\n- category: identifying\n  text: we collect your email address and any profile information you provide (name, username)\n- category: behavioral\n  text: we use PostHog analytics to collect information about how the platform is used — pages visited, features\n    used, session duration — and session recordings of your visit\n- category: financial\n  text: We store your Stripe customer ID and subscription\
  \ status but never have access to your card details.\n- category: communication\n  text: If you subscribe to our newsletter, we store your email address via Resend.\n- category: other\n  text: Your product ideas, blueprints, story maps, and associated content that you create on the platform.\npurposes:\n- purpose: provide and improve service\n  text: To provide and improve the intentdocs.com service\n- purpose: process payments\n  text: To process payments and manage your subscription\n- purpose: transactional emails\n  text: To send transactional emails (account notifications, receipts)\n- purpose: newsletter\n  text: To send the newsletter, if you have subscribed (you can unsubscribe at any time)\n- purpose: aggregate usage analytics\n  text: To understand aggregate usage patterns and improve the product (analytics, with consent only)\nretention:\n- scope: account and project data\n  period: as long as your account is active\n  text: 'Account and project data: retained for as long as\
  \ your account is active. Deleted immediately when you\n    delete your account.'\n- scope: payment records\n  period: 7 years\n  text: 'Payment records: retained for 7 years as required by UK tax law (HMRC)'\n- scope: analytics data\n  period: 2 years\n  text: 'Analytics data: retained per PostHog''s retention policy (2 years)'\n- scope: session recordings\n  period: null\n  text: 'Session recordings: retained per PostHog''s session replay retention policy (a much shorter window than\n    analytics events), then deleted automatically'\nresidency:\n- region: EU\n  text: Recordings are stored by PostHog on EU servers\n- region: EU\n  text: Supabase — database (hosted in EU)\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings → Account\n  text: Erasure — delete your account and all associated data at any time from Settings → Account\nrights:\n- right: access\n  text: Access the data we hold about you\n\
  - right: rectification\n  text: Rectify inaccurate data\n- right: erasure\n  text: Erasure — delete your account and all associated data at any time from Settings → Account\n- right: restrict processing\n  text: Restrict processing\n- right: portability\n  text: Data portability\n- right: object\n  text: Object to processing based on legitimate interests\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/intentdocs-com/privacy/intentdocs-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 24 quoted statements, read from intentdocs-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Spec-Driven
- Platform
- Automation
- Low-Code
---
