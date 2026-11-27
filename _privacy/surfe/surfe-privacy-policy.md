---
api_specs:
- filename: surfe-account-api-openapi.yml
  format: yaml
  label: Surfe Account API
  slug: surfe-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfe/openapi/surfe-account-api-openapi.yml
- filename: surfe-companies-api-openapi.yml
  format: yaml
  label: Surfe Companies API
  slug: surfe-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfe/openapi/surfe-companies-api-openapi.yml
- filename: surfe-people-api-openapi.yml
  format: yaml
  label: Surfe People API
  slug: surfe-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfe/openapi/surfe-people-api-openapi.yml
- filename: surfe-recommendations-api-openapi.yml
  format: yaml
  label: Surfe Recommendations API
  slug: surfe-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/surfe/openapi/surfe-recommendations-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: Contact information (name, email address, phone number)
  - category: identifying
    text: Account information (username, password, company details)
  - category: financial
    text: Billing information (if applicable, for purchasing services)
  - category: device
    text: Device information (IP address, browser type, operating system)
  - category: behavioral
    text: Usage data (pages visited, time spent on site, referring website)
  - category: professional
    text: Job title and company name
  - category: professional
    text: Professional social media profiles
  deletion:
    route: Email support@surfe.com or opt-out form for business contact data
    text: When the retention of your data is no longer necessary for the purposes for which it is retained, we will delete or anonymize your personal data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing and managing services
    text: Operate, maintain, and improve our website and services.
  - purpose: Marketing and advertising
    text: Sending promotional emails and targeted advertisements.
  - purpose: Selling business contact data to customers
    text: Surfe collects and sells business contact data to third parties.
  - purpose: Security and fraud prevention
    text: Detect and prevent fraudulent activities, security threats, and unauthorized access.
  residency:
  - region: European Union
    text: Surfe endeavours to keep personal data within the European Union to the greatest extent possible.
  retention:
  - period: null
    scope: Personal data generally
    text: We try to limit the retention period of personal data as much as possible.
  rights:
  - right: Access
    text: to be provided with a copy of any personal data that we hold about you
  - right: Rectification
    text: to require us to update or correct any inaccurate personal data
  - right: Objection
    text: to object to the processing of your personal data
  - right: Erasure
    text: to require us to delete your personal data
  - right: Restriction
    text: to restrict our processing of your personal data
  role:
    text: In the vast majority of cases, Surfe acts in the capacity of a data processor within the meaning of the GDPR
    value: both
  sale_or_sharing:
    stance: allowed
    text: Surfe collects and sells business contact data to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: including, where applicable, the use of standard contractual clauses adopted by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Surfe
provenance_date: '2026-11-10'
provider_name: Surfe
provider_slug: surfe
slug: surfe-privacy-policy
source_date: '2026-11-10'
source_filename: surfe-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.surfe.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Surfe\naid: surfe\nurl: https://www.surfe.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: In the vast majority of cases, Surfe acts in the capacity of a data processor within the meaning of the\n    GDPR\ndata_categories:\n- category: contact\n  text: Contact information (name, email address, phone number)\n- category: identifying\n  text: Account information (username, password, company details)\n- category: financial\n  text: Billing information (if applicable, for purchasing services)\n- category: device\n  text: Device information (IP address, browser type, operating system)\n\
  - category: behavioral\n  text: Usage data (pages visited, time spent on site, referring website)\n- category: professional\n  text: Job title and company name\n- category: professional\n  text: Professional social media profiles\npurposes:\n- purpose: Providing and managing services\n  text: Operate, maintain, and improve our website and services.\n- purpose: Marketing and advertising\n  text: Sending promotional emails and targeted advertisements.\n- purpose: Selling business contact data to customers\n  text: Surfe collects and sells business contact data to third parties.\n- purpose: Security and fraud prevention\n  text: Detect and prevent fraudulent activities, security threats, and unauthorized access.\nretention:\n- scope: Personal data generally\n  period: null\n  text: We try to limit the retention period of personal data as much as possible.\nresidency:\n- region: European Union\n  text: Surfe endeavours to keep personal data within the European Union to the greatest extent\
  \ possible.\ntransfers:\n- mechanism: SCC\n  text: including, where applicable, the use of standard contractual clauses adopted by the European Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@surfe.com or opt-out form for business contact data\n  text: When the retention of your data is no longer necessary for the purposes for which it is retained, we will\n    delete or anonymize your personal data.\nrights:\n- right: Access\n  text: to be provided with a copy of any personal data that we hold about you\n- right: Rectification\n  text: to require us to update or correct any inaccurate personal data\n- right: Objection\n  text: to object to the processing of your personal data\n- right: Erasure\n  text: to require us to delete your personal data\n- right: Restriction\n  text: to restrict our processing of your personal data\nsale_or_sharing:\n  stance: allowed\n  text: Surfe collects and sells\
  \ business contact data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/surfe/privacy/surfe-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Surfe's own page on 2026-11-10.
synthetic: false
tags:
- B2B Data
- Contact Data
- Sales Intelligence
- Data Enrichment
- Lead Generation
- CRM
- Prospecting
---
