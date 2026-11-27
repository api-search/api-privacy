---
api_specs:
- filename: cqnce-app-agents-admin-api-openapi.yml
  format: yaml
  label: cQnce Agents – Admin API
  slug: cqnce-app-agents-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqnce-app/openapi/cqnce-app-agents-admin-api-openapi.yml
- filename: cqnce-app-agents-self-api-openapi.yml
  format: yaml
  label: cQnce Agents – Self API
  slug: cqnce-app-agents-self-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqnce-app/openapi/cqnce-app-agents-self-api-openapi.yml
- filename: cqnce-app-alarms-api-openapi.yml
  format: yaml
  label: cQnce Alarms API
  slug: cqnce-app-alarms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqnce-app/openapi/cqnce-app-alarms-api-openapi.yml
- filename: cqnce-app-auth-agent-api-openapi.yml
  format: yaml
  label: cQnce Auth – Agent API
  slug: cqnce-app-auth-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqnce-app/openapi/cqnce-app-auth-agent-api-openapi.yml
- filename: cqnce-app-auth-tenant-api-openapi.yml
  format: yaml
  label: cQnce Auth – Tenant API
  slug: cqnce-app-auth-tenant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqnce-app/openapi/cqnce-app-auth-tenant-api-openapi.yml
- filename: cqnce-app-callbacks-api-openapi.yml
  format: yaml
  label: cQnce Callbacks API
  slug: cqnce-app-callbacks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqnce-app/openapi/cqnce-app-callbacks-api-openapi.yml
- filename: cqnce-app-health-api-openapi.yml
  format: yaml
  label: cQnce Health API
  slug: cqnce-app-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqnce-app/openapi/cqnce-app-health-api-openapi.yml
- filename: cqnce-app-logs-api-openapi.yml
  format: yaml
  label: cQnce Logs API
  slug: cqnce-app-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqnce-app/openapi/cqnce-app-logs-api-openapi.yml
- filename: cqnce-app-projects-api-openapi.yml
  format: yaml
  label: cQnce Projects API
  slug: cqnce-app-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqnce-app/openapi/cqnce-app-projects-api-openapi.yml
- filename: cqnce-app-public-api-openapi.yml
  format: yaml
  label: cQnce Public API
  slug: cqnce-app-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqnce-app/openapi/cqnce-app-public-api-openapi.yml
- filename: cqnce-app-requests-api-openapi.yml
  format: yaml
  label: cQnce Requests API
  slug: cqnce-app-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqnce-app/openapi/cqnce-app-requests-api-openapi.yml
- filename: cqnce-app-routing-rules-api-openapi.yml
  format: yaml
  label: cQnce Routing Rules API
  slug: cqnce-app-routing-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqnce-app/openapi/cqnce-app-routing-rules-api-openapi.yml
- filename: cqnce-app-subscriptions-api-openapi.yml
  format: yaml
  label: cQnce Subscriptions API
  slug: cqnce-app-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqnce-app/openapi/cqnce-app-subscriptions-api-openapi.yml
- filename: cqnce-app-teams-api-openapi.yml
  format: yaml
  label: cQnce Teams API
  slug: cqnce-app-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqnce-app/openapi/cqnce-app-teams-api-openapi.yml
