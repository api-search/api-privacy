---
api_specs:
- filename: chimpanseo-app-audit-api-openapi.yml
  format: yaml
  label: ChimpanSEO Audit API
  slug: chimpanseo-app-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chimpanseo-app/openapi/chimpanseo-app-audit-api-openapi.yml
- filename: chimpanseo-app-mcp-api-openapi.yml
  format: yaml
  label: ChimpanSEO MCP API
  slug: chimpanseo-app-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chimpanseo-app/openapi/chimpanseo-app-mcp-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Registration data: email address, name (optional)'
  - category: identifying
    text: 'WordPress credentials: site URL, username, and Application Password — encrypted with AES-256 and never readable in plain text'
  - category: financial
    text: 'Payment data: handled entirely by Stripe Inc. — ChimpanSEO does not store credit card information'
  - category: device
    text: 'Technical data: IP address, browser, operating system (anonymous technical logs)'
  - category: behavioral
    text: 'Usage data: articles generated, connected sites, number of API requests'
  deletion:
    route: Account deletion; written request to hello@chimpanseo.app
    text: To exercise your rights, write to hello@chimpanseo.app .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Deliver the service
    text: Deliver the ChimpanSEO service (article generation, WordPress publishing)
  - purpose: Account management
    text: Manage user accounts and authentication
  - purpose: Subscription payments
    text: Process subscription payments
  - purpose: Service communications
    text: Send service communications (confirmations, updates, weekly digest)
  - purpose: Product improvement
    text: Improve the product through aggregated and anonymous usage data
  - purpose: Legal and tax compliance
    text: Comply with legal and tax obligations
  retention:
  - period: until account deletion
    scope: Account data
    text: Account data is retained until account deletion.
  - period: 10 years
    scope: Billing data
    text: Billing data is retained for 10 years for tax compliance (Italian D.P.R. 600/73).
  - period: 90 days
    scope: Technical logs
    text: Technical logs are deleted after 90 days.
  rights:
  - right: Access
    text: Access — obtain a copy of your data
  - right: Rectification
    text: Rectification — correct inaccurate data
  - right: Erasure
    text: Erasure — "right to be forgotten"
  - right: Portability
    text: Portability — receive data in a structured format
  - right: Objection
    text: Objection — object to processing based on legitimate interest
  - right: Restriction
    text: Restriction — restrict processing in certain circumstances
  role:
    text: The data controller is Nicolas Benedetti , reachable at hello@chimpanseo.app .
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Data transfers to the USA are based on Standard Contractual Clauses (SCCs) approved by the European Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ChimpanSEO
provenance_date: '2026-11-09'
provider_name: ChimpanSEO
provider_slug: chimpanseo-app
slug: chimpanseo-app-privacy-policy
source_date: '2026-11-09'
source_filename: chimpanseo-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://chimpanseo.app/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ChimpanSEO\naid: chimpanseo-app\nurl: https://chimpanseo.app/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is Nicolas Benedetti , reachable at hello@chimpanseo.app .\ndata_categories:\n- category: contact\n  text: 'Registration data: email address, name (optional)'\n- category: identifying\n  text: 'WordPress credentials: site URL, username, and Application Password — encrypted with AES-256 and never\n    readable in plain text'\n- category: financial\n  text: 'Payment data: handled entirely by Stripe Inc. — ChimpanSEO does not store credit card information'\n\
  - category: device\n  text: 'Technical data: IP address, browser, operating system (anonymous technical logs)'\n- category: behavioral\n  text: 'Usage data: articles generated, connected sites, number of API requests'\npurposes:\n- purpose: Deliver the service\n  text: Deliver the ChimpanSEO service (article generation, WordPress publishing)\n- purpose: Account management\n  text: Manage user accounts and authentication\n- purpose: Subscription payments\n  text: Process subscription payments\n- purpose: Service communications\n  text: Send service communications (confirmations, updates, weekly digest)\n- purpose: Product improvement\n  text: Improve the product through aggregated and anonymous usage data\n- purpose: Legal and tax compliance\n  text: Comply with legal and tax obligations\nretention:\n- scope: Account data\n  period: until account deletion\n  text: Account data is retained until account deletion.\n- scope: Billing data\n  period: 10 years\n  text: Billing data is retained\
  \ for 10 years for tax compliance (Italian D.P.R. 600/73).\n- scope: Technical logs\n  period: 90 days\n  text: Technical logs are deleted after 90 days.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Data transfers to the USA are based on Standard Contractual Clauses (SCCs) approved by the European Commission.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion; written request to hello@chimpanseo.app\n  text: To exercise your rights, write to hello@chimpanseo.app .\nrights:\n- right: Access\n  text: Access — obtain a copy of your data\n- right: Rectification\n  text: Rectification — correct inaccurate data\n- right: Erasure\n  text: Erasure — \"right to be forgotten\"\n- right: Portability\n  text: Portability — receive data in a structured format\n- right: Objection\n  text: Objection — object to processing based on legitimate interest\n- right: Restriction\n  text: Restriction — restrict processing\
  \ in certain circumstances\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chimpanseo-app/privacy/chimpanseo-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 23 quoted statements, read from ChimpanSEO's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SEO
- Generative Engine Optimization
- AI Content
- Content Marketing
- WordPress
- MCP
---
