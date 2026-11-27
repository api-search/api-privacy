---
api_specs:
- filename: dibri-ai-openapi-generated.yml
  format: yaml
  label: Dibri API
  slug: dibri-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dibri-ai/openapi/_ae-authored/dibri-ai-openapi-generated.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: your name, email address, organization name and role.'
  - category: financial
    text: 'Billing information: payments are handled by Stripe. We keep your plan, subscription status and Stripe customer and subscription identifiers.'
  - category: communication
    text: Messages you send us through our contact and partner forms or by email.
  - category: device
    text: server logs that include IP addresses, timestamps and browser details, used for security and troubleshooting
  - category: behavioral
    text: the text of questions asked in the app, through the API or MCP server, in the widget or on hosted agent pages, the answers, the sources used, confidence scores, refusals, and feedback or flags on answers
  - category: other
    text: 'Content: documents you upload, website pages you ask us to crawl, files from OneDrive or Google Drive you connect, notes, grounding notes, approvals and the version history of your documents.'
  deletion:
    route: Delete documents and vaults in the app; email speak@dibri.ai to request deletion of personal information
    text: You can delete documents and vaults at any time; they're removed from the live service right away.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the service
    text: 'To run Dibri: indexing your content, answering questions from it, enforcing plan limits and showing your dashboards.'
  - purpose: billing and service emails
    text: To bill you, send service emails (such as receipts, password resets and security notices) and answer your messages.
  - purpose: security
    text: 'To keep Dibri secure: preventing abuse, detecting attacks and investigating problems.'
  - purpose: improvement
    text: To improve Dibri using aggregated usage information.
  residency:
  - region: United States
    text: Dibri is operated from the United States, and information is processed there.
  retention:
  - period: as long as your account is active
    scope: account information and content
    text: We keep account information and content for as long as your account is active.
  - period: within 30 days
    scope: closed accounts
    text: When an account is closed, we delete its content and records within 30 days.
  - period: up to 90 days
    scope: backups
    text: Backups are kept for up to 90 days (daily backups for 30 days, weekly backups for 90)
  rights:
  - right: access, correct, export or delete
    text: You can also ask us to access, correct, export or delete your personal information by emailing speak@dibri.ai .
  - right: additional local-law rights
    text: Depending on where you live, you may have additional rights under local law; we'll honor them as required and respond within 30 days.
  role:
    text: Your organization's content and its users' questions. Documents your organization adds to Dibri, and the questions people ask its agents, are processed on your organization's behalf and under its control.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, we do not use it for advertising, and we never use your content or your users' questions to train AI models.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Dibri
provenance_date: '2026-11-09'
provider_name: Dibri
provider_slug: dibri-ai
slug: dibri-ai-privacy-policy
source_date: '2026-11-09'
source_filename: dibri-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dibri.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Dibri\naid: dibri-ai\nurl: https://dibri.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Your organization's content and its users' questions. Documents your organization adds to Dibri, and the\n    questions people ask its agents, are processed on your organization's behalf and under its control.\ndata_categories:\n- category: identifying\n  text: 'Account information: your name, email address, organization name and role.'\n- category: financial\n  text: 'Billing information: payments are handled by Stripe. We keep your plan, subscription status and Stripe\n    customer and subscription\
  \ identifiers.'\n- category: communication\n  text: Messages you send us through our contact and partner forms or by email.\n- category: device\n  text: server logs that include IP addresses, timestamps and browser details, used for security and troubleshooting\n- category: behavioral\n  text: the text of questions asked in the app, through the API or MCP server, in the widget or on hosted agent\n    pages, the answers, the sources used, confidence scores, refusals, and feedback or flags on answers\n- category: other\n  text: 'Content: documents you upload, website pages you ask us to crawl, files from OneDrive or Google Drive you\n    connect, notes, grounding notes, approvals and the version history of your documents.'\npurposes:\n- purpose: run the service\n  text: 'To run Dibri: indexing your content, answering questions from it, enforcing plan limits and showing your\n    dashboards.'\n- purpose: billing and service emails\n  text: To bill you, send service emails (such as receipts,\
  \ password resets and security notices) and answer your\n    messages.\n- purpose: security\n  text: 'To keep Dibri secure: preventing abuse, detecting attacks and investigating problems.'\n- purpose: improvement\n  text: To improve Dibri using aggregated usage information.\nretention:\n- scope: account information and content\n  period: as long as your account is active\n  text: We keep account information and content for as long as your account is active.\n- scope: closed accounts\n  period: within 30 days\n  text: When an account is closed, we delete its content and records within 30 days.\n- scope: backups\n  period: up to 90 days\n  text: Backups are kept for up to 90 days (daily backups for 30 days, weekly backups for 90)\nresidency:\n- region: United States\n  text: Dibri is operated from the United States, and information is processed there.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete\
  \ documents and vaults in the app; email speak@dibri.ai to request deletion of personal information\n  text: You can delete documents and vaults at any time; they're removed from the live service right away.\nrights:\n- right: access, correct, export or delete\n  text: You can also ask us to access, correct, export or delete your personal information by emailing speak@dibri.ai\n    .\n- right: additional local-law rights\n  text: Depending on where you live, you may have additional rights under local law; we'll honor them as required\n    and respond within 30 days.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, we do not use it for advertising, and we never use your content or\n    your users' questions to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/dibri-ai/privacy/dibri-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Dibri's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Knowledge Base
- RAG
- Customer Service
- MCP
- REST API
---
