---
api_specs:
- filename: procuros-all-transactions-api-openapi.yml
  format: yaml
  label: Procuros All Transactions API
  slug: procuros-all-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/procuros/openapi/procuros-all-transactions-api-openapi.yml
- filename: procuros-incoming-transactions-api-openapi.yml
  format: yaml
  label: Procuros Incoming Transactions API
  slug: procuros-incoming-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/procuros/openapi/procuros-incoming-transactions-api-openapi.yml
- filename: procuros-misc-api-openapi.yml
  format: yaml
  label: Procuros Misc API
  slug: procuros-misc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/procuros/openapi/procuros-misc-api-openapi.yml
- filename: procuros-outgoing-transactions-api-openapi.yml
  format: yaml
  label: Procuros Outgoing Transactions API
  slug: procuros-outgoing-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/procuros/openapi/procuros-outgoing-transactions-api-openapi.yml
claim_count: 7
description: ''
doc:
  data_categories:
  - category: contact
    text: Name, first name, gender, address, e-mail address, telephone number, cell phone number
  - category: professional
    text: Job title, tasks, activities, qualifications
  - category: communication
    text: Professional email and chat messages, actions performed in the contractor's software.
  deletion:
    route: null
    text: null
  dpa:
    available: true
    text: PROCESSING AGREEMENT ACCORDING TO ART. 28 GDPR
    url: https://procuros.io/data-processing
  purposes:
  - purpose: Business contact and order processing
    text: Personal data (names, e-mail addresses, telephone numbers as well as titles) of employees of the Client or its customers are processed
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'The approved subcontractors at the time of entering into this OPA include: Nr. Subcontractor (name, address, contact person) Categories of data processed Activity description Place of data processing'
    url: https://procuros.io/data-processing
  transfers:
  - mechanism: other
    text: LLM provider US
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Procuros
provenance_date: '2026-11-10'
provider_name: Procuros
provider_slug: procuros
slug: procuros-privacy-policy
source_date: '2026-11-10'
source_filename: procuros-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://procuros.io/data-processing
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Procuros\naid: procuros\nurl: https://procuros.io/data-processing\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Name, first name, gender, address, e-mail address, telephone number, cell phone number\n- category: professional\n  text: Job title, tasks, activities, qualifications\n- category: communication\n  text: Professional email and chat messages, actions performed in the contractor's software.\npurposes:\n- purpose: Business contact and order processing\n  text: Personal data (names, e-mail addresses, telephone numbers as well as titles)\
  \ of employees of the Client\n    or its customers are processed\nretention: []\nresidency: []\ntransfers:\n- mechanism: other\n  text: LLM provider US\nsubprocessors:\n  url: https://procuros.io/data-processing\n  text: 'The approved subcontractors at the time of entering into this OPA include: Nr. Subcontractor (name, address,\n    contact person) Categories of data processed Activity description Place of data processing'\ndpa:\n  available: true\n  url: https://procuros.io/data-processing\n  text: PROCESSING AGREEMENT ACCORDING TO ART. 28 GDPR\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/procuros/privacy/procuros-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- transfers
- subprocessors
- dpa
summary_line: 7 quoted statements, read from Procuros's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- EDI
- E-Invoicing
- Supply Chain
- Procurement
- B2B Integration
- Logistics
- ERP Integration
---
