---
api_specs:
- filename: inngest-account-api-openapi.yml
  format: yaml
  label: Inngest Account API
  slug: inngest-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-account-api-openapi.yml
- filename: inngest-apps-api-openapi.yml
  format: yaml
  label: Inngest Apps API
  slug: inngest-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-apps-api-openapi.yml
- filename: inngest-environments-api-openapi.yml
  format: yaml
  label: Inngest Environments API
  slug: inngest-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-environments-api-openapi.yml
- filename: inngest-events-api-openapi.yml
  format: yaml
  label: Inngest Events API
  slug: inngest-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-events-api-openapi.yml
- filename: inngest-functions-api-openapi.yml
  format: yaml
  label: Inngest Functions API
  slug: inngest-functions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-functions-api-openapi.yml
- filename: inngest-keys-api-openapi.yml
  format: yaml
  label: Inngest Keys API
  slug: inngest-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-keys-api-openapi.yml
- filename: inngest-runs-api-openapi.yml
  format: yaml
  label: Inngest Runs API
  slug: inngest-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-runs-api-openapi.yml
- filename: inngest-webhooks-api-openapi.yml
  format: yaml
  label: Inngest Webhooks API
  slug: inngest-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-webhooks-api-openapi.yml
- filename: inngest-experiments-api-openapi.yml
  format: yaml
  label: Inngest Experiments API
  slug: inngest-experiments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-experiments-api-openapi.yml
- filename: inngest-insights-api-openapi.yml
  format: yaml
  label: Inngest Insights API
  slug: inngest-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-insights-api-openapi.yml
- filename: inngest-partner-api-api-openapi.yml
  format: yaml
  label: Inngest Partner API
  slug: inngest-partner-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-partner-api-api-openapi.yml
- filename: inngest-sandboxes-api-openapi.yml
  format: yaml
  label: Inngest Sandboxes API
  slug: inngest-sandboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-sandboxes-api-openapi.yml
- filename: inngest-sessions-api-openapi.yml
  format: yaml
  label: Inngest Sessions API
  slug: inngest-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-sessions-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Contact form Personal Data: email address'
  - category: financial
    text: 'Stripe Personal Data: billing address; email address; first name; last name; payment info; purchase history'
  - category: identifying
    text: 'Direct Registration Personal Data: email address; password; workplace'
  - category: device
    text: 'Google Analytics 4 Personal Data: browser information'
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Analytics
    text: Analytics Google Analytics 4
  - purpose: Contacting the User
    text: Contacting the User Contact form
  - purpose: Handling payments
    text: Handling payments Stripe
  - purpose: Registration and authentication
    text: Registration and authentication provided directly by this Application Direct Registration
  - purpose: Hosting and backend infrastructure
    text: Hosting and backend infrastructure Amazon Web Services (AWS)
  role:
    text: Owner & Data Controller Inngest Inc - 600 California St Suite 1200 San Francisco, CA 94109, USA
    value: controller
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
name: Inngest
provenance_date: '2026-11-09'
provider_name: Inngest
provider_slug: inngest
slug: inngest-privacy-policy
source_date: '2026-11-09'
source_filename: inngest-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.inngest.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Inngest\naid: inngest\nurl: https://www.inngest.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Owner & Data Controller Inngest Inc - 600 California St Suite 1200 San Francisco, CA 94109, USA\ndata_categories:\n- category: contact\n  text: 'Contact form Personal Data: email address'\n- category: financial\n  text: 'Stripe Personal Data: billing address; email address; first name; last name; payment info; purchase history'\n- category: identifying\n  text: 'Direct Registration Personal Data: email address; password; workplace'\n- category: device\n  text: 'Google Analytics 4 Personal\
  \ Data: browser information'\npurposes:\n- purpose: Analytics\n  text: Analytics Google Analytics 4\n- purpose: Contacting the User\n  text: Contacting the User Contact form\n- purpose: Handling payments\n  text: Handling payments Stripe\n- purpose: Registration and authentication\n  text: Registration and authentication provided directly by this Application Direct Registration\n- purpose: Hosting and backend infrastructure\n  text: Hosting and backend infrastructure Amazon Web Services (AWS)\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/inngest/privacy/inngest-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
summary_line: 10 quoted statements, read from Inngest's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- AgentKit
- Background Jobs
- Connect
- Cron Jobs
- Dev Server
- Durable Endpoints
- Durable Execution
- Event-Driven
- Insights
- Orchestration
- Queues
- Real-Time
- Self-Hosting
- Serverless
- Signals
- Step Functions
- Webhook
- Workflows
---
