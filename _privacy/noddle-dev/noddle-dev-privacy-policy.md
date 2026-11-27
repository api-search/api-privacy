---
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data — email, display name, and a password hash (or your identity from an SSO provider, if your team uses OIDC single sign-on).
  - category: communication
    text: Your content — boards (diagram data and rendered SVG), comments, version history, and files you upload for import or AI conversion.
  - category: behavioral
    text: Operational records — an audit trail of account and board lifecycle events (login, share, delete) visible to the board owner, subscription state, and ✦ credit usage.
  - category: financial
    text: Payments — handled entirely by Lemon Squeezy as merchant of record. Card numbers never touch noddle’s servers; we receive only the subscription status and a customer reference.
  deletion:
    route: Request deletion via support
    text: Deleting your account (via support ) removes account data and owned boards, minus what payment law requires Lemon Squeezy to retain on their side.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: AI processing
    text: AI features send only the content you explicitly submit — the text prompt, Mermaid, or image you hand to generation, or the board you ask the Claude co-editor to change — to an AI model for processing.
  retention:
  - period: null
    scope: Boards and account data
    text: Boards and account data are stored on noddle’s infrastructure and kept while your account exists.
  - period: null
    scope: Board deletion
    text: Deleting a board deletes its data, versions, and comments.
  rights:
  - right: Access and export
    text: You can access and export your data yourself, correct your profile in-app, and request deletion at any time.
  - right: Correction
    text: correct your profile in-app
  - right: Deletion
    text: request deletion at any time
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
name: noddle-dev
provenance_date: '2026-11-10'
provider_name: noddle-dev
provider_slug: noddle-dev
slug: noddle-dev-privacy-policy
source_date: '2026-11-10'
source_filename: noddle-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://noddle.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: noddle-dev\naid: noddle-dev\nurl: https://noddle.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account data — email, display name, and a password hash (or your identity from an SSO provider, if your\n    team uses OIDC single sign-on).\n- category: communication\n  text: Your content — boards (diagram data and rendered SVG), comments, version history, and files you upload for\n    import or AI conversion.\n- category: behavioral\n  text: Operational records — an audit trail of account and board lifecycle events (login, share,\
  \ delete) visible\n    to the board owner, subscription state, and ✦ credit usage.\n- category: financial\n  text: Payments — handled entirely by Lemon Squeezy as merchant of record. Card numbers never touch noddle’s servers;\n    we receive only the subscription status and a customer reference.\npurposes:\n- purpose: AI processing\n  text: AI features send only the content you explicitly submit — the text prompt, Mermaid, or image you hand to\n    generation, or the board you ask the Claude co-editor to change — to an AI model for processing.\nretention:\n- scope: Boards and account data\n  period: null\n  text: Boards and account data are stored on noddle’s infrastructure and kept while your account exists.\n- scope: Board deletion\n  period: null\n  text: Deleting a board deletes its data, versions, and comments.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion via support\n\
  \  text: Deleting your account (via support ) removes account data and owned boards, minus what payment law requires\n    Lemon Squeezy to retain on their side.\nrights:\n- right: Access and export\n  text: You can access and export your data yourself, correct your profile in-app, and request deletion at any time.\n- right: Correction\n  text: correct your profile in-app\n- right: Deletion\n  text: request deletion at any time\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/noddle-dev/privacy/noddle-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 11 quoted statements, read from noddle-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Developer Platform
- API Management
- Web Development
- Cloud Services
---
