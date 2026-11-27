---
api_specs:
- filename: antwork-io-accounts-api-openapi.yml
  format: yaml
  label: Antwork Accounts API
  slug: antwork-io-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antwork-io/openapi/antwork-io-accounts-api-openapi.yml
- filename: antwork-io-analytics-api-openapi.yml
  format: yaml
  label: Antwork Analytics API
  slug: antwork-io-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antwork-io/openapi/antwork-io-analytics-api-openapi.yml
- filename: antwork-io-campaigns-api-openapi.yml
  format: yaml
  label: Antwork Campaigns API
  slug: antwork-io-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antwork-io/openapi/antwork-io-campaigns-api-openapi.yml
- filename: antwork-io-media-api-openapi.yml
  format: yaml
  label: Antwork Media API
  slug: antwork-io-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antwork-io/openapi/antwork-io-media-api-openapi.yml
- filename: antwork-io-platforms-api-openapi.yml
  format: yaml
  label: Antwork Platforms API
  slug: antwork-io-platforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antwork-io/openapi/antwork-io-platforms-api-openapi.yml
- filename: antwork-io-posts-api-openapi.yml
  format: yaml
  label: Antwork Posts API
  slug: antwork-io-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antwork-io/openapi/antwork-io-posts-api-openapi.yml
- filename: antwork-io-usage-api-openapi.yml
  format: yaml
  label: Antwork Usage API
  slug: antwork-io-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antwork-io/openapi/antwork-io-usage-api-openapi.yml
