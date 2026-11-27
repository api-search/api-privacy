---
api_specs:
- filename: adsturbo-ai-adclone-api-openapi.yml
  format: yaml
  label: AdsTurbo Ad Clone API
  slug: adsturbo-ai-adclone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-adclone-api-openapi.yml
- filename: adsturbo-ai-adclone-v2beta-api-openapi.yml
  format: yaml
  label: AdsTurbo AdClone (v2beta) API
  slug: adsturbo-ai-adclone-v2beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-adclone-v2beta-api-openapi.yml
- filename: adsturbo-ai-aiactor-api-openapi.yml
  format: yaml
  label: AdsTurbo AI Actor API
  slug: adsturbo-ai-aiactor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-aiactor-api-openapi.yml
- filename: adsturbo-ai-image-api-openapi.yml
  format: yaml
  label: AdsTurbo Image API
  slug: adsturbo-ai-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-image-api-openapi.yml
- filename: adsturbo-ai-image-v2beta-api-openapi.yml
  format: yaml
  label: AdsTurbo Image (v2beta) API
  slug: adsturbo-ai-image-v2beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-image-v2beta-api-openapi.yml
- filename: adsturbo-ai-persona-api-openapi.yml
  format: yaml
  label: AdsTurbo Persona API
  slug: adsturbo-ai-persona-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-persona-api-openapi.yml
- filename: adsturbo-ai-video-api-openapi.yml
  format: yaml
  label: AdsTurbo Video API
  slug: adsturbo-ai-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-video-api-openapi.yml
- filename: adsturbo-ai-video-v2beta-api-openapi.yml
  format: yaml
  label: AdsTurbo Video (v2beta) API
  slug: adsturbo-ai-video-v2beta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-video-v2beta-api-openapi.yml
- filename: adsturbo-ai-work-api-openapi.yml
  format: yaml
  label: AdsTurbo Work API
  slug: adsturbo-ai-work-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adsturbo-ai/openapi/adsturbo-ai-work-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name (with consent only); Username and Password (for Account creation); Email Address (for communication and login)
  - category: financial
    text: Payment Information (processed securely by third-party payment providers)
  - category: device
    text: IP Address; Web Browser Type and Version; Operating System
  - category: behavioral
    text: A list of URLs starting with a referring site, your activity on our Site, and the site you exit to.
  - category: biometric
    text: 'Facial Feature Data: For features like Video Face Swap and AI Lip Sync, our AI models analyze facial features in your uploaded media to perform the requested edits.'
  - category: communication
    text: 'Audio and Voice Data: Voice recordings for features like AI Video Translation and Video Script Extraction.'
  deletion:
    route: Upon specific request or via library deletion
    text: Your data will be deleted if we no longer need it in accordance with our Data Retention Policy, or upon your specific request.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing and managing account
    text: Allowing access to the AdsTurbo dashboard.
  - purpose: Service fulfillment
    text: Processing your uploaded User Content to generate AI videos (e.g., rendering a "Face Swap" video or "Upscaling" a low-res clip).
  - purpose: Product improvement
    text: Analyzing usage patterns (e.g., which tools like Smart Highlight or Watermark Removal are used most) to improve our AI models and user interface.
  - purpose: Security
    text: Detecting and preventing fraudulent use of our tools.
  - purpose: Communication
    text: Responding to emails and supplying you with newsletters or alerts (you may unsubscribe at any time).
  retention:
  - period: null
    scope: User Content
    text: Original uploaded files and generated videos are stored on secure cloud servers to allow you to access your project history. You may delete these files from your library at any time.
  - period: null
    scope: general
    text: We only keep your data for as long as we need to use it as described above, or for as long as we have your permission to keep it.
  rights:
  - right: Access
    text: Ask for a copy of your personal data held by us.
  - right: Rectification
    text: Correct any inaccurate data.
  - right: Deletion
    text: Request deletion of your personal data and Account.
  - right: Restrict processing
    text: Limit how we use your data.
  - right: Data portability
    text: Obtain your data in a structured format.
  - right: Object
    text: Object to the processing of your data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We will NEVER sell your personal information or User Content to anyone.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AdsTurbo
provenance_date: '2026-11-09'
provider_name: AdsTurbo
provider_slug: adsturbo-ai
slug: adsturbo-ai-privacy-policy
source_date: '2026-11-09'
source_filename: adsturbo-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://adsturbo.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AdsTurbo\naid: adsturbo-ai\nurl: https://adsturbo.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name (with consent only); Username and Password (for Account creation); Email Address (for communication\n    and login)\n- category: financial\n  text: Payment Information (processed securely by third-party payment providers)\n- category: device\n  text: IP Address; Web Browser Type and Version; Operating System\n- category: behavioral\n  text: A list of URLs starting with a referring site, your activity on our Site, and\
  \ the site you exit to.\n- category: biometric\n  text: 'Facial Feature Data: For features like Video Face Swap and AI Lip Sync, our AI models analyze facial features\n    in your uploaded media to perform the requested edits.'\n- category: communication\n  text: 'Audio and Voice Data: Voice recordings for features like AI Video Translation and Video Script Extraction.'\npurposes:\n- purpose: Providing and managing account\n  text: Allowing access to the AdsTurbo dashboard.\n- purpose: Service fulfillment\n  text: Processing your uploaded User Content to generate AI videos (e.g., rendering a \"Face Swap\" video or \"Upscaling\"\n    a low-res clip).\n- purpose: Product improvement\n  text: Analyzing usage patterns (e.g., which tools like Smart Highlight or Watermark Removal are used most) to\n    improve our AI models and user interface.\n- purpose: Security\n  text: Detecting and preventing fraudulent use of our tools.\n- purpose: Communication\n  text: Responding to emails and supplying\
  \ you with newsletters or alerts (you may unsubscribe at any time).\nretention:\n- scope: User Content\n  period: null\n  text: Original uploaded files and generated videos are stored on secure cloud servers to allow you to access your\n    project history. You may delete these files from your library at any time.\n- scope: general\n  period: null\n  text: We only keep your data for as long as we need to use it as described above, or for as long as we have your\n    permission to keep it.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Upon specific request or via library deletion\n  text: Your data will be deleted if we no longer need it in accordance with our Data Retention Policy, or upon\n    your specific request.\nrights:\n- right: Access\n  text: Ask for a copy of your personal data held by us.\n- right: Rectification\n  text: Correct any inaccurate data.\n- right: Deletion\n  text:\
  \ Request deletion of your personal data and Account.\n- right: Restrict processing\n  text: Limit how we use your data.\n- right: Data portability\n  text: Obtain your data in a structured format.\n- right: Object\n  text: Object to the processing of your data.\nsale_or_sharing:\n  stance: prohibited\n  text: We will NEVER sell your personal information or User Content to anyone.\n"
source_yaml_url: https://artifacts.apis.io/adsturbo-ai/privacy/adsturbo-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from AdsTurbo's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Video Ads
- E-Commerce
- Marketing
- Automation
---
