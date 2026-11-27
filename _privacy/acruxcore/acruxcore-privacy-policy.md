---
api_specs:
- filename: acruxcore-account-api-openapi.yml
  format: yaml
  label: Acrux Core Account API
  slug: acruxcore-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acruxcore/openapi/acruxcore-account-api-openapi.yml
- filename: acruxcore-acrux-core-api-api-openapi.yml
  format: yaml
  label: Acrux Core Acrux Core API
  slug: acruxcore-acrux-core-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acruxcore/openapi/acruxcore-acrux-core-api-api-openapi.yml
- filename: acruxcore-prompts-api-openapi.yml
  format: yaml
  label: Acrux Core Prompts API
  slug: acruxcore-prompts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acruxcore/openapi/acruxcore-prompts-api-openapi.yml
- filename: acruxcore-tools-api-openapi.yml
  format: yaml
  label: Acrux Core Tools API
  slug: acruxcore-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acruxcore/openapi/acruxcore-tools-api-openapi.yml
- filename: acruxcore-traces-api-openapi.yml
  format: yaml
  label: Acrux Core Traces API
  slug: acruxcore-traces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/acruxcore/openapi/acruxcore-traces-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information — your name, email address, team details, and authentication data when you sign up.
  - category: other
    text: Content you send to the platform — prompts, tool definitions, API keys you create, and provider credentials you connect.
  - category: other
    text: Operational data — trace metadata such as model, token counts, latency, and cost for calls routed through the gateway.
  - category: device
    text: Usage and device data — log data, IP address, and basic analytics needed to operate and secure the service.
  deletion:
    route: delete resources or account
    text: Deleting your account removes associated data, subject to backups and legal requirements.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and improve platform
    text: To provide, maintain, and improve the platform.
  - purpose: authenticate and enforce access
    text: To authenticate users and enforce team-level access.
  - purpose: route, price, and record calls
    text: To route, price, and record the model calls you send through the gateway.
  - purpose: abuse monitoring and security
    text: To monitor for abuse, secure the service, and meet legal obligations.
  retention:
  - period: 90 days
    scope: traced call input and output
    text: On the hosted service, we delete the input and output content of traced calls after 90 days.
  - period: while your account is active
    scope: account and content data
    text: We keep account and content data while your account is active and as long as we need it to provide the service.
  - period: within 15 minutes after that time ends
    scope: cached model responses
    text: We delete the response within 15 minutes after that time ends, or earlier if you clear the cache.
  rights:
  - right: access, correct, export, or delete
    text: you may have the right to access, correct, export, or delete your personal information
  role:
    text: For the hosted service, AcruxCore is the controller of the personal data described below.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Acrux Core
provenance_date: '2026-11-09'
provider_name: Acrux Core
provider_slug: acruxcore
slug: acruxcore-privacy-policy
source_date: '2026-11-09'
source_filename: acruxcore-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://acruxcore.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Acrux Core\naid: acruxcore\nurl: https://acruxcore.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: For the hosted service, AcruxCore is the controller of the personal data described below.\ndata_categories:\n- category: identifying\n  text: Account information — your name, email address, team details, and authentication data when you sign up.\n- category: other\n  text: Content you send to the platform — prompts, tool definitions, API keys you create, and provider credentials\n    you connect.\n- category: other\n  text: Operational data — trace metadata such as model, token counts,\
  \ latency, and cost for calls routed through\n    the gateway.\n- category: device\n  text: Usage and device data — log data, IP address, and basic analytics needed to operate and secure the service.\npurposes:\n- purpose: provide and improve platform\n  text: To provide, maintain, and improve the platform.\n- purpose: authenticate and enforce access\n  text: To authenticate users and enforce team-level access.\n- purpose: route, price, and record calls\n  text: To route, price, and record the model calls you send through the gateway.\n- purpose: abuse monitoring and security\n  text: To monitor for abuse, secure the service, and meet legal obligations.\nretention:\n- scope: traced call input and output\n  period: 90 days\n  text: On the hosted service, we delete the input and output content of traced calls after 90 days.\n- scope: account and content data\n  period: while your account is active\n  text: We keep account and content data while your account is active and as long as we need\
  \ it to provide the service.\n- scope: cached model responses\n  period: within 15 minutes after that time ends\n  text: We delete the response within 15 minutes after that time ends, or earlier if you clear the cache.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete resources or account\n  text: Deleting your account removes associated data, subject to backups and legal requirements.\nrights:\n- right: access, correct, export, or delete\n  text: you may have the right to access, correct, export, or delete your personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/acruxcore/privacy/acruxcore-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from Acrux Core's own page on 2026-11-09.
synthetic: false
tags:
- LLMOps
- Open Source
- Platform
- Engineering
- Artificial Intelligence
---
