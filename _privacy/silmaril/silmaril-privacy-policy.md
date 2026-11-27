---
claim_count: 7
description: ''
doc:
  data_categories:
  - category: other
    text: We process prompts, metadata, and threat scores to provide real-time filtering.
  deletion:
    route: automatic after POC termination
    text: All Service Data and logs are permanently deleted within 30 days of POC termination unless a production agreement is signed.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: real-time filtering
    text: We process prompts, metadata, and threat scores to provide real-time filtering.
  - purpose: security testing
    text: Silmaril uses the Client’s UI and APIs to send simulated malicious content to identify security gaps.
  residency:
  - region: US
    text: Hosted on AWS (US-East-1 & US-West-2).
  retention:
  - period: 30 days
    scope: Service Data and logs
    text: All Service Data and logs are permanently deleted within 30 days of POC termination unless a production agreement is signed.
  role:
    text: Silmaril acts as a Data Processor for all Client Service Data.
    value: processor
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
name: Silmaril
provenance_date: '2026-11-10'
provider_name: Silmaril
provider_slug: silmaril
slug: silmaril-privacy-policy
source_date: '2026-11-10'
source_filename: silmaril-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.silmaril.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Silmaril\naid: silmaril\nurl: https://www.silmaril.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: Silmaril acts as a Data Processor for all Client Service Data.\ndata_categories:\n- category: other\n  text: We process prompts, metadata, and threat scores to provide real-time filtering.\npurposes:\n- purpose: real-time filtering\n  text: We process prompts, metadata, and threat scores to provide real-time filtering.\n- purpose: security testing\n  text: Silmaril uses the Client’s UI and APIs to send simulated malicious content to identify security gaps.\nretention:\n- scope: Service\
  \ Data and logs\n  period: 30 days\n  text: All Service Data and logs are permanently deleted within 30 days of POC termination unless a production\n    agreement is signed.\nresidency:\n- region: US\n  text: Hosted on AWS (US-East-1 & US-West-2).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: automatic after POC termination\n  text: All Service Data and logs are permanently deleted within 30 days of POC termination unless a production\n    agreement is signed.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/silmaril/privacy/silmaril-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
summary_line: 7 quoted statements, read from Silmaril's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Security
- AI Firewall
- Prompt Injection
- Agent Security
- Runtime Security
- Guardrails
- MCP
- LLM Security
- Developer Tools
---
