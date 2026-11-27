---
api_specs:
- filename: zus-auth-api-openapi.yml
  format: yaml
  label: Zus Health Auth API
  slug: zus-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zus/openapi/zus-auth-api-openapi.yml
- filename: zus-documents-api-openapi.yml
  format: yaml
  label: Zus Health Documents API
  slug: zus-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zus/openapi/zus-documents-api-openapi.yml
- filename: zus-fhir-api-openapi.yml
  format: yaml
  label: Zus Health FHIR API
  slug: zus-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zus/openapi/zus-fhir-api-openapi.yml
- filename: zus-patient-api-openapi.yml
  format: yaml
  label: Zus Health Patient API
  slug: zus-patient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zus/openapi/zus-patient-api-openapi.yml
- filename: zus-patient-history-api-openapi.yml
  format: yaml
  label: Zus Health Patient History API
  slug: zus-patient-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zus/openapi/zus-patient-history-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, job title and your position at your company.
  - category: contact
    text: Contact information and date of birth, including email address.
  - category: professional
    text: Information about your company, its products and customers.
  - category: behavioral
    text: Other information that we may collect for customer surveys.
  - category: device
    text: your IP address, device information, and browsing activity
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: schedule meetings
    text: To schedule meetings.
  - purpose: improve products and services
    text: To improve our products and services.
  - purpose: marketing emails
    text: To send you promotional emails about new products or services or other information we think you may find interesting.
  - purpose: market research
    text: To contact you for market research purposes, including by email, phone fax, or mail.
  - purpose: internal record keeping
    text: For internal record keeping purposes.
  - purpose: personalization and advertising via cookies
    text: We may use cookies and similar tracking technologies (such as pixels and tags) to personalize visitor experience on the Website, provide content that we believe may be of interest, track visitor trends and patterns, engage in marketing and advertising
  rights:
  - right: opt out of cookies
    text: You may choose to accept or decline cookies by visiting the “Manage Cookies” link in the Website footer
  role:
    text: Zus Health, Inc. (“Company”, “we”, or “us”) uses and protects any information that you give to the Company
    value: controller
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
name: Zus Health
provenance_date: '2026-11-10'
provider_name: Zus Health
provider_slug: zus
slug: zus-privacy-policy
source_date: '2026-11-10'
source_filename: zus-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.zushealth.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Zus Health\naid: zus\nurl: https://www.zushealth.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Zus Health, Inc. (“Company”, “we”, or “us”) uses and protects any information that you give to the Company\ndata_categories:\n- category: identifying\n  text: Name, job title and your position at your company.\n- category: contact\n  text: Contact information and date of birth, including email address.\n- category: professional\n  text: Information about your company, its products and customers.\n- category: behavioral\n  text: Other information that we may collect for customer\
  \ surveys.\n- category: device\n  text: your IP address, device information, and browsing activity\npurposes:\n- purpose: schedule meetings\n  text: To schedule meetings.\n- purpose: improve products and services\n  text: To improve our products and services.\n- purpose: marketing emails\n  text: To send you promotional emails about new products or services or other information we think you may find\n    interesting.\n- purpose: market research\n  text: To contact you for market research purposes, including by email, phone fax, or mail.\n- purpose: internal record keeping\n  text: For internal record keeping purposes.\n- purpose: personalization and advertising via cookies\n  text: We may use cookies and similar tracking technologies (such as pixels and tags) to personalize visitor experience\n    on the Website, provide content that we believe may be of interest, track visitor trends and patterns, engage\n    in marketing and advertising\nretention: []\nresidency: []\ntransfers: []\n\
  subprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: opt out of cookies\n  text: You may choose to accept or decline cookies by visiting the “Manage Cookies” link in the Website footer\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/zus/privacy/zus-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- rights
summary_line: 13 quoted statements, read from Zus Health's own page on 2026-11-10.
synthetic: false
tags:
- Health
- FHIR
- Interoperability
- Patient Data
- Healthcare
---
