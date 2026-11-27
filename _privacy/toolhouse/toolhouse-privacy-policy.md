---
api_specs:
- filename: toolhouse-agent-runs-api-openapi.yml
  format: yaml
  label: Toolhouse Agent Runs API
  slug: toolhouse-agent-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolhouse/openapi/toolhouse-agent-runs-api-openapi.yml
- filename: toolhouse-api-keys-api-openapi.yml
  format: yaml
  label: Toolhouse API Keys API
  slug: toolhouse-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolhouse/openapi/toolhouse-api-keys-api-openapi.yml
- filename: toolhouse-backoffice-api-openapi.yml
  format: yaml
  label: Toolhouse Backoffice API
  slug: toolhouse-backoffice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolhouse/openapi/toolhouse-backoffice-api-openapi.yml
- filename: toolhouse-logs-api-openapi.yml
  format: yaml
  label: Toolhouse Logs API
  slug: toolhouse-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolhouse/openapi/toolhouse-logs-api-openapi.yml
- filename: toolhouse-metrics-api-openapi.yml
  format: yaml
  label: Toolhouse Metrics API
  slug: toolhouse-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolhouse/openapi/toolhouse-metrics-api-openapi.yml
- filename: toolhouse-sdk-api-api-openapi.yml
  format: yaml
  label: Toolhouse SDK API
  slug: toolhouse-sdk-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolhouse/openapi/toolhouse-sdk-api-api-openapi.yml
- filename: toolhouse-user-api-api-openapi.yml
  format: yaml
  label: Toolhouse User API
  slug: toolhouse-user-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/toolhouse/openapi/toolhouse-user-api-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: Name and contact information (email address, phone number)
  - category: identifying
    text: Account credentials and authentication data
  - category: financial
    text: Billing and payment information
  - category: professional
    text: Professional information (company name, job title)
  - category: device
    text: IP addresses and device identifiers
  - category: behavioral
    text: Pages visited and features used
  - category: other
    text: Files and documents you store through our platform
  deletion:
    route: Delete your account through your account settings
    text: Delete your account through your account settings
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing, maintaining, and improving services
    text: Providing, maintaining, and improving our Services
  - purpose: Account and transaction processing
    text: Processing transactions and managing your account
  - purpose: Fraud and security
    text: Detecting and preventing fraud, abuse, and security threats
  - purpose: Analytics
    text: Analyzing usage patterns and optimizing platform performance
  - purpose: Marketing newsletters
    text: Sending newsletters and promotional materials (with your consent)
  retention:
  - period: 365 days
    scope: general personal information
    text: We retain your personal information for up to 365 days from the date of collection or your last interaction with our Services
  - period: 30 days
    scope: account deletion
    text: we will delete or anonymize your personal information within 30 days
  rights:
  - right: access and portability
    text: Request access to your personal information
  - right: correction
    text: Correct inaccurate or incomplete personal information
  - right: deletion
    text: Request deletion of your personal information
  - right: processing restriction or objection
    text: Object to or restrict certain processing of your personal information
  - right: withdraw consent
    text: Withdraw consent where processing is based on consent
  - right: unsubscribe
    text: Unsubscribe from marketing communications
  role:
    text: we typically act as a data processor (under GDPR) or service provider (under CCPA), while you act as the data controller or business
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data to third parties for monetary or other valuable consideration.
  subprocessors:
    text: We maintain a list of our subprocessors and will notify you of any changes.
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses approved by relevant authorities
  - mechanism: adequacy
    text: Adequacy decisions by competent data protection authorities
  - mechanism: other
    text: Other legally recognized transfer mechanisms
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Toolhouse
provenance_date: '2026-11-10'
provider_name: Toolhouse
provider_slug: toolhouse
slug: toolhouse-privacy-policy
source_date: '2026-11-10'
source_filename: toolhouse-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://toolhouse.ai/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Toolhouse\naid: toolhouse\nurl: https://toolhouse.ai/en/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we typically act as a data processor (under GDPR) or service provider (under CCPA), while you act as the\n    data controller or business\ndata_categories:\n- category: contact\n  text: Name and contact information (email address, phone number)\n- category: identifying\n  text: Account credentials and authentication data\n- category: financial\n  text: Billing and payment information\n- category: professional\n  text: Professional information (company name, job title)\n- category: device\n\
  \  text: IP addresses and device identifiers\n- category: behavioral\n  text: Pages visited and features used\n- category: other\n  text: Files and documents you store through our platform\npurposes:\n- purpose: Providing, maintaining, and improving services\n  text: Providing, maintaining, and improving our Services\n- purpose: Account and transaction processing\n  text: Processing transactions and managing your account\n- purpose: Fraud and security\n  text: Detecting and preventing fraud, abuse, and security threats\n- purpose: Analytics\n  text: Analyzing usage patterns and optimizing platform performance\n- purpose: Marketing newsletters\n  text: Sending newsletters and promotional materials (with your consent)\nretention:\n- scope: general personal information\n  period: 365 days\n  text: We retain your personal information for up to 365 days from the date of collection or your last interaction\n    with our Services\n- scope: account deletion\n  period: 30 days\n  text: we will\
  \ delete or anonymize your personal information within 30 days\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses approved by relevant authorities\n- mechanism: adequacy\n  text: Adequacy decisions by competent data protection authorities\n- mechanism: other\n  text: Other legally recognized transfer mechanisms\nsubprocessors:\n  url: null\n  text: We maintain a list of our subprocessors and will notify you of any changes.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account through your account settings\n  text: Delete your account through your account settings\nrights:\n- right: access and portability\n  text: Request access to your personal information\n- right: correction\n  text: Correct inaccurate or incomplete personal information\n- right: deletion\n  text: Request deletion of your personal information\n- right: processing restriction or objection\n  text: Object to or restrict certain processing of your personal\
  \ information\n- right: withdraw consent\n  text: Withdraw consent where processing is based on consent\n- right: unsubscribe\n  text: Unsubscribe from marketing communications\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data to third parties for monetary or other valuable consideration.\n"
source_yaml_url: https://artifacts.apis.io/toolhouse/privacy/toolhouse-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from Toolhouse's own page on 2026-11-10.
synthetic: false
tags:
- Agent Infrastructure
- AI Agents
- AI Workers
- Backend-as-a-Service
- MCP
- MCP Discovery
- RAG
- Tools
- Workers API
---
