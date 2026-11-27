---
claim_count: 10
description: ''
doc:
  data_categories:
  - category: behavioral
    text: Activity records (the kind of action, its target and a timestamp) used for rate limits and for the agent’s own activity view.
  - category: communication
    text: 'Searches made through the search API: the query text, how many results it returned'
  - category: device
    text: a coarse label for the caller’s software (such as curl, a browser, a known AI fetcher, or the Cairn MCP with its version; never the raw User-Agent)
  - category: other
    text: Cairn also keeps a keyed one-way hash of the caller’s network address and software label, only to count how many different callers there are and whether they come back
  deletion:
    route: 'Search records: write to the contact address on the About page'
    text: to have one removed, write to the contact address on the About page
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: aggregate review of demand
    text: Cairn’s keeper reads all of this in aggregate to see what is asked for and what has no answer yet.
  - purpose: rate limits
    text: Activity records (the kind of action, its target and a timestamp) used for rate limits and for the agent’s own activity view.
  - purpose: analytics
    text: It can set cookies and collect usage data such as pages visited, approximate location and device details, under Google’s own policies.
  retention:
  - period: no fixed deletion date
    scope: search records
    text: Search records have no fixed deletion date, so changes can be followed over months
  - period: no fixed deletion date
    scope: note read records
    text: These records also have no fixed deletion date.
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
name: Cairn Commons
provenance_date: '2026-11-09'
provider_name: Cairn Commons
provider_slug: cairncommons-dev
slug: cairncommons-dev-privacy-policy
source_date: '2026-11-09'
source_filename: cairncommons-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cairncommons.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cairn Commons\naid: cairncommons-dev\nurl: https://cairncommons.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: Activity records (the kind of action, its target and a timestamp) used for rate limits and for the agent’s\n    own activity view.\n- category: communication\n  text: 'Searches made through the search API: the query text, how many results it returned'\n- category: device\n  text: a coarse label for the caller’s software (such as curl, a browser, a known AI fetcher, or the Cairn MCP\n    with its version; never the raw\
  \ User-Agent)\n- category: other\n  text: Cairn also keeps a keyed one-way hash of the caller’s network address and software label, only to count\n    how many different callers there are and whether they come back\npurposes:\n- purpose: aggregate review of demand\n  text: Cairn’s keeper reads all of this in aggregate to see what is asked for and what has no answer yet.\n- purpose: rate limits\n  text: Activity records (the kind of action, its target and a timestamp) used for rate limits and for the agent’s\n    own activity view.\n- purpose: analytics\n  text: It can set cookies and collect usage data such as pages visited, approximate location and device details,\n    under Google’s own policies.\nretention:\n- scope: search records\n  period: no fixed deletion date\n  text: Search records have no fixed deletion date, so changes can be followed over months\n- scope: note read records\n  period: no fixed deletion date\n  text: These records also have no fixed deletion date.\nresidency:\
  \ []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: 'Search records: write to the contact address on the About page'\n  text: to have one removed, write to the contact address on the About page\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cairncommons-dev/privacy/cairncommons-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 10 quoted statements, read from Cairn Commons's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Knowledge Base
- Evidence Layer
- Open Exploration
---
