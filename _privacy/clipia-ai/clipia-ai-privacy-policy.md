---
api_specs:
- filename: clipia-ai-account-api-openapi.yml
  format: yaml
  label: Clipia.ai Account API
  slug: clipia-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipia-ai/openapi/clipia-ai-account-api-openapi.yml
- filename: clipia-ai-llm-api-openapi.yml
  format: yaml
  label: Clipia.ai LLM API
  slug: clipia-ai-llm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipia-ai/openapi/clipia-ai-llm-api-openapi.yml
- filename: clipia-ai-models-api-openapi.yml
  format: yaml
  label: Clipia.ai Models API
  slug: clipia-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipia-ai/openapi/clipia-ai-models-api-openapi.yml
- filename: clipia-ai-queue-api-openapi.yml
  format: yaml
  label: Clipia.ai Queue API
  slug: clipia-ai-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipia-ai/openapi/clipia-ai-queue-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email and name during registration
  - category: financial
    text: Payment information (processed through secure payment systems)
  - category: device
    text: Device and browser information
  - category: behavioral
    text: Service usage statistics
  - category: communication
    text: Support requests and related correspondence
  - category: other
    text: Text prompts for generation
  - category: other
    text: Uploaded images and videos
  deletion:
    route: Account deletion; requests to privacy@clipia.ai or dpo@clipia.ai
    text: Send your request to privacy@clipia.ai or dpo@clipia.ai .
  dpa:
    available: null
    text: under a data processing agreement that requires appropriate safeguards
    url: null
  purposes:
  - purpose: Providing and improving the Service
    text: Providing and improving the Service
  - purpose: Processing payments
    text: Processing payments
  - purpose: Content moderation and security
    text: Content moderation and security
  - purpose: Personalizing user experience
    text: Personalizing user experience
  - purpose: Communicating with users
    text: Communicating with users
  - purpose: Complying with legal requirements
    text: Complying with legal requirements
  residency:
  - region: Russian Federation
    text: Personal data is processed and stored using infrastructure operated by our service provider located in the Russian Federation
  retention:
  - period: Until account deletion + 30 days
    scope: Account data
    text: Account data Until account deletion + 30 days
  - period: 15 days
    scope: Web server logs
    text: Web server logs — 15 days
  - period: 90 days
    scope: Moderation logs
    text: Moderation logs 90 days (critical — 7 years)
  - period: 90 days
    scope: API request log
    text: API request log 90 days; older records are removed by an automatic daily cleanup
  - period: No more than 1 year
    scope: Administrator action log
    text: Administrator action log No more than 1 year; older records are removed by an automatic daily cleanup
  - period: 14 days
    scope: Database backups
    text: scheduled copies are deleted automatically no later than 14 days after creation
  rights:
  - right: Right to know / access
    text: Right to know / access — request the categories and specific pieces of personal information we have collected
  - right: Right to delete
    text: Right to delete — request deletion of the personal information we collected from you, subject to legal exceptions
  - right: Right to correct
    text: Right to correct — request correction of inaccurate personal information
  - right: Right to opt out of sale or sharing
    text: Right to opt out of sale or sharing — direct us not to sell or share your personal information.
  - right: Right to data portability
    text: Right to data portability — receive a copy of your personal information in a portable, machine-readable format
  - right: Right to non-discrimination
    text: Right to non-discrimination — we will not discriminate against you for exercising any of your privacy rights
  role:
    text: Clipia.ai is a service operated by Clipia LLC, a Wyoming (USA) limited liability company ("we," "our," "the Company"), which acts as the controller of your personal data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and do not disseminate it to an indefinite group of persons
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: some disclosures involve the international transfer of personal information
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Clipia.ai
provenance_date: '2026-11-09'
provider_name: Clipia.ai
provider_slug: clipia-ai
slug: clipia-ai-privacy-policy
source_date: '2026-11-09'
source_filename: clipia-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://clipia.ai/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Clipia.ai\naid: clipia-ai\nurl: https://clipia.ai/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Clipia.ai is a service operated by Clipia LLC, a Wyoming (USA) limited liability company (\"we,\" \"our,\" \"the\n    Company\"), which acts as the controller of your personal data.\ndata_categories:\n- category: identifying\n  text: Email and name during registration\n- category: financial\n  text: Payment information (processed through secure payment systems)\n- category: device\n  text: Device and browser information\n- category: behavioral\n  text: Service usage statistics\n- category:\
  \ communication\n  text: Support requests and related correspondence\n- category: other\n  text: Text prompts for generation\n- category: other\n  text: Uploaded images and videos\npurposes:\n- purpose: Providing and improving the Service\n  text: Providing and improving the Service\n- purpose: Processing payments\n  text: Processing payments\n- purpose: Content moderation and security\n  text: Content moderation and security\n- purpose: Personalizing user experience\n  text: Personalizing user experience\n- purpose: Communicating with users\n  text: Communicating with users\n- purpose: Complying with legal requirements\n  text: Complying with legal requirements\nretention:\n- scope: Account data\n  period: Until account deletion + 30 days\n  text: Account data Until account deletion + 30 days\n- scope: Web server logs\n  period: 15 days\n  text: Web server logs — 15 days\n- scope: Moderation logs\n  period: 90 days\n  text: Moderation logs 90 days (critical — 7 years)\n- scope: API request\
  \ log\n  period: 90 days\n  text: API request log 90 days; older records are removed by an automatic daily cleanup\n- scope: Administrator action log\n  period: No more than 1 year\n  text: Administrator action log No more than 1 year; older records are removed by an automatic daily cleanup\n- scope: Database backups\n  period: 14 days\n  text: scheduled copies are deleted automatically no later than 14 days after creation\nresidency:\n- region: Russian Federation\n  text: Personal data is processed and stored using infrastructure operated by our service provider located in the\n    Russian Federation\ntransfers:\n- mechanism: other\n  text: some disclosures involve the international transfer of personal information\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: under a data processing agreement that requires appropriate safeguards\ndeletion:\n  route: Account deletion; requests to privacy@clipia.ai or dpo@clipia.ai\n  text: Send your request\
  \ to privacy@clipia.ai or dpo@clipia.ai .\nrights:\n- right: Right to know / access\n  text: Right to know / access — request the categories and specific pieces of personal information we have collected\n- right: Right to delete\n  text: Right to delete — request deletion of the personal information we collected from you, subject to legal exceptions\n- right: Right to correct\n  text: Right to correct — request correction of inaccurate personal information\n- right: Right to opt out of sale or sharing\n  text: Right to opt out of sale or sharing — direct us not to sell or share your personal information.\n- right: Right to data portability\n  text: Right to data portability — receive a copy of your personal information in a portable, machine-readable\n    format\n- right: Right to non-discrimination\n  text: Right to non-discrimination — we will not discriminate against you for exercising any of your privacy rights\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal\
  \ data and do not disseminate it to an indefinite group of persons\n"
source_yaml_url: https://artifacts.apis.io/clipia-ai/privacy/clipia-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 31 quoted statements, read from Clipia.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video Generation
- Image Generation
- Generative AI
- Model Context Protocol
- Text To Video
---
