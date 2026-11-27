---
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: Handle name and email address you provide when claiming a namepoint
  - category: contact
    text: Username, public profile info, verified email, account age, repo count, and follower count — used for verification only
  - category: behavioral
    text: 'MCP requests: Tool calls and context reads/writes you make via the MCP protocol'
  - category: device
    text: 'Session cookies: A session ID stored in a secure cookie (expires after 1 hour)'
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Register namepoint and send welcome email
    text: 'Handle + email: To register your namepoint and send your welcome email'
  - purpose: Anti-abuse verification
    text: 'GitHub profile: To verify your account for anti-abuse purposes (account age, activity level)'
  - purpose: Store and serve context
    text: 'MCP data: To store and serve your context (souls) on demand'
  retention:
  - period: 1 hour
    scope: Sessions
    text: Sessions expire automatically (1 hour).
  - period: 10 minutes
    scope: OAuth state tokens
    text: OAuth state tokens expire in 10 minutes.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, share, or transfer your data to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: mcpaas-live
provenance_date: '2026-11-10'
provider_name: mcpaas-live
provider_slug: mcpaas-live
slug: mcpaas-live-privacy-policy
source_date: '2026-11-10'
source_filename: mcpaas-live-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mcpaas.live/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: mcpaas-live\naid: mcpaas-live\nurl: https://mcpaas.live/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Handle name and email address you provide when claiming a namepoint\n- category: contact\n  text: Username, public profile info, verified email, account age, repo count, and follower count — used for verification\n    only\n- category: behavioral\n  text: 'MCP requests: Tool calls and context reads/writes you make via the MCP protocol'\n- category: device\n  text: 'Session cookies: A session ID stored in a secure cookie (expires\
  \ after 1 hour)'\npurposes:\n- purpose: Register namepoint and send welcome email\n  text: 'Handle + email: To register your namepoint and send your welcome email'\n- purpose: Anti-abuse verification\n  text: 'GitHub profile: To verify your account for anti-abuse purposes (account age, activity level)'\n- purpose: Store and serve context\n  text: 'MCP data: To store and serve your context (souls) on demand'\nretention:\n- scope: Sessions\n  period: 1 hour\n  text: Sessions expire automatically (1 hour).\n- scope: OAuth state tokens\n  period: 10 minutes\n  text: OAuth state tokens expire in 10 minutes.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, share, or transfer your data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/mcpaas-live/privacy/mcpaas-live-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- sale_or_sharing
summary_line: 10 quoted statements, read from mcpaas-live's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCPaaS
- Edge Computing
- Artificial Intelligence
- Zig
- Wasm
---
