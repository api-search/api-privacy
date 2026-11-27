---
api_specs:
- filename: classifier-dev-account-api-openapi.yml
  format: yaml
  label: classifier-dev Account API
  slug: classifier-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classifier-dev/openapi/classifier-dev-account-api-openapi.yml
- filename: classifier-dev-classifier-dev-api-openapi.yml
  format: yaml
  label: classifier-dev Classifier.dev API
  slug: classifier-dev-classifier-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classifier-dev/openapi/classifier-dev-classifier-dev-api-openapi.yml
- filename: classifier-dev-classify-api-openapi.yml
  format: yaml
  label: classifier-dev Classify API
  slug: classifier-dev-classify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classifier-dev/openapi/classifier-dev-classify-api-openapi.yml
- filename: classifier-dev-docs-api-openapi.yml
  format: yaml
  label: classifier-dev Docs API
  slug: classifier-dev-docs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classifier-dev/openapi/classifier-dev-docs-api-openapi.yml
- filename: classifier-dev-feedback-api-openapi.yml
  format: yaml
  label: classifier-dev Feedback API
  slug: classifier-dev-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classifier-dev/openapi/classifier-dev-feedback-api-openapi.yml
- filename: classifier-dev-subscribe-api-openapi.yml
  format: yaml
  label: classifier-dev Subscribe API
  slug: classifier-dev-subscribe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/classifier-dev/openapi/classifier-dev-subscribe-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Our workspace database, hosted by Neon, stores your account ID, email, display name, memberships, invitations, workspace settings, key names, usage and billing records.
  - category: contact
    text: The updates form keeps the address you typed, the date, the signup source and what you ticked, in the subscriber table of our application database.
  - category: device
    text: a client family derived from the User-Agent (curl, python, browser, MCP, ...)
  - category: location
    text: a coarse request-country
  - category: communication
    text: Synchronous classification request text, labels, instructions and model results are retained for model training and operator review in private Cloudflare storage by default.
  - category: behavioral
    text: Usage records include request IDs, timestamps, API or MCP source, item and token counts when available, model, status, latency and cost.
  deletion:
    route: Email contact@classifier.dev
    text: Contact contact@classifier.dev about a contribution or deletion.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: model training and evaluation
    text: Contributions may be used to train and evaluate our models and are retained until deleted, including in derived training datasets.
  - purpose: rate limiting and operations
    text: 'Per request, for rate limiting and operations: which tier ran, which model answered, the latency, the response status, a coarse request-country and a client family derived from the User-Agent'
  - purpose: access management and billing
    text: Signed-in workspaces store account details, API keys and usage records so you can manage access and billing.
  - purpose: newsletter updates
    text: 'The address gets the updates and nothing else: never sold, shared or passed to an advertiser.'
  retention:
  - period: 90 days
    scope: successful classifier label names
    text: Successful classifier label names are retained for 90 days as one aggregate record per label set, without caller identity or source text.
  - period: null
    scope: shared classification records
    text: Contributions may be used to train and evaluate our models and are retained until deleted, including in derived training datasets.
  - period: 90 days
    scope: workspace analytics
    text: Workspace analytics are stored separately in Cloudflare Analytics Engine for 90 days
  - period: up to three UTC days
    scope: free spending reservations and reputation entries
    text: Free spending reservations and reputation entries are removed after their retention window (up to three UTC days)
  - period: 24 hours after creation
    scope: whole-document job source text
    text: Cancellation, failure and expiry (24 hours after creation) delete remaining source and evidence.
  rights:
  - right: access to account data
    text: Ask contact@classifier.dev about access to or deletion of your account data.
  - right: inspect and export contributions
    text: Operators can inspect and export contributions in the authenticated admin dashboard.
  - right: opt out of training collection
    text: 'Set share_data: false or X-Classifier-Share-Data: false to opt out and use standard limits.'
  role:
    text: Operators can inspect and export contributions in the authenticated admin dashboard.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: 'The address gets the updates and nothing else: never sold, shared or passed to an advertiser.'
  subprocessors:
    text: The model provider that answers the request — TypeSafe for the decision model, directly or through Vercel AI Gateway, and for the smart tier's re-asked items, the reasoning model's provider via OpenRouter.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: classifier-dev
