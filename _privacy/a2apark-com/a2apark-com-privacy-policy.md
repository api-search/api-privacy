---
claim_count: 7
description: ''
doc:
  data_categories:
  - category: device
    text: PostHog receives the page path, referring site, broad screen class, campaign source, and named interactions such as an outbound link click.
  - category: other
    text: Runs may be stored by the park operator and include selected actions, simulated scenario state, outcomes, and score.
  deletion:
    route: private publication link
    text: Keep the private publication link to remove a posted result from the site; copies others have already made may remain.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: site measurement
    text: PostHog receives the page path, referring site, broad screen class, campaign source, and named interactions such as an outbound link click.
  - purpose: private aggregate run reports
    text: This record contains no IP address, browser fingerprint, full referrer URL, or visitor account, and is used for private aggregate run reports.
  retention:
  - period: 500 recent saved runs
    scope: public prototype run cache
    text: The public prototype keeps at most 500 recent saved runs in each run cache; older runs may be deleted automatically.
  - period: capped at 500
    scope: MCP run snapshots
    text: MCP run snapshots use a separate persistent cache capped at 500.
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
name: A2APark
provenance_date: '2026-11-09'
provider_name: A2APark
provider_slug: a2apark-com
slug: a2apark-com-privacy-policy
source_date: '2026-11-09'
source_filename: a2apark-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://a2apark.com/legal.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: A2APark\naid: a2apark-com\nurl: https://a2apark.com/legal.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: PostHog receives the page path, referring site, broad screen class, campaign source, and named interactions\n    such as an outbound link click.\n- category: other\n  text: Runs may be stored by the park operator and include selected actions, simulated scenario state, outcomes,\n    and score.\npurposes:\n- purpose: site measurement\n  text: PostHog receives the page path, referring site, broad screen class, campaign source, and named\
  \ interactions\n    such as an outbound link click.\n- purpose: private aggregate run reports\n  text: This record contains no IP address, browser fingerprint, full referrer URL, or visitor account, and is used\n    for private aggregate run reports.\nretention:\n- scope: public prototype run cache\n  period: 500 recent saved runs\n  text: The public prototype keeps at most 500 recent saved runs in each run cache; older runs may be deleted automatically.\n- scope: MCP run snapshots\n  period: capped at 500\n  text: MCP run snapshots use a separate persistent cache capped at 500.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: private publication link\n  text: Keep the private publication link to remove a posted result from the site; copies others have already made\n    may remain.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/a2apark-com/privacy/a2apark-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 7 quoted statements, read from A2APark's own page on 2026-11-09.
synthetic: false
tags:
- Agent Evaluation
- AI Agents
- A2A
- Agent Safety
- Benchmarking
- Browser Agents
- Testing
- CI/CD
- Simulation
---
