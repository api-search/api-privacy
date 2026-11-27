---
api_specs:
- filename: everymcp-ai-openapi-generated.yml
  format: yaml
  label: Every MCP API
  slug: everymcp-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everymcp-ai/openapi/_ae-authored/everymcp-ai-openapi-generated.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: behavioral
    text: Every MCP records a small amount of data about searches, so it can report what people look for and what they fail to find.
  - category: device
    text: It also sends your country, browser and device type.
  - category: identifying
    text: Rows carry a value called client_bucket. It is the day's secret keyed over your network prefix, which is the /24 of an IPv4 address or the /48 of an IPv6 one, together with the name your MCP client reported for itself.
  deletion:
    route: null
    text: There is nothing here to send you a copy of or to delete on request.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: reporting search demand and unmet searches
    text: so it can report what people look for and what they fail to find
  retention:
  - period: ninety days
    scope: row-level search and resolution events
    text: Row-level events are deleted ninety days after they happen.
  - period: null
    scope: daily rollup tables
    text: The three daily rollup tables are kept for as long as the project runs.
  - period: null
    scope: daily analytics salt
    text: A new one is generated each day and every earlier one is deleted, with no archive and no backup of them anywhere in the design.
  rights:
  - right: raise concerns
    text: To raise anything about this page, write to abuse@everymcp.ai .
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
name: Every MCP
provenance_date: '2026-11-09'
provider_name: Every MCP
provider_slug: everymcp-ai
slug: everymcp-ai-privacy-policy
source_date: '2026-11-09'
source_filename: everymcp-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://everymcp.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Every MCP\naid: everymcp-ai\nurl: https://everymcp.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: Every MCP records a small amount of data about searches, so it can report what people look for and what\n    they fail to find.\n- category: device\n  text: It also sends your country, browser and device type.\n- category: identifying\n  text: Rows carry a value called client_bucket. It is the day's secret keyed over your network prefix, which is\n    the /24 of an IPv4 address or the /48 of an IPv6 one, together with the name your\
  \ MCP client reported for itself.\npurposes:\n- purpose: reporting search demand and unmet searches\n  text: so it can report what people look for and what they fail to find\nretention:\n- scope: row-level search and resolution events\n  period: ninety days\n  text: Row-level events are deleted ninety days after they happen.\n- scope: daily rollup tables\n  period: null\n  text: The three daily rollup tables are kept for as long as the project runs.\n- scope: daily analytics salt\n  period: null\n  text: A new one is generated each day and every earlier one is deleted, with no archive and no backup of them\n    anywhere in the design.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: There is nothing here to send you a copy of or to delete on request.\nrights:\n- right: raise concerns\n  text: To raise anything about this page, write to abuse@everymcp.ai .\nsale_or_sharing:\n \
  \ stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/everymcp-ai/privacy/everymcp-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 9 quoted statements, read from Every MCP's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- MCP
- Automation
- Productivity
- Integration
---
