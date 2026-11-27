---
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information — When you sign in with Google, we receive your email address, name, and profile picture.
  - category: communication
    text: WhatsApp messages — Messages sent and received through WhatsApp accounts you connect, including text, media, and metadata (sender, timestamp, delivery status).
  - category: device
    text: Usage data — Logs of API calls, Edge Function invocations, and billing events for operating the service.
  deletion:
    route: Delete organization in the app; request full account deletion by contacting us
    text: You can delete your organization at any time, which removes associated contacts, conversations, and messages. Request full account deletion by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Message routing
    text: Routing WhatsApp messages between Meta's WhatsApp Business API and your AI agents or team members.
  - purpose: Conversation storage
    text: Storing your conversations so you can access them from the web interface.
  - purpose: Billing and usage reporting
    text: Billing and usage reporting.
  - purpose: Troubleshooting and security
    text: Troubleshooting and security.
  retention:
  - period: null
    scope: Active account data
    text: Data is retained for as long as your account is active.
  - period: null
    scope: Deleted data
    text: Deleted data is removed from active databases immediately; backups may retain data for up to 30 days.
  rights:
  - right: Access
    text: Access — Your data is available through the web interface at any time.
  - right: Export
    text: Export — You can export your data via the REST API.
  - right: Deletion
    text: Deletion — You can delete your organization at any time, which removes associated contacts, conversations, and messages.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'We use the following processors to operate the service: Supabase — hosts the database, authentication, and Edge Functions. Meta (WhatsApp) — delivers messages to and from your WhatsApp accounts. Google — provides sign-in and, optionally, Gemini-based media preprocessing for accounts that enable it. LLM providers (OpenAI, Anthropic, Google, Groq, etc.) — only when you configure an AI agent to use them.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: openbsp-dev
provenance_date: '2026-11-10'
provider_name: openbsp-dev
provider_slug: openbsp-dev
slug: openbsp-dev-privacy-policy
source_date: '2026-11-10'
source_filename: openbsp-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://openbsp.dev/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: openbsp-dev\naid: openbsp-dev\nurl: https://openbsp.dev/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information — When you sign in with Google, we receive your email address, name, and profile picture.\n- category: communication\n  text: WhatsApp messages — Messages sent and received through WhatsApp accounts you connect, including text, media,\n    and metadata (sender, timestamp, delivery status).\n- category: device\n  text: Usage data — Logs of API calls, Edge Function invocations, and billing events for\
  \ operating the service.\npurposes:\n- purpose: Message routing\n  text: Routing WhatsApp messages between Meta's WhatsApp Business API and your AI agents or team members.\n- purpose: Conversation storage\n  text: Storing your conversations so you can access them from the web interface.\n- purpose: Billing and usage reporting\n  text: Billing and usage reporting.\n- purpose: Troubleshooting and security\n  text: Troubleshooting and security.\nretention:\n- scope: Active account data\n  period: null\n  text: Data is retained for as long as your account is active.\n- scope: Deleted data\n  period: null\n  text: Deleted data is removed from active databases immediately; backups may retain data for up to 30 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We use the following processors to operate the service: Supabase — hosts the database, authentication,\n    and Edge Functions. Meta (WhatsApp) — delivers messages to and from your WhatsApp accounts. Google — provides\n\
  \    sign-in and, optionally, Gemini-based media preprocessing for accounts that enable it. LLM providers (OpenAI,\n    Anthropic, Google, Groq, etc.) — only when you configure an AI agent to use them.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete organization in the app; request full account deletion by contacting us\n  text: You can delete your organization at any time, which removes associated contacts, conversations, and messages.\n    Request full account deletion by contacting us.\nrights:\n- right: Access\n  text: Access — Your data is available through the web interface at any time.\n- right: Export\n  text: Export — You can export your data via the REST API.\n- right: Deletion\n  text: Deletion — You can delete your organization at any time, which removes associated contacts, conversations,\n    and messages.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/openbsp-dev/privacy/openbsp-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 14 quoted statements, read from openbsp-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Open Source
- WhatsApp
- Messaging
- Artificial Intelligence
---
