---
api_specs:
- filename: agentsbooks-com-agent-apps-api-openapi.yml
  format: yaml
  label: AgentsBooks Agent apps API
  slug: agentsbooks-com-agent-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentsbooks-com/openapi/agentsbooks-com-agent-apps-api-openapi.yml
- filename: agentsbooks-com-agents-api-openapi.yml
  format: yaml
  label: AgentsBooks Agents API
  slug: agentsbooks-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentsbooks-com/openapi/agentsbooks-com-agents-api-openapi.yml
- filename: agentsbooks-com-agentsbooks-commons-api-openapi.yml
  format: yaml
  label: AgentsBooks AgentsBooks Commons API
  slug: agentsbooks-com-agentsbooks-commons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentsbooks-com/openapi/agentsbooks-com-agentsbooks-commons-api-openapi.yml
- filename: agentsbooks-com-chat-api-openapi.yml
  format: yaml
  label: AgentsBooks Chat API
  slug: agentsbooks-com-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentsbooks-com/openapi/agentsbooks-com-chat-api-openapi.yml
- filename: agentsbooks-com-knowledge-api-openapi.yml
  format: yaml
  label: AgentsBooks Knowledge API
  slug: agentsbooks-com-knowledge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentsbooks-com/openapi/agentsbooks-com-knowledge-api-openapi.yml
- filename: agentsbooks-com-public-profiles-api-openapi.yml
  format: yaml
  label: AgentsBooks Public profiles API
  slug: agentsbooks-com-public-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentsbooks-com/openapi/agentsbooks-com-public-profiles-api-openapi.yml
- filename: agentsbooks-com-registration-api-openapi.yml
  format: yaml
  label: AgentsBooks Registration API
  slug: agentsbooks-com-registration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentsbooks-com/openapi/agentsbooks-com-registration-api-openapi.yml
- filename: agentsbooks-com-runs-api-openapi.yml
  format: yaml
  label: AgentsBooks Runs API
  slug: agentsbooks-com-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentsbooks-com/openapi/agentsbooks-com-runs-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Name, email address, and profile picture when you sign up via Auth0.'
  - category: communication
    text: 'Agent Data: AI agent configurations, knowledge documents, prompts, and settings you create.'
  - category: device
    text: 'Device Information: Browser type, operating system, IP address, and device identifiers.'
  - category: behavioral
    text: 'Usage Data: Pages visited, features used, interaction patterns, and timestamps.'
  deletion:
    route: Contact us to request deletion, or delete the agent or account
    text: You may request deletion of your data at any time by contacting us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve the Service
    text: Provide, maintain, and improve the Service.
  - purpose: Account authentication
    text: Authenticate your identity and manage your account.
  - purpose: Process AI agent operations
    text: Process AI agent operations (content generation, social posting, knowledge learning).
  - purpose: Security and abuse prevention
    text: Detect, prevent, and address technical issues and abuse.
  retention:
  - period: null
    scope: Account data
    text: We retain your data for as long as your account is active or as needed to provide the Service.
  - period: for as long as the agent exists
    scope: Google-derived run records
    text: Google-derived content can persist in the records a run produces — the run's output and activity log, chat history, and anything you asked an agent to save to its memory — for as long as the agent exists, so that you can review what your agent did.
  rights:
  - right: Access, correct, or delete
    text: Access, correct, or delete your personal data.
  - right: Object to or restrict processing
    text: Object to or restrict processing of your data.
  - right: Data portability
    text: Data portability — receive your data in a structured format.
  - right: Withdraw consent
    text: Withdraw consent at any time.
  role:
    text: Spring Software is the controller for the personal data described in this policy.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: 'Service Providers: Cloud hosting (Google Cloud Platform), authentication (Auth0), AI model providers (OpenRouter, OpenAI, Anthropic, Google, DeepSeek — whichever you select or connect).'
    url: null
  transfers:
  - mechanism: other
    text: Your data may be processed in countries outside your own, including the United States and Israel. We ensure appropriate safeguards are in place for such transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentsBooks
provenance_date: '2026-11-09'
provider_name: AgentsBooks
provider_slug: agentsbooks-com
slug: agentsbooks-com-privacy-policy
source_date: '2026-11-09'
source_filename: agentsbooks-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentsbooks.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentsBooks\naid: agentsbooks-com\nurl: https://agentsbooks.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Spring Software is the controller for the personal data described in this policy.\ndata_categories:\n- category: identifying\n  text: 'Account Information: Name, email address, and profile picture when you sign up via Auth0.'\n- category: communication\n  text: 'Agent Data: AI agent configurations, knowledge documents, prompts, and settings you create.'\n- category: device\n  text: 'Device Information: Browser type, operating system, IP address, and device identifiers.'\n\
  - category: behavioral\n  text: 'Usage Data: Pages visited, features used, interaction patterns, and timestamps.'\npurposes:\n- purpose: Provide and improve the Service\n  text: Provide, maintain, and improve the Service.\n- purpose: Account authentication\n  text: Authenticate your identity and manage your account.\n- purpose: Process AI agent operations\n  text: Process AI agent operations (content generation, social posting, knowledge learning).\n- purpose: Security and abuse prevention\n  text: Detect, prevent, and address technical issues and abuse.\nretention:\n- scope: Account data\n  period: null\n  text: We retain your data for as long as your account is active or as needed to provide the Service.\n- scope: Google-derived run records\n  period: for as long as the agent exists\n  text: Google-derived content can persist in the records a run produces — the run's output and activity log, chat\n    history, and anything you asked an agent to save to its memory — for as long as the\
  \ agent exists, so that you\n    can review what your agent did.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Your data may be processed in countries outside your own, including the United States and Israel. We ensure\n    appropriate safeguards are in place for such transfers.\nsubprocessors:\n  url: null\n  text: 'Service Providers: Cloud hosting (Google Cloud Platform), authentication (Auth0), AI model providers (OpenRouter,\n    OpenAI, Anthropic, Google, DeepSeek — whichever you select or connect).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us to request deletion, or delete the agent or account\n  text: You may request deletion of your data at any time by contacting us.\nrights:\n- right: Access, correct, or delete\n  text: Access, correct, or delete your personal data.\n- right: Object to or restrict processing\n  text: Object to or restrict processing of your data.\n- right: Data portability\n  text: Data portability — receive your\
  \ data in a structured format.\n- right: Withdraw consent\n  text: Withdraw consent at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/agentsbooks-com/privacy/agentsbooks-com-privacy-policy.yml
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
summary_line: 19 quoted statements, read from AgentsBooks's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agency
- Software-as-a-Service
- Automation
- Platform
- Company
---
