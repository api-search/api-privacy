---
api_specs:
- filename: trackmcp-openapi-generated.yml
  format: yaml
  label: TrackMCP API
  slug: trackmcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trackmcp/openapi/_ae-authored/trackmcp-openapi-generated.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your first name, last name, work email, company, and workspace details when you sign up.'
  - category: behavioral
    text: 'Usage telemetry from your MCP server: the tool called, timing, status, client type, and error details.'
  - category: behavioral
    text: 'Product analytics: how you use the TrackMCP dashboard, so we can improve it.'
  deletion:
    route: email privacy@trackmcp.com
    text: For privacy questions or a deletion request, email privacy@trackmcp.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide analytics
    text: 'To provide the analytics you asked for: turning your server''s calls into dashboards, sessions, and weekly summaries.'
  - purpose: operate, secure, improve service
    text: To operate, secure, and improve the service, and to communicate with you about your account.
  residency:
  - region: selected region
    text: Telemetry is stored in your selected region on managed infrastructure.
  retention:
  - period: null
    scope: telemetry
    text: Telemetry is stored in the managed TrackMCP service for the applicable service terms.
  rights:
  - right: account export
    text: Signed-in workspace members can request a bounded account export from the account export endpoint.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data, and we do not use your telemetry to train models for other customers.
  subprocessors:
    text: We use a small set of infrastructure providers to run the service.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TrackMCP
provenance_date: '2026-11-10'
provider_name: TrackMCP
provider_slug: trackmcp
slug: trackmcp-privacy-policy
source_date: '2026-11-10'
source_filename: trackmcp-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://trackmcp.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TrackMCP\naid: trackmcp\nurl: https://trackmcp.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account data: your first name, last name, work email, company, and workspace details when you sign up.'\n- category: behavioral\n  text: 'Usage telemetry from your MCP server: the tool called, timing, status, client type, and error details.'\n- category: behavioral\n  text: 'Product analytics: how you use the TrackMCP dashboard, so we can improve it.'\npurposes:\n- purpose: provide analytics\n  text: 'To provide the analytics you\
  \ asked for: turning your server''s calls into dashboards, sessions, and weekly\n    summaries.'\n- purpose: operate, secure, improve service\n  text: To operate, secure, and improve the service, and to communicate with you about your account.\nretention:\n- scope: telemetry\n  period: null\n  text: Telemetry is stored in the managed TrackMCP service for the applicable service terms.\nresidency:\n- region: selected region\n  text: Telemetry is stored in your selected region on managed infrastructure.\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use a small set of infrastructure providers to run the service.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@trackmcp.com\n  text: For privacy questions or a deletion request, email privacy@trackmcp.com.\nrights:\n- right: account export\n  text: Signed-in workspace members can request a bounded account export from the account export endpoint.\nsale_or_sharing:\n  stance: prohibited\n  text: We\
  \ do not sell your data, and we do not use your telemetry to train models for other customers.\n"
source_yaml_url: https://artifacts.apis.io/trackmcp/privacy/trackmcp-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 11 quoted statements, read from TrackMCP's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Monitoring
- Analytics
- MCP
- Dashboards
---
