---
api_specs:
- filename: shapeways-cart-api-openapi.yml
  format: yaml
  label: Shapeways Cart API
  slug: shapeways-cart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shapeways/openapi/shapeways-cart-api-openapi.yml
- filename: shapeways-materials-api-openapi.yml
  format: yaml
  label: Shapeways Materials API
  slug: shapeways-materials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shapeways/openapi/shapeways-materials-api-openapi.yml
- filename: shapeways-models-api-openapi.yml
  format: yaml
  label: Shapeways Models API
  slug: shapeways-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shapeways/openapi/shapeways-models-api-openapi.yml
- filename: shapeways-orders-api-openapi.yml
  format: yaml
  label: Shapeways Orders API
  slug: shapeways-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shapeways/openapi/shapeways-orders-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, Username, Shipping address, Billing address, IP address, Email address
  - category: contact
    text: Name, Address, Telephone number, Profile picture, Bank account number, Tax ID number
  - category: financial
    text: Purchase history, Services considered, Services offered for sale
  - category: behavioral
    text: Browsing history, Search history, Click history
  - category: location
    text: Physical location
  - category: professional
    text: Professional experience
  - category: other
    text: Data from children aged 13-16 as per regular user data
  deletion:
    route: Request via legal@shapeways.com
    text: 'Deletion: Request deletion of your data under certain conditions.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Implementing agreements and processing orders
    text: To process and deliver your order, we require your name, email address, delivery address, payment details, and phone number.
  - purpose: Customer service and product delivery
    text: This information helps us process your requests, contact you, and keep you informed.
  - purpose: Business development
    text: For business development, we collect commercially relevant information about companies and their contacts to identify potential customers and suppliers.
  - purpose: Fraud prevention
    text: we may occasionally receive and use some financial data for transaction purposes and fraud prevention.
  - purpose: Employee and applicant processing
    text: Shapeways processes employee data as part of employment contracts and in compliance with legal requirements.
  retention:
  - period: four weeks
    scope: Applicant data
    text: Applicant data is collected during the selection process and retained for no longer than four weeks post-procedure, unless consent is given for a longer retention period.
  - period: null
    scope: Personal data generally
    text: Personal data is retained only as long as necessary for the purposes for which it was collected or as required by law.
  rights:
  - right: Right of access
    text: 'Right of access: Request information on whether we process your data.'
  - right: Corrections or additions
    text: 'Corrections or additions: Request corrections or additions to your data.'
  - right: Deletion
    text: 'Deletion: Request deletion of your data under certain conditions.'
  - right: Limitation of processing
    text: 'Limitation of processing: Request limited processing while a request is being handled.'
  - right: Transfer of digital data
    text: 'Transfer of digital data: Request a copy or transfer of your data.'
  - right: Objection
    text: 'Objection: Object to data processing, particularly for direct marketing.'
  - right: Non-discrimination
    text: 'Non-discrimination: Shapeways does not discriminate against those exercising their privacy rights.'
  role:
    text: Shapeways is the controller responsible for processing and storing personal data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Note that Shapeways has never sold and does not intend to sell personal data to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Shapeways
provenance_date: '2026-11-10'
provider_name: Shapeways
provider_slug: shapeways
slug: shapeways-privacy-policy
source_date: '2026-11-10'
source_filename: shapeways-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.shapeways.com/privacy-statement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Shapeways\naid: shapeways\nurl: https://www.shapeways.com/privacy-statement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Shapeways is the controller responsible for processing and storing personal data.\ndata_categories:\n- category: identifying\n  text: Name, Username, Shipping address, Billing address, IP address, Email address\n- category: contact\n  text: Name, Address, Telephone number, Profile picture, Bank account number, Tax ID number\n- category: financial\n  text: Purchase history, Services considered, Services offered for sale\n- category: behavioral\n  text: Browsing history,\
  \ Search history, Click history\n- category: location\n  text: Physical location\n- category: professional\n  text: Professional experience\n- category: other\n  text: Data from children aged 13-16 as per regular user data\npurposes:\n- purpose: Implementing agreements and processing orders\n  text: To process and deliver your order, we require your name, email address, delivery address, payment details,\n    and phone number.\n- purpose: Customer service and product delivery\n  text: This information helps us process your requests, contact you, and keep you informed.\n- purpose: Business development\n  text: For business development, we collect commercially relevant information about companies and their contacts\n    to identify potential customers and suppliers.\n- purpose: Fraud prevention\n  text: we may occasionally receive and use some financial data for transaction purposes and fraud prevention.\n- purpose: Employee and applicant processing\n  text: Shapeways processes employee\
  \ data as part of employment contracts and in compliance with legal requirements.\nretention:\n- scope: Applicant data\n  period: four weeks\n  text: Applicant data is collected during the selection process and retained for no longer than four weeks post-procedure,\n    unless consent is given for a longer retention period.\n- scope: Personal data generally\n  period: null\n  text: Personal data is retained only as long as necessary for the purposes for which it was collected or as required\n    by law.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via legal@shapeways.com\n  text: 'Deletion: Request deletion of your data under certain conditions.'\nrights:\n- right: Right of access\n  text: 'Right of access: Request information on whether we process your data.'\n- right: Corrections or additions\n  text: 'Corrections or additions: Request corrections or additions to your data.'\n\
  - right: Deletion\n  text: 'Deletion: Request deletion of your data under certain conditions.'\n- right: Limitation of processing\n  text: 'Limitation of processing: Request limited processing while a request is being handled.'\n- right: Transfer of digital data\n  text: 'Transfer of digital data: Request a copy or transfer of your data.'\n- right: Objection\n  text: 'Objection: Object to data processing, particularly for direct marketing.'\n- right: Non-discrimination\n  text: 'Non-discrimination: Shapeways does not discriminate against those exercising their privacy rights.'\nsale_or_sharing:\n  stance: prohibited\n  text: Note that Shapeways has never sold and does not intend to sell personal data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/shapeways/privacy/shapeways-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Shapeways's own page on 2026-11-10.
synthetic: false
tags:
- Company
- 3D Printing
- Manufacturing
- Prototyping
- Hardware
- Fulfillment
- E-Commerce
---
