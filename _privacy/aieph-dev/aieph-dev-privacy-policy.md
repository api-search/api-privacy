---
claim_count: 8
description: ''
doc:
  data_categories:
  - category: behavioral
    text: Rule ID, package, from_major, result — dependency-major judgment and rule-match observation
  - category: identifying
    text: A random UUID either your browser generates at /setup , or the CLI generates at ~/.aieph/install.json when you run aieph init
  - category: device
    text: The raw User-Agent is never stored
  - category: other
    text: No code snippets, paths, or full queries
  deletion:
    route: remove install ID from MCP config or set telemetry to false
    text: 'Delete the line from your MCP config, or set "telemetry": false'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: aggregation of dependency-major and rule-match observations
    text: Date (day granularity) and schema — for aggregation.
  - purpose: counting users and active installs
    text: used only to count users and active installs
  retention:
  - period: per month
    scope: IP address hash
    text: we record only a one-way hash of the IP salted per month
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
name: AIeph
provenance_date: '2026-11-09'
provider_name: AIeph
provider_slug: aieph-dev
slug: aieph-dev-privacy-policy
source_date: '2026-11-09'
source_filename: aieph-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aieph.dev/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AIeph\naid: aieph-dev\nurl: https://aieph.dev/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: Rule ID, package, from_major, result — dependency-major judgment and rule-match observation\n- category: identifying\n  text: A random UUID either your browser generates at /setup , or the CLI generates at ~/.aieph/install.json when\n    you run aieph init\n- category: device\n  text: The raw User-Agent is never stored\n- category: other\n  text: No code snippets, paths, or full queries\npurposes:\n- purpose: aggregation of dependency-major\
  \ and rule-match observations\n  text: Date (day granularity) and schema — for aggregation.\n- purpose: counting users and active installs\n  text: used only to count users and active installs\nretention:\n- scope: IP address hash\n  period: per month\n  text: we record only a one-way hash of the IP salted per month\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: remove install ID from MCP config or set telemetry to false\n  text: 'Delete the line from your MCP config, or set \"telemetry\": false'\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aieph-dev/privacy/aieph-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 8 quoted statements, read from AIeph's own page on 2026-11-09.
synthetic: false
tags:
- knowledge cache
- AI Coding Agents
- Privacy
- shared cache
---
