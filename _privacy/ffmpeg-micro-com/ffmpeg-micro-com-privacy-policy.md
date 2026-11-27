---
api_specs:
- filename: ffmpeg-micro-com-blueprints-api-openapi.yml
  format: yaml
  label: ffmpeg-micro-com Blueprints API
  slug: ffmpeg-micro-com-blueprints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ffmpeg-micro-com/openapi/ffmpeg-micro-com-blueprints-api-openapi.yml
- filename: ffmpeg-micro-com-ffprobe-api-openapi.yml
  format: yaml
  label: ffmpeg-micro-com Ffprobe API
  slug: ffmpeg-micro-com-ffprobe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ffmpeg-micro-com/openapi/ffmpeg-micro-com-ffprobe-api-openapi.yml
- filename: ffmpeg-micro-com-generate-api-openapi.yml
  format: yaml
  label: ffmpeg-micro-com Generate API
  slug: ffmpeg-micro-com-generate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ffmpeg-micro-com/openapi/ffmpeg-micro-com-generate-api-openapi.yml
- filename: ffmpeg-micro-com-transcodes-api-openapi.yml
  format: yaml
  label: ffmpeg-micro-com Transcodes API
  slug: ffmpeg-micro-com-transcodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ffmpeg-micro-com/openapi/ffmpeg-micro-com-transcodes-api-openapi.yml
- filename: ffmpeg-micro-com-transcribe-api-openapi.yml
  format: yaml
  label: ffmpeg-micro-com Transcribe API
  slug: ffmpeg-micro-com-transcribe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ffmpeg-micro-com/openapi/ffmpeg-micro-com-transcribe-api-openapi.yml
- filename: ffmpeg-micro-com-transcribes-api-openapi.yml
  format: yaml
  label: ffmpeg-micro-com Transcribes API
  slug: ffmpeg-micro-com-transcribes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ffmpeg-micro-com/openapi/ffmpeg-micro-com-transcribes-api-openapi.yml
- filename: ffmpeg-micro-com-upload-api-openapi.yml
  format: yaml
  label: ffmpeg-micro-com Upload API
  slug: ffmpeg-micro-com-upload-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ffmpeg-micro-com/openapi/ffmpeg-micro-com-upload-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: name, email, and password when you sign up.'
  - category: financial
    text: 'Billing information: payment details provided to Stripe when subscribing to a paid plan.'
  - category: behavioral
    text: 'Usage data: API calls, timestamps, IP addresses, and performance metrics to monitor abuse and service health.'
  - category: other
    text: 'Media files: uploaded input files and generated output files, stored temporarily for processing.'
  deletion:
    route: Request deletion by contacting javid@ffmpeg-micro.com
    text: You can request deletion of your account and associated data at any time by contacting us at javid@ffmpeg-micro.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve service
    text: Provide, maintain, and improve our Service
  - purpose: Process payments
    text: Process payments and manage subscriptions
  - purpose: Customer support
    text: Respond to customer support requests
  - purpose: Abuse prevention
    text: Monitor usage and prevent abuse
  - purpose: Service emails
    text: Send important service-related emails
  retention:
  - period: 7 days
    scope: Input media files
    text: Input files are automatically deleted after 7 days
  - period: 30 days
    scope: Output media files
    text: output files after 30 days
  - period: null
    scope: Account and billing data
    text: We retain account and billing data as long as your account is active or as required by law.
  rights:
  - right: Access, correction, deletion
    text: you may have rights to access, correct, or delete your personal data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent personal data to any third parties.
  subprocessors:
    text: 'We use trusted third-party providers to operate our Service: Vercel for hosting our website and API Supabase for database and authentication Stripe for billing and payments Resend for transactional and support emails'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ffmpeg-micro-com
provenance_date: '2026-11-09'
provider_name: ffmpeg-micro-com
provider_slug: ffmpeg-micro-com
slug: ffmpeg-micro-com-privacy-policy
source_date: '2026-11-09'
source_filename: ffmpeg-micro-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.ffmpeg-micro.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ffmpeg-micro-com\naid: ffmpeg-micro-com\nurl: https://www.ffmpeg-micro.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account information: name, email, and password when you sign up.'\n- category: financial\n  text: 'Billing information: payment details provided to Stripe when subscribing to a paid plan.'\n- category: behavioral\n  text: 'Usage data: API calls, timestamps, IP addresses, and performance metrics to monitor abuse and service health.'\n- category: other\n  text: 'Media files: uploaded input files and generated\
  \ output files, stored temporarily for processing.'\npurposes:\n- purpose: Provide and improve service\n  text: Provide, maintain, and improve our Service\n- purpose: Process payments\n  text: Process payments and manage subscriptions\n- purpose: Customer support\n  text: Respond to customer support requests\n- purpose: Abuse prevention\n  text: Monitor usage and prevent abuse\n- purpose: Service emails\n  text: Send important service-related emails\nretention:\n- scope: Input media files\n  period: 7 days\n  text: Input files are automatically deleted after 7 days\n- scope: Output media files\n  period: 30 days\n  text: output files after 30 days\n- scope: Account and billing data\n  period: null\n  text: We retain account and billing data as long as your account is active or as required by law.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We use trusted third-party providers to operate our Service: Vercel for hosting our website and API Supabase\n    for database\
  \ and authentication Stripe for billing and payments Resend for transactional and support emails'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion by contacting javid@ffmpeg-micro.com\n  text: You can request deletion of your account and associated data at any time by contacting us at javid@ffmpeg-micro.com.\nrights:\n- right: Access, correction, deletion\n  text: you may have rights to access, correct, or delete your personal data\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal data to any third parties.\n"
source_yaml_url: https://artifacts.apis.io/ffmpeg-micro-com/privacy/ffmpeg-micro-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from ffmpeg-micro-com's own page on 2026-11-09.
synthetic: false
tags:
- Video
- Automation
- FFmpeg
- Cloud
- Media Processing
---
