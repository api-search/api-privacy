---
api_specs:
- filename: ambermem-com-openapi-generated.yml
  format: yaml
  label: Amber API
  slug: ambermem-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ambermem-com/openapi/_ae-authored/ambermem-com-openapi-generated.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your PayPal Payer ID (a permanent account identifier) and account verification status.
  - category: communication
    text: Any text content you choose to save through the MCP tools. This is the core service.
  - category: behavioral
    text: 'Connection activity: So we can tell a broken setup from an unused account, your account record keeps the time your AI assistant last connected'
  - category: financial
    text: We track subscription status and payment events for billing purposes.
  - category: device
    text: We take your IP address , combine it with a secret and store only the resulting hash
  deletion:
    route: amber_delete_account tool
    text: To delete all your data, use the amber_delete_account tool.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Amber service
    text: We use your data solely to provide the Amber service
  - purpose: Semantic search embeddings
    text: Generate vector embeddings from your memory text so it can be found by semantic search.
  - purpose: Subscription and billing
    text: Manage your subscription and billing through PayPal.
  - purpose: Rate limiting
    text: it is used for nothing except that rate limit.
  retention:
  - period: null
    scope: Active account memories
    text: Your memories are stored for as long as your account is active.
  - period: more than 12 months
    scope: Cancelled or expired subscription
    text: If your subscription has been cancelled or expired for more than 12 months, we may delete your database.
  - period: 30 days
    scope: Deleted account
    text: deletion is scheduled for 30 days later
  rights:
  - right: Export
    text: You can export all your memories at any time using the amber_export_memories tool, which returns all your data as JSON.
  - right: Delete individual memories
    text: You can delete individual memories at any time using the amber_delete_memory tool.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, share, or use your data for advertising, training AI models, or any purpose other than providing the service to you.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Your memory content and search queries are sent to OpenAI's embedding API to generate the numeric vectors used for matching.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Amber
provenance_date: '2026-11-09'
provider_name: Amber
provider_slug: ambermem-com
slug: ambermem-com-privacy-policy
source_date: '2026-11-09'
source_filename: ambermem-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ambermem.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Amber\naid: ambermem-com\nurl: https://ambermem.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your PayPal Payer ID (a permanent account identifier) and account verification status.\n- category: communication\n  text: Any text content you choose to save through the MCP tools. This is the core service.\n- category: behavioral\n  text: 'Connection activity: So we can tell a broken setup from an unused account, your account record keeps the\n    time your AI assistant last connected'\n- category: financial\n  text: We track subscription\
  \ status and payment events for billing purposes.\n- category: device\n  text: We take your IP address , combine it with a secret and store only the resulting hash\npurposes:\n- purpose: Provide the Amber service\n  text: We use your data solely to provide the Amber service\n- purpose: Semantic search embeddings\n  text: Generate vector embeddings from your memory text so it can be found by semantic search.\n- purpose: Subscription and billing\n  text: Manage your subscription and billing through PayPal.\n- purpose: Rate limiting\n  text: it is used for nothing except that rate limit.\nretention:\n- scope: Active account memories\n  period: null\n  text: Your memories are stored for as long as your account is active.\n- scope: Cancelled or expired subscription\n  period: more than 12 months\n  text: If your subscription has been cancelled or expired for more than 12 months, we may delete your database.\n- scope: Deleted account\n  period: 30 days\n  text: deletion is scheduled for 30 days\
  \ later\nresidency: []\ntransfers:\n- mechanism: other\n  text: Your memory content and search queries are sent to OpenAI's embedding API to generate the numeric vectors\n    used for matching.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: amber_delete_account tool\n  text: To delete all your data, use the amber_delete_account tool.\nrights:\n- right: Export\n  text: You can export all your memories at any time using the amber_export_memories tool, which returns all your\n    data as JSON.\n- right: Delete individual memories\n  text: You can delete individual memories at any time using the amber_delete_memory tool.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, share, or use your data for advertising, training AI models, or any purpose other than providing\n    the service to you.\n"
source_yaml_url: https://artifacts.apis.io/ambermem-com/privacy/ambermem-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Amber's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- Subscription
- MCP
- Personal Data
---
