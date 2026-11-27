---
api_specs:
- filename: machinelibrary-ai-documents-api-openapi.yml
  format: yaml
  label: Space Frontiers Documents API
  slug: machinelibrary-ai-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/machinelibrary-ai/openapi/machinelibrary-ai-documents-api-openapi.yml
- filename: machinelibrary-ai-payments-api-openapi.yml
  format: yaml
  label: Space Frontiers Payments API
  slug: machinelibrary-ai-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/machinelibrary-ai/openapi/machinelibrary-ai-payments-api-openapi.yml
- filename: machinelibrary-ai-raw-document-downloads-api-openapi.yml
  format: yaml
  label: Space Frontiers Raw document downloads API
  slug: machinelibrary-ai-raw-document-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/machinelibrary-ai/openapi/machinelibrary-ai-raw-document-downloads-api-openapi.yml
- filename: machinelibrary-ai-recognition-api-openapi.yml
  format: yaml
  label: Space Frontiers Recognition API
  slug: machinelibrary-ai-recognition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/machinelibrary-ai/openapi/machinelibrary-ai-recognition-api-openapi.yml
- filename: machinelibrary-ai-search-api-openapi.yml
  format: yaml
  label: Space Frontiers Search API
  slug: machinelibrary-ai-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/machinelibrary-ai/openapi/machinelibrary-ai-search-api-openapi.yml
- filename: machinelibrary-ai-conversations-api-openapi.yml
  format: yaml
  label: Space Frontiers Conversations API
  slug: machinelibrary-ai-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/machinelibrary-ai/openapi/machinelibrary-ai-conversations-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account details: email address, password (stored as a hash), username, display name and avatar'
  - category: financial
    text: 'Payment details: amounts, dates, status and Stripe references for top-ups and subscriptions'
  - category: behavioral
    text: 'Search and activity logs: your searches and questions, the documents you open, and actions in the product'
  - category: communication
    text: Messages you send us
  - category: device
    text: IP address and browser details
  deletion:
    route: Profile → Delete account
    text: You can delete your account yourself at Profile → Delete account
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: To provide the service you signed up for (contract)
  - purpose: Keep the service secure
    text: 'To keep the service secure (legitimate interests: protecting accounts and infrastructure, preventing fraud, abuse and payment misuse)'
  - purpose: Improve search
    text: 'To improve search (legitimate interests: making results more relevant)'
  - purpose: Product news and offers
    text: To send product news and offers (consent)
  - purpose: Work with publishers and rights holders
    text: 'To work with publishers and rights holders (legitimate interests: licensing content, showing publishers demand for their works, and handling rights enquiries and claims)'
  residency:
  - region: United States
    text: Space Frontiers is based in the United States, so information you send us goes to the US.
  - region: European Union and US
    text: It is stored and processed on servers in the European Union and the US
  retention:
  - period: While your account exists
    scope: Account data
    text: While your account exists; deleted when you delete it.
  - period: For a limited period
    scope: Security access logs
    text: For a limited period, for security.
  - period: typically 7 years, at most 10
    scope: Payment and billing records
    text: typically 7 years, at most 10, after the end of the tax year.
  - period: Until overwritten in our backup cycle
    scope: Backups
    text: Until overwritten in our backup cycle
  - period: 3 years
    scope: Deletion request record
    text: Record of a deletion request 3 years, with no content.
  rights:
  - right: access
    text: access your personal information and get a copy
  - right: correct
    text: correct it
  - right: delete
    text: delete it (section 11)
  - right: restrict use
    text: restrict how we use it
  - right: portability
    text: receive the information you gave us in a machine-readable format (portability)
  - right: object
    text: object to uses based on legitimate interests, and to direct marketing at any time
  - right: withdraw consent
    text: withdraw consent at any time, without affecting earlier use
  - right: complain
    text: complain to a data protection authority
  role:
    text: The controller of your personal information is Space Frontiers, a Wyoming private corporation
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information or share it for cross-context behavioural advertising.
  subprocessors:
    text: We share it with these service providers, each limited to what its job needs
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the providers' Standard Contractual Clauses
  - mechanism: DPF
    text: their certification under the EU-US Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Space Frontiers
