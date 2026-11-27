---
api_specs:
- filename: runbios-openapi-generated.yml
  format: yaml
  label: UltraSafe AI API
  slug: runbios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runbios/openapi/_ae-authored/runbios-openapi-generated.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address and profile details.
  - category: financial
    text: We keep records of your wallet credits, top-ups and per-second usage charges so we can show you an accurate billing history.
  - category: behavioral
    text: Training job configurations, job status and logs, API requests and standard server logs such as IP address and browser type.
  - category: device
    text: a short summary of your browser configuration such as its language, time zone and screen size
  - category: communication
    text: Anything you send us through the contact form or support tickets, so we can answer you and keep a record of the conversation.
  deletion:
    route: email contact@runbios.ai
    text: If you want your entire account removed, email contact@runbios.ai and we will delete your account and associated content
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run training jobs
    text: To run your training jobs on dedicated GPU pods and store the results.
  - purpose: metering and billing
    text: To meter GPU usage per second and charge it against your prepaid wallet credits.
  - purpose: transactional email
    text: To send transactional email, such as job completion notices, receipts and password resets.
  - purpose: security
    text: To keep the platform secure, for example detecting abuse or unauthorized access.
  retention:
  - period: 180 days
    scope: signup fraud signals
    text: The signup fraud signals above are kept for at most 180 days and then deleted automatically
  - period: null
    scope: content
    text: We keep your content for as long as your account is active or until you delete it from your workspace.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: We use a small number of service providers to run the platform.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: UltraSafe AI
provenance_date: '2026-11-10'
provider_name: UltraSafe AI
provider_slug: runbios
slug: runbios-privacy-policy
source_date: '2026-11-10'
source_filename: runbios-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://runbios.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: UltraSafe AI\naid: runbios\nurl: https://runbios.ai/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your name, email address and profile details.\n- category: financial\n  text: We keep records of your wallet credits, top-ups and per-second usage charges so we can show you an accurate\n    billing history.\n- category: behavioral\n  text: Training job configurations, job status and logs, API requests and standard server logs such as IP address\n    and browser type.\n- category: device\n  text: a short summary of your browser configuration\
  \ such as its language, time zone and screen size\n- category: communication\n  text: Anything you send us through the contact form or support tickets, so we can answer you and keep a record\n    of the conversation.\npurposes:\n- purpose: run training jobs\n  text: To run your training jobs on dedicated GPU pods and store the results.\n- purpose: metering and billing\n  text: To meter GPU usage per second and charge it against your prepaid wallet credits.\n- purpose: transactional email\n  text: To send transactional email, such as job completion notices, receipts and password resets.\n- purpose: security\n  text: To keep the platform secure, for example detecting abuse or unauthorized access.\nretention:\n- scope: signup fraud signals\n  period: 180 days\n  text: The signup fraud signals above are kept for at most 180 days and then deleted automatically\n- scope: content\n  period: null\n  text: We keep your content for as long as your account is active or until you delete it from your\
  \ workspace.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use a small number of service providers to run the platform.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email contact@runbios.ai\n  text: If you want your entire account removed, email contact@runbios.ai and we will delete your account and associated\n    content\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/runbios/privacy/runbios-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- sale_or_sharing
summary_line: 14 quoted statements, read from UltraSafe AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Enterprise
- Platform
- Training
- Inference
---
