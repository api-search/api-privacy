---
api_specs:
- filename: probabl-anthropic-compatible-agent-api-openapi.yml
  format: yaml
  label: Probabl Anthropic Compatible Agent API
  slug: probabl-anthropic-compatible-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/probabl/openapi/probabl-anthropic-compatible-agent-api-openapi.yml
- filename: probabl-health-api-openapi.yml
  format: yaml
  label: Probabl Health API
  slug: probabl-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/probabl/openapi/probabl-health-api-openapi.yml
- filename: probabl-identity-api-openapi.yml
  format: yaml
  label: Probabl Identity API
  slug: probabl-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/probabl/openapi/probabl-identity-api-openapi.yml
- filename: probabl-liveness-api-openapi.yml
  format: yaml
  label: Probabl Liveness API
  slug: probabl-liveness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/probabl/openapi/probabl-liveness-api-openapi.yml
- filename: probabl-llm-provider-api-openapi.yml
  format: yaml
  label: Probabl LLM Provider API
  slug: probabl-llm-provider-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/probabl/openapi/probabl-llm-provider-api-openapi.yml
- filename: probabl-openai-compatible-agent-api-openapi.yml
  format: yaml
  label: Probabl OpenAI Compatible Agent API
  slug: probabl-openai-compatible-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/probabl/openapi/probabl-openai-compatible-agent-api-openapi.yml
- filename: probabl-projects-api-openapi.yml
  format: yaml
  label: Probabl Projects API
  slug: probabl-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/probabl/openapi/probabl-projects-api-openapi.yml
- filename: probabl-readiness-api-openapi.yml
  format: yaml
  label: Probabl Readiness API
  slug: probabl-readiness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/probabl/openapi/probabl-readiness-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Website interactions may request: name, email, postal address, telephone number, social media profiles.'
  - category: professional
    text: your company name, job title, or business interest
  - category: device
    text: your IP address, language and operating system
  - category: behavioral
    text: Application performance and usage monitoring data during your interaction with skore hub.
  - category: identifying
    text: 'User Identity Information: Authentication data via ORY partner.'
  - category: communication
    text: Information you provide to us in regular interviews and/or video interviews.
  deletion:
    route: Account deletion request
    text: When you choose to delete your account, we will delete all your Personal Data from the Product feedback service.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Enhance and provide products and services
    text: Enhance and provide Products and Services.
  - purpose: Communication and marketing
    text: Communicate, including marketing and customer support.
  - purpose: Process job applications
    text: Process job applications.
  - purpose: Analyze website usage
    text: Analyze website usage.
  - purpose: Product improvement
    text: Improve our products and services through usage analytics.
  residency:
  - region: European Union
    text: Skore Hub is hosted at AWS data center in Paris, France.
  retention:
  - period: 1 year of inactivity
    scope: Marketing information
    text: Retained as long as you are an active website visitor, or for a period of 1 year of inactivity.
  - period: 1 year of inactivity
    scope: Online recruitment information
    text: Retained as long as you are active, have an ongoing purpose, or for a period of 1 year of inactivity.
  - period: 90 days
    scope: Skore user data
    text: If you do not use your tenant for 90 days following the end of the Trial Period, all your User Data will be deleted.
  - period: 90 days
    scope: System logs
    text: System logs are automatically expired and removed after 90 days.
  rights:
  - right: Access
    text: You have the right to request Probabl for copies of your Personal Data.
  - right: Rectification
    text: You have the right to request that Probabl corrects any information you believe is inaccurate.
  - right: Restrict processing
    text: You have the right to request that Probabl restricts the processing of your Personal Data.
  - right: Erasure
    text: You have the right to request that Probabl erases your Personal Data, under certain conditions.
  - right: Object to processing
    text: You have the right to object to Probabl’s processing of your Personal Data, under certain conditions.
  - right: Data portability
    text: You have the right to request that Probabl transfer the data that we have collected to another organization, or directly to you, under certain conditions.
  role:
    text: Probabl is the Data Controller.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Third-party service providers receive Personal Data for website, product, and service support.
    url: null
  transfers:
  - mechanism: other
    text: We ensure that such transfers comply with applicable data protection laws, including the GDPR.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Probabl
provenance_date: '2026-11-10'
provider_name: Probabl
provider_slug: probabl
slug: probabl-privacy-policy
source_date: '2026-11-10'
source_filename: probabl-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.probabl.ai/legal/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Probabl\naid: probabl\nurl: https://www.probabl.ai/legal/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Probabl is the Data Controller.\ndata_categories:\n- category: contact\n  text: 'Website interactions may request: name, email, postal address, telephone number, social media profiles.'\n- category: professional\n  text: your company name, job title, or business interest\n- category: device\n  text: your IP address, language and operating system\n- category: behavioral\n  text: Application performance and usage monitoring data during your interaction with skore hub.\n- category:\
  \ identifying\n  text: 'User Identity Information: Authentication data via ORY partner.'\n- category: communication\n  text: Information you provide to us in regular interviews and/or video interviews.\npurposes:\n- purpose: Enhance and provide products and services\n  text: Enhance and provide Products and Services.\n- purpose: Communication and marketing\n  text: Communicate, including marketing and customer support.\n- purpose: Process job applications\n  text: Process job applications.\n- purpose: Analyze website usage\n  text: Analyze website usage.\n- purpose: Product improvement\n  text: Improve our products and services through usage analytics.\nretention:\n- scope: Marketing information\n  period: 1 year of inactivity\n  text: Retained as long as you are an active website visitor, or for a period of 1 year of inactivity.\n- scope: Online recruitment information\n  period: 1 year of inactivity\n  text: Retained as long as you are active, have an ongoing purpose, or for a period\
  \ of 1 year of inactivity.\n- scope: Skore user data\n  period: 90 days\n  text: If you do not use your tenant for 90 days following the end of the Trial Period, all your User Data will\n    be deleted.\n- scope: System logs\n  period: 90 days\n  text: System logs are automatically expired and removed after 90 days.\nresidency:\n- region: European Union\n  text: Skore Hub is hosted at AWS data center in Paris, France.\ntransfers:\n- mechanism: other\n  text: We ensure that such transfers comply with applicable data protection laws, including the GDPR.\nsubprocessors:\n  url: null\n  text: Third-party service providers receive Personal Data for website, product, and service support.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion request\n  text: When you choose to delete your account, we will delete all your Personal Data from the Product feedback\n    service.\nrights:\n- right: Access\n  text: You have the right to request Probabl for copies\
  \ of your Personal Data.\n- right: Rectification\n  text: You have the right to request that Probabl corrects any information you believe is inaccurate.\n- right: Restrict processing\n  text: You have the right to request that Probabl restricts the processing of your Personal Data.\n- right: Erasure\n  text: You have the right to request that Probabl erases your Personal Data, under certain conditions.\n- right: Object to processing\n  text: You have the right to object to Probabl’s processing of your Personal Data, under certain conditions.\n- right: Data portability\n  text: You have the right to request that Probabl transfer the data that we have collected to another organization,\n    or directly to you, under certain conditions.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/probabl/privacy/probabl-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Probabl's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Open Source
- Machine Learning
- Data Science
- scikit-learn
- MLOps
- Model Evaluation
- Experiment Tracking
- Agent Skills
- Artificial Intelligence
- Python
- France
---
