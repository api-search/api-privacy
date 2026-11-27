---
api_specs:
- filename: composio-auth-configs-api-openapi.yml
  format: yaml
  label: Composio Auth Configs API
  slug: composio-auth-configs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-auth-configs-api-openapi.yml
- filename: composio-authentication-api-openapi.yml
  format: yaml
  label: Composio Authentication API
  slug: composio-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-authentication-api-openapi.yml
- filename: composio-cli-api-openapi.yml
  format: yaml
  label: Composio CLI API
  slug: composio-cli-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-cli-api-openapi.yml
- filename: composio-cli-authentication-api-openapi.yml
  format: yaml
  label: Composio CLI Authentication API
  slug: composio-cli-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-cli-authentication-api-openapi.yml
- filename: composio-connected-accounts-api-openapi.yml
  format: yaml
  label: Composio Connected Accounts API
  slug: composio-connected-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-connected-accounts-api-openapi.yml
- filename: composio-files-api-openapi.yml
  format: yaml
  label: Composio Files API
  slug: composio-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-files-api-openapi.yml
- filename: composio-logs-api-openapi.yml
  format: yaml
  label: Composio Logs API
  slug: composio-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-logs-api-openapi.yml
- filename: composio-mcp-api-openapi.yml
  format: yaml
  label: Composio MCP API
  slug: composio-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-mcp-api-openapi.yml
- filename: composio-migration-api-openapi.yml
  format: yaml
  label: Composio Migration API
  slug: composio-migration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-migration-api-openapi.yml
- filename: composio-organization-management-api-openapi.yml
  format: yaml
  label: Composio Organization Management API
  slug: composio-organization-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-organization-management-api-openapi.yml
- filename: composio-projects-api-openapi.yml
  format: yaml
  label: Composio Projects API
  slug: composio-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-projects-api-openapi.yml
- filename: composio-tool-router-api-openapi.yml
  format: yaml
  label: Composio Tool Router API
  slug: composio-tool-router-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-tool-router-api-openapi.yml
- filename: composio-toolkits-api-openapi.yml
  format: yaml
  label: Composio Toolkits API
  slug: composio-toolkits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-toolkits-api-openapi.yml
- filename: composio-tools-api-openapi.yml
  format: yaml
  label: Composio Tools API
  slug: composio-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-tools-api-openapi.yml
- filename: composio-triggers-api-openapi.yml
  format: yaml
  label: Composio Triggers API
  slug: composio-triggers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-triggers-api-openapi.yml
- filename: composio-webhook-endpoints-api-openapi.yml
  format: yaml
  label: Composio Webhook Endpoints API
  slug: composio-webhook-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-webhook-endpoints-api-openapi.yml
- filename: composio-webhook-subscriptions-api-openapi.yml
  format: yaml
  label: Composio Webhook Subscriptions API
  slug: composio-webhook-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-webhook-subscriptions-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personally identifiable information, such as your name, email address, and other contact details
  - category: device
    text: Information our servers automatically collect when you access the platform, such as your IP address, browser type, operating system
  - category: communication
    text: the request arguments and response data of each call, and the payloads of trigger events
  deletion:
    route: Contact support@composio.dev or request deletion
    text: Deletion requests are completed as described in Section 6.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve core platform functionality
    text: We use your information strictly for providing and improving our platform’s core functionality.
  - purpose: Account management
    text: Facilitate the creation and management of your account on our platform
  - purpose: Legal compliance
    text: Comply with legal obligations
  retention:
  - period: one year
    scope: Payload data
    text: Payload data that we store is kept in execution logs and automatically deleted one year after the call.
  - period: 30 calendar days
    scope: YouTube API data
    text: YouTube API data is retained for a maximum of 30 calendar days
  - period: until you ask us to delete it
    scope: Account data
    text: We retain account data about your organization and its members, such as names, email addresses, and organization and developer records, until you ask us to delete it.
  rights:
  - right: Access
    text: Access your personal data
  - right: Correction
    text: Request corrections to your data
  - right: Deletion
    text: Request deletion of your data
  - right: Withdraw consent
    text: Withdraw consent for data processing
  - right: Portability
    text: Receive a copy of your data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell your Google user data
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Composio
provenance_date: '2026-11-09'
provider_name: Composio
provider_slug: composio
slug: composio-privacy-policy
source_date: '2026-11-09'
source_filename: composio-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://composio.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Composio\naid: composio\nurl: https://composio.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Personally identifiable information, such as your name, email address, and other contact details\n- category: device\n  text: Information our servers automatically collect when you access the platform, such as your IP address, browser\n    type, operating system\n- category: communication\n  text: the request arguments and response data of each call, and the payloads of trigger events\npurposes:\n- purpose: Provide and improve core\
  \ platform functionality\n  text: We use your information strictly for providing and improving our platform’s core functionality.\n- purpose: Account management\n  text: Facilitate the creation and management of your account on our platform\n- purpose: Legal compliance\n  text: Comply with legal obligations\nretention:\n- scope: Payload data\n  period: one year\n  text: Payload data that we store is kept in execution logs and automatically deleted one year after the call.\n- scope: YouTube API data\n  period: 30 calendar days\n  text: YouTube API data is retained for a maximum of 30 calendar days\n- scope: Account data\n  period: until you ask us to delete it\n  text: We retain account data about your organization and its members, such as names, email addresses, and organization\n    and developer records, until you ask us to delete it.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact\
  \ support@composio.dev or request deletion\n  text: Deletion requests are completed as described in Section 6.\nrights:\n- right: Access\n  text: Access your personal data\n- right: Correction\n  text: Request corrections to your data\n- right: Deletion\n  text: Request deletion of your data\n- right: Withdraw consent\n  text: Withdraw consent for data processing\n- right: Portability\n  text: Receive a copy of your data\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell your Google user data\n"
source_yaml_url: https://artifacts.apis.io/composio/privacy/composio-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Composio's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Authentication
- Integration
- MCP
- OAuth
- Sandbox
- Tools
- Triggers
- Unified API
- Webhook
---
