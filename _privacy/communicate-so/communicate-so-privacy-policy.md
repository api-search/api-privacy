---
api_specs:
- filename: communicate-so-account-credentials-api-openapi.yml
  format: yaml
  label: communicate-so Account credentials API
  slug: communicate-so-account-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/communicate-so/openapi/communicate-so-account-credentials-api-openapi.yml
- filename: communicate-so-account-preferences-api-openapi.yml
  format: yaml
  label: communicate-so Account preferences API
  slug: communicate-so-account-preferences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/communicate-so/openapi/communicate-so-account-preferences-api-openapi.yml
- filename: communicate-so-agents-api-openapi.yml
  format: yaml
  label: communicate-so Agents API
  slug: communicate-so-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/communicate-so/openapi/communicate-so-agents-api-openapi.yml
- filename: communicate-so-authentication-api-openapi.yml
  format: yaml
  label: communicate-so Authentication API
  slug: communicate-so-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/communicate-so/openapi/communicate-so-authentication-api-openapi.yml
- filename: communicate-so-chat-api-openapi.yml
  format: yaml
  label: communicate-so Chat API
  slug: communicate-so-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/communicate-so/openapi/communicate-so-chat-api-openapi.yml
- filename: communicate-so-discovery-api-openapi.yml
  format: yaml
  label: communicate-so Discovery API
  slug: communicate-so-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/communicate-so/openapi/communicate-so-discovery-api-openapi.yml
- filename: communicate-so-grill-api-openapi.yml
  format: yaml
  label: communicate-so Grill API
  slug: communicate-so-grill-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/communicate-so/openapi/communicate-so-grill-api-openapi.yml
- filename: communicate-so-inbox-api-openapi.yml
  format: yaml
  label: communicate-so Inbox API
  slug: communicate-so-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/communicate-so/openapi/communicate-so-inbox-api-openapi.yml
- filename: communicate-so-learnings-api-openapi.yml
  format: yaml
  label: communicate-so Learnings API
  slug: communicate-so-learnings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/communicate-so/openapi/communicate-so-learnings-api-openapi.yml
- filename: communicate-so-notifications-api-openapi.yml
  format: yaml
  label: communicate-so Notifications API
  slug: communicate-so-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/communicate-so/openapi/communicate-so-notifications-api-openapi.yml
- filename: communicate-so-sources-api-openapi.yml
  format: yaml
  label: communicate-so Sources API
  slug: communicate-so-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/communicate-so/openapi/communicate-so-sources-api-openapi.yml
- filename: communicate-so-teams-api-openapi.yml
  format: yaml
  label: communicate-so Teams API
  slug: communicate-so-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/communicate-so/openapi/communicate-so-teams-api-openapi.yml
- filename: communicate-so-workspace-members-api-openapi.yml
  format: yaml
  label: communicate-so Workspace members API
  slug: communicate-so-workspace-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/communicate-so/openapi/communicate-so-workspace-members-api-openapi.yml
