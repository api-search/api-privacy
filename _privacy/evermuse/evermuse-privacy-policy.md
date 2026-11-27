---
api_specs:
- filename: evermuse-ingestion-api-openapi.yml
  format: yaml
  label: Evermuse Ingestion API
  slug: evermuse-ingestion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evermuse/openapi/evermuse-ingestion-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account and profile information: name, email address, password or single sign-on identifiers, organization/workspace, role, and similar details'
  - category: financial
    text: 'Billing information: billing contact details and transaction records.'
  - category: communication
    text: Customer Data such as call and meeting recordings, transcripts, chat and support messages, documents, audio and voice data
  - category: device
    text: usage and device information such as IP address, browser and device type, pages and features viewed
  - category: professional
    text: professional or employment-related information
  deletion:
    route: Contact privacy@evermuse.com for data we control; customer contacted for Customer Data
    text: To exercise rights regarding data we control (such as your account or marketing data), contact us at privacy@evermuse.com
  dpa:
    available: true
    text: Our Data Processing Addendum (DPA) , which governs our processing of personal data contained in Customer Data on a customer's behalf.
    url: null
  purposes:
  - purpose: provide and operate the Service
    text: provide, operate, maintain, and secure the Service
  - purpose: analytics and improvement
    text: analyze and improve the Service, including evaluating the performance, accuracy, and quality of features
  - purpose: fraud and security
    text: detect, investigate, and prevent fraud, abuse, and security incidents
  residency:
  - region: United States
    text: We are based in the United States and use service providers in various locations.
  retention:
  - period: thirty (30) days
    scope: Customer Data after termination
    text: we make Customer Data available for export for thirty (30) days , then delete it from active systems within sixty (60) days
  - period: sixty (60) days
    scope: Customer Data in active systems
    text: then delete it from active systems within sixty (60) days and from backups in the ordinary course of our backup and retention cycle
  - period: null
    scope: Personal data generally
    text: We retain personal data for as long as needed to provide the Service, comply with our legal obligations, resolve disputes, and enforce our agreements
  rights:
  - right: access
    text: rights to access, correct, delete, port, or restrict the processing of your personal data
  - right: object and withdraw consent
    text: to object to certain processing, and to withdraw consent
  - right: opt out of marketing
    text: you can opt out of marketing emails at any time using the unsubscribe link or by contacting us
  - right: California rights
    text: 'California residents: you have the right to know, delete, and correct personal information, and to opt out of sale/sharing'
  role:
    text: We act as a controller for personal data we determine the purposes and means of processing
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, and we do not "share" it for cross-context behavioral advertising
  subprocessors:
    text: Our current AI/LLM subprocessors are listed, and kept up to date, at evermuse.com/data-subprocessors .
    url: evermuse.com/data-subprocessors
  transfers:
  - mechanism: SCC
    text: the European Commission's Standard Contractual Clauses (SCCs), the UK International Data Transfer Addendum
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Evermuse
provenance_date: '2026-11-09'
provider_name: Evermuse
provider_slug: evermuse
slug: evermuse-privacy-policy
source_date: '2026-11-09'
source_filename: evermuse-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.evermuse.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Evermuse\naid: evermuse\nurl: https://www.evermuse.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We act as a controller for personal data we determine the purposes and means of processing\ndata_categories:\n- category: identifying\n  text: 'Account and profile information: name, email address, password or single sign-on identifiers, organization/workspace,\n    role, and similar details'\n- category: financial\n  text: 'Billing information: billing contact details and transaction records.'\n- category: communication\n  text: Customer Data such as call and meeting recordings,\
  \ transcripts, chat and support messages, documents, audio\n    and voice data\n- category: device\n  text: usage and device information such as IP address, browser and device type, pages and features viewed\n- category: professional\n  text: professional or employment-related information\npurposes:\n- purpose: provide and operate the Service\n  text: provide, operate, maintain, and secure the Service\n- purpose: analytics and improvement\n  text: analyze and improve the Service, including evaluating the performance, accuracy, and quality of features\n- purpose: fraud and security\n  text: detect, investigate, and prevent fraud, abuse, and security incidents\nretention:\n- scope: Customer Data after termination\n  period: thirty (30) days\n  text: we make Customer Data available for export for thirty (30) days , then delete it from active systems within\n    sixty (60) days\n- scope: Customer Data in active systems\n  period: sixty (60) days\n  text: then delete it from active systems\
  \ within sixty (60) days and from backups in the ordinary course of our\n    backup and retention cycle\n- scope: Personal data generally\n  period: null\n  text: We retain personal data for as long as needed to provide the Service, comply with our legal obligations,\n    resolve disputes, and enforce our agreements\nresidency:\n- region: United States\n  text: We are based in the United States and use service providers in various locations.\ntransfers:\n- mechanism: SCC\n  text: the European Commission's Standard Contractual Clauses (SCCs), the UK International Data Transfer Addendum\nsubprocessors:\n  url: evermuse.com/data-subprocessors\n  text: Our current AI/LLM subprocessors are listed, and kept up to date, at evermuse.com/data-subprocessors .\ndpa:\n  available: true\n  url: null\n  text: Our Data Processing Addendum (DPA) , which governs our processing of personal data contained in Customer\n    Data on a customer's behalf.\ndeletion:\n  route: Contact privacy@evermuse.com for\
  \ data we control; customer contacted for Customer Data\n  text: To exercise rights regarding data we control (such as your account or marketing data), contact us at privacy@evermuse.com\nrights:\n- right: access\n  text: rights to access, correct, delete, port, or restrict the processing of your personal data\n- right: object and withdraw consent\n  text: to object to certain processing, and to withdraw consent\n- right: opt out of marketing\n  text: you can opt out of marketing emails at any time using the unsubscribe link or by contacting us\n- right: California rights\n  text: 'California residents: you have the right to know, delete, and correct personal information, and to opt\n    out of sale/sharing'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, and we do not \"share\" it for cross-context behavioral advertising\n"
source_yaml_url: https://artifacts.apis.io/evermuse/privacy/evermuse-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Evermuse's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Product Management
- Customer Feedback
- Voice of Customer
- Artificial Intelligence
- Data Ingestion
- Product Analytics
- MCP
- Developer Tools
---
