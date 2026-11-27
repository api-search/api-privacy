---
api_specs:
- filename: anamai-avatars-api-openapi.yml
  format: yaml
  label: Anam.ai Avatars API
  slug: anamai-avatars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anamai/openapi/anamai-avatars-api-openapi.yml
- filename: anamai-engine-api-openapi.yml
  format: yaml
  label: Anam.ai Engine API
  slug: anamai-engine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anamai/openapi/anamai-engine-api-openapi.yml
- filename: anamai-knowledge-api-openapi.yml
  format: yaml
  label: Anam.ai Knowledge API
  slug: anamai-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anamai/openapi/anamai-knowledge-api-openapi.yml
- filename: anamai-meetings-api-openapi.yml
  format: yaml
  label: Anam.ai Meetings API
  slug: anamai-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anamai/openapi/anamai-meetings-api-openapi.yml
- filename: anamai-personas-api-openapi.yml
  format: yaml
  label: Anam.ai Personas API
  slug: anamai-personas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anamai/openapi/anamai-personas-api-openapi.yml
- filename: anamai-sessions-api-openapi.yml
  format: yaml
  label: Anam.ai Sessions API
  slug: anamai-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anamai/openapi/anamai-sessions-api-openapi.yml
- filename: anamai-share-links-api-openapi.yml
  format: yaml
  label: Anam.ai Share Links API
  slug: anamai-share-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anamai/openapi/anamai-share-links-api-openapi.yml
- filename: anamai-tools-api-openapi.yml
  format: yaml
  label: Anam.ai Tools API
  slug: anamai-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anamai/openapi/anamai-tools-api-openapi.yml
- filename: anamai-voices-api-openapi.yml
  format: yaml
  label: Anam.ai Voices API
  slug: anamai-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anamai/openapi/anamai-voices-api-openapi.yml
- filename: anamai-llms-api-openapi.yml
  format: yaml
  label: Anam.ai LL Ms API
  slug: anamai-llms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anamai/openapi/anamai-llms-api-openapi.yml
- filename: anamai-avatar-videos-api-openapi.yml
  format: yaml
  label: Anam.ai Avatar Videos API
  slug: anamai-avatar-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anamai/openapi/anamai-avatar-videos-api-openapi.yml
