---
api_specs:
- filename: chieflab-io-connectors-api-openapi.yml
  format: yaml
  label: ChiefLab Connectors API
  slug: chieflab-io-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chieflab-io/openapi/chieflab-io-connectors-api-openapi.yml
- filename: chieflab-io-gtm-api-openapi.yml
  format: yaml
  label: ChiefLab GTM API
  slug: chieflab-io-gtm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chieflab-io/openapi/chieflab-io-gtm-api-openapi.yml
- filename: chieflab-io-mcp-api-openapi.yml
  format: yaml
  label: ChiefLab MCP API
  slug: chieflab-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chieflab-io/openapi/chieflab-io-mcp-api-openapi.yml
- filename: chieflab-io-public-api-openapi.yml
  format: yaml
  label: ChiefLab Public API
  slug: chieflab-io-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chieflab-io/openapi/chieflab-io-public-api-openapi.yml
- filename: chieflab-io-runs-api-openapi.yml
  format: yaml
  label: ChiefLab Runs API
  slug: chieflab-io-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chieflab-io/openapi/chieflab-io-runs-api-openapi.yml
- filename: chieflab-io-workspace-api-openapi.yml
  format: yaml
  label: ChiefLab Workspace API
  slug: chieflab-io-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chieflab-io/openapi/chieflab-io-workspace-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: email, workspace ID, API key (stored as a SHA-256 hash, never the raw key).'
  - category: financial
    text: 'Billing: Stripe customer ID and plan tier (when wired). We do not store card numbers; Stripe does.'
  - category: device
    text: IP address, user agent, request timestamps for rate limiting and abuse detection.
  - category: behavioral
    text: Audit log — who accessed what within your workspace.
  - category: other
    text: Brain — brand voice samples, repo facts, ICPs, proof points, competitor watch, approved drafts
  deletion:
    route: 'chieflab_delete_workspace({ confirm: "DELETE-MY-WORKSPACE" }) and chieflab_purge_subject({ handle, confirm: "PURGE-SUBJECT" }); email privacy@chieflab.io for bespoke DSAR requests'
    text: 'chieflab_delete_workspace({ confirm: "DELETE-MY-WORKSPACE" }) — Shipped. Hard-purges all workspace data across 38+ tables, revokes the API key, returns a deletion receipt.'
  dpa:
    available: true
    text: The Data Processing Agreement is the contract that governs that relationship. Sign it with your enterprise buyers
    url: null
  purposes:
  - purpose: Operate the service
    text: Operate the service you signed up for.
  - purpose: Billing
    text: Bill you (when applicable).
  - purpose: Abuse detection and prevention
    text: Detect and prevent abuse.
  - purpose: Service improvement
    text: Improve the service using aggregated, non-identifying signals only.
  - purpose: Legal compliance
    text: Comply with law and respond to legally valid requests (and challenge improper ones).
  residency:
  - region: US
    text: 'Primary database: Supabase, US region by default.'
  - region: EU
    text: EU region available on Enterprise.
  retention:
  - period: null
    scope: Active workspace data
    text: Active workspace data — kept while your workspace exists.
  - period: 30 days
    scope: Deleted workspace data
    text: deleted within 30 days of a workspace deletion request
  - period: 7 days
    scope: Backups
    text: Supabase point-in-time recovery retains up to 7 days of historical state past a hard delete.
  - period: 90 days minimum
    scope: Audit log
    text: Audit log — 90 days minimum, longer on Enterprise.
  - period: 7 years
    scope: Billing records
    text: Billing records — 7 years (tax / accounting legal obligation).
  rights:
  - right: Access
    text: Access — chieflab_export_workspace() returns a full structured JSON dump.
  - right: Correction
    text: Correction — edit via /app or email hi@chieflab.io .
  - right: Deletion
    text: 'Deletion — chieflab_delete_workspace({ confirm: "DELETE-MY-WORKSPACE" }) hard-purges across 38+ tables on confirmation.'
  - right: Portability
    text: Portability — same as Access; the export is structured JSON, importable elsewhere.
  - right: Object / restrict / withdraw consent
    text: Object / restrict / withdraw consent — email privacy@chieflab.io .
  - right: Opt out of sale
    text: California residents (CCPA/CPRA) — right to know, delete, correct, opt out of sale (we don't sell)
  role:
    text: you are the controller . We are the processor .
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data. Ever.
  subprocessors:
    text: Subprocessors at /legal/subprocessors , each bound by data protection terms substantively equivalent to this policy and the DPA .
    url: https://chieflab.io/legal/subprocessors
  transfers:
  - mechanism: SCC
    text: For transfers from EEA / UK / Switzerland to outside, Standard Contractual Clauses (EU Commission Decision 2021/914) apply
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ChiefLab
provenance_date: '2026-11-09'
provider_name: ChiefLab
provider_slug: chieflab-io
slug: chieflab-io-privacy-policy
source_date: '2026-11-09'
source_filename: chieflab-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://chieflab.io/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ChiefLab\naid: chieflab-io\nurl: https://chieflab.io/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: you are the controller . We are the processor .\ndata_categories:\n- category: identifying\n  text: 'Account: email, workspace ID, API key (stored as a SHA-256 hash, never the raw key).'\n- category: financial\n  text: 'Billing: Stripe customer ID and plan tier (when wired). We do not store card numbers; Stripe does.'\n- category: device\n  text: IP address, user agent, request timestamps for rate limiting and abuse detection.\n- category: behavioral\n  text: Audit log — who accessed\
  \ what within your workspace.\n- category: other\n  text: Brain — brand voice samples, repo facts, ICPs, proof points, competitor watch, approved drafts\npurposes:\n- purpose: Operate the service\n  text: Operate the service you signed up for.\n- purpose: Billing\n  text: Bill you (when applicable).\n- purpose: Abuse detection and prevention\n  text: Detect and prevent abuse.\n- purpose: Service improvement\n  text: Improve the service using aggregated, non-identifying signals only.\n- purpose: Legal compliance\n  text: Comply with law and respond to legally valid requests (and challenge improper ones).\nretention:\n- scope: Active workspace data\n  period: null\n  text: Active workspace data — kept while your workspace exists.\n- scope: Deleted workspace data\n  period: 30 days\n  text: deleted within 30 days of a workspace deletion request\n- scope: Backups\n  period: 7 days\n  text: Supabase point-in-time recovery retains up to 7 days of historical state past a hard delete.\n- scope:\
  \ Audit log\n  period: 90 days minimum\n  text: Audit log — 90 days minimum, longer on Enterprise.\n- scope: Billing records\n  period: 7 years\n  text: Billing records — 7 years (tax / accounting legal obligation).\nresidency:\n- region: US\n  text: 'Primary database: Supabase, US region by default.'\n- region: EU\n  text: EU region available on Enterprise.\ntransfers:\n- mechanism: SCC\n  text: For transfers from EEA / UK / Switzerland to outside, Standard Contractual Clauses (EU Commission Decision\n    2021/914) apply\nsubprocessors:\n  url: https://chieflab.io/legal/subprocessors\n  text: Subprocessors at /legal/subprocessors , each bound by data protection terms substantively equivalent to\n    this policy and the DPA .\ndpa:\n  available: true\n  url: null\n  text: The Data Processing Agreement is the contract that governs that relationship. Sign it with your enterprise\n    buyers\ndeletion:\n  route: 'chieflab_delete_workspace({ confirm: \"DELETE-MY-WORKSPACE\" }) and chieflab_purge_subject({\
  \ handle, confirm:\n    \"PURGE-SUBJECT\" }); email privacy@chieflab.io for bespoke DSAR requests'\n  text: 'chieflab_delete_workspace({ confirm: \"DELETE-MY-WORKSPACE\" }) — Shipped. Hard-purges all workspace data\n    across 38+ tables, revokes the API key, returns a deletion receipt.'\nrights:\n- right: Access\n  text: Access — chieflab_export_workspace() returns a full structured JSON dump.\n- right: Correction\n  text: Correction — edit via /app or email hi@chieflab.io .\n- right: Deletion\n  text: 'Deletion — chieflab_delete_workspace({ confirm: \"DELETE-MY-WORKSPACE\" }) hard-purges across 38+ tables\n    on confirmation.'\n- right: Portability\n  text: Portability — same as Access; the export is structured JSON, importable elsewhere.\n- right: Object / restrict / withdraw consent\n  text: Object / restrict / withdraw consent — email privacy@chieflab.io .\n- right: Opt out of sale\n  text: California residents (CCPA/CPRA) — right to know, delete, correct, opt out of sale (we don't\
  \ sell)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data. Ever.\n"
source_yaml_url: https://artifacts.apis.io/chieflab-io/privacy/chieflab-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from ChiefLab's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Growth Marketing
- MCP
- Product Launch
- Marketing Automation
- Approval Workflows
- Developer Tools
---
