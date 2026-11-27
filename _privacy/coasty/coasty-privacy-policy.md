---
api_specs:
- filename: coasty-keys-api-openapi.yml
  format: yaml
  label: Coasty Keys API
  slug: coasty-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coasty/openapi/coasty-keys-api-openapi.yml
- filename: coasty-machines-api-openapi.yml
  format: yaml
  label: Coasty Machines API
  slug: coasty-machines-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coasty/openapi/coasty-machines-api-openapi.yml
- filename: coasty-predict-api-openapi.yml
  format: yaml
  label: Coasty Predict API
  slug: coasty-predict-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coasty/openapi/coasty-predict-api-openapi.yml
- filename: coasty-runs-api-openapi.yml
  format: yaml
  label: Coasty Runs API
  slug: coasty-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coasty/openapi/coasty-runs-api-openapi.yml
- filename: coasty-schedules-api-openapi.yml
  format: yaml
  label: Coasty Schedules API
  slug: coasty-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coasty/openapi/coasty-schedules-api-openapi.yml
- filename: coasty-sessions-api-openapi.yml
  format: yaml
  label: Coasty Sessions API
  slug: coasty-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coasty/openapi/coasty-sessions-api-openapi.yml
- filename: coasty-triggers-api-openapi.yml
  format: yaml
  label: Coasty Triggers API
  slug: coasty-triggers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coasty/openapi/coasty-triggers-api-openapi.yml
- filename: coasty-workflows-api-openapi.yml
  format: yaml
  label: Coasty Workflows API
  slug: coasty-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coasty/openapi/coasty-workflows-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, and your name and profile picture if you provide them.
  - category: contact
    text: Onboarding details you choose to share (role, company, team size, use case).
  - category: financial
    text: Subscription, billing, and transaction records.
  - category: behavioral
    text: Usage patterns, performance data, and, where you have consented, cookies and analytics identifiers.
  - category: device
    text: IP address, device and browser information, and the desktop app's system identifiers.
  - category: communication
    text: Your prompts and chats, and the assistant's replies.
  - category: other
    text: Screenshots of the screen the agent is operating, captured during a session so the model can see what it is doing.
  deletion:
    route: Account, then Data
    text: you can delete your entire account and its associated data from Account, then Data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the service
    text: Provide and operate the service, and run the AI agents and virtual machines you request.
  - purpose: Security and abuse prevention
    text: Secure the service, detect and prevent abuse, fraud, and misuse, and enforce our Terms.
  - purpose: Improve the service
    text: Measure usage and analyze, debug, and improve the service, our agents, and the product experience.
  - purpose: Billing and support
    text: Bill you, manage subscriptions and credits, and provide support.
  - purpose: Legal compliance
    text: Comply with legal obligations and respond to lawful requests.
  residency:
  - region: United States
    text: Coasty is operated from the United States, and the providers above process data in the United States.
  retention:
  - period: as long as your account is active
    scope: Account data
    text: We keep your data for as long as your account is active so the service works as expected.
  - period: null
    scope: Limited records
    text: We retain limited records longer where we need them for billing, security, dispute resolution, or to meet legal obligations, and backups age out on a rolling basis.
  rights:
  - right: Access and export
    text: Access and export a copy of your data from Account, then Data.
  - right: Deletion
    text: Delete your account and associated data from Account, then Data.
  - right: Correction
    text: Correct or update your profile information at any time.
  - right: Object or restrict processing
    text: you may also have rights to object to or restrict certain processing, to data portability, and to lodge a complaint with your local data protection authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information
  subprocessors:
    text: 'Amazon Web Services (AWS): managed AI inference uses Amazon Bedrock, and AWS provides compute for agent virtual machines in the United States.'
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we rely on appropriate safeguards such as Standard Contractual Clauses or equivalent mechanisms for these transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Coasty
provenance_date: '2026-11-09'
provider_name: Coasty
provider_slug: coasty
slug: coasty-privacy-policy
source_date: '2026-11-09'
source_filename: coasty-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://coasty.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Coasty\naid: coasty\nurl: https://coasty.ai/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address, and your name and profile picture if you provide them.\n- category: contact\n  text: Onboarding details you choose to share (role, company, team size, use case).\n- category: financial\n  text: Subscription, billing, and transaction records.\n- category: behavioral\n  text: Usage patterns, performance data, and, where you have consented, cookies and analytics identifiers.\n- category: device\n  text: IP address, device and\
  \ browser information, and the desktop app's system identifiers.\n- category: communication\n  text: Your prompts and chats, and the assistant's replies.\n- category: other\n  text: Screenshots of the screen the agent is operating, captured during a session so the model can see what it\n    is doing.\npurposes:\n- purpose: Provide and operate the service\n  text: Provide and operate the service, and run the AI agents and virtual machines you request.\n- purpose: Security and abuse prevention\n  text: Secure the service, detect and prevent abuse, fraud, and misuse, and enforce our Terms.\n- purpose: Improve the service\n  text: Measure usage and analyze, debug, and improve the service, our agents, and the product experience.\n- purpose: Billing and support\n  text: Bill you, manage subscriptions and credits, and provide support.\n- purpose: Legal compliance\n  text: Comply with legal obligations and respond to lawful requests.\nretention:\n- scope: Account data\n  period: as long as your\
  \ account is active\n  text: We keep your data for as long as your account is active so the service works as expected.\n- scope: Limited records\n  period: null\n  text: We retain limited records longer where we need them for billing, security, dispute resolution, or to meet\n    legal obligations, and backups age out on a rolling basis.\nresidency:\n- region: United States\n  text: Coasty is operated from the United States, and the providers above process data in the United States.\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on appropriate safeguards such as Standard Contractual Clauses or equivalent mechanisms\n    for these transfers.\nsubprocessors:\n  url: null\n  text: 'Amazon Web Services (AWS): managed AI inference uses Amazon Bedrock, and AWS provides compute for agent\n    virtual machines in the United States.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account, then Data\n  text: you can delete your entire account and its associated\
  \ data from Account, then Data.\nrights:\n- right: Access and export\n  text: Access and export a copy of your data from Account, then Data.\n- right: Deletion\n  text: Delete your account and associated data from Account, then Data.\n- right: Correction\n  text: Correct or update your profile information at any time.\n- right: Object or restrict processing\n  text: you may also have rights to object to or restrict certain processing, to data portability, and to lodge\n    a complaint with your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information\n"
source_yaml_url: https://artifacts.apis.io/coasty/privacy/coasty-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Coasty's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Computer Use
- AI Agents
- Automation
- RPA
- Desktop Automation
- Browser Automation
- MCP
- Virtual Machines
- Developer Tools
---
