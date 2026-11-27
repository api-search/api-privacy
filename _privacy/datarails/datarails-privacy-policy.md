---
api_specs:
- filename: datarails-health-api-openapi.yml
  format: yaml
  label: Datarails Health API
  slug: datarails-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datarails/openapi/datarails-health-api-openapi.yml
- filename: datarails-ready-api-openapi.yml
  format: yaml
  label: Datarails Ready API
  slug: datarails-ready-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datarails/openapi/datarails-ready-api-openapi.yml
- filename: datarails-well-known-api-openapi.yml
  format: yaml
  label: Datarails .well Known API
  slug: datarails-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datarails/openapi/datarails-well-known-api-openapi.yml
- filename: datarails-oauth-api-openapi.yml
  format: yaml
  label: Datarails OAUTH API
  slug: datarails-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/datarails/openapi/datarails-oauth-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: This may include name, email address, company name, login credentials, contact information, usage information and device and browser information.
  - category: contact
    text: This may include contact details, professional information, and information relating to interactions with our marketing materials or services
  - category: financial
    text: If you purchase subscriptions to the Service, we may collect billing and payment information.
  - category: device
    text: When you access or use the Website or the Service, our servers may automatically record certain technical information, including IP address, browser type, device information, and usage data.
  - category: behavioral
    text: These tools may collect information such as pages visited, referring websites, and general usage statistics.
  deletion:
    route: compliance@datarails.com
    text: 'Requests regarding Personal Information may be submitted to: compliance@datarails.com .'
  dpa:
    available: true
    text: in accordance with the applicable Data Processing Agreement
    url: null
  purposes:
  - purpose: Provision of service
    text: To operate, maintain, and provide the Service, including enabling access to the platform, delivering requested features, and improving the functionality and performance of the Service.
  - purpose: Customer support
    text: To respond to support requests, troubleshoot issues, and communicate with users regarding their use of the Service.
  - purpose: Marketing communications
    text: We may send marketing communications regarding our services, events, webinars, or updates that may be of interest to you.
  - purpose: Analytics and service improvement
    text: To analyze usage patterns, conduct research, and improve the functionality, performance, and security of our products and services.
  - purpose: Artificial intelligence functionality
    text: we may process inputs, prompts, files, or other data submitted by users in order to generate automated outputs such as analyses, insights, or recommendations.
  residency:
  - region: Israel and United States
    text: Personal Information may be transferred to and processed in countries where Datarails or its service providers operate, including, without limitation, Israel and the United States.
  retention:
  - period: null
    scope: Customer Content
    text: Customer Content is retained for the duration of the customer subscription and in accordance with the Terms of Service or customer instructions.
  - period: indefinitely
    scope: Anonymized or aggregated information
    text: We may retain anonymized or aggregated information indefinitely for analytics and product improvement.
  rights:
  - right: access
    text: access their Personal Information
  - right: correction
    text: correct inaccurate information
  - right: deletion
    text: request deletion of their Personal Information
  - right: restriction or objection
    text: restrict or object to certain processing activities
  - right: portability
    text: request data portability
  role:
    text: Where Datarails processes Personal Information, it does so on behalf of the customer and in accordance with the applicable Data Processing Agreement .
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Datarails does not sell Personal Information.
  subprocessors:
    text: Sub Processors
    url: null
  transfers:
  - mechanism: SCC
    text: Datarails implements appropriate safeguards for international data transfers, including the use of Standard Contractual Clauses approved by the European Commission, the UK Information Commissioner’s Office, or other applicable mechanisms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Datarails
provenance_date: '2026-11-09'
provider_name: Datarails
provider_slug: datarails
slug: datarails-privacy-policy
source_date: '2026-11-09'
source_filename: datarails-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.datarails.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Datarails\naid: datarails\nurl: https://www.datarails.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Where Datarails processes Personal Information, it does so on behalf of the customer and in accordance with\n    the applicable Data Processing Agreement .\ndata_categories:\n- category: identifying\n  text: This may include name, email address, company name, login credentials, contact information, usage information\n    and device and browser information.\n- category: contact\n  text: This may include contact details, professional information, and information relating to interactions\
  \ with\n    our marketing materials or services\n- category: financial\n  text: If you purchase subscriptions to the Service, we may collect billing and payment information.\n- category: device\n  text: When you access or use the Website or the Service, our servers may automatically record certain technical\n    information, including IP address, browser type, device information, and usage data.\n- category: behavioral\n  text: These tools may collect information such as pages visited, referring websites, and general usage statistics.\npurposes:\n- purpose: Provision of service\n  text: To operate, maintain, and provide the Service, including enabling access to the platform, delivering requested\n    features, and improving the functionality and performance of the Service.\n- purpose: Customer support\n  text: To respond to support requests, troubleshoot issues, and communicate with users regarding their use of the\n    Service.\n- purpose: Marketing communications\n  text: We may send\
  \ marketing communications regarding our services, events, webinars, or updates that may be of\n    interest to you.\n- purpose: Analytics and service improvement\n  text: To analyze usage patterns, conduct research, and improve the functionality, performance, and security of\n    our products and services.\n- purpose: Artificial intelligence functionality\n  text: we may process inputs, prompts, files, or other data submitted by users in order to generate automated outputs\n    such as analyses, insights, or recommendations.\nretention:\n- scope: Customer Content\n  period: null\n  text: Customer Content is retained for the duration of the customer subscription and in accordance with the Terms\n    of Service or customer instructions.\n- scope: Anonymized or aggregated information\n  period: indefinitely\n  text: We may retain anonymized or aggregated information indefinitely for analytics and product improvement.\nresidency:\n- region: Israel and United States\n  text: Personal Information\
  \ may be transferred to and processed in countries where Datarails or its service providers\n    operate, including, without limitation, Israel and the United States.\ntransfers:\n- mechanism: SCC\n  text: Datarails implements appropriate safeguards for international data transfers, including the use of Standard\n    Contractual Clauses approved by the European Commission, the UK Information Commissioner’s Office, or other\n    applicable mechanisms.\nsubprocessors:\n  url: null\n  text: Sub Processors\ndpa:\n  available: true\n  url: null\n  text: in accordance with the applicable Data Processing Agreement\ndeletion:\n  route: compliance@datarails.com\n  text: 'Requests regarding Personal Information may be submitted to: compliance@datarails.com .'\nrights:\n- right: access\n  text: access their Personal Information\n- right: correction\n  text: correct inaccurate information\n- right: deletion\n  text: request deletion of their Personal Information\n- right: restriction or objection\n\
  \  text: restrict or object to certain processing activities\n- right: portability\n  text: request data portability\nsale_or_sharing:\n  stance: prohibited\n  text: Datarails does not sell Personal Information.\n"
source_yaml_url: https://artifacts.apis.io/datarails/privacy/datarails-privacy-policy.yml
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
summary_line: 24 quoted statements, read from Datarails's own page on 2026-11-09.
synthetic: false
tags:
- Company
- FP&A
- Financial Planning
- Finance
- Accounting
- Budgeting
- Forecasting
- Business Intelligence
- Reporting
- Data Integration
- MCP
- Artificial Intelligence
- Excel
- Software-as-a-Service
---
