---
api_specs:
- filename: civitai-blobs-api-openapi.yml
  format: yaml
  label: Civitai Blobs API
  slug: civitai-blobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-blobs-api-openapi.yml
- filename: civitai-creators-api-openapi.yml
  format: yaml
  label: Civitai Creators API
  slug: civitai-creators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-creators-api-openapi.yml
- filename: civitai-enums-api-openapi.yml
  format: yaml
  label: Civitai Enums API
  slug: civitai-enums-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-enums-api-openapi.yml
- filename: civitai-images-api-openapi.yml
  format: yaml
  label: Civitai Images API
  slug: civitai-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-images-api-openapi.yml
- filename: civitai-models-api-openapi.yml
  format: yaml
  label: Civitai Models API
  slug: civitai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-models-api-openapi.yml
- filename: civitai-permissions-api-openapi.yml
  format: yaml
  label: Civitai Permissions API
  slug: civitai-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-permissions-api-openapi.yml
- filename: civitai-tags-api-openapi.yml
  format: yaml
  label: Civitai Tags API
  slug: civitai-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-tags-api-openapi.yml
- filename: civitai-users-api-openapi.yml
  format: yaml
  label: Civitai Users API
  slug: civitai-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-users-api-openapi.yml
- filename: civitai-vault-api-openapi.yml
  format: yaml
  label: Civitai Vault API
  slug: civitai-vault-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-vault-api-openapi.yml
- filename: civitai-workflows-api-openapi.yml
  format: yaml
  label: Civitai Workflows API
  slug: civitai-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-workflows-api-openapi.yml
- filename: civitai-model-versions-api-openapi.yml
  format: yaml
  label: Civitai Model Versions API
  slug: civitai-model-versions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/civitai/openapi/civitai-model-versions-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: we ask you for information such as your email address
  - category: identifying
    text: If you sign up using a social media account, we will also receive information from those social media services such as your username and email address.
  - category: location
    text: we may infer your general location information, for example by using your internet protocol (IP) address
  - category: device
    text: We receive information about the device and software you use to access our Services, including IP address, web browser type, operating system version, phone carrier and manufacturer, application installations, device identifiers, mobile advertising identifiers, and push notification tokens.
  - category: behavioral
    text: we automatically receive information about your interactions with our Services, like the pages or other content you view, the searches you conduct, creators you follow, your comments, any content you post, and the dates and times of your visits
  - category: financial
    text: your payment-related information, such as credit card or other financial information, is collected by our third-party payment processor on our behalf
  - category: professional
    text: We will collect the information you choose to provide on your resume, such as your education and employment experience.
  deletion:
    route: account settings
    text: You may delete your account at any time from your account settings.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and improve services
    text: To provide, maintain, improve, and enhance our Services
  - purpose: personalization
    text: To personalize your experience on our Services such as by providing tailored content and recommendations
  - purpose: marketing and advertising
    text: For marketing and advertising purposes, such as developing and providing promotional and advertising materials that may be relevant, valuable or otherwise of interest to you
  - purpose: fraud and abuse prevention
    text: To find and prevent fraud and abuse, and respond to trust and safety issues that may arise
  - purpose: transactions and payments
    text: To facilitate transactions and payments
  residency:
  - region: United States
    text: Our Services are hosted in the United States (" U.S. ") and intended for visitors located within the U.S.
  retention:
  - period: null
    scope: account information after deletion
    text: We may retain certain information for legitimate business purposes or where we believe it is required by applicable law.
  rights:
  - right: access and deletion requests
    text: want to make a request about your personal information (such as access or deletion), please email us at [email protected]
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: we may also transfer your data from the U.S. to other countries or regions in connection with storage and processing of data
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Civitai
provenance_date: '2026-11-09'
provider_name: Civitai
provider_slug: civitai
slug: civitai-privacy-policy
source_date: '2026-11-09'
source_filename: civitai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://civitai.com/content/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Civitai\naid: civitai\nurl: https://civitai.com/content/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: we ask you for information such as your email address\n- category: identifying\n  text: If you sign up using a social media account, we will also receive information from those social media services\n    such as your username and email address.\n- category: location\n  text: we may infer your general location information, for example by using your internet protocol (IP) address\n- category: device\n  text: We receive information about\
  \ the device and software you use to access our Services, including IP address,\n    web browser type, operating system version, phone carrier and manufacturer, application installations, device\n    identifiers, mobile advertising identifiers, and push notification tokens.\n- category: behavioral\n  text: we automatically receive information about your interactions with our Services, like the pages or other\n    content you view, the searches you conduct, creators you follow, your comments, any content you post, and the\n    dates and times of your visits\n- category: financial\n  text: your payment-related information, such as credit card or other financial information, is collected by our\n    third-party payment processor on our behalf\n- category: professional\n  text: We will collect the information you choose to provide on your resume, such as your education and employment\n    experience.\npurposes:\n- purpose: provide and improve services\n  text: To provide, maintain, improve,\
  \ and enhance our Services\n- purpose: personalization\n  text: To personalize your experience on our Services such as by providing tailored content and recommendations\n- purpose: marketing and advertising\n  text: For marketing and advertising purposes, such as developing and providing promotional and advertising materials\n    that may be relevant, valuable or otherwise of interest to you\n- purpose: fraud and abuse prevention\n  text: To find and prevent fraud and abuse, and respond to trust and safety issues that may arise\n- purpose: transactions and payments\n  text: To facilitate transactions and payments\nretention:\n- scope: account information after deletion\n  period: null\n  text: We may retain certain information for legitimate business purposes or where we believe it is required by\n    applicable law.\nresidency:\n- region: United States\n  text: Our Services are hosted in the United States (\" U.S. \") and intended for visitors located within the U.S.\ntransfers:\n- mechanism:\
  \ other\n  text: we may also transfer your data from the U.S. to other countries or regions in connection with storage and\n    processing of data\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account settings\n  text: You may delete your account at any time from your account settings.\nrights:\n- right: access and deletion requests\n  text: want to make a request about your personal information (such as access or deletion), please email us at\n    [email protected]\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/civitai/privacy/civitai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 17 quoted statements, read from Civitai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Image Generation
- Video Generation
- Stable Diffusion
- SDXL
- Flux
- LoRA
- Model Hosting
- Community
- Generative AI
---