provenance_date: '2026-11-10'
provider_name: Space Frontiers
provider_slug: machinelibrary-ai
slug: machinelibrary-ai-privacy-policy
source_date: '2026-11-10'
source_filename: machinelibrary-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://machinelibrary.ai/privacy/world
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Space Frontiers\naid: machinelibrary-ai\nurl: https://machinelibrary.ai/privacy/world\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of your personal information is Space Frontiers, a Wyoming private corporation\ndata_categories:\n- category: identifying\n  text: 'Account details: email address, password (stored as a hash), username, display name and avatar'\n- category: financial\n  text: 'Payment details: amounts, dates, status and Stripe references for top-ups and subscriptions'\n- category: behavioral\n  text: 'Search and activity logs: your searches and questions, the documents\
  \ you open, and actions in the product'\n- category: communication\n  text: Messages you send us\n- category: device\n  text: IP address and browser details\npurposes:\n- purpose: Provide the service\n  text: To provide the service you signed up for (contract)\n- purpose: Keep the service secure\n  text: 'To keep the service secure (legitimate interests: protecting accounts and infrastructure, preventing fraud,\n    abuse and payment misuse)'\n- purpose: Improve search\n  text: 'To improve search (legitimate interests: making results more relevant)'\n- purpose: Product news and offers\n  text: To send product news and offers (consent)\n- purpose: Work with publishers and rights holders\n  text: 'To work with publishers and rights holders (legitimate interests: licensing content, showing publishers\n    demand for their works, and handling rights enquiries and claims)'\nretention:\n- scope: Account data\n  period: While your account exists\n  text: While your account exists; deleted when\
  \ you delete it.\n- scope: Security access logs\n  period: For a limited period\n  text: For a limited period, for security.\n- scope: Payment and billing records\n  period: typically 7 years, at most 10\n  text: typically 7 years, at most 10, after the end of the tax year.\n- scope: Backups\n  period: Until overwritten in our backup cycle\n  text: Until overwritten in our backup cycle\n- scope: Deletion request record\n  period: 3 years\n  text: Record of a deletion request 3 years, with no content.\nresidency:\n- region: United States\n  text: Space Frontiers is based in the United States, so information you send us goes to the US.\n- region: European Union and US\n  text: It is stored and processed on servers in the European Union and the US\ntransfers:\n- mechanism: SCC\n  text: we rely on the providers' Standard Contractual Clauses\n- mechanism: DPF\n  text: their certification under the EU-US Data Privacy Framework\nsubprocessors:\n  url: null\n  text: We share it with these service\
  \ providers, each limited to what its job needs\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Profile → Delete account\n  text: You can delete your account yourself at Profile → Delete account\nrights:\n- right: access\n  text: access your personal information and get a copy\n- right: correct\n  text: correct it\n- right: delete\n  text: delete it (section 11)\n- right: restrict use\n  text: restrict how we use it\n- right: portability\n  text: receive the information you gave us in a machine-readable format (portability)\n- right: object\n  text: object to uses based on legitimate interests, and to direct marketing at any time\n- right: withdraw consent\n  text: withdraw consent at any time, without affecting earlier use\n- right: complain\n  text: complain to a data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information or share it for cross-context behavioural advertising.\n"
source_yaml_url: https://artifacts.apis.io/machinelibrary-ai/privacy/machinelibrary-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 31 quoted statements, read from Space Frontiers's own page on 2026-11-10.
synthetic: false
tags:
- Research
- Scholarly Search
- Full-Text Search
- Retrieval
- RAG
- Patents
- Documents
- OCR
- Document Recognition
- MCP
- A2A
- Agent-Native
- AI Agents
- Data
- Search
---
