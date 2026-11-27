---
api_specs:
- filename: tensorwave-generate-api-openapi.yml
  format: yaml
  label: TensorWave Generate API
  slug: tensorwave-generate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tensorwave/openapi/tensorwave-generate-api-openapi.yml
- filename: tensorwave-health-api-openapi.yml
  format: yaml
  label: TensorWave Health API
  slug: tensorwave-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tensorwave/openapi/tensorwave-health-api-openapi.yml
- filename: tensorwave-openai-api-openapi.yml
  format: yaml
  label: TensorWave Open AI API
  slug: tensorwave-openai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tensorwave/openapi/tensorwave-openai-api-openapi.yml
- filename: tensorwave-slurm-api-openapi.yml
  format: yaml
  label: TensorWave Slurm API
  slug: tensorwave-slurm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tensorwave/openapi/tensorwave-slurm-api-openapi.yml
- filename: tensorwave-training-api-openapi.yml
  format: yaml
  label: TensorWave Training API
  slug: tensorwave-training-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tensorwave/openapi/tensorwave-training-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address First name and last name Phone number IP Address
  - category: device
    text: Usage Data may include information such as the type of device you’re using, your device's browser type, browser version, the pages of the Service that you visit, the time and date of your visit, the time spent on those pages, unique device identifiers and other diagnostic data.
  deletion:
    route: Right to be Forgotten request via email
    text: You can request that we delete all of your Personal Data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: 'To provide and maintain our Service: including to monitor the usage of the Service.'
  - purpose: Manage user accounts
    text: 'To manage your account: including your registration as a user of the Service.'
  - purpose: Contact users
    text: 'To contact you: including by email, telephone calls, SMS, or other equivalent forms of electronic communication'
  - purpose: Marketing and news
    text: To provide you with news, special offers and general information
  retention:
  - period: null
    scope: Personal Data
    text: We will retain your Personal Data only for as long as is necessary for the purposes set out in this Privacy Policy.
  rights:
  - right: Access and update
    text: You can review and change your Personal Data that we have about you to ensure that it is complete, accurate, and as current as possible.
  - right: Restriction
    text: You can restrict our processing of your Personal Data under certain circumstances
  - right: Portability
    text: You can request that we provide you a copy of, or access to, all or part of your Personal Data in a structured, commonly used and machine-readable form.
  - right: Withdraw consent
    text: you may withdraw your consent at any time.
  - right: Complaint
    text: You have the right to lodge a complaint with the applicable supervisory authority or regulator in the country you live in
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share your Personal Data collected from you through the Website or Services with third parties for targeted advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: no transfer of your Personal Data will take place to an organization or a country unless there are adequate controls in place to protect the security and confidentiality of your Personal Data.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TensorWave
provenance_date: '2026-11-10'
provider_name: TensorWave
provider_slug: tensorwave
slug: tensorwave-privacy-policy
source_date: '2026-11-10'
source_filename: tensorwave-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tensorwave.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TensorWave\naid: tensorwave\nurl: https://tensorwave.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address First name and last name Phone number IP Address\n- category: device\n  text: Usage Data may include information such as the type of device you’re using, your device's browser type,\n    browser version, the pages of the Service that you visit, the time and date of your visit, the time spent on\n    those pages, unique device identifiers and other diagnostic data.\npurposes:\n- purpose: Provide and maintain the\
  \ Service\n  text: 'To provide and maintain our Service: including to monitor the usage of the Service.'\n- purpose: Manage user accounts\n  text: 'To manage your account: including your registration as a user of the Service.'\n- purpose: Contact users\n  text: 'To contact you: including by email, telephone calls, SMS, or other equivalent forms of electronic communication'\n- purpose: Marketing and news\n  text: To provide you with news, special offers and general information\nretention:\n- scope: Personal Data\n  period: null\n  text: We will retain your Personal Data only for as long as is necessary for the purposes set out in this Privacy\n    Policy.\nresidency: []\ntransfers:\n- mechanism: other\n  text: no transfer of your Personal Data will take place to an organization or a country unless there are adequate\n    controls in place to protect the security and confidentiality of your Personal Data.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n\
  \  text: null\ndeletion:\n  route: Right to be Forgotten request via email\n  text: You can request that we delete all of your Personal Data.\nrights:\n- right: Access and update\n  text: You can review and change your Personal Data that we have about you to ensure that it is complete, accurate,\n    and as current as possible.\n- right: Restriction\n  text: You can restrict our processing of your Personal Data under certain circumstances\n- right: Portability\n  text: You can request that we provide you a copy of, or access to, all or part of your Personal Data in a structured,\n    commonly used and machine-readable form.\n- right: Withdraw consent\n  text: you may withdraw your consent at any time.\n- right: Complaint\n  text: You have the right to lodge a complaint with the applicable supervisory authority or regulator in the country\n    you live in\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share your Personal Data collected from you through the Website or\
  \ Services with third\n    parties for targeted advertising.\n"
source_yaml_url: https://artifacts.apis.io/tensorwave/privacy/tensorwave-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from TensorWave's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Cloud Computing
- GPU
- Infrastructure
- Inference
- Model Training
- High Performance Computing
- Data Center
---
