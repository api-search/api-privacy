---
api_specs:
- filename: claw-link-dev-discovery-api-openapi.yml
  format: yaml
  label: ClawLink Discovery API
  slug: claw-link-dev-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claw-link-dev/openapi/claw-link-dev-discovery-api-openapi.yml
- filename: claw-link-dev-execution-api-openapi.yml
  format: yaml
  label: ClawLink Execution API
  slug: claw-link-dev-execution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claw-link-dev/openapi/claw-link-dev-execution-api-openapi.yml
- filename: claw-link-dev-mcp-api-openapi.yml
  format: yaml
  label: ClawLink MCP API
  slug: claw-link-dev-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claw-link-dev/openapi/claw-link-dev-mcp-api-openapi.yml
- filename: claw-link-dev-registration-api-openapi.yml
  format: yaml
  label: ClawLink Registration API
  slug: claw-link-dev-registration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claw-link-dev/openapi/claw-link-dev-registration-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: your email address and the identifiers from sign-in.'
  - category: financial
    text: We receive your plan, subscription status, payments and credit balance.
  - category: communication
    text: 'Support: the messages you send us in the chat or by email'
  - category: behavioral
    text: 'Usage and device data: the pages you visit, the features you use, your IP address, browser, device type and approximate location.'
  - category: other
    text: for each call your agent makes, we log the tool name, the arguments your agent sent, the response the app returned, the status and the time it took.
  deletion:
    route: Settings, then Security, then Delete account
    text: To delete your account, open Settings, then Security, then Delete account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide ClawLink (contract)
    text: 'To provide ClawLink (performance of our contract with you, GDPR Art. 6(1)(b)): create your account, connect your apps, run the tool calls that you or your agent request, bill you, and give support.'
  - purpose: Security and improvement (legitimate interests)
    text: 'To keep ClawLink secure and improve it (our legitimate interests, GDPR Art. 6(1)(f)): find and fix failures, prevent abuse and fraud, enforce plan limits, measure which features people use, measure which campaigns bring sign-ups, and send you tips about ClawLink.'
  residency:
  - region: United States, European Union, Singapore and China
    text: Our providers are in the United States, the European Union, Singapore and China
  retention:
  - period: 90 days
    scope: Tool-call logs
    text: 'Tool-call logs: 90 days. After that, we delete them automatically.'
  - period: 30 days
    scope: Database backups
    text: Database backups expire within 30 days.
  - period: while your account exists
    scope: Account, connection and playground data
    text: 'Account, connection and playground data: while your account exists.'
  - period: as long as tax and accounting law requires
    scope: Billing records
    text: 'Billing records: as long as tax and accounting law requires.'
  rights:
  - right: Access
    text: get a copy of the personal data we hold about you
  - right: Correction
    text: correct data that is wrong or incomplete
  - right: Erasure
    text: ask us to delete your data
  - right: Restriction
    text: ask us to limit how we use your data
  - right: Objection
    text: object to a use based on our legitimate interests, and to all marketing
  - right: Portability
    text: get the data you gave us in a machine-readable format
  role:
    text: ClawLink is the controller of your account, billing, support and usage data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: The full list of subprocessors, our security controls and our documents are on the ClawLink Trust Center
    url: null
  transfers:
  - mechanism: SCC
    text: such as the European Commission's Standard Contractual Clauses
  - mechanism: DPF
    text: certification under the EU-U.S. Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ClawLink
provenance_date: '2026-11-09'
provider_name: ClawLink
provider_slug: claw-link-dev
slug: claw-link-dev-privacy-policy
source_date: '2026-11-09'
source_filename: claw-link-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://claw-link.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ClawLink\naid: claw-link-dev\nurl: https://claw-link.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: ClawLink is the controller of your account, billing, support and usage data.\ndata_categories:\n- category: identifying\n  text: 'Account: your email address and the identifiers from sign-in.'\n- category: financial\n  text: We receive your plan, subscription status, payments and credit balance.\n- category: communication\n  text: 'Support: the messages you send us in the chat or by email'\n- category: behavioral\n  text: 'Usage and device data: the pages you visit, the features\
  \ you use, your IP address, browser, device type\n    and approximate location.'\n- category: other\n  text: for each call your agent makes, we log the tool name, the arguments your agent sent, the response the app\n    returned, the status and the time it took.\npurposes:\n- purpose: Provide ClawLink (contract)\n  text: 'To provide ClawLink (performance of our contract with you, GDPR Art. 6(1)(b)): create your account, connect\n    your apps, run the tool calls that you or your agent request, bill you, and give support.'\n- purpose: Security and improvement (legitimate interests)\n  text: 'To keep ClawLink secure and improve it (our legitimate interests, GDPR Art. 6(1)(f)): find and fix failures,\n    prevent abuse and fraud, enforce plan limits, measure which features people use, measure which campaigns bring\n    sign-ups, and send you tips about ClawLink.'\nretention:\n- scope: Tool-call logs\n  period: 90 days\n  text: 'Tool-call logs: 90 days. After that, we delete them automatically.'\n\
  - scope: Database backups\n  period: 30 days\n  text: Database backups expire within 30 days.\n- scope: Account, connection and playground data\n  period: while your account exists\n  text: 'Account, connection and playground data: while your account exists.'\n- scope: Billing records\n  period: as long as tax and accounting law requires\n  text: 'Billing records: as long as tax and accounting law requires.'\nresidency:\n- region: United States, European Union, Singapore and China\n  text: Our providers are in the United States, the European Union, Singapore and China\ntransfers:\n- mechanism: SCC\n  text: such as the European Commission's Standard Contractual Clauses\n- mechanism: DPF\n  text: certification under the EU-U.S. Data Privacy Framework\nsubprocessors:\n  url: null\n  text: The full list of subprocessors, our security controls and our documents are on the ClawLink Trust Center\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings, then Security,\
  \ then Delete account\n  text: To delete your account, open Settings, then Security, then Delete account.\nrights:\n- right: Access\n  text: get a copy of the personal data we hold about you\n- right: Correction\n  text: correct data that is wrong or incomplete\n- right: Erasure\n  text: ask us to delete your data\n- right: Restriction\n  text: ask us to limit how we use your data\n- right: Objection\n  text: object to a use based on our legitimate interests, and to all marketing\n- right: Portability\n  text: get the data you gave us in a machine-readable format\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/claw-link-dev/privacy/claw-link-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from ClawLink's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Integration
- Automation
- Productivity
- Developer Tools
---
