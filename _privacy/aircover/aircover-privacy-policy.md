---
api_specs:
- filename: aircover-discovery-api-openapi.yml
  format: yaml
  label: Aircover Discovery API
  slug: aircover-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aircover/openapi/aircover-discovery-api-openapi.yml
- filename: aircover-mcp-api-openapi.yml
  format: yaml
  label: Aircover MCP API
  slug: aircover-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aircover/openapi/aircover-mcp-api-openapi.yml
- filename: aircover-oauth-api-openapi.yml
  format: yaml
  label: Aircover OAuth API
  slug: aircover-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aircover/openapi/aircover-oauth-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: Such information includes your full name, work email and company's name.
  - category: contact
    text: your customers and potential customers information (users names, email addresses, phone numbers and job titles)
  - category: communication
    text: transcribed content of conversations of such calls
  - category: behavioral
    text: traffic data that Our Website users' online activities generate such as IP, browser information, session durations and viewed pages
  deletion:
    route: email request to privacy@aircover.ai
    text: You may request deletion of your personal information.
  dpa:
    available: true
    text: You may request a copy of our Data Processing Addendum (DPA) and Transfer Impact Assessment by contacting privacy@aircover.ai
    url: null
  purposes:
  - purpose: operate and enable the Service
    text: Operate and enable the Service
  - purpose: contact and communicate with users
    text: Contact and communicate with you
  - purpose: improve user experience
    text: Improve and customize users' experience with the Service
  - purpose: fraud and misuse prevention
    text: Prevent and remediate fraud, misappropriation, infringements, identity theft, cyber-attacks and other illegal activities and misuse of the Service
  residency:
  - region: US
    text: We process Personal Information in the US.
  retention:
  - period: 60 days
    scope: customer meeting data and transcripts after account termination
    text: Upon account termination, customer meeting data and transcripts are deleted within 60 days.
  - period: for the duration of your subscription
    scope: transcripts and meeting data
    text: Transcripts and meeting data are retained for the duration of your subscription unless requested otherwise
  - period: null
    scope: personal data generally
    text: We keep personal data only for as long as we reasonably need it to manage and grow our relationship with you
  rights:
  - right: access
    text: request to access the Personal Information that We keep about you
  - right: correction, amendment or deletion
    text: request the correction, amendment or deletion of Personal Information related to you if it is inaccurate
  - right: opt out of mailing list
    text: At any time, you may opt out of our mailing list
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, lease or otherwise provide Personal Information to third parties.
  subprocessors:
    text: A current list of sub-processors is available upon request by contacting privacy@aircover.ai
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on Standard Contractual Clauses (SCCs) approved by the European Commission and/or UK authorities
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Aircover
provenance_date: '2026-11-09'
provider_name: Aircover
provider_slug: aircover
slug: aircover-privacy-policy
source_date: '2026-11-09'
source_filename: aircover-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.aircover.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Aircover\naid: aircover\nurl: https://www.aircover.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Such information includes your full name, work email and company's name.\n- category: contact\n  text: your customers and potential customers information (users names, email addresses, phone numbers and job\n    titles)\n- category: communication\n  text: transcribed content of conversations of such calls\n- category: behavioral\n  text: traffic data that Our Website users' online activities generate such as IP, browser information,\
  \ session\n    durations and viewed pages\npurposes:\n- purpose: operate and enable the Service\n  text: Operate and enable the Service\n- purpose: contact and communicate with users\n  text: Contact and communicate with you\n- purpose: improve user experience\n  text: Improve and customize users' experience with the Service\n- purpose: fraud and misuse prevention\n  text: Prevent and remediate fraud, misappropriation, infringements, identity theft, cyber-attacks and other illegal\n    activities and misuse of the Service\nretention:\n- scope: customer meeting data and transcripts after account termination\n  period: 60 days\n  text: Upon account termination, customer meeting data and transcripts are deleted within 60 days.\n- scope: transcripts and meeting data\n  period: for the duration of your subscription\n  text: Transcripts and meeting data are retained for the duration of your subscription unless requested otherwise\n- scope: personal data generally\n  period: null\n  text: We\
  \ keep personal data only for as long as we reasonably need it to manage and grow our relationship with\n    you\nresidency:\n- region: US\n  text: We process Personal Information in the US.\ntransfers:\n- mechanism: SCC\n  text: we rely on Standard Contractual Clauses (SCCs) approved by the European Commission and/or UK authorities\nsubprocessors:\n  url: null\n  text: A current list of sub-processors is available upon request by contacting privacy@aircover.ai\ndpa:\n  available: true\n  url: null\n  text: You may request a copy of our Data Processing Addendum (DPA) and Transfer Impact Assessment by contacting\n    privacy@aircover.ai\ndeletion:\n  route: email request to privacy@aircover.ai\n  text: You may request deletion of your personal information.\nrights:\n- right: access\n  text: request to access the Personal Information that We keep about you\n- right: correction, amendment or deletion\n  text: request the correction, amendment or deletion of Personal Information related to\
  \ you if it is inaccurate\n- right: opt out of mailing list\n  text: At any time, you may opt out of our mailing list\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, lease or otherwise provide Personal Information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/aircover/privacy/aircover-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Aircover's own page on 2026-11-09.
synthetic: false
tags:
- Sales Enablement
- Conversation Intelligence
- Sales Coaching
- Revenue Intelligence
- AI Agents
- MCP
- Agent-Native
- CRM
- Meetings
- Transcription
- OAuth
- Authentication
---
