---
api_specs:
- filename: ordogrid-clients-api-openapi.yml
  format: yaml
  label: OrdoGrid Clients API
  slug: ordogrid-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-clients-api-openapi.yml
- filename: ordogrid-credit-notes-api-openapi.yml
  format: yaml
  label: OrdoGrid Credit Notes API
  slug: ordogrid-credit-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-credit-notes-api-openapi.yml
- filename: ordogrid-fidelity-api-openapi.yml
  format: yaml
  label: OrdoGrid Fidelity API
  slug: ordogrid-fidelity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-fidelity-api-openapi.yml
- filename: ordogrid-invoices-api-openapi.yml
  format: yaml
  label: OrdoGrid Invoices API
  slug: ordogrid-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-invoices-api-openapi.yml
- filename: ordogrid-meta-api-openapi.yml
  format: yaml
  label: OrdoGrid Meta API
  slug: ordogrid-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-meta-api-openapi.yml
- filename: ordogrid-payments-api-openapi.yml
  format: yaml
  label: OrdoGrid Payments API
  slug: ordogrid-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-payments-api-openapi.yml
- filename: ordogrid-peppol-api-openapi.yml
  format: yaml
  label: OrdoGrid Peppol API
  slug: ordogrid-peppol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-peppol-api-openapi.yml
- filename: ordogrid-quotes-api-openapi.yml
  format: yaml
  label: OrdoGrid Quotes API
  slug: ordogrid-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-quotes-api-openapi.yml
- filename: ordogrid-receipts-api-openapi.yml
  format: yaml
  label: OrdoGrid Receipts API
  slug: ordogrid-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-receipts-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identification data: first name, last name, email address, phone number'
  - category: financial
    text: 'Company data: legal name, VAT number, registered office address, bank details (IBAN, BIC), logo'
  - category: contact
    text: 'Client data: name, email, address, VAT number of your clients'
  - category: device
    text: 'Connection data: IP address, browser type, operating system, pages visited'
  - category: behavioral
    text: 'Usage data: interactions with the Platform, features used, navigation events'
  - category: other
    text: 'Uploaded documents: PDF invoices, bank statements, supporting documents, company logo'
  deletion:
    route: account deletion
    text: 'After account deletion: data is deleted immediately, except for data we are legally required to retain'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Contract performance
    text: 'Contract performance: creation and management of your account, provision of invoicing, accounting, project management and online payment services'
  - purpose: Calendar synchronisation
    text: 'Calendar synchronisation: if you enable a calendar integration, your tasks (title, dates, status, description) are sent to Google Calendar/Tasks or Outlook Calendar, or made available via an ICS feed for iOS Calendar'
  - purpose: Service improvement
    text: 'Service improvement: anonymised analysis of Platform usage via Google Analytics (browser cookies only) to improve the user experience'
  - purpose: Advertising measurement
    text: 'Advertising measurement: measurement of the effectiveness of our campaigns via Google Ads (browser cookies only — this purpose never applies to data obtained via Google OAuth)'
  - purpose: Security
    text: 'Security: protection against fraud and unauthorised access'
  residency:
  - region: EU
    text: Data hosting within the European Union
  retention:
  - period: for the duration of your active subscription
    scope: Account data
    text: 'Account data: retained for the duration of your active subscription'
  - period: 7 years
    scope: Accounting records
    text: 'Belgian accounting and tax obligations: 7 years for accounting records'
  - period: a maximum of 14 months
    scope: Analytics data
    text: 'Analytics data: anonymised and retained for a maximum of 14 months (Google Analytics policy)'
  - period: deleted immediately upon disconnection
    scope: Calendar integration tokens
    text: 'Calendar integration tokens (Google, Outlook): deleted immediately upon disconnection of the integration or account deletion'
  rights:
  - right: Right of access
    text: 'Right of access: obtain a copy of your personal data'
  - right: Right to erasure
    text: 'Right to erasure: request deletion of your data'
  - right: Right to object
    text: 'Right to object: object to the processing of your data based on our legitimate interest'
  - right: Right to portability
    text: 'Right to portability: receive your data in a structured, machine-readable format'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'We use the following processors for the processing of your data:'
    url: null
  transfers:
  - mechanism: SCC
    text: European Commission standard contractual clauses
  - mechanism: DPF
    text: EU-US Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: OrdoGrid
