---
api_specs:
- filename: spicyapi-account-api-openapi.yml
  format: yaml
  label: SpicyAPI Account API
  slug: spicyapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi/openapi/spicyapi-account-api-openapi.yml
- filename: spicyapi-media-api-openapi.yml
  format: yaml
  label: SpicyAPI Media API
  slug: spicyapi-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi/openapi/spicyapi-media-api-openapi.yml
- filename: spicyapi-models-api-openapi.yml
  format: yaml
  label: SpicyAPI Models API
  slug: spicyapi-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi/openapi/spicyapi-models-api-openapi.yml
- filename: spicyapi-openai-compatible-api-openapi.yml
  format: yaml
  label: SpicyAPI OpenAI Compatible API
  slug: spicyapi-openai-compatible-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi/openapi/spicyapi-openai-compatible-api-openapi.yml
- filename: spicyapi-tasks-api-openapi.yml
  format: yaml
  label: SpicyAPI Tasks API
  slug: spicyapi-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spicyapi/openapi/spicyapi-tasks-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, password hash, any linked Google or GitHub identity, the country determined at sign-up
  - category: device
    text: Each login session records the IP address, the browser user-agent string and the country.
  - category: financial
    text: Top-up orders, wallet balances and daily spend aggregates sit alongside them.
  - category: other
    text: Prompts, negative prompts and free-text parameters
  deletion:
    route: Console account closure or requests to support@spicyapi.ai
    text: A request that the console cannot complete goes to support@spicyapi.ai and is reviewed by a person.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Security and account activity
    text: This is used to detect unusual sign-ins, investigate account changes and show you your own active sessions and recent security activity.
  - purpose: Payment processing
    text: Saving a payment method, processing a top-up and reconciling its result
  retention:
  - period: Up to 30 days, then erased
    scope: Prompts and free-text parameters
    text: Up to 30 days, then erased
  - period: Up to about 14 days
    scope: Generated media
    text: Up to about 14 days
  - period: 35 days
    scope: Database backups
    text: Database backups are retained for 35 days.
  - period: As long as US tax and accounting law requires
    scope: Ledger entries
    text: They are kept for as long as US tax and accounting law requires of us, which is a period measured in years and is not ours to shorten on request.
  rights:
  - right: access, correct, delete, restrict, object, port
    text: Depending on where you live, you may have rights to access, correct, delete, restrict, object to or port your data, and to complain to a supervisory authority.
  role:
    text: The operator is the data controller for everything described below
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent personal data.
  subprocessors:
    text: Who else processes your data
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the European Commission's standard contractual clauses together with the UK addendum to them.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SpicyAPI
provenance_date: '2026-11-10'
provider_name: SpicyAPI
provider_slug: spicyapi
slug: spicyapi-privacy-policy
source_date: '2026-11-10'
source_filename: spicyapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://spicyapi.ai/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SpicyAPI\naid: spicyapi\nurl: https://spicyapi.ai/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The operator is the data controller for everything described below\ndata_categories:\n- category: identifying\n  text: Email address, password hash, any linked Google or GitHub identity, the country determined at sign-up\n- category: device\n  text: Each login session records the IP address, the browser user-agent string and the country.\n- category: financial\n  text: Top-up orders, wallet balances and daily spend aggregates sit alongside them.\n- category: other\n  text: Prompts,\
  \ negative prompts and free-text parameters\npurposes:\n- purpose: Security and account activity\n  text: This is used to detect unusual sign-ins, investigate account changes and show you your own active sessions\n    and recent security activity.\n- purpose: Payment processing\n  text: Saving a payment method, processing a top-up and reconciling its result\nretention:\n- scope: Prompts and free-text parameters\n  period: Up to 30 days, then erased\n  text: Up to 30 days, then erased\n- scope: Generated media\n  period: Up to about 14 days\n  text: Up to about 14 days\n- scope: Database backups\n  period: 35 days\n  text: Database backups are retained for 35 days.\n- scope: Ledger entries\n  period: As long as US tax and accounting law requires\n  text: They are kept for as long as US tax and accounting law requires of us, which is a period measured in years\n    and is not ours to shorten on request.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we rely on the European Commission's\
  \ standard contractual clauses together with the UK addendum to them.\nsubprocessors:\n  url: null\n  text: Who else processes your data\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Console account closure or requests to support@spicyapi.ai\n  text: A request that the console cannot complete goes to support@spicyapi.ai and is reviewed by a person.\nrights:\n- right: access, correct, delete, restrict, object, port\n  text: Depending on where you live, you may have rights to access, correct, delete, restrict, object to or port\n    your data, and to complain to a supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal data.\n"
source_yaml_url: https://artifacts.apis.io/spicyapi/privacy/spicyapi-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from SpicyAPI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative Media
- LLM
- Video Generation
- Image Generation
- Model Aggregator
---
