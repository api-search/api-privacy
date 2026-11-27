---
api_specs:
- filename: agentcreditdata-com-agent-api-openapi.yml
  format: yaml
  label: Agent Credit Bureau Agent API
  slug: agentcreditdata-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcreditdata-com/openapi/agentcreditdata-com-agent-api-openapi.yml
- filename: agentcreditdata-com-assess-api-openapi.yml
  format: yaml
  label: Agent Credit Bureau Assess API
  slug: agentcreditdata-com-assess-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcreditdata-com/openapi/agentcreditdata-com-assess-api-openapi.yml
- filename: agentcreditdata-com-verify-api-openapi.yml
  format: yaml
  label: Agent Credit Bureau Verify API
  slug: agentcreditdata-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentcreditdata-com/openapi/agentcreditdata-com-verify-api-openapi.yml
claim_count: 4
description: ''
doc:
  data_categories:
  - category: financial
    text: A private payment journal retains authorization coordinates and a credential hash for replay protection and reconciliation; it does not retain signatures.
  - category: behavioral
    text: We record source costs, timing, status, payment outcome and pseudonymous usage counts.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: replay protection and reconciliation
    text: A private payment journal retains authorization coordinates and a credential hash for replay protection and reconciliation; it does not retain signatures.
  - purpose: reproducible reports
    text: retain versioned evidence to make reports reproducible.
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
name: Agent Credit Bureau
provenance_date: '2026-11-09'
provider_name: Agent Credit Bureau
provider_slug: agentcreditdata-com
slug: agentcreditdata-com-privacy-policy
source_date: '2026-11-09'
source_filename: agentcreditdata-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentcreditdata.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agent Credit Bureau\naid: agentcreditdata-com\nurl: https://agentcreditdata.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: financial\n  text: A private payment journal retains authorization coordinates and a credential hash for replay protection\n    and reconciliation; it does not retain signatures.\n- category: behavioral\n  text: We record source costs, timing, status, payment outcome and pseudonymous usage counts.\npurposes:\n- purpose: replay protection and reconciliation\n  text: A private payment journal retains authorization coordinates\
  \ and a credential hash for replay protection\n    and reconciliation; it does not retain signatures.\n- purpose: reproducible reports\n  text: retain versioned evidence to make reports reproducible.\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentcreditdata-com/privacy/agentcreditdata-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
summary_line: 4 quoted statements, read from Agent Credit Bureau's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Credit
- Artificial Intelligence
- Data
---
