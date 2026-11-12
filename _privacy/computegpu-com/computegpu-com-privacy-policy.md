---
api_specs:
- filename: computegpu-com-gpu-api-openapi.yml
  format: yaml
  label: ComputeGpu Gpu API
  slug: computegpu-com-gpu-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computegpu-com/openapi/computegpu-com-gpu-api-openapi.yml
- filename: computegpu-com-signup-api-openapi.yml
  format: yaml
  label: ComputeGpu Signup API
  slug: computegpu-com-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/computegpu-com/openapi/computegpu-com-signup-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account details (name, email address, password)
  - category: financial
    text: Payment information (processed securely via Stripe and Stripe Connect)
  - category: location
    text: IP address and approximate location
  - category: device
    text: Browser type, device type, and operating system
  - category: behavioral
    text: Pages visited, features used, and session duration
  - category: communication
    text: Communications with our support team
  deletion:
    route: Account deletion within 90 days of termination; data export request within 30 days of termination
    text: Account data is deleted within 90 days of termination
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: Provide, operate, and maintain the Service
  - purpose: Process payments and payouts
    text: Process payments and facilitate host payouts via Stripe Connect
  - purpose: Fraud and security
    text: Detect, prevent, and address fraud or security issues
  - purpose: Legal compliance
    text: Comply with legal obligations
  retention:
  - period: 90 days
    scope: Account data
    text: Account data is deleted within 90 days of termination
  - period: 7 years
    scope: Usage and billing records
    text: Usage and billing records may be retained for up to 7 years to comply with tax and accounting regulations
  - period: indefinitely
    scope: Anonymised and aggregated data
    text: Anonymised and aggregated data may be retained indefinitely for analytics
  rights:
  - right: Access
    text: Right of access — request a copy of the personal data we hold about you
  - right: Rectification
    text: Right to rectification — request correction of inaccurate data
  - right: Erasure
    text: Right to erasure — request deletion of your personal data
  - right: Restriction
    text: Right to restrict processing — request that we limit how we use your data
  - right: Portability
    text: Right to data portability — receive your data in a structured, machine-readable format
  - right: Object
    text: Right to object — object to processing based on legitimate interests
  - right: Withdraw consent
    text: Right to withdraw consent — withdraw consent at any time where processing is based on consent
  - right: CCPA opt-out of sale
    text: Right to opt-out — opt out of the sale of personal information (we do not sell personal data)
  role:
    text: 'Data Controller: Tyga.Cloud Ltd, Ground Floor, Unit 2 Mallard Court, Mallard Way, Crewe Business Park, Crewe, Cheshire, CW1 6ZQ, United Kingdom.'
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
name: ComputeGpu
provenance_date: '2026-11-09'
provider_name: ComputeGpu
provider_slug: computegpu-com
slug: computegpu-com-privacy-policy
source_date: '2026-11-09'
source_filename: computegpu-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://computegpu.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ComputeGpu\naid: computegpu-com\nurl: https://computegpu.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Data Controller: Tyga.Cloud Ltd, Ground Floor, Unit 2 Mallard Court, Mallard Way, Crewe Business Park,\n    Crewe, Cheshire, CW1 6ZQ, United Kingdom.'\ndata_categories:\n- category: identifying\n  text: Account details (name, email address, password)\n- category: financial\n  text: Payment information (processed securely via Stripe and Stripe Connect)\n- category: location\n  text: IP address and approximate location\n- category: device\n  text: Browser type, device type, and\
  \ operating system\n- category: behavioral\n  text: Pages visited, features used, and session duration\n- category: communication\n  text: Communications with our support team\npurposes:\n- purpose: Provide and operate the Service\n  text: Provide, operate, and maintain the Service\n- purpose: Process payments and payouts\n  text: Process payments and facilitate host payouts via Stripe Connect\n- purpose: Fraud and security\n  text: Detect, prevent, and address fraud or security issues\n- purpose: Legal compliance\n  text: Comply with legal obligations\nretention:\n- scope: Account data\n  period: 90 days\n  text: Account data is deleted within 90 days of termination\n- scope: Usage and billing records\n  period: 7 years\n  text: Usage and billing records may be retained for up to 7 years to comply with tax and accounting regulations\n- scope: Anonymised and aggregated data\n  period: indefinitely\n  text: Anonymised and aggregated data may be retained indefinitely for analytics\nresidency:\
  \ []\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) approved by the UK Information Commissioner's Office\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion within 90 days of termination; data export request within 30 days of termination\n  text: Account data is deleted within 90 days of termination\nrights:\n- right: Access\n  text: Right of access — request a copy of the personal data we hold about you\n- right: Rectification\n  text: Right to rectification — request correction of inaccurate data\n- right: Erasure\n  text: Right to erasure — request deletion of your personal data\n- right: Restriction\n  text: Right to restrict processing — request that we limit how we use your data\n- right: Portability\n  text: Right to data portability — receive your data in a structured, machine-readable format\n- right: Object\n  text: Right to object — object to processing based on legitimate\
  \ interests\n- right: Withdraw consent\n  text: Right to withdraw consent — withdraw consent at any time where processing is based on consent\n- right: CCPA opt-out of sale\n  text: Right to opt-out — opt out of the sale of personal information (we do not sell personal data)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/computegpu-com/privacy/computegpu-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from ComputeGpu's own page on 2026-11-09.
synthetic: false
tags:
- Company
- GPU Cloud
- AI Infrastructure
- Compute
- Machine Learning
- Inference
- LLM
- MCP
- CLI
---