- filename: cqnce-app-users-api-openapi.yml
  format: yaml
  label: cQnce Users API
  slug: cqnce-app-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cqnce-app/openapi/cqnce-app-users-api-openapi.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: First name, last name, avatar image (optional)
  - category: contact
    text: Email address and password (tenant dashboard users)
  - category: contact
    text: Phone number (agents — used for OTP authentication and push notifications)
  - category: device
    text: Device public key (ECDSA P-256, registered on first mobile login)
  - category: device
    text: IP address, HTTP method, path, response status, and duration (API access log)
  - category: behavioral
    text: Analytics identifiers and usage events from website, web app, and mobile app (when analytics is enabled by user consent where required)
  - category: communication
    text: Email addresses used for transactional emails (account activation, password reset)
  - category: other
    text: Authorization request payloads and metadata (JSON, provided by your application)
  deletion:
    route: Contact privacy@cqnce.app
    text: To exercise any of these rights, contact us at privacy@cqnce.app .
  dpa:
    available: null
    text: Other infrastructure providers — database, object storage, and email delivery services that process data on our behalf under data processing agreements.
    url: null
  purposes:
  - purpose: Providing the Service
    text: Providing the Service (routing, notifications, webhooks)
  - purpose: Authenticating users and agents
    text: Authenticating users and agents (JWT, OTP, device keys)
  - purpose: Audit trail and compliance logging
    text: Audit trail and compliance logging
  - purpose: Improving the Service and debugging
    text: Improving the Service and debugging
  - purpose: Usage analytics
    text: Usage analytics for product improvement and reliability (website, web app, mobile app)
  retention:
  - period: until you close your account
    scope: Account data
    text: Account data is kept until you close your account.
  - period: up to 12 months after termination
    scope: Authorization request records and audit logs
    text: Authorization request records and audit logs are retained for the duration of the contract and up to 12 months after termination unless a shorter period is agreed.
  - period: 90 days
    scope: API access logs
    text: API access logs are retained for 90 days by default.
  - period: up to 14 months
    scope: Analytics event data (Google Analytics)
    text: Analytics event data is retained according to configured provider settings (for Google Analytics, up to 14 months unless changed).
  rights:
  - right: Access
    text: Access — request a copy of the data we hold about you.
  - right: Rectification
    text: Rectification — ask us to correct inaccurate data.
  - right: Erasure
    text: Erasure — ask us to delete your data (subject to legal retention obligations).
  - right: Restriction
    text: Restriction — ask us to restrict processing in certain circumstances.
  - right: Portability
    text: Portability — receive your data in a structured, machine-readable format.
  - right: Objection
    text: Objection — object to processing based on legitimate interest.
  - right: Withdraw consent
    text: Withdraw consent — withdraw consent at any time where processing is consent-based.
  role:
    text: The data controller responsible for your personal data is TECH S.r.l.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: Railway — hosting and deployment infrastructure for backend and web services, acting as a processor under appropriate contractual safeguards.
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards such as standard contractual clauses and vendor agreements, where applicable.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: cQnce
provenance_date: '2026-11-09'
provider_name: cQnce
provider_slug: cqnce-app
slug: cqnce-app-privacy-policy
source_date: '2026-11-09'
source_filename: cqnce-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cqnce.app/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: cQnce\naid: cqnce-app\nurl: https://cqnce.app/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller responsible for your personal data is TECH S.r.l.\ndata_categories:\n- category: identifying\n  text: First name, last name, avatar image (optional)\n- category: contact\n  text: Email address and password (tenant dashboard users)\n- category: contact\n  text: Phone number (agents — used for OTP authentication and push notifications)\n- category: device\n  text: Device public key (ECDSA P-256, registered on first mobile login)\n- category: device\n  text: IP address,\
  \ HTTP method, path, response status, and duration (API access log)\n- category: behavioral\n  text: Analytics identifiers and usage events from website, web app, and mobile app (when analytics is enabled\n    by user consent where required)\n- category: communication\n  text: Email addresses used for transactional emails (account activation, password reset)\n- category: other\n  text: Authorization request payloads and metadata (JSON, provided by your application)\npurposes:\n- purpose: Providing the Service\n  text: Providing the Service (routing, notifications, webhooks)\n- purpose: Authenticating users and agents\n  text: Authenticating users and agents (JWT, OTP, device keys)\n- purpose: Audit trail and compliance logging\n  text: Audit trail and compliance logging\n- purpose: Improving the Service and debugging\n  text: Improving the Service and debugging\n- purpose: Usage analytics\n  text: Usage analytics for product improvement and reliability (website, web app, mobile app)\n\
  retention:\n- scope: Account data\n  period: until you close your account\n  text: Account data is kept until you close your account.\n- scope: Authorization request records and audit logs\n  period: up to 12 months after termination\n  text: Authorization request records and audit logs are retained for the duration of the contract and up to 12\n    months after termination unless a shorter period is agreed.\n- scope: API access logs\n  period: 90 days\n  text: API access logs are retained for 90 days by default.\n- scope: Analytics event data (Google Analytics)\n  period: up to 14 months\n  text: Analytics event data is retained according to configured provider settings (for Google Analytics, up to\n    14 months unless changed).\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate safeguards such as standard contractual clauses and vendor agreements, where applicable.\nsubprocessors:\n  url: null\n  text: Railway — hosting and deployment infrastructure for backend\
  \ and web services, acting as a processor under\n    appropriate contractual safeguards.\ndpa:\n  available: null\n  url: null\n  text: Other infrastructure providers — database, object storage, and email delivery services that process data\n    on our behalf under data processing agreements.\ndeletion:\n  route: Contact privacy@cqnce.app\n  text: To exercise any of these rights, contact us at privacy@cqnce.app .\nrights:\n- right: Access\n  text: Access — request a copy of the data we hold about you.\n- right: Rectification\n  text: Rectification — ask us to correct inaccurate data.\n- right: Erasure\n  text: Erasure — ask us to delete your data (subject to legal retention obligations).\n- right: Restriction\n  text: Restriction — ask us to restrict processing in certain circumstances.\n- right: Portability\n  text: Portability — receive your data in a structured, machine-readable format.\n- right: Objection\n  text: Objection — object to processing based on legitimate interest.\n- right:\
  \ Withdraw consent\n  text: Withdraw consent — withdraw consent at any time where processing is consent-based.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/cqnce-app/privacy/cqnce-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 30 quoted statements, read from cQnce's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Human-in-the-Loop
- Approvals
- Authorization
- AI Agents
- MCP
- Webhook
- Workflows
- Audit
---
