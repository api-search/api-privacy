---
api_specs:
- filename: beatapi-account-api-openapi.yml
  format: yaml
  label: BeatAPI Account API
  slug: beatapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-account-api-openapi.yml
- filename: beatapi-capabilities-api-openapi.yml
  format: yaml
  label: BeatAPI Capabilities API
  slug: beatapi-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-capabilities-api-openapi.yml
- filename: beatapi-decisions-api-openapi.yml
  format: yaml
  label: BeatAPI Decisions API
  slug: beatapi-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-decisions-api-openapi.yml
- filename: beatapi-ecommerce-video-api-openapi.yml
  format: yaml
  label: BeatAPI Ecommerce Video API
  slug: beatapi-ecommerce-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-ecommerce-video-api-openapi.yml
- filename: beatapi-effects-api-openapi.yml
  format: yaml
  label: BeatAPI Effects API
  slug: beatapi-effects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-effects-api-openapi.yml
- filename: beatapi-files-api-openapi.yml
  format: yaml
  label: BeatAPI Files API
  slug: beatapi-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-files-api-openapi.yml
- filename: beatapi-generation-api-openapi.yml
  format: yaml
  label: BeatAPI Generation API
  slug: beatapi-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-generation-api-openapi.yml
- filename: beatapi-music-video-api-openapi.yml
  format: yaml
  label: BeatAPI Music Video API
  slug: beatapi-music-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-music-video-api-openapi.yml
- filename: beatapi-realtime-video-api-openapi.yml
  format: yaml
  label: BeatAPI Realtime Video API
  slug: beatapi-realtime-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-realtime-video-api-openapi.yml
- filename: beatapi-social-data-api-openapi.yml
  format: yaml
  label: BeatAPI Social Data API
  slug: beatapi-social-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-social-data-api-openapi.yml
- filename: beatapi-tasks-api-openapi.yml
  format: yaml
  label: BeatAPI Tasks API
  slug: beatapi-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-tasks-api-openapi.yml
- filename: beatapi-text-api-openapi.yml
  format: yaml
  label: BeatAPI Text API
  slug: beatapi-text-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-text-api-openapi.yml
- filename: beatapi-usage-api-openapi.yml
  format: yaml
  label: BeatAPI Usage API
  slug: beatapi-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-usage-api-openapi.yml
- filename: beatapi-video-analysis-api-openapi.yml
  format: yaml
  label: BeatAPI Video Analysis API
  slug: beatapi-video-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-video-analysis-api-openapi.yml
- filename: beatapi-web-search-api-openapi.yml
  format: yaml
  label: BeatAPI Web Search API
  slug: beatapi-web-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-web-search-api-openapi.yml
- filename: beatapi-webhooks-api-openapi.yml
  format: yaml
  label: BeatAPI Webhooks API
  slug: beatapi-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-webhooks-api-openapi.yml
- filename: beatapi-workflows-api-openapi.yml
  format: yaml
  label: BeatAPI Workflows API
  slug: beatapi-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatapi/openapi/beatapi-workflows-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address, login provider details, and account settings.
  - category: financial
    text: Purchase amount, balance added, transaction status, billing email, and payment processor references.
  - category: device
    text: IP address, browser, device, approximate location, cookies, and similar data used for authentication, fraud prevention, abuse detection, and reliability.
  - category: communication
    text: Messages, attachments, and diagnostic details you send when requesting help.
  - category: other
    text: Prompts, metadata, uploaded files, source URLs, generated videos, thumbnails, and other content you submit or receive through a workflow.
  deletion:
    route: Contact support@beatapi.io for privacy and deletion requests
    text: Contact support@beatapi.io for privacy and deletion requests.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Create and secure accounts
    text: Create and secure your account.
  - purpose: Run AI video workflows
    text: Run AI video workflows, process uploads, deliver outputs, and send webhook events.
  - purpose: Billing and usage tracking
    text: Track billing, usage, failures, retries, and task history.
  - purpose: Security and abuse prevention
    text: Monitor performance, debug incidents, prevent abuse, and protect the service.
  - purpose: Product improvement
    text: Improve BeatAPI using aggregated or de-identified usage data.
  retention:
  - period: null
    scope: Account, billing, usage, file, task and support records
    text: We keep account, billing, API usage, file, task, webhook, Realtime session metadata, and support records for as long as needed to provide the service, comply with legal obligations, resolve disputes, prevent abuse, and maintain audit logs.
  - period: until the associated authorization expires
    scope: OAuth credential hashes
    text: Credential hashes may be retained until the associated authorization expires for replay detection.
  rights:
  - right: access, correction, export, deletion
    text: You may request access, correction, export, or deletion of certain personal information by contacting us.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BeatAPI
provenance_date: '2026-11-09'
provider_name: BeatAPI
provider_slug: beatapi
slug: beatapi-privacy-policy
source_date: '2026-11-09'
source_filename: beatapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://beatapi.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BeatAPI\naid: beatapi\nurl: https://beatapi.io/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your name, email address, login provider details, and account settings.\n- category: financial\n  text: Purchase amount, balance added, transaction status, billing email, and payment processor references.\n- category: device\n  text: IP address, browser, device, approximate location, cookies, and similar data used for authentication, fraud\n    prevention, abuse detection, and reliability.\n- category: communication\n  text: Messages,\
  \ attachments, and diagnostic details you send when requesting help.\n- category: other\n  text: Prompts, metadata, uploaded files, source URLs, generated videos, thumbnails, and other content you submit\n    or receive through a workflow.\npurposes:\n- purpose: Create and secure accounts\n  text: Create and secure your account.\n- purpose: Run AI video workflows\n  text: Run AI video workflows, process uploads, deliver outputs, and send webhook events.\n- purpose: Billing and usage tracking\n  text: Track billing, usage, failures, retries, and task history.\n- purpose: Security and abuse prevention\n  text: Monitor performance, debug incidents, prevent abuse, and protect the service.\n- purpose: Product improvement\n  text: Improve BeatAPI using aggregated or de-identified usage data.\nretention:\n- scope: Account, billing, usage, file, task and support records\n  period: null\n  text: We keep account, billing, API usage, file, task, webhook, Realtime session metadata, and support records\n\
  \    for as long as needed to provide the service, comply with legal obligations, resolve disputes, prevent abuse,\n    and maintain audit logs.\n- scope: OAuth credential hashes\n  period: until the associated authorization expires\n  text: Credential hashes may be retained until the associated authorization expires for replay detection.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact support@beatapi.io for privacy and deletion requests\n  text: Contact support@beatapi.io for privacy and deletion requests.\nrights:\n- right: access, correction, export, deletion\n  text: You may request access, correction, export, or deletion of certain personal information by contacting us.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/beatapi/privacy/beatapi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from BeatAPI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Platform
- Unified API
- Data Integration
---
