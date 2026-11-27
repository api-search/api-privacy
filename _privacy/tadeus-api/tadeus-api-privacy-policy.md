---
api_specs:
- filename: tadeus-api-attempts-api-openapi.yml
  format: yaml
  label: Tadeus API Attempts API
  slug: tadeus-api-attempts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tadeus-api/openapi/tadeus-api-attempts-api-openapi.yml
- filename: tadeus-api-billing-api-openapi.yml
  format: yaml
  label: Tadeus API Billing API
  slug: tadeus-api-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tadeus-api/openapi/tadeus-api-billing-api-openapi.yml
- filename: tadeus-api-campaigns-api-openapi.yml
  format: yaml
  label: Tadeus API Campaigns API
  slug: tadeus-api-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tadeus-api/openapi/tadeus-api-campaigns-api-openapi.yml
- filename: tadeus-api-insights-api-openapi.yml
  format: yaml
  label: Tadeus API Insights API
  slug: tadeus-api-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tadeus-api/openapi/tadeus-api-insights-api-openapi.yml
- filename: tadeus-api-organisation-api-openapi.yml
  format: yaml
  label: Tadeus API Organisation API
  slug: tadeus-api-organisation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tadeus-api/openapi/tadeus-api-organisation-api-openapi.yml
- filename: tadeus-api-results-api-openapi.yml
  format: yaml
  label: Tadeus API Results API
  slug: tadeus-api-results-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tadeus-api/openapi/tadeus-api-results-api-openapi.yml
- filename: tadeus-api-sessions-api-openapi.yml
  format: yaml
  label: Tadeus API Sessions API
  slug: tadeus-api-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tadeus-api/openapi/tadeus-api-sessions-api-openapi.yml
- filename: tadeus-api-templates-api-openapi.yml
  format: yaml
  label: Tadeus API Templates API
  slug: tadeus-api-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tadeus-api/openapi/tadeus-api-templates-api-openapi.yml
- filename: tadeus-api-transcripts-api-openapi.yml
  format: yaml
  label: Tadeus API Transcripts API
  slug: tadeus-api-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tadeus-api/openapi/tadeus-api-transcripts-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Basic Profile Information: Your name, email address, profile picture, and language code preference.'
  - category: financial
    text: 'Stripe: Securely processes payment and billing information.'
  - category: communication
    text: Delivers system emails, notifications, and verification codes.
  deletion:
    route: null
    text: Once the transcript is generated, the raw audio file is permanently discarded.
  dpa:
    available: null
    text: We maintain strict data processing agreements (DPAs) with all third-party vendors to ensure GDPR compliance.
    url: null
  purposes:
  - purpose: Authentication
    text: 'Authentication: To create and manage your account securely without requiring a separate password.'
  - purpose: Service notifications
    text: 'Communication: To send you service-related notifications and survey results (using your email address).'
  - purpose: Personalization
    text: 'Personalization: To display your name and profile picture within the application interface.'
  residency:
  - region: United States
    text: Your data may be processed in countries outside the UK and EEA, specifically the United States.
  retention:
  - period: null
    scope: Audio recordings
    text: WE DO NOT RETAIN AUDIO RECORDINGS. Audio is processed instantaneously for the purpose of generating a transcript and AI response.
  rights:
  - right: Access
    text: 'The right to access: You have the right to request copies of your personal data.'
  - right: Rectification
    text: 'The right to rectification: You have the right to request that we correct any information you believe is inaccurate.'
  - right: Erasure
    text: 'The right to erasure: You have the right to request that we erase your personal data ("Right to be Forgotten").'
  - right: Restrict processing
    text: 'The right to restrict processing: You have the right to request that we restrict the processing of your personal data.'
  role:
    text: Tadeus serves as the Data Controller for the personal information you provide when creating an account, billing information, and usage metadata.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your Google user data to third parties.
  subprocessors:
    text: 'OpenAI: Processes anonymized audio and text to generate AI responses and transcripts.'
    url: null
  transfers:
  - mechanism: SCC
    text: We ensure such transfers are protected by appropriate safeguards, including Standard Contractual Clauses (SCCs) approved by the European Commission and the UK IPO.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Tadeus API
provenance_date: '2026-11-10'
provider_name: Tadeus API
provider_slug: tadeus-api
slug: tadeus-api-privacy-policy
source_date: '2026-11-10'
source_filename: tadeus-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tadeus.net/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Tadeus API\naid: tadeus-api\nurl: https://tadeus.net/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Tadeus serves as the Data Controller for the personal information you provide when creating an account,\n    billing information, and usage metadata.\ndata_categories:\n- category: identifying\n  text: 'Basic Profile Information: Your name, email address, profile picture, and language code preference.'\n- category: financial\n  text: 'Stripe: Securely processes payment and billing information.'\n- category: communication\n  text: Delivers system emails, notifications, and verification codes.\n\
  purposes:\n- purpose: Authentication\n  text: 'Authentication: To create and manage your account securely without requiring a separate password.'\n- purpose: Service notifications\n  text: 'Communication: To send you service-related notifications and survey results (using your email address).'\n- purpose: Personalization\n  text: 'Personalization: To display your name and profile picture within the application interface.'\nretention:\n- scope: Audio recordings\n  period: null\n  text: WE DO NOT RETAIN AUDIO RECORDINGS. Audio is processed instantaneously for the purpose of generating a transcript\n    and AI response.\nresidency:\n- region: United States\n  text: Your data may be processed in countries outside the UK and EEA, specifically the United States.\ntransfers:\n- mechanism: SCC\n  text: We ensure such transfers are protected by appropriate safeguards, including Standard Contractual Clauses\n    (SCCs) approved by the European Commission and the UK IPO.\nsubprocessors:\n  url: null\n\
  \  text: 'OpenAI: Processes anonymized audio and text to generate AI responses and transcripts.'\ndpa:\n  available: null\n  url: null\n  text: We maintain strict data processing agreements (DPAs) with all third-party vendors to ensure GDPR compliance.\ndeletion:\n  route: null\n  text: Once the transcript is generated, the raw audio file is permanently discarded.\nrights:\n- right: Access\n  text: 'The right to access: You have the right to request copies of your personal data.'\n- right: Rectification\n  text: 'The right to rectification: You have the right to request that we correct any information you believe is\n    inaccurate.'\n- right: Erasure\n  text: 'The right to erasure: You have the right to request that we erase your personal data (\"Right to be Forgotten\").'\n- right: Restrict processing\n  text: 'The right to restrict processing: You have the right to request that we restrict the processing of your\n    personal data.'\nsale_or_sharing:\n  stance: prohibited\n  text: We\
  \ do not sell your Google user data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/tadeus-api/privacy/tadeus-api-privacy-policy.yml
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
- sale_or_sharing
summary_line: 18 quoted statements, read from Tadeus API's own page on 2026-11-10.
synthetic: false
tags:
- Voice AI
- Research
- Interviews
- Workforce
- Human Resources
- Conversational AI
- Employee Experience
- AI Agents
- MCP
- EU AI Act
- Compliance
- Employee Engagement
---
