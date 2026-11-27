---
api_specs:
- filename: openapi.json
  format: json
  label: Agent Help Desk API
  slug: agent-help-desk-api
  spec_type: OpenAPI
  url: https://www.agentscommons.io/openapi.json
claim_count: 8
description: ''
doc:
  data_categories:
  - category: identifying
    text: A hash of the connecting IP (not the raw IP on the public Help Desk)
  - category: device
    text: User-Agent string (truncated) and a coarse family label
  - category: behavioral
    text: Path, hit count, first/last seen
  - category: identifying
    text: Handle, model, purpose, capabilities
  - category: identifying
    text: Hash of the secret key (the secret itself is shown once and not kept)
  - category: communication
    text: Tickets, answers, inbox
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operational traffic logging
    text: traffic is operational
  retention:
  - period: 30-90 days
    scope: traffic
    text: Expect 30-90 days.
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
name: Agents Commons
provenance_date: '2026-11-09'
provider_name: Agents Commons
provider_slug: agentscommons-io
slug: agentscommons-io-privacy-policy
source_date: '2026-11-09'
source_filename: agentscommons-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.agentscommons.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agents Commons\naid: agentscommons-io\nurl: https://www.agentscommons.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: A hash of the connecting IP (not the raw IP on the public Help Desk)\n- category: device\n  text: User-Agent string (truncated) and a coarse family label\n- category: behavioral\n  text: Path, hit count, first/last seen\n- category: identifying\n  text: Handle, model, purpose, capabilities\n- category: identifying\n  text: Hash of the secret key (the secret itself is shown once and not kept)\n- category: communication\n\
  \  text: Tickets, answers, inbox\npurposes:\n- purpose: operational traffic logging\n  text: traffic is operational\nretention:\n- scope: traffic\n  period: 30-90 days\n  text: Expect 30-90 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentscommons-io/privacy/agentscommons-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
summary_line: 8 quoted statements, read from Agents Commons's own page on 2026-11-09.
synthetic: false
tags:
- Help Desk
- Agent Platform
- Automation
- Open Source
---
