---
api_specs:
- filename: cuein-answers-api-openapi.yml
  format: yaml
  label: Cuein Answers API
  slug: cuein-answers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cuein/openapi/cuein-answers-api-openapi.yml
- filename: cuein-conversations-api-openapi.yml
  format: yaml
  label: Cuein Conversations API
  slug: cuein-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cuein/openapi/cuein-conversations-api-openapi.yml
claim_count: 4
description: ''
doc:
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide requested service
    text: We only ask for personal information when we truly need it to provide a service to you.
  retention:
  - period: null
    scope: Collected information
    text: We only retain collected information for as long as necessary to provide you with your requested service.
  role:
    text: It is Cuein Inc.'s policy to respect your privacy regarding any information we may collect from you through our app, Cuein.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don't share any personally identifying information publicly or with third-parties, except when required to by law.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cuein
provenance_date: '2026-11-09'
provider_name: Cuein
provider_slug: cuein
slug: cuein-privacy-policy
source_date: '2026-11-09'
source_filename: cuein-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cuein.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cuein\naid: cuein\nurl: https://cuein.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: It is Cuein Inc.'s policy to respect your privacy regarding any information we may collect from you through\n    our app, Cuein.\ndata_categories: []\npurposes:\n- purpose: Provide requested service\n  text: We only ask for personal information when we truly need it to provide a service to you.\nretention:\n- scope: Collected information\n  period: null\n  text: We only retain collected information for as long as necessary to provide you with your requested service.\nresidency: []\ntransfers: []\n\
  subprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We don't share any personally identifying information publicly or with third-parties, except when required\n    to by law.\n"
source_yaml_url: https://artifacts.apis.io/cuein/privacy/cuein-privacy-policy.yml
stated_fields:
- role
- purposes
- retention
- sale_or_sharing
summary_line: 4 quoted statements, read from Cuein's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Experience
- Customer Service
- Conversation Intelligence
- Generative AI
- Insights
- Knowledge Base
- Contact Center
---
