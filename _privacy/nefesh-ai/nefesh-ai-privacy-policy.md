---
claim_count: 10
description: ''
doc:
  data_categories:
  - category: biometric
    text: Only extracted features (heart rate, tone classification, expression label) are sent to the API.
  - category: biometric
    text: No video frames, audio recordings, or facial images ever reach our servers.
  deletion:
    route: DELETE /v1/subjects/{subject_id}
    text: call DELETE /v1/subjects/{subject_id} for cascading deletion of all data
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Stress score generation
    text: We process the minimum amount of data needed to generate a stress score
  - purpose: Real-time AI context only
    text: data is used exclusively for real-time AI context, not analytics, advertising, or profiling
  retention:
  - period: 20 minutes (auto-delete)
    scope: Live session state
    text: Live session state 20 minutes (auto-delete)
  - period: 24 hours
    scope: Session history
    text: Session history 24 hours
  - period: Persistent until deleted via API
    scope: Memory profiles
    text: Persistent until deleted via API
  - period: Never stored
    scope: Raw video / audio
    text: Never stored (edge processing only)
  rights:
  - right: Deletion
    text: Right to deletion
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Nefesh AI
provenance_date: '2026-11-10'
provider_name: Nefesh AI
provider_slug: nefesh-ai
slug: nefesh-ai-privacy-policy
source_date: '2026-11-10'
source_filename: nefesh-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://nefesh.ai/docs/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Nefesh AI\naid: nefesh-ai\nurl: https://nefesh.ai/docs/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: biometric\n  text: Only extracted features (heart rate, tone classification, expression label) are sent to the API.\n- category: biometric\n  text: No video frames, audio recordings, or facial images ever reach our servers.\npurposes:\n- purpose: Stress score generation\n  text: We process the minimum amount of data needed to generate a stress score\n- purpose: Real-time AI context only\n  text: data is used exclusively for real-time AI context, not\
  \ analytics, advertising, or profiling\nretention:\n- scope: Live session state\n  period: 20 minutes (auto-delete)\n  text: Live session state 20 minutes (auto-delete)\n- scope: Session history\n  period: 24 hours\n  text: Session history 24 hours\n- scope: Memory profiles\n  period: Persistent until deleted via API\n  text: Persistent until deleted via API\n- scope: Raw video / audio\n  period: Never stored\n  text: Never stored (edge processing only)\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: DELETE /v1/subjects/{subject_id}\n  text: call DELETE /v1/subjects/{subject_id} for cascading deletion of all data\nrights:\n- right: Deletion\n  text: Right to deletion\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nefesh-ai/privacy/nefesh-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 10 quoted statements, read from Nefesh AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biometrics
- Human State
- Stress Detection
- Emotion AI
- AI Agents
- MCP
- A2A
- LLM Gateway
- Wearables
- Digital Health
- Middleware
---