- filename: antwork-io-workspaces-api-openapi.yml
  format: yaml
  label: Antwork Workspaces API
  slug: antwork-io-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/antwork-io/openapi/antwork-io-workspaces-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and email address
  - category: contact
    text: Name and email address
  - category: financial
    text: Payment and billing information (processed securely through Stripe)
  - category: device
    text: Device information and IP addresses
  - category: behavioral
    text: Product analytics events tied to your account identifier (PostHog)
  - category: communication
    text: Posts and drafts you or the AI assistant you connect create, schedule or publish
  deletion:
    route: Data Deletion Request page at /data-deletion-request, or email to iker.gonzalez@antwork.io
    text: We provide a dedicated Data Deletion Request page that allows you to request deletion of your connected social media account data.
  dpa:
    available: null
    text: engagement metrics of posts published through Antwork are analysed in our product analytics provider (PostHog) under a data processing agreement.
    url: null
  purposes:
  - purpose: Run the service
    text: 'Run the service: Let you, and the AI assistant you connect, draft, schedule and publish posts to your connected accounts'
  - purpose: Enable collaboration
    text: 'Enable collaboration: Support workspace and team management features'
  - purpose: Communicate with you
    text: 'Communicate with you: Send service-related notifications, respond to support requests, and (with your consent) send marketing communications using only your Antwork account information'
  - purpose: Improve platform
    text: 'Improve our platform: Analyze usage patterns to enhance features, ensure security, and prevent fraud'
  residency:
  - region: EU (Google OAuth tokens)
    text: Google OAuth tokens are encrypted and stored in Google Cloud (Firestore) in the EU region and are used only by our servers.
  retention:
  - period: within 30 days
    scope: Account data after account deletion
    text: When you delete your account, we will delete your personal information, workspaces, campaigns and scheduled posts within 30 days, except where retention is required by law.
  - period: up to 14 weeks
    scope: Encrypted backups
    text: Deleted data can remain in our encrypted backups for up to 14 weeks, which exist only to restore the service
  - period: within 30 days
    scope: Google user data after account deletion
    text: When you delete your Antwork account, your Google profile data, tokens and stored video statistics are deleted within 30 days.
  rights:
  - right: Access
    text: 'Access: Request a copy of your personal information, posts and usage statistics'
  - right: Correction
    text: 'Correction: Update or correct inaccurate information, including your workspace details'
  - right: Deletion
    text: 'Deletion: Request deletion of your personal information, workspaces and associated content'
  - right: Portability
    text: 'Portability: Export your data in a portable format, including posts and campaigns'
  - right: Opt-out
    text: 'Opt-out: Unsubscribe from marketing communications'
  role:
    text: 'Antwork is operated by: Company Name: POLYNODE TECHNOLOGIES, SL'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, trade, or rent your personal information to third parties.
  subprocessors:
    text: 5.1 Service Providers › Google Cloud Platform (hosting, infrastructure, and Cloud Tasks for scheduled publishing) › Firebase (authentication and database) › PostHog (product analytics, session recording, and analysis of post engagement metrics) › Stripe (payment processing)
    url: null
  transfers:
  - mechanism: SCC
    text: Standard contractual clauses
  - mechanism: adequacy
    text: Adequacy decisions by relevant authorities
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Antwork
provenance_date: '2026-11-09'
provider_name: Antwork
provider_slug: antwork-io
slug: antwork-io-privacy-policy
source_date: '2026-11-09'
source_filename: antwork-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://antwork.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Antwork\naid: antwork-io\nurl: https://antwork.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Antwork is operated by: Company Name: POLYNODE TECHNOLOGIES, SL'\ndata_categories:\n- category: identifying\n  text: Name and email address\n- category: contact\n  text: Name and email address\n- category: financial\n  text: Payment and billing information (processed securely through Stripe)\n- category: device\n  text: Device information and IP addresses\n- category: behavioral\n  text: Product analytics events tied to your account identifier (PostHog)\n- category: communication\n  text:\
  \ Posts and drafts you or the AI assistant you connect create, schedule or publish\npurposes:\n- purpose: Run the service\n  text: 'Run the service: Let you, and the AI assistant you connect, draft, schedule and publish posts to your connected\n    accounts'\n- purpose: Enable collaboration\n  text: 'Enable collaboration: Support workspace and team management features'\n- purpose: Communicate with you\n  text: 'Communicate with you: Send service-related notifications, respond to support requests, and (with your consent)\n    send marketing communications using only your Antwork account information'\n- purpose: Improve platform\n  text: 'Improve our platform: Analyze usage patterns to enhance features, ensure security, and prevent fraud'\nretention:\n- scope: Account data after account deletion\n  period: within 30 days\n  text: When you delete your account, we will delete your personal information, workspaces, campaigns and scheduled\n    posts within 30 days, except where retention is\
  \ required by law.\n- scope: Encrypted backups\n  period: up to 14 weeks\n  text: Deleted data can remain in our encrypted backups for up to 14 weeks, which exist only to restore the service\n- scope: Google user data after account deletion\n  period: within 30 days\n  text: When you delete your Antwork account, your Google profile data, tokens and stored video statistics are deleted\n    within 30 days.\nresidency:\n- region: EU (Google OAuth tokens)\n  text: Google OAuth tokens are encrypted and stored in Google Cloud (Firestore) in the EU region and are used only\n    by our servers.\ntransfers:\n- mechanism: SCC\n  text: Standard contractual clauses\n- mechanism: adequacy\n  text: Adequacy decisions by relevant authorities\nsubprocessors:\n  url: null\n  text: 5.1 Service Providers › Google Cloud Platform (hosting, infrastructure, and Cloud Tasks for scheduled publishing)\n    › Firebase (authentication and database) › PostHog (product analytics, session recording, and analysis of\
  \ post\n    engagement metrics) › Stripe (payment processing)\ndpa:\n  available: null\n  url: null\n  text: engagement metrics of posts published through Antwork are analysed in our product analytics provider (PostHog)\n    under a data processing agreement.\ndeletion:\n  route: Data Deletion Request page at /data-deletion-request, or email to iker.gonzalez@antwork.io\n  text: We provide a dedicated Data Deletion Request page that allows you to request deletion of your connected\n    social media account data.\nrights:\n- right: Access\n  text: 'Access: Request a copy of your personal information, posts and usage statistics'\n- right: Correction\n  text: 'Correction: Update or correct inaccurate information, including your workspace details'\n- right: Deletion\n  text: 'Deletion: Request deletion of your personal information, workspaces and associated content'\n- right: Portability\n  text: 'Portability: Export your data in a portable format, including posts and campaigns'\n- right: Opt-out\n\
  \  text: 'Opt-out: Unsubscribe from marketing communications'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, trade, or rent your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/antwork-io/privacy/antwork-io-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Antwork's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Social Media
- Automation
- Scheduler
- Marketing
---
