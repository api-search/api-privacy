---
api_specs:
- filename: argus-town-alerts-api-openapi.yml
  format: yaml
  label: argus-town Alerts API
  slug: argus-town-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-alerts-api-openapi.yml
- filename: argus-town-connect-links-api-openapi.yml
  format: yaml
  label: argus-town Connect links API
  slug: argus-town-connect-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-connect-links-api-openapi.yml
- filename: argus-town-connections-api-openapi.yml
  format: yaml
  label: argus-town Connections API
  slug: argus-town-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-connections-api-openapi.yml
- filename: argus-town-events-api-openapi.yml
  format: yaml
  label: argus-town Events API
  slug: argus-town-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-events-api-openapi.yml
- filename: argus-town-negotiated-pricing-api-openapi.yml
  format: yaml
  label: argus-town Negotiated pricing API
  slug: argus-town-negotiated-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-negotiated-pricing-api-openapi.yml
- filename: argus-town-project-api-openapi.yml
  format: yaml
  label: argus-town Project API
  slug: argus-town-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-project-api-openapi.yml
- filename: argus-town-providers-api-openapi.yml
  format: yaml
  label: argus-town Providers API
  slug: argus-town-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-providers-api-openapi.yml
- filename: argus-town-spend-api-openapi.yml
  format: yaml
  label: argus-town Spend API
  slug: argus-town-spend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-spend-api-openapi.yml
- filename: argus-town-start-api-openapi.yml
  format: yaml
  label: argus-town Start API
  slug: argus-town-start-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-start-api-openapi.yml
- filename: argus-town-syncs-api-openapi.yml
  format: yaml
  label: argus-town Syncs API
  slug: argus-town-syncs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/argus-town/openapi/argus-town-syncs-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address, an optional display name, and your password.
  - category: financial
    text: Stripe collects your card and billing details directly; we never see or store your full card number.
  - category: device
    text: Your IP address is used to rate-limit sign-in, sign-up and waitlist requests, and is recorded in our audit log alongside security-relevant actions such as creating keys or deleting connections.
  - category: behavioral
    text: 'Usage telemetry you send. If you use the SDK or post to /ingest , each event can include: provider and hostname, request path (not the query string), HTTP method and status, latency, model, token and other unit counts, cost, credits spent or remaining, rate-limit headers, the provider’s request id, a timestamp, and up to 2 KB of metadata tags you choose.'
  - category: communication
    text: Connector builder conversations. On paid plans you can ask an AI agent to build a connector for a provider we don’t support yet. We keep the conversation, any docs you paste, the requests the agent made to the provider (method, host, path, status) and the resulting connector code.
  deletion:
    route: Delete a project or account in Settings, or delete connections and keys in the dashboard
    text: Deleting a project in Settings cancels its subscription and deletes its data from our live database immediately; deleting your last project closes your account and deletes it too.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the service
    text: 'To run the service: sync provider data, price and chart your usage, forecast runway and send the alerts you configure.'
  - purpose: Secure the service
    text: 'To secure the service: authenticate you, rate-limit abuse and keep an audit trail.'
  - purpose: Billing
    text: To bill you for a paid plan.
  - purpose: Account emails
    text: To email you about your account and the alerts you set up. We don't send marketing email without asking.
  - purpose: Diagnostics and improvement
    text: To diagnose problems and improve the service, using operational telemetry.
  retention:
  - period: 30 days
    scope: Raw usage events, Free plan
    text: Raw usage events, Free plan 30 days
  - period: 90 days
    scope: Raw usage events, Pro plan
    text: Raw usage events, Pro plan 90 days
  - period: 365 days
    scope: Raw usage events, Team plan
    text: Raw usage events, Team plan 365 days
  - period: 400 days
    scope: Audit log, including IP addresses
    text: Audit log, including IP addresses 400 days
  - period: 14 days
    scope: Error events
    text: Error events 14 days
  - period: Until you delete them or close your account
    scope: Account details, credentials and settings
    text: Account details, credentials and settings Until you delete them or close your account
  rights:
  - right: Access, correct, delete or port
    text: you may have rights to access, correct, delete or port your data
  - right: Object or restrict processing
    text: to object to or restrict some processing
  - right: Complain to a data protection authority
    text: to complain to a data protection authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell personal data, share it for advertising, or use your provider data or telemetry to train AI models.
  subprocessors:
    text: 'Subprocessors These companies process data on our behalf to provide the service:'
    url: null
  transfers:
  - mechanism: other
    text: We’re based in the United States, and our subprocessors may process data in the United States and other countries. By using the service you understand your data will be processed outside your home country.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: argus-town
