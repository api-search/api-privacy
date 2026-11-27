---
api_specs:
- filename: botx402-io-agent-api-openapi.yml
  format: yaml
  label: BotX402 Agent API
  slug: botx402-io-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botx402-io/openapi/botx402-io-agent-api-openapi.yml
- filename: botx402-io-base-address-balance-api-openapi.yml
  format: yaml
  label: BotX402 Base Address Balance API
  slug: botx402-io-base-address-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botx402-io/openapi/botx402-io-base-address-balance-api-openapi.yml
- filename: botx402-io-well-known-api-openapi.yml
  format: yaml
  label: BotX402 .well Known API
  slug: botx402-io-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/botx402-io/openapi/botx402-io-well-known-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address — the one you give us at checkout
  - category: financial
    text: Payment method — card payments are handled entirely by Stripe (PCI Level 1).
  - category: identifying
    text: Payer wallet address — the EIP-55 lower-cased 0x… address that signed the EIP-3009 authorization.
  - category: device
    text: User-agent header — the standard HTTP one your client sends.
  - category: device
    text: IP address — used, never stored as such
  - category: behavioral
    text: If you visit on prd, anonymised analytics (page views, no individual identifiers) via Plausible
  - category: other
    text: The inputs you send a bot — for example the figures or files you paste or upload for a report.
  deletion:
    route: Email hello@botx402.io
    text: Email hello@botx402.io to delete your data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Take payment and send receipt
    text: Email address — the one you give us at checkout (or that your AI assistant passes on for you, see section 03). Stripe sends a payment receipt to it
  - purpose: Refunds and audit
    text: Receipt ID, run timestamps, run status — kept in our jobs table for refund and audit purposes.
  - purpose: Rate limiting
    text: Caller fingerprint — sha256(wallet || user-agent), truncated to 8 bytes (16 hex chars). Used only to enforce the per-caller daily USDC spend cap
  - purpose: Generate report
    text: The inputs you send a bot — for example the figures or files you paste or upload for a report.
  residency:
  - region: United States
    text: All run data, encrypted tokens, and PDFs are stored in the United States.
  retention:
  - period: one day
    scope: Inputs staged for card checkout
    text: deleted automatically after one day
  - period: 90 days
    scope: Report files
    text: kept encrypted at rest for 90 days, then deleted
  - period: 90 days
    scope: Receipt PDF
    text: encrypted at rest, deleted after 90 days.
  - period: null
    scope: Job records
    text: Job records are not deleted automatically; we delete yours when you ask, except where we must keep a record of a sale for tax purposes.
  - period: 90 days
    scope: Server logs
    text: server logs 90 days, fulfillment logs 30 days
  rights:
  - right: access
    text: You can request a copy of any data we hold about you
  - right: deletion
    text: request deletion of all of it
  - right: correction
    text: or correct anything that's wrong.
  role:
    text: The data controller is Arnhem Labs Pty Ltd (ABN 53 696 663 297)
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don't sell, rent, or syndicate.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on standard contractual clauses where applicable.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BotX402
provenance_date: '2026-11-09'
provider_name: BotX402
provider_slug: botx402-io
slug: botx402-io-privacy-policy
source_date: '2026-11-09'
source_filename: botx402-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://botx402.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BotX402\naid: botx402-io\nurl: https://botx402.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is Arnhem Labs Pty Ltd (ABN 53 696 663 297)\ndata_categories:\n- category: contact\n  text: Email address — the one you give us at checkout\n- category: financial\n  text: Payment method — card payments are handled entirely by Stripe (PCI Level 1).\n- category: identifying\n  text: Payer wallet address — the EIP-55 lower-cased 0x… address that signed the EIP-3009 authorization.\n- category: device\n  text: User-agent header — the standard HTTP one your client sends.\n\
  - category: device\n  text: IP address — used, never stored as such\n- category: behavioral\n  text: If you visit on prd, anonymised analytics (page views, no individual identifiers) via Plausible\n- category: other\n  text: The inputs you send a bot — for example the figures or files you paste or upload for a report.\npurposes:\n- purpose: Take payment and send receipt\n  text: Email address — the one you give us at checkout (or that your AI assistant passes on for you, see section\n    03). Stripe sends a payment receipt to it\n- purpose: Refunds and audit\n  text: Receipt ID, run timestamps, run status — kept in our jobs table for refund and audit purposes.\n- purpose: Rate limiting\n  text: Caller fingerprint — sha256(wallet || user-agent), truncated to 8 bytes (16 hex chars). Used only to enforce\n    the per-caller daily USDC spend cap\n- purpose: Generate report\n  text: The inputs you send a bot — for example the figures or files you paste or upload for a report.\nretention:\n\
  - scope: Inputs staged for card checkout\n  period: one day\n  text: deleted automatically after one day\n- scope: Report files\n  period: 90 days\n  text: kept encrypted at rest for 90 days, then deleted\n- scope: Receipt PDF\n  period: 90 days\n  text: encrypted at rest, deleted after 90 days.\n- scope: Job records\n  period: null\n  text: Job records are not deleted automatically; we delete yours when you ask, except where we must keep a record\n    of a sale for tax purposes.\n- scope: Server logs\n  period: 90 days\n  text: server logs 90 days, fulfillment logs 30 days\nresidency:\n- region: United States\n  text: All run data, encrypted tokens, and PDFs are stored in the United States.\ntransfers:\n- mechanism: SCC\n  text: We rely on standard contractual clauses where applicable.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@botx402.io\n  text: Email hello@botx402.io to delete your data.\nrights:\n\
  - right: access\n  text: You can request a copy of any data we hold about you\n- right: deletion\n  text: request deletion of all of it\n- right: correction\n  text: or correct anything that's wrong.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell, rent, or syndicate.\n"
source_yaml_url: https://artifacts.apis.io/botx402-io/privacy/botx402-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from BotX402's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Pay-per-use
- Bots
- Business
- Automation
- SaaS-alternative
---
