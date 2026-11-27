---
api_specs:
- filename: awareness-market-openapi-generated.yml
  format: yaml
  label: Awareness API
  slug: awareness-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/awareness-market/openapi/_ae-authored/awareness-market-openapi-generated.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: we may receive your name, email address, and profile image from the provider
  - category: behavioral
    text: Content you ingest through the MCP Server, REST API, SDK, or web interface, including conversation logs, documents, embeddings, notes, and metadata, may be stored in our databases and associated with your account.
  - category: device
    text: We collect technical and operational logs, such as API timestamps, error logs, performance metrics, and service diagnostics.
  - category: communication
    text: If you contact us for support, enterprise evaluation, or partnership discussions, we may retain those communications to respond to you and improve the Service.
  deletion:
    route: account deletion
    text: After account deletion, we will delete or anonymize personal data within 30 days
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and improve the Service
    text: provide, operate, maintain, and improve the Service
  - purpose: AI-assisted workflows
    text: process memory retrieval, indexing, and AI-assisted workflows on your behalf
  - purpose: security and fraud prevention
    text: detect and prevent fraud, abuse, and security incidents
  - purpose: legal compliance
    text: comply with legal obligations and respond to lawful government requests
  retention:
  - period: null
    scope: account data and memory content
    text: We retain account data and memory content for as long as your account remains active or as needed to provide the Service.
  - period: 30 days
    scope: after account deletion
    text: After account deletion, we will delete or anonymize personal data within 30 days unless retention is required for legal compliance, dispute resolution, fraud prevention, or legitimate audit needs.
  rights:
  - right: access
    text: access the personal data we hold about you
  - right: correction
    text: correct inaccurate or incomplete data
  - right: deletion
    text: request deletion of your personal data, subject to lawful retention obligations
  - right: portability
    text: receive your data in a structured, machine-readable format where applicable
  - right: restriction
    text: restrict processing in certain circumstances
  - right: objection
    text: object to processing based on legitimate interests
  - right: withdraw consent
    text: withdraw consent where processing relies on consent
  role:
    text: Awareness acts as the data controller for personal data processed in connection with account registration, authentication, billing, and platform usage. For processing activities that you initiate through the Service, such as ingesting third-party memory content, you act as the data controller and Awareness acts as your data processor.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where personal data is transferred outside your jurisdiction, we implement appropriate safeguards, such as Standard Contractual Clauses or similar lawful transfer mechanisms where required.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Awareness
provenance_date: '2026-11-09'
provider_name: Awareness
provider_slug: awareness-market
slug: awareness-market-privacy-policy
source_date: '2026-11-09'
source_filename: awareness-market-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://awareness.market/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Awareness\naid: awareness-market\nurl: https://awareness.market/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Awareness acts as the data controller for personal data processed in connection with account registration,\n    authentication, billing, and platform usage. For processing activities that you initiate through the Service,\n    such as ingesting third-party memory content, you act as the data controller and Awareness acts as your data\n    processor.\ndata_categories:\n- category: identifying\n  text: we may receive your name, email address, and profile image from the provider\n\
  - category: behavioral\n  text: Content you ingest through the MCP Server, REST API, SDK, or web interface, including conversation logs,\n    documents, embeddings, notes, and metadata, may be stored in our databases and associated with your account.\n- category: device\n  text: We collect technical and operational logs, such as API timestamps, error logs, performance metrics, and\n    service diagnostics.\n- category: communication\n  text: If you contact us for support, enterprise evaluation, or partnership discussions, we may retain those communications\n    to respond to you and improve the Service.\npurposes:\n- purpose: provide and improve the Service\n  text: provide, operate, maintain, and improve the Service\n- purpose: AI-assisted workflows\n  text: process memory retrieval, indexing, and AI-assisted workflows on your behalf\n- purpose: security and fraud prevention\n  text: detect and prevent fraud, abuse, and security incidents\n- purpose: legal compliance\n  text: comply with\
  \ legal obligations and respond to lawful government requests\nretention:\n- scope: account data and memory content\n  period: null\n  text: We retain account data and memory content for as long as your account remains active or as needed to provide\n    the Service.\n- scope: after account deletion\n  period: 30 days\n  text: After account deletion, we will delete or anonymize personal data within 30 days unless retention is required\n    for legal compliance, dispute resolution, fraud prevention, or legitimate audit needs.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where personal data is transferred outside your jurisdiction, we implement appropriate safeguards, such\n    as Standard Contractual Clauses or similar lawful transfer mechanisms where required.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion\n  text: After account deletion, we will delete or anonymize personal data within 30 days\n\
  rights:\n- right: access\n  text: access the personal data we hold about you\n- right: correction\n  text: correct inaccurate or incomplete data\n- right: deletion\n  text: request deletion of your personal data, subject to lawful retention obligations\n- right: portability\n  text: receive your data in a structured, machine-readable format where applicable\n- right: restriction\n  text: restrict processing in certain circumstances\n- right: objection\n  text: object to processing based on legitimate interests\n- right: withdraw consent\n  text: withdraw consent where processing relies on consent\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/awareness-market/privacy/awareness-market-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Awareness's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- Agents
- Open Source
- Cloud
---
