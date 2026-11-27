---
api_specs:
- filename: trellistech-properties-api-openapi.yml
  format: yaml
  label: Trellis Properties API
  slug: trellistech-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trellistech/openapi/trellistech-properties-api-openapi.yml
- filename: trellistech-tasks-api-openapi.yml
  format: yaml
  label: Trellis Tasks API
  slug: trellistech-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trellistech/openapi/trellistech-tasks-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: we may collect your name, address, mobile phone number, and email address when you submit an inquiry
  - category: location
    text: we access and collect precise and approximate device location data, including latitude, longitude, GPS accuracy, speed, heading
  - category: financial
    text: 'Bank Details: If necessary, for specific transactions such as payments to property owners or refunds, we may collect and process bank account information.'
  - category: device
    text: 'IP Address: To ensure the security of transactions and prevent fraudulent activities, we may collect your IP address when using our services.'
  - category: behavioral
    text: Cookies are small text files stored on your device that hold data specific to a website or server.
  deletion:
    route: Contact privacy requests email or deletion request under Section 9.2
    text: Right to Deletion You have the right to request that we delete any of your personal information.
  dpa:
    available: true
    text: We have entered into data processing agreements with each of these providers that include appropriate confidentiality, security, and data protection obligations.
    url: null
  purposes:
  - purpose: Field operations and shift tracking
    text: 'we use location data to: (a) automatically detect when a worker arrives at or leaves an assigned property ("geofencing")'
  - purpose: Marketing and retargeted advertising
    text: We may use data provided by you to send you email newsletters with updates on product features; to provide retargeted advertising; and to conduct sales outreach to prospective customers.
  - purpose: AI-powered guest communications and automation
    text: Our Service uses artificial intelligence ("AI") and machine learning ("ML") technologies to provide core platform functionality, including AI-powered guest communications, task scheduling, and property management automation.
  residency:
  - region: European Union (Stockholm, Sweden)
    text: Our primary database, its backups, and our application servers are hosted in the European Union, in Stockholm, Sweden, on infrastructure provided by Supabase and Amazon Web Services (AWS).
  retention:
  - period: 3 years
    scope: Customer account data
    text: Retained for the duration of the customer relationship and for a period of 3 years thereafter
  - period: typically 7 years
    scope: Payment and financial data
    text: Retained for the period required by applicable tax and financial regulations (typically 7 years).
  - period: 26 months
    scope: Cookie and analytics data
    text: Retained for up to 26 months from the date of collection.
  - period: null
    scope: Historical mobile location data
    text: Historical location points are retained for the duration of the customer relationship and deleted within 90 days of account termination
  rights:
  - right: Access
    text: The right to request a copy of your personal data that Trellis holds about you.
  - right: Correction
    text: The right to request that Trellis correct your personal data if inaccurate or out of date.
  - right: Deletion
    text: The right to request that your personal data be deleted when it is no longer necessary for Trellis to retain such data.
  - right: Portability
    text: The right to request that Trellis provide you with your personal data in a portable format
  - right: Objection
    text: The right to object to the processing of personal data, in case data processing has been based on legitimate interest and/or direct marketing.
  role:
    text: Trellis acts as a data processor when processing guest personal data, property data, and communications data on behalf of its customers (property management companies, or "PMCs").
    value: both
  sale_or_sharing:
    stance: conditional
    text: we do allow advertising networks such as Meta and Google to collect your electronic activity while on our website for retargeted advertising purposes.
  subprocessors:
    text: Some of our service providers, including the AI providers described in this Policy, process data in the United States and other countries where they operate.
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) approved by the European Commission, supplemented by the UK International Data Transfer Addendum for transfers subject to the UK GDPR
  - mechanism: BCR
    text: binding corporate rules
  - mechanism: adequacy
    text: adequacy decisions or regulations, where applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Trellis
