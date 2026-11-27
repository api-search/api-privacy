---
api_specs:
- filename: gridline-deepfake-api-openapi.yml
  format: yaml
  label: Gridlines Deepfake API
  slug: gridline-deepfake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gridline/openapi/gridline-deepfake-api-openapi.yml
- filename: gridline-digilocker-api-openapi.yml
  format: yaml
  label: Gridlines Digilocker API
  slug: gridline-digilocker-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gridline/openapi/gridline-digilocker-api-openapi.yml
- filename: gridline-e-sign-api-openapi.yml
  format: yaml
  label: Gridlines E Sign API
  slug: gridline-e-sign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gridline/openapi/gridline-e-sign-api-openapi.yml
- filename: gridline-face-api-api-openapi.yml
  format: yaml
  label: Gridlines Face API
  slug: gridline-face-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gridline/openapi/gridline-face-api-api-openapi.yml
- filename: gridline-individual-api-openapi.yml
  format: yaml
  label: Gridlines Individual API
  slug: gridline-individual-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gridline/openapi/gridline-individual-api-openapi.yml
- filename: gridline-liveness-api-openapi.yml
  format: yaml
  label: Gridlines Liveness API
  slug: gridline-liveness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gridline/openapi/gridline-liveness-api-openapi.yml
- filename: gridline-pull-education-documents-api-openapi.yml
  format: yaml
  label: Gridlines Pull Education Documents API
  slug: gridline-pull-education-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gridline/openapi/gridline-pull-education-documents-api-openapi.yml
- filename: gridline-uidai-ovse-api-openapi.yml
  format: yaml
  label: Gridlines UIDAI OVSE API
  slug: gridline-uidai-ovse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gridline/openapi/gridline-uidai-ovse-api-openapi.yml
- filename: gridline-utility-api-openapi.yml
  format: yaml
  label: Gridlines Utility API
  slug: gridline-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gridline/openapi/gridline-utility-api-openapi.yml
- filename: gridline-workflow-mgmt-api-openapi.yml
  format: yaml
  label: Gridlines Workflow Mgmt API
  slug: gridline-workflow-mgmt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gridline/openapi/gridline-workflow-mgmt-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: we may collect your name, job title, address, location, email address, phone number, IP address, company name
  - category: identifying
    text: one or more of your ID proofs like passport number, Aadhaar number, PAN number, Driving License
  - category: financial
    text: run a credit bureau check and other information basis the scope of work
  - category: financial
    text: payment and billing information, such as your billing address, Goods & Service Tax Identification Number
  - category: behavioral
    text: general Internet data, such as your domain name, browser type, device, date and time of access, which of our web pages you visited
  - category: demographic
    text: date of birth
  - category: location
    text: Like location data is used for the purpose of validating the individual's presence at the claimed address.
  deletion:
    route: email request
    text: Individuals may request removal of their personal data by emailing contact@ongrid.in or support@ongrid.in
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: providing services
    text: FOR PROVIDING OUR SERVICES - HOSPL acts as a processor when processing information on behalf of our controller clients
  - purpose: conducting searches
    text: FOR CONDUCTING SEARCHES ON PUBLICLY AVAILABLE AND PRIVATE DATABASES
  - purpose: marketing
    text: FOR MARKETING PURPOSES - HOSPL also may process personal information to send you information about new developments
  - purpose: legal compliance
    text: FOR COMPLIANCE WITH LEGAL OBLIGATIONS - We also process your personal information in order to comply with our legal and regulatory obligations.
  retention:
  - period: null
    scope: personal information
    text: HOSPL retains personal information as needed to provide you services, respond to inquiries, consider your employment application, partner with you, or as required by contractual, statutory or other legal obligations.
  - period: null
    scope: background verification data
    text: HOSPL retains personal information only for as long as required to provide background verification (BGV) services.
  rights:
  - right: review and correct
    text: You may review, correct, update, or change the information on the website by emailing us at support@ongrid.in
  role:
    text: HOSPL acts as a processor when processing information on behalf of our controller clients
    value: both
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
name: Gridlines
provenance_date: '2026-11-09'
provider_name: Gridlines
provider_slug: gridline
slug: gridline-privacy-policy
source_date: '2026-11-09'
source_filename: gridline-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ongrid.in/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Gridlines\naid: gridline\nurl: https://ongrid.in/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: HOSPL acts as a processor when processing information on behalf of our controller clients\ndata_categories:\n- category: identifying\n  text: we may collect your name, job title, address, location, email address, phone number, IP address, company\n    name\n- category: identifying\n  text: one or more of your ID proofs like passport number, Aadhaar number, PAN number, Driving License\n- category: financial\n  text: run a credit bureau check and other information basis the scope of work\n\
  - category: financial\n  text: payment and billing information, such as your billing address, Goods & Service Tax Identification Number\n- category: behavioral\n  text: general Internet data, such as your domain name, browser type, device, date and time of access, which of\n    our web pages you visited\n- category: demographic\n  text: date of birth\n- category: location\n  text: Like location data is used for the purpose of validating the individual's presence at the claimed address.\npurposes:\n- purpose: providing services\n  text: FOR PROVIDING OUR SERVICES - HOSPL acts as a processor when processing information on behalf of our controller\n    clients\n- purpose: conducting searches\n  text: FOR CONDUCTING SEARCHES ON PUBLICLY AVAILABLE AND PRIVATE DATABASES\n- purpose: marketing\n  text: FOR MARKETING PURPOSES - HOSPL also may process personal information to send you information about new developments\n- purpose: legal compliance\n  text: FOR COMPLIANCE WITH LEGAL OBLIGATIONS -\
  \ We also process your personal information in order to comply with\n    our legal and regulatory obligations.\nretention:\n- scope: personal information\n  period: null\n  text: HOSPL retains personal information as needed to provide you services, respond to inquiries, consider your\n    employment application, partner with you, or as required by contractual, statutory or other legal obligations.\n- scope: background verification data\n  period: null\n  text: HOSPL retains personal information only for as long as required to provide background verification (BGV)\n    services.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: Individuals may request removal of their personal data by emailing contact@ongrid.in or support@ongrid.in\nrights:\n- right: review and correct\n  text: You may review, correct, update, or change the information on the website by emailing us at support@ongrid.in\n\
  sale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gridline/privacy/gridline-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 16 quoted statements, read from Gridlines's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Onboarding
- Identity Verification
- KYC
- E-signing
- Fraud Prevention
- VideoKYC
- DigitalOnboarding
- Fintech
---
