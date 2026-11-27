---
api_specs:
- filename: browser-use-browsers-api-openapi.yml
  format: yaml
  label: Browser Use Browsers API
  slug: browser-use-browsers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browser-use/openapi/browser-use-browsers-api-openapi.yml
- filename: browser-use-profiles-api-openapi.yml
  format: yaml
  label: Browser Use Profiles API
  slug: browser-use-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browser-use/openapi/browser-use-profiles-api-openapi.yml
- filename: browser-use-runs-api-openapi.yml
  format: yaml
  label: Browser Use Runs API
  slug: browser-use-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browser-use/openapi/browser-use-runs-api-openapi.yml
- filename: browser-use-sessions-api-openapi.yml
  format: yaml
  label: Browser Use Sessions API
  slug: browser-use-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browser-use/openapi/browser-use-sessions-api-openapi.yml
- filename: browser-use-workspaces-api-openapi.yml
  format: yaml
  label: Browser Use Workspaces API
  slug: browser-use-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browser-use/openapi/browser-use-workspaces-api-openapi.yml
- filename: browser-use-extensions-api-openapi.yml
  format: yaml
  label: Browser Use Extensions API
  slug: browser-use-extensions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browser-use/openapi/browser-use-extensions-api-openapi.yml
- filename: browser-use-integrations-api-openapi.yml
  format: yaml
  label: Browser Use Integrations API
  slug: browser-use-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browser-use/openapi/browser-use-integrations-api-openapi.yml
