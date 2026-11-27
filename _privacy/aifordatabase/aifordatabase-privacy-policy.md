---
api_specs:
- filename: aifordatabase-chat-api-openapi.yml
  format: yaml
  label: AI for Database Chat API
  slug: aifordatabase-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-chat-api-openapi.yml
- filename: aifordatabase-connections-api-openapi.yml
  format: yaml
  label: AI for Database Connections API
  slug: aifordatabase-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-connections-api-openapi.yml
- filename: aifordatabase-conversations-api-openapi.yml
  format: yaml
  label: AI for Database Conversations API
  slug: aifordatabase-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-conversations-api-openapi.yml
- filename: aifordatabase-dashboards-api-openapi.yml
  format: yaml
  label: AI for Database Dashboards API
  slug: aifordatabase-dashboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-dashboards-api-openapi.yml
- filename: aifordatabase-keys-api-openapi.yml
  format: yaml
  label: AI for Database Keys API
  slug: aifordatabase-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-keys-api-openapi.yml
- filename: aifordatabase-metrics-api-openapi.yml
  format: yaml
  label: AI for Database Metrics API
  slug: aifordatabase-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-metrics-api-openapi.yml
- filename: aifordatabase-query-approval-api-openapi.yml
  format: yaml
  label: AI for Database Query Approval API
  slug: aifordatabase-query-approval-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-query-approval-api-openapi.yml
- filename: aifordatabase-saved-queries-api-openapi.yml
  format: yaml
  label: AI for Database Saved Queries API
  slug: aifordatabase-saved-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-saved-queries-api-openapi.yml
- filename: aifordatabase-usage-api-openapi.yml
  format: yaml
  label: AI for Database Usage API
  slug: aifordatabase-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-usage-api-openapi.yml
- filename: aifordatabase-webhooks-api-openapi.yml
  format: yaml
  label: AI for Database Webhooks API
  slug: aifordatabase-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-webhooks-api-openapi.yml
- filename: aifordatabase-workflow-credentials-api-openapi.yml
  format: yaml
  label: AI for Database Workflow Credentials API
  slug: aifordatabase-workflow-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-workflow-credentials-api-openapi.yml
- filename: aifordatabase-workflows-api-openapi.yml
  format: yaml
  label: AI for Database Workflows API
  slug: aifordatabase-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifordatabase/openapi/aifordatabase-workflows-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your name, email address, and authentication credentials
  - category: contact
    text: we collect your name, email address, and authentication credentials
  - category: financial
    text: Send you account-related communications (e.g., security alerts, billing updates).
  - category: device
    text: We automatically collect device type, browser type, IP address, and general location data when you access the Service.
  - category: location
    text: general location data when you access the Service
  - category: behavioral
    text: We also collect usage data such as features used, session duration, and interaction patterns to improve the Service.
  - category: other
    text: we store connection credentials (host, port, database name, username, and encrypted password) for the databases you connect
  deletion:
    route: Delete your account
    text: If you delete your account, we will delete your personal data and database credentials within 30 days, except where retention is required by law.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: Provide, operate, and maintain the Service.
  - purpose: AI query processing
    text: Process your natural language queries through AI model providers to generate SQL and insights.
  - purpose: Account communications
    text: Send you account-related communications (e.g., security alerts, billing updates).
  - purpose: Service improvement
    text: Improve the Service, fix bugs, and develop new features.
  - purpose: Legal compliance
    text: Comply with legal obligations.
  retention:
  - period: 30 days
    scope: Account deletion data
    text: If you delete your account, we will delete your personal data and database credentials within 30 days, except where retention is required by law.
  - period: null
    scope: Active account data
    text: We retain your data for as long as your account is active or as needed to provide the Service.
  rights:
  - right: Access
    text: Access the personal data we hold about you.
  - right: Correction
    text: Request correction of inaccurate data.
  - right: Deletion
    text: Request deletion of your data.
  - right: Objection or restriction
    text: Object to or restrict certain processing of your data.
  - right: Portability
    text: Export your data in a portable format.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AI for Database
provenance_date: '2026-11-09'
provider_name: AI for Database
provider_slug: aifordatabase
slug: aifordatabase-privacy-policy
source_date: '2026-11-09'
source_filename: aifordatabase-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.aifordatabase.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AI for Database\naid: aifordatabase\nurl: https://www.aifordatabase.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we collect your name, email address, and authentication credentials\n- category: contact\n  text: we collect your name, email address, and authentication credentials\n- category: financial\n  text: Send you account-related communications (e.g., security alerts, billing updates).\n- category: device\n  text: We automatically collect device type, browser type, IP address, and general location data when you access\n\
  \    the Service.\n- category: location\n  text: general location data when you access the Service\n- category: behavioral\n  text: We also collect usage data such as features used, session duration, and interaction patterns to improve\n    the Service.\n- category: other\n  text: we store connection credentials (host, port, database name, username, and encrypted password) for the databases\n    you connect\npurposes:\n- purpose: Provide and operate the Service\n  text: Provide, operate, and maintain the Service.\n- purpose: AI query processing\n  text: Process your natural language queries through AI model providers to generate SQL and insights.\n- purpose: Account communications\n  text: Send you account-related communications (e.g., security alerts, billing updates).\n- purpose: Service improvement\n  text: Improve the Service, fix bugs, and develop new features.\n- purpose: Legal compliance\n  text: Comply with legal obligations.\nretention:\n- scope: Account deletion data\n  period:\
  \ 30 days\n  text: If you delete your account, we will delete your personal data and database credentials within 30 days, except\n    where retention is required by law.\n- scope: Active account data\n  period: null\n  text: We retain your data for as long as your account is active or as needed to provide the Service.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account\n  text: If you delete your account, we will delete your personal data and database credentials within 30 days, except\n    where retention is required by law.\nrights:\n- right: Access\n  text: Access the personal data we hold about you.\n- right: Correction\n  text: Request correction of inaccurate data.\n- right: Deletion\n  text: Request deletion of your data.\n- right: Objection or restriction\n  text: Object to or restrict certain processing of your data.\n- right: Portability\n  text: Export your data\
  \ in a portable format.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/aifordatabase/privacy/aifordatabase-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from AI for Database's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Database
- Analytics
- Developer Tools
- Natural Language Query
- Text-to-SQL
- Dashboards
- Business Intelligence
- Workflow Automation
- Alerts
- Agent-Native
- Llms.txt
- OpenAPI
- Webhook
- MCP
- PostgreSQL
- MySQL
- MongoDB
---
