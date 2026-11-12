---
api_specs:
- filename: clipform-io-analytics-api-openapi.yml
  format: yaml
  label: Clipform Analytics API
  slug: clipform-io-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-analytics-api-openapi.yml
- filename: clipform-io-authentication-api-openapi.yml
  format: yaml
  label: Clipform Authentication API
  slug: clipform-io-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-authentication-api-openapi.yml
- filename: clipform-io-dynamic-links-api-openapi.yml
  format: yaml
  label: Clipform Dynamic Links API
  slug: clipform-io-dynamic-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-dynamic-links-api-openapi.yml
- filename: clipform-io-forms-api-openapi.yml
  format: yaml
  label: Clipform Forms API
  slug: clipform-io-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-forms-api-openapi.yml
- filename: clipform-io-integrations-api-openapi.yml
  format: yaml
  label: Clipform Integrations API
  slug: clipform-io-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-integrations-api-openapi.yml
- filename: clipform-io-node-media-api-openapi.yml
  format: yaml
  label: Clipform Node Media API
  slug: clipform-io-node-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-node-media-api-openapi.yml
- filename: clipform-io-nodes-api-openapi.yml
  format: yaml
  label: Clipform Nodes API
  slug: clipform-io-nodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-nodes-api-openapi.yml
- filename: clipform-io-tags-api-openapi.yml
  format: yaml
  label: Clipform Tags API
  slug: clipform-io-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-tags-api-openapi.yml
- filename: clipform-io-tracked-links-api-openapi.yml
  format: yaml
  label: Clipform Tracked Links API
  slug: clipform-io-tracked-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-tracked-links-api-openapi.yml
- filename: clipform-io-webhooks-api-openapi.yml
  format: yaml
  label: Clipform Webhooks API
  slug: clipform-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipform-io/openapi/clipform-io-webhooks-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account holders: email address, name, billing details (handled by our payment processor)'
  - category: communication
    text: 'Respondents: the answers, recordings, and files submitted through a form'
  - category: device
    text: 'Everyone: technical and usage data such as device information, log data, and product analytics.'
  - category: identifying
    text: account and workspace identifiers (for example your workspace name and internal workspace ID)
  deletion:
    route: Delete account or form in dashboard or by request
    text: deleting your account deletes your data, in each case within 30 days
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: To provide the service under our contract with you
  - purpose: Legitimate interests
    text: for our legitimate interests in securing, analysing, and improving the service
  - purpose: AI-assisted generation
    text: Where forms use AI-assisted generation, the relevant prompts and form content are processed by AI service providers to provide that feature.
  - purpose: Aggregated data
    text: We may also create aggregated or de-identified data that no longer identifies anyone and use or publish it for any purpose
  residency:
  - region: Outside UK and EEA
    text: Some providers are located outside the UK and EEA
  retention:
  - period: 30 days
    scope: Account data
    text: deleting your account deletes your data, in each case within 30 days
  - period: up to 12 months
    scope: Technical logs and product analytics
    text: Technical logs and product analytics events are retained for up to 12 months
  rights:
  - right: access
    text: You may request access to, correction of, deletion of, or a copy of your personal data
  - right: object or restrict
    text: you may object to or ask us to restrict certain processing
  - right: complain
    text: You also have the right to complain to the Information Commissioner's Office (ICO) or your local supervisory authority.
  role:
    text: For the personal data of account holders, we are the data controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Details are available on request.
    url: null
  transfers:
  - mechanism: adequacy
    text: we rely on appropriate safeguards such as adequacy decisions or standard contractual clauses
  - mechanism: SCC
    text: we rely on appropriate safeguards such as adequacy decisions or standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Clipform
provenance_date: '2026-11-09'
provider_name: Clipform
provider_slug: clipform-io
slug: clipform-io-privacy-policy
source_date: '2026-11-09'
source_filename: clipform-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.clipform.io/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Clipform\naid: clipform-io\nurl: https://www.clipform.io/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For the personal data of account holders, we are the data controller.\ndata_categories:\n- category: contact\n  text: 'Account holders: email address, name, billing details (handled by our payment processor)'\n- category: communication\n  text: 'Respondents: the answers, recordings, and files submitted through a form'\n- category: device\n  text: 'Everyone: technical and usage data such as device information, log data, and product analytics.'\n- category: identifying\n  text: account\
  \ and workspace identifiers (for example your workspace name and internal workspace ID)\npurposes:\n- purpose: Provide the service\n  text: To provide the service under our contract with you\n- purpose: Legitimate interests\n  text: for our legitimate interests in securing, analysing, and improving the service\n- purpose: AI-assisted generation\n  text: Where forms use AI-assisted generation, the relevant prompts and form content are processed by AI service\n    providers to provide that feature.\n- purpose: Aggregated data\n  text: We may also create aggregated or de-identified data that no longer identifies anyone and use or publish\n    it for any purpose\nretention:\n- scope: Account data\n  period: 30 days\n  text: deleting your account deletes your data, in each case within 30 days\n- scope: Technical logs and product analytics\n  period: up to 12 months\n  text: Technical logs and product analytics events are retained for up to 12 months\nresidency:\n- region: Outside UK and EEA\n\
  \  text: Some providers are located outside the UK and EEA\ntransfers:\n- mechanism: adequacy\n  text: we rely on appropriate safeguards such as adequacy decisions or standard contractual clauses\n- mechanism: SCC\n  text: we rely on appropriate safeguards such as adequacy decisions or standard contractual clauses\nsubprocessors:\n  url: null\n  text: Details are available on request.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account or form in dashboard or by request\n  text: deleting your account deletes your data, in each case within 30 days\nrights:\n- right: access\n  text: You may request access to, correction of, deletion of, or a copy of your personal data\n- right: object or restrict\n  text: you may object to or ask us to restrict certain processing\n- right: complain\n  text: You also have the right to complain to the Information Commissioner's Office (ICO) or your local supervisory\n    authority.\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/clipform-io/privacy/clipform-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Clipform's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Forms
- Form Builder
- Video
- Surveys
- Webhooks
- MCP
- Lead Capture
---
