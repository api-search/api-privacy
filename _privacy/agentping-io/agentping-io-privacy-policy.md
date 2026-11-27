---
api_specs:
- filename: agentping-io-openapi-generated.yml
  format: yaml
  label: Agent Ping API
  slug: agentping-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentping-io/openapi/_ae-authored/agentping-io-openapi-generated.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email, team details and authentication data.
  - category: financial
    text: Plan, subscription status and the payment metadata Stripe returns. Card numbers are handled by Stripe, not stored by us.
  - category: behavioral
    text: Basic analytics about how the dashboard is used, so we can improve it.
  - category: other
    text: Run records (timing, status, cost, scores), the step-by-step detail of each run, and the content your agents report through the SDK or API.
  deletion:
    route: Email or in-product export/deletion requests
    text: Under the GDPR and UK GDPR you can access, correct, export or delete your personal data, and object to or restrict certain processing.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the service
    text: 'To run the service you asked for: ingest and store your telemetry, show it back to you, alert you, score runs when you enable that, take payment, provide support, keep the service secure, and meet our legal obligations.'
  - purpose: Evaluation scoring
    text: When evaluations are switched on for a team, the relevant run content is sent to Anthropic's API to be scored against your goal.
  residency:
  - region: United Kingdom
    text: Agent Ping runs on DigitalOcean in London, United Kingdom, which holds an EU adequacy decision.
  retention:
  - period: null
    scope: Step-by-step detail and run history
    text: Step-by-step detail and run history each have their own retention window, set by your plan and listed on the pricing page.
  - period: null
    scope: Backups
    text: When you delete data or close your account, copies in backups age out on the backup schedule rather than living forever.
  rights:
  - right: Access, correct, export, delete
    text: Under the GDPR and UK GDPR you can access, correct, export or delete your personal data, and object to or restrict certain processing.
  - right: Complain to supervisory authority
    text: If you are in the EU or UK you also have the right to complain to your local supervisory authority.
  role:
    text: For the data you send us about your agents, you are the controller and we are the processor. For your account and billing details, we are the controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data, and we do not train models on it.
  subprocessors:
    text: 'The third parties that process data on our behalf: DigitalOcean: hosting, compute and the database (London, UK). Laravel Forge: server management and deployment.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agent Ping
provenance_date: '2026-11-09'
provider_name: Agent Ping
provider_slug: agentping-io
slug: agentping-io-privacy-policy
source_date: '2026-11-09'
source_filename: agentping-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentping.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agent Ping\naid: agentping-io\nurl: https://agentping.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For the data you send us about your agents, you are the controller and we are the processor. For your account\n    and billing details, we are the controller.\ndata_categories:\n- category: identifying\n  text: Your name, email, team details and authentication data.\n- category: financial\n  text: Plan, subscription status and the payment metadata Stripe returns. Card numbers are handled by Stripe, not\n    stored by us.\n- category: behavioral\n  text: Basic analytics about how the dashboard\
  \ is used, so we can improve it.\n- category: other\n  text: Run records (timing, status, cost, scores), the step-by-step detail of each run, and the content your agents\n    report through the SDK or API.\npurposes:\n- purpose: Run the service\n  text: 'To run the service you asked for: ingest and store your telemetry, show it back to you, alert you, score\n    runs when you enable that, take payment, provide support, keep the service secure, and meet our legal obligations.'\n- purpose: Evaluation scoring\n  text: When evaluations are switched on for a team, the relevant run content is sent to Anthropic's API to be scored\n    against your goal.\nretention:\n- scope: Step-by-step detail and run history\n  period: null\n  text: Step-by-step detail and run history each have their own retention window, set by your plan and listed on\n    the pricing page.\n- scope: Backups\n  period: null\n  text: When you delete data or close your account, copies in backups age out on the backup schedule\
  \ rather than\n    living forever.\nresidency:\n- region: United Kingdom\n  text: Agent Ping runs on DigitalOcean in London, United Kingdom, which holds an EU adequacy decision.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'The third parties that process data on our behalf: DigitalOcean: hosting, compute and the database (London,\n    UK). Laravel Forge: server management and deployment.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email or in-product export/deletion requests\n  text: Under the GDPR and UK GDPR you can access, correct, export or delete your personal data, and object to or\n    restrict certain processing.\nrights:\n- right: Access, correct, export, delete\n  text: Under the GDPR and UK GDPR you can access, correct, export or delete your personal data, and object to or\n    restrict certain processing.\n- right: Complain to supervisory authority\n  text: If you are in the EU or UK you also have the right to complain to your local supervisory\
  \ authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data, and we do not train models on it.\n"
source_yaml_url: https://artifacts.apis.io/agentping-io/privacy/agentping-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from Agent Ping's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Observability
- Monitoring
- Cost Management
- Software-as-a-Service
---