- filename: browser-use-wallets-api-openapi.yml
  format: yaml
  label: Browser Use Wallets API
  slug: browser-use-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/browser-use/openapi/browser-use-wallets-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Contact and account credentials , such as your name, email address, and password when you sign up for an account
  - category: contact
    text: Feedback or correspondence , such as information you provide when you contact us with questions, feedback, or otherwise correspond with us online.
  - category: financial
    text: Payment information , needed to complete any transactions with us, including your name, payment card details, and billing address.
  - category: location
    text: General location information , such as city, state or geographic area.
  - category: behavioral
    text: Usage data , such as how long was spent on the AI agent, usage history, navigation paths
  - category: device
    text: Device data , such as the computer or mobile device's operating system type and version, manufacturer and model, browser type, screen resolution, device type (e.g., phone, tablet), IP address, unique identifiers, language settings.
  - category: communication
    text: 'User-Provided Content (Inputs/Prompts) : When you interact with the AI agent, we collect the data, text, files, images, or other content you submit to the agent ("Inputs").'
  deletion:
    route: Request via privacy@browser-use.com
    text: Deletion of personal information that we no longer need to provide our Services or for other lawful purposes.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate the Services
    text: We use Inputs, including any personal information in them, to provide, operate, maintain, and secure our Services in accordance with our Terms of Service.
  - purpose: Model training
    text: 'Model Training : We use Inputs to train our AI models in order to improve the Services.'
  - purpose: Aggregate and de-identified datasets
    text: To create aggregated, de-identified, anonymous, or sanitized data and task datasets derived from Inputs, Outputs, usage telemetry, and workflow patterns.
  - purpose: Direct marketing
    text: We may from time-to-time send you direct marketing communications as permitted by law.
  - purpose: Compliance and protection
    text: We may use your personal information to comply with legal obligations
  retention:
  - period: null
    scope: Personal information generally
    text: We retain personal information for as long as necessary in order to provide our Services to you, or for other legitimate business purposes such as resolving disputes, safety and security reasons, or complying with our legal obligations.
  rights:
  - right: Access
    text: Access to a copy of the personal information that we have collected about you.
  - right: Correction
    text: Correction of personal information that is inaccurate or out of date.
  - right: Deletion
    text: Deletion of personal information that we no longer need to provide our Services or for other lawful purposes.
  - right: Opt out of sale or sharing
    text: Opt out of the sale of your information or sharing of your information for interest-based advertising.
  - right: Object or restrict
    text: Additional rights , such as to object to our processing of your personal information where we rely on our legitimate business interest to do so, request that we restrict our use of personal information
  - right: Complain
    text: 'Right to complain : Depending on where you reside, such as if you reside in the European Economic Area (EEA) or United Kingdom, you may have the right to complain to a data protection regulator'
  role:
    text: Browser Use, Inc. is the entity responsible for the processing of personal information under this Privacy Policy (as a controller or business, where provided under applicable law).
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not engage (and have not in the past 12 months engaged) in the sale of your personal information, or the sharing of your personal information for interest-based advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Browser Use
provenance_date: '2026-11-09'
provider_name: Browser Use
provider_slug: browser-use
slug: browser-use-privacy-policy
source_date: '2026-11-09'
source_filename: browser-use-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://browser-use.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Browser Use\naid: browser-use\nurl: https://browser-use.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Browser Use, Inc. is the entity responsible for the processing of personal information under this Privacy\n    Policy (as a controller or business, where provided under applicable law).\ndata_categories:\n- category: identifying\n  text: Contact and account credentials , such as your name, email address, and password when you sign up for an\n    account\n- category: contact\n  text: Feedback or correspondence , such as information you provide when you contact us with questions,\
  \ feedback,\n    or otherwise correspond with us online.\n- category: financial\n  text: Payment information , needed to complete any transactions with us, including your name, payment card details,\n    and billing address.\n- category: location\n  text: General location information , such as city, state or geographic area.\n- category: behavioral\n  text: Usage data , such as how long was spent on the AI agent, usage history, navigation paths\n- category: device\n  text: Device data , such as the computer or mobile device's operating system type and version, manufacturer and\n    model, browser type, screen resolution, device type (e.g., phone, tablet), IP address, unique identifiers, language\n    settings.\n- category: communication\n  text: 'User-Provided Content (Inputs/Prompts) : When you interact with the AI agent, we collect the data, text,\n    files, images, or other content you submit to the agent (\"Inputs\").'\npurposes:\n- purpose: Operate the Services\n  text: We use Inputs,\
  \ including any personal information in them, to provide, operate, maintain, and secure our\n    Services in accordance with our Terms of Service.\n- purpose: Model training\n  text: 'Model Training : We use Inputs to train our AI models in order to improve the Services.'\n- purpose: Aggregate and de-identified datasets\n  text: To create aggregated, de-identified, anonymous, or sanitized data and task datasets derived from Inputs,\n    Outputs, usage telemetry, and workflow patterns.\n- purpose: Direct marketing\n  text: We may from time-to-time send you direct marketing communications as permitted by law.\n- purpose: Compliance and protection\n  text: We may use your personal information to comply with legal obligations\nretention:\n- scope: Personal information generally\n  period: null\n  text: We retain personal information for as long as necessary in order to provide our Services to you, or for\n    other legitimate business purposes such as resolving disputes, safety and security\
  \ reasons, or complying with\n    our legal obligations.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via privacy@browser-use.com\n  text: Deletion of personal information that we no longer need to provide our Services or for other lawful purposes.\nrights:\n- right: Access\n  text: Access to a copy of the personal information that we have collected about you.\n- right: Correction\n  text: Correction of personal information that is inaccurate or out of date.\n- right: Deletion\n  text: Deletion of personal information that we no longer need to provide our Services or for other lawful purposes.\n- right: Opt out of sale or sharing\n  text: Opt out of the sale of your information or sharing of your information for interest-based advertising.\n- right: Object or restrict\n  text: Additional rights , such as to object to our processing of your personal information where we rely on our\n\
  \    legitimate business interest to do so, request that we restrict our use of personal information\n- right: Complain\n  text: 'Right to complain : Depending on where you reside, such as if you reside in the European Economic Area\n    (EEA) or United Kingdom, you may have the right to complain to a data protection regulator'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not engage (and have not in the past 12 months engaged) in the sale of your personal information,\n    or the sharing of your personal information for interest-based advertising.\n"
source_yaml_url: https://artifacts.apis.io/browser-use/privacy/browser-use-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Browser Use's own page on 2026-11-09.
synthetic: false
tags:
- AI Automation
- Browser Automation
- Web Agents
- Web Scraping
- Agent Infrastructure
- MCP
- Cloud Browser
- A2A
---
