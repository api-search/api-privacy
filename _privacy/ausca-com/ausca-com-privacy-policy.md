---
api_specs:
- filename: ausca-com-agent-inboxes-api-openapi.yml
  format: yaml
  label: Ausca Agent Inboxes API
  slug: ausca-com-agent-inboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-agent-inboxes-api-openapi.yml
- filename: ausca-com-analyze-document-api-openapi.yml
  format: yaml
  label: Ausca Analyze Document API
  slug: ausca-com-analyze-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-analyze-document-api-openapi.yml
- filename: ausca-com-artifacts-api-openapi.yml
  format: yaml
  label: Ausca Artifacts API
  slug: ausca-com-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-artifacts-api-openapi.yml
- filename: ausca-com-browser-sessions-api-openapi.yml
  format: yaml
  label: Ausca Browser Sessions API
  slug: ausca-com-browser-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-browser-sessions-api-openapi.yml
- filename: ausca-com-extend-inbox-api-openapi.yml
  format: yaml
  label: Ausca Extend Inbox API
  slug: ausca-com-extend-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-extend-inbox-api-openapi.yml
- filename: ausca-com-extract-text-api-openapi.yml
  format: yaml
  label: Ausca Extract Text API
  slug: ausca-com-extract-text-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-extract-text-api-openapi.yml
- filename: ausca-com-invocations-api-openapi.yml
  format: yaml
  label: Ausca Invocations API
  slug: ausca-com-invocations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-invocations-api-openapi.yml
- filename: ausca-com-lease-browser-api-openapi.yml
  format: yaml
  label: Ausca Lease Browser API
  slug: ausca-com-lease-browser-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-lease-browser-api-openapi.yml
- filename: ausca-com-offers-api-openapi.yml
  format: yaml
  label: Ausca Offers API
  slug: ausca-com-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-offers-api-openapi.yml
- filename: ausca-com-open-inbox-api-openapi.yml
  format: yaml
  label: Ausca Open Inbox API
  slug: ausca-com-open-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-open-inbox-api-openapi.yml
- filename: ausca-com-transcribe-media-api-openapi.yml
  format: yaml
  label: Ausca Transcribe Media API
  slug: ausca-com-transcribe-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ausca-com/openapi/ausca-com-transcribe-media-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: behavioral
    text: Ausca uses Microsoft Clarity to understand page performance and interaction.
  - category: device
    text: Clarity may use first-party and third-party cookies to connect page views into a visit
  - category: location
    text: For visitors in the EEA, United Kingdom, and Switzerland, Clarity withholds those cookies until analytics storage is explicitly allowed.
  - category: other
    text: Cloudflare processes request metadata for routing, abuse prevention, reliability, and aggregate operational analytics.
  - category: financial
    text: Paid calls produce settlement and receipt records needed to execute, verify, reconcile, and prevent replay of a transaction.
  deletion:
    route: null
    text: Each service SKILL.md states its exact inputs, limits, lifecycle, and cleanup behavior.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: website analytics
    text: Ausca uses Microsoft Clarity to understand page performance and interaction.
  - purpose: service execution
    text: Ausca processes service inputs to perform the requested job.
  - purpose: routing, abuse prevention, reliability
    text: Cloudflare processes request metadata for routing, abuse prevention, reliability, and aggregate operational analytics.
  - purpose: transaction verification
    text: Paid calls produce settlement and receipt records needed to execute, verify, reconcile, and prevent replay of a transaction.
  retention:
  - period: 24 hours
    scope: input and result artifacts
    text: Input and result artifacts are retained for 24 hours.
  - period: null
    scope: agent inbox
    text: An agent inbox retains messages and clean attachments until it is deleted or expires.
  - period: null
    scope: browser lease
    text: A browser lease ends when it is closed or expires.
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
name: Ausca
provenance_date: '2026-11-09'
provider_name: Ausca
provider_slug: ausca-com
slug: ausca-com-privacy-policy
source_date: '2026-11-09'
source_filename: ausca-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ausca.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Ausca\naid: ausca-com\nurl: https://ausca.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: behavioral\n  text: Ausca uses Microsoft Clarity to understand page performance and interaction.\n- category: device\n  text: Clarity may use first-party and third-party cookies to connect page views into a visit\n- category: location\n  text: For visitors in the EEA, United Kingdom, and Switzerland, Clarity withholds those cookies until analytics\n    storage is explicitly allowed.\n- category: other\n  text: Cloudflare processes request metadata for routing,\
  \ abuse prevention, reliability, and aggregate operational\n    analytics.\n- category: financial\n  text: Paid calls produce settlement and receipt records needed to execute, verify, reconcile, and prevent replay\n    of a transaction.\npurposes:\n- purpose: website analytics\n  text: Ausca uses Microsoft Clarity to understand page performance and interaction.\n- purpose: service execution\n  text: Ausca processes service inputs to perform the requested job.\n- purpose: routing, abuse prevention, reliability\n  text: Cloudflare processes request metadata for routing, abuse prevention, reliability, and aggregate operational\n    analytics.\n- purpose: transaction verification\n  text: Paid calls produce settlement and receipt records needed to execute, verify, reconcile, and prevent replay\n    of a transaction.\nretention:\n- scope: input and result artifacts\n  period: 24 hours\n  text: Input and result artifacts are retained for 24 hours.\n- scope: agent inbox\n  period: null\n  text:\
  \ An agent inbox retains messages and clean attachments until it is deleted or expires.\n- scope: browser lease\n  period: null\n  text: A browser lease ends when it is closed or expires.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: Each service SKILL.md states its exact inputs, limits, lifecycle, and cleanup behavior.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ausca-com/privacy/ausca-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
summary_line: 13 quoted statements, read from Ausca's own page on 2026-11-09.
synthetic: false
tags:
- Pay-per-call APIs
- Agent Infrastructure
- Document OCR
- Media transcription
- Inbox verification
---
