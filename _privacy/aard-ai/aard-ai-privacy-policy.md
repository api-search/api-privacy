---
api_specs:
- filename: aard-ai-status-api-openapi.yml
  format: yaml
  label: Aard Status API
  slug: aard-ai-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aard-ai/openapi/aard-ai-status-api-openapi.yml
- filename: aard-ai-tools-api-openapi.yml
  format: yaml
  label: Aard Tools API
  slug: aard-ai-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aard-ai/openapi/aard-ai-tools-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information — name, work email, organisation — provided when you sign up.
  - category: behavioral
    text: Usage metadata — timestamps, tool names, request counts and the content of each request
  - category: device
    text: the User-Agent string sent by your client software
  - category: location
    text: the country and network your request reaches us from
  - category: identifying
    text: your IP address
  - category: financial
    text: Billing information for paid plans is processed by Paddle.com Market Limited, our merchant of record.
  - category: communication
    text: Support correspondence you send to us, retained for the duration of the issue.
  deletion:
    route: Request deletion; removal within thirty days
    text: You may request deletion at any time and we will remove personal information within thirty days, except where retention is legally required.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide, rate limit, prevent abuse, bill, improve
    text: We use the information above to provide the service, enforce rate limits, prevent abuse, bill paid accounts, and improve Aard's accuracy.
  - purpose: identify client applications, investigate abuse
    text: We use this to identify which client applications are calling the service, to enforce rate limits, and to investigate abuse.
  retention:
  - period: ninety days
    scope: Operational logs including connection information
    text: Operational logs, including the connection information described above, are retained for ninety days and then deleted automatically.
  - period: while your account is active
    scope: Account records
    text: Account records are retained while your account is active.
  - period: up to 180 days
    scope: Payment provider webhook notifications
    text: webhook notifications from our payments provider are retained in full for up to 180 days for audit and reconciliation purposes
  rights:
  - right: access, correct, export, delete
    text: Depending on your jurisdiction you may have the right to access, correct, export or delete your personal information.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: A current list is available on request.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Aard
provenance_date: '2026-11-09'
provider_name: Aard
provider_slug: aard-ai
slug: aard-ai-privacy-policy
source_date: '2026-11-09'
source_filename: aard-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aard.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Aard\naid: aard-ai\nurl: https://aard.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information — name, work email, organisation — provided when you sign up.\n- category: behavioral\n  text: Usage metadata — timestamps, tool names, request counts and the content of each request\n- category: device\n  text: the User-Agent string sent by your client software\n- category: location\n  text: the country and network your request reaches us from\n- category: identifying\n  text: your IP address\n- category: financial\n  text:\
  \ Billing information for paid plans is processed by Paddle.com Market Limited, our merchant of record.\n- category: communication\n  text: Support correspondence you send to us, retained for the duration of the issue.\npurposes:\n- purpose: provide, rate limit, prevent abuse, bill, improve\n  text: We use the information above to provide the service, enforce rate limits, prevent abuse, bill paid accounts,\n    and improve Aard's accuracy.\n- purpose: identify client applications, investigate abuse\n  text: We use this to identify which client applications are calling the service, to enforce rate limits, and to\n    investigate abuse.\nretention:\n- scope: Operational logs including connection information\n  period: ninety days\n  text: Operational logs, including the connection information described above, are retained for ninety days and\n    then deleted automatically.\n- scope: Account records\n  period: while your account is active\n  text: Account records are retained while your\
  \ account is active.\n- scope: Payment provider webhook notifications\n  period: up to 180 days\n  text: webhook notifications from our payments provider are retained in full for up to 180 days for audit and reconciliation\n    purposes\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: A current list is available on request.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion; removal within thirty days\n  text: You may request deletion at any time and we will remove personal information within thirty days, except\n    where retention is legally required.\nrights:\n- right: access, correct, export, delete\n  text: Depending on your jurisdiction you may have the right to access, correct, export or delete your personal\n    information.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/aard-ai/privacy/aard-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Aard's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Data
- Macroeconomics
- MCP
---
