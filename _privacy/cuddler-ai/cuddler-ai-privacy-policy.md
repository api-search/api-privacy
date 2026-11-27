---
api_specs:
- filename: cuddler-ai-platform-api-api-openapi.yml
  format: yaml
  label: Cuddler Platform API
  slug: cuddler-ai-platform-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cuddler-ai/openapi/cuddler-ai-platform-api-api-openapi.yml
- filename: cuddler-ai-platform-ark-api-openapi.yml
  format: yaml
  label: Cuddler Platform Ark API
  slug: cuddler-ai-platform-ark-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cuddler-ai/openapi/cuddler-ai-platform-ark-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, and profile picture when you register via Google, Apple, or email.
  - category: financial
    text: We may receive transaction status, order identifiers, subscription plan, and expiration information, but we do not directly store complete payment card or bank account details.
  - category: communication
    text: 'Voice Data: Audio samples you upload for voice cloning, recordings you make for voice input, and microphone audio you provide when using voice-call features.'
  - category: device
    text: Browser type, operating system, device type, and screen resolution.
  - category: location
    text: 'IP Address: Used for security, fraud prevention, and approximate geolocation.'
  - category: behavioral
    text: 'Usage Data: Pages visited, features used, chat interactions, and session duration.'
  deletion:
    route: Delete your account or content in the app; contact privacy email
    text: Request deletion of your account and associated data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain, and improve the Service
    text: Provide, maintain, and improve the Service
  - purpose: Generate AI responses and content
    text: Generate AI responses and content based on your inputs
  - purpose: Fraud and security
    text: Detect and prevent fraud, abuse, and security threats
  - purpose: Advertising measurement
    text: Measure and improve the performance of our own advertising campaigns, including by sharing conversion events with Google Ads and X as described in Section 5
  residency:
  - region: United States, China and other countries
    text: Your data may be processed in the United States, China and other countries where we or our service providers operate.
  retention:
  - period: null
    scope: Account data
    text: Account data is retained while your account is active.
  - period: 90 days
    scope: Ad click identifiers and session attributes
    text: Ad click identifiers and session attributes are deleted 90 days after the click.
  - period: null
    scope: Replaced AI reply versions
    text: Replaced versions are deleted together with the conversation when you delete it, and with the rest of your content when you close your account.
  rights:
  - right: Access
    text: 'Access: Request a copy of your personal data.'
  - right: Correction
    text: 'Correction: Update inaccurate personal information.'
  - right: Deletion
    text: 'Deletion: Request deletion of your account and associated data.'
  - right: Portability
    text: 'Portability: Export your data in a machine-readable format.'
  - right: Objection
    text: 'Object: Object to processing of your data for certain purposes.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We ensure appropriate safeguards are in place for cross-border transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cuddler
provenance_date: '2026-11-09'
provider_name: Cuddler
provider_slug: cuddler-ai
slug: cuddler-ai-privacy-policy
source_date: '2026-11-09'
source_filename: cuddler-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cuddler.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cuddler\naid: cuddler-ai\nurl: https://cuddler.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, email address, and profile picture when you register via Google, Apple, or email.\n- category: financial\n  text: We may receive transaction status, order identifiers, subscription plan, and expiration information, but\n    we do not directly store complete payment card or bank account details.\n- category: communication\n  text: 'Voice Data: Audio samples you upload for voice cloning, recordings you make for voice input, and\
  \ microphone\n    audio you provide when using voice-call features.'\n- category: device\n  text: Browser type, operating system, device type, and screen resolution.\n- category: location\n  text: 'IP Address: Used for security, fraud prevention, and approximate geolocation.'\n- category: behavioral\n  text: 'Usage Data: Pages visited, features used, chat interactions, and session duration.'\npurposes:\n- purpose: Provide, maintain, and improve the Service\n  text: Provide, maintain, and improve the Service\n- purpose: Generate AI responses and content\n  text: Generate AI responses and content based on your inputs\n- purpose: Fraud and security\n  text: Detect and prevent fraud, abuse, and security threats\n- purpose: Advertising measurement\n  text: Measure and improve the performance of our own advertising campaigns, including by sharing conversion events\n    with Google Ads and X as described in Section 5\nretention:\n- scope: Account data\n  period: null\n  text: Account data is\
  \ retained while your account is active.\n- scope: Ad click identifiers and session attributes\n  period: 90 days\n  text: Ad click identifiers and session attributes are deleted 90 days after the click.\n- scope: Replaced AI reply versions\n  period: null\n  text: Replaced versions are deleted together with the conversation when you delete it, and with the rest of your\n    content when you close your account.\nresidency:\n- region: United States, China and other countries\n  text: Your data may be processed in the United States, China and other countries where we or our service providers\n    operate.\ntransfers:\n- mechanism: other\n  text: We ensure appropriate safeguards are in place for cross-border transfers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account or content in the app; contact privacy email\n  text: Request deletion of your account and associated data.\nrights:\n- right: Access\n  text:\
  \ 'Access: Request a copy of your personal data.'\n- right: Correction\n  text: 'Correction: Update inaccurate personal information.'\n- right: Deletion\n  text: 'Deletion: Request deletion of your account and associated data.'\n- right: Portability\n  text: 'Portability: Export your data in a machine-readable format.'\n- right: Objection\n  text: 'Object: Object to processing of your data for certain purposes.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/cuddler-ai/privacy/cuddler-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Cuddler's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video Generation
- Image Generation
- Interactive Storytelling
- Generative Media
- MCP
---
