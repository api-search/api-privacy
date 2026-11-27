---
api_specs:
- filename: grandet-ai-openapi.yml
  format: yaml
  label: Grandet Anonymous Price Discovery API
  slug: grandet-anonymous-price-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grandet-ai/openapi/grandet-ai-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: device
    text: Fields include random installation and event IDs, revision, operation, Skill version, content digest, source, host and scope categories
  - category: behavioral
    text: Lookup records retain UTC dates, source and target app labels and version tags
  - category: identifying
    text: Star ratings, account management and provider submissions use email sign-in.
  - category: communication
    text: Visitors and agents can leave messages directly.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: installation statistics and troubleshooting
    text: Receipts support installation statistics and troubleshooting.
  - purpose: page measurement
    text: Page views and visits are measured with Cloudflare Web Analytics, which uses no cookies and does not identify individuals.
  - purpose: restoring the page after a site update
    text: a page-version marker that restores the page after a site update
  retention:
  - period: 24 months
    scope: installation receipts
    text: Raw receipts are retained for 24 months; later archiving is a separate policy.
  - period: null
    scope: hosting logs
    text: we are still confirming how long it keeps logs.
  rights:
  - right: access by owners
    text: Details are available to owners.
  - right: opt out of installation telemetry
    text: Use --no-telemetry or GRANDET_INSTALL_TELEMETRY=0 to disable sending and clear this installation’s unsent queue.
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
name: grandet-ai
provenance_date: '2026-11-09'
provider_name: grandet-ai
provider_slug: grandet-ai
slug: grandet-ai-privacy-policy
source_date: '2026-11-09'
source_filename: grandet-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://grandet.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: grandet-ai\naid: grandet-ai\nurl: https://grandet.ai/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: Fields include random installation and event IDs, revision, operation, Skill version, content digest, source,\n    host and scope categories\n- category: behavioral\n  text: Lookup records retain UTC dates, source and target app labels and version tags\n- category: identifying\n  text: Star ratings, account management and provider submissions use email sign-in.\n- category: communication\n  text: Visitors and agents can leave messages\
  \ directly.\npurposes:\n- purpose: installation statistics and troubleshooting\n  text: Receipts support installation statistics and troubleshooting.\n- purpose: page measurement\n  text: Page views and visits are measured with Cloudflare Web Analytics, which uses no cookies and does not identify\n    individuals.\n- purpose: restoring the page after a site update\n  text: a page-version marker that restores the page after a site update\nretention:\n- scope: installation receipts\n  period: 24 months\n  text: Raw receipts are retained for 24 months; later archiving is a separate policy.\n- scope: hosting logs\n  period: null\n  text: we are still confirming how long it keeps logs.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access by owners\n  text: Details are available to owners.\n- right: opt out of installation telemetry\n  text: Use --no-telemetry\
  \ or GRANDET_INSTALL_TELEMETRY=0 to disable sending and clear this installation’s unsent\n    queue.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/grandet-ai/privacy/grandet-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- rights
summary_line: 11 quoted statements, read from grandet-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- Pricing
- Data
---
