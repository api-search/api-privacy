---
api_specs:
- filename: autoposting-ai-agents-api-openapi.yml
  format: yaml
  label: Autoposting.ai Agents API
  slug: autoposting-ai-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-agents-api-openapi.yml
- filename: autoposting-ai-api-keys-api-openapi.yml
  format: yaml
  label: Autoposting.ai API Keys API
  slug: autoposting-ai-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-api-keys-api-openapi.yml
- filename: autoposting-ai-auth-api-openapi.yml
  format: yaml
  label: Autoposting.ai Auth API
  slug: autoposting-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-auth-api-openapi.yml
- filename: autoposting-ai-billing-api-openapi.yml
  format: yaml
  label: Autoposting.ai Billing API
  slug: autoposting-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-billing-api-openapi.yml
- filename: autoposting-ai-brands-api-openapi.yml
  format: yaml
  label: Autoposting.ai Brands API
  slug: autoposting-ai-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-brands-api-openapi.yml
- filename: autoposting-ai-carousels-api-openapi.yml
  format: yaml
  label: Autoposting.ai Carousels API
  slug: autoposting-ai-carousels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-carousels-api-openapi.yml
- filename: autoposting-ai-clips-api-openapi.yml
  format: yaml
  label: Autoposting.ai Clips API
  slug: autoposting-ai-clips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-clips-api-openapi.yml
- filename: autoposting-ai-knowledge-base-api-openapi.yml
  format: yaml
  label: Autoposting.ai Knowledge Base API
  slug: autoposting-ai-knowledge-base-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-knowledge-base-api-openapi.yml
- filename: autoposting-ai-notifications-api-openapi.yml
  format: yaml
  label: Autoposting.ai Notifications API
  slug: autoposting-ai-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-notifications-api-openapi.yml
- filename: autoposting-ai-organizations-api-openapi.yml
  format: yaml
  label: Autoposting.ai Organizations API
  slug: autoposting-ai-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-organizations-api-openapi.yml
- filename: autoposting-ai-platform-oauth-api-openapi.yml
  format: yaml
  label: Autoposting.ai Platform OAuth API
  slug: autoposting-ai-platform-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-platform-oauth-api-openapi.yml
- filename: autoposting-ai-posts-api-openapi.yml
  format: yaml
  label: Autoposting.ai Posts API
  slug: autoposting-ai-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-posts-api-openapi.yml
- filename: autoposting-ai-teams-api-openapi.yml
  format: yaml
  label: Autoposting.ai Teams API
  slug: autoposting-ai-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-teams-api-openapi.yml
- filename: autoposting-ai-usage-api-openapi.yml
  format: yaml
  label: Autoposting.ai Usage API
  slug: autoposting-ai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-usage-api-openapi.yml
