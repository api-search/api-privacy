---
api_specs:
- filename: relaygpu-com-openapi-generated.yml
  format: yaml
  label: relaygpu-com API
  slug: relaygpu-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/relaygpu-com/openapi/_ae-authored/relaygpu-com-openapi-generated.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, email address, organization name, role, password (stored hashed), and account settings
  - category: financial
    text: 'Billing data: billing name and address, tax identifiers, purchase history and invoices.'
  - category: device
    text: 'Device and log data: IP address, browser type, device information, operating system, pages viewed, referring URL and approximate location derived from IP address.'
  - category: location
    text: approximate location derived from IP address
  - category: communication
    text: 'Communications: support requests, abuse reports, appeals, feedback, survey responses and correspondence with us.'
  deletion:
    route: Customer deletes Instance; otherwise delete or de-identify when no longer needed
    text: When we no longer need personal data, we delete or de-identify it.
  dpa:
    available: true
    text: including under a Data Processing Addendum where one has been signed.
    url: null
  purposes:
  - purpose: Provide the Services
    text: Create and manage accounts, authenticate users, route and meter requests, provision compute, provide support
  - purpose: Safety and abuse prevention
    text: Detect and respond to abuse, fraud and security incidents, enforce our terms, respond to provider abuse notices
  - purpose: Improvement and analytics
    text: Analyze usage metadata and website use to improve the Services
  residency:
  - region: United States
    text: Relay is based in the United States, and we and our service providers process personal data in the United States and other countries.
  retention:
  - period: up to 90 days
    scope: API request and response content
    text: Currently up to 90 days
  - period: null
    scope: Generated files and task results
    text: Generated files and task results are retained for the periods described in the API Services Terms.
  rights:
  - right: access, rectify, erase, restrict, object, portability
    text: the right to access, rectify, erase, restrict or object to our processing of your personal data, the right to data portability
  - right: know, correct, delete, opt out of sale/sharing
    text: to know and access the personal information we hold about you, to correct it, to delete it, to obtain a portable copy, to opt out of sale, sharing, targeted advertising and certain profiling
  - right: withdraw consent
    text: the right to withdraw consent at any time where we rely on consent
  role:
    text: Relay is the controller of the personal data described in this Policy, such as account, billing, verification, usage and website data.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and do not share it for cross-context behavioral advertising.
  subprocessors:
    text: Our current list is at relaygpu.com/legals/subprocessors .
    url: https://relaygpu.com/legals/subprocessors
  transfers:
  - mechanism: SCC
    text: we rely on the European Commission's Standard Contractual Clauses (with the UK Addendum or Swiss amendments as applicable) or another lawful mechanism for transfers to Relay.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: relaygpu-com
provenance_date: '2026-11-10'
provider_name: relaygpu-com
provider_slug: relaygpu-com
slug: relaygpu-com-privacy-policy
source_date: '2026-11-10'
source_filename: relaygpu-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://relaygpu.com/legals/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: relaygpu-com\naid: relaygpu-com\nurl: https://relaygpu.com/legals/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Relay is the controller of the personal data described in this Policy, such as account, billing, verification,\n    usage and website data.\ndata_categories:\n- category: identifying\n  text: name, email address, organization name, role, password (stored hashed), and account settings\n- category: financial\n  text: 'Billing data: billing name and address, tax identifiers, purchase history and invoices.'\n- category: device\n  text: 'Device and log data: IP address, browser type,\
  \ device information, operating system, pages viewed, referring\n    URL and approximate location derived from IP address.'\n- category: location\n  text: approximate location derived from IP address\n- category: communication\n  text: 'Communications: support requests, abuse reports, appeals, feedback, survey responses and correspondence\n    with us.'\npurposes:\n- purpose: Provide the Services\n  text: Create and manage accounts, authenticate users, route and meter requests, provision compute, provide support\n- purpose: Safety and abuse prevention\n  text: Detect and respond to abuse, fraud and security incidents, enforce our terms, respond to provider abuse\n    notices\n- purpose: Improvement and analytics\n  text: Analyze usage metadata and website use to improve the Services\nretention:\n- scope: API request and response content\n  period: up to 90 days\n  text: Currently up to 90 days\n- scope: Generated files and task results\n  period: null\n  text: Generated files and task\
  \ results are retained for the periods described in the API Services Terms.\nresidency:\n- region: United States\n  text: Relay is based in the United States, and we and our service providers process personal data in the United\n    States and other countries.\ntransfers:\n- mechanism: SCC\n  text: we rely on the European Commission's Standard Contractual Clauses (with the UK Addendum or Swiss amendments\n    as applicable) or another lawful mechanism for transfers to Relay.\nsubprocessors:\n  url: https://relaygpu.com/legals/subprocessors\n  text: Our current list is at relaygpu.com/legals/subprocessors .\ndpa:\n  available: true\n  url: null\n  text: including under a Data Processing Addendum where one has been signed.\ndeletion:\n  route: Customer deletes Instance; otherwise delete or de-identify when no longer needed\n  text: When we no longer need personal data, we delete or de-identify it.\nrights:\n- right: access, rectify, erase, restrict, object, portability\n  text: the right\
  \ to access, rectify, erase, restrict or object to our processing of your personal data, the right\n    to data portability\n- right: know, correct, delete, opt out of sale/sharing\n  text: to know and access the personal information we hold about you, to correct it, to delete it, to obtain a\n    portable copy, to opt out of sale, sharing, targeted advertising and certain profiling\n- right: withdraw consent\n  text: the right to withdraw consent at any time where we rely on consent\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and do not share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/relaygpu-com/privacy/relaygpu-com-privacy-policy.yml
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
summary_line: 20 quoted statements, read from relaygpu-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Compute
- GPU
- Cloud
---