provenance_date: '2026-11-09'
provider_name: classifier-dev
provider_slug: classifier-dev
slug: classifier-dev-privacy-policy
source_date: '2026-11-09'
source_filename: classifier-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://classifier.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: classifier-dev\naid: classifier-dev\nurl: https://classifier.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Operators can inspect and export contributions in the authenticated admin dashboard.\ndata_categories:\n- category: identifying\n  text: Our workspace database, hosted by Neon, stores your account ID, email, display name, memberships, invitations,\n    workspace settings, key names, usage and billing records.\n- category: contact\n  text: The updates form keeps the address you typed, the date, the signup source and what you ticked, in the subscriber\n    table of our application\
  \ database.\n- category: device\n  text: a client family derived from the User-Agent (curl, python, browser, MCP, ...)\n- category: location\n  text: a coarse request-country\n- category: communication\n  text: Synchronous classification request text, labels, instructions and model results are retained for model training\n    and operator review in private Cloudflare storage by default.\n- category: behavioral\n  text: Usage records include request IDs, timestamps, API or MCP source, item and token counts when available,\n    model, status, latency and cost.\npurposes:\n- purpose: model training and evaluation\n  text: Contributions may be used to train and evaluate our models and are retained until deleted, including in\n    derived training datasets.\n- purpose: rate limiting and operations\n  text: 'Per request, for rate limiting and operations: which tier ran, which model answered, the latency, the response\n    status, a coarse request-country and a client family derived from the\
  \ User-Agent'\n- purpose: access management and billing\n  text: Signed-in workspaces store account details, API keys and usage records so you can manage access and billing.\n- purpose: newsletter updates\n  text: 'The address gets the updates and nothing else: never sold, shared or passed to an advertiser.'\nretention:\n- scope: successful classifier label names\n  period: 90 days\n  text: Successful classifier label names are retained for 90 days as one aggregate record per label set, without\n    caller identity or source text.\n- scope: shared classification records\n  period: null\n  text: Contributions may be used to train and evaluate our models and are retained until deleted, including in\n    derived training datasets.\n- scope: workspace analytics\n  period: 90 days\n  text: Workspace analytics are stored separately in Cloudflare Analytics Engine for 90 days\n- scope: free spending reservations and reputation entries\n  period: up to three UTC days\n  text: Free spending reservations\
  \ and reputation entries are removed after their retention window (up to three\n    UTC days)\n- scope: whole-document job source text\n  period: 24 hours after creation\n  text: Cancellation, failure and expiry (24 hours after creation) delete remaining source and evidence.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: The model provider that answers the request — TypeSafe for the decision model, directly or through Vercel\n    AI Gateway, and for the smart tier's re-asked items, the reasoning model's provider via OpenRouter.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email contact@classifier.dev\n  text: Contact contact@classifier.dev about a contribution or deletion.\nrights:\n- right: access to account data\n  text: Ask contact@classifier.dev about access to or deletion of your account data.\n- right: inspect and export contributions\n  text: Operators can inspect and export contributions in the authenticated admin dashboard.\n- right:\
  \ opt out of training collection\n  text: 'Set share_data: false or X-Classifier-Share-Data: false to opt out and use standard limits.'\nsale_or_sharing:\n  stance: conditional\n  text: 'The address gets the updates and nothing else: never sold, shared or passed to an advertiser.'\n"
source_yaml_url: https://artifacts.apis.io/classifier-dev/privacy/classifier-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from classifier-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Machine Learning
- Natural Language Processing
- Classification
- OpenAPI
---