provenance_date: '2026-11-09'
provider_name: argus-town
provider_slug: argus-town
slug: argus-town-privacy-policy
source_date: '2026-11-09'
source_filename: argus-town-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://argus.town/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: argus-town\naid: argus-town\nurl: https://argus.town/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email address, an optional display name, and your password.\n- category: financial\n  text: Stripe collects your card and billing details directly; we never see or store your full card number.\n- category: device\n  text: Your IP address is used to rate-limit sign-in, sign-up and waitlist requests, and is recorded in our audit\n    log alongside security-relevant actions such as creating keys or deleting connections.\n- category:\
  \ behavioral\n  text: 'Usage telemetry you send. If you use the SDK or post to /ingest , each event can include: provider and\n    hostname, request path (not the query string), HTTP method and status, latency, model, token and other unit\n    counts, cost, credits spent or remaining, rate-limit headers, the provider’s request id, a timestamp, and up\n    to 2 KB of metadata tags you choose.'\n- category: communication\n  text: Connector builder conversations. On paid plans you can ask an AI agent to build a connector for a provider\n    we don’t support yet. We keep the conversation, any docs you paste, the requests the agent made to the provider\n    (method, host, path, status) and the resulting connector code.\npurposes:\n- purpose: Run the service\n  text: 'To run the service: sync provider data, price and chart your usage, forecast runway and send the alerts\n    you configure.'\n- purpose: Secure the service\n  text: 'To secure the service: authenticate you, rate-limit abuse and\
  \ keep an audit trail.'\n- purpose: Billing\n  text: To bill you for a paid plan.\n- purpose: Account emails\n  text: To email you about your account and the alerts you set up. We don't send marketing email without asking.\n- purpose: Diagnostics and improvement\n  text: To diagnose problems and improve the service, using operational telemetry.\nretention:\n- scope: Raw usage events, Free plan\n  period: 30 days\n  text: Raw usage events, Free plan 30 days\n- scope: Raw usage events, Pro plan\n  period: 90 days\n  text: Raw usage events, Pro plan 90 days\n- scope: Raw usage events, Team plan\n  period: 365 days\n  text: Raw usage events, Team plan 365 days\n- scope: Audit log, including IP addresses\n  period: 400 days\n  text: Audit log, including IP addresses 400 days\n- scope: Error events\n  period: 14 days\n  text: Error events 14 days\n- scope: Account details, credentials and settings\n  period: Until you delete them or close your account\n  text: Account details, credentials and\
  \ settings Until you delete them or close your account\nresidency: []\ntransfers:\n- mechanism: other\n  text: We’re based in the United States, and our subprocessors may process data in the United States and other\n    countries. By using the service you understand your data will be processed outside your home country.\nsubprocessors:\n  url: null\n  text: 'Subprocessors These companies process data on our behalf to provide the service:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete a project or account in Settings, or delete connections and keys in the dashboard\n  text: Deleting a project in Settings cancels its subscription and deletes its data from our live database immediately;\n    deleting your last project closes your account and deletes it too.\nrights:\n- right: Access, correct, delete or port\n  text: you may have rights to access, correct, delete or port your data\n- right: Object or restrict processing\n  text: to object to or restrict some\
  \ processing\n- right: Complain to a data protection authority\n  text: to complain to a data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell personal data, share it for advertising, or use your provider data or telemetry to train AI\n    models.\n"
source_yaml_url: https://artifacts.apis.io/argus-town/privacy/argus-town-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from argus-town's own page on 2026-11-09.
synthetic: false
tags:
- Company
- API Monitoring
- Cost Management
- Developer Tools
- MCP
---
