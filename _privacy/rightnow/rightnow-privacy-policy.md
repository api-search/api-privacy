---
api_specs:
- filename: rightnow-audio-api-openapi.yml
  format: yaml
  label: RightNow AI Audio API
  slug: rightnow-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-audio-api-openapi.yml
- filename: rightnow-embeddings-api-openapi.yml
  format: yaml
  label: RightNow AI Embeddings API
  slug: rightnow-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-embeddings-api-openapi.yml
- filename: rightnow-images-api-openapi.yml
  format: yaml
  label: RightNow AI Images API
  slug: rightnow-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-images-api-openapi.yml
- filename: rightnow-models-api-openapi.yml
  format: yaml
  label: RightNow AI Models API
  slug: rightnow-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-models-api-openapi.yml
- filename: rightnow-rerank-api-openapi.yml
  format: yaml
  label: RightNow AI Rerank API
  slug: rightnow-rerank-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-rerank-api-openapi.yml
- filename: rightnow-responses-api-openapi.yml
  format: yaml
  label: RightNow AI Responses API
  slug: rightnow-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-responses-api-openapi.yml
- filename: rightnow-chat-completions-api-openapi.yml
  format: yaml
  label: RightNow AI Chat Completions API
  slug: rightnow-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-chat-completions-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personal Information includes your email address, name, company legal name, job title, billing details, typed signature, IP address, user agent
  - category: behavioral
    text: Site usage patterns and interaction data
  - category: device
    text: Device information, browser type, and operating system
  - category: communication
    text: Messages you send in-product assistant features, and their replies
  - category: financial
    text: 'Billing and plan data: credit purchases, balances and expiry dates'
  deletion:
    route: Self-service deletion in Settings, or emailed request
    text: You can delete your account yourself in Settings, Account. That deletion is immediate and permanent.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: To provide the Service, including the hosted Model APIs and coding plans, and for performance of the enterprise license contract
  - purpose: Improve product and security
    text: To improve our product, ensure security, prevent fraud, and support our legitimate interest in enforcing the enterprise license terms
  - purpose: Marketing communications
    text: 'Consent: For marketing communications and optional features'
  residency:
  - region: United States
    text: Hosted Model APIs inference is served from GPU hardware located in the United States.
  - region: EU
    text: A dedicated model endpoint can run in a region you select, including EU regions
  retention:
  - period: 2 years
    scope: Usage analytics
    text: 'Usage analytics: 2 years'
  - period: 90 days
    scope: Error logs
    text: 'Error logs: 90 days'
  - period: 90 days
    scope: Backups
    text: Automated backups retained for 90 days
  - period: within 30 days of an emailed request
    scope: Deleted accounts
    text: Deleted at once when you delete your account yourself, or within 30 days of an emailed request
  rights:
  - right: Access
    text: Access your personal data
  - right: Correct
    text: Correct inaccurate data
  - right: Deletion
    text: Request deletion of your data
  - right: Portability
    text: Export your data in a portable format (JSON)
  - right: Restrict processing
    text: Restrict processing of your data
  - right: Object
    text: Object to processing of your data
  role:
    text: RightNow AI, Inc., 131 Continental Dr, Newark, DE 19713, United States (the “Company”)
    value: controller
  sale_or_sharing:
    stance: conditional
    text: we do not sell Personal Information for monetary consideration and we do not share Personal Information for cross-context behavioral advertising.
  subprocessors:
    text: 'We use the following third-party services to operate our platform: Supabase Purpose: Database, authentication'
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) with all vendors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: RightNow AI
provenance_date: '2026-11-10'
provider_name: RightNow AI
provider_slug: rightnow
slug: rightnow-privacy-policy
source_date: '2026-11-10'
source_filename: rightnow-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://runinfra.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: RightNow AI\naid: rightnow\nurl: https://runinfra.ai/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: RightNow AI, Inc., 131 Continental Dr, Newark, DE 19713, United States (the “Company”)\ndata_categories:\n- category: identifying\n  text: Personal Information includes your email address, name, company legal name, job title, billing details,\n    typed signature, IP address, user agent\n- category: behavioral\n  text: Site usage patterns and interaction data\n- category: device\n  text: Device information, browser type, and operating system\n- category: communication\n  text:\
  \ Messages you send in-product assistant features, and their replies\n- category: financial\n  text: 'Billing and plan data: credit purchases, balances and expiry dates'\npurposes:\n- purpose: Provide the Service\n  text: To provide the Service, including the hosted Model APIs and coding plans, and for performance of the enterprise\n    license contract\n- purpose: Improve product and security\n  text: To improve our product, ensure security, prevent fraud, and support our legitimate interest in enforcing\n    the enterprise license terms\n- purpose: Marketing communications\n  text: 'Consent: For marketing communications and optional features'\nretention:\n- scope: Usage analytics\n  period: 2 years\n  text: 'Usage analytics: 2 years'\n- scope: Error logs\n  period: 90 days\n  text: 'Error logs: 90 days'\n- scope: Backups\n  period: 90 days\n  text: Automated backups retained for 90 days\n- scope: Deleted accounts\n  period: within 30 days of an emailed request\n  text: Deleted at once\
  \ when you delete your account yourself, or within 30 days of an emailed request\nresidency:\n- region: United States\n  text: Hosted Model APIs inference is served from GPU hardware located in the United States.\n- region: EU\n  text: A dedicated model endpoint can run in a region you select, including EU regions\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) with all vendors\nsubprocessors:\n  url: null\n  text: 'We use the following third-party services to operate our platform: Supabase Purpose: Database, authentication'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Self-service deletion in Settings, or emailed request\n  text: You can delete your account yourself in Settings, Account. That deletion is immediate and permanent.\nrights:\n- right: Access\n  text: Access your personal data\n- right: Correct\n  text: Correct inaccurate data\n- right: Deletion\n  text: Request deletion of your data\n- right: Portability\n  text: Export\
  \ your data in a portable format (JSON)\n- right: Restrict processing\n  text: Restrict processing of your data\n- right: Object\n  text: Object to processing of your data\nsale_or_sharing:\n  stance: conditional\n  text: we do not sell Personal Information for monetary consideration and we do not share Personal Information\n    for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/rightnow/privacy/rightnow-privacy-policy.yml
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
summary_line: 25 quoted statements, read from RightNow AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Inference
- GPU
- Model Deployment
- Serverless
- OpenAI-Compatible
- Embeddings
- MLOps
---
