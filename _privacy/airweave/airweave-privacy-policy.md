---
api_specs:
- filename: airweave-collections-api-openapi.yml
  format: yaml
  label: Airweave Collections API
  slug: airweave-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airweave/openapi/airweave-collections-api-openapi.yml
- filename: airweave-collections-search-api-openapi.yml
  format: yaml
  label: Airweave collections > search API
  slug: airweave-collections-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airweave/openapi/airweave-collections-search-api-openapi.yml
- filename: airweave-source-connections-api-openapi.yml
  format: yaml
  label: Airweave Source Connections API
  slug: airweave-source-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airweave/openapi/airweave-source-connections-api-openapi.yml
- filename: airweave-sources-api-openapi.yml
  format: yaml
  label: Airweave Sources API
  slug: airweave-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airweave/openapi/airweave-sources-api-openapi.yml
- filename: airweave-webhooks-api-openapi.yml
  format: yaml
  label: Airweave Webhooks API
  slug: airweave-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airweave/openapi/airweave-webhooks-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information (e.g., name, email, organization, role).
  - category: financial
    text: Billing information if you purchase paid Services.
  - category: behavioral
    text: Usage and diagnostics (e.g., device, browser, IP address, timestamps, page views, API calls, performance metrics).
  - category: communication
    text: Communications (e.g., support inquiries, feedback).
  - category: other
    text: Data from integrated sources you connect via OAuth2, API keys, database credentials, or file connectors (e.g., documents, tickets, issues, messages, records, metadata).
  deletion:
    route: Contact hello@airweave.ai
    text: 'Requests: contact hello@airweave.ai .'
  dpa:
    available: true
    text: We make a data processing addendum (DPA) available on request for customers who require GDPR- or similar-compliant processor terms
    url: null
  purposes:
  - purpose: Provide and secure Services
    text: To provide, operate, maintain, and secure the Services.
  - purpose: Sync and index Customer Data
    text: To sync, transform, and index Customer Data per your configuration and instructions.
  - purpose: Improve features
    text: To improve and develop features, performance, and usability.
  - purpose: Marketing communications
    text: and—with consent or as permitted—product and marketing communications.
  - purpose: Legal compliance
    text: To comply with law, enforce terms, and protect rights and safety.
  residency:
  - region: United States and Netherlands
    text: We operate in the U.S. and the Netherlands and may process data in these and other jurisdictions.
  retention:
  - period: null
    scope: Personal data generally
    text: We retain personal data for as long as necessary to provide the Services, comply with legal obligations, resolve disputes, and enforce our agreements.
  - period: null
    scope: Processor data
    text: For processor data, retention follows your configuration and instructions, including deletion upon termination or your request, subject to legal requirements.
  rights:
  - right: access
    text: you may have rights to access, correct, delete, restrict, object, or port your personal data
  - right: withdraw consent
    text: and to withdraw consent where processing is based on consent
  - right: complaint to supervisory authority
    text: 'EEA/UK: You may also lodge a complaint with your local supervisory authority.'
  - right: CCPA opt out of sales/sharing
    text: 'California: You may have rights under the CCPA/CPRA, including to know, delete, correct, and opt out of certain “sales”/“sharing”'
  role:
    text: 'Customer as Controller: For content and data you connect to the Services (e.g., data pulled from your third-party apps, databases, or file stores), you are typically the “data controller” (or equivalent) and Airweave acts as a “data processor” (or equivalent)'
    value: both
  sale_or_sharing:
    stance: unstated
    text: we do not sell personal information in the conventional sense
  subprocessors:
    text: A list of material subprocessors is available upon request and will be updated as our service evolves.
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we use appropriate safeguards for cross-border transfers (e.g., EU Standard Contractual Clauses).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Airweave
provenance_date: '2026-11-09'
provider_name: Airweave
provider_slug: airweave
slug: airweave-privacy-policy
source_date: '2026-11-09'
source_filename: airweave-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://airweave.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Airweave\naid: airweave\nurl: https://airweave.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Customer as Controller: For content and data you connect to the Services (e.g., data pulled from your third-party\n    apps, databases, or file stores), you are typically the “data controller” (or equivalent) and Airweave acts\n    as a “data processor” (or equivalent)'\ndata_categories:\n- category: identifying\n  text: Account information (e.g., name, email, organization, role).\n- category: financial\n  text: Billing information if you purchase paid Services.\n- category: behavioral\n\
  \  text: Usage and diagnostics (e.g., device, browser, IP address, timestamps, page views, API calls, performance\n    metrics).\n- category: communication\n  text: Communications (e.g., support inquiries, feedback).\n- category: other\n  text: Data from integrated sources you connect via OAuth2, API keys, database credentials, or file connectors\n    (e.g., documents, tickets, issues, messages, records, metadata).\npurposes:\n- purpose: Provide and secure Services\n  text: To provide, operate, maintain, and secure the Services.\n- purpose: Sync and index Customer Data\n  text: To sync, transform, and index Customer Data per your configuration and instructions.\n- purpose: Improve features\n  text: To improve and develop features, performance, and usability.\n- purpose: Marketing communications\n  text: and—with consent or as permitted—product and marketing communications.\n- purpose: Legal compliance\n  text: To comply with law, enforce terms, and protect rights and safety.\nretention:\n\
  - scope: Personal data generally\n  period: null\n  text: We retain personal data for as long as necessary to provide the Services, comply with legal obligations,\n    resolve disputes, and enforce our agreements.\n- scope: Processor data\n  period: null\n  text: For processor data, retention follows your configuration and instructions, including deletion upon termination\n    or your request, subject to legal requirements.\nresidency:\n- region: United States and Netherlands\n  text: We operate in the U.S. and the Netherlands and may process data in these and other jurisdictions.\ntransfers:\n- mechanism: SCC\n  text: Where required, we use appropriate safeguards for cross-border transfers (e.g., EU Standard Contractual\n    Clauses).\nsubprocessors:\n  url: null\n  text: A list of material subprocessors is available upon request and will be updated as our service evolves.\ndpa:\n  available: true\n  url: null\n  text: We make a data processing addendum (DPA) available on request for\
  \ customers who require GDPR- or similar-compliant\n    processor terms\ndeletion:\n  route: Contact hello@airweave.ai\n  text: 'Requests: contact hello@airweave.ai .'\nrights:\n- right: access\n  text: you may have rights to access, correct, delete, restrict, object, or port your personal data\n- right: withdraw consent\n  text: and to withdraw consent where processing is based on consent\n- right: complaint to supervisory authority\n  text: 'EEA/UK: You may also lodge a complaint with your local supervisory authority.'\n- right: CCPA opt out of sales/sharing\n  text: 'California: You may have rights under the CCPA/CPRA, including to know, delete, correct, and opt out of\n    certain “sales”/“sharing”'\nsale_or_sharing:\n  stance: unstated\n  text: we do not sell personal information in the conventional sense\n"
source_yaml_url: https://artifacts.apis.io/airweave/privacy/airweave-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Airweave's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Search
- RAG
- Retrieval
- Agents
- MCP
- Vector Search
- Data Integration
- Context
---
