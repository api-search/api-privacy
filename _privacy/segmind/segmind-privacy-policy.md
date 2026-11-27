---
api_specs:
- filename: segmind-inference-api-openapi.yml
  format: yaml
  label: Segmind Inference API
  slug: segmind-inference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/segmind/openapi/segmind-inference-api-openapi.yml
- filename: segmind-account-api-openapi.yml
  format: yaml
  label: Segmind Account API
  slug: segmind-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/segmind/openapi/segmind-account-api-openapi.yml
- filename: segmind-storage-api-openapi.yml
  format: yaml
  label: Segmind Storage API
  slug: segmind-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/segmind/openapi/segmind-storage-api-openapi.yml
- filename: segmind-fine-tuning-api-openapi.yml
  format: yaml
  label: Segmind Fine-tuning API
  slug: segmind-fine-tuning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/segmind/openapi/segmind-fine-tuning-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: names phone numbers email addresses mailing addresses job titles usernames passwords
  - category: financial
    text: billing addresses debit/credit card numbers
  - category: device
    text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device you use to access the Services.
  - category: location
    text: Location Data. We collect location data such as information about your device's location, which can be either precise or imprecise.
  - category: behavioral
    text: Log and usage data is service-related, diagnostic, usage, and performance information our servers automatically collect when you access or use our Services
  deletion:
    route: data subject request form or contact
    text: 'To request to review, update, or delete your personal information, please visit: https://platform.segmind.com/profile'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account management
    text: To facilitate account creation and authentication and otherwise manage user accounts.
  - purpose: deliver services
    text: To deliver and facilitate delivery of services to the user.
  - purpose: fulfil orders
    text: To fulfill and manage your orders.
  - purpose: protect services
    text: To protect our Services.
  - purpose: improve experience
    text: Understand how our users use our products and services so we can improve user experience
  retention:
  - period: three (3) months
    scope: after account termination
    text: No purpose in this notice will require us keeping your personal information for longer than three (3) months past the termination of the user's account.
  - period: 6 months
    scope: Category A identifiers
    text: Category A - 6 months
  - period: As long as the user has an account with us
    scope: Category B personal information categories
    text: Category B - As long as the user has an account with us
  rights:
  - right: access
    text: to request access and obtain a copy of your personal information
  - right: rectification or erasure
    text: to request rectification or erasure
  - right: restriction
    text: to restrict the processing of your personal information
  - right: portability
    text: if applicable, to data portability
  - right: objection
    text: You may object to the processing of your personal information.
  - right: withdraw consent
    text: you have the right to withdraw your consent at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Segmind Inc. will not sell or share personal information in the future belonging to website visitors, users, and other consumers.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Segmind
provenance_date: '2026-11-10'
provider_name: Segmind
provider_slug: segmind
slug: segmind-privacy-policy
source_date: '2026-11-10'
source_filename: segmind-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.segmind.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Segmind\naid: segmind\nurl: https://www.segmind.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: names phone numbers email addresses mailing addresses job titles usernames passwords\n- category: financial\n  text: billing addresses debit/credit card numbers\n- category: device\n  text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device\n    you use to access the Services.\n- category: location\n  text: Location Data. We collect location data such as information about your\
  \ device's location, which can be either\n    precise or imprecise.\n- category: behavioral\n  text: Log and usage data is service-related, diagnostic, usage, and performance information our servers automatically\n    collect when you access or use our Services\npurposes:\n- purpose: account management\n  text: To facilitate account creation and authentication and otherwise manage user accounts.\n- purpose: deliver services\n  text: To deliver and facilitate delivery of services to the user.\n- purpose: fulfil orders\n  text: To fulfill and manage your orders.\n- purpose: protect services\n  text: To protect our Services.\n- purpose: improve experience\n  text: Understand how our users use our products and services so we can improve user experience\nretention:\n- scope: after account termination\n  period: three (3) months\n  text: No purpose in this notice will require us keeping your personal information for longer than three (3) months\n    past the termination of the user's account.\n\
  - scope: Category A identifiers\n  period: 6 months\n  text: Category A - 6 months\n- scope: Category B personal information categories\n  period: As long as the user has an account with us\n  text: Category B - As long as the user has an account with us\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: data subject request form or contact\n  text: 'To request to review, update, or delete your personal information, please visit: https://platform.segmind.com/profile'\nrights:\n- right: access\n  text: to request access and obtain a copy of your personal information\n- right: rectification or erasure\n  text: to request rectification or erasure\n- right: restriction\n  text: to restrict the processing of your personal information\n- right: portability\n  text: if applicable, to data portability\n- right: objection\n  text: You may object to the processing of your personal information.\n- right:\
  \ withdraw consent\n  text: you have the right to withdraw your consent at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: Segmind Inc. will not sell or share personal information in the future belonging to website visitors, users,\n    and other consumers.\n"
source_yaml_url: https://artifacts.apis.io/segmind/privacy/segmind-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Segmind's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Machine Learning
- Generative AI
- Inference
- Image Generation
- Video Generation
- Serverless
- GPU
- Workflows
- Fine-Tuning
---
