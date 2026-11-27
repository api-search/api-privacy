---
api_specs:
- filename: longwatch-dev-mcp-api-openapi.yml
  format: yaml
  label: longwatch-dev MCP API
  slug: longwatch-dev-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/longwatch-dev/openapi/longwatch-dev-mcp-api-openapi.yml
- filename: longwatch-dev-website-monitoring-api-openapi.yml
  format: yaml
  label: longwatch-dev website monitoring API
  slug: longwatch-dev-website-monitoring-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/longwatch-dev/openapi/longwatch-dev-website-monitoring-api-openapi.yml
claim_count: 8
description: ''
doc:
  data_categories:
  - category: identifying
    text: Operational metrics may include the request time, method, path, status, MCP client name, a salted hash of the caller IP address, and the public payer wallet address for x402 calls.
  - category: contact
    text: For privacy questions or deletion help, email contact@coinop.dev .
  - category: other
    text: A standing watch stores its source configuration, generated access key, polling state, timestamps, and recent alert history.
  - category: other
    text: A webhook watch also stores its destination URL and sends alert payloads to that destination.
  deletion:
    route: Delete a watch through the API, or email contact@coinop.dev for deletion help
    text: Deleting a watch through the API deletes its watch and alert records.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Execute API calls, maintain watches, deliver alerts, prevent abuse, operate the service
    text: It processes the data needed to execute API calls, maintain watches, deliver alerts, prevent abuse, and operate the service.
  - purpose: Perform a watch
    text: To perform a watch, Longwatch requests the configured public source, such as a web page, RSS feed, CoinGecko price endpoint, SEC EDGAR endpoint, or x402 API.
  retention:
  - period: 500 events
    scope: Alert history per watch
    text: Alert history is capped at 500 events per watch.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: longwatch-dev
provenance_date: '2026-11-09'
provider_name: longwatch-dev
provider_slug: longwatch-dev
slug: longwatch-dev-privacy-policy
source_date: '2026-11-09'
source_filename: longwatch-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://longwatch.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: longwatch-dev\naid: longwatch-dev\nurl: https://longwatch.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Operational metrics may include the request time, method, path, status, MCP client name, a salted hash of\n    the caller IP address, and the public payer wallet address for x402 calls.\n- category: contact\n  text: For privacy questions or deletion help, email contact@coinop.dev .\n- category: other\n  text: A standing watch stores its source configuration, generated access key, polling state, timestamps, and recent\n \
  \   alert history.\n- category: other\n  text: A webhook watch also stores its destination URL and sends alert payloads to that destination.\npurposes:\n- purpose: Execute API calls, maintain watches, deliver alerts, prevent abuse, operate the service\n  text: It processes the data needed to execute API calls, maintain watches, deliver alerts, prevent abuse, and\n    operate the service.\n- purpose: Perform a watch\n  text: To perform a watch, Longwatch requests the configured public source, such as a web page, RSS feed, CoinGecko\n    price endpoint, SEC EDGAR endpoint, or x402 API.\nretention:\n- scope: Alert history per watch\n  period: 500 events\n  text: Alert history is capped at 500 events per watch.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete a watch through the API, or email contact@coinop.dev for deletion help\n  text: Deleting a watch through the API deletes its watch\
  \ and alert records.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/longwatch-dev/privacy/longwatch-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 8 quoted statements, read from longwatch-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Monitoring
- Artificial Intelligence
- Web
- Finance
---
