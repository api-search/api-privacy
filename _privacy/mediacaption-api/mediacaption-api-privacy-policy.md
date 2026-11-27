---
api_specs:
- filename: mediacaption-api-balance-api-openapi.yml
  format: yaml
  label: MediaCaption API Balance API
  slug: mediacaption-api-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediacaption-api/openapi/mediacaption-api-balance-api-openapi.yml
- filename: mediacaption-api-jobs-api-openapi.yml
  format: yaml
  label: MediaCaption API Jobs API
  slug: mediacaption-api-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediacaption-api/openapi/mediacaption-api-jobs-api-openapi.yml
- filename: mediacaption-api-transcriptions-api-openapi.yml
  format: yaml
  label: MediaCaption API Transcriptions API
  slug: mediacaption-api-transcriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediacaption-api/openapi/mediacaption-api-transcriptions-api-openapi.yml
- filename: mediacaption-api-transcripts-api-openapi.yml
  format: yaml
  label: MediaCaption API Transcripts API
  slug: mediacaption-api-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediacaption-api/openapi/mediacaption-api-transcripts-api-openapi.yml
- filename: mediacaption-api-uploads-api-openapi.yml
  format: yaml
  label: MediaCaption API Uploads API
  slug: mediacaption-api-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediacaption-api/openapi/mediacaption-api-uploads-api-openapi.yml
- filename: mediacaption-api-user-api-openapi.yml
  format: yaml
  label: MediaCaption API User API
  slug: mediacaption-api-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediacaption-api/openapi/mediacaption-api-user-api-openapi.yml
- filename: mediacaption-api-webhooks-api-openapi.yml
  format: yaml
  label: MediaCaption API Webhooks API
  slug: mediacaption-api-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mediacaption-api/openapi/mediacaption-api-webhooks-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: We store your account identifier and email address to manage your account.
  - category: contact
    text: email address
  - category: behavioral
    text: Basic usage analytics (page views, errors) for service improvement
  - category: device
    text: API request logs, including endpoint, method, status code, request ID, timing, error code, and credit movement
  - category: communication
    text: Webhook endpoint URLs, selected event types, delivery attempts, delivery status, response status, timing, and related job IDs
  - category: other
    text: Content URLs, identifiers, or files that you submit
  - category: other
    text: API key metadata, such as key name, status, creation time, last used time, and partial key prefix for display
  deletion:
    route: Request removal of a public output via the report page
    text: Request removal of a public output (contact us via the report page)
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Generate and display transcripts
    text: Generate and display transcripts and related outputs
  - purpose: Authenticate and manage API keys
    text: Authenticate API requests and manage API keys
  - purpose: Webhook deliveries
    text: Send, retry, and debug webhook deliveries
  - purpose: Rate limits, billing and abuse prevention
    text: Apply rate limits, billing, credits, and abuse prevention
  - purpose: Improve service
    text: Improve our service and fix bugs
  - purpose: Advertising
    text: Display advertisements (ad-supported service)
  - purpose: Usage analysis
    text: Analyze usage patterns to enhance user experience
  retention:
  - period: 3 days
    scope: API transcript bodies
    text: API transcript bodies expire after 3 days.
  - period: indefinitely
    scope: Outputs stored on servers
    text: Outputs stored on our servers may be retained indefinitely.
  - period: null
    scope: Billing, analytics, logs and operational metadata
    text: may be retained longer so we can operate the service, resolve support issues, audit usage, and prevent abuse
  rights:
  - right: Request removal of public output
    text: Request removal of a public output (contact us via the report page)
  - right: Opt out of non-essential cookies
    text: Opt out of non-essential cookies
  - right: Discontinue use at any time
    text: Discontinue use of the service at any time
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MediaCaption API
provenance_date: '2026-11-10'
provider_name: MediaCaption API
provider_slug: mediacaption-api
slug: mediacaption-api-privacy-policy
source_date: '2026-11-10'
source_filename: mediacaption-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.mediacaption.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MediaCaption API\naid: mediacaption-api\nurl: https://www.mediacaption.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We store your account identifier and email address to manage your account.\n- category: contact\n  text: email address\n- category: behavioral\n  text: Basic usage analytics (page views, errors) for service improvement\n- category: device\n  text: API request logs, including endpoint, method, status code, request ID, timing, error code, and credit movement\n- category: communication\n  text: Webhook endpoint\
  \ URLs, selected event types, delivery attempts, delivery status, response status, timing,\n    and related job IDs\n- category: other\n  text: Content URLs, identifiers, or files that you submit\n- category: other\n  text: API key metadata, such as key name, status, creation time, last used time, and partial key prefix for display\npurposes:\n- purpose: Generate and display transcripts\n  text: Generate and display transcripts and related outputs\n- purpose: Authenticate and manage API keys\n  text: Authenticate API requests and manage API keys\n- purpose: Webhook deliveries\n  text: Send, retry, and debug webhook deliveries\n- purpose: Rate limits, billing and abuse prevention\n  text: Apply rate limits, billing, credits, and abuse prevention\n- purpose: Improve service\n  text: Improve our service and fix bugs\n- purpose: Advertising\n  text: Display advertisements (ad-supported service)\n- purpose: Usage analysis\n  text: Analyze usage patterns to enhance user experience\nretention:\n\
  - scope: API transcript bodies\n  period: 3 days\n  text: API transcript bodies expire after 3 days.\n- scope: Outputs stored on servers\n  period: indefinitely\n  text: Outputs stored on our servers may be retained indefinitely.\n- scope: Billing, analytics, logs and operational metadata\n  period: null\n  text: may be retained longer so we can operate the service, resolve support issues, audit usage, and prevent abuse\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request removal of a public output via the report page\n  text: Request removal of a public output (contact us via the report page)\nrights:\n- right: Request removal of public output\n  text: Request removal of a public output (contact us via the report page)\n- right: Opt out of non-essential cookies\n  text: Opt out of non-essential cookies\n- right: Discontinue use at any time\n  text: Discontinue use of the service at any\
  \ time\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mediacaption-api/privacy/mediacaption-api-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 21 quoted statements, read from MediaCaption API's own page on 2026-11-10.
synthetic: false
tags:
- YouTube
- Transcription
- Captions
- Subtitles
- Video
- REST
- OpenAPI
- Webhook
- Speech-to-Text
- Media
- Developer Tools
---
