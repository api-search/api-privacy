---
api_specs:
- filename: parasail-ai-batch-api-openapi.yml
  format: yaml
  label: Parasail Batch API
  slug: parasail-ai-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parasail-ai/openapi/parasail-ai-batch-api-openapi.yml
- filename: parasail-ai-completions-api-openapi.yml
  format: yaml
  label: Parasail Completions API
  slug: parasail-ai-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parasail-ai/openapi/parasail-ai-completions-api-openapi.yml
- filename: parasail-ai-deployments-api-openapi.yml
  format: yaml
  label: Parasail Deployments API
  slug: parasail-ai-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parasail-ai/openapi/parasail-ai-deployments-api-openapi.yml
- filename: parasail-ai-embeddings-api-openapi.yml
  format: yaml
  label: Parasail Embeddings API
  slug: parasail-ai-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parasail-ai/openapi/parasail-ai-embeddings-api-openapi.yml
- filename: parasail-ai-files-api-openapi.yml
  format: yaml
  label: Parasail Files API
  slug: parasail-ai-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parasail-ai/openapi/parasail-ai-files-api-openapi.yml
- filename: parasail-ai-models-api-openapi.yml
  format: yaml
  label: Parasail Models API
  slug: parasail-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parasail-ai/openapi/parasail-ai-models-api-openapi.yml
- filename: parasail-ai-chat-completions-api-openapi.yml
  format: yaml
  label: Parasail Chat Completions API
  slug: parasail-ai-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/parasail-ai/openapi/parasail-ai-chat-completions-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personal data associated with creating and updating your user account(s) on the Platform . This may include things like email address and name.
  - category: financial
    text: Personal data associated with collecting and/or processing payments . This may include things like name and address.
  - category: device
    text: device, connectivity, and configuration data (including things like information about your device, the network you use to connect to the Platform/Service, data about your operating system and other software installed on your device, IP address, browser type, and referring URLs)
  - category: location
    text: statistics related to your usage of the Platform/Service (e.g., length of engagement, location, and browser type)
  - category: professional
    text: educational and work history
  - category: behavioral
    text: usage data (including things like the features of the Platform/Service you choose to use, the web pages you visit, your interactions on our website(s)
  deletion:
    route: Email hello@parasail.io to request deletion
    text: You can request that Parasail delete your personal data by sending an email to hello@parasail.io.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve the Platform
    text: We use personal data to provide and improve the Platform and the Service, and to perform essential business operations.
  - purpose: Marketing communications
    text: to send you information about products and services that we think may be of interest to you
  - purpose: Advertising and business development
    text: We use these services for analytics, attribution, advertising measurement, and business development.
  residency:
  - region: United States, European Union, or other countries
    text: Personal data we collect may be stored and processed in the United States, the European Union, or in any other country where Parasail or its affiliates, future subsidiaries or service providers maintain facilities.
  retention:
  - period: 30 days
    scope: Batch version Input
    text: We generally store and log any personal data you send as Input to the “batch” version of the Service for 30 days, though the specific timeframe may vary.
  - period: null
    scope: Serverless and dedicated Input
    text: We do not store or log any personal data you send as Input to the “serverless” and “dedicated” versions of the Service
  rights:
  - right: Access and copy
    text: You can request a copy of your personal data by sending an email to hello@parasail.io
  - right: Correction
    text: the right to correct personal data or opt out of certain sales, sharing, or targeted advertising
  - right: Marketing opt-out
    text: You can also opt out from receiving marketing communications from us by using the opt-out link on the communication.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: We do not sell personal data for money.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: including standard contractual clauses that have been approved by the European Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Parasail
provenance_date: '2026-11-10'
provider_name: Parasail
provider_slug: parasail-ai
slug: parasail-ai-privacy-policy
source_date: '2026-11-10'
source_filename: parasail-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.parasail.io/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Parasail\naid: parasail-ai\nurl: https://www.parasail.io/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Personal data associated with creating and updating your user account(s) on the Platform . This may include\n    things like email address and name.\n- category: financial\n  text: Personal data associated with collecting and/or processing payments . This may include things like name\n    and address.\n- category: device\n  text: device, connectivity, and configuration data (including things like information about\
  \ your device, the network\n    you use to connect to the Platform/Service, data about your operating system and other software installed on\n    your device, IP address, browser type, and referring URLs)\n- category: location\n  text: statistics related to your usage of the Platform/Service (e.g., length of engagement, location, and browser\n    type)\n- category: professional\n  text: educational and work history\n- category: behavioral\n  text: usage data (including things like the features of the Platform/Service you choose to use, the web pages\n    you visit, your interactions on our website(s)\npurposes:\n- purpose: Provide and improve the Platform\n  text: We use personal data to provide and improve the Platform and the Service, and to perform essential business\n    operations.\n- purpose: Marketing communications\n  text: to send you information about products and services that we think may be of interest to you\n- purpose: Advertising and business development\n  text: We use\
  \ these services for analytics, attribution, advertising measurement, and business development.\nretention:\n- scope: Batch version Input\n  period: 30 days\n  text: We generally store and log any personal data you send as Input to the “batch” version of the Service for\n    30 days, though the specific timeframe may vary.\n- scope: Serverless and dedicated Input\n  period: null\n  text: We do not store or log any personal data you send as Input to the “serverless” and “dedicated” versions\n    of the Service\nresidency:\n- region: United States, European Union, or other countries\n  text: Personal data we collect may be stored and processed in the United States, the European Union, or in any\n    other country where Parasail or its affiliates, future subsidiaries or service providers maintain facilities.\ntransfers:\n- mechanism: SCC\n  text: including standard contractual clauses that have been approved by the European Commission.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@parasail.io to request deletion\n  text: You can request that Parasail delete your personal data by sending an email to hello@parasail.io.\nrights:\n- right: Access and copy\n  text: You can request a copy of your personal data by sending an email to hello@parasail.io\n- right: Correction\n  text: the right to correct personal data or opt out of certain sales, sharing, or targeted advertising\n- right: Marketing opt-out\n  text: You can also opt out from receiving marketing communications from us by using the opt-out link on the communication.\nsale_or_sharing:\n  stance: unstated\n  text: We do not sell personal data for money.\n"
source_yaml_url: https://artifacts.apis.io/parasail-ai/privacy/parasail-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 17 quoted statements, read from Parasail's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- GPU
- Inference
- LLM
- Open Source Models
- Hugging Face
- Batch
- Embeddings
- Tokenmaxxing
- Supercloud
---
