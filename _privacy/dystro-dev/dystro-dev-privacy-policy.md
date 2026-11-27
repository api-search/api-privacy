---
api_specs:
- filename: dystro-dev-accounts-api-openapi.yml
  format: yaml
  label: dystro-dev Accounts API
  slug: dystro-dev-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-accounts-api-openapi.yml
- filename: dystro-dev-analytics-api-openapi.yml
  format: yaml
  label: dystro-dev Analytics API
  slug: dystro-dev-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-analytics-api-openapi.yml
- filename: dystro-dev-api-keys-api-openapi.yml
  format: yaml
  label: dystro-dev API Keys API
  slug: dystro-dev-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-api-keys-api-openapi.yml
- filename: dystro-dev-campaigns-api-openapi.yml
  format: yaml
  label: dystro-dev Campaigns API
  slug: dystro-dev-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-campaigns-api-openapi.yml
- filename: dystro-dev-connect-api-openapi.yml
  format: yaml
  label: dystro-dev Connect API
  slug: dystro-dev-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-connect-api-openapi.yml
- filename: dystro-dev-inbox-api-openapi.yml
  format: yaml
  label: dystro-dev Inbox API
  slug: dystro-dev-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-inbox-api-openapi.yml
- filename: dystro-dev-media-api-openapi.yml
  format: yaml
  label: dystro-dev Media API
  slug: dystro-dev-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-media-api-openapi.yml
- filename: dystro-dev-meta-api-openapi.yml
  format: yaml
  label: dystro-dev Meta API
  slug: dystro-dev-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-meta-api-openapi.yml
- filename: dystro-dev-posts-api-openapi.yml
  format: yaml
  label: dystro-dev Posts API
  slug: dystro-dev-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-posts-api-openapi.yml
- filename: dystro-dev-queue-api-openapi.yml
  format: yaml
  label: dystro-dev Queue API
  slug: dystro-dev-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-queue-api-openapi.yml
- filename: dystro-dev-webhooks-api-openapi.yml
  format: yaml
  label: dystro-dev Webhooks API
  slug: dystro-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dystro-dev/openapi/dystro-dev-webhooks-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information — name, email address, organization details, and authentication identifiers when you sign up.
  - category: contact
    text: name, email address, organization details, and authentication identifiers when you sign up
  - category: communication
    text: Communications — messages you send us for support or sales.
  - category: behavioral
    text: engagement data such as comments, mentions, messages, and metrics
  - category: device
    text: log data (including IP address and device/browser metadata)
  - category: other
    text: access and refresh tokens
  deletion:
    route: Dashboard disconnection or account/data deletion request; see Data Deletion page
    text: You can disconnect any social account at any time from the dashboard, and you can request deletion of your account and data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate the Service
    text: To operate the Service — authenticate you, connect accounts, and publish, schedule, and manage content you direct us to.
  - purpose: Deliver enabled features
    text: To deliver features you enable — media transcoding, webhooks and unified inbox, analytics, and approval workflows.
  - purpose: Security and abuse prevention
    text: To maintain security, prevent abuse and spam, and enforce rate limits and our Terms.
  - purpose: Support
    text: To provide support and communicate with you about the Service.
  - purpose: Reliability improvement
    text: To improve reliability and performance using aggregated, non-identifying diagnostics.
  retention:
  - period: null
    scope: Account information
    text: We keep account information for as long as your account is active.
  - period: null
    scope: Content and connected-platform data
    text: Content and connected-platform data are retained while the relevant account is connected and for a limited period afterward to support recovery and audit, then deleted or anonymized.
  - period: null
    scope: Access and refresh tokens
    text: Access and refresh tokens are deleted promptly when you disconnect an account or delete your account.
  rights:
  - right: access, correct, export, restrict, delete
    text: Depending on your location, you may have rights to access, correct, export, restrict, or delete your personal data, and to withdraw consent.
  - right: CCPA/CPRA right to know and delete
    text: California residents have rights under the CCPA/CPRA, including the right to know and delete
  role:
    text: If your social account was connected to Dystro by a business you work with, that business is the controller of your data
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We never sell personal information.
  subprocessors:
    text: 'We use the following categories of sub-processors: Sub-processor Purpose Convex Application database & backend runtime Cloudflare (R2, Pages, network) Media storage, content delivery, hosting WorkOS Authentication & identity Stripe Billing & payment processing Resend Transactional email Upstash Caching & rate limiting PostHog Product analytics & error tracking'
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we rely on appropriate safeguards such as Standard Contractual Clauses for cross-border transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: dystro-dev
provenance_date: '2026-11-09'
provider_name: dystro-dev
provider_slug: dystro-dev
slug: dystro-dev-privacy-policy
source_date: '2026-11-09'
source_filename: dystro-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dystro.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: dystro-dev\naid: dystro-dev\nurl: https://dystro.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: If your social account was connected to Dystro by a business you work with, that business is the controller\n    of your data\ndata_categories:\n- category: identifying\n  text: Account information — name, email address, organization details, and authentication identifiers when you\n    sign up.\n- category: contact\n  text: name, email address, organization details, and authentication identifiers when you sign up\n- category: communication\n  text: Communications — messages you send us for\
  \ support or sales.\n- category: behavioral\n  text: engagement data such as comments, mentions, messages, and metrics\n- category: device\n  text: log data (including IP address and device/browser metadata)\n- category: other\n  text: access and refresh tokens\npurposes:\n- purpose: Operate the Service\n  text: To operate the Service — authenticate you, connect accounts, and publish, schedule, and manage content you\n    direct us to.\n- purpose: Deliver enabled features\n  text: To deliver features you enable — media transcoding, webhooks and unified inbox, analytics, and approval\n    workflows.\n- purpose: Security and abuse prevention\n  text: To maintain security, prevent abuse and spam, and enforce rate limits and our Terms.\n- purpose: Support\n  text: To provide support and communicate with you about the Service.\n- purpose: Reliability improvement\n  text: To improve reliability and performance using aggregated, non-identifying diagnostics.\nretention:\n- scope: Account information\n\
  \  period: null\n  text: We keep account information for as long as your account is active.\n- scope: Content and connected-platform data\n  period: null\n  text: Content and connected-platform data are retained while the relevant account is connected and for a limited\n    period afterward to support recovery and audit, then deleted or anonymized.\n- scope: Access and refresh tokens\n  period: null\n  text: Access and refresh tokens are deleted promptly when you disconnect an account or delete your account.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on appropriate safeguards such as Standard Contractual Clauses for cross-border\n    transfers.\nsubprocessors:\n  url: null\n  text: 'We use the following categories of sub-processors: Sub-processor Purpose Convex Application database &\n    backend runtime Cloudflare (R2, Pages, network) Media storage, content delivery, hosting WorkOS Authentication\n    & identity Stripe Billing & payment processing Resend\
  \ Transactional email Upstash Caching & rate limiting PostHog\n    Product analytics & error tracking'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Dashboard disconnection or account/data deletion request; see Data Deletion page\n  text: You can disconnect any social account at any time from the dashboard, and you can request deletion of your\n    account and data.\nrights:\n- right: access, correct, export, restrict, delete\n  text: Depending on your location, you may have rights to access, correct, export, restrict, or delete your personal\n    data, and to withdraw consent.\n- right: CCPA/CPRA right to know and delete\n  text: California residents have rights under the CCPA/CPRA, including the right to know and delete\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/dystro-dev/privacy/dystro-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from dystro-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developers
- Technology
- Integration
---
