---
api_specs:
- filename: best-practice-fhir-api-openapi.yml
  format: yaml
  label: Best Practice Software FHIR API
  slug: best-practice-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/best-practice/openapi/best-practice-fhir-api-openapi.yml
- filename: best-practice-registered-queries-api-openapi.yml
  format: yaml
  label: Best Practice Software Registered Queries API
  slug: best-practice-registered-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/best-practice/openapi/best-practice-registered-queries-api-openapi.yml
- filename: best-practice-sites-api-openapi.yml
  format: yaml
  label: Best Practice Software Sites API
  slug: best-practice-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/best-practice/openapi/best-practice-sites-api-openapi.yml
- filename: best-practice-sql-passthrough-api-openapi.yml
  format: yaml
  label: Best Practice Software SQL Passthrough API
  slug: best-practice-sql-passthrough-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/best-practice/openapi/best-practice-sql-passthrough-api-openapi.yml
- filename: best-practice-tokens-api-openapi.yml
  format: yaml
  label: Best Practice Software Tokens API
  slug: best-practice-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/best-practice/openapi/best-practice-tokens-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: Bp collects personal information from you (in your capacity as a Medical Practitioner or Medical Staff member) such as your name, street, delivery and email addresses, contact telephone number, contact facsimile number, the name of your employer, and bank account details or credit card details (as required).
  - category: health
    text: Bp may also collect health information concerning your current health, including notes of any symptoms, the details of your appointment (including the Medical Practitioner or Medical Clinic that you wish to attend), your prescriptions, your genetic information and your healthcare identifier
  - category: demographic
    text: Bp collects other personal information from you, including your date of birth and your gender.
  - category: financial
    text: Details of your financial accounts (including bank account and/or credit card details).
  deletion:
    route: Request to delete
    text: a reasonable time after you ask Bp to delete it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide products and services
    text: To enable Bp to provide you or your Medical Clinic with our products and services;
  - purpose: Process transactions and administer accounts
    text: To process transactions and to administer accounts (including by processing of invoices, bills, statements of accounts and related financial matters necessary to enable Bp to provide products and/or services to you or to your Medical Clinic);
  - purpose: Marketing
    text: To send you or your organisation information updates, marketing materials and newsletters (unless you have notified Bp that you no longer wish to receive such marketing materials);
  - purpose: Quality assurance
    text: For quality assurance purposes, including to improve the quality of the products and services provided to you or to your Medical Clinic;
  residency:
  - region: Australia and New Zealand
    text: Bp may disclose your personal information between its Affiliates in Australia and New Zealand (where required).
  retention:
  - period: indefinitely
    scope: Personal information generally
    text: Bp will continue to store and hold your personal information indefinitely, until such time as Bp no longer needs the information for any purpose
  rights:
  - right: Complaint
    text: a complaint may also be made to the Office of the Australian Information Commissioner
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Best Practice Software
provenance_date: '2026-11-09'
provider_name: Best Practice Software
provider_slug: best-practice
slug: best-practice-privacy-policy
source_date: '2026-11-09'
source_filename: best-practice-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bestpracticesoftware.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Best Practice Software\naid: best-practice\nurl: https://bestpracticesoftware.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Bp collects personal information from you (in your capacity as a Medical Practitioner or Medical Staff member)\n    such as your name, street, delivery and email addresses, contact telephone number, contact facsimile number,\n    the name of your employer, and bank account details or credit card details (as required).\n- category: health\n  text: Bp may also collect health information concerning your\
  \ current health, including notes of any symptoms,\n    the details of your appointment (including the Medical Practitioner or Medical Clinic that you wish to attend),\n    your prescriptions, your genetic information and your healthcare identifier\n- category: demographic\n  text: Bp collects other personal information from you, including your date of birth and your gender.\n- category: financial\n  text: Details of your financial accounts (including bank account and/or credit card details).\npurposes:\n- purpose: Provide products and services\n  text: To enable Bp to provide you or your Medical Clinic with our products and services;\n- purpose: Process transactions and administer accounts\n  text: To process transactions and to administer accounts (including by processing of invoices, bills, statements\n    of accounts and related financial matters necessary to enable Bp to provide products and/or services to you\n    or to your Medical Clinic);\n- purpose: Marketing\n  text: To send\
  \ you or your organisation information updates, marketing materials and newsletters (unless you have\n    notified Bp that you no longer wish to receive such marketing materials);\n- purpose: Quality assurance\n  text: For quality assurance purposes, including to improve the quality of the products and services provided to\n    you or to your Medical Clinic;\nretention:\n- scope: Personal information generally\n  period: indefinitely\n  text: Bp will continue to store and hold your personal information indefinitely, until such time as Bp no longer\n    needs the information for any purpose\nresidency:\n- region: Australia and New Zealand\n  text: Bp may disclose your personal information between its Affiliates in Australia and New Zealand (where required).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request to delete\n  text: a reasonable time after you ask Bp to delete it.\nrights:\n- right: Complaint\n\
  \  text: a complaint may also be made to the Office of the Australian Information Commissioner\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/best-practice/privacy/best-practice-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 12 quoted statements, read from Best Practice Software's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Australia
- Electronic Health Records
- FHIR
- HL7
- Interoperability
- AU Base
- Practice Management
- General Practice
- Appointments
- Scheduling
---
