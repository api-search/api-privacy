---
api_specs:
- filename: zendesk-sell.postman_collection.json
  format: json
  label: Zendesk Sell (Sales CRM) API
  slug: sales-crm-api
  spec_type: Postman
  url: https://artifacts.apis.io/zendesk-sell/collections/zendesk-sell.postman_collection.json
- filename: zendesk-sell-contacts-api-openapi.yml
  format: yaml
  label: Zendesk Sell Contacts API
  slug: zendesk-sell-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zendesk-sell/openapi/zendesk-sell-contacts-api-openapi.yml
- filename: zendesk-sell-deals-api-openapi.yml
  format: yaml
  label: Zendesk Sell Deals API
  slug: zendesk-sell-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zendesk-sell/openapi/zendesk-sell-deals-api-openapi.yml
- filename: zendesk-sell-leads-api-openapi.yml
  format: yaml
  label: Zendesk Sell Leads API
  slug: zendesk-sell-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zendesk-sell/openapi/zendesk-sell-leads-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers , such as your name, email address, postal address, phone number, and device identifiers (e.g., advertising identifiers and IP address).
  - category: financial
    text: Commercial information , including preferences, such as purchasing history or tendencies and transactional information, such as banking information.
  - category: location
    text: Geolocation information , such as approximate location based on your IP address, mobile device location
  - category: behavioral
    text: Internet or other electronic network activity information and device information , such as your browsing history, search history, device information
  - category: other
    text: Sensitive Personal Data , such as proof of vaccination or race and ethnicity (optional)
  - category: communication
    text: customer support chat or messaging logs
  deletion:
    route: Privacy request webform
    text: You may have the right to access, correct, update, and, in some cases, request deletion of your personal data (subject to exceptions).
  dpa:
    available: true
    text: Data Processing Agreement
    url: null
  purposes:
  - purpose: Provide products and Services
    text: To provide our products, Services, and Digital Properties to you
  - purpose: Own business purposes
    text: For our own business purposes
  - purpose: Legal, safety, or security
    text: For legal, safety, or security reasons
  - purpose: Marketing
    text: For marketing our products and Services or those of third parties
  retention:
  - period: as long as necessary
    scope: General personal data
    text: Your personal data will be generally retained as long as necessary to fulfill the purposes for which we collected the personal data.
  rights:
  - right: Access
    text: Right to Access. You have the right to obtain confirmation from us whether we are processing your personal data and related information
  - right: Delete
    text: Right to Delete. You have the right to request that we delete personal data that we have collected from you.
  - right: Correct
    text: Right to Correct. You have the right to request that we correct inaccurate personal data that we maintain about you.
  - right: Opt out of sale or sharing
    text: you have the right to opt out of this “sale” or “sharing” of personal data
  role:
    text: Zendesk is a Processor , not a Controller, of personal data that we process on behalf of our Subscribers when they use Zendesk products and Services.
    value: both
  sale_or_sharing:
    stance: conditional
    text: you have the right to opt out of this “sale” or “sharing” of personal data
  subprocessors:
    text: Zendesk uses a limited number of third-party service providers to assist us in processing data for certain purposes.
    url: null
  transfers:
  - mechanism: SCC
    text: such as the EU Standard Contractual Clauses and/or the U.K. Addendum to such clauses
  - mechanism: DPF
    text: Zendesk, Inc., FutureSimple Inc., and Smooch Technologies US Inc. comply with the EU-U.S. Data Privacy Framework (EU-U.S. DPF)
  - mechanism: BCR
    text: More information on (including a copy of) our Binding Corporate Rules is available here
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Zendesk Sell
provenance_date: '2026-11-10'
provider_name: Zendesk Sell
provider_slug: zendesk-sell
slug: zendesk-sell-privacy-policy
source_date: '2026-11-10'
source_filename: zendesk-sell-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.zendesk.com/company/agreements-and-terms/privacy-notice/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Zendesk Sell\naid: zendesk-sell\nurl: https://www.zendesk.com/company/agreements-and-terms/privacy-notice/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Zendesk is a Processor , not a Controller, of personal data that we process on behalf of our Subscribers\n    when they use Zendesk products and Services.\ndata_categories:\n- category: identifying\n  text: Identifiers , such as your name, email address, postal address, phone number, and device identifiers (e.g.,\n    advertising identifiers and IP address).\n- category: financial\n  text: Commercial information , including preferences, such as\
  \ purchasing history or tendencies and transactional\n    information, such as banking information.\n- category: location\n  text: Geolocation information , such as approximate location based on your IP address, mobile device location\n- category: behavioral\n  text: Internet or other electronic network activity information and device information , such as your browsing\n    history, search history, device information\n- category: other\n  text: Sensitive Personal Data , such as proof of vaccination or race and ethnicity (optional)\n- category: communication\n  text: customer support chat or messaging logs\npurposes:\n- purpose: Provide products and Services\n  text: To provide our products, Services, and Digital Properties to you\n- purpose: Own business purposes\n  text: For our own business purposes\n- purpose: Legal, safety, or security\n  text: For legal, safety, or security reasons\n- purpose: Marketing\n  text: For marketing our products and Services or those of third parties\n\
  retention:\n- scope: General personal data\n  period: as long as necessary\n  text: Your personal data will be generally retained as long as necessary to fulfill the purposes for which we\n    collected the personal data.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: such as the EU Standard Contractual Clauses and/or the U.K. Addendum to such clauses\n- mechanism: DPF\n  text: Zendesk, Inc., FutureSimple Inc., and Smooch Technologies US Inc. comply with the EU-U.S. Data Privacy Framework\n    (EU-U.S. DPF)\n- mechanism: BCR\n  text: More information on (including a copy of) our Binding Corporate Rules is available here\nsubprocessors:\n  url: null\n  text: Zendesk uses a limited number of third-party service providers to assist us in processing data for certain\n    purposes.\ndpa:\n  available: true\n  url: null\n  text: Data Processing Agreement\ndeletion:\n  route: Privacy request webform\n  text: You may have the right to access, correct, update, and, in some cases, request\
  \ deletion of your personal\n    data (subject to exceptions).\nrights:\n- right: Access\n  text: Right to Access. You have the right to obtain confirmation from us whether we are processing your personal\n    data and related information\n- right: Delete\n  text: Right to Delete. You have the right to request that we delete personal data that we have collected from\n    you.\n- right: Correct\n  text: Right to Correct. You have the right to request that we correct inaccurate personal data that we maintain\n    about you.\n- right: Opt out of sale or sharing\n  text: you have the right to opt out of this “sale” or “sharing” of personal data\nsale_or_sharing:\n  stance: conditional\n  text: you have the right to opt out of this “sale” or “sharing” of personal data\n"
source_yaml_url: https://artifacts.apis.io/zendesk-sell/privacy/zendesk-sell-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Zendesk Sell's own page on 2026-11-10.
synthetic: false
tags:
- CRM
- Sales
- Sales Automation
- Leads
- Deals
- Pipelines
- Customer Experience
---
