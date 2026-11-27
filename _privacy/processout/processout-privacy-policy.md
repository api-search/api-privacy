---
api_specs:
- filename: processout-balances-api-openapi.yml
  format: yaml
  label: ProcessOut Balances API
  slug: processout-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-balances-api-openapi.yml
- filename: processout-cards-api-openapi.yml
  format: yaml
  label: ProcessOut Cards API
  slug: processout-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-cards-api-openapi.yml
- filename: processout-customers-api-openapi.yml
  format: yaml
  label: ProcessOut Customers API
  slug: processout-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-customers-api-openapi.yml
- filename: processout-events-api-openapi.yml
  format: yaml
  label: ProcessOut Events API
  slug: processout-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-events-api-openapi.yml
- filename: processout-invoices-api-openapi.yml
  format: yaml
  label: ProcessOut Invoices API
  slug: processout-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-invoices-api-openapi.yml
- filename: processout-network-tokens-api-openapi.yml
  format: yaml
  label: ProcessOut Network Tokens API
  slug: processout-network-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-network-tokens-api-openapi.yml
- filename: processout-payouts-api-openapi.yml
  format: yaml
  label: ProcessOut Payouts API
  slug: processout-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-payouts-api-openapi.yml
- filename: processout-projects-api-openapi.yml
  format: yaml
  label: ProcessOut Projects API
  slug: processout-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-projects-api-openapi.yml
- filename: processout-transactions-api-openapi.yml
  format: yaml
  label: ProcessOut Transactions API
  slug: processout-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-transactions-api-openapi.yml
- filename: processout-uploads-api-openapi.yml
  format: yaml
  label: ProcessOut Uploads API
  slug: processout-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-uploads-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: names, email addresses, phone numbers, shipping and billing addresses, locations, IP addresses, transactional and financial information (e.g., card details), unique identifiers
  - category: contact
    text: Relevant contact information such as name, job title, email address, phone number, personal or business postal address.
  - category: device
    text: the browser name, the type of computer and technical information about a Site user's means of connection to our Site
  - category: behavioral
    text: Our Site may use "cookies" to perform data analytics to improve and optimize our website, products, services, marketing, customer relationships and enhance experiences.
  deletion:
    route: null
    text: Once the personal data is no longer required for these purposes, we securely erase it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: process payments
    text: To process payments.
  - purpose: improve customer service
    text: To improve customer service.
  - purpose: improve products or services
    text: To improve our products or services.
  - purpose: marketing
    text: To send Site users information they agreed to receive about topics we think will be of interest to them.
  retention:
  - period: null
    scope: personal data
    text: We will only retain personal data for as long as reasonably necessary to fulfil the following purposes
  rights:
  - right: access
    text: Right to request access to your personal data
  - right: correction
    text: Right to request correction of the personal data we hold about you
  - right: erasure
    text: Right to request erasure of your personal data
  - right: objection
    text: Right to object to processing of your personal data
  - right: restriction
    text: Request restriction of processing of your personal data
  - right: withdraw consent
    text: Withdrawal of consent
  - right: opt-out of direct marketing
    text: Right to opt-out of direct marketing communications
  role:
    text: We typically process personal data on behalf of our Customers as a data processor
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, trade, or rent personal data to others.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the EU Standard Contractual Clauses (SCCs)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ProcessOut
provenance_date: '2026-11-10'
provider_name: ProcessOut
provider_slug: processout
slug: processout-privacy-policy
source_date: '2026-11-10'
source_filename: processout-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.processout.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ProcessOut\naid: processout\nurl: https://www.processout.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We typically process personal data on behalf of our Customers as a data processor\ndata_categories:\n- category: identifying\n  text: names, email addresses, phone numbers, shipping and billing addresses, locations, IP addresses, transactional\n    and financial information (e.g., card details), unique identifiers\n- category: contact\n  text: Relevant contact information such as name, job title, email address, phone number, personal or business\n    postal address.\n- category:\
  \ device\n  text: the browser name, the type of computer and technical information about a Site user's means of connection\n    to our Site\n- category: behavioral\n  text: Our Site may use \"cookies\" to perform data analytics to improve and optimize our website, products, services,\n    marketing, customer relationships and enhance experiences.\npurposes:\n- purpose: process payments\n  text: To process payments.\n- purpose: improve customer service\n  text: To improve customer service.\n- purpose: improve products or services\n  text: To improve our products or services.\n- purpose: marketing\n  text: To send Site users information they agreed to receive about topics we think will be of interest to them.\nretention:\n- scope: personal data\n  period: null\n  text: We will only retain personal data for as long as reasonably necessary to fulfil the following purposes\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we rely on the EU Standard Contractual Clauses (SCCs)\nsubprocessors:\n\
  \  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: Once the personal data is no longer required for these purposes, we securely erase it.\nrights:\n- right: access\n  text: Right to request access to your personal data\n- right: correction\n  text: Right to request correction of the personal data we hold about you\n- right: erasure\n  text: Right to request erasure of your personal data\n- right: objection\n  text: Right to object to processing of your personal data\n- right: restriction\n  text: Request restriction of processing of your personal data\n- right: withdraw consent\n  text: Withdrawal of consent\n- right: opt-out of direct marketing\n  text: Right to opt-out of direct marketing communications\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, trade, or rent personal data to others.\n"
source_yaml_url: https://artifacts.apis.io/processout/privacy/processout-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from ProcessOut's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Payment Orchestration
- Smart Routing
- Tokenization
- Checkout
- Reconciliation
- Fraud Prevention
- 3D Secure
- Company
---
