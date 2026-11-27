---
api_specs:
- filename: transcriptfetch-system-api-openapi.yml
  format: yaml
  label: TranscriptFetch System API
  slug: transcriptfetch-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptfetch/openapi/transcriptfetch-system-api-openapi.yml
- filename: transcriptfetch-transcripts-api-openapi.yml
  format: yaml
  label: TranscriptFetch Transcripts API
  slug: transcriptfetch-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcriptfetch/openapi/transcriptfetch-transcripts-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: Account data - your email and authentication details, handled by our auth provider (Clerk).
  - category: behavioral
    text: Usage data - API requests, the sources you fetch, credits used, timestamps, and IP address
  - category: device
    text: a device fingerprint (a hash derived from browser/device properties such as screen size, timezone, language, and graphics capabilities)
  - category: financial
    text: Payment data - processed by Stripe.
  - category: communication
    text: Support data - messages you send us.
  - category: behavioral
    text: how long the page was visible and how far you scrolled
  - category: device
    text: your browser family, operating system and country
  deletion:
    route: contacting support, or deleting your account
    text: Deleting your account removes your associated data, subject to records we must retain by law.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: billing, rate limiting, abuse prevention
    text: used for billing, rate limiting, and abuse prevention
  - purpose: rate-limit free tool
    text: solely to rate-limit and prevent abuse of the paid infrastructure behind it
  - purpose: site analytics
    text: We use privacy-focused product analytics (Microsoft Clarity) to understand how the site is used
  - purpose: repeat sign-up prevention
    text: They are used only to spot repeat sign-ups claiming the free credits again, never for advertising
  - purpose: speech recognition
    text: when a video you request has no caption track, we extract its audio and send it to DeepInfra to be transcribed
  retention:
  - period: 30 days
    scope: free-tool records (IP address and device fingerprint)
    text: these records are automatically deleted after 30 days
  - period: as long as your account is active
    scope: account and usage data
    text: We retain account and usage data for as long as your account is active and as needed for legal, billing, and security purposes.
  rights:
  - right: access, correction, deletion
    text: You may request access to, correction of, or deletion of your personal data by contacting support
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TranscriptFetch
provenance_date: '2026-11-10'
provider_name: TranscriptFetch
provider_slug: transcriptfetch
slug: transcriptfetch-privacy-policy
source_date: '2026-11-10'
source_filename: transcriptfetch-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://transcriptfetch.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TranscriptFetch\naid: transcriptfetch\nurl: https://transcriptfetch.com/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Account data - your email and authentication details, handled by our auth provider (Clerk).\n- category: behavioral\n  text: Usage data - API requests, the sources you fetch, credits used, timestamps, and IP address\n- category: device\n  text: a device fingerprint (a hash derived from browser/device properties such as screen size, timezone, language,\n    and graphics capabilities)\n- category: financial\n  text: Payment\
  \ data - processed by Stripe.\n- category: communication\n  text: Support data - messages you send us.\n- category: behavioral\n  text: how long the page was visible and how far you scrolled\n- category: device\n  text: your browser family, operating system and country\npurposes:\n- purpose: billing, rate limiting, abuse prevention\n  text: used for billing, rate limiting, and abuse prevention\n- purpose: rate-limit free tool\n  text: solely to rate-limit and prevent abuse of the paid infrastructure behind it\n- purpose: site analytics\n  text: We use privacy-focused product analytics (Microsoft Clarity) to understand how the site is used\n- purpose: repeat sign-up prevention\n  text: They are used only to spot repeat sign-ups claiming the free credits again, never for advertising\n- purpose: speech recognition\n  text: when a video you request has no caption track, we extract its audio and send it to DeepInfra to be transcribed\nretention:\n- scope: free-tool records (IP address and device\
  \ fingerprint)\n  period: 30 days\n  text: these records are automatically deleted after 30 days\n- scope: account and usage data\n  period: as long as your account is active\n  text: We retain account and usage data for as long as your account is active and as needed for legal, billing,\n    and security purposes.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contacting support, or deleting your account\n  text: Deleting your account removes your associated data, subject to records we must retain by law.\nrights:\n- right: access, correction, deletion\n  text: You may request access to, correction of, or deletion of your personal data by contacting support\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/transcriptfetch/privacy/transcriptfetch-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from TranscriptFetch's own page on 2026-11-10.
synthetic: false
tags:
- Transcripts
- Speech-to-Text
- Captions
- YouTube
- TikTok
- Instagram
- Podcasts
- MCP
- Llms.txt
- OpenAPI
- Transcription
- Video
- AI/LLM
- RAG
- Agents
- Developer Tools
- Media
- Content
- Spotify
- Apple Podcasts
---
