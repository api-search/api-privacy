---
api_specs:
- filename: kaiv-ai-account-api-openapi.yml
  format: yaml
  label: kaiv-ai Account API
  slug: kaiv-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiv-ai/openapi/kaiv-ai-account-api-openapi.yml
- filename: kaiv-ai-activity-api-openapi.yml
  format: yaml
  label: kaiv-ai Activity API
  slug: kaiv-ai-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiv-ai/openapi/kaiv-ai-activity-api-openapi.yml
- filename: kaiv-ai-changes-api-openapi.yml
  format: yaml
  label: kaiv-ai Changes API
  slug: kaiv-ai-changes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiv-ai/openapi/kaiv-ai-changes-api-openapi.yml
- filename: kaiv-ai-credentials-api-openapi.yml
  format: yaml
  label: kaiv-ai Credentials API
  slug: kaiv-ai-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiv-ai/openapi/kaiv-ai-credentials-api-openapi.yml
- filename: kaiv-ai-documents-api-openapi.yml
  format: yaml
  label: kaiv-ai Documents API
  slug: kaiv-ai-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiv-ai/openapi/kaiv-ai-documents-api-openapi.yml
- filename: kaiv-ai-keys-api-openapi.yml
  format: yaml
  label: kaiv-ai Keys API
  slug: kaiv-ai-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiv-ai/openapi/kaiv-ai-keys-api-openapi.yml
- filename: kaiv-ai-no-account-api-openapi.yml
  format: yaml
  label: kaiv-ai No account API
  slug: kaiv-ai-no-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiv-ai/openapi/kaiv-ai-no-account-api-openapi.yml
- filename: kaiv-ai-policies-api-openapi.yml
  format: yaml
  label: kaiv-ai Policies API
  slug: kaiv-ai-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiv-ai/openapi/kaiv-ai-policies-api-openapi.yml
- filename: kaiv-ai-servers-api-openapi.yml
  format: yaml
  label: kaiv-ai Servers API
  slug: kaiv-ai-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kaiv-ai/openapi/kaiv-ai-servers-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (used for authentication)
  - category: contact
    text: Name, work email, role, and company (where provided)
  - category: financial
    text: We do not store card numbers on Kaiva systems.
  - category: device
    text: IP address for maintaining platform security
  - category: behavioral
    text: Feature usage and engagement analytics
  - category: communication
    text: 'Email delivery provider: Sends our service emails'
  deletion:
    route: Email [email protected] to exercise rights, including erasure
    text: Erasure , request deletion, subject to legal retention obligations and security holds.
  dpa:
    available: null
    text: Where a specific data-processing agreement applies between us, its terms govern.
    url: null
  purposes:
  - purpose: Service provision
    text: Relay tool calls between your AI client and the systems you connect
  - purpose: Analytics and improvement
    text: Understand how the product is used
  - purpose: Communication
    text: Send important service updates and notifications
  residency:
  - region: EU
    text: Our production infrastructure is located in the EU by default.
  retention:
  - period: 90 days
    scope: Kaiva Bridge tool-call records
    text: Kept 90 days, or up to 365 days for a specific complaint or legal claim; deleted with the workspace.
  - period: 90 days
    scope: IP addresses
    text: IP addresses 90 days
  - period: 7 years
    scope: Billing and financial records
    text: Billing and financial records 7 years
  - period: 14 days
    scope: Database backups
    text: Database backups 14 days
  rights:
  - right: Access
    text: Access , request a copy of personal data we hold about you.
  - right: Erasure
    text: Erasure , request deletion, subject to legal retention obligations and security holds.
  - right: Rectification
    text: Rectification , request correction of inaccurate or incomplete data.
  - right: Portability
    text: Portability , where applicable.
  - right: Object
    text: Object , to processing on the basis of legitimate interest or for direct marketing.
  role:
    text: We are controller for our website and marketing; processor for customer data routed through the product.
    value: both
  sale_or_sharing:
    stance: unstated
    text: We do not sell your personal data, and we do not use customer data to train foundation models.
  subprocessors:
    text: A current list of sub-processors is available on request to [email protected] .
    url: null
  transfers:
  - mechanism: adequacy
    text: an adequacy decision (including, for UK transfers, the UK extension to the EU–US Data Privacy Framework where applicable)
  - mechanism: SCC
    text: the EU Standard Contractual Clauses 2021/914 where a transfer is EEA-originating
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: kaiv-ai
provenance_date: '2026-11-09'
provider_name: kaiv-ai
provider_slug: kaiv-ai
slug: kaiv-ai-privacy-policy
source_date: '2026-11-09'
source_filename: kaiv-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://kaiv.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: kaiv-ai\naid: kaiv-ai\nurl: https://kaiv.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are controller for our website and marketing; processor for customer data routed through the product.\ndata_categories:\n- category: identifying\n  text: Email address (used for authentication)\n- category: contact\n  text: Name, work email, role, and company (where provided)\n- category: financial\n  text: We do not store card numbers on Kaiva systems.\n- category: device\n  text: IP address for maintaining platform security\n- category: behavioral\n  text: Feature usage and engagement analytics\n\
  - category: communication\n  text: 'Email delivery provider: Sends our service emails'\npurposes:\n- purpose: Service provision\n  text: Relay tool calls between your AI client and the systems you connect\n- purpose: Analytics and improvement\n  text: Understand how the product is used\n- purpose: Communication\n  text: Send important service updates and notifications\nretention:\n- scope: Kaiva Bridge tool-call records\n  period: 90 days\n  text: Kept 90 days, or up to 365 days for a specific complaint or legal claim; deleted with the workspace.\n- scope: IP addresses\n  period: 90 days\n  text: IP addresses 90 days\n- scope: Billing and financial records\n  period: 7 years\n  text: Billing and financial records 7 years\n- scope: Database backups\n  period: 14 days\n  text: Database backups 14 days\nresidency:\n- region: EU\n  text: Our production infrastructure is located in the EU by default.\ntransfers:\n- mechanism: adequacy\n  text: an adequacy decision (including, for UK transfers,\
  \ the UK extension to the EU–US Data Privacy Framework\n    where applicable)\n- mechanism: SCC\n  text: the EU Standard Contractual Clauses 2021/914 where a transfer is EEA-originating\nsubprocessors:\n  url: null\n  text: A current list of sub-processors is available on request to [email protected] .\ndpa:\n  available: null\n  url: null\n  text: Where a specific data-processing agreement applies between us, its terms govern.\ndeletion:\n  route: Email [email protected] to exercise rights, including erasure\n  text: Erasure , request deletion, subject to legal retention obligations and security holds.\nrights:\n- right: Access\n  text: Access , request a copy of personal data we hold about you.\n- right: Erasure\n  text: Erasure , request deletion, subject to legal retention obligations and security holds.\n- right: Rectification\n  text: Rectification , request correction of inaccurate or incomplete data.\n- right: Portability\n  text: Portability , where applicable.\n- right: Object\n\
  \  text: Object , to processing on the basis of legitimate interest or for direct marketing.\nsale_or_sharing:\n  stance: unstated\n  text: We do not sell your personal data, and we do not use customer data to train foundation models.\n"
source_yaml_url: https://artifacts.apis.io/kaiv-ai/privacy/kaiv-ai-privacy-policy.yml
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
summary_line: 25 quoted statements, read from kaiv-ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Infrastructure
- MCP
- Bridge
- Enterprise
- Developer Tools
---
