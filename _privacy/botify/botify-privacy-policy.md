---
api_specs:
- filename: botify-analysis-api-openapi.yml
  format: yaml
  label: Botify Analysis API
  slug: botify-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botify/openapi/botify-analysis-api-openapi.yml
- filename: botify-collections-api-openapi.yml
  format: yaml
  label: Botify Collections API
  slug: botify-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botify/openapi/botify-collections-api-openapi.yml
- filename: botify-job-api-openapi.yml
  format: yaml
  label: Botify Job API
  slug: botify-job-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botify/openapi/botify-job-api-openapi.yml
- filename: botify-keywordsgroups-api-openapi.yml
  format: yaml
  label: Botify Keywords Groups API
  slug: botify-keywordsgroups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botify/openapi/botify-keywordsgroups-api-openapi.yml
- filename: botify-project-api-openapi.yml
  format: yaml
  label: Botify Project API
  slug: botify-project-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botify/openapi/botify-project-api-openapi.yml
- filename: botify-projectquery-api-openapi.yml
  format: yaml
  label: Botify Project Query API
  slug: botify-projectquery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botify/openapi/botify-projectquery-api-openapi.yml
- filename: botify-user-api-openapi.yml
  format: yaml
  label: Botify User API
  slug: botify-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botify/openapi/botify-user-api-openapi.yml
- filename: botify-data-source-api-openapi.yml
  format: yaml
  label: Botify Data Source API
  slug: botify-data-source-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botify/openapi/botify-data-source-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personal data needed for the creation of your account on the Website such as your first name, last name, email address, postal address, telephone number, company, job title and date of birth.
  - category: financial
    text: credit or debit card four last numbers and expiration date
  - category: behavioral
    text: 'Personal data needed for navigation traffic analysis, i.e.: IP address, length of the visit on the Website, history of the consulted pages, etc.'
  deletion:
    route: email to Dpo@botify.com or postal notice to Botify
    text: 'Please send notice to Botify at: 8-12 rue d’Amsterdam, 75009 Paris, France or via email at the following addresses: Dpo@botify.com.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide requested services and demo
    text: provide you with the services you requested, such as a demo, and/or purchased on the Website
  - purpose: account creation and service provision for service users
    text: create, use and keep your user account; provide you with the Services
  - purpose: news and updates
    text: inform you about news and updates of our services
  residency:
  - region: outside the European Union
    text: We may transfer and/or store your personal data (i.e. your name and email address) outside the European Union, for the purpose of performing the Services and in particular for hosting purposes.
  retention:
  - period: 3 years
    scope: Services user account
    text: When a Service User is inactive for an interrupted period of 3 years, Botify will delete all data relating to this account.
  - period: up to thirteen months
    scope: Credit card data
    text: the four last numbers of the card number and its expiration date may be retained for evidentiary purposes in case of a possible dispute relating to the transaction, for a period of up to thirteen months following the debit date.
  - period: up to thirteen months
    scope: Cookies and raw usage data
    text: Raw usage data resulting from user identification may be retained by Botify for a period of up to thirteen months.
  rights:
  - right: access
    text: The Website and Services Users have the right to request from Botify that incomplete or inaccurate personal data is rectified, completed or updated without undue delay.
  - right: erasure
    text: The Website and Services Users have the right to obtain from Botify the erasure, without undue delay, of personal data concerning them when personal data is no longer necessary
  - right: portability
    text: Right to data portability When the processing is based on the consent of the Website and Services Users, or on the basis of a contract concluded with Botify’s customer
  - right: object
    text: The Website and Services Users have the right to object, at any time, on grounds relating to their particular situation
  - right: lodge complaint
    text: the Website and Services Users have the right to lodge a complaint with the Commission Nationale Informatique et Libertés (CNIL)
  role:
    text: Botify collects and processes personal data, as a data controller, in the following situations
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We will never sell or share your data with third parties for their marketing and advertising purposes without your consent.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: All personal data stored and transferred by Botify outside of the European Union is either protected by the Standard Contractual Clauses adopted by the European Commission or the Privacy Shield (as far as the USA is concerned).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Botify
provenance_date: '2026-11-09'
provider_name: Botify
provider_slug: botify
slug: botify-privacy-policy
source_date: '2026-11-09'
source_filename: botify-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.botify.com/privacy-and-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Botify\naid: botify\nurl: https://www.botify.com/privacy-and-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Botify collects and processes personal data, as a data controller, in the following situations\ndata_categories:\n- category: identifying\n  text: Personal data needed for the creation of your account on the Website such as your first name, last name,\n    email address, postal address, telephone number, company, job title and date of birth.\n- category: financial\n  text: credit or debit card four last numbers and expiration date\n- category: behavioral\n  text: 'Personal data needed\
  \ for navigation traffic analysis, i.e.: IP address, length of the visit on the Website,\n    history of the consulted pages, etc.'\npurposes:\n- purpose: provide requested services and demo\n  text: provide you with the services you requested, such as a demo, and/or purchased on the Website\n- purpose: account creation and service provision for service users\n  text: create, use and keep your user account; provide you with the Services\n- purpose: news and updates\n  text: inform you about news and updates of our services\nretention:\n- scope: Services user account\n  period: 3 years\n  text: When a Service User is inactive for an interrupted period of 3 years, Botify will delete all data relating\n    to this account.\n- scope: Credit card data\n  period: up to thirteen months\n  text: the four last numbers of the card number and its expiration date may be retained for evidentiary purposes\n    in case of a possible dispute relating to the transaction, for a period of up to thirteen\
  \ months following the\n    debit date.\n- scope: Cookies and raw usage data\n  period: up to thirteen months\n  text: Raw usage data resulting from user identification may be retained by Botify for a period of up to thirteen\n    months.\nresidency:\n- region: outside the European Union\n  text: We may transfer and/or store your personal data (i.e. your name and email address) outside the European\n    Union, for the purpose of performing the Services and in particular for hosting purposes.\ntransfers:\n- mechanism: SCC\n  text: All personal data stored and transferred by Botify outside of the European Union is either protected by\n    the Standard Contractual Clauses adopted by the European Commission or the Privacy Shield (as far as the USA\n    is concerned).\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to Dpo@botify.com or postal notice to Botify\n  text: 'Please send notice to Botify at: 8-12 rue d’Amsterdam,\
  \ 75009 Paris, France or via email at the following\n    addresses: Dpo@botify.com.'\nrights:\n- right: access\n  text: The Website and Services Users have the right to request from Botify that incomplete or inaccurate personal\n    data is rectified, completed or updated without undue delay.\n- right: erasure\n  text: The Website and Services Users have the right to obtain from Botify the erasure, without undue delay, of\n    personal data concerning them when personal data is no longer necessary\n- right: portability\n  text: Right to data portability When the processing is based on the consent of the Website and Services Users,\n    or on the basis of a contract concluded with Botify’s customer\n- right: object\n  text: The Website and Services Users have the right to object, at any time, on grounds relating to their particular\n    situation\n- right: lodge complaint\n  text: the Website and Services Users have the right to lodge a complaint with the Commission Nationale Informatique\n\
  \    et Libertés (CNIL)\nsale_or_sharing:\n  stance: prohibited\n  text: We will never sell or share your data with third parties for their marketing and advertising purposes without\n    your consent.\n"
source_yaml_url: https://artifacts.apis.io/botify/privacy/botify-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Botify's own page on 2026-11-09.
synthetic: false
tags:
- SEO
- Organic search
- Web Crawling
- Log Analysis
- Search Console
- Marketing Analytics
- AI Search
- Data Export
- MCP
- Agent-Native
---
