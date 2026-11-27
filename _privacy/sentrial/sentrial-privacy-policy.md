---
api_specs:
- filename: sentrial-events-api-openapi.yml
  format: yaml
  label: Sentrial Events API
  slug: sentrial-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentrial/openapi/sentrial-events-api-openapi.yml
- filename: sentrial-sessions-api-openapi.yml
  format: yaml
  label: Sentrial Sessions API
  slug: sentrial-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sentrial/openapi/sentrial-sessions-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Name, email address, password, and organization details when you register'
  - category: financial
    text: 'Payment Information: Billing address and payment method details (processed securely by our payment provider)'
  - category: device
    text: 'Device Information: Browser type, operating system, and device identifiers'
  - category: location
    text: 'Log Data: IP address, access times, and referring URLs'
  - category: behavioral
    text: 'Usage Data: Pages visited, features used, and interactions with the Service'
  - category: other
    text: 'Trace Data: Logs, metrics, and traces from your AI agents that you send to our platform'
  - category: other
    text: 'Code Snippets: Code samples provided for analysis and fix generation'
  deletion:
    route: Contact the provider
    text: You can request deletion of your data at any time by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve the Service
    text: Provide, maintain, and improve the Service
  - purpose: Process transactions
    text: Process transactions and send related information
  - purpose: Security and technical issues
    text: Detect, prevent, and address technical issues and security threats
  - purpose: AI model improvement
    text: Generate anonymized, aggregated insights to improve our AI models
  retention:
  - period: null
    scope: Account and service data
    text: We retain your information for as long as your account is active or as needed to provide the Service.
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal data we hold about you'
  - right: Correction
    text: 'Correction: Request correction of inaccurate or incomplete data'
  - right: Deletion
    text: 'Deletion: Request deletion of your personal data'
  - right: Portability
    text: 'Portability: Request transfer of your data to another service'
  - right: Objection
    text: 'Objection: Object to certain processing of your data'
  - right: Withdrawal
    text: 'Withdrawal: Withdraw consent where processing is based on consent'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses approved by the European Commission, to protect your data during such transfers
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Sentrial
provenance_date: '2026-11-10'
provider_name: Sentrial
provider_slug: sentrial
slug: sentrial-privacy-policy
source_date: '2026-11-10'
source_filename: sentrial-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.sentrial.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Sentrial\naid: sentrial\nurl: https://www.sentrial.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Information: Name, email address, password, and organization details when you register'\n- category: financial\n  text: 'Payment Information: Billing address and payment method details (processed securely by our payment provider)'\n- category: device\n  text: 'Device Information: Browser type, operating system, and device identifiers'\n- category: location\n  text: 'Log Data: IP address, access times, and referring URLs'\n\
  - category: behavioral\n  text: 'Usage Data: Pages visited, features used, and interactions with the Service'\n- category: other\n  text: 'Trace Data: Logs, metrics, and traces from your AI agents that you send to our platform'\n- category: other\n  text: 'Code Snippets: Code samples provided for analysis and fix generation'\npurposes:\n- purpose: Provide and improve the Service\n  text: Provide, maintain, and improve the Service\n- purpose: Process transactions\n  text: Process transactions and send related information\n- purpose: Security and technical issues\n  text: Detect, prevent, and address technical issues and security threats\n- purpose: AI model improvement\n  text: Generate anonymized, aggregated insights to improve our AI models\nretention:\n- scope: Account and service data\n  period: null\n  text: We retain your information for as long as your account is active or as needed to provide the Service.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual\
  \ Clauses approved by the European Commission, to protect your data during such transfers\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact the provider\n  text: You can request deletion of your data at any time by contacting us.\nrights:\n- right: Access\n  text: 'Access: Request a copy of the personal data we hold about you'\n- right: Correction\n  text: 'Correction: Request correction of inaccurate or incomplete data'\n- right: Deletion\n  text: 'Deletion: Request deletion of your personal data'\n- right: Portability\n  text: 'Portability: Request transfer of your data to another service'\n- right: Objection\n  text: 'Objection: Object to certain processing of your data'\n- right: Withdrawal\n  text: 'Withdrawal: Withdraw consent where processing is based on consent'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/sentrial/privacy/sentrial-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Sentrial's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Agents
- Observability
- Monitoring
- LLM
- Developer Tools
- Tracing
---
