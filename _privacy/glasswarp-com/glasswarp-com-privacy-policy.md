---
api_specs:
- filename: glasswarp-com-agent-api-openapi.yml
  format: yaml
  label: glasswarp-com Agent API
  slug: glasswarp-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glasswarp-com/openapi/glasswarp-com-agent-api-openapi.yml
- filename: glasswarp-com-api-keys-api-openapi.yml
  format: yaml
  label: glasswarp-com API Keys API
  slug: glasswarp-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glasswarp-com/openapi/glasswarp-com-api-keys-api-openapi.yml
- filename: glasswarp-com-apps-api-openapi.yml
  format: yaml
  label: glasswarp-com Apps API
  slug: glasswarp-com-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glasswarp-com/openapi/glasswarp-com-apps-api-openapi.yml
- filename: glasswarp-com-grounding-api-openapi.yml
  format: yaml
  label: glasswarp-com Grounding API
  slug: glasswarp-com-grounding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glasswarp-com/openapi/glasswarp-com-grounding-api-openapi.yml
- filename: glasswarp-com-input-api-openapi.yml
  format: yaml
  label: glasswarp-com Input API
  slug: glasswarp-com-input-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glasswarp-com/openapi/glasswarp-com-input-api-openapi.yml
- filename: glasswarp-com-rigs-api-openapi.yml
  format: yaml
  label: glasswarp-com Rigs API
  slug: glasswarp-com-rigs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glasswarp-com/openapi/glasswarp-com-rigs-api-openapi.yml
- filename: glasswarp-com-screenshots-api-openapi.yml
  format: yaml
  label: glasswarp-com Screenshots API
  slug: glasswarp-com-screenshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glasswarp-com/openapi/glasswarp-com-screenshots-api-openapi.yml
- filename: glasswarp-com-sessions-api-openapi.yml
  format: yaml
  label: glasswarp-com Sessions API
  slug: glasswarp-com-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glasswarp-com/openapi/glasswarp-com-sessions-api-openapi.yml
- filename: glasswarp-com-streaming-api-openapi.yml
  format: yaml
  label: glasswarp-com Streaming API
  slug: glasswarp-com-streaming-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glasswarp-com/openapi/glasswarp-com-streaming-api-openapi.yml
- filename: glasswarp-com-webhooks-api-openapi.yml
  format: yaml
  label: glasswarp-com Webhooks API
  slug: glasswarp-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/glasswarp-com/openapi/glasswarp-com-webhooks-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, account identifiers, and authentication data processed through our identity provider.
  - category: financial
    text: Plan or subscription status, usage metering metadata (for example, session duration for billing), invoices, and payment provider customer / payment identifiers when paid plans are enabled
  - category: device
    text: Hardware and capability metadata reported by the host agent (for example, display or encode-related capabilities needed to operate sessions)
  - category: behavioral
    text: Connection and performance telemetry shown in the product or collected for operation
  - category: communication
    text: Support communications you send to our contact addresses (for example, inbound mail to our published support address)
  deletion:
    route: Request account closure by email to hello@glasswarp.com
    text: To exercise rights, or to request account closure, contact hello@glasswarp.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the Service
    text: Provide, operate, secure, and improve the Service
  - purpose: Billing and fraud prevention
    text: Bill usage, prevent fraud, and process payments
  - purpose: Communications and support
    text: Communicate about the Service, security notices, and support
  - purpose: Advertising measurement
    text: We also load the Reddit Ads pixel (Reddit, Inc.) to measure whether ads on Reddit led to site visits and account sign-ups.
  residency:
  - region: United States
    text: We operate the Service from the United States.
  retention:
  - period: null
    scope: Account, host, billing, and audit metadata
    text: We retain account, host, billing, and audit metadata while your account is active and as reasonably needed for security, legal, tax, and billing purposes.
  - period: null
    scope: Operational logs and stream telemetry
    text: Operational logs and stream telemetry are kept for shorter periods appropriate to diagnosis and abuse prevention.
  - period: null
    scope: Desktop video
    text: Desktop video is not stored in our database.
  rights:
  - right: Access, correct, delete, or obtain a copy
    text: Depending on where you live, you may have rights to access, correct, delete, or obtain a copy of personal information, or to object to or restrict certain processing.
  role:
    text: This policy covers personal information and related data we process as a service operator.
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: glasswarp-com
provenance_date: '2026-11-09'
provider_name: glasswarp-com
provider_slug: glasswarp-com
slug: glasswarp-com-privacy-policy
source_date: '2026-11-09'
source_filename: glasswarp-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.glasswarp.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: glasswarp-com\naid: glasswarp-com\nurl: https://www.glasswarp.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: This policy covers personal information and related data we process as a service operator.\ndata_categories:\n- category: identifying\n  text: Email address, account identifiers, and authentication data processed through our identity provider.\n- category: financial\n  text: Plan or subscription status, usage metering metadata (for example, session duration for billing), invoices,\n    and payment provider customer / payment identifiers when paid plans are enabled\n- category:\
  \ device\n  text: Hardware and capability metadata reported by the host agent (for example, display or encode-related capabilities\n    needed to operate sessions)\n- category: behavioral\n  text: Connection and performance telemetry shown in the product or collected for operation\n- category: communication\n  text: Support communications you send to our contact addresses (for example, inbound mail to our published support\n    address)\npurposes:\n- purpose: Provide and operate the Service\n  text: Provide, operate, secure, and improve the Service\n- purpose: Billing and fraud prevention\n  text: Bill usage, prevent fraud, and process payments\n- purpose: Communications and support\n  text: Communicate about the Service, security notices, and support\n- purpose: Advertising measurement\n  text: We also load the Reddit Ads pixel (Reddit, Inc.) to measure whether ads on Reddit led to site visits and\n    account sign-ups.\nretention:\n- scope: Account, host, billing, and audit metadata\n\
  \  period: null\n  text: We retain account, host, billing, and audit metadata while your account is active and as reasonably needed\n    for security, legal, tax, and billing purposes.\n- scope: Operational logs and stream telemetry\n  period: null\n  text: Operational logs and stream telemetry are kept for shorter periods appropriate to diagnosis and abuse prevention.\n- scope: Desktop video\n  period: null\n  text: Desktop video is not stored in our database.\nresidency:\n- region: United States\n  text: We operate the Service from the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request account closure by email to hello@glasswarp.com\n  text: To exercise rights, or to request account closure, contact hello@glasswarp.com.\nrights:\n- right: Access, correct, delete, or obtain a copy\n  text: Depending on where you live, you may have rights to access, correct, delete, or obtain a copy of\
  \ personal\n    information, or to object to or restrict certain processing.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/glasswarp-com/privacy/glasswarp-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from glasswarp-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automation
- Windows
- RPA
---
