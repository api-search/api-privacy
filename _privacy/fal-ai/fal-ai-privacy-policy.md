---
api_specs:
- filename: fal-ai-asyncapi.yml
  format: yaml
  label: fal Realtime API
  slug: fal-realtime-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/fal-ai/asyncapi/fal-ai-asyncapi.yml
- filename: fal-ai-asyncapi.yml
  format: yaml
  label: fal Streaming API
  slug: fal-streaming-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/fal-ai/asyncapi/fal-ai-asyncapi.yml
- filename: fal-ai-apps-api-openapi.yml
  format: yaml
  label: fal Apps API
  slug: fal-ai-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fal-ai/openapi/fal-ai-apps-api-openapi.yml
- filename: fal-ai-files-api-openapi.yml
  format: yaml
  label: fal Files API
  slug: fal-ai-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fal-ai/openapi/fal-ai-files-api-openapi.yml
- filename: fal-ai-queue-api-openapi.yml
  format: yaml
  label: fal Queue API
  slug: fal-ai-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fal-ai/openapi/fal-ai-queue-api-openapi.yml
- filename: fal-ai-secrets-api-openapi.yml
  format: yaml
  label: fal Secrets API
  slug: fal-ai-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fal-ai/openapi/fal-ai-secrets-api-openapi.yml
- filename: fal-ai-storage-api-openapi.yml
  format: yaml
  label: fal Storage API
  slug: fal-ai-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fal-ai/openapi/fal-ai-storage-api-openapi.yml
- filename: fal-ai-streaming-api-openapi.yml
  format: yaml
  label: fal Streaming API
  slug: fal-ai-streaming-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fal-ai/openapi/fal-ai-streaming-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, email address, phone number, and any other information you choose to provide
  - category: financial
    text: last 4 digits of your credit card or account number, credit card provider or bank name, billing address, and IP address
  - category: device
    text: data about the device and network you use, such as your hardware model, operating system version, mobile network, IP address, unique device identifiers, and browser type
  - category: behavioral
    text: browsing behavior (such as pages viewed and links clicked), and information about your activity on specific pages (such as mouse movements and keystrokes)
  - category: location
    text: we may infer your approximate location based on your IP address
  - category: communication
    text: we also collect personal data that you provide in the input to our Services, including your prompts and other content you choose to upload, such as files, images, audio and video, and other data
  deletion:
    route: email support@fal.ai to request deletion; or log in to the fal dashboard
    text: You have the right to (1) request to know more about and access your personal information, including in a portable format, (2) request deletion of your personal information, and (3) request correction of inaccurate personal information.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide, maintain, and improve the Services
    text: We use the information we collect to provide, maintain, and improve the Services.
  - purpose: targeted advertising
    text: Target advertisements to you on third-party platforms and websites
  - purpose: security
    text: Detect, investigate, respond to, prosecute, and help protect against security incidents and other malicious, deceptive, fraudulent, or illegal activity
  - purpose: marketing communications
    text: Send you marketing communications such as newsletters, promotional materials, and other information that may interest you
  residency:
  - region: United States and other countries
    text: we and our service providers process and store personal information on servers located in the United States and other countries
  retention:
  - period: as long as your account remains active
    scope: account information
    text: We store personal information associated with your account for as long as your account remains active.
  - period: 30 days
    scope: closed accounts
    text: If you close your account, we will delete personal information related to your account within 30 days
  - period: two years of account inactivity
    scope: inactive accounts
    text: otherwise, we will delete this information after two years of account inactivity
  rights:
  - right: access
    text: You have the right to (1) request to know more about and access your personal information, including in a portable format
  - right: deletion
    text: (2) request deletion of your personal information
  - right: correction
    text: (3) request correction of inaccurate personal information
  - right: objection or restriction (EU)
    text: you may have the right to object to certain processing or request we restrict certain processing
  - right: lodge complaint with DPA
    text: you have the right to lodge a complaint with the Data Protection Authority where you reside
  role:
    text: we handle your personal information as a service provider (sometimes called a "processor") on behalf of the enterprise customer. Personal information processed on behalf of our enterprise customers is not subject to this Privacy Policy.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: we take steps to ensure that your personal information receives an adequate level of protection (by putting in place appropriate safeguards, such as contractual clauses)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: fal
provenance_date: '2026-11-09'
provider_name: fal
provider_slug: fal-ai
slug: fal-ai-privacy-policy
source_date: '2026-11-09'
source_filename: fal-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fal.ai/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: fal\naid: fal-ai\nurl: https://fal.ai/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we handle your personal information as a service provider (sometimes called a \"processor\") on behalf of\n    the enterprise customer. Personal information processed on behalf of our enterprise customers is not subject\n    to this Privacy Policy.\ndata_categories:\n- category: identifying\n  text: your name, email address, phone number, and any other information you choose to provide\n- category: financial\n  text: last 4 digits of your credit card or account number, credit card provider or\
  \ bank name, billing address,\n    and IP address\n- category: device\n  text: data about the device and network you use, such as your hardware model, operating system version, mobile\n    network, IP address, unique device identifiers, and browser type\n- category: behavioral\n  text: browsing behavior (such as pages viewed and links clicked), and information about your activity on specific\n    pages (such as mouse movements and keystrokes)\n- category: location\n  text: we may infer your approximate location based on your IP address\n- category: communication\n  text: we also collect personal data that you provide in the input to our Services, including your prompts and\n    other content you choose to upload, such as files, images, audio and video, and other data\npurposes:\n- purpose: provide, maintain, and improve the Services\n  text: We use the information we collect to provide, maintain, and improve the Services.\n- purpose: targeted advertising\n  text: Target advertisements\
  \ to you on third-party platforms and websites\n- purpose: security\n  text: Detect, investigate, respond to, prosecute, and help protect against security incidents and other malicious,\n    deceptive, fraudulent, or illegal activity\n- purpose: marketing communications\n  text: Send you marketing communications such as newsletters, promotional materials, and other information that\n    may interest you\nretention:\n- scope: account information\n  period: as long as your account remains active\n  text: We store personal information associated with your account for as long as your account remains active.\n- scope: closed accounts\n  period: 30 days\n  text: If you close your account, we will delete personal information related to your account within 30 days\n- scope: inactive accounts\n  period: two years of account inactivity\n  text: otherwise, we will delete this information after two years of account inactivity\nresidency:\n- region: United States and other countries\n  text: we and\
  \ our service providers process and store personal information on servers located in the United States\n    and other countries\ntransfers:\n- mechanism: other\n  text: we take steps to ensure that your personal information receives an adequate level of protection (by putting\n    in place appropriate safeguards, such as contractual clauses)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@fal.ai to request deletion; or log in to the fal dashboard\n  text: You have the right to (1) request to know more about and access your personal information, including in\n    a portable format, (2) request deletion of your personal information, and (3) request correction of inaccurate\n    personal information.\nrights:\n- right: access\n  text: You have the right to (1) request to know more about and access your personal information, including in\n    a portable format\n- right: deletion\n  text: (2) request deletion\
  \ of your personal information\n- right: correction\n  text: (3) request correction of inaccurate personal information\n- right: objection or restriction (EU)\n  text: you may have the right to object to certain processing or request we restrict certain processing\n- right: lodge complaint with DPA\n  text: you have the right to lodge a complaint with the Data Protection Authority where you reside\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fal-ai/privacy/fal-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 22 quoted statements, read from fal's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Generative AI
- Generative Media
- Image Generation
- Video Generation
- Audio Generation
- Inference
- Serverless
- GPU
- MCP
- Real-Time
---
