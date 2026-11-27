---
api_specs:
- filename: codehooks-events-asyncapi.yml
  format: yaml
  label: Codehooks Events (AsyncAPI)
  slug: codehooks-events
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/codehooks/asyncapi/codehooks-events-asyncapi.yml
- filename: codehooks-documents-api-openapi.yml
  format: yaml
  label: Codehooks Documents API
  slug: codehooks-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codehooks/openapi/codehooks-documents-api-openapi.yml
- filename: codehooks-key-value-store-api-openapi.yml
  format: yaml
  label: Codehooks Key-Value Store API
  slug: codehooks-key-value-store-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codehooks/openapi/codehooks-key-value-store-api-openapi.yml
- filename: codehooks-queue-api-openapi.yml
  format: yaml
  label: Codehooks Queue API
  slug: codehooks-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codehooks/openapi/codehooks-queue-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: contact
    text: Personally identifiable information includes your email address and your name ("Personal Information").
  - category: device
    text: This Log Data may include information such as your computer's Internet Protocol ("IP") address, browser type, browser version
  - category: behavioral
    text: the pages of our Service that you visit, the time and date of your visit, the time spent on those pages and other statistics.
  deletion:
    route: Account deletion via functionality provided
    text: We provide functionality for deleting your account. Deleting the account will also delete your data.
  dpa:
    available: true
    text: This is the up-to-date list referred to in section 3.3 of our Data Processing Agreement
    url: null
  purposes:
  - purpose: Delivering the Service
    text: The use of this information is for the sole purpose of delivering the Service to you.
  - purpose: Providing and improving the Service
    text: We use your Personal Information for providing and improving the Service.
  residency:
  - region: European Union
    text: Customer data stored in Codehooks services, including backups, is stored and processed on servers located in the European Union (Amsterdam and Ireland).
  retention:
  - period: for as long as you have an account on the system
    scope: Personal data (email, name)
    text: CODEHOOKS AS will keep your personal data (email, name) for as long as you have an account on the system.
  role:
    text: CODEHOOKS AS ("us", "we", or "our") operates the codehooks.io website (the "Service").
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not use cookies for advertising, and we do not share cookie data with advertising networks or data brokers.
  subprocessors:
    text: These are the subprocessors we use.
    url: null
  transfers:
  - mechanism: other
    text: Some third party providers we use for payment processing, support chat and website analytics may process limited account or visitor data outside the EU/EEA, under the safeguards described in Chapter V of the GDPR.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Codehooks
provenance_date: '2026-11-09'
provider_name: Codehooks
provider_slug: codehooks
slug: codehooks-privacy-policy
source_date: '2026-11-09'
source_filename: codehooks-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://codehooks.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Codehooks\naid: codehooks\nurl: https://codehooks.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: CODEHOOKS AS (\"us\", \"we\", or \"our\") operates the codehooks.io website (the \"Service\").\ndata_categories:\n- category: contact\n  text: Personally identifiable information includes your email address and your name (\"Personal Information\").\n- category: device\n  text: This Log Data may include information such as your computer's Internet Protocol (\"IP\") address, browser\n    type, browser version\n- category: behavioral\n  text: the pages of our Service that you visit, the\
  \ time and date of your visit, the time spent on those pages\n    and other statistics.\npurposes:\n- purpose: Delivering the Service\n  text: The use of this information is for the sole purpose of delivering the Service to you.\n- purpose: Providing and improving the Service\n  text: We use your Personal Information for providing and improving the Service.\nretention:\n- scope: Personal data (email, name)\n  period: for as long as you have an account on the system\n  text: CODEHOOKS AS will keep your personal data (email, name) for as long as you have an account on the system.\nresidency:\n- region: European Union\n  text: Customer data stored in Codehooks services, including backups, is stored and processed on servers located\n    in the European Union (Amsterdam and Ireland).\ntransfers:\n- mechanism: other\n  text: Some third party providers we use for payment processing, support chat and website analytics may process\n    limited account or visitor data outside the EU/EEA, under the\
  \ safeguards described in Chapter V of the GDPR.\nsubprocessors:\n  url: null\n  text: These are the subprocessors we use.\ndpa:\n  available: true\n  url: null\n  text: This is the up-to-date list referred to in section 3.3 of our Data Processing Agreement\ndeletion:\n  route: Account deletion via functionality provided\n  text: We provide functionality for deleting your account. Deleting the account will also delete your data.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not use cookies for advertising, and we do not share cookie data with advertising networks or data\n    brokers.\n"
source_yaml_url: https://artifacts.apis.io/codehooks/privacy/codehooks-privacy-policy.yml
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
- sale_or_sharing
summary_line: 13 quoted statements, read from Codehooks's own page on 2026-11-09.
synthetic: false
tags:
- Backend
- Database
- Event
- Hooks
- JavaScript
- NoSQL
- Queues
- Serverless
- Webhook
- Workers
- Workflows
---
