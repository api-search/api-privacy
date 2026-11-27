---
api_specs:
- filename: blendduck-com-analytics-api-openapi.yml
  format: yaml
  label: BlendDuck Analytics API
  slug: blendduck-com-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blendduck-com/openapi/blendduck-com-analytics-api-openapi.yml
- filename: blendduck-com-channels-api-openapi.yml
  format: yaml
  label: BlendDuck Channels API
  slug: blendduck-com-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blendduck-com/openapi/blendduck-com-channels-api-openapi.yml
- filename: blendduck-com-media-api-openapi.yml
  format: yaml
  label: BlendDuck Media API
  slug: blendduck-com-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blendduck-com/openapi/blendduck-com-media-api-openapi.yml
- filename: blendduck-com-posts-api-openapi.yml
  format: yaml
  label: BlendDuck Posts API
  slug: blendduck-com-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blendduck-com/openapi/blendduck-com-posts-api-openapi.yml
- filename: blendduck-com-providers-api-openapi.yml
  format: yaml
  label: BlendDuck Providers API
  slug: blendduck-com-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blendduck-com/openapi/blendduck-com-providers-api-openapi.yml
- filename: blendduck-com-tenant-api-openapi.yml
  format: yaml
  label: BlendDuck Tenant API
  slug: blendduck-com-tenant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blendduck-com/openapi/blendduck-com-tenant-api-openapi.yml
- filename: blendduck-com-webhooks-api-openapi.yml
  format: yaml
  label: BlendDuck Webhooks API
  slug: blendduck-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blendduck-com/openapi/blendduck-com-webhooks-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account details such as name, email address, avatar, authentication provider, and workspace membership.
  - category: other
    text: Connected-channel metadata such as account names, provider identifiers, OAuth scopes, token status, and publishing capabilities.
  - category: other
    text: Content data such as drafts, schedules, media references, brand knowledge, chat history, and publishing status.
  - category: device
    text: Operational data such as usage events, billing state, errors, security logs, and device or browser metadata.
  deletion:
    route: Dashboard → Settings
    text: Authenticated users can export portable account data, record optional analytics or marketing choices, review request receipts, delete owned workspaces, and request account erasure from Dashboard → Settings.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authenticate users
    text: To authenticate users and keep workspaces scoped to the right team.
  - purpose: content operations
    text: To generate, review, schedule, publish, and measure content across connected platforms.
  - purpose: abuse protection and reliability
    text: To protect the service from abuse, debug failures, and improve reliability.
  residency:
  - region: deployment-configured
    text: BlendDuck stores workspace records in the configured database and media or attachments in the configured storage backend.
  retention:
  - period: null
    scope: account and workspace erasure
    text: account and workspace erasure removes controlled application data unless a documented legal or paid-resource exception blocks the request.
  rights:
  - right: export account data
    text: Authenticated users can export portable account data
  - right: delete workspaces and request erasure
    text: delete owned workspaces, and request account erasure from Dashboard → Settings
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: BlendDuck may use infrastructure, authentication, payment, email, analytics, AI, storage, and support providers to operate the service.
    url: null
  transfers:
  - mechanism: other
    text: Where required, the operator of your BlendDuck deployment is responsible for selecting appropriate providers and transfer safeguards.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BlendDuck
provenance_date: '2026-11-09'
provider_name: BlendDuck
provider_slug: blendduck-com
slug: blendduck-com-privacy-policy
source_date: '2026-11-09'
source_filename: blendduck-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://blendduck.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BlendDuck\naid: blendduck-com\nurl: https://blendduck.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account details such as name, email address, avatar, authentication provider, and workspace membership.\n- category: other\n  text: Connected-channel metadata such as account names, provider identifiers, OAuth scopes, token status, and\n    publishing capabilities.\n- category: other\n  text: Content data such as drafts, schedules, media references, brand knowledge, chat history, and publishing\n    status.\n- category: device\n\
  \  text: Operational data such as usage events, billing state, errors, security logs, and device or browser metadata.\npurposes:\n- purpose: authenticate users\n  text: To authenticate users and keep workspaces scoped to the right team.\n- purpose: content operations\n  text: To generate, review, schedule, publish, and measure content across connected platforms.\n- purpose: abuse protection and reliability\n  text: To protect the service from abuse, debug failures, and improve reliability.\nretention:\n- scope: account and workspace erasure\n  period: null\n  text: account and workspace erasure removes controlled application data unless a documented legal or paid-resource\n    exception blocks the request.\nresidency:\n- region: deployment-configured\n  text: BlendDuck stores workspace records in the configured database and media or attachments in the configured\n    storage backend.\ntransfers:\n- mechanism: other\n  text: Where required, the operator of your BlendDuck deployment is responsible\
  \ for selecting appropriate providers\n    and transfer safeguards.\nsubprocessors:\n  url: null\n  text: BlendDuck may use infrastructure, authentication, payment, email, analytics, AI, storage, and support providers\n    to operate the service.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Dashboard → Settings\n  text: Authenticated users can export portable account data, record optional analytics or marketing choices, review\n    request receipts, delete owned workspaces, and request account erasure from Dashboard → Settings.\nrights:\n- right: export account data\n  text: Authenticated users can export portable account data\n- right: delete workspaces and request erasure\n  text: delete owned workspaces, and request account erasure from Dashboard → Settings\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/blendduck-com/privacy/blendduck-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 14 quoted statements, read from BlendDuck's own page on 2026-11-09.
synthetic: false
tags:
- Social
- Collaboration
- Artificial Intelligence
- Branding
- Marketing
- Company
---
