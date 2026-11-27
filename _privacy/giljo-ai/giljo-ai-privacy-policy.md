---
api_specs:
- filename: giljo-ai-account-deletion-api-openapi.yml
  format: yaml
  label: giljo-ai Account Deletion API
  slug: giljo-ai-account-deletion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-account-deletion-api-openapi.yml
- filename: giljo-ai-account-lifecycle-api-openapi.yml
  format: yaml
  label: giljo-ai Account Lifecycle API
  slug: giljo-ai-account-lifecycle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-account-lifecycle-api-openapi.yml
- filename: giljo-ai-auth-api-openapi.yml
  format: yaml
  label: giljo-ai Auth API
  slug: giljo-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-auth-api-openapi.yml
- filename: giljo-ai-comm-threads-api-openapi.yml
  format: yaml
  label: giljo-ai Comm Threads API
  slug: giljo-ai-comm-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-comm-threads-api-openapi.yml
- filename: giljo-ai-connected-accounts-api-openapi.yml
  format: yaml
  label: giljo-ai Connected Accounts API
  slug: giljo-ai-connected-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-connected-accounts-api-openapi.yml
- filename: giljo-ai-health-api-openapi.yml
  format: yaml
  label: giljo-ai Health API
  slug: giljo-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-health-api-openapi.yml
- filename: giljo-ai-legal-api-openapi.yml
  format: yaml
  label: giljo-ai Legal API
  slug: giljo-ai-legal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-legal-api-openapi.yml
- filename: giljo-ai-oauth-api-openapi.yml
  format: yaml
  label: giljo-ai OAuth API
  slug: giljo-ai-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-oauth-api-openapi.yml
- filename: giljo-ai-oauth-dcr-api-openapi.yml
  format: yaml
  label: giljo-ai OAUTH Dcr API
  slug: giljo-ai-oauth-dcr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-oauth-dcr-api-openapi.yml
- filename: giljo-ai-social-login-api-openapi.yml
  format: yaml
  label: giljo-ai Social Login API
  slug: giljo-ai-social-login-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-social-login-api-openapi.yml
- filename: giljo-ai-task-statuses-api-openapi.yml
  format: yaml
  label: giljo-ai Task Statuses API
  slug: giljo-ai-task-statuses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-task-statuses-api-openapi.yml
- filename: giljo-ai-tasks-api-openapi.yml
  format: yaml
  label: giljo-ai Tasks API
  slug: giljo-ai-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-tasks-api-openapi.yml
- filename: giljo-ai-users-api-openapi.yml
  format: yaml
  label: giljo-ai Users API
  slug: giljo-ai-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-users-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account data: email address and bcrypt-hashed password'
  - category: financial
    text: 'Subscription data: subscription status, plan, billing period'
  - category: device
    text: 'Sign-in and connection records: for each account we keep the IP addresses, browser or agent type'
  - category: other
    text: 'Product content: the product definitions, vision documents, project data, agent configurations, 360 Memory entries'
  - category: other
    text: 'Operational logs: timestamped records of API requests, agent job runs, and errors'
  - category: other
    text: 'Session data: standard authentication session tokens'
  deletion:
    route: account deletion through the dashboard or by contacting support
    text: Delete your account through the dashboard. An email confirmation lets you choose immediate deletion or an optional 30-day grace period.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: deliver the service
    text: processed only to deliver the service
  - purpose: account protection
    text: to protect accounts and to detect an account being shared
  - purpose: service reliability and security
    text: 'Operational logs: retained for a limited period for service reliability and security, then deleted.'
  residency:
  - region: United States
    text: Hosted-service data is stored in the United States.
  - region: US East
    text: with encryption at rest and US East region pinning
  retention:
  - period: null
    scope: active subscription
    text: 'While your subscription is active: we keep your data for as long as your subscription is active.'
  - period: 365 days
    scope: after paid access ends
    text: accounts become eligible for scheduled deletion 365 days after paid access ends
  - period: 90 days
    scope: sign-in and connection records
    text: each record is deleted 90 days after it was last seen
  - period: 6 days
    scope: provider platform snapshots
    text: Our hosting provider also takes daily platform snapshots of the database, kept for 6 days
  - period: seven years
    scope: deletion and legal records
    text: seven years after deletion by default
  rights:
  - right: access
    text: Access your data through the dashboard
  - right: export
    text: Export your full dataset as a downloadable ZIP from the dashboard's data-export feature
  - right: correct
    text: Correct any data through the dashboard, or by emailing us
  - right: object and restrict processing (GDPR/UK GDPR)
    text: the right to object to processing, restrict processing
  - right: complaint and portability (GDPR/UK GDPR)
    text: lodge a complaint with your national data protection authority, and request data portability in a structured format
  - right: know, delete and correct (CCPA/CPRA)
    text: the right to know what personal information we collect, the right to delete it, the right to correct it
  role:
    text: GiljoAI LLC acts as controller for account administration, billing administration, security, and support information where we determine the purposes and means of processing.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share your personal information.
  subprocessors:
    text: The Hosted service relies on the following third-party subprocessors.
    url: null
  transfers:
  - mechanism: SCC
    text: including the European Commission's Standard Contractual Clauses with our subprocessors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: giljo-ai
