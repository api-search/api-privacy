---
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'What we store: your account (through Clerk), the products you create and their memory'
  - category: device
    text: 'It sends anonymous usage counts : a random install id, event and tool names, success, outcome counts (how many records a brief cited, a check''s verdict), the version and operating system.'
  - category: behavioral
    text: 'Analytics: PostHog counts how the site is used (which buttons, whether a judgment was accepted), not the text of your records.'
  - category: other
    text: decisions, rules, bets, roadmap, releases, the public pages you confirm, what connected sources show, a history of changes and which agents read what
  deletion:
    route: Settings for products; GitHub issue for account
    text: To delete your account and everything in it, or to ask anything about this page, open an issue at github.com/bluet-dev/bluet-plugin .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: giving memory back to user and their agents
    text: we do not use your memory for anything but giving it back to you and your agents
  - purpose: judging and writing briefs
    text: to judge what it reads and to write briefs, Bluet sends the relevant material
  - purpose: site analytics
    text: PostHog counts how the site is used (which buttons, whether a judgment was accepted)
  residency:
  - region: local machine
    text: Everything it reads and records stays on your machine, in ~/.bluet , unless you link it to bluet.dev.
  retention:
  - period: null
    scope: product memory
    text: 'Deleting a product in Settings deletes everything recorded for it: its memory, proposals, findings, saves and share links.'
  - period: until you disconnect them
    scope: source connections
    text: Source connections belong to your workspace and stay until you disconnect them under Sources.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data
  subprocessors:
    text: Who processes it Vercel (hosting), Supabase (the database), Clerk (sign-in), Anthropic (models), PostHog (analytics), and Composio or Bluet's own GitHub App (reading GitHub), each only for the purpose above.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bluet
provenance_date: '2026-11-09'
provider_name: Bluet
provider_slug: bluet-dev
slug: bluet-dev-privacy-policy
source_date: '2026-11-09'
source_filename: bluet-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bluet.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bluet\naid: bluet-dev\nurl: https://bluet.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'What we store: your account (through Clerk), the products you create and their memory'\n- category: device\n  text: 'It sends anonymous usage counts : a random install id, event and tool names, success, outcome counts (how\n    many records a brief cited, a check''s verdict), the version and operating system.'\n- category: behavioral\n  text: 'Analytics: PostHog counts how the site is used (which buttons, whether a judgment was accepted),\
  \ not the\n    text of your records.'\n- category: other\n  text: decisions, rules, bets, roadmap, releases, the public pages you confirm, what connected sources show, a\n    history of changes and which agents read what\npurposes:\n- purpose: giving memory back to user and their agents\n  text: we do not use your memory for anything but giving it back to you and your agents\n- purpose: judging and writing briefs\n  text: to judge what it reads and to write briefs, Bluet sends the relevant material\n- purpose: site analytics\n  text: PostHog counts how the site is used (which buttons, whether a judgment was accepted)\nretention:\n- scope: product memory\n  period: null\n  text: 'Deleting a product in Settings deletes everything recorded for it: its memory, proposals, findings, saves\n    and share links.'\n- scope: source connections\n  period: until you disconnect them\n  text: Source connections belong to your workspace and stay until you disconnect them under Sources.\nresidency:\n\
  - region: local machine\n  text: Everything it reads and records stays on your machine, in ~/.bluet , unless you link it to bluet.dev.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Who processes it Vercel (hosting), Supabase (the database), Clerk (sign-in), Anthropic (models), PostHog\n    (analytics), and Composio or Bluet's own GitHub App (reading GitHub), each only for the purpose above.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings for products; GitHub issue for account\n  text: To delete your account and everything in it, or to ask anything about this page, open an issue at github.com/bluet-dev/bluet-plugin\n    .\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell data\n"
source_yaml_url: https://artifacts.apis.io/bluet-dev/privacy/bluet-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- sale_or_sharing
summary_line: 13 quoted statements, read from Bluet's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Product-Memory
- MCP
- Open Source
- Decision-Making
---
