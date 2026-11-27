---
api_specs:
- filename: archastro-activity-feed-api-openapi.yml
  format: yaml
  label: Archastro Activity Feed API
  slug: archastro-activity-feed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archastro/openapi/archastro-activity-feed-api-openapi.yml
- filename: archastro-agents-api-openapi.yml
  format: yaml
  label: Archastro Agents API
  slug: archastro-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archastro/openapi/archastro-agents-api-openapi.yml
- filename: archastro-auth-api-openapi.yml
  format: yaml
  label: Archastro Auth API
  slug: archastro-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archastro/openapi/archastro-auth-api-openapi.yml
- filename: archastro-files-api-openapi.yml
  format: yaml
  label: Archastro Files API
  slug: archastro-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archastro/openapi/archastro-files-api-openapi.yml
- filename: archastro-s2s-api-openapi.yml
  format: yaml
  label: Archastro S2s API
  slug: archastro-s2s-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archastro/openapi/archastro-s2s-api-openapi.yml
- filename: archastro-slack-channel-bindings-api-openapi.yml
  format: yaml
  label: Archastro Slack Channel Bindings API
  slug: archastro-slack-channel-bindings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archastro/openapi/archastro-slack-channel-bindings-api-openapi.yml
- filename: archastro-teams-api-openapi.yml
  format: yaml
  label: Archastro Teams API
  slug: archastro-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archastro/openapi/archastro-teams-api-openapi.yml
- filename: archastro-threads-api-openapi.yml
  format: yaml
  label: Archastro Threads API
  slug: archastro-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archastro/openapi/archastro-threads-api-openapi.yml
- filename: archastro-users-api-openapi.yml
  format: yaml
  label: Archastro Users API
  slug: archastro-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archastro/openapi/archastro-users-api-openapi.yml
- filename: archastro-oauth-api-openapi.yml
  format: yaml
  label: Archastro OAUTH API
  slug: archastro-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/archastro/openapi/archastro-oauth-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: Business contact data (name, work email, title, organization).
  - category: financial
    text: Commercial and account data (contracting and billing contacts, support interactions).
  - category: device
    text: Website and product access metadata (IP address, browser/device metadata, timestamps).
  - category: communication
    text: Customers may submit data to the Services, including prompts, files, memory content, integration payloads, agent logs, and workflow artifacts.
  deletion:
    route: Contact privacy@archastro.ai for controller data; customer contract governs Customer Data
    text: For controller data, individuals may request access, correction, deletion, or restriction, subject to applicable law.
  dpa:
    available: true
    text: data processing agreement ("DPA")
    url: null
  purposes:
  - purpose: Service delivery and model inference
    text: ArchAstro processes data solely for service delivery, including model inference and related platform operations
  - purpose: Account administration
    text: Provide and administer accounts.
  - purpose: Security
    text: Secure the Services and detect misuse.
  - purpose: Support
    text: Provide support and customer communications.
  - purpose: Analytics
    text: ArchAstro uses Google Analytics 4 on its public websites (archastro.ai and archagents.com) to understand aggregate traffic and how visitors use the sites.
  retention:
  - period: null
    scope: Controller data
    text: Controller data is retained according to business need, legal obligations, and recordkeeping requirements.
  - period: null
    scope: Customer Data
    text: Customer Data retention, deletion, and export timelines are governed by the customer contract and service configuration.
  rights:
  - right: access
    text: individuals may request access, correction, deletion, or restriction, subject to applicable law.
  role:
    text: For Customer Data processed through the Services, ArchAstro acts as a processor/service provider under customer instructions
    value: both
  sale_or_sharing:
    stance: prohibited
    text: ArchAstro does not sell personal data.
  subprocessors:
    text: ArchAstro maintains a subprocessor list and will provide relevant subprocessor information through customer documentation or the contract process.
    url: null
  transfers:
  - mechanism: other
    text: Where required by applicable data protection law, ArchAstro implements appropriate safeguards for cross-border transfers (for example, contractual transfer mechanisms)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Archastro
provenance_date: '2026-11-09'
provider_name: Archastro
provider_slug: archastro
slug: archastro-privacy-policy
source_date: '2026-11-09'
source_filename: archastro-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://archastro.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Archastro\naid: archastro\nurl: https://archastro.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For Customer Data processed through the Services, ArchAstro acts as a processor/service provider under customer\n    instructions\ndata_categories:\n- category: contact\n  text: Business contact data (name, work email, title, organization).\n- category: financial\n  text: Commercial and account data (contracting and billing contacts, support interactions).\n- category: device\n  text: Website and product access metadata (IP address, browser/device metadata, timestamps).\n- category: communication\n\
  \  text: Customers may submit data to the Services, including prompts, files, memory content, integration payloads,\n    agent logs, and workflow artifacts.\npurposes:\n- purpose: Service delivery and model inference\n  text: ArchAstro processes data solely for service delivery, including model inference and related platform operations\n- purpose: Account administration\n  text: Provide and administer accounts.\n- purpose: Security\n  text: Secure the Services and detect misuse.\n- purpose: Support\n  text: Provide support and customer communications.\n- purpose: Analytics\n  text: ArchAstro uses Google Analytics 4 on its public websites (archastro.ai and archagents.com) to understand\n    aggregate traffic and how visitors use the sites.\nretention:\n- scope: Controller data\n  period: null\n  text: Controller data is retained according to business need, legal obligations, and recordkeeping requirements.\n- scope: Customer Data\n  period: null\n  text: Customer Data retention, deletion,\
  \ and export timelines are governed by the customer contract and service\n    configuration.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Where required by applicable data protection law, ArchAstro implements appropriate safeguards for cross-border\n    transfers (for example, contractual transfer mechanisms)\nsubprocessors:\n  url: null\n  text: ArchAstro maintains a subprocessor list and will provide relevant subprocessor information through customer\n    documentation or the contract process.\ndpa:\n  available: true\n  url: null\n  text: data processing agreement (\"DPA\")\ndeletion:\n  route: Contact privacy@archastro.ai for controller data; customer contract governs Customer Data\n  text: For controller data, individuals may request access, correction, deletion, or restriction, subject to applicable\n    law.\nrights:\n- right: access\n  text: individuals may request access, correction, deletion, or restriction, subject to applicable law.\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: ArchAstro does not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/archastro/privacy/archastro-privacy-policy.yml
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
summary_line: 18 quoted statements, read from Archastro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Developer Platform
- Automation
- Integration
- MCP
- Workflows
---
