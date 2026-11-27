---
api_specs:
- filename: halo-connect-fhir-api-openapi.yml
  format: yaml
  label: Halo Connect FHIR API
  slug: halo-connect-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halo-connect/openapi/halo-connect-fhir-api-openapi.yml
- filename: halo-connect-registered-queries-api-openapi.yml
  format: yaml
  label: Halo Connect Registered Queries API
  slug: halo-connect-registered-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halo-connect/openapi/halo-connect-registered-queries-api-openapi.yml
- filename: halo-connect-sites-api-openapi.yml
  format: yaml
  label: Halo Connect Sites API
  slug: halo-connect-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halo-connect/openapi/halo-connect-sites-api-openapi.yml
- filename: halo-connect-sql-passthrough-api-openapi.yml
  format: yaml
  label: Halo Connect SQL Passthrough API
  slug: halo-connect-sql-passthrough-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halo-connect/openapi/halo-connect-sql-passthrough-api-openapi.yml
- filename: halo-connect-tokens-api-openapi.yml
  format: yaml
  label: Halo Connect Tokens API
  slug: halo-connect-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halo-connect/openapi/halo-connect-tokens-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: health
    text: the Medical Practice Data we collect and process may include sensitive information such as health information about individuals
  - category: contact
    text: We collect and store contact details such as names, addresses, email addresses and phone numbers, from our clients, potential clients, contacts, suppliers and business partners
  - category: financial
    text: accounting information used for our internal accounting records
  - category: device
    text: technical information arising from use of our services and this site, including internet addresses and so-called cookies
  deletion:
    route: null
    text: including where you want to access, correct, amend, or request that the user delete, your personal information
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: providing services
    text: We collect, hold and use personal information for the purpose of providing our services
  - purpose: legal compliance
    text: We may also use personal information where necessary in order to comply with our legal and regulatory obligations.
  - purpose: product updates and marketing
    text: We may occasionally send product and service updates to Halo Connect contacts, clients and potential clients whose contact details we hold.
  residency:
  - region: Australia
    text: In respect of sensitive information such as health information provided to us by medical practices, we use technical infrastructure (cloud storage and processing providers) located in Australia.
  retention:
  - period: null
    scope: Medical Practice Data
    text: we are only the conduit for data and do not store information for longer than it takes to transfer data between the Integrator and the medical practice (or vice versa)
  - period: null
    scope: job applicant information
    text: We will hold your personal information for future job opportunities with us unless you tell us not to.
  rights:
  - right: access
    text: We can be contacted by email at info@haloconnect.io to request access to or correction of personal information held by us.
  - right: withdraw consent
    text: You may withdraw your consent to use or disclose your personal information at any time.
  - right: opt out of marketing
    text: Individual recipients can opt-out of receiving that kind of contact at any time.
  role:
    text: we are only the conduit for data and do not store information for longer than it takes to transfer data between the Integrator and the medical practice
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Other information such as contact and accounting information, may be stored and processed by us using infrastructure providers outside Australia.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Halo Connect
provenance_date: '2026-11-09'
provider_name: Halo Connect
provider_slug: halo-connect
slug: halo-connect-privacy-policy
source_date: '2026-11-09'
source_filename: halo-connect-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://haloconnect.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Halo Connect\naid: halo-connect\nurl: https://haloconnect.io/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we are only the conduit for data and do not store information for longer than it takes to transfer data\n    between the Integrator and the medical practice\ndata_categories:\n- category: health\n  text: the Medical Practice Data we collect and process may include sensitive information such as health information\n    about individuals\n- category: contact\n  text: We collect and store contact details such as names, addresses, email addresses and phone numbers, from our\n   \
  \ clients, potential clients, contacts, suppliers and business partners\n- category: financial\n  text: accounting information used for our internal accounting records\n- category: device\n  text: technical information arising from use of our services and this site, including internet addresses and so-called\n    cookies\npurposes:\n- purpose: providing services\n  text: We collect, hold and use personal information for the purpose of providing our services\n- purpose: legal compliance\n  text: We may also use personal information where necessary in order to comply with our legal and regulatory obligations.\n- purpose: product updates and marketing\n  text: We may occasionally send product and service updates to Halo Connect contacts, clients and potential clients\n    whose contact details we hold.\nretention:\n- scope: Medical Practice Data\n  period: null\n  text: we are only the conduit for data and do not store information for longer than it takes to transfer data\n    between the\
  \ Integrator and the medical practice (or vice versa)\n- scope: job applicant information\n  period: null\n  text: We will hold your personal information for future job opportunities with us unless you tell us not to.\nresidency:\n- region: Australia\n  text: In respect of sensitive information such as health information provided to us by medical practices, we use\n    technical infrastructure (cloud storage and processing providers) located in Australia.\ntransfers:\n- mechanism: other\n  text: Other information such as contact and accounting information, may be stored and processed by us using infrastructure\n    providers outside Australia.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: including where you want to access, correct, amend, or request that the user delete, your personal information\nrights:\n- right: access\n  text: We can be contacted by email at info@haloconnect.io to request access to\
  \ or correction of personal information\n    held by us.\n- right: withdraw consent\n  text: You may withdraw your consent to use or disclose your personal information at any time.\n- right: opt out of marketing\n  text: Individual recipients can opt-out of receiving that kind of contact at any time.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/halo-connect/privacy/halo-connect-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 16 quoted statements, read from Halo Connect's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Australia
- FHIR
- HL7
- Interoperability
- Electronic Health Records
- Practice Management
- Primary Care
- AU Base
- Health Data
---
