---
api_specs:
- filename: dibatto-com-episodes-api-openapi.yml
  format: yaml
  label: Dibatto Episodes API
  slug: dibatto-com-episodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dibatto-com/openapi/dibatto-com-episodes-api-openapi.yml
- filename: dibatto-com-shows-api-openapi.yml
  format: yaml
  label: Dibatto Shows API
  slug: dibatto-com-shows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dibatto-com/openapi/dibatto-com-shows-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your email address, display name, timezone and sign-in sessions.'
  - category: behavioral
    text: 'Usage data: session lengths, credit spend and cost lines, used for billing and plan limits.'
  - category: communication
    text: 'Recordings: the audio and optional video you record, the transcripts derived from them, and the artifacts produced in the wrap.'
  deletion:
    route: Email hello@dibatto.com to export or delete your data
    text: Email hello@dibatto.com to export or delete your data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the product
    text: 'To run the product you asked for: generate rundowns, host live sessions, produce episodes, enforce plan limits and bill you.'
  retention:
  - period: 30 days after upload
    scope: Free-tier media
    text: Free-tier media is deleted 30 days after upload.
  - period: null
    scope: Paid media
    text: Paid media is kept while your account is open.
  rights:
  - right: export or delete data
    text: Email hello@dibatto.com to export or delete your data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell it, and we do not use your recordings to train models.
  subprocessors:
    text: Processors Cloudflare — hosting, database, object storage and transcription. OpenAI — the live voice co-host during a session. OpenRouter — rundown research, producer cues and wrap analysis. Stripe — payments. Card details never reach our servers. Resend — sign-in links and recap email.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Dibatto
provenance_date: '2026-11-09'
provider_name: Dibatto
provider_slug: dibatto-com
slug: dibatto-com-privacy-policy
source_date: '2026-11-09'
source_filename: dibatto-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dibatto.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Dibatto\naid: dibatto-com\nurl: https://dibatto.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account data: your email address, display name, timezone and sign-in sessions.'\n- category: behavioral\n  text: 'Usage data: session lengths, credit spend and cost lines, used for billing and plan limits.'\n- category: communication\n  text: 'Recordings: the audio and optional video you record, the transcripts derived from them, and the artifacts\n    produced in the wrap.'\npurposes:\n- purpose: Run the product\n  text: 'To\
  \ run the product you asked for: generate rundowns, host live sessions, produce episodes, enforce plan\n    limits and bill you.'\nretention:\n- scope: Free-tier media\n  period: 30 days after upload\n  text: Free-tier media is deleted 30 days after upload.\n- scope: Paid media\n  period: null\n  text: Paid media is kept while your account is open.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Processors Cloudflare — hosting, database, object storage and transcription. OpenAI — the live voice co-host\n    during a session. OpenRouter — rundown research, producer cues and wrap analysis. Stripe — payments. Card details\n    never reach our servers. Resend — sign-in links and recap email.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@dibatto.com to export or delete your data\n  text: Email hello@dibatto.com to export or delete your data.\nrights:\n- right: export or delete data\n  text: Email hello@dibatto.com to export or delete\
  \ your data.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell it, and we do not use your recordings to train models.\n"
source_yaml_url: https://artifacts.apis.io/dibatto-com/privacy/dibatto-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 10 quoted statements, read from Dibatto's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Podcasts
- Artificial Intelligence
- Voice
- Audio
- Content Creation
- MCP
---
