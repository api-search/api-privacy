---
api_specs:
- filename: betterstack-heartbeats-api-openapi.yml
  format: yaml
  label: Better Stack Heartbeats API
  slug: betterstack-heartbeats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betterstack/openapi/betterstack-heartbeats-api-openapi.yml
- filename: betterstack-incidents-api-openapi.yml
  format: yaml
  label: Better Stack Incidents API
  slug: betterstack-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betterstack/openapi/betterstack-incidents-api-openapi.yml
- filename: betterstack-monitors-api-openapi.yml
  format: yaml
  label: Better Stack Monitors API
  slug: betterstack-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betterstack/openapi/betterstack-monitors-api-openapi.yml
- filename: betterstack-status-pages-api-openapi.yml
  format: yaml
  label: Better Stack Status Pages API
  slug: betterstack-status-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betterstack/openapi/betterstack-status-pages-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: first and second names email address professional experience and other PII provided by you voluntarily when you use our Services
  - category: device
    text: the browser name and type the type of computer or device accessing our Service
  - category: location
    text: IP address
  - category: behavioral
    text: time spent on the Service
  deletion:
    route: Email hello@betterstack.com
    text: Right to erasure. You may also ask us to erase your PII from our systems.
  dpa:
    available: true
    text: A full list of our sub-processors is found in our DPA .
    url: null
  purposes:
  - purpose: Provide services
    text: Provide our Services to you.
  - purpose: Recruitment
    text: Process an application as part of Better Stack’s recruitment.
  - purpose: Marketing
    text: Market our Services. We may market our current or future Services if you subscribe to our newsletter on our Site
  - purpose: Improve services
    text: Improve our Services. This purpose includes the following processing activities using technical information
  - purpose: Fraud prevention
    text: Find and prevent fraud
  residency:
  - region: European Union
    text: We process personal data primarily in the European Union.
  retention:
  - period: null
    scope: Personal data
    text: Better Stack stores your PII only if it is legally permitted and necessary for the purposes for which the data were collected or we are legally obliged to do so.
  rights:
  - right: Access
    text: Right of access. Better Stack offers you access to your PII we process.
  - right: Erasure
    text: Right to erasure. You may also ask us to erase your PII from our systems.
  - right: Restriction of processing
    text: Right to restriction of processing. You may request us to restrict certain processing of your personal data.
  role:
    text: Better Stack shall process PII only as a processor or sub-processor (as applicable to your use of the Services).
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: A full list of our sub-processors is found in our DPA .
    url: null
  transfers:
  - mechanism: SCC
    text: such as standard contractual clauses or binding internal company rules
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Better Stack
provenance_date: '2026-11-09'
provider_name: Better Stack
provider_slug: betterstack
slug: betterstack-privacy-policy
source_date: '2026-11-09'
source_filename: betterstack-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://betterstack.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Better Stack\naid: betterstack\nurl: https://betterstack.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Better Stack shall process PII only as a processor or sub-processor (as applicable to your use of the Services).\ndata_categories:\n- category: identifying\n  text: first and second names email address professional experience and other PII provided by you voluntarily when\n    you use our Services\n- category: device\n  text: the browser name and type the type of computer or device accessing our Service\n- category: location\n  text: IP address\n- category: behavioral\n  text: time\
  \ spent on the Service\npurposes:\n- purpose: Provide services\n  text: Provide our Services to you.\n- purpose: Recruitment\n  text: Process an application as part of Better Stack’s recruitment.\n- purpose: Marketing\n  text: Market our Services. We may market our current or future Services if you subscribe to our newsletter on\n    our Site\n- purpose: Improve services\n  text: Improve our Services. This purpose includes the following processing activities using technical information\n- purpose: Fraud prevention\n  text: Find and prevent fraud\nretention:\n- scope: Personal data\n  period: null\n  text: Better Stack stores your PII only if it is legally permitted and necessary for the purposes for which the\n    data were collected or we are legally obliged to do so.\nresidency:\n- region: European Union\n  text: We process personal data primarily in the European Union.\ntransfers:\n- mechanism: SCC\n  text: such as standard contractual clauses or binding internal company rules\nsubprocessors:\n\
  \  url: null\n  text: A full list of our sub-processors is found in our DPA .\ndpa:\n  available: true\n  url: null\n  text: A full list of our sub-processors is found in our DPA .\ndeletion:\n  route: Email hello@betterstack.com\n  text: Right to erasure. You may also ask us to erase your PII from our systems.\nrights:\n- right: Access\n  text: Right of access. Better Stack offers you access to your PII we process.\n- right: Erasure\n  text: Right to erasure. You may also ask us to erase your PII from our systems.\n- right: Restriction of processing\n  text: Right to restriction of processing. You may request us to restrict certain processing of your personal data.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/betterstack/privacy/betterstack-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 19 quoted statements, read from Better Stack's own page on 2026-11-09.
synthetic: false
tags:
- Observability
- Uptime Monitoring
- Incidents
- Logs
- Monitoring
- Status Pages
- On-Call
- Error Tracking
- OpenTelemetry
- MCP
---
