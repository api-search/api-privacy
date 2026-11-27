---
api_specs:
- filename: precog-admin-api-openapi.yml
  format: yaml
  label: Precog Admin API
  slug: precog-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precog/openapi/precog-admin-api-openapi.yml
- filename: precog-data-model-api-openapi.yml
  format: yaml
  label: Precog Data Model API
  slug: precog-data-model-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precog/openapi/precog-data-model-api-openapi.yml
- filename: precog-datasets-api-openapi.yml
  format: yaml
  label: Precog Datasets API
  slug: precog-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precog/openapi/precog-datasets-api-openapi.yml
- filename: precog-destinations-api-openapi.yml
  format: yaml
  label: Precog Destinations API
  slug: precog-destinations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precog/openapi/precog-destinations-api-openapi.yml
- filename: precog-issues-api-openapi.yml
  format: yaml
  label: Precog Issues API
  slug: precog-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precog/openapi/precog-issues-api-openapi.yml
- filename: precog-kinds-api-openapi.yml
  format: yaml
  label: Precog Kinds API
  slug: precog-kinds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precog/openapi/precog-kinds-api-openapi.yml
- filename: precog-loads-api-openapi.yml
  format: yaml
  label: Precog Loads API
  slug: precog-loads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precog/openapi/precog-loads-api-openapi.yml
- filename: precog-log-api-openapi.yml
  format: yaml
  label: Precog Log API
  slug: precog-log-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precog/openapi/precog-log-api-openapi.yml
- filename: precog-pipelines-api-openapi.yml
  format: yaml
  label: Precog Pipelines API
  slug: precog-pipelines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precog/openapi/precog-pipelines-api-openapi.yml
- filename: precog-semantic-model-api-openapi.yml
  format: yaml
  label: Precog Semantic Model API
  slug: precog-semantic-model-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precog/openapi/precog-semantic-model-api-openapi.yml
- filename: precog-sources-api-openapi.yml
  format: yaml
  label: Precog Sources API
  slug: precog-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precog/openapi/precog-sources-api-openapi.yml
- filename: precog-stripe-api-openapi.yml
  format: yaml
  label: Precog Stripe API
  slug: precog-stripe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/precog/openapi/precog-stripe-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: contact
    text: Emails
  - category: identifying
    text: User names
  - category: identifying
    text: SSN
  - category: behavioral
    text: information about his or her activity on the Site
  - category: device
    text: IP address, browser type, system type
  deletion:
    route: email to privacy mailbox
    text: These requests may also be submitted to our privacy mailbox.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide requested services
    text: We use personal information to provide services and information that you request
  - purpose: fraud prevention
    text: to prevent fraudulent use of our Site and Service
  - purpose: marketing contact
    text: We may also use the personal information you provide to contact you regarding our products and services.
  residency:
  - region: United States
    text: Data may be processed in the United States in the Amazon East or Amazon EU Central regions depending on customer selection.
  retention:
  - period: 30 days
    scope: AI provider processing of API content
    text: provider processing may retain API content for up to 30 days by default
  rights:
  - right: deletion and update
    text: You do have the right to submit requests to have your information deleted and updated as necessary
  - right: opt-out of marketing emails
    text: You may also opt-out from receiving commercial emails from us by sending us an email
  role:
    text: Precog Data, Inc. acts as both a Data Controller and a Data Processor from the perspective of our interactions with our customers.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Precog may disclose Personal Information and Customer Data to service providers and subprocessors that assist in providing the Service
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Precog
provenance_date: '2026-11-10'
provider_name: Precog
provider_slug: precog
slug: precog-privacy-policy
source_date: '2026-11-10'
source_filename: precog-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://studio.precog.cloud/docs/current/trust-and-security/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Precog\naid: precog\nurl: https://studio.precog.cloud/docs/current/trust-and-security/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Precog Data, Inc. acts as both a Data Controller and a Data Processor from the perspective of our interactions\n    with our customers.\ndata_categories:\n- category: contact\n  text: Emails\n- category: identifying\n  text: User names\n- category: identifying\n  text: SSN\n- category: behavioral\n  text: information about his or her activity on the Site\n- category: device\n  text: IP address, browser type, system type\npurposes:\n- purpose: provide\
  \ requested services\n  text: We use personal information to provide services and information that you request\n- purpose: fraud prevention\n  text: to prevent fraudulent use of our Site and Service\n- purpose: marketing contact\n  text: We may also use the personal information you provide to contact you regarding our products and services.\nretention:\n- scope: AI provider processing of API content\n  period: 30 days\n  text: provider processing may retain API content for up to 30 days by default\nresidency:\n- region: United States\n  text: Data may be processed in the United States in the Amazon East or Amazon EU Central regions depending on\n    customer selection.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Precog may disclose Personal Information and Customer Data to service providers and subprocessors that assist\n    in providing the Service\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to privacy mailbox\n  text: These requests may also\
  \ be submitted to our privacy mailbox.\nrights:\n- right: deletion and update\n  text: You do have the right to submit requests to have your information deleted and updated as necessary\n- right: opt-out of marketing emails\n  text: You may also opt-out from receiving commercial emails from us by sending us an email\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/precog/privacy/precog-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
summary_line: 15 quoted statements, read from Precog's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Integration
- ETL
- Artificial Intelligence
- Semantic Layer
- MCP
- Data Pipeline
- Analytics
- Enterprise
---