- filename: communicate-so-workspaces-api-openapi.yml
  format: yaml
  label: communicate-so Workspaces API
  slug: communicate-so-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/communicate-so/openapi/communicate-so-workspaces-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name and email address.
  - category: contact
    text: Contact identifiers an end user submits during a chat, such as an email address or name.
  - category: financial
    text: Billing contact details and billing preferences.
  - category: location
    text: IP address and approximate location derived from it.
  - category: behavioral
    text: Pages viewed, features used, and actions taken inside the product.
  - category: device
    text: Browser type, device, and operating system.
  - category: communication
    text: Messages exchanged between a customer end user and the AI agent or a human agent.
  deletion:
    route: email request
    text: To exercise any right under GDPR or CCPA, email [email protected] .
  dpa:
    available: true
    text: Our DPA is published at https://communicate.so/gdpr and applies automatically when you accept our Terms.
    url: https://communicate.so/gdpr
  purposes:
  - purpose: provide the service
    text: 'To provide the service: authenticate you, load your workspace, train your AI agent on the sources you connect'
  - purpose: process billing
    text: 'To process billing: apply your one-time account activation, track credit usage, generate invoices, and maintain your billing history.'
  - purpose: secure the platform
    text: 'To secure the platform: detect and prevent abuse, fraud, and unauthorized access, and maintain audit and error logs.'
  - purpose: advertising measurement with permission
    text: With your permission, to measure website visits and selected account, agent, checkout, and verified-purchase events using Meta Pixel and Conversions API
  residency:
  - region: United States
    text: all customer data is stored on Railway in the United States.
  retention:
  - period: 30 days
    scope: deletion requests
    text: When you request deletion, we delete the relevant personal data within 30 days, subject to the legal retention below.
  - period: 7 years
    scope: billing records
    text: Billing records are retained for 7 years to meet tax, accounting, and other legal requirements.
  rights:
  - right: access
    text: 'Access: obtain a copy of the personal data we hold about you.'
  - right: erasure
    text: 'Erasure: request deletion of your data.'
  - right: portability
    text: 'Portability: receive your data in a portable, machine-readable format.'
  - right: opt out of marketing measurement
    text: 'Opt out: decline or withdraw optional marketing measurement on https://communicate.so/cookies#marketing-choices'
  role:
    text: Communicate sits in both roles depending on the data.
    value: both
  sale_or_sharing:
    stance: conditional
    text: If you allow marketing measurement, we also share selected website and account-conversion events with Meta for advertising measurement.
  subprocessors:
    text: The current list of subprocessors is published at https://communicate.so/gdpr#subprocessors .
    url: https://communicate.so/gdpr#subprocessors
  transfers:
  - mechanism: SCC
    text: For personal data that leaves the EEA or the UK, we rely on Standard Contractual Clauses (SCCs) as the legal transfer mechanism
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: communicate-so
provenance_date: '2026-11-09'
provider_name: communicate-so
provider_slug: communicate-so
slug: communicate-so-privacy-policy
source_date: '2026-11-09'
source_filename: communicate-so-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://communicate.so/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: communicate-so\naid: communicate-so\nurl: https://communicate.so/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Communicate sits in both roles depending on the data.\ndata_categories:\n- category: identifying\n  text: Your name and email address.\n- category: contact\n  text: Contact identifiers an end user submits during a chat, such as an email address or name.\n- category: financial\n  text: Billing contact details and billing preferences.\n- category: location\n  text: IP address and approximate location derived from it.\n- category: behavioral\n  text: Pages viewed, features used, and\
  \ actions taken inside the product.\n- category: device\n  text: Browser type, device, and operating system.\n- category: communication\n  text: Messages exchanged between a customer end user and the AI agent or a human agent.\npurposes:\n- purpose: provide the service\n  text: 'To provide the service: authenticate you, load your workspace, train your AI agent on the sources you connect'\n- purpose: process billing\n  text: 'To process billing: apply your one-time account activation, track credit usage, generate invoices, and\n    maintain your billing history.'\n- purpose: secure the platform\n  text: 'To secure the platform: detect and prevent abuse, fraud, and unauthorized access, and maintain audit and\n    error logs.'\n- purpose: advertising measurement with permission\n  text: With your permission, to measure website visits and selected account, agent, checkout, and verified-purchase\n    events using Meta Pixel and Conversions API\nretention:\n- scope: deletion requests\n  period:\
  \ 30 days\n  text: When you request deletion, we delete the relevant personal data within 30 days, subject to the legal retention\n    below.\n- scope: billing records\n  period: 7 years\n  text: Billing records are retained for 7 years to meet tax, accounting, and other legal requirements.\nresidency:\n- region: United States\n  text: all customer data is stored on Railway in the United States.\ntransfers:\n- mechanism: SCC\n  text: For personal data that leaves the EEA or the UK, we rely on Standard Contractual Clauses (SCCs) as the legal\n    transfer mechanism\nsubprocessors:\n  url: https://communicate.so/gdpr#subprocessors\n  text: The current list of subprocessors is published at https://communicate.so/gdpr#subprocessors .\ndpa:\n  available: true\n  url: https://communicate.so/gdpr\n  text: Our DPA is published at https://communicate.so/gdpr and applies automatically when you accept our Terms.\ndeletion:\n  route: email request\n  text: To exercise any right under GDPR or CCPA,\
  \ email [email protected] .\nrights:\n- right: access\n  text: 'Access: obtain a copy of the personal data we hold about you.'\n- right: erasure\n  text: 'Erasure: request deletion of your data.'\n- right: portability\n  text: 'Portability: receive your data in a portable, machine-readable format.'\n- right: opt out of marketing measurement\n  text: 'Opt out: decline or withdraw optional marketing measurement on https://communicate.so/cookies#marketing-choices'\nsale_or_sharing:\n  stance: conditional\n  text: If you allow marketing measurement, we also share selected website and account-conversion events with Meta\n    for advertising measurement.\n"
source_yaml_url: https://artifacts.apis.io/communicate-so/privacy/communicate-so-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from communicate-so's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Customer Service
- Chatbots
- Software-as-a-Service
- Automation
---
