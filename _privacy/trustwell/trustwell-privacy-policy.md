---
api_specs:
- filename: trustwell-compliance-api-openapi.yml
  format: yaml
  label: Trustwell Compliance API
  slug: trustwell-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-compliance-api-openapi.yml
- filename: trustwell-products-api-openapi.yml
  format: yaml
  label: Trustwell Products API
  slug: trustwell-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-products-api-openapi.yml
- filename: trustwell-quality-api-openapi.yml
  format: yaml
  label: Trustwell Quality API
  slug: trustwell-quality-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-quality-api-openapi.yml
- filename: trustwell-recalls-api-openapi.yml
  format: yaml
  label: Trustwell Recalls API
  slug: trustwell-recalls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-recalls-api-openapi.yml
- filename: trustwell-suppliers-api-openapi.yml
  format: yaml
  label: Trustwell Suppliers API
  slug: trustwell-suppliers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-suppliers-api-openapi.yml
- filename: trustwell-traceability-api-openapi.yml
  format: yaml
  label: Trustwell Traceability API
  slug: trustwell-traceability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustwell/openapi/trustwell-traceability-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers such as your name, e-mail address, and IP address.
  - category: contact
    text: E-mail address, postal address, and telephone numbers
  - category: financial
    text: 'Sensitive personal information: payment card information.'
  - category: behavioral
    text: Internet activity/usage on our websites and platforms.
  - category: professional
    text: Professional and employment-related information, such as your resume or job role.
  - category: location
    text: imprecise location
  deletion:
    route: Rights request to Trustwell or employer, contact privacy@trustwell.com
    text: Request deletion of your personal information
  dpa:
    available: true
    text: our processing of your information is governed by a Data Processing Addendum (DPA) between your organization and Trustwell.
    url: null
  purposes:
  - purpose: Provide services to employer
    text: As a processor , to provide our Services to your employer, for example by managing log-ins and maintaining the security and confidentiality of data contained in the Services
  - purpose: Improve services
    text: To help us improve our Services and user experience, for example by identifying the parts of our Services you find useful or difficult to use.
  - purpose: Respond to requests
    text: To respond to your requests or questions, for example when you reach out to us using contact information and forms on our public websites, or apply for a job via our careers pages.
  - purpose: Marketing
    text: Where permitted by applicable law, we may send you marketing messages, including targeted advertising, for Trustwell Services that we think may interest you
  residency:
  - region: United States
    text: Trustwell is based in the United States and your personal information is stored on our systems in the US.
  retention:
  - period: null
    scope: Personal information generally
    text: We will retain your personal information as long as necessary to fulfill the purposes for which it was collected, and to satisfy legal, accounting, and reporting obligations, or to resolve disputes or enforce our agreements.
  rights:
  - right: Access
    text: Access personal information held about you
  - right: Correct
    text: Correct inaccurate or out-of-date personal information
  - right: Delete
    text: Request deletion of your personal information
  - right: Restrict processing
    text: Restrict processing of your personal information
  - right: Object
    text: Object to processing for which the legal basis is our legitimate interests
  role:
    text: When Trustwell processes your personal information in order to provide our Services to your organization, your organization is usually the “controller” of your information and Trustwell is a “processor” (also called a “service provider”).
    value: both
  sale_or_sharing:
    stance: conditional
    text: Trustwell does not sell your personal information.
  subprocessors:
    text: We use service providers to perform certain tasks for us, for example hosting our job application pages, CRM system, and webinars; or providing website analytics, or payment processing services.
    url: null
  transfers:
  - mechanism: other
    text: We collaborate with our international customers to put in place legally recognized safeguards for international transfer.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Trustwell
provenance_date: '2026-11-10'
provider_name: Trustwell
provider_slug: trustwell
slug: trustwell-privacy-policy
source_date: '2026-11-10'
source_filename: trustwell-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.trustwell.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Trustwell\naid: trustwell\nurl: https://www.trustwell.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: When Trustwell processes your personal information in order to provide our Services to your organization,\n    your organization is usually the “controller” of your information and Trustwell is a “processor” (also called\n    a “service provider”).\ndata_categories:\n- category: identifying\n  text: Identifiers such as your name, e-mail address, and IP address.\n- category: contact\n  text: E-mail address, postal address, and telephone numbers\n- category: financial\n  text: 'Sensitive\
  \ personal information: payment card information.'\n- category: behavioral\n  text: Internet activity/usage on our websites and platforms.\n- category: professional\n  text: Professional and employment-related information, such as your resume or job role.\n- category: location\n  text: imprecise location\npurposes:\n- purpose: Provide services to employer\n  text: As a processor , to provide our Services to your employer, for example by managing log-ins and maintaining\n    the security and confidentiality of data contained in the Services\n- purpose: Improve services\n  text: To help us improve our Services and user experience, for example by identifying the parts of our Services\n    you find useful or difficult to use.\n- purpose: Respond to requests\n  text: To respond to your requests or questions, for example when you reach out to us using contact information\n    and forms on our public websites, or apply for a job via our careers pages.\n- purpose: Marketing\n  text: Where permitted\
  \ by applicable law, we may send you marketing messages, including targeted advertising, for\n    Trustwell Services that we think may interest you\nretention:\n- scope: Personal information generally\n  period: null\n  text: We will retain your personal information as long as necessary to fulfill the purposes for which it was collected,\n    and to satisfy legal, accounting, and reporting obligations, or to resolve disputes or enforce our agreements.\nresidency:\n- region: United States\n  text: Trustwell is based in the United States and your personal information is stored on our systems in the US.\ntransfers:\n- mechanism: other\n  text: We collaborate with our international customers to put in place legally recognized safeguards for international\n    transfer.\nsubprocessors:\n  url: null\n  text: We use service providers to perform certain tasks for us, for example hosting our job application pages,\n    CRM system, and webinars; or providing website analytics, or payment processing\
  \ services.\ndpa:\n  available: true\n  url: null\n  text: our processing of your information is governed by a Data Processing Addendum (DPA) between your organization\n    and Trustwell.\ndeletion:\n  route: Rights request to Trustwell or employer, contact privacy@trustwell.com\n  text: Request deletion of your personal information\nrights:\n- right: Access\n  text: Access personal information held about you\n- right: Correct\n  text: Correct inaccurate or out-of-date personal information\n- right: Delete\n  text: Request deletion of your personal information\n- right: Restrict processing\n  text: Restrict processing of your personal information\n- right: Object\n  text: Object to processing for which the legal basis is our legitimate interests\nsale_or_sharing:\n  stance: conditional\n  text: Trustwell does not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/trustwell/privacy/trustwell-privacy-policy.yml
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
summary_line: 23 quoted statements, read from Trustwell's own page on 2026-11-10.
synthetic: false
tags:
- FoodIndustry
- Food Safety
- Nutrition
- Supply Chain
- Food Labeling
- Traceability
- Compliance
- Food Technology
- Quality Management
- Recall
- Artificial Intelligence
---
