---
api_specs:
- filename: publora-connections-api-openapi.yml
  format: yaml
  label: Publora Connections API
  slug: publora-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publora/openapi/publora-connections-api-openapi.yml
- filename: publora-linkedin-analytics-api-openapi.yml
  format: yaml
  label: Publora LinkedIn Analytics API
  slug: publora-linkedin-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publora/openapi/publora-linkedin-analytics-api-openapi.yml
- filename: publora-logs-api-openapi.yml
  format: yaml
  label: Publora Logs API
  slug: publora-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publora/openapi/publora-logs-api-openapi.yml
- filename: publora-media-api-openapi.yml
  format: yaml
  label: Publora Media API
  slug: publora-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publora/openapi/publora-media-api-openapi.yml
- filename: publora-platform-analytics-api-openapi.yml
  format: yaml
  label: Publora Platform Analytics API
  slug: publora-platform-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publora/openapi/publora-platform-analytics-api-openapi.yml
- filename: publora-posts-api-openapi.yml
  format: yaml
  label: Publora Posts API
  slug: publora-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publora/openapi/publora-posts-api-openapi.yml
- filename: publora-webhooks-api-openapi.yml
  format: yaml
  label: Publora Webhooks API
  slug: publora-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publora/openapi/publora-webhooks-api-openapi.yml
- filename: publora-workspace-api-openapi.yml
  format: yaml
  label: Publora Workspace API
  slug: publora-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/publora/openapi/publora-workspace-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: account information such as your name, email address, login credentials, and billing information where applicable
  - category: contact
    text: email address
  - category: device
    text: technical and usage information such as IP address, browser type, device information, session data, logs, cookies, diagnostics, and security events
  - category: communication
    text: support requests, feedback, and correspondence
  - category: behavioral
    text: Page, profile, and post analytics made available by LinkedIn
  deletion:
    route: Disconnect channel under Channels, or email privacy@publora.com
    text: You may also request deletion of your stored YouTube API Data by contacting privacy@publora.com . We will process the request as soon as possible and no later than 7 calendar days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and operate service
    text: provide, operate, maintain, secure, and improve Publora
  - purpose: publish content
    text: publish, edit, schedule, or delete content on behalf of authorized users or organizations
  - purpose: fraud and security
    text: prevent fraud, abuse, misuse, and security incidents
  - purpose: legal compliance
    text: comply with legal obligations
  retention:
  - period: null
    scope: general personal data
    text: We retain personal data only for as long as reasonably necessary for the purposes described in this Policy, unless a longer period is required or permitted by law.
  - period: 30 calendar days
    scope: YouTube API Data
    text: Other YouTube API Data is refreshed or deleted at least once every 30 calendar days, unless YouTube’s policies permit it to be retained for longer.
  - period: approximately one hour after upload
    scope: Files uploaded but never attached to a post
    text: Files that are uploaded but never attached to a post are deleted automatically approximately one hour after upload.
  - period: 48 hours
    scope: LinkedIn members' social activity data
    text: Members’ social activity data, including comments, reactions, mentions, posts, and related metadata Stored for no more than 48 hours
  rights:
  - right: access, correct, delete, restrict, object, portability
    text: you may have the right to access, correct, delete, restrict, object to, or request portability of your personal data
  - right: withdraw consent
    text: and to withdraw consent where processing is based on consent
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data. We do not sell LinkedIn-derived data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Where required by law, we use appropriate safeguards for cross-border transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Publora
provenance_date: '2026-11-10'
provider_name: Publora
provider_slug: publora
slug: publora-privacy-policy
source_date: '2026-11-10'
source_filename: publora-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://publora.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Publora\naid: publora\nurl: https://publora.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: account information such as your name, email address, login credentials, and billing information where applicable\n- category: contact\n  text: email address\n- category: device\n  text: technical and usage information such as IP address, browser type, device information, session data, logs,\n    cookies, diagnostics, and security events\n- category: communication\n  text: support requests, feedback, and correspondence\n- category: behavioral\n\
  \  text: Page, profile, and post analytics made available by LinkedIn\npurposes:\n- purpose: provide and operate service\n  text: provide, operate, maintain, secure, and improve Publora\n- purpose: publish content\n  text: publish, edit, schedule, or delete content on behalf of authorized users or organizations\n- purpose: fraud and security\n  text: prevent fraud, abuse, misuse, and security incidents\n- purpose: legal compliance\n  text: comply with legal obligations\nretention:\n- scope: general personal data\n  period: null\n  text: We retain personal data only for as long as reasonably necessary for the purposes described in this Policy,\n    unless a longer period is required or permitted by law.\n- scope: YouTube API Data\n  period: 30 calendar days\n  text: Other YouTube API Data is refreshed or deleted at least once every 30 calendar days, unless YouTube’s policies\n    permit it to be retained for longer.\n- scope: Files uploaded but never attached to a post\n  period: approximately\
  \ one hour after upload\n  text: Files that are uploaded but never attached to a post are deleted automatically approximately one hour after\n    upload.\n- scope: LinkedIn members' social activity data\n  period: 48 hours\n  text: Members’ social activity data, including comments, reactions, mentions, posts, and related metadata Stored\n    for no more than 48 hours\nresidency: []\ntransfers:\n- mechanism: other\n  text: Where required by law, we use appropriate safeguards for cross-border transfers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Disconnect channel under Channels, or email privacy@publora.com\n  text: You may also request deletion of your stored YouTube API Data by contacting privacy@publora.com . We will\n    process the request as soon as possible and no later than 7 calendar days.\nrights:\n- right: access, correct, delete, restrict, object, portability\n  text: you may have the right to access, correct,\
  \ delete, restrict, object to, or request portability of your personal\n    data\n- right: withdraw consent\n  text: and to withdraw consent where processing is based on consent\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data. We do not sell LinkedIn-derived data.\n"
source_yaml_url: https://artifacts.apis.io/publora/privacy/publora-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Publora's own page on 2026-11-10.
synthetic: false
tags:
- Social Media
- Publishing
- Scheduling
- MCP
- Content
- Social Media Management
- Webhook
- AI Agents
---
