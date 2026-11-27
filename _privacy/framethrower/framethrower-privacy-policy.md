---
api_specs:
- filename: framethrower-discovery-api-openapi.yml
  format: yaml
  label: FrameThrower Discovery API
  slug: framethrower-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/framethrower/openapi/framethrower-discovery-api-openapi.yml
- filename: framethrower-films-api-openapi.yml
  format: yaml
  label: FrameThrower Films API
  slug: framethrower-films-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/framethrower/openapi/framethrower-films-api-openapi.yml
- filename: framethrower-frames-api-openapi.yml
  format: yaml
  label: FrameThrower Frames API
  slug: framethrower-frames-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/framethrower/openapi/framethrower-frames-api-openapi.yml
- filename: framethrower-search-api-openapi.yml
  format: yaml
  label: FrameThrower Search API
  slug: framethrower-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/framethrower/openapi/framethrower-search-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address, name, and (if you sign in with Google) your Google profile image.
  - category: financial
    text: We store your subscription status, plan, and billing period — never your card number
  - category: behavioral
    text: Search queries, frames you view, downloads, image searches, and approximate time spent in the app.
  - category: device
    text: IP address and browser user-agent in security and download logs (rate limiting, bot and scraping defense)
  - category: other
    text: Saved frames and movies, collections, moodboards and canvases, notes, hotkey and content preferences.
  deletion:
    route: In-app Settings → Privacy → Delete my account, or email privacy@framethrower.ai
    text: Use Settings → Privacy → Delete my account (we email you a link to confirm, and everything is erased 14 days later), or email privacy@framethrower.ai from your account email and we complete it within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operating the Service
    text: 'Operating the Service: accounts, libraries, moodboards, sharing.'
  - purpose: Enforcing quotas and billing
    text: Enforcing plan quotas and processing subscriptions.
  - purpose: Abuse prevention
    text: 'Preventing abuse: scraping, bulk downloading, automated access.'
  - purpose: Product improvement
    text: Improving the product — e.g. understanding which searches fail so we can make results better.
  residency:
  - region: United States
    text: We rely on a small set of vetted, US-based infrastructure providers
  retention:
  - period: null
    scope: Content while account exists
    text: Your content (libraries, moodboards, preferences) is kept while your account exists.
  - period: 14 days
    scope: Account deletion
    text: we email you a link to confirm, and everything is erased 14 days later
  - period: 30 days
    scope: Email deletion request
    text: email privacy@framethrower.ai from your account email and we complete it within 30 days
  rights:
  - right: access, correct, export, delete, object
    text: you may have rights to access, correct, export, or delete your personal data, and to object to certain processing
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We will never sell your data. We do not sell or rent personal data, share it with advertisers
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FrameThrower
provenance_date: '2026-11-09'
provider_name: FrameThrower
provider_slug: framethrower
slug: framethrower-privacy-policy
source_date: '2026-11-09'
source_filename: framethrower-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://framethrower.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FrameThrower\naid: framethrower\nurl: https://framethrower.ai/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email address, name, and (if you sign in with Google) your Google profile image.\n- category: financial\n  text: We store your subscription status, plan, and billing period — never your card number\n- category: behavioral\n  text: Search queries, frames you view, downloads, image searches, and approximate time spent in the app.\n- category: device\n  text: IP address and browser user-agent in security and download\
  \ logs (rate limiting, bot and scraping defense)\n- category: other\n  text: Saved frames and movies, collections, moodboards and canvases, notes, hotkey and content preferences.\npurposes:\n- purpose: Operating the Service\n  text: 'Operating the Service: accounts, libraries, moodboards, sharing.'\n- purpose: Enforcing quotas and billing\n  text: Enforcing plan quotas and processing subscriptions.\n- purpose: Abuse prevention\n  text: 'Preventing abuse: scraping, bulk downloading, automated access.'\n- purpose: Product improvement\n  text: Improving the product — e.g. understanding which searches fail so we can make results better.\nretention:\n- scope: Content while account exists\n  period: null\n  text: Your content (libraries, moodboards, preferences) is kept while your account exists.\n- scope: Account deletion\n  period: 14 days\n  text: we email you a link to confirm, and everything is erased 14 days later\n- scope: Email deletion request\n  period: 30 days\n  text: email privacy@framethrower.ai\
  \ from your account email and we complete it within 30 days\nresidency:\n- region: United States\n  text: We rely on a small set of vetted, US-based infrastructure providers\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: In-app Settings → Privacy → Delete my account, or email privacy@framethrower.ai\n  text: Use Settings → Privacy → Delete my account (we email you a link to confirm, and everything is erased 14\n    days later), or email privacy@framethrower.ai from your account email and we complete it within 30 days.\nrights:\n- right: access, correct, export, delete, object\n  text: you may have rights to access, correct, export, or delete your personal data, and to object to certain processing\nsale_or_sharing:\n  stance: prohibited\n  text: We will never sell your data. We do not sell or rent personal data, share it with advertisers\n"
source_yaml_url: https://artifacts.apis.io/framethrower/privacy/framethrower-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from FrameThrower's own page on 2026-11-09.
synthetic: false
tags:
- Film
- Cinematography
- Visual Reference
- Image Search
- Media
- Creative Tools
- MCP
- Agent-Native
---
