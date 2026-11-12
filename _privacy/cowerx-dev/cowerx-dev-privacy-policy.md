---
api_specs:
- filename: cowerx-dev-api-tool-calls-openapi.yml
  format: yaml
  label: API Tool Calls
  slug: api-tool-calls
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cowerx-dev/openapi/cowerx-dev-api-tool-calls-openapi.yml
claim_count: 4
description: ''
doc:
  data_categories:
  - category: behavioral
    text: records the UTC day, the site section, a random tab-session identifier, an event kind (page view, funnel step, or conversion), and an optional step label
  - category: identifying
    text: The network request reaches Cloudflare with an IP address as ordinary web traffic does.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: understand page and link usefulness
    text: We use these counts to understand which pages and links are useful.
  retention:
  - period: when the tab closes
    scope: tab-session identifier
    text: The identifier normally ends when the tab closes.
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
name: Cowerx
provenance_date: '2026-11-09'
provider_name: Cowerx
provider_slug: cowerx-dev
slug: cowerx-dev-privacy-policy
source_date: '2026-11-09'
source_filename: cowerx-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cowerx.dev/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cowerx\naid: cowerx-dev\nurl: https://cowerx.dev/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: records the UTC day, the site section, a random tab-session identifier, an event kind (page view, funnel\n    step, or conversion), and an optional step label\n- category: identifying\n  text: The network request reaches Cloudflare with an IP address as ordinary web traffic does.\npurposes:\n- purpose: understand page and link usefulness\n  text: We use these counts to understand which pages and links are useful.\nretention:\n- scope:\
  \ tab-session identifier\n  period: when the tab closes\n  text: The identifier normally ends when the tab closes.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cowerx-dev/privacy/cowerx-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
summary_line: 4 quoted statements, read from Cowerx's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Research
- Web Tools
- Website Auditing
- Open Source
- MCP
- Developer Tools
---
