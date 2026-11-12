---
api_specs:
- filename: clipspeed-ai-openapi-generated.yml
  format: yaml
  label: ClipSpeed API
  slug: clipspeed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipspeed-ai/openapi/_ae-authored/clipspeed-ai-openapi-generated.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information — your name and email address, provided via "Sign in with Google" or email signup.
  - category: financial
    text: We only see a charge confirmation, the last 4 digits of your card, and your Stripe customer ID.
  - category: device
    text: Device information — screen size, timezone, language (for rendering the UI correctly).
  - category: behavioral
    text: Usage logs — IP address, browser user-agent, pages visited, features used, timestamps.
  - category: communication
    text: 'Email logs (transactional): 90 days.'
  deletion:
    route: Settings → Account → Delete Account, or email privacy@clipspeed.ai
    text: Delete your entire account — Settings → Account → Delete Account. This triggers a cascade delete of every project, clip, transcript, OAuth token, and uploaded asset.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: generate short-form clips from videos you submit, show you analytics, publish clips you authorize to third-party platforms.
  - purpose: Marketing emails
    text: Send product updates or marketing emails only if you opt in .
  - purpose: Abuse and fraud prevention
    text: Detect and prevent abuse, fraud, and violations of our Terms of Service.
  - purpose: Legal compliance
    text: Comply with legal obligations (tax records, lawful requests from authorities).
  residency:
  - region: United States
    text: 'Location: United States (data hosted in US regions on Supabase, Railway, and Cloudflare)'
  retention:
  - period: 30 days
    scope: Usage logs
    text: Retained for 30 days for debugging and security, then deleted.
  - period: 90 days
    scope: Email logs
    text: 'Email logs (transactional): 90 days.'
  - period: up to 7 years after account deletion
    scope: Account and billing data
    text: plus up to 7 years after account deletion for tax and legal compliance (Stripe transactions only; no content).
  - period: null
    scope: Generated clips and transcripts
    text: 'Generated clips + transcripts: until you delete them or delete your account.'
  rights:
  - right: Access
    text: Access — request a copy of the personal information we hold about you.
  - right: Rectification
    text: Rectification — correct inaccurate data.
  - right: Erasure
    text: Erasure — delete your account and all associated data.
  - right: Portability
    text: Portability — receive your data in a portable format (JSON) so you can take it to another service.
  - right: Objection
    text: Objection — object to specific processing activities (e.g., marketing emails).
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: With your consent, we share limited event data (such as page views and sign-up events) with our advertising partners — TikTok, and Meta where enabled — to measure and improve our ads.
  subprocessors:
    text: Service processors (Supabase, Railway, Cloudflare, Stripe, Resend, AssemblyAI, Deepgram, OpenAI/Whisper, ElevenLabs) that operate on our behalf under data-processing agreements.
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on appropriate safeguards for such transfers, including Standard Contractual Clauses with our data processors where applicable.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ClipSpeedAI
provenance_date: '2026-11-09'
provider_name: ClipSpeedAI
provider_slug: clipspeed-ai
slug: clipspeed-ai-privacy-policy
source_date: '2026-11-09'
source_filename: clipspeed-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.clipspeed.ai/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ClipSpeedAI\naid: clipspeed-ai\nurl: https://www.clipspeed.ai/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information — your name and email address, provided via \"Sign in with Google\" or email signup.\n- category: financial\n  text: We only see a charge confirmation, the last 4 digits of your card, and your Stripe customer ID.\n- category: device\n  text: Device information — screen size, timezone, language (for rendering the UI correctly).\n- category: behavioral\n  text: Usage logs — IP address, browser user-agent,\
  \ pages visited, features used, timestamps.\n- category: communication\n  text: 'Email logs (transactional): 90 days.'\npurposes:\n- purpose: Provide the Service\n  text: generate short-form clips from videos you submit, show you analytics, publish clips you authorize to third-party\n    platforms.\n- purpose: Marketing emails\n  text: Send product updates or marketing emails only if you opt in .\n- purpose: Abuse and fraud prevention\n  text: Detect and prevent abuse, fraud, and violations of our Terms of Service.\n- purpose: Legal compliance\n  text: Comply with legal obligations (tax records, lawful requests from authorities).\nretention:\n- scope: Usage logs\n  period: 30 days\n  text: Retained for 30 days for debugging and security, then deleted.\n- scope: Email logs\n  period: 90 days\n  text: 'Email logs (transactional): 90 days.'\n- scope: Account and billing data\n  period: up to 7 years after account deletion\n  text: plus up to 7 years after account deletion for tax and legal\
  \ compliance (Stripe transactions only; no content).\n- scope: Generated clips and transcripts\n  period: null\n  text: 'Generated clips + transcripts: until you delete them or delete your account.'\nresidency:\n- region: United States\n  text: 'Location: United States (data hosted in US regions on Supabase, Railway, and Cloudflare)'\ntransfers:\n- mechanism: SCC\n  text: we rely on appropriate safeguards for such transfers, including Standard Contractual Clauses with our data\n    processors where applicable.\nsubprocessors:\n  url: null\n  text: Service processors (Supabase, Railway, Cloudflare, Stripe, Resend, AssemblyAI, Deepgram, OpenAI/Whisper,\n    ElevenLabs) that operate on our behalf under data-processing agreements.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings → Account → Delete Account, or email privacy@clipspeed.ai\n  text: Delete your entire account — Settings → Account → Delete Account. This triggers a cascade delete of every\n    project,\
  \ clip, transcript, OAuth token, and uploaded asset.\nrights:\n- right: Access\n  text: Access — request a copy of the personal information we hold about you.\n- right: Rectification\n  text: Rectification — correct inaccurate data.\n- right: Erasure\n  text: Erasure — delete your account and all associated data.\n- right: Portability\n  text: Portability — receive your data in a portable format (JSON) so you can take it to another service.\n- right: Objection\n  text: Objection — object to specific processing activities (e.g., marketing emails).\nsale_or_sharing:\n  stance: conditional\n  text: With your consent, we share limited event data (such as page views and sign-up events) with our advertising\n    partners — TikTok, and Meta where enabled — to measure and improve our ads.\n"
source_yaml_url: https://artifacts.apis.io/clipspeed-ai/privacy/clipspeed-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from ClipSpeedAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Video
- Video Clipping
- Image Generation
- Generative AI
- Live Streaming
- Social Media
- MCP
---
