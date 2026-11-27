---
api_specs:
- filename: substructure-openapi-generated.yml
  format: yaml
  label: Substructure API
  slug: substructure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/substructure/openapi/_ae-authored/substructure-openapi-generated.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address, and the name and avatar your identity provider returns if you sign in with Google or GitHub.
  - category: financial
    text: We store the Stripe customer and checkout identifiers, how many credits an organization has bought, and when they lapse.
  - category: behavioral
    text: 'A durable event log for every session: the messages in and out, tool calls and their results, subagent runs, approval steps, and per-turn token counts.'
  - category: communication
    text: If you connect Slack, that includes messages in the channels an agent is present in, and the mentions and direct messages sent to it.
  - category: device
    text: Ordinary server logs (request paths, timings, status codes, IP addresses), kept for debugging and abuse investigation.
  - category: other
    text: Your model provider API keys, Slack bot tokens, and MCP OAuth tokens. These are encrypted with AES-256-GCM before they are written
  deletion:
    route: Email support@substructure.ai
    text: To have the data itself erased rather than archived, write to support@substructure.ai .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the service
    text: 'To run the service you asked for: executing agent turns, keeping sessions durable across restarts, delivering webhooks, counting the credits you spend, and billing you.'
  - purpose: Security and abuse
    text: To keep accounts secure and investigate abuse.
  - purpose: Analytics
    text: To understand which parts of the site lead to signups.
  residency:
  - region: United States
    text: Data is stored in the United States.
  retention:
  - period: 90 days
    scope: Sessions and event logs
    text: Sessions and their event logs are retained for 90 days , then removed.
  - period: null
    scope: Account, organization, and billing records
    text: Account, organization, and billing records are kept while the account is open, and afterwards only as long as we need them for tax and accounting.
  - period: null
    scope: Encrypted database backups
    text: Encrypted database backups are retained on a rolling basis, so deleted data can persist in a backup for a short period after it is gone from the live system.
  rights:
  - right: Access
    text: Write to support@substructure.ai to get a copy of what we hold about you, correct it, or have your account and its data deleted.
  - right: Deletion
    text: Write to support@substructure.ai to get a copy of what we hold about you, correct it, or have your account and its data deleted.
  - right: Correction
    text: correct it
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, and we do not use the content of your agent sessions to train models.
  subprocessors:
    text: We use a small number of providers to run the service. Each receives only what its job needs.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Substructure
provenance_date: '2026-11-10'
provider_name: Substructure
provider_slug: substructure
slug: substructure-privacy-policy
source_date: '2026-11-10'
source_filename: substructure-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://substructure.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Substructure\naid: substructure\nurl: https://substructure.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your email address, and the name and avatar your identity provider returns if you sign in with Google or\n    GitHub.\n- category: financial\n  text: We store the Stripe customer and checkout identifiers, how many credits an organization has bought, and\n    when they lapse.\n- category: behavioral\n  text: 'A durable event log for every session: the messages in and out, tool calls and their results, subagent\n    runs,\
  \ approval steps, and per-turn token counts.'\n- category: communication\n  text: If you connect Slack, that includes messages in the channels an agent is present in, and the mentions and\n    direct messages sent to it.\n- category: device\n  text: Ordinary server logs (request paths, timings, status codes, IP addresses), kept for debugging and abuse\n    investigation.\n- category: other\n  text: Your model provider API keys, Slack bot tokens, and MCP OAuth tokens. These are encrypted with AES-256-GCM\n    before they are written\npurposes:\n- purpose: Run the service\n  text: 'To run the service you asked for: executing agent turns, keeping sessions durable across restarts, delivering\n    webhooks, counting the credits you spend, and billing you.'\n- purpose: Security and abuse\n  text: To keep accounts secure and investigate abuse.\n- purpose: Analytics\n  text: To understand which parts of the site lead to signups.\nretention:\n- scope: Sessions and event logs\n  period: 90 days\n\
  \  text: Sessions and their event logs are retained for 90 days , then removed.\n- scope: Account, organization, and billing records\n  period: null\n  text: Account, organization, and billing records are kept while the account is open, and afterwards only as long\n    as we need them for tax and accounting.\n- scope: Encrypted database backups\n  period: null\n  text: Encrypted database backups are retained on a rolling basis, so deleted data can persist in a backup for\n    a short period after it is gone from the live system.\nresidency:\n- region: United States\n  text: Data is stored in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use a small number of providers to run the service. Each receives only what its job needs.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@substructure.ai\n  text: To have the data itself erased rather than archived, write to support@substructure.ai .\nrights:\n- right: Access\n  text:\
  \ Write to support@substructure.ai to get a copy of what we hold about you, correct it, or have your account\n    and its data deleted.\n- right: Deletion\n  text: Write to support@substructure.ai to get a copy of what we hold about you, correct it, or have your account\n    and its data deleted.\n- right: Correction\n  text: correct it\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, and we do not use the content of your agent sessions to train models.\n"
source_yaml_url: https://artifacts.apis.io/substructure/privacy/substructure-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Substructure's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- Cloud-Native
- Automation
---
