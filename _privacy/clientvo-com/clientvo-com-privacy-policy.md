---
api_specs:
- filename: clientvo-com-dataset-api-openapi.yml
  format: yaml
  label: clientvo-com Dataset API
  slug: clientvo-com-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clientvo-com/openapi/clientvo-com-dataset-api-openapi.yml
- filename: clientvo-com-mcp-api-openapi.yml
  format: yaml
  label: clientvo-com MCP API
  slug: clientvo-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clientvo-com/openapi/clientvo-com-mcp-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: If you send the enquiry form we collect your name, your email, your company and what you wrote in it.
  - category: identifying
    text: If you open an account we hold the email you sign in with and the records you save.
  - category: communication
    text: we store your email address, the exact sentence you agreed to and its version, where you signed up and when
  deletion:
    route: Email hello@clientvo.com to ask for deletion
    text: 'ask for deletion at any time: hello@clientvo.com'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Enquiry handling
    text: we collect your name, your email, your company and what you wrote in it
  - purpose: Email updates
    text: We email you only about what that sentence names.
  - purpose: Sending results
    text: If you ask us to email you a result from a calculator or a checker, we send it to you once.
  retention:
  - period: 24 months
    scope: Enquiry records
    text: Enquiry records are kept for 24 months from when they are sent, then deleted
  - period: null
    scope: Email updates
    text: 'Email updates: kept while you are subscribed.'
  - period: 30 days
    scope: Unconfirmed sign-up
    text: A sign-up never confirmed is deleted after 30 days.
  - period: indefinitely
    scope: Aggregate statistics
    text: Aggregate statistics that identify nobody are kept indefinitely.
  rights:
  - right: Access
    text: You can ask what we hold about you, ask for a copy
  - right: Deletion
    text: 'or ask for deletion at any time: hello@clientvo.com'
  - right: Complaint
    text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.
  role:
    text: The controller of the personal data on this site is Ellul Solutions Ltd, company 17364530, registered in England and Wales (Companies House)
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: your enquiry is not sold, shared or passed to a partner, and there is no third party waiting behind this form.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: clientvo-com
provenance_date: '2026-11-09'
provider_name: clientvo-com
provider_slug: clientvo-com
slug: clientvo-com-privacy-policy
source_date: '2026-11-09'
source_filename: clientvo-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://clientvo.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: clientvo-com\naid: clientvo-com\nurl: https://clientvo.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of the personal data on this site is Ellul Solutions Ltd, company 17364530, registered in\n    England and Wales (Companies House)\ndata_categories:\n- category: contact\n  text: If you send the enquiry form we collect your name, your email, your company and what you wrote in it.\n- category: identifying\n  text: If you open an account we hold the email you sign in with and the records you save.\n- category: communication\n  text: we store your email address, the\
  \ exact sentence you agreed to and its version, where you signed up and when\npurposes:\n- purpose: Enquiry handling\n  text: we collect your name, your email, your company and what you wrote in it\n- purpose: Email updates\n  text: We email you only about what that sentence names.\n- purpose: Sending results\n  text: If you ask us to email you a result from a calculator or a checker, we send it to you once.\nretention:\n- scope: Enquiry records\n  period: 24 months\n  text: Enquiry records are kept for 24 months from when they are sent, then deleted\n- scope: Email updates\n  period: null\n  text: 'Email updates: kept while you are subscribed.'\n- scope: Unconfirmed sign-up\n  period: 30 days\n  text: A sign-up never confirmed is deleted after 30 days.\n- scope: Aggregate statistics\n  period: indefinitely\n  text: Aggregate statistics that identify nobody are kept indefinitely.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n\
  \  text: null\ndeletion:\n  route: Email hello@clientvo.com to ask for deletion\n  text: 'ask for deletion at any time: hello@clientvo.com'\nrights:\n- right: Access\n  text: You can ask what we hold about you, ask for a copy\n- right: Deletion\n  text: 'or ask for deletion at any time: hello@clientvo.com'\n- right: Complaint\n  text: You can complain to the Information Commissioner's Office (ico.org.uk) in the UK.\nsale_or_sharing:\n  stance: prohibited\n  text: your enquiry is not sold, shared or passed to a partner, and there is no third party waiting behind this\n    form.\n"
source_yaml_url: https://artifacts.apis.io/clientvo-com/privacy/clientvo-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from clientvo-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Lending
- Compliance
- KYC
---
