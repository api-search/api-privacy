---
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address, your name if you give one, and an identifier from the sign-in provider you use.
  - category: communication
    text: Emails you send us, and our replies.
  - category: device
    text: 'Standard server logs: IP address, browser or client identifiers, request times and error records.'
  - category: location
    text: With each call, ChatGPT sends a conversation identifier, your locale and an approximate location.
  deletion:
    route: Dashboard deletion of account
    text: Deleting your account removes all data within 30 days and we confirm by email.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the service
    text: To run the service. Storing your memory and serving it back to your agent when it calls our tools; keeping versions so every change is reversible.
  - purpose: Keep agent alive
    text: If the daily cycle has not run for more than 36 hours, we send you a short nudge email with reconnect guidance.
  - purpose: Protect the memory
    text: Every write passes a pattern scan for injection attempts; suspicious spans are stored but flagged, never silently absorbed.
  - purpose: Product improvement
    text: looking at aggregate, de-identified usage (for example how many people complete setup, or how often each tool is called and how fast it answers) during the beta
  residency:
  - region: United States
    text: Our infrastructure is located in the United States.
  retention:
  - period: null
    scope: Memory and account data
    text: Memory and account data stay as long as your account exists.
  - period: 30 days
    scope: Deleted account live data
    text: After you delete your account, live data is removed within 30 days and backups are purged within a further 30 days.
  - period: 90 days
    scope: Server logs
    text: Server logs are kept for 90 days, and tool-call records are kept for the life of your account and removed with it.
  - period: 30 minutes
    scope: Hashed conversation identifiers
    text: Hashed conversation identifiers are kept for 30 minutes.
  rights:
  - right: Access, portability, restriction and objection
    text: Depending on where you live you may also have rights to access, portability, restriction and objection, and the right to complain to your data protection authority.
  - right: Export
    text: The dashboard produces a zip of every memory file, every earlier version and the raw event log.
  - right: Correct
    text: Tell your agent in chat and it updates its files, keeping the old version visible; or edit an agent-writable file in the dashboard.
  role:
    text: We are the data controller for the personal data described in this policy.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and we do not share it with advertisers or data brokers.
  subprocessors:
    text: Infrastructure providers. Servers and logs at Render (United States); the database at Neon (United States); sign-in at WorkOS (United States); and Resend (United States) for the watchdog and confirmation emails.
    url: null
  transfers:
  - mechanism: SCC
    text: Where personal data is transferred across borders we rely on appropriate safeguards such as standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cornelius
provenance_date: '2026-11-09'
provider_name: Cornelius
provider_slug: cornelius-bot
slug: cornelius-bot-privacy-policy
source_date: '2026-11-09'
source_filename: cornelius-bot-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cornelius.bot/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cornelius\naid: cornelius-bot\nurl: https://cornelius.bot/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the data controller for the personal data described in this policy.\ndata_categories:\n- category: identifying\n  text: Your email address, your name if you give one, and an identifier from the sign-in provider you use.\n- category: communication\n  text: Emails you send us, and our replies.\n- category: device\n  text: 'Standard server logs: IP address, browser or client identifiers, request times and error records.'\n- category: location\n  text: With each call, ChatGPT\
  \ sends a conversation identifier, your locale and an approximate location.\npurposes:\n- purpose: Run the service\n  text: To run the service. Storing your memory and serving it back to your agent when it calls our tools; keeping\n    versions so every change is reversible.\n- purpose: Keep agent alive\n  text: If the daily cycle has not run for more than 36 hours, we send you a short nudge email with reconnect guidance.\n- purpose: Protect the memory\n  text: Every write passes a pattern scan for injection attempts; suspicious spans are stored but flagged, never\n    silently absorbed.\n- purpose: Product improvement\n  text: looking at aggregate, de-identified usage (for example how many people complete setup, or how often each\n    tool is called and how fast it answers) during the beta\nretention:\n- scope: Memory and account data\n  period: null\n  text: Memory and account data stay as long as your account exists.\n- scope: Deleted account live data\n  period: 30 days\n  text: After\
  \ you delete your account, live data is removed within 30 days and backups are purged within a further\n    30 days.\n- scope: Server logs\n  period: 90 days\n  text: Server logs are kept for 90 days, and tool-call records are kept for the life of your account and removed\n    with it.\n- scope: Hashed conversation identifiers\n  period: 30 minutes\n  text: Hashed conversation identifiers are kept for 30 minutes.\nresidency:\n- region: United States\n  text: Our infrastructure is located in the United States.\ntransfers:\n- mechanism: SCC\n  text: Where personal data is transferred across borders we rely on appropriate safeguards such as standard contractual\n    clauses.\nsubprocessors:\n  url: null\n  text: Infrastructure providers. Servers and logs at Render (United States); the database at Neon (United States);\n    sign-in at WorkOS (United States); and Resend (United States) for the watchdog and confirmation emails.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n\
  \  route: Dashboard deletion of account\n  text: Deleting your account removes all data within 30 days and we confirm by email.\nrights:\n- right: Access, portability, restriction and objection\n  text: Depending on where you live you may also have rights to access, portability, restriction and objection,\n    and the right to complain to your data protection authority.\n- right: Export\n  text: The dashboard produces a zip of every memory file, every earlier version and the raw event log.\n- right: Correct\n  text: Tell your agent in chat and it updates its files, keeping the old version visible; or edit an agent-writable\n    file in the dashboard.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and we do not share it with advertisers or data brokers.\n"
source_yaml_url: https://artifacts.apis.io/cornelius-bot/privacy/cornelius-bot-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Cornelius's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Personal Assistant
- Model Context Protocol
- Knowledge Graph
- Productivity
---
