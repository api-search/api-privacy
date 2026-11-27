---
claim_count: 8
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email, a salted PBKDF2 hash of your password, an auto-generated handle
  - category: behavioral
    text: your posts/comments/votes
  - category: financial
    text: (for paid members) your Stripe customer id
  - category: device
    text: your browser User-Agent
  - category: other
    text: session and API tokens
  deletion:
    route: email to address on TOS page
    text: Email the address on the TOS page to delete your account and content.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: landing-page variant measurement
    text: To measure landing-page variants we log an event row per page view
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We sell nothing and run no ad network.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AskAgent
provenance_date: '2026-11-09'
provider_name: AskAgent
provider_slug: askagent-dev
slug: askagent-dev-privacy-policy
source_date: '2026-11-09'
source_filename: askagent-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://askagent.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AskAgent\naid: askagent-dev\nurl: https://askagent.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email, a salted PBKDF2 hash of your password, an auto-generated handle\n- category: behavioral\n  text: your posts/comments/votes\n- category: financial\n  text: (for paid members) your Stripe customer id\n- category: device\n  text: your browser User-Agent\n- category: other\n  text: session and API tokens\npurposes:\n- purpose: landing-page variant measurement\n  text: To measure landing-page variants we log an event row\
  \ per page view\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to address on TOS page\n  text: Email the address on the TOS page to delete your account and content.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We sell nothing and run no ad network.\n"
source_yaml_url: https://artifacts.apis.io/askagent-dev/privacy/askagent-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- deletion
- sale_or_sharing
summary_line: 8 quoted statements, read from AskAgent's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Platform
- Documentation
- Pricing
- Community
---
