---
api_specs:
- filename: clawdcall-com-cc-api-openapi.yml
  format: yaml
  label: ClawdCall Cc API
  slug: clawdcall-com-cc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawdcall-com/openapi/clawdcall-com-cc-api-openapi.yml
- filename: clawdcall-com-external-api-openapi.yml
  format: yaml
  label: ClawdCall External API
  slug: clawdcall-com-external-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clawdcall-com/openapi/clawdcall-com-external-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information name email company
  - category: communication
    text: call recordings voice audio streams call transcripts
  - category: contact
    text: phone numbers involved in the call
  - category: device
    text: API requests device data logs and diagnostics
  - category: behavioral
    text: call outcome data
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate the Service
    text: 'We use personal information to: operate the Service route calls generate transcripts prevent fraud and abuse support customers improve reliability'
  - purpose: AI speech processing
    text: 'These technologies may analyze call audio or transcripts in order to: generate responses during conversations produce call summaries improve system performance'
  - purpose: service improvement
    text: 'We may use aggregated or anonymized call data to: improve speech recognition enhance system reliability optimize automated call performance'
  residency:
  - region: US
    text: Primary data processing regions AWS us-east-1
  retention:
  - period: 4 hours
    scope: metadata
    text: Default metadata retention 4 hours, with call detail records retained longer where required for billing and operations
  - period: 30 days
    scope: transcripts
    text: Default transcript retention 30 days by default, unless a shorter or longer retention period is configured
  - period: null
    scope: audio
    text: Default audio retention Disabled by default, but configurable by customer
  rights:
  - right: access
    text: access personal information we hold about you
  - right: correction
    text: request correction of inaccurate data
  - right: deletion
    text: request deletion of certain information
  - right: objection
    text: object to processing in certain circumstances
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
name: ClawdCall
provenance_date: '2026-11-09'
provider_name: ClawdCall
provider_slug: clawdcall-com
slug: clawdcall-com-privacy-policy
source_date: '2026-11-09'
source_filename: clawdcall-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://clawdcall.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ClawdCall\naid: clawdcall-com\nurl: https://clawdcall.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information name email company\n- category: communication\n  text: call recordings voice audio streams call transcripts\n- category: contact\n  text: phone numbers involved in the call\n- category: device\n  text: API requests device data logs and diagnostics\n- category: behavioral\n  text: call outcome data\npurposes:\n- purpose: operate the Service\n  text: 'We use personal information to: operate the Service\
  \ route calls generate transcripts prevent fraud and\n    abuse support customers improve reliability'\n- purpose: AI speech processing\n  text: 'These technologies may analyze call audio or transcripts in order to: generate responses during conversations\n    produce call summaries improve system performance'\n- purpose: service improvement\n  text: 'We may use aggregated or anonymized call data to: improve speech recognition enhance system reliability\n    optimize automated call performance'\nretention:\n- scope: metadata\n  period: 4 hours\n  text: Default metadata retention 4 hours, with call detail records retained longer where required for billing\n    and operations\n- scope: transcripts\n  period: 30 days\n  text: Default transcript retention 30 days by default, unless a shorter or longer retention period is configured\n- scope: audio\n  period: null\n  text: Default audio retention Disabled by default, but configurable by customer\nresidency:\n- region: US\n  text: Primary data\
  \ processing regions AWS us-east-1\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: access personal information we hold about you\n- right: correction\n  text: request correction of inaccurate data\n- right: deletion\n  text: request deletion of certain information\n- right: objection\n  text: object to processing in certain circumstances\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clawdcall-com/privacy/clawdcall-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- rights
summary_line: 16 quoted statements, read from ClawdCall's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Voice
- Automation
- Agents
- Telephony
---