provenance_date: '2026-11-10'
provider_name: OrdoGrid
provider_slug: ordogrid
slug: ordogrid-privacy-policy
source_date: '2026-11-10'
source_filename: ordogrid-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ordogrid.com/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: OrdoGrid\naid: ordogrid\nurl: https://ordogrid.com/en/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Identification data: first name, last name, email address, phone number'\n- category: financial\n  text: 'Company data: legal name, VAT number, registered office address, bank details (IBAN, BIC), logo'\n- category: contact\n  text: 'Client data: name, email, address, VAT number of your clients'\n- category: device\n  text: 'Connection data: IP address, browser type, operating system, pages visited'\n- category: behavioral\n  text:\
  \ 'Usage data: interactions with the Platform, features used, navigation events'\n- category: other\n  text: 'Uploaded documents: PDF invoices, bank statements, supporting documents, company logo'\npurposes:\n- purpose: Contract performance\n  text: 'Contract performance: creation and management of your account, provision of invoicing, accounting, project\n    management and online payment services'\n- purpose: Calendar synchronisation\n  text: 'Calendar synchronisation: if you enable a calendar integration, your tasks (title, dates, status, description)\n    are sent to Google Calendar/Tasks or Outlook Calendar, or made available via an ICS feed for iOS Calendar'\n- purpose: Service improvement\n  text: 'Service improvement: anonymised analysis of Platform usage via Google Analytics (browser cookies only)\n    to improve the user experience'\n- purpose: Advertising measurement\n  text: 'Advertising measurement: measurement of the effectiveness of our campaigns via Google Ads (browser\
  \ cookies\n    only — this purpose never applies to data obtained via Google OAuth)'\n- purpose: Security\n  text: 'Security: protection against fraud and unauthorised access'\nretention:\n- scope: Account data\n  period: for the duration of your active subscription\n  text: 'Account data: retained for the duration of your active subscription'\n- scope: Accounting records\n  period: 7 years\n  text: 'Belgian accounting and tax obligations: 7 years for accounting records'\n- scope: Analytics data\n  period: a maximum of 14 months\n  text: 'Analytics data: anonymised and retained for a maximum of 14 months (Google Analytics policy)'\n- scope: Calendar integration tokens\n  period: deleted immediately upon disconnection\n  text: 'Calendar integration tokens (Google, Outlook): deleted immediately upon disconnection of the integration\n    or account deletion'\nresidency:\n- region: EU\n  text: Data hosting within the European Union\ntransfers:\n- mechanism: SCC\n  text: European Commission\
  \ standard contractual clauses\n- mechanism: DPF\n  text: EU-US Data Privacy Framework\nsubprocessors:\n  url: null\n  text: 'We use the following processors for the processing of your data:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion\n  text: 'After account deletion: data is deleted immediately, except for data we are legally required to retain'\nrights:\n- right: Right of access\n  text: 'Right of access: obtain a copy of your personal data'\n- right: Right to erasure\n  text: 'Right to erasure: request deletion of your data'\n- right: Right to object\n  text: 'Right to object: object to the processing of your data based on our legitimate interest'\n- right: Right to portability\n  text: 'Right to portability: receive your data in a structured, machine-readable format'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ordogrid/privacy/ordogrid-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 24 quoted statements, read from OrdoGrid's own page on 2026-11-10.
synthetic: false
tags:
- Invoicing
- Peppol
- Belgium
- Software-as-a-Service
- business-documents
---
