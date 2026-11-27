---
api_specs:
- filename: attestari-ai-health-api-openapi.yml
  format: yaml
  label: Attestari Health API
  slug: attestari-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestari-ai/openapi/attestari-ai-health-api-openapi.yml
- filename: attestari-ai-manifest-api-openapi.yml
  format: yaml
  label: Attestari Manifest API
  slug: attestari-ai-manifest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestari-ai/openapi/attestari-ai-manifest-api-openapi.yml
- filename: attestari-ai-remote-api-openapi.yml
  format: yaml
  label: Attestari Remote API
  slug: attestari-ai-remote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestari-ai/openapi/attestari-ai-remote-api-openapi.yml
- filename: attestari-ai-verdict-api-openapi.yml
  format: yaml
  label: Attestari Verdict API
  slug: attestari-ai-verdict-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/attestari-ai/openapi/attestari-ai-verdict-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: name, email, company; sign-in by a code sent to your email'
  - category: device
    text: Agents and their servers (computer name, system, agent, hook version, each server's name, source, package and version)
  - category: financial
    text: 'Billing: plan, seats, billing address, tax ID if given, payment status, last four digits of the card'
  - category: location
    text: 'Sign-in history: the time of each sign-in, the IP address it came from, the approximate city of that address, and the browser'
  - category: communication
    text: 'Messages: emails and appeals you send us'
  deletion:
    route: Web app or email to contact@elite360.ai
    text: You can see, export, correct or delete your data from the web app, or by emailing contact@elite360.ai .
  dpa:
    available: true
    text: When a company uses Attestari to manage its people's devices, the company controls that data and we process it on its behalf under the Data Processing Agreement
    url: null
  purposes:
  - purpose: Create and secure account
    text: To create and secure your account
  - purpose: Charge and keep tax records
    text: To charge you and keep tax records. Stripe holds the full card details
  - purpose: Show tools with grades and enforce policy
    text: To show your tools with their grades, to enforce your policy, and to email you when the grade of one of them changes
  - purpose: Tell about package grade changes
    text: To tell you when the grade of a package you depend on changes
  - purpose: Examine private artifacts
    text: To examine them and produce your report
  retention:
  - period: 30 days
    scope: Account data
    text: While your account is open, then deleted within 30 days of closing it
  - period: 13 months
    scope: Lookup records
    text: Lookup records 13 months, for billing and abuse prevention
  - period: 30 days
    scope: Private artifacts
    text: Deleted within 30 days after the report is delivered.
  - period: 7 years
    scope: Billing and tax records
    text: Billing and tax records 7 years, as tax law requires
  - period: 30 days
    scope: Service logs and crash reports
    text: Service logs and crash reports 30 days
  - period: 24 months
    scope: Messages and appeals
    text: Messages and appeals 24 months after the matter is closed
  rights:
  - right: See, export, correct or delete data
    text: You can see, export, correct or delete your data from the web app, or by emailing contact@elite360.ai .
  - right: Complain to data protection authority
    text: including the right to complain to your data protection authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell personal information and never use it for advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Code you send us for a private examination is analysed by our AI provider, Anthropic, which does not train its models on it.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Attestari
provenance_date: '2026-11-09'
provider_name: Attestari
provider_slug: attestari-ai
slug: attestari-ai-privacy-policy
source_date: '2026-11-09'
source_filename: attestari-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://attestari.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Attestari\naid: attestari-ai\nurl: https://attestari.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account: name, email, company; sign-in by a code sent to your email'\n- category: device\n  text: Agents and their servers (computer name, system, agent, hook version, each server's name, source, package\n    and version)\n- category: financial\n  text: 'Billing: plan, seats, billing address, tax ID if given, payment status, last four digits of the card'\n- category: location\n  text: 'Sign-in history: the time of each sign-in,\
  \ the IP address it came from, the approximate city of that address,\n    and the browser'\n- category: communication\n  text: 'Messages: emails and appeals you send us'\npurposes:\n- purpose: Create and secure account\n  text: To create and secure your account\n- purpose: Charge and keep tax records\n  text: To charge you and keep tax records. Stripe holds the full card details\n- purpose: Show tools with grades and enforce policy\n  text: To show your tools with their grades, to enforce your policy, and to email you when the grade of one of\n    them changes\n- purpose: Tell about package grade changes\n  text: To tell you when the grade of a package you depend on changes\n- purpose: Examine private artifacts\n  text: To examine them and produce your report\nretention:\n- scope: Account data\n  period: 30 days\n  text: While your account is open, then deleted within 30 days of closing it\n- scope: Lookup records\n  period: 13 months\n  text: Lookup records 13 months, for billing and\
  \ abuse prevention\n- scope: Private artifacts\n  period: 30 days\n  text: Deleted within 30 days after the report is delivered.\n- scope: Billing and tax records\n  period: 7 years\n  text: Billing and tax records 7 years, as tax law requires\n- scope: Service logs and crash reports\n  period: 30 days\n  text: Service logs and crash reports 30 days\n- scope: Messages and appeals\n  period: 24 months\n  text: Messages and appeals 24 months after the matter is closed\nresidency: []\ntransfers:\n- mechanism: other\n  text: Code you send us for a private examination is analysed by our AI provider, Anthropic, which does not train\n    its models on it.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: When a company uses Attestari to manage its people's devices, the company controls that data and we process\n    it on its behalf under the Data Processing Agreement\ndeletion:\n  route: Web app or email to contact@elite360.ai\n  text: You can see, export,\
  \ correct or delete your data from the web app, or by emailing contact@elite360.ai .\nrights:\n- right: See, export, correct or delete data\n  text: You can see, export, correct or delete your data from the web app, or by emailing contact@elite360.ai .\n- right: Complain to data protection authority\n  text: including the right to complain to your data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell personal information and never use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/attestari-ai/privacy/attestari-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Attestari's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- MCP
- Security
- Compliance
- Open Source
---
