---
api_specs:
- filename: gptzero-batch-api-openapi.yml
  format: yaml
  label: GPTZero Batch API
  slug: gptzero-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gptzero/openapi/gptzero-batch-api-openapi.yml
- filename: gptzero-detection-api-openapi.yml
  format: yaml
  label: GPTZero Detection API
  slug: gptzero-detection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gptzero/openapi/gptzero-detection-api-openapi.yml
- filename: gptzero-documents-api-openapi.yml
  format: yaml
  label: GPTZero Documents API
  slug: gptzero-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/gptzero/openapi/gptzero-documents-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: names phone numbers email addresses job titles passwords usernames
  - category: financial
    text: debit/credit card numbers
  - category: device
    text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device you use to access the Services.
  - category: location
    text: Location Data. We collect location data such as information about your device's location, which can be either precise or imprecise.
  - category: behavioral
    text: information about how and when you use our Services
  - category: communication
    text: submitted content for use of providing our services
  deletion:
    route: Account termination request or data subject access request
    text: Upon your request to terminate your account, we will deactivate or delete your account and information from our active databases.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and administer services
    text: We process your information to provide, improve, and administer our Services, communicate with you, for security and fraud prevention, and to comply with law.
  - purpose: Targeted advertising
    text: To deliver targeted advertising to you. We may process your information to develop and display personalized content and advertising tailored to your interests, location, and more.
  - purpose: Identify usage trends
    text: To identify usage trends. We may process information about how you use our Services to better understand how they are being used so we can improve them.
  residency:
  - region: United States
    text: Our servers are located in the United States .
  retention:
  - period: three (3) months
    scope: Post-account termination
    text: No purpose in this notice will require us keeping your personal information for longer than three (3) months past the termination of the user's account .
  rights:
  - right: Access
    text: to request access and obtain a copy of your personal information
  - right: Rectification or erasure
    text: to request rectification or erasure
  - right: Restrict processing
    text: to restrict the processing of your personal information
  - right: Data portability
    text: if applicable, to data portability
  role:
    text: We are responsible for making decisions about how your personal information is processed.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: We have not sold or shared any personal information to third parties for a business or commercial purpose in the preceding twelve (12) months.
  subprocessors:
    text: We provide the AI Products through third-party service providers ( " AI Service Providers " ), including Anthropic , Baseten , Cerebras , Cohere , Databricks , Fireworks , Google Cloud AI , Groq , Hugging Face , Microsoft Azure AI , Mistral AI , OpenAI , Perplexity and Modal .
    url: null
  transfers:
  - mechanism: SCC
    text: We have implemented measures to protect your personal information, including by using the European Commission's Standard Contractual Clauses for transfers of personal information between our group companies and between us and our third-party providers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: GPTZero
provenance_date: '2026-11-09'
provider_name: GPTZero
provider_slug: gptzero
slug: gptzero-privacy-policy
source_date: '2026-11-09'
source_filename: gptzero-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://gptzero.me/privacy-policy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: GPTZero\naid: gptzero\nurl: https://gptzero.me/privacy-policy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are responsible for making decisions about how your personal information is processed.\ndata_categories:\n- category: identifying\n  text: names phone numbers email addresses job titles passwords usernames\n- category: financial\n  text: debit/credit card numbers\n- category: device\n  text: Device Data. We collect device data such as information about your computer, phone, tablet, or other device\n    you use to access the Services.\n- category: location\n  text: Location Data.\
  \ We collect location data such as information about your device's location, which can be either\n    precise or imprecise.\n- category: behavioral\n  text: information about how and when you use our Services\n- category: communication\n  text: submitted content for use of providing our services\npurposes:\n- purpose: Provide and administer services\n  text: We process your information to provide, improve, and administer our Services, communicate with you, for\n    security and fraud prevention, and to comply with law.\n- purpose: Targeted advertising\n  text: To deliver targeted advertising to you. We may process your information to develop and display personalized\n    content and advertising tailored to your interests, location, and more.\n- purpose: Identify usage trends\n  text: To identify usage trends. We may process information about how you use our Services to better understand\n    how they are being used so we can improve them.\nretention:\n- scope: Post-account termination\n\
  \  period: three (3) months\n  text: No purpose in this notice will require us keeping your personal information for longer than three (3) months\n    past the termination of the user's account .\nresidency:\n- region: United States\n  text: Our servers are located in the United States .\ntransfers:\n- mechanism: SCC\n  text: We have implemented measures to protect your personal information, including by using the European Commission's\n    Standard Contractual Clauses for transfers of personal information between our group companies and between us\n    and our third-party providers.\nsubprocessors:\n  url: null\n  text: We provide the AI Products through third-party service providers ( \" AI Service Providers \" ), including\n    Anthropic , Baseten , Cerebras , Cohere , Databricks , Fireworks , Google Cloud AI , Groq , Hugging Face , Microsoft\n    Azure AI , Mistral AI , OpenAI , Perplexity and Modal .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account\
  \ termination request or data subject access request\n  text: Upon your request to terminate your account, we will deactivate or delete your account and information from\n    our active databases.\nrights:\n- right: Access\n  text: to request access and obtain a copy of your personal information\n- right: Rectification or erasure\n  text: to request rectification or erasure\n- right: Restrict processing\n  text: to restrict the processing of your personal information\n- right: Data portability\n  text: if applicable, to data portability\nsale_or_sharing:\n  stance: unstated\n  text: We have not sold or shared any personal information to third parties for a business or commercial purpose\n    in the preceding twelve (12) months.\n"
source_yaml_url: https://artifacts.apis.io/gptzero/privacy/gptzero-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 19 quoted statements, read from GPTZero's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Detection
- Content Moderation
- Machine Learning
- Text Analysis
- Natural Language Processing
- Education
---