- filename: autoposting-ai-webhooks-api-openapi.yml
  format: yaml
  label: Autoposting.ai Webhooks API
  slug: autoposting-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoposting-ai/openapi/autoposting-ai-webhooks-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, and password (hashed, never stored in plaintext)
  - category: contact
    text: Organization name and billing contact details
  - category: communication
    text: Posts, captions, images, and videos you create or schedule
  - category: behavioral
    text: Feature usage patterns (aggregated and anonymized)
  - category: device
    text: Log data (IP address, browser type, pages visited, timestamps)
  - category: financial
    text: Subscription plan and billing history
  deletion:
    route: Email request or in-app Disconnect; Meta data deletion via /data-deletion page
    text: 'Email: Contact [email protected] and we will process your request within 30 days.'
  dpa:
    available: true
    text: For business customers who require a Data Processing Agreement (DPA) for GDPR compliance, please contact us at [email protected] . We will provide a signed DPA upon request.
    url: null
  purposes:
  - purpose: Operate the platform
    text: Operate the platform – authenticate sessions, schedule and publish posts, manage your connected accounts
  - purpose: Process payments
    text: Process payments – manage subscriptions and AI credit balances
  - purpose: Send notifications
    text: Send notifications – publishing confirmations, billing alerts, security notices (configurable in preferences)
  - purpose: Improve the product
    text: Improve the product – analyze aggregated usage patterns, fix bugs, develop new features
  - purpose: Comply with legal obligations
    text: Comply with legal obligations – respond to lawful requests from authorities
  retention:
  - period: null
    scope: Active account data
    text: Active account data is retained while your account is active
  - period: 7 years
    scope: Billing records
    text: Billing records are retained for 7 years as required by law
  - period: null
    scope: OAuth tokens
    text: OAuth tokens are deleted when you successfully disconnect a social account.
  - period: 30 days
    scope: YouTube raw view, like and comment counts
    text: Raw YouTube view, like and comment counts are retained for no more than 30 days.
  rights:
  - right: Access
    text: Access – Request a copy of all personal data we hold about you
  - right: Erasure
    text: Erasure – Request deletion of your account and associated data
  - right: Portability
    text: Portability – Export your data in a machine-readable format (JSON/CSV)
  - right: Objection
    text: Objection – Object to processing based on legitimate interests
  - right: Know (CCPA)
    text: Know – What personal information we collect and how it is used
  - right: Delete (CCPA)
    text: Delete – Request deletion of your personal information
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data to third parties. Ever.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we use appropriate safeguards including Standard Contractual Clauses (SCCs) approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Autoposting.ai
provenance_date: '2026-11-09'
provider_name: Autoposting.ai
provider_slug: autoposting-ai
slug: autoposting-ai-privacy-policy
source_date: '2026-11-09'
source_filename: autoposting-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://autoposting.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Autoposting.ai\naid: autoposting-ai\nurl: https://autoposting.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email address, and password (hashed, never stored in plaintext)\n- category: contact\n  text: Organization name and billing contact details\n- category: communication\n  text: Posts, captions, images, and videos you create or schedule\n- category: behavioral\n  text: Feature usage patterns (aggregated and anonymized)\n- category: device\n  text: Log data (IP address, browser type, pages visited, timestamps)\n- category:\
  \ financial\n  text: Subscription plan and billing history\npurposes:\n- purpose: Operate the platform\n  text: Operate the platform – authenticate sessions, schedule and publish posts, manage your connected accounts\n- purpose: Process payments\n  text: Process payments – manage subscriptions and AI credit balances\n- purpose: Send notifications\n  text: Send notifications – publishing confirmations, billing alerts, security notices (configurable in preferences)\n- purpose: Improve the product\n  text: Improve the product – analyze aggregated usage patterns, fix bugs, develop new features\n- purpose: Comply with legal obligations\n  text: Comply with legal obligations – respond to lawful requests from authorities\nretention:\n- scope: Active account data\n  period: null\n  text: Active account data is retained while your account is active\n- scope: Billing records\n  period: 7 years\n  text: Billing records are retained for 7 years as required by law\n- scope: OAuth tokens\n  period:\
  \ null\n  text: OAuth tokens are deleted when you successfully disconnect a social account.\n- scope: YouTube raw view, like and comment counts\n  period: 30 days\n  text: Raw YouTube view, like and comment counts are retained for no more than 30 days.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we use appropriate safeguards including Standard Contractual Clauses (SCCs) approved by the European Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: For business customers who require a Data Processing Agreement (DPA) for GDPR compliance, please contact\n    us at [email protected] . We will provide a signed DPA upon request.\ndeletion:\n  route: Email request or in-app Disconnect; Meta data deletion via /data-deletion page\n  text: 'Email: Contact [email protected] and we will process your request within 30 days.'\nrights:\n- right: Access\n  text: Access – Request a copy of all personal data we hold about you\n- right: Erasure\n \
  \ text: Erasure – Request deletion of your account and associated data\n- right: Portability\n  text: Portability – Export your data in a machine-readable format (JSON/CSV)\n- right: Objection\n  text: Objection – Object to processing based on legitimate interests\n- right: Know (CCPA)\n  text: Know – What personal information we collect and how it is used\n- right: Delete (CCPA)\n  text: Delete – Request deletion of your personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data to third parties. Ever.\n"
source_yaml_url: https://artifacts.apis.io/autoposting-ai/privacy/autoposting-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Autoposting.ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Social Media
- Automation
- Marketing
- Developer Tools
- Company
---
