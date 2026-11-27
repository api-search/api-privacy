---
api_specs:
- filename: mcpnest-openapi-generated.yml
  format: yaml
  label: MCPNest API
  slug: mcpnest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mcpnest/openapi/_ae-authored/mcpnest-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: name, email address, GitHub username and avatar (via GitHub OAuth)'
  - category: behavioral
    text: 'Usage data: pages visited, search queries, MCP servers viewed and installed'
  - category: financial
    text: 'Payment data: handled entirely by Stripe — we never store card details'
  - category: device
    text: 'Technical data: IP address, browser type, device information, cookies'
  deletion:
    route: Delete account; email malasartes@mcpnest.io for erasure requests
    text: If you delete your account, we delete your personal data within 30 days
  dpa:
    available: null
    text: Each service has its own privacy policy and data processing terms.
    url: null
  purposes:
  - purpose: Provide and improve service
    text: Provide and improve the MCPNest service
  - purpose: Authentication
    text: Authenticate you via GitHub OAuth
  - purpose: Payment processing
    text: Process payments via Stripe
  - purpose: Transactional emails
    text: Send transactional emails (receipts, account notifications)
  - purpose: Usage analysis
    text: Analyze usage to improve the platform
  - purpose: Legal compliance
    text: Comply with legal obligations
  residency:
  - region: Portugal (EU)
    text: MCPNest is operated from Portugal (EU).
  retention:
  - period: as long as your account is active
    scope: Account data
    text: We retain your account data for as long as your account is active.
  - period: 30 days
    scope: Deleted account personal data
    text: If you delete your account, we delete your personal data within 30 days, except where we are legally required to retain it
  - period: 7 years
    scope: Financial records
    text: financial records for 7 years under Portuguese law
  rights:
  - right: Access
    text: Access — request a copy of your personal data
  - right: Rectification
    text: Rectification — correct inaccurate data
  - right: Erasure
    text: Erasure — request deletion of your data ("right to be forgotten")
  - right: Portability
    text: Portability — receive your data in a machine-readable format
  - right: Restriction
    text: Restriction — limit how we process your data
  - right: Objection
    text: Objection — object to processing based on legitimate interests
  role:
    text: MCPNest ("we", "us", "our") is a marketplace for Model Context Protocol (MCP) servers, operated by Ricardo Rodrigues, based in Portugal.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: These transfers are covered by Standard Contractual Clauses (SCCs) approved by the European Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MCPNest
provenance_date: '2026-11-10'
provider_name: MCPNest
provider_slug: mcpnest
slug: mcpnest-privacy-policy
source_date: '2026-11-10'
source_filename: mcpnest-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mcpnest.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MCPNest\naid: mcpnest\nurl: https://mcpnest.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: MCPNest (\"we\", \"us\", \"our\") is a marketplace for Model Context Protocol (MCP) servers, operated by Ricardo\n    Rodrigues, based in Portugal.\ndata_categories:\n- category: identifying\n  text: 'Account data: name, email address, GitHub username and avatar (via GitHub OAuth)'\n- category: behavioral\n  text: 'Usage data: pages visited, search queries, MCP servers viewed and installed'\n- category: financial\n  text: 'Payment data: handled entirely by Stripe — we never store card details'\n\
  - category: device\n  text: 'Technical data: IP address, browser type, device information, cookies'\npurposes:\n- purpose: Provide and improve service\n  text: Provide and improve the MCPNest service\n- purpose: Authentication\n  text: Authenticate you via GitHub OAuth\n- purpose: Payment processing\n  text: Process payments via Stripe\n- purpose: Transactional emails\n  text: Send transactional emails (receipts, account notifications)\n- purpose: Usage analysis\n  text: Analyze usage to improve the platform\n- purpose: Legal compliance\n  text: Comply with legal obligations\nretention:\n- scope: Account data\n  period: as long as your account is active\n  text: We retain your account data for as long as your account is active.\n- scope: Deleted account personal data\n  period: 30 days\n  text: If you delete your account, we delete your personal data within 30 days, except where we are legally required\n    to retain it\n- scope: Financial records\n  period: 7 years\n  text: financial\
  \ records for 7 years under Portuguese law\nresidency:\n- region: Portugal (EU)\n  text: MCPNest is operated from Portugal (EU).\ntransfers:\n- mechanism: SCC\n  text: These transfers are covered by Standard Contractual Clauses (SCCs) approved by the European Commission.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Each service has its own privacy policy and data processing terms.\ndeletion:\n  route: Delete account; email malasartes@mcpnest.io for erasure requests\n  text: If you delete your account, we delete your personal data within 30 days\nrights:\n- right: Access\n  text: Access — request a copy of your personal data\n- right: Rectification\n  text: Rectification — correct inaccurate data\n- right: Erasure\n  text: Erasure — request deletion of your data (\"right to be forgotten\")\n- right: Portability\n  text: Portability — receive your data in a machine-readable format\n- right: Restriction\n  text: Restriction — limit how we process\
  \ your data\n- right: Objection\n  text: Objection — object to processing based on legitimate interests\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/mcpnest/privacy/mcpnest-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from MCPNest's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Cloud
- DevOps
- Artificial Intelligence
---
