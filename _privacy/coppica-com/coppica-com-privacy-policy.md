---
api_specs:
- filename: coppica-com-clients-api-openapi.yml
  format: yaml
  label: Coppica Clients API
  slug: coppica-com-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coppica-com/openapi/coppica-com-clients-api-openapi.yml
- filename: coppica-com-deploy-track-api-openapi.yml
  format: yaml
  label: Coppica Deploy & track API
  slug: coppica-com-deploy-track-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coppica-com/openapi/coppica-com-deploy-track-api-openapi.yml
- filename: coppica-com-generation-api-openapi.yml
  format: yaml
  label: Coppica Generation API
  slug: coppica-com-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coppica-com/openapi/coppica-com-generation-api-openapi.yml
- filename: coppica-com-learning-loop-api-openapi.yml
  format: yaml
  label: Coppica Learning loop API
  slug: coppica-com-learning-loop-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coppica-com/openapi/coppica-com-learning-loop-api-openapi.yml
- filename: coppica-com-reference-api-openapi.yml
  format: yaml
  label: Coppica Reference API
  slug: coppica-com-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coppica-com/openapi/coppica-com-reference-api-openapi.yml
- filename: coppica-com-resources-api-openapi.yml
  format: yaml
  label: Coppica Resources API
  slug: coppica-com-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coppica-com/openapi/coppica-com-resources-api-openapi.yml
