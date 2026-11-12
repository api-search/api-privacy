---
api_specs:
- filename: corvio-ai-agent-collaboration-api-openapi.yml
  format: yaml
  label: Corvio Agent collaboration API
  slug: corvio-ai-agent-collaboration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corvio-ai/openapi/corvio-ai-agent-collaboration-api-openapi.yml
- filename: corvio-ai-public-api-v1-api-openapi.yml
  format: yaml
  label: Corvio Public API v1 API
  slug: corvio-ai-public-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corvio-ai/openapi/corvio-ai-public-api-v1-api-openapi.yml
- filename: corvio-ai-public-api-v1-files-api-openapi.yml
  format: yaml
  label: Corvio Public API v1 - Files API
  slug: corvio-ai-public-api-v1-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corvio-ai/openapi/corvio-ai-public-api-v1-files-api-openapi.yml
- filename: corvio-ai-public-api-v1-local-markdown-sync-api-openapi.yml
  format: yaml
  label: Corvio Public API v1 - Local Markdown Sync API
  slug: corvio-ai-public-api-v1-local-markdown-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corvio-ai/openapi/corvio-ai-public-api-v1-local-markdown-sync-api-openapi.yml
- filename: corvio-ai-public-api-v1-source-publication-api-openapi.yml
  format: yaml
  label: Corvio Public API v1 - Source publication API
  slug: corvio-ai-public-api-v1-source-publication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/corvio-ai/openapi/corvio-ai-public-api-v1-source-publication-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and identity data, such as name, username, email, phone number, and organization details
  - category: financial
    text: billing and transaction data, such as payment method identifiers, billing address, invoices, and tax information
  - category: device
    text: usage and device data, such as IP address, device identifiers, browser type, operating system, timestamps, feature usage metrics, and diagnostic logs
  - category: communication
    text: support and communications data, such as messages sent to support, feedback, and survey responses
  - category: other
    text: Content data to the extent it includes personal data, including personal data contained in documents, prompts, notes, messages, or attachments you upload
  - category: behavioral
    text: security and compliance data, such as authentication logs, access records, and abuse signals
  deletion:
    route: null
    text: we may retain certain logs and backups for a limited period even after deletion requests
  dpa:
    available: null
    text: where NeoFlux acts as a processor, the applicable Data Processing Addendum (“DPA”) governs
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: We process personal data to provide and operate the Service, including account creation, authentication, hosting content, generating Output, providing search/retrieval, enabling collaboration, and delivering customer support
  - purpose: Billing and payments
    text: to administer subscriptions, billing, and payments
  - purpose: Security and abuse prevention
    text: to secure the Service, prevent fraud, detect abuse, and enforce policies
  - purpose: Improve the Service
    text: to improve and develop the Service, including debugging and performance monitoring
  retention:
  - period: null
    scope: Personal data generally
    text: We retain personal data for as long as necessary to provide the Service, to fulfill the purposes described herein, to comply with legal obligations, to resolve disputes, and to enforce agreements
  - period: a limited period
    scope: Logs and backups after deletion requests
    text: we may retain certain logs and backups for a limited period even after deletion requests
  rights:
  - right: access, correct, delete, or port
    text: you may have rights to access, correct, delete, or port your personal data
  - right: withdraw consent
    text: to withdraw consent (where processing is based on consent)
  - right: object
    text: and to object to certain processing
  role:
    text: Depending on the context, NeoFlux may process personal data as a controller (e.g., when you create an Account, purchase a Subscription, or interact with our marketing sites) and/or as a processor
    value: both
  sale_or_sharing:
    stance: prohibited
    text: we do not sell personal data in the ordinary meaning of “sell” under common privacy statutes
  subprocessors:
    text: we require AI inference providers not to train their foundation models on Corvio inputs or outputs
    url: null
  transfers:
  - mechanism: SCC
    text: where required, we implement appropriate safeguards, which may include contractual protections, such as standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Corvio
provenance_date: '2026-11-09'
provider_name: Corvio
provider_slug: corvio-ai
slug: corvio-ai-privacy-policy
source_date: '2026-11-09'
source_filename: corvio-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://corvio.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Corvio\naid: corvio-ai\nurl: https://corvio.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Depending on the context, NeoFlux may process personal data as a controller (e.g., when you create an Account,\n    purchase a Subscription, or interact with our marketing sites) and/or as a processor\ndata_categories:\n- category: identifying\n  text: Account and identity data, such as name, username, email, phone number, and organization details\n- category: financial\n  text: billing and transaction data, such as payment method identifiers, billing address, invoices, and tax information\n- category:\
  \ device\n  text: usage and device data, such as IP address, device identifiers, browser type, operating system, timestamps,\n    feature usage metrics, and diagnostic logs\n- category: communication\n  text: support and communications data, such as messages sent to support, feedback, and survey responses\n- category: other\n  text: Content data to the extent it includes personal data, including personal data contained in documents, prompts,\n    notes, messages, or attachments you upload\n- category: behavioral\n  text: security and compliance data, such as authentication logs, access records, and abuse signals\npurposes:\n- purpose: Provide and operate the Service\n  text: We process personal data to provide and operate the Service, including account creation, authentication,\n    hosting content, generating Output, providing search/retrieval, enabling collaboration, and delivering customer\n    support\n- purpose: Billing and payments\n  text: to administer subscriptions, billing, and\
  \ payments\n- purpose: Security and abuse prevention\n  text: to secure the Service, prevent fraud, detect abuse, and enforce policies\n- purpose: Improve the Service\n  text: to improve and develop the Service, including debugging and performance monitoring\nretention:\n- scope: Personal data generally\n  period: null\n  text: We retain personal data for as long as necessary to provide the Service, to fulfill the purposes described\n    herein, to comply with legal obligations, to resolve disputes, and to enforce agreements\n- scope: Logs and backups after deletion requests\n  period: a limited period\n  text: we may retain certain logs and backups for a limited period even after deletion requests\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: where required, we implement appropriate safeguards, which may include contractual protections, such as\n    standard contractual clauses\nsubprocessors:\n  url: null\n  text: we require AI inference providers not to train their foundation\
  \ models on Corvio inputs or outputs\ndpa:\n  available: null\n  url: null\n  text: where NeoFlux acts as a processor, the applicable Data Processing Addendum (“DPA”) governs\ndeletion:\n  route: null\n  text: we may retain certain logs and backups for a limited period even after deletion requests\nrights:\n- right: access, correct, delete, or port\n  text: you may have rights to access, correct, delete, or port your personal data\n- right: withdraw consent\n  text: to withdraw consent (where processing is based on consent)\n- right: object\n  text: and to object to certain processing\nsale_or_sharing:\n  stance: prohibited\n  text: we do not sell personal data in the ordinary meaning of “sell” under common privacy statutes\n"
source_yaml_url: https://artifacts.apis.io/corvio-ai/privacy/corvio-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Corvio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Notes
- Knowledge Management
- Workspace
- AI Agents
- MCP
- Developer API
- CLI
---
