---
api_specs:
- filename: leadiq-account-api-openapi.yml
  format: yaml
  label: LeadIQ Account API
  slug: leadiq-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadiq/openapi/leadiq-account-api-openapi.yml
- filename: leadiq-lists-api-openapi.yml
  format: yaml
  label: LeadIQ Lists API
  slug: leadiq-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadiq/openapi/leadiq-lists-api-openapi.yml
- filename: leadiq-prospects-api-openapi.yml
  format: yaml
  label: LeadIQ Prospects API
  slug: leadiq-prospects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadiq/openapi/leadiq-prospects-api-openapi.yml
- filename: leadiq-company-lists-api-openapi.yml
  format: yaml
  label: LeadIQ Company Lists API
  slug: leadiq-company-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadiq/openapi/leadiq-company-lists-api-openapi.yml
- filename: leadiq-salesforce-api-openapi.yml
  format: yaml
  label: LeadIQ Salesforce API
  slug: leadiq-salesforce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadiq/openapi/leadiq-salesforce-api-openapi.yml
- filename: leadiq-graph-ql-api-openapi.yml
  format: yaml
  label: LeadIQ Graph QL API
  slug: leadiq-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/leadiq/openapi/leadiq-graph-ql-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: full name, professional email addresses and phone numbers, city location, job title and department, company/employer name and postal address
  - category: professional
    text: employment history, educational background and related social media profiles
  - category: device
    text: IP address, Internet Service Provider, approximate geographic location, referring/exit URLs, page requests, browser type, operating system
  - category: financial
    text: To purchase and access our Services, you may be asked to submit payment information, which is collected and processed by our trusted third-party payment processor.
  - category: communication
    text: We also collect information from customers about their use of the Services, such as user session time and activity.
  deletion:
    route: Privacy Center https://privacy.leadiq.com or privacy@leadiq.com
    text: If you have any questions or wish to review, update, or delete any of your information collected by us, please contact us through our Privacy Center https://privacy.leadiq.com or at privacy@leadiq.com.
  dpa:
    available: true
    text: We enter into legally binding agreements, including Data Processing Agreements, with these third-party service providers that ensure your personal information is protected.
    url: null
  purposes:
  - purpose: Provide services
    text: To set up and maintain secure access to our customers’ LeadIQ account and provide the services requested.
  - purpose: Improve services
    text: To better understand our customers’ needs by analyzing usage data or through voluntary feedback so we can personalize the experience and improve our Services.
  - purpose: Marketing
    text: To contact you about our new product features, promotions, events or other news we believe may be of interest to you.
  - purpose: Legal and compliance
    text: To comply with our necessary legal and regulatory obligations (e.g. civil or criminal subpoenas, court orders, and other compulsory orders)
  - purpose: Directory database
    text: To compile profiles for our Directory Database which provides an up to date and accurate database of professional profiles and contact information for our customers to use for business-to-business sales prospecting or recruitment.
  residency:
  - region: United States
    text: LeadIQ and our service providers may collect, process, and store your personal information in the United States and other countries.
  retention:
  - period: null
    scope: personal information generally
    text: Until we no longer have a business need to retain your personal information.
  - period: null
    scope: legally required
    text: For any legally required duration to comply with our legal obligations, resolve disputes or enforce our agreements.
  - period: null
    scope: deletion on request
    text: Upon your request to delete your personal information.
  rights:
  - right: access
    text: The right to access - You have the right to access your data at any time.
  - right: rectification
    text: The right to rectification - If the information LeadIQ holds about you is inaccurate or not complete, you have the right to ask us to rectify it.
  - right: erasure
    text: The right to erasure - You have the right to request that LeadIQ erase your personal data.
  - right: restrict processing
    text: The right to restrict processing - You have the right to ask LeadIQ to restrict how we process your data.
  - right: data portability
    text: The right to data portability - LeadIQ must allow you to port and reuse your personal data for your own purposes across different platforms.
  - right: object
    text: The right to object - You have the right to object to LeadIQ processing your data even if our processing is due to legitimate purposes as described in this Privacy Policy.
  - right: withdraw consent
    text: The right to withdraw consent - If you have given us your consent to process your data but change your mind later, you have the right to withdraw your consent at any time, and LeadIQ must stop processing your data.
  role:
    text: LeadIQ collects and processes business contact information and maintains a database of professional profiles
    value: both
  sale_or_sharing:
    stance: conditional
    text: We do not sell information that’s shared with LeadIQ by our customers via an integration unless you expressly agree to do so if you join LeadIQ Data Community.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: When transferring data from the EU, the EEA, the United Kingdom and Switzerland, LeadIQ relies on Standard Contractual Clauses as approved by the European Commission under Decision 2021/914 of 4 June 2021
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LeadIQ
provenance_date: '2026-11-09'
provider_name: LeadIQ
provider_slug: leadiq
slug: leadiq-privacy-policy
source_date: '2026-11-09'
source_filename: leadiq-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://leadiq.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LeadIQ\naid: leadiq\nurl: https://leadiq.com/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: LeadIQ collects and processes business contact information and maintains a database of professional profiles\ndata_categories:\n- category: contact\n  text: full name, professional email addresses and phone numbers, city location, job title and department, company/employer\n    name and postal address\n- category: professional\n  text: employment history, educational background and related social media profiles\n- category: device\n  text: IP address, Internet Service Provider, approximate\
  \ geographic location, referring/exit URLs, page requests,\n    browser type, operating system\n- category: financial\n  text: To purchase and access our Services, you may be asked to submit payment information, which is collected\n    and processed by our trusted third-party payment processor.\n- category: communication\n  text: We also collect information from customers about their use of the Services, such as user session time and\n    activity.\npurposes:\n- purpose: Provide services\n  text: To set up and maintain secure access to our customers’ LeadIQ account and provide the services requested.\n- purpose: Improve services\n  text: To better understand our customers’ needs by analyzing usage data or through voluntary feedback so we can\n    personalize the experience and improve our Services.\n- purpose: Marketing\n  text: To contact you about our new product features, promotions, events or other news we believe may be of interest\n    to you.\n- purpose: Legal and compliance\n \
  \ text: To comply with our necessary legal and regulatory obligations (e.g. civil or criminal subpoenas, court orders,\n    and other compulsory orders)\n- purpose: Directory database\n  text: To compile profiles for our Directory Database which provides an up to date and accurate database of professional\n    profiles and contact information for our customers to use for business-to-business sales prospecting or recruitment.\nretention:\n- scope: personal information generally\n  period: null\n  text: Until we no longer have a business need to retain your personal information.\n- scope: legally required\n  period: null\n  text: For any legally required duration to comply with our legal obligations, resolve disputes or enforce our\n    agreements.\n- scope: deletion on request\n  period: null\n  text: Upon your request to delete your personal information.\nresidency:\n- region: United States\n  text: LeadIQ and our service providers may collect, process, and store your personal information\
  \ in the United\n    States and other countries.\ntransfers:\n- mechanism: SCC\n  text: When transferring data from the EU, the EEA, the United Kingdom and Switzerland, LeadIQ relies on Standard\n    Contractual Clauses as approved by the European Commission under Decision 2021/914 of 4 June 2021\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: We enter into legally binding agreements, including Data Processing Agreements, with these third-party service\n    providers that ensure your personal information is protected.\ndeletion:\n  route: Privacy Center https://privacy.leadiq.com or privacy@leadiq.com\n  text: If you have any questions or wish to review, update, or delete any of your information collected by us,\n    please contact us through our Privacy Center https://privacy.leadiq.com or at privacy@leadiq.com.\nrights:\n- right: access\n  text: The right to access - You have the right to access your data at any time.\n- right: rectification\n\
  \  text: The right to rectification - If the information LeadIQ holds about you is inaccurate or not complete, you\n    have the right to ask us to rectify it.\n- right: erasure\n  text: The right to erasure - You have the right to request that LeadIQ erase your personal data.\n- right: restrict processing\n  text: The right to restrict processing - You have the right to ask LeadIQ to restrict how we process your data.\n- right: data portability\n  text: The right to data portability - LeadIQ must allow you to port and reuse your personal data for your own\n    purposes across different platforms.\n- right: object\n  text: The right to object - You have the right to object to LeadIQ processing your data even if our processing\n    is due to legitimate purposes as described in this Privacy Policy.\n- right: withdraw consent\n  text: The right to withdraw consent - If you have given us your consent to process your data but change your mind\n    later, you have the right to withdraw your\
  \ consent at any time, and LeadIQ must stop processing your data.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell information that’s shared with LeadIQ by our customers via an integration unless you expressly\n    agree to do so if you join LeadIQ Data Community.\n"
source_yaml_url: https://artifacts.apis.io/leadiq/privacy/leadiq-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from LeadIQ's own page on 2026-11-09.
synthetic: false
tags:
- Sales Intelligence
- B2B Data
- Contact Data
- Lead Generation
- Prospecting
- CRM Enrichment
- Sales Engagement
- GraphQL
- MCP
- Revenue Operations
- Go-To-Market
- Data Enrichment
---
