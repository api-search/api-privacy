---
api_specs:
- filename: agenticmemory-ai-openapi-generated.yml
  format: yaml
  label: agenticmemory-ai API
  slug: agenticmemory-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agenticmemory-ai/openapi/_ae-authored/agenticmemory-ai-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account details (name, email address, password)
  - category: financial
    text: Payment information (processed securely via Stripe)
  - category: location
    text: IP address and approximate location
  - category: device
    text: Browser type, device type, and operating system
  - category: behavioral
    text: Pages visited, features used, and session duration
  - category: communication
    text: Communications with our support team
  deletion:
    route: Request deletion via Data Protection Officer or account termination
    text: Right to erasure — request deletion of your personal data ("right to be forgotten")
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: Provide, operate, and maintain the Service
  - purpose: Billing
    text: Process transactions and send billing notifications
  - purpose: Fraud and security
    text: Detect, prevent, and address fraud or security issues
  - purpose: Analytics
    text: Analyse usage to improve the Service
  retention:
  - period: 24-hour auto-deletion
    scope: Memory data on Starter plan
    text: 'Starter plan: 24-hour auto-deletion'
  - period: 45 days
    scope: Usage counters
    text: Usage counters are retained for 45 days and auto-expire
  - period: 90 days
    scope: Account data after termination
    text: Account data is deleted within 90 days of termination
  - period: indefinitely
    scope: Anonymised and aggregated data
    text: Anonymised and aggregated data may be retained indefinitely for analytics
  rights:
  - right: Access
    text: Right of access — request a copy of the personal data we hold about you
  - right: Rectification
    text: Right to rectification — request correction of inaccurate data
  - right: Erasure
    text: Right to erasure — request deletion of your personal data ("right to be forgotten")
  - right: Portability
    text: Right to data portability — receive your data in a structured, machine-readable format (use our space export API)
  - right: Object
    text: Right to object — object to processing based on legitimate interests
  - right: Opt-out of sale
    text: Right to opt-out — opt out of the sale of personal information (we do not sell personal data)
  role:
    text: Tyga.Cloud Ltd (company number 14643275), registered in England and Wales ("we", "us", "our"), collects, uses, and protects personal data when you use the Agentic Memory platform
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) approved by the UK Information Commissioner's Office
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: agenticmemory-ai
provenance_date: '2026-11-09'
provider_name: agenticmemory-ai
provider_slug: agenticmemory-ai
slug: agenticmemory-ai-privacy-policy
source_date: '2026-11-09'
source_filename: agenticmemory-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agenticmemory.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: agenticmemory-ai\naid: agenticmemory-ai\nurl: https://agenticmemory.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Tyga.Cloud Ltd (company number 14643275), registered in England and Wales (\"we\", \"us\", \"our\"), collects,\n    uses, and protects personal data when you use the Agentic Memory platform\ndata_categories:\n- category: identifying\n  text: Account details (name, email address, password)\n- category: financial\n  text: Payment information (processed securely via Stripe)\n- category: location\n  text: IP address and approximate location\n- category: device\n  text:\
  \ Browser type, device type, and operating system\n- category: behavioral\n  text: Pages visited, features used, and session duration\n- category: communication\n  text: Communications with our support team\npurposes:\n- purpose: Provide and operate the Service\n  text: Provide, operate, and maintain the Service\n- purpose: Billing\n  text: Process transactions and send billing notifications\n- purpose: Fraud and security\n  text: Detect, prevent, and address fraud or security issues\n- purpose: Analytics\n  text: Analyse usage to improve the Service\nretention:\n- scope: Memory data on Starter plan\n  period: 24-hour auto-deletion\n  text: 'Starter plan: 24-hour auto-deletion'\n- scope: Usage counters\n  period: 45 days\n  text: Usage counters are retained for 45 days and auto-expire\n- scope: Account data after termination\n  period: 90 days\n  text: Account data is deleted within 90 days of termination\n- scope: Anonymised and aggregated data\n  period: indefinitely\n  text: Anonymised\
  \ and aggregated data may be retained indefinitely for analytics\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) approved by the UK Information Commissioner's Office\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion via Data Protection Officer or account termination\n  text: Right to erasure — request deletion of your personal data (\"right to be forgotten\")\nrights:\n- right: Access\n  text: Right of access — request a copy of the personal data we hold about you\n- right: Rectification\n  text: Right to rectification — request correction of inaccurate data\n- right: Erasure\n  text: Right to erasure — request deletion of your personal data (\"right to be forgotten\")\n- right: Portability\n  text: Right to data portability — receive your data in a structured, machine-readable format (use our space export\n    API)\n- right: Object\n  text: Right to object — object\
  \ to processing based on legitimate interests\n- right: Opt-out of sale\n  text: Right to opt-out — opt out of the sale of personal information (we do not sell personal data)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/agenticmemory-ai/privacy/agenticmemory-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from agenticmemory-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Memory
- Agents
- LLM
---
