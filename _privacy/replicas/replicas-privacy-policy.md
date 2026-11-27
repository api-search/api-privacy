---
api_specs:
- filename: replicas-analytics-api-openapi.yml
  format: yaml
  label: Replicas Analytics API
  slug: replicas-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicas/openapi/replicas-analytics-api-openapi.yml
- filename: replicas-api-keys-api-openapi.yml
  format: yaml
  label: Replicas API Keys API
  slug: replicas-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicas/openapi/replicas-api-keys-api-openapi.yml
- filename: replicas-automation-api-openapi.yml
  format: yaml
  label: Replicas Automation API
  slug: replicas-automation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicas/openapi/replicas-automation-api-openapi.yml
- filename: replicas-credentials-api-openapi.yml
  format: yaml
  label: Replicas Credentials API
  slug: replicas-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicas/openapi/replicas-credentials-api-openapi.yml
- filename: replicas-downloads-api-openapi.yml
  format: yaml
  label: Replicas Downloads API
  slug: replicas-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicas/openapi/replicas-downloads-api-openapi.yml
- filename: replicas-environments-api-openapi.yml
  format: yaml
  label: Replicas Environments API
  slug: replicas-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicas/openapi/replicas-environments-api-openapi.yml
- filename: replicas-google-search-console-api-openapi.yml
  format: yaml
  label: Replicas Google Search Console API
  slug: replicas-google-search-console-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicas/openapi/replicas-google-search-console-api-openapi.yml
- filename: replicas-preview-api-openapi.yml
  format: yaml
  label: Replicas Preview API
  slug: replicas-preview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicas/openapi/replicas-preview-api-openapi.yml
- filename: replicas-profile-api-openapi.yml
  format: yaml
  label: Replicas Profile API
  slug: replicas-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicas/openapi/replicas-profile-api-openapi.yml
- filename: replicas-replica-api-openapi.yml
  format: yaml
  label: Replicas Replica API
  slug: replicas-replica-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicas/openapi/replicas-replica-api-openapi.yml
- filename: replicas-repository-api-openapi.yml
  format: yaml
  label: Replicas Repository API
  slug: replicas-repository-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicas/openapi/replicas-repository-api-openapi.yml
- filename: replicas-slack-api-openapi.yml
  format: yaml
  label: Replicas Slack API
  slug: replicas-slack-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicas/openapi/replicas-slack-api-openapi.yml
- filename: replicas-terminal-api-openapi.yml
  format: yaml
  label: Replicas Terminal API
  slug: replicas-terminal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replicas/openapi/replicas-terminal-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information (name, email address, password)
  - category: financial
    text: Payment information (processed securely through third-party payment processors)
  - category: behavioral
    text: Session replays of interactions with the Service
  - category: device
    text: Log data (IP addresses, browser type, access times, pages viewed)
  - category: communication
    text: 'Slack: workspace IDs and channel references (not message contents)'
  deletion:
    route: Account → Delete account in iOS app; or email founders@replicas.dev
    text: In the iOS app, open Account → Delete account to initiate permanent account deletion.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain, and improve the Service
    text: Provide, maintain, and improve the Service
  - purpose: Process transactions and manage subscription
    text: Process transactions and manage your subscription
  - purpose: Detect and prevent fraud
    text: Detect, prevent, and address technical issues or fraudulent activity
  - purpose: Comply with legal obligations
    text: Comply with legal obligations
  retention:
  - period: null
    scope: Workspace data
    text: All workspace data, code, files, environment variables, and credentials are permanently deleted when a workspace is destroyed.
  - period: null
    scope: In-chat media
    text: This media is retained until you request its deletion.
  - period: null
    scope: Analytics and session replay
    text: PostHog analytics events and masked session replays are retained only while needed to analyze and improve the Service, subject to our configured PostHog retention settings and applicable legal obligations.
  - period: 30 days
    scope: Account deletion
    text: We complete requests within 30 days and send an email confirmation.
  rights:
  - right: Access or deletion of analytics data
    text: You may request access to or deletion of analytics data associated with your account by emailing founders@replicas.dev .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Replicas
provenance_date: '2026-11-10'
provider_name: Replicas
provider_slug: replicas
slug: replicas-privacy-policy
source_date: '2026-11-10'
source_filename: replicas-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://replicas.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Replicas\naid: replicas\nurl: https://replicas.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information (name, email address, password)\n- category: financial\n  text: Payment information (processed securely through third-party payment processors)\n- category: behavioral\n  text: Session replays of interactions with the Service\n- category: device\n  text: Log data (IP addresses, browser type, access times, pages viewed)\n- category: communication\n  text: 'Slack: workspace IDs and channel references (not message\
  \ contents)'\npurposes:\n- purpose: Provide, maintain, and improve the Service\n  text: Provide, maintain, and improve the Service\n- purpose: Process transactions and manage subscription\n  text: Process transactions and manage your subscription\n- purpose: Detect and prevent fraud\n  text: Detect, prevent, and address technical issues or fraudulent activity\n- purpose: Comply with legal obligations\n  text: Comply with legal obligations\nretention:\n- scope: Workspace data\n  period: null\n  text: All workspace data, code, files, environment variables, and credentials are permanently deleted when a workspace\n    is destroyed.\n- scope: In-chat media\n  period: null\n  text: This media is retained until you request its deletion.\n- scope: Analytics and session replay\n  period: null\n  text: PostHog analytics events and masked session replays are retained only while needed to analyze and improve\n    the Service, subject to our configured PostHog retention settings and applicable legal\
  \ obligations.\n- scope: Account deletion\n  period: 30 days\n  text: We complete requests within 30 days and send an email confirmation.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account → Delete account in iOS app; or email founders@replicas.dev\n  text: In the iOS app, open Account → Delete account to initiate permanent account deletion.\nrights:\n- right: Access or deletion of analytics data\n  text: You may request access to or deletion of analytics data associated with your account by emailing founders@replicas.dev\n    .\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/replicas/privacy/replicas-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Replicas's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Coding Agents
- Developer Tools
- Automation
- Cloud Workspaces
- MCP
- DevOps
---