- filename: anamai-pronunciation-dictionaries-api-openapi.yml
  format: yaml
  label: Anam.ai Pronunciation Dictionaries API
  slug: anamai-pronunciation-dictionaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anamai/openapi/anamai-pronunciation-dictionaries-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: you may provide information such as your name, work email address, organization, account credentials, billing details, feedback and correspondence
  - category: device
    text: We also collect information about your device, such as device type, unique device identifiers, and mobile network information.
  - category: location
    text: We may collect general location information, such as the city or country you’re accessing our Site from, based on your IP address.
  - category: communication
    text: the service may process conversation content and session information such as audio, transcripts, model prompts and responses, timing, diagnostics and—where recording is enabled—a video recording
  deletion:
    route: DELETE /v1/sessions/{id}
    text: Customers can delete customer information for an ended session using DELETE /v1/sessions/{id} .
  dpa:
    available: true
    text: under the applicable agreement and Data Processing Addendum
    url: null
  purposes:
  - purpose: operate services and security
    text: We use personal information to operate the Site, public demos, Lab accounts and support services; authenticate users; process transactions; communicate about the service; maintain security
  residency:
  - region: Spain/EU and US East
    text: Customer-facing production inference and media are hosted on CoreWeave in Spain/EU and US East.
  retention:
  - period: as long as reasonably necessary
    scope: business records
    text: We retain website, account, support, billing and business records for as long as reasonably necessary for the purposes described in this Policy
  - period: up to 30 days
    scope: non-ZDR session recordings
    text: For non-ZDR sessions, recordings are retained for up to 30 days
  - period: after the session
    scope: ZDR customer session content
    text: With ZDR enabled, Anam does not persist customer session content after the session
  rights:
  - right: access
    text: 'The right to access: You can request copies of your personal information that we hold.'
  - right: rectification
    text: 'The right to rectification: If you believe any information we hold about you is inaccurate or incomplete, you have the right to ask us to correct or complete it.'
  - right: erasure
    text: 'The right to erasure: You have the right to ask us to delete your personal information from our records at any time.'
  - right: restrict processing
    text: 'The right to restrict processing: You may have the right to request that we limit the way we use your personal information.'
  - right: data portability
    text: 'The right to data portability: You can request that we transfer your data to another organization or directly to you'
  - right: object
    text: 'The right to object: You have the right to object to our processing of your personal information in certain circumstances.'
  role:
    text: In those contexts, Anam generally determines the purposes and means of processing.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We want to assure you that we do not sell your personal information to third parties.
  subprocessors:
    text: Our current subprocessors and supporting compliance information are available in the Anam Trust Center .
    url: null
  transfers:
  - mechanism: adequacy
    text: we use safeguards required by applicable law, which may include adequacy decisions
  - mechanism: SCC
    text: the European Commission’s Standard Contractual Clauses
  - mechanism: other
    text: the UK International Data Transfer Addendum
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Anam.ai
provenance_date: '2026-11-09'
provider_name: Anam.ai
provider_slug: anamai
slug: anamai-privacy-policy
source_date: '2026-11-09'
source_filename: anamai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://anam.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Anam.ai\naid: anamai\nurl: https://anam.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: In those contexts, Anam generally determines the purposes and means of processing.\ndata_categories:\n- category: contact\n  text: you may provide information such as your name, work email address, organization, account credentials, billing\n    details, feedback and correspondence\n- category: device\n  text: We also collect information about your device, such as device type, unique device identifiers, and mobile\n    network information.\n- category: location\n  text: We may collect general\
  \ location information, such as the city or country you’re accessing our Site from,\n    based on your IP address.\n- category: communication\n  text: the service may process conversation content and session information such as audio, transcripts, model prompts\n    and responses, timing, diagnostics and—where recording is enabled—a video recording\npurposes:\n- purpose: operate services and security\n  text: We use personal information to operate the Site, public demos, Lab accounts and support services; authenticate\n    users; process transactions; communicate about the service; maintain security\nretention:\n- scope: business records\n  period: as long as reasonably necessary\n  text: We retain website, account, support, billing and business records for as long as reasonably necessary for\n    the purposes described in this Policy\n- scope: non-ZDR session recordings\n  period: up to 30 days\n  text: For non-ZDR sessions, recordings are retained for up to 30 days\n- scope: ZDR customer\
  \ session content\n  period: after the session\n  text: With ZDR enabled, Anam does not persist customer session content after the session\nresidency:\n- region: Spain/EU and US East\n  text: Customer-facing production inference and media are hosted on CoreWeave in Spain/EU and US East.\ntransfers:\n- mechanism: adequacy\n  text: we use safeguards required by applicable law, which may include adequacy decisions\n- mechanism: SCC\n  text: the European Commission’s Standard Contractual Clauses\n- mechanism: other\n  text: the UK International Data Transfer Addendum\nsubprocessors:\n  url: null\n  text: Our current subprocessors and supporting compliance information are available in the Anam Trust Center .\ndpa:\n  available: true\n  url: null\n  text: under the applicable agreement and Data Processing Addendum\ndeletion:\n  route: DELETE /v1/sessions/{id}\n  text: Customers can delete customer information for an ended session using DELETE /v1/sessions/{id} .\nrights:\n- right: access\n \
  \ text: 'The right to access: You can request copies of your personal information that we hold.'\n- right: rectification\n  text: 'The right to rectification: If you believe any information we hold about you is inaccurate or incomplete,\n    you have the right to ask us to correct or complete it.'\n- right: erasure\n  text: 'The right to erasure: You have the right to ask us to delete your personal information from our records\n    at any time.'\n- right: restrict processing\n  text: 'The right to restrict processing: You may have the right to request that we limit the way we use your personal\n    information.'\n- right: data portability\n  text: 'The right to data portability: You can request that we transfer your data to another organization or directly\n    to you'\n- right: object\n  text: 'The right to object: You have the right to object to our processing of your personal information in certain\n    circumstances.'\nsale_or_sharing:\n  stance: prohibited\n  text: We want to assure\
  \ you that we do not sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/anamai/privacy/anamai-privacy-policy.yml
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
- sale_or_sharing
summary_line: 23 quoted statements, read from Anam.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Avatars
- Conversational AI
- Real-Time Video
- WebRTC
- Digital Humans
- Generative AI
---
