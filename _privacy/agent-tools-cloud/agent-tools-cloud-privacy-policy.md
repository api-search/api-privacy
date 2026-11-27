---
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Server logs — standard web-server records: IP address, timestamp, requested URL, status code, referrer and user-agent.'
  - category: behavioral
    text: Page-view counts — when a real browser opens a service detail page, a small script records that the page was viewed (page type, slug, referrer, IP, user-agent).
  - category: behavioral
    text: MCP tool calls — for calls to /mcp-discovery/ we log the tool name, its arguments (including search text), result count, client name and IP.
  - category: identifying
    text: Account records, only if you create one — signing in with GitHub stores your GitHub numeric id and login
  - category: financial
    text: Sponsored paid-verification records — account id, payer and recipient wallet addresses, amount, authorization nonce and validity window
  - category: contact
    text: A contact address, only if you give one — optional when you submit a service or claim a host, and used only to reach you about that listing.
  - category: contact
    text: Public business contacts for claim invitations — a published contact email and its first-party source URL, source-page hash and check time, review status, message hash and sending result.
  deletion:
    route: Privacy erasure request approved by the provider, via the privacy contact address
    text: When we approve a privacy erasure request, we remove the listing, its submitted URLs, ownership claim and linked crawl or measurement records.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operations and security
    text: Used for operations, security, abuse prevention and aggregate traffic statistics.
  - purpose: measuring listing popularity
    text: This measures which listings people find useful.
  - purpose: account-scoped actions
    text: An account supports account-scoped actions such as sponsored paid verification and, after domain verification, correcting listings you control.
  - purpose: reaching listing contact
    text: used only to reach you about that listing
  retention:
  - period: 90 days
    scope: sponsored paid-verification underlying records
    text: their underlying records are retained for at most 90 days, then pruned.
  - period: 30 days
    scope: sponsored paid-verification results
    text: The result and transaction hash are public on the service card for 30 days when they still match the current listing version.
  - period: null
    scope: edit history
    text: 'Edit history is different: it is part of a listing''s public record and stays for as long as the listing does.'
  - period: null
    scope: MCP tool call logs
    text: These logs currently have no fixed expiry.
  - period: null
    scope: logs and view records
    text: Logs and view records are kept only as long as useful for operations, security and trend analysis, then rotated or aggregated.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data and we do not run third-party advertising trackers.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agent Tools
provenance_date: '2026-11-09'
provider_name: Agent Tools
provider_slug: agent-tools-cloud
slug: agent-tools-cloud-privacy-policy
source_date: '2026-11-09'
source_filename: agent-tools-cloud-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agent-tools.cloud/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agent Tools\naid: agent-tools-cloud\nurl: https://agent-tools.cloud/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Server logs — standard web-server records: IP address, timestamp, requested URL, status code, referrer\n    and user-agent.'\n- category: behavioral\n  text: Page-view counts — when a real browser opens a service detail page, a small script records that the page\n    was viewed (page type, slug, referrer, IP, user-agent).\n- category: behavioral\n  text: MCP tool calls — for calls to /mcp-discovery/ we log the tool\
  \ name, its arguments (including search text),\n    result count, client name and IP.\n- category: identifying\n  text: Account records, only if you create one — signing in with GitHub stores your GitHub numeric id and login\n- category: financial\n  text: Sponsored paid-verification records — account id, payer and recipient wallet addresses, amount, authorization\n    nonce and validity window\n- category: contact\n  text: A contact address, only if you give one — optional when you submit a service or claim a host, and used only\n    to reach you about that listing.\n- category: contact\n  text: Public business contacts for claim invitations — a published contact email and its first-party source URL,\n    source-page hash and check time, review status, message hash and sending result.\npurposes:\n- purpose: operations and security\n  text: Used for operations, security, abuse prevention and aggregate traffic statistics.\n- purpose: measuring listing popularity\n  text: This measures which\
  \ listings people find useful.\n- purpose: account-scoped actions\n  text: An account supports account-scoped actions such as sponsored paid verification and, after domain verification,\n    correcting listings you control.\n- purpose: reaching listing contact\n  text: used only to reach you about that listing\nretention:\n- scope: sponsored paid-verification underlying records\n  period: 90 days\n  text: their underlying records are retained for at most 90 days, then pruned.\n- scope: sponsored paid-verification results\n  period: 30 days\n  text: The result and transaction hash are public on the service card for 30 days when they still match the current\n    listing version.\n- scope: edit history\n  period: null\n  text: 'Edit history is different: it is part of a listing''s public record and stays for as long as the listing\n    does.'\n- scope: MCP tool call logs\n  period: null\n  text: These logs currently have no fixed expiry.\n- scope: logs and view records\n  period: null\n \
  \ text: Logs and view records are kept only as long as useful for operations, security and trend analysis, then\n    rotated or aggregated.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy erasure request approved by the provider, via the privacy contact address\n  text: When we approve a privacy erasure request, we remove the listing, its submitted URLs, ownership claim and\n    linked crawl or measurement records.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell data and we do not run third-party advertising trackers.\n"
source_yaml_url: https://artifacts.apis.io/agent-tools-cloud/privacy/agent-tools-cloud-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 18 quoted statements, read from Agent Tools's own page on 2026-11-09.
synthetic: false
tags:
- Discovery
- Directory
- x402
- MCP
- A2A
---
