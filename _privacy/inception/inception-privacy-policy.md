---
api_specs:
- filename: inception-edit-api-openapi.yml
  format: yaml
  label: Inception Edit API
  slug: inception-edit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inception/openapi/inception-edit-api-openapi.yml
- filename: inception-fim-api-openapi.yml
  format: yaml
  label: Inception FIM API
  slug: inception-fim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inception/openapi/inception-fim-api-openapi.yml
- filename: inception-models-api-openapi.yml
  format: yaml
  label: Inception Models API
  slug: inception-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inception/openapi/inception-models-api-openapi.yml
- filename: inception-chat-completions-api-openapi.yml
  format: yaml
  label: Inception Chat Completions API
  slug: inception-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inception/openapi/inception-chat-completions-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: Profile or Contact Data such as first and last name, email and username.
  - category: financial
    text: Payment Data such as payment card type, last 4 digits of payment card, billing address, billing phone number and billing email.
  - category: behavioral
    text: Inferences Drawn From Other Personal Data Collected such as attributes, user behavior, and predispositions.
  - category: location
    text: Geolocation Data such as IP-address-based location information.
  - category: device
    text: Device/IP Data
  - category: communication
    text: Personal Data contained in prompts, inputs and uploaded content processed by our models.
  deletion:
    route: null
    text: If we learn we have collected Personal Data from a child under 13 years of age, we will delete that information as quickly as possible.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing and improving the Services
    text: Improving the Services, including testing, research, internal analytics and product development, including training and refining our models and analyzing usage patters to improve speed and efficiency.
  - purpose: Marketing
    text: Marketing and selling the Services.
  - purpose: Fraud protection and security
    text: Doing fraud protection, security and debugging.
  retention:
  - period: null
    scope: General personal data
    text: We retain Personal Data about you for as long as necessary to provide you with our Services or to perform our business or commercial purposes for collecting your Personal Data.
  - period: as long as we need it
    scope: Device/IP data
    text: For example, we retain your device/IP data for as long as we need it to ensure that our systems are working appropriately, effectively and efficiently.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: Please note that we do not currently sell your Personal Data as sales are defined in Nevada Revised Statutes Chapter 603A.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Inception
provenance_date: '2026-11-09'
provider_name: Inception
provider_slug: inception
slug: inception-privacy-policy
source_date: '2026-11-09'
source_filename: inception-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.inceptionlabs.ai/docs/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Inception\naid: inception\nurl: https://www.inceptionlabs.ai/docs/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Profile or Contact Data such as first and last name, email and username.\n- category: financial\n  text: Payment Data such as payment card type, last 4 digits of payment card, billing address, billing phone number\n    and billing email.\n- category: behavioral\n  text: Inferences Drawn From Other Personal Data Collected such as attributes, user behavior, and predispositions.\n- category: location\n  text: Geolocation\
  \ Data such as IP-address-based location information.\n- category: device\n  text: Device/IP Data\n- category: communication\n  text: Personal Data contained in prompts, inputs and uploaded content processed by our models.\npurposes:\n- purpose: Providing and improving the Services\n  text: Improving the Services, including testing, research, internal analytics and product development, including\n    training and refining our models and analyzing usage patters to improve speed and efficiency.\n- purpose: Marketing\n  text: Marketing and selling the Services.\n- purpose: Fraud protection and security\n  text: Doing fraud protection, security and debugging.\nretention:\n- scope: General personal data\n  period: null\n  text: We retain Personal Data about you for as long as necessary to provide you with our Services or to perform\n    our business or commercial purposes for collecting your Personal Data.\n- scope: Device/IP data\n  period: as long as we need it\n  text: For example, we retain\
  \ your device/IP data for as long as we need it to ensure that our systems are working\n    appropriately, effectively and efficiently.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: If we learn we have collected Personal Data from a child under 13 years of age, we will delete that information\n    as quickly as possible.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: Please note that we do not currently sell your Personal Data as sales are defined in Nevada Revised Statutes\n    Chapter 603A.\n"
source_yaml_url: https://artifacts.apis.io/inception/privacy/inception-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 12 quoted statements, read from Inception's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- Diffusion Models
- Code Completion
- Machine Learning
- Developer Tools
- Foundation Models
---