- filename: coppica-com-webhooks-api-openapi.yml
  format: yaml
  label: Coppica Webhooks API
  slug: coppica-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coppica-com/openapi/coppica-com-webhooks-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: contact
    text: When you create an account, we collect your email address, display name, company name, and the plan you select.
  - category: financial
    text: We receive and store billing metadata such as plan type, subscription status, and transaction history.
  - category: behavioral
    text: We collect usage data including pages visited, features used, bot runs initiated, API request metadata, IP addresses, browser type, and device information.
  - category: communication
    text: CRM records including contact names, email addresses, phone numbers, tags, and lifecycle stage data
  - category: biometric
    text: Meeting transcripts, call recordings, and participant information from connected meeting intelligence services
  deletion:
    route: Email support@coppica.com or delete via Settings; Meta data deletion via Settings → Integrations → Meta Ads → Disconnect
    text: You may request earlier deletion of your data at any time by contacting support@coppica.com .
  dpa:
    available: true
    text: Any paying customer may request a Data Processing Agreement (DPA) by contacting support@coppica.com .
    url: null
  purposes:
  - purpose: Provide the Service
    text: 'To provide the Service: Processing your intake form data through our AI pipeline, generating outputs, and storing your results.'
  - purpose: Manage account
    text: 'To manage your account: Authentication, billing, subscription management, and customer support.'
  - purpose: Improve the Service
    text: 'To improve the Service: Analyzing aggregate, non-personally-identifying usage patterns to improve performance, features, and user experience.'
  - purpose: Security
    text: 'For security: Detecting and preventing fraud, abuse, and security incidents.'
  - purpose: Communications
    text: 'For communications: Sending transactional emails (account confirmations, billing receipts, service updates).'
  residency:
  - region: United States
    text: Your data is primarily processed in the United States.
  - region: United States
    text: Google data is stored in our database in the United States and is encrypted in transit and at rest.
  retention:
  - period: null
    scope: Account data
    text: 'Account data: Retained for the duration of your subscription plus 90 days after cancellation.'
  - period: 12 months
    scope: Usage logs
    text: 'Usage logs: Retained for 12 months, then automatically deleted.'
  - period: typically 7 years
    scope: Billing records
    text: 'Billing records: Retained as required by applicable tax and financial reporting laws (typically 7 years).'
  - period: minimum of 7 years
    scope: Electronic signature records
    text: 'Electronic signature records: Audit trail data, signed document references, and certificates of completion are retained for a minimum of 7 years from the date of execution, regardless of account status.'
  - period: 400 days
    scope: Clarity totals
    text: We store these totals only, never recordings or individual visitor sessions, drop query strings from page addresses, and keep the totals for 400 days
  rights:
  - right: Access
    text: 'Access : request a copy of the personal data we hold about you.'
  - right: Correction
    text: 'Correction : request correction of inaccurate personal data.'
  - right: Deletion
    text: 'Deletion : request deletion of your personal data (right to erasure).'
  - right: Portability
    text: 'Portability : receive your data in a structured, machine-readable format.'
  - right: Objection
    text: 'Objection : object to processing based on legitimate interests.'
  - right: Restriction
    text: 'Restriction : request restriction of processing while a dispute is resolved.'
  - right: Know (CCPA)
    text: 'Know : request disclosure of the categories and specific pieces of personal information we collect, use, and disclose.'
  - right: Opt-out of sale or sharing (CCPA)
    text: 'Opt-out of sale or sharing : Coppica does not sell personal information as defined by the CCPA.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: For transfers from the EEA, UK, or Switzerland, we rely on Standard Contractual Clauses (SCCs) approved by the European Commission, or other lawful transfer mechanisms
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Coppica
provenance_date: '2026-11-09'
provider_name: Coppica
provider_slug: coppica-com
slug: coppica-com-privacy-policy
source_date: '2026-11-09'
source_filename: coppica-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://coppica.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Coppica\naid: coppica-com\nurl: https://coppica.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: When you create an account, we collect your email address, display name, company name, and the plan you\n    select.\n- category: financial\n  text: We receive and store billing metadata such as plan type, subscription status, and transaction history.\n- category: behavioral\n  text: We collect usage data including pages visited, features used, bot runs initiated, API request metadata,\n    IP addresses, browser type, and device information.\n\
  - category: communication\n  text: CRM records including contact names, email addresses, phone numbers, tags, and lifecycle stage data\n- category: biometric\n  text: Meeting transcripts, call recordings, and participant information from connected meeting intelligence services\npurposes:\n- purpose: Provide the Service\n  text: 'To provide the Service: Processing your intake form data through our AI pipeline, generating outputs, and\n    storing your results.'\n- purpose: Manage account\n  text: 'To manage your account: Authentication, billing, subscription management, and customer support.'\n- purpose: Improve the Service\n  text: 'To improve the Service: Analyzing aggregate, non-personally-identifying usage patterns to improve performance,\n    features, and user experience.'\n- purpose: Security\n  text: 'For security: Detecting and preventing fraud, abuse, and security incidents.'\n- purpose: Communications\n  text: 'For communications: Sending transactional emails (account confirmations,\
  \ billing receipts, service updates).'\nretention:\n- scope: Account data\n  period: null\n  text: 'Account data: Retained for the duration of your subscription plus 90 days after cancellation.'\n- scope: Usage logs\n  period: 12 months\n  text: 'Usage logs: Retained for 12 months, then automatically deleted.'\n- scope: Billing records\n  period: typically 7 years\n  text: 'Billing records: Retained as required by applicable tax and financial reporting laws (typically 7 years).'\n- scope: Electronic signature records\n  period: minimum of 7 years\n  text: 'Electronic signature records: Audit trail data, signed document references, and certificates of completion\n    are retained for a minimum of 7 years from the date of execution, regardless of account status.'\n- scope: Clarity totals\n  period: 400 days\n  text: We store these totals only, never recordings or individual visitor sessions, drop query strings from page\n    addresses, and keep the totals for 400 days\nresidency:\n- region:\
  \ United States\n  text: Your data is primarily processed in the United States.\n- region: United States\n  text: Google data is stored in our database in the United States and is encrypted in transit and at rest.\ntransfers:\n- mechanism: SCC\n  text: For transfers from the EEA, UK, or Switzerland, we rely on Standard Contractual Clauses (SCCs) approved\n    by the European Commission, or other lawful transfer mechanisms\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Any paying customer may request a Data Processing Agreement (DPA) by contacting support@coppica.com .\ndeletion:\n  route: Email support@coppica.com or delete via Settings; Meta data deletion via Settings → Integrations → Meta\n    Ads → Disconnect\n  text: You may request earlier deletion of your data at any time by contacting support@coppica.com .\nrights:\n- right: Access\n  text: 'Access : request a copy of the personal data we hold about you.'\n- right: Correction\n  text: 'Correction\
  \ : request correction of inaccurate personal data.'\n- right: Deletion\n  text: 'Deletion : request deletion of your personal data (right to erasure).'\n- right: Portability\n  text: 'Portability : receive your data in a structured, machine-readable format.'\n- right: Objection\n  text: 'Objection : object to processing based on legitimate interests.'\n- right: Restriction\n  text: 'Restriction : request restriction of processing while a dispute is resolved.'\n- right: Know (CCPA)\n  text: 'Know : request disclosure of the categories and specific pieces of personal information we collect, use,\n    and disclose.'\n- right: Opt-out of sale or sharing (CCPA)\n  text: 'Opt-out of sale or sharing : Coppica does not sell personal information as defined by the CCPA.'\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/coppica-com/privacy/coppica-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from Coppica's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketing
- Copywriting
- Generative AI
- Advertising
- Conversion Tracking
- Attribution
- MCP
- AI Agents
---
