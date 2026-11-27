---
api_specs:
- filename: cherami-to-access-api-openapi.yml
  format: yaml
  label: Cherami Access API
  slug: cherami-to-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-access-api-openapi.yml
- filename: cherami-to-drafts-api-openapi.yml
  format: yaml
  label: Cherami Drafts API
  slug: cherami-to-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-drafts-api-openapi.yml
- filename: cherami-to-feedback-api-openapi.yml
  format: yaml
  label: Cherami Feedback API
  slug: cherami-to-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-feedback-api-openapi.yml
- filename: cherami-to-inboxes-api-openapi.yml
  format: yaml
  label: Cherami Inboxes API
  slug: cherami-to-inboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-inboxes-api-openapi.yml
- filename: cherami-to-labels-api-openapi.yml
  format: yaml
  label: Cherami Labels API
  slug: cherami-to-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-labels-api-openapi.yml
- filename: cherami-to-messages-api-openapi.yml
  format: yaml
  label: Cherami Messages API
  slug: cherami-to-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-messages-api-openapi.yml
- filename: cherami-to-sending-api-openapi.yml
  format: yaml
  label: Cherami Sending API
  slug: cherami-to-sending-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-sending-api-openapi.yml
- filename: cherami-to-threads-api-openapi.yml
  format: yaml
  label: Cherami Threads API
  slug: cherami-to-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-threads-api-openapi.yml
- filename: cherami-to-trash-api-openapi.yml
  format: yaml
  label: Cherami Trash API
  slug: cherami-to-trash-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-trash-api-openapi.yml
- filename: cherami-to-webhooks-api-openapi.yml
  format: yaml
  label: Cherami Webhooks API
  slug: cherami-to-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cherami-to/openapi/cherami-to-webhooks-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Your verified contact email, account and inbox identifiers
  - category: communication
    text: Incoming messages in full, including headers and attachments; saved drafts; and outgoing mail with its recipients, content, attachments and the result of sending it.
  - category: device
    text: network information such as IP addresses
  - category: behavioral
    text: usage and rate-limit counters
  - category: other
    text: Optional signup questions
  deletion:
    route: Account Settings or email to hello@cherami.to
    text: Request deletion in Account Settings , or email hello@cherami.to naming the account or one of its inboxes.
  dpa:
    available: null
    text: If your work calls for a data-processing agreement, a SOC 2 report, storage in a particular region or handling regulated data, email hello@cherami.to with what you need and why.
    url: null
  purposes:
  - purpose: Provide and protect the service
    text: We use that mail for our own purposes only to provide and protect the service, to review sent mail to detect or investigate abuse, and to meet legal obligations.
  - purpose: Run account and keep it secure
    text: We use it to run your account and keep access to it secure.
  - purpose: Enforce limits and troubleshoot
    text: We use it to enforce limits and troubleshoot.
  residency:
  - region: Outside Quebec and Canada
    text: Your information may be processed outside Quebec and Canada, including in the United States, where different laws and lawful-access rules apply.
  - region: No guaranteed country
    text: We don’t guarantee storage or processing in any particular country.
  retention:
  - period: null
    scope: Messages and drafts you keep
    text: Messages and drafts you keep don’t expire.
  - period: seven days
    scope: Deleted messages in Trash
    text: Deleted received messages, sent copies and conversations go to the inbox’s Trash for seven days, where you can restore them.
  - period: 30 days
    scope: Account deletion
    text: delete the account with its inboxes, mail, drafts, API keys, connections and webhooks within 30 days of receiving the request
  - period: up to 30 days
    scope: Backups
    text: Deleted information can remain in our recovery backups for up to 30 days.
  - period: up to 7 days
    scope: Cloudflare operational logs
    text: Cloudflare’s operational logs are kept for up to 7 days
  - period: six hours
    scope: Agent approvals
    text: An approval to connect an agent expires six hours after you give it
  rights:
  - right: Access
    text: You can ask for access to the personal information we hold about you
  - right: Correction or deletion
    text: have it corrected or deleted
  - right: Withdraw consent
    text: withdraw consent where that applies
  - right: Privacy complaint
    text: make a privacy complaint
  role:
    text: We decide how your account information, answers to optional signup questions, technical information and support correspondence are handled.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell mail or use its contents for advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cherami
provenance_date: '2026-11-09'
provider_name: Cherami
provider_slug: cherami-to
slug: cherami-to-privacy-policy
source_date: '2026-11-09'
source_filename: cherami-to-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cherami.to/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cherami\naid: cherami-to\nurl: https://cherami.to/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We decide how your account information, answers to optional signup questions, technical information and\n    support correspondence are handled.\ndata_categories:\n- category: contact\n  text: Your verified contact email, account and inbox identifiers\n- category: communication\n  text: Incoming messages in full, including headers and attachments; saved drafts; and outgoing mail with its recipients,\n    content, attachments and the result of sending it.\n- category: device\n  text: network information\
  \ such as IP addresses\n- category: behavioral\n  text: usage and rate-limit counters\n- category: other\n  text: Optional signup questions\npurposes:\n- purpose: Provide and protect the service\n  text: We use that mail for our own purposes only to provide and protect the service, to review sent mail to detect\n    or investigate abuse, and to meet legal obligations.\n- purpose: Run account and keep it secure\n  text: We use it to run your account and keep access to it secure.\n- purpose: Enforce limits and troubleshoot\n  text: We use it to enforce limits and troubleshoot.\nretention:\n- scope: Messages and drafts you keep\n  period: null\n  text: Messages and drafts you keep don’t expire.\n- scope: Deleted messages in Trash\n  period: seven days\n  text: Deleted received messages, sent copies and conversations go to the inbox’s Trash for seven days, where you\n    can restore them.\n- scope: Account deletion\n  period: 30 days\n  text: delete the account with its inboxes, mail, drafts,\
  \ API keys, connections and webhooks within 30 days of\n    receiving the request\n- scope: Backups\n  period: up to 30 days\n  text: Deleted information can remain in our recovery backups for up to 30 days.\n- scope: Cloudflare operational logs\n  period: up to 7 days\n  text: Cloudflare’s operational logs are kept for up to 7 days\n- scope: Agent approvals\n  period: six hours\n  text: An approval to connect an agent expires six hours after you give it\nresidency:\n- region: Outside Quebec and Canada\n  text: Your information may be processed outside Quebec and Canada, including in the United States, where different\n    laws and lawful-access rules apply.\n- region: No guaranteed country\n  text: We don’t guarantee storage or processing in any particular country.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: If your work calls for a data-processing agreement, a SOC 2 report, storage in a particular region or handling\n    regulated\
  \ data, email hello@cherami.to with what you need and why.\ndeletion:\n  route: Account Settings or email to hello@cherami.to\n  text: Request deletion in Account Settings , or email hello@cherami.to naming the account or one of its inboxes.\nrights:\n- right: Access\n  text: You can ask for access to the personal information we hold about you\n- right: Correction or deletion\n  text: have it corrected or deleted\n- right: Withdraw consent\n  text: withdraw consent where that applies\n- right: Privacy complaint\n  text: make a privacy complaint\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell mail or use its contents for advertising.\n"
source_yaml_url: https://artifacts.apis.io/cherami-to/privacy/cherami-to-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Cherami's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- AI Agents
- MCP
- Webhook
- Messaging
- Email API
---