provenance_date: '2026-11-10'
provider_name: Trellis
provider_slug: trellistech
slug: trellistech-privacy-policy
source_date: '2026-11-10'
source_filename: trellistech-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.trellistech.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Trellis\naid: trellistech\nurl: https://www.trellistech.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Trellis acts as a data processor when processing guest personal data, property data, and communications\n    data on behalf of its customers (property management companies, or \"PMCs\").\ndata_categories:\n- category: contact\n  text: we may collect your name, address, mobile phone number, and email address when you submit an inquiry\n- category: location\n  text: we access and collect precise and approximate device location data, including latitude, longitude, GPS accuracy,\n    speed,\
  \ heading\n- category: financial\n  text: 'Bank Details: If necessary, for specific transactions such as payments to property owners or refunds, we\n    may collect and process bank account information.'\n- category: device\n  text: 'IP Address: To ensure the security of transactions and prevent fraudulent activities, we may collect your\n    IP address when using our services.'\n- category: behavioral\n  text: Cookies are small text files stored on your device that hold data specific to a website or server.\npurposes:\n- purpose: Field operations and shift tracking\n  text: 'we use location data to: (a) automatically detect when a worker arrives at or leaves an assigned property\n    (\"geofencing\")'\n- purpose: Marketing and retargeted advertising\n  text: We may use data provided by you to send you email newsletters with updates on product features; to provide\n    retargeted advertising; and to conduct sales outreach to prospective customers.\n- purpose: AI-powered guest communications\
  \ and automation\n  text: Our Service uses artificial intelligence (\"AI\") and machine learning (\"ML\") technologies to provide core\n    platform functionality, including AI-powered guest communications, task scheduling, and property management\n    automation.\nretention:\n- scope: Customer account data\n  period: 3 years\n  text: Retained for the duration of the customer relationship and for a period of 3 years thereafter\n- scope: Payment and financial data\n  period: typically 7 years\n  text: Retained for the period required by applicable tax and financial regulations (typically 7 years).\n- scope: Cookie and analytics data\n  period: 26 months\n  text: Retained for up to 26 months from the date of collection.\n- scope: Historical mobile location data\n  period: null\n  text: Historical location points are retained for the duration of the customer relationship and deleted within\n    90 days of account termination\nresidency:\n- region: European Union (Stockholm, Sweden)\n  text:\
  \ Our primary database, its backups, and our application servers are hosted in the European Union, in Stockholm,\n    Sweden, on infrastructure provided by Supabase and Amazon Web Services (AWS).\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) approved by the European Commission, supplemented by the UK International\n    Data Transfer Addendum for transfers subject to the UK GDPR\n- mechanism: BCR\n  text: binding corporate rules\n- mechanism: adequacy\n  text: adequacy decisions or regulations, where applicable\nsubprocessors:\n  url: null\n  text: Some of our service providers, including the AI providers described in this Policy, process data in the\n    United States and other countries where they operate.\ndpa:\n  available: true\n  url: null\n  text: We have entered into data processing agreements with each of these providers that include appropriate confidentiality,\n    security, and data protection obligations.\ndeletion:\n  route: Contact privacy requests\
  \ email or deletion request under Section 9.2\n  text: Right to Deletion You have the right to request that we delete any of your personal information.\nrights:\n- right: Access\n  text: The right to request a copy of your personal data that Trellis holds about you.\n- right: Correction\n  text: The right to request that Trellis correct your personal data if inaccurate or out of date.\n- right: Deletion\n  text: The right to request that your personal data be deleted when it is no longer necessary for Trellis to retain\n    such data.\n- right: Portability\n  text: The right to request that Trellis provide you with your personal data in a portable format\n- right: Objection\n  text: The right to object to the processing of personal data, in case data processing has been based on legitimate\n    interest and/or direct marketing.\nsale_or_sharing:\n  stance: conditional\n  text: we do allow advertising networks such as Meta and Google to collect your electronic activity while on our\n  \
  \  website for retargeted advertising purposes.\n"
source_yaml_url: https://artifacts.apis.io/trellistech/privacy/trellistech-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Trellis's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Property Management
- Vacation Rentals
- Short-Term Rental
- AI Agents
- Hospitality
- Task Management
- MCP
---