provenance_date: '2026-11-09'
provider_name: giljo-ai
provider_slug: giljo-ai
slug: giljo-ai-privacy-policy
source_date: '2026-11-09'
source_filename: giljo-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://giljo.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: giljo-ai\naid: giljo-ai\nurl: https://giljo.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: GiljoAI LLC acts as controller for account administration, billing administration, security, and support\n    information where we determine the purposes and means of processing.\ndata_categories:\n- category: contact\n  text: 'Account data: email address and bcrypt-hashed password'\n- category: financial\n  text: 'Subscription data: subscription status, plan, billing period'\n- category: device\n  text: 'Sign-in and connection records: for each account we keep the IP addresses, browser or agent\
  \ type'\n- category: other\n  text: 'Product content: the product definitions, vision documents, project data, agent configurations, 360 Memory\n    entries'\n- category: other\n  text: 'Operational logs: timestamped records of API requests, agent job runs, and errors'\n- category: other\n  text: 'Session data: standard authentication session tokens'\npurposes:\n- purpose: deliver the service\n  text: processed only to deliver the service\n- purpose: account protection\n  text: to protect accounts and to detect an account being shared\n- purpose: service reliability and security\n  text: 'Operational logs: retained for a limited period for service reliability and security, then deleted.'\nretention:\n- scope: active subscription\n  period: null\n  text: 'While your subscription is active: we keep your data for as long as your subscription is active.'\n- scope: after paid access ends\n  period: 365 days\n  text: accounts become eligible for scheduled deletion 365 days after paid access\
  \ ends\n- scope: sign-in and connection records\n  period: 90 days\n  text: each record is deleted 90 days after it was last seen\n- scope: provider platform snapshots\n  period: 6 days\n  text: Our hosting provider also takes daily platform snapshots of the database, kept for 6 days\n- scope: deletion and legal records\n  period: seven years\n  text: seven years after deletion by default\nresidency:\n- region: United States\n  text: Hosted-service data is stored in the United States.\n- region: US East\n  text: with encryption at rest and US East region pinning\ntransfers:\n- mechanism: SCC\n  text: including the European Commission's Standard Contractual Clauses with our subprocessors\nsubprocessors:\n  url: null\n  text: The Hosted service relies on the following third-party subprocessors.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion through the dashboard or by contacting support\n  text: Delete your account through the dashboard. An email\
  \ confirmation lets you choose immediate deletion or an\n    optional 30-day grace period.\nrights:\n- right: access\n  text: Access your data through the dashboard\n- right: export\n  text: Export your full dataset as a downloadable ZIP from the dashboard's data-export feature\n- right: correct\n  text: Correct any data through the dashboard, or by emailing us\n- right: object and restrict processing (GDPR/UK GDPR)\n  text: the right to object to processing, restrict processing\n- right: complaint and portability (GDPR/UK GDPR)\n  text: lodge a complaint with your national data protection authority, and request data portability in a structured\n    format\n- right: know, delete and correct (CCPA/CPRA)\n  text: the right to know what personal information we collect, the right to delete it, the right to correct it\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share your personal information.\n"
source_yaml_url: https://artifacts.apis.io/giljo-ai/privacy/giljo-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from giljo-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- Collaboration
- Platform
---
