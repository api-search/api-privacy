---
api_specs:
- filename: captions-audio-api-openapi.yml
  format: yaml
  label: Captions Audio API
  slug: captions-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captions/openapi/captions-audio-api-openapi.yml
- filename: captions-health-api-openapi.yml
  format: yaml
  label: Captions Health API
  slug: captions-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captions/openapi/captions-health-api-openapi.yml
- filename: captions-internal-api-openapi.yml
  format: yaml
  label: Captions Internal API
  slug: captions-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captions/openapi/captions-internal-api-openapi.yml
- filename: captions-meta-text-overlays-api-openapi.yml
  format: yaml
  label: Captions Meta Text Overlays API
  slug: captions-meta-text-overlays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captions/openapi/captions-meta-text-overlays-api-openapi.yml
- filename: captions-root-api-openapi.yml
  format: yaml
  label: Captions Root API
  slug: captions-root-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captions/openapi/captions-root-api-openapi.yml
- filename: captions-video-captions-api-openapi.yml
  format: yaml
  label: Captions Video Captions API
  slug: captions-video-captions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captions/openapi/captions-video-captions-api-openapi.yml
- filename: captions-videos-api-openapi.yml
  format: yaml
  label: Captions Videos API
  slug: captions-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captions/openapi/captions-videos-api-openapi.yml
- filename: captions-ai-ads-api-openapi.yml
  format: yaml
  label: Captions AI Ads API
  slug: captions-ai-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captions/openapi/captions-ai-ads-api-openapi.yml
- filename: captions-ai-creator-api-openapi.yml
  format: yaml
  label: Captions AI Creator API
  slug: captions-ai-creator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captions/openapi/captions-ai-creator-api-openapi.yml
- filename: captions-catalog-api-openapi.yml
  format: yaml
  label: Captions Catalog API
  slug: captions-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captions/openapi/captions-catalog-api-openapi.yml
- filename: captions-internal-fal-api-openapi.yml
  format: yaml
  label: Captions Internal Fal API
  slug: captions-internal-fal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captions/openapi/captions-internal-fal-api-openapi.yml
- filename: captions-videos-v2-api-openapi.yml
  format: yaml
  label: Captions Videos v2 API
  slug: captions-videos-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/captions/openapi/captions-videos-v2-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Contact Information, including name, phone number, email address, mailing address, and communication preferences.
  - category: biometric
    text: 'Biometric Information: To enable certain features, such as our augmented reality features and voice to text, we may generate biometric information from your face or voice.'
  - category: behavioral
    text: We may also track when and how frequently you access or use the Services, including how you engage with or navigate our websites or mobile applications.
  - category: location
    text: When you use the Services, we may collect your general geographic location based on IP address.
  - category: financial
    text: Financial information, in connection with payment for the Services.
  - category: communication
    text: 'Audio, Video, and Text Data: AI-generated transcriptions and captions, video corrections and edits'
  deletion:
    route: email request
    text: If you would like to exercise any of these rights, please submit a request by emailing us at [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: train AI/ML models
    text: including to train our artificial intelligence/machine learning models and for our augmented reality features.
  - purpose: third-party training
    text: we may also disclose your information collected through our platform to third parties for their own business and commercial purposes, including for the purpose of enhancing their services, training their algorithms, and marketing third-party products or services to users.
  - purpose: targeted advertising
    text: to assist in determining relevant advertising (both on and off the Services)
  retention:
  - period: as long as necessary
    scope: general
    text: We will retain your information for as long as necessary to provide the Services and for the other purposes set out in this Policy.
  - period: three years after your last interaction with Mirage
    scope: biometric identifiers and information
    text: We delete biometric identifiers and biometric information that we collect or obtain upon the earlier of (1) satisfaction of the initial purpose for collecting such identifiers or information; or (2) three years after your last interaction with Mirage
  rights:
  - right: access
    text: Provide access to and/or a copy of certain information we hold about you.
  - right: delete
    text: Delete certain information we have about you.
  - right: correct
    text: Correct inaccurate personal information that we maintain about you.
  - right: opt out of targeted advertising
    text: You may also have the right to opt out of the use of your information for targeted advertising.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We “share” information for these purposes to provide more relevant and tailored advertising to you regarding our Services.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: This includes signing Standard Contractual Clauses that govern the transfers of such data, which may be used in conjunction with additional safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Captions
provenance_date: '2026-11-09'
provider_name: Captions
provider_slug: captions
slug: captions-privacy-policy
source_date: '2026-11-09'
source_filename: captions-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mirage.app/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Captions\naid: captions\nurl: https://mirage.app/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Contact Information, including name, phone number, email address, mailing address, and communication preferences.\n- category: biometric\n  text: 'Biometric Information: To enable certain features, such as our augmented reality features and voice to\n    text, we may generate biometric information from your face or voice.'\n- category: behavioral\n  text: We may also track when and how frequently you access or use the Services,\
  \ including how you engage with\n    or navigate our websites or mobile applications.\n- category: location\n  text: When you use the Services, we may collect your general geographic location based on IP address.\n- category: financial\n  text: Financial information, in connection with payment for the Services.\n- category: communication\n  text: 'Audio, Video, and Text Data: AI-generated transcriptions and captions, video corrections and edits'\npurposes:\n- purpose: train AI/ML models\n  text: including to train our artificial intelligence/machine learning models and for our augmented reality features.\n- purpose: third-party training\n  text: we may also disclose your information collected through our platform to third parties for their own business\n    and commercial purposes, including for the purpose of enhancing their services, training their algorithms, and\n    marketing third-party products or services to users.\n- purpose: targeted advertising\n  text: to assist in determining\
  \ relevant advertising (both on and off the Services)\nretention:\n- scope: general\n  period: as long as necessary\n  text: We will retain your information for as long as necessary to provide the Services and for the other purposes\n    set out in this Policy.\n- scope: biometric identifiers and information\n  period: three years after your last interaction with Mirage\n  text: We delete biometric identifiers and biometric information that we collect or obtain upon the earlier of\n    (1) satisfaction of the initial purpose for collecting such identifiers or information; or (2) three years after\n    your last interaction with Mirage\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: This includes signing Standard Contractual Clauses that govern the transfers of such data, which may be\n    used in conjunction with additional safeguards.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: If you\
  \ would like to exercise any of these rights, please submit a request by emailing us at [email protected]\n    .\nrights:\n- right: access\n  text: Provide access to and/or a copy of certain information we hold about you.\n- right: delete\n  text: Delete certain information we have about you.\n- right: correct\n  text: Correct inaccurate personal information that we maintain about you.\n- right: opt out of targeted advertising\n  text: You may also have the right to opt out of the use of your information for targeted advertising.\nsale_or_sharing:\n  stance: conditional\n  text: We “share” information for these purposes to provide more relevant and tailored advertising to you regarding\n    our Services.\n"
source_yaml_url: https://artifacts.apis.io/captions/privacy/captions-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Captions's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Artificial Intelligence
- Video Editing
- Video Generation
- Captions
- Subtitles
- Text-to-Speech
- AI Avatars
- Content Creation
- Media
---
