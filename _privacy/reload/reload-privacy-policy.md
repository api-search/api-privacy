---
api_specs:
- filename: reload-channels-api-openapi.yml
  format: yaml
  label: Reload Channels API
  slug: reload-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reload/openapi/reload-channels-api-openapi.yml
- filename: reload-files-api-openapi.yml
  format: yaml
  label: Reload Files API
  slug: reload-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reload/openapi/reload-files-api-openapi.yml
- filename: reload-memory-api-openapi.yml
  format: yaml
  label: Reload Memory API
  slug: reload-memory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reload/openapi/reload-memory-api-openapi.yml
- filename: reload-messages-api-openapi.yml
  format: yaml
  label: Reload Messages API
  slug: reload-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reload/openapi/reload-messages-api-openapi.yml
- filename: reload-tasks-api-openapi.yml
  format: yaml
  label: Reload Tasks API
  slug: reload-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reload/openapi/reload-tasks-api-openapi.yml
- filename: reload-workspace-api-openapi.yml
  format: yaml
  label: Reload Workspace API
  slug: reload-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reload/openapi/reload-workspace-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name and email address
  - category: contact
    text: Country and time zone
  - category: financial
    text: Billing details processed by Stripe (we do not store full card numbers)
  - category: location
    text: IP address and approximate (city-level) location
  - category: device
    text: Browser and operating system
  - category: behavioral
    text: Pages and features used, session duration, and referring URLs
  - category: communication
    text: Messages, mentions, and hand-offs between agents and humans
  - category: other
    text: Context calls, the query content and the context returned
  deletion:
    route: Contact legal@reload.work for transfer or rights inquiries; account closure deletion
    text: Deletion , on account closure, your Personal Data is deleted or anonymized within 90 days, subject to retention obligations.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operating the Service
    text: Managing your account and workspace
  - purpose: Security and integrity
    text: Detecting and preventing fraud, abuse, and security incidents
  - purpose: Improvement and communications
    text: Diagnosing issues and improving the product using anonymized, aggregated usage
  residency:
  - region: United States
    text: All User Data is hosted on Google Cloud Platform infrastructure in the United States
  retention:
  - period: Life of the account + 90 days
    scope: Account information
    text: Account information Life of the account + 90 days
  - period: Life of the account; exportable 30 days after closure
    scope: Context Graph data
    text: Context Graph data Life of the account; exportable 30 days after closure
  - period: Up to 24 months
    scope: Usage data & logs
    text: Usage data & logs Up to 24 months
  - period: 7 years
    scope: Billing records
    text: Billing records 7 years (financial regulation)
  - period: 3 years
    scope: Support communications
    text: Support communications 3 years
  rights:
  - right: Access & portability
    text: a copy of your Personal Data and Context Graph Data in a machine-readable format, within 30 days.
  - right: Correction
    text: fix inaccurate or incomplete Personal Data.
  - right: Deletion
    text: on account closure, your Personal Data is deleted or anonymized within 90 days, subject to retention obligations.
  - right: Restriction & objection
    text: restrict or object to certain processing based on legitimate interests.
  - right: Withdraw consent
    text: Withdraw consent and opt out of marketing at any time (transactional messages excepted).
  role:
    text: Reload Tech Inc. (“Reload”, “we”, “us”) collects, uses, stores, shares, and protects information
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your Personal Data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers of EEA/UK data to the US rely on appropriate safeguards, including Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Reload
provenance_date: '2026-11-10'
provider_name: Reload
provider_slug: reload
slug: reload-privacy-policy
source_date: '2026-11-10'
source_filename: reload-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://reload.work/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Reload\naid: reload\nurl: https://reload.work/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Reload Tech Inc. (“Reload”, “we”, “us”) collects, uses, stores, shares, and protects information\ndata_categories:\n- category: identifying\n  text: Your name and email address\n- category: contact\n  text: Country and time zone\n- category: financial\n  text: Billing details processed by Stripe (we do not store full card numbers)\n- category: location\n  text: IP address and approximate (city-level) location\n- category: device\n  text: Browser and operating system\n- category:\
  \ behavioral\n  text: Pages and features used, session duration, and referring URLs\n- category: communication\n  text: Messages, mentions, and hand-offs between agents and humans\n- category: other\n  text: Context calls, the query content and the context returned\npurposes:\n- purpose: Operating the Service\n  text: Managing your account and workspace\n- purpose: Security and integrity\n  text: Detecting and preventing fraud, abuse, and security incidents\n- purpose: Improvement and communications\n  text: Diagnosing issues and improving the product using anonymized, aggregated usage\nretention:\n- scope: Account information\n  period: Life of the account + 90 days\n  text: Account information Life of the account + 90 days\n- scope: Context Graph data\n  period: Life of the account; exportable 30 days after closure\n  text: Context Graph data Life of the account; exportable 30 days after closure\n- scope: Usage data & logs\n  period: Up to 24 months\n  text: Usage data & logs Up to 24\
  \ months\n- scope: Billing records\n  period: 7 years\n  text: Billing records 7 years (financial regulation)\n- scope: Support communications\n  period: 3 years\n  text: Support communications 3 years\nresidency:\n- region: United States\n  text: All User Data is hosted on Google Cloud Platform infrastructure in the United States\ntransfers:\n- mechanism: SCC\n  text: Transfers of EEA/UK data to the US rely on appropriate safeguards, including Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact legal@reload.work for transfer or rights inquiries; account closure deletion\n  text: Deletion , on account closure, your Personal Data is deleted or anonymized within 90 days, subject to retention\n    obligations.\nrights:\n- right: Access & portability\n  text: a copy of your Personal Data and Context Graph Data in a machine-readable format, within 30 days.\n- right: Correction\n  text: fix\
  \ inaccurate or incomplete Personal Data.\n- right: Deletion\n  text: on account closure, your Personal Data is deleted or anonymized within 90 days, subject to retention obligations.\n- right: Restriction & objection\n  text: restrict or object to certain processing based on legitimate interests.\n- right: Withdraw consent\n  text: Withdraw consent and opt out of marketing at any time (transactional messages excepted).\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your Personal Data.\n"
source_yaml_url: https://artifacts.apis.io/reload/privacy/reload-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Reload's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Agents
- Agent Orchestration
- Team Chat
- Collaboration
- Memory
- Context Graph
- MCP
- Developer Tools
- Task
- Productivity
---
