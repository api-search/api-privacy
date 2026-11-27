---
api_specs:
- filename: abmeter-ai-agent-feedback-api-openapi.yml
  format: yaml
  label: ABMeter Agent Feedback API
  slug: abmeter-ai-agent-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abmeter-ai/openapi/abmeter-ai-agent-feedback-api-openapi.yml
- filename: abmeter-ai-assignment-config-api-openapi.yml
  format: yaml
  label: ABMeter Assignment Config API
  slug: abmeter-ai-assignment-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abmeter-ai/openapi/abmeter-ai-assignment-config-api-openapi.yml
- filename: abmeter-ai-audiences-api-openapi.yml
  format: yaml
  label: ABMeter Audiences API
  slug: abmeter-ai-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abmeter-ai/openapi/abmeter-ai-audiences-api-openapi.yml
- filename: abmeter-ai-event-types-api-openapi.yml
  format: yaml
  label: ABMeter Event Types API
  slug: abmeter-ai-event-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abmeter-ai/openapi/abmeter-ai-event-types-api-openapi.yml
- filename: abmeter-ai-events-api-openapi.yml
  format: yaml
  label: ABMeter Events API
  slug: abmeter-ai-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abmeter-ai/openapi/abmeter-ai-events-api-openapi.yml
- filename: abmeter-ai-experiments-api-openapi.yml
  format: yaml
  label: ABMeter Experiments API
  slug: abmeter-ai-experiments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abmeter-ai/openapi/abmeter-ai-experiments-api-openapi.yml
- filename: abmeter-ai-exposures-api-openapi.yml
  format: yaml
  label: ABMeter Exposures API
  slug: abmeter-ai-exposures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abmeter-ai/openapi/abmeter-ai-exposures-api-openapi.yml
- filename: abmeter-ai-feature-flags-api-openapi.yml
  format: yaml
  label: ABMeter Feature Flags API
  slug: abmeter-ai-feature-flags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abmeter-ai/openapi/abmeter-ai-feature-flags-api-openapi.yml
- filename: abmeter-ai-metrics-api-openapi.yml
  format: yaml
  label: ABMeter Metrics API
  slug: abmeter-ai-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abmeter-ai/openapi/abmeter-ai-metrics-api-openapi.yml
- filename: abmeter-ai-parameters-api-openapi.yml
  format: yaml
  label: ABMeter Parameters API
  slug: abmeter-ai-parameters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abmeter-ai/openapi/abmeter-ai-parameters-api-openapi.yml
- filename: abmeter-ai-spaces-api-openapi.yml
  format: yaml
  label: ABMeter Spaces API
  slug: abmeter-ai-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abmeter-ai/openapi/abmeter-ai-spaces-api-openapi.yml
- filename: abmeter-ai-up-api-openapi.yml
  format: yaml
  label: ABMeter Up API
  slug: abmeter-ai-up-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abmeter-ai/openapi/abmeter-ai-up-api-openapi.yml
- filename: abmeter-ai-user-assignments-api-openapi.yml
  format: yaml
  label: ABMeter User Assignments API
  slug: abmeter-ai-user-assignments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abmeter-ai/openapi/abmeter-ai-user-assignments-api-openapi.yml
- filename: abmeter-ai-variants-api-openapi.yml
  format: yaml
  label: ABMeter Variants API
  slug: abmeter-ai-variants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/abmeter-ai/openapi/abmeter-ai-variants-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign in with GitHub or Google, ABMeter receives your email address, name, and the provider's account id.
  - category: behavioral
    text: It stores the resources you create - spaces, experiments, feature flags, parameters, and audiences - along with the events and exposures your SDKs send.
  - category: other
    text: It also stores the API keys and access tokens your SDKs and MCP clients authenticate with.
  - category: behavioral
    text: 'ABMeter counts visits to public pages, such as the statistics page: which page, the site that linked to it, and the time.'
  deletion:
    route: email request
    text: to have your account and its data deleted, email [email protected]
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the service
    text: 'ABMeter uses your data to run the service: assign users to variants, evaluate flags, and compute experiment results.'
  retention:
  - period: 90 days
    scope: events and exposures
    text: ABMeter deletes events and exposures older than 90 days.
  - period: null
    scope: pre-signup page visits
    text: Until then, they are held in the session cookie this site already uses for signing in.
  rights:
  - right: access
    text: To ask what ABMeter holds about you
  - right: deletion
    text: to have your account and its data deleted
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: ABMeter does not sell your data, use it for advertising, or run analytics or tracking software against it.
  subprocessors:
    text: Hosting and database providers process data on ABMeter's behalf.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ABMeter
provenance_date: '2026-11-09'
provider_name: ABMeter
provider_slug: abmeter-ai
slug: abmeter-ai-privacy-policy
source_date: '2026-11-09'
source_filename: abmeter-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://abmeter.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ABMeter\naid: abmeter-ai\nurl: https://abmeter.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you sign in with GitHub or Google, ABMeter receives your email address, name, and the provider's account\n    id.\n- category: behavioral\n  text: It stores the resources you create - spaces, experiments, feature flags, parameters, and audiences - along\n    with the events and exposures your SDKs send.\n- category: other\n  text: It also stores the API keys and access tokens your SDKs and MCP clients authenticate with.\n- category:\
  \ behavioral\n  text: 'ABMeter counts visits to public pages, such as the statistics page: which page, the site that linked to\n    it, and the time.'\npurposes:\n- purpose: run the service\n  text: 'ABMeter uses your data to run the service: assign users to variants, evaluate flags, and compute experiment\n    results.'\nretention:\n- scope: events and exposures\n  period: 90 days\n  text: ABMeter deletes events and exposures older than 90 days.\n- scope: pre-signup page visits\n  period: null\n  text: Until then, they are held in the session cookie this site already uses for signing in.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Hosting and database providers process data on ABMeter's behalf.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: to have your account and its data deleted, email [email protected]\nrights:\n- right: access\n  text: To ask what ABMeter holds about you\n- right: deletion\n  text: to have your\
  \ account and its data deleted\nsale_or_sharing:\n  stance: prohibited\n  text: ABMeter does not sell your data, use it for advertising, or run analytics or tracking software against it.\n"
source_yaml_url: https://artifacts.apis.io/abmeter-ai/privacy/abmeter-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 12 quoted statements, read from ABMeter's own page on 2026-11-09.
synthetic: false
tags:
- A/B Testing
- Analytics
- Experimentation
- Software-as-a-Service
- Developer Tools
---
