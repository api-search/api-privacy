---
claim_count: 8
description: ''
doc:
  data_categories:
  - category: behavioral
    text: Tool-call metadata — tool name, timestamp, a one-way hash of parameters, latency, and outcome.
  - category: identifying
    text: Payer addresses — the on-chain address that paid a call (public blockchain data by nature).
  - category: device
    text: IP addresses — for the free demo endpoint only, kept in memory for rate-limiting windows (about an hour) and not written to disk.
  - category: communication
    text: Feedback submissions — whatever an agent sends to submit_feedback , displayed in aggregate on the public roadmap.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Public stats and roadmap ranking
    text: Used for the public stats page and to rank the roadmap.
  - purpose: Metering API calls
    text: Used as the agent identity for metering.
  retention:
  - period: about an hour
    scope: IP addresses (demo endpoint)
    text: kept in memory for rate-limiting windows (about an hour) and not written to disk
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Raw logs are not sold or shared, except if required by law.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cerberus Index
provenance_date: '2026-11-09'
provider_name: Cerberus Index
provider_slug: cerberusindex-com
slug: cerberusindex-com-privacy-policy
source_date: '2026-11-09'
source_filename: cerberusindex-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cerberusindex.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cerberus Index\naid: cerberusindex-com\nurl: https://cerberusindex.com/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: Tool-call metadata — tool name, timestamp, a one-way hash of parameters, latency, and outcome.\n- category: identifying\n  text: Payer addresses — the on-chain address that paid a call (public blockchain data by nature).\n- category: device\n  text: IP addresses — for the free demo endpoint only, kept in memory for rate-limiting windows (about an hour)\n    and not written to disk.\n- category: communication\n\
  \  text: Feedback submissions — whatever an agent sends to submit_feedback , displayed in aggregate on the public\n    roadmap.\npurposes:\n- purpose: Public stats and roadmap ranking\n  text: Used for the public stats page and to rank the roadmap.\n- purpose: Metering API calls\n  text: Used as the agent identity for metering.\nretention:\n- scope: IP addresses (demo endpoint)\n  period: about an hour\n  text: kept in memory for rate-limiting windows (about an hour) and not written to disk\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: Raw logs are not sold or shared, except if required by law.\n"
source_yaml_url: https://artifacts.apis.io/cerberusindex-com/privacy/cerberusindex-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- sale_or_sharing
summary_line: 8 quoted statements, read from Cerberus Index's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Safety
- XRPL
- Tokens
- Autonomous Agents
---
