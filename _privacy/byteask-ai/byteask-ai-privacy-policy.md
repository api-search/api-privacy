---
api_specs:
- filename: byteask-ai-api-openapi.json
  format: json
  label: ByteAsk public status endpoints Api API
  slug: byteask-public-status-endpoints-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/byteask-ai/openapi/_original/byteask-ai-api-openapi.json
claim_count: 15
description: ''
doc:
  data_categories:
  - category: contact
    text: Your email address, when you sign in with a magic link.
  - category: device
    text: A short-lived authentication token stored on your device after sign-in.
  - category: behavioral
    text: It records which pages you view, how long you stay, what you click, how far you scroll, how quickly the page loaded, the referring site, and the browser type.
  - category: communication
    text: The prompts you type and the repository content the CLI sends are processed in memory to answer your request and are then dropped.
  deletion:
    route: email request
    text: You can request access to or deletion of your data at any time by writing to [email protected] , and we will act on the request promptly.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: reliability, abuse prevention, billing of credits
    text: Minimal operational metadata about requests (timestamps, status, token counts) used for reliability, abuse prevention, and billing of credits.
  - purpose: advertising measurement
    text: To measure our own advertising, byteask.ai loads the Meta Pixel (Meta Platforms) and the Reddit Pixel (Reddit, Inc.).
  - purpose: site usage analytics
    text: We use PostHog (hosted in the United States) to understand how the site is used.
  residency:
  - region: United States
    text: We use PostHog (hosted in the United States) to understand how the site is used.
  retention:
  - period: null
    scope: prompts and repository content
    text: The prompts you type and the repository content the CLI sends are processed in memory to answer your request and are then dropped.
  - period: while your account is active
    scope: account email
    text: We keep your account email while your account is active.
  - period: 30 days
    scope: PostHog session replays
    text: Replays are kept for 30 days.
  rights:
  - right: access
    text: You can request access to or deletion of your data at any time by writing to [email protected]
  - right: deletion
    text: You can request access to or deletion of your data at any time by writing to [email protected]
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ByteAsk
provenance_date: '2026-11-09'
provider_name: ByteAsk
provider_slug: byteask-ai
slug: byteask-ai-privacy-policy
source_date: '2026-11-09'
source_filename: byteask-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://byteask.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ByteAsk\naid: byteask-ai\nurl: https://byteask.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Your email address, when you sign in with a magic link.\n- category: device\n  text: A short-lived authentication token stored on your device after sign-in.\n- category: behavioral\n  text: It records which pages you view, how long you stay, what you click, how far you scroll, how quickly the\n    page loaded, the referring site, and the browser type.\n- category: communication\n  text: The prompts you type and the repository content the\
  \ CLI sends are processed in memory to answer your request\n    and are then dropped.\npurposes:\n- purpose: reliability, abuse prevention, billing of credits\n  text: Minimal operational metadata about requests (timestamps, status, token counts) used for reliability, abuse\n    prevention, and billing of credits.\n- purpose: advertising measurement\n  text: To measure our own advertising, byteask.ai loads the Meta Pixel (Meta Platforms) and the Reddit Pixel (Reddit,\n    Inc.).\n- purpose: site usage analytics\n  text: We use PostHog (hosted in the United States) to understand how the site is used.\nretention:\n- scope: prompts and repository content\n  period: null\n  text: The prompts you type and the repository content the CLI sends are processed in memory to answer your request\n    and are then dropped.\n- scope: account email\n  period: while your account is active\n  text: We keep your account email while your account is active.\n- scope: PostHog session replays\n  period: 30 days\n\
  \  text: Replays are kept for 30 days.\nresidency:\n- region: United States\n  text: We use PostHog (hosted in the United States) to understand how the site is used.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: You can request access to or deletion of your data at any time by writing to [email protected] , and we\n    will act on the request promptly.\nrights:\n- right: access\n  text: You can request access to or deletion of your data at any time by writing to [email protected]\n- right: deletion\n  text: You can request access to or deletion of your data at any time by writing to [email protected]\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell data.\n"
source_yaml_url: https://artifacts.apis.io/byteask-ai/privacy/byteask-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from ByteAsk's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Coding
- C++
- Terminal
- Automation
---
