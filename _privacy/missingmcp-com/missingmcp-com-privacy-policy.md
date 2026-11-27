---
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your sign-in identifier for the connected service (the account email)
  - category: identifying
    text: Encrypted credentials for the connected service — AES-256-GCM at rest.
  - category: behavioral
    text: 'Per-account tool-usage counters: tool name, call count, and last-used timestamp — never tool arguments or results.'
  - category: contact
    text: 'If you opted in on the home page while that form was offered: your email address (for MissingMCP news, like new connectors and important service changes)'
  deletion:
    route: Email the operator
    text: Email the operator ( [email protected] ) to have every stored record — including any newsletter signup — deleted.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Connecting accounts to Claude
    text: MissingMCP stores the minimum needed to connect your accounts to Claude
  - purpose: Service announcements
    text: also used to send occasional service announcements (e.g. a fix that affects your connection)
  - purpose: Monitoring
    text: Operational logs (kept on the gateway’s own server at Hetzner in the EU) record account email, tool names, and timings for monitoring
  residency:
  - region: EU
    text: Operational logs (kept on the gateway’s own server at Hetzner in the EU)
  retention:
  - period: null
    scope: Stored records
    text: Email the operator ( [email protected] ) to have every stored record — including any newsletter signup — deleted.
  rights:
  - right: Unsubscribe
    text: Every email has a one-click unsubscribe.
  role:
    text: This instance is operated by Vaclav Slajs
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Nothing is sold or shared with any other party.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: missingmcp-com
provenance_date: '2026-11-10'
provider_name: missingmcp-com
provider_slug: missingmcp-com
slug: missingmcp-com-privacy-policy
source_date: '2026-11-10'
source_filename: missingmcp-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://missingmcp.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: missingmcp-com\naid: missingmcp-com\nurl: https://missingmcp.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This instance is operated by Vaclav Slajs\ndata_categories:\n- category: identifying\n  text: Your sign-in identifier for the connected service (the account email)\n- category: identifying\n  text: Encrypted credentials for the connected service — AES-256-GCM at rest.\n- category: behavioral\n  text: 'Per-account tool-usage counters: tool name, call count, and last-used timestamp — never tool arguments\n    or results.'\n- category: contact\n  text: 'If you opted in on the\
  \ home page while that form was offered: your email address (for MissingMCP news,\n    like new connectors and important service changes)'\npurposes:\n- purpose: Connecting accounts to Claude\n  text: MissingMCP stores the minimum needed to connect your accounts to Claude\n- purpose: Service announcements\n  text: also used to send occasional service announcements (e.g. a fix that affects your connection)\n- purpose: Monitoring\n  text: Operational logs (kept on the gateway’s own server at Hetzner in the EU) record account email, tool names,\n    and timings for monitoring\nretention:\n- scope: Stored records\n  period: null\n  text: Email the operator ( [email protected] ) to have every stored record — including any newsletter signup —\n    deleted.\nresidency:\n- region: EU\n  text: Operational logs (kept on the gateway’s own server at Hetzner in the EU)\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route:\
  \ Email the operator\n  text: Email the operator ( [email protected] ) to have every stored record — including any newsletter signup —\n    deleted.\nrights:\n- right: Unsubscribe\n  text: Every email has a one-click unsubscribe.\nsale_or_sharing:\n  stance: prohibited\n  text: Nothing is sold or shared with any other party.\n"
source_yaml_url: https://artifacts.apis.io/missingmcp-com/privacy/missingmcp-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from missingmcp-com's own page on 2026-11-10.
synthetic: false
tags:
- AI Connectors
- Health Data
- OAuth
- Open Source
---
