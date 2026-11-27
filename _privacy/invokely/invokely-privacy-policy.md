---
api_specs:
- filename: invokely-openapi-generated.yml
  format: yaml
  label: Invokely API
  slug: invokely-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invokely/openapi/_ae-authored/invokely-openapi-generated.yml
- filename: invokely-rank-api-openapi.yml
  format: yaml
  label: Invokely Rank API
  slug: invokely-rank-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/invokely/openapi/invokely-rank-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your email address. If you sign in with Google, also your name and your Google account identifier.'
  - category: financial
    text: 'Billing data: your Stripe customer and subscription identifiers, your plan, billing period, and prepaid credit balance and movements.'
  - category: device
    text: 'Technical data: IP address, requested path, user agent and time of each request, kept in our reverse proxy logs.'
  - category: behavioral
    text: 'Usage counts: the number of calls per account, day, channel (API or MCP) and operation, plus monthly totals and credit use.'
  - category: communication
    text: Messages you send us, for example support or privacy requests.
  deletion:
    route: Close your account; data deleted within 30 days
    text: When you close your account, we delete them within 30 days.
  dpa:
    available: true
    text: 'They process it under data processing agreements and our instructions, except where noted:'
    url: null
  purposes:
  - purpose: Account and service provision
    text: To create and run your account, sign you in, issue API keys, connect MCP clients, meter usage and provide paid plans and credits.
  - purpose: Transactional email
    text: To send transactional email, such as sign-in links and messages about your account or billing.
  - purpose: Accounting and tax
    text: To issue invoices and keep accounting and tax records.
  - purpose: Security and abuse prevention
    text: To protect the service from abuse, enforce rate limits, run the anonymous MCP trial, check sign-in forms with Turnstile, investigate incidents, and keep backups.
  residency:
  - region: European Union
    text: Our application and database run in the European Union.
  retention:
  - period: while your account is open
    scope: Account data and usage counts
    text: 'Account data, API key records, connected client records and usage counts: while your account is open.'
  - period: 14 days
    scope: Reverse proxy logs
    text: 'Reverse proxy logs: 14 days.'
  - period: up to 5 weeks
    scope: Backups
    text: 'Backups: encrypted database backups are kept for up to 5 weeks, then overwritten.'
  - period: 6 years after the end of the financial year they relate to
    scope: Billing records and invoices
    text: 'Billing records and invoices: 6 years after the end of the financial year they relate to, as required by Article 30 of the Spanish Commercial Code.'
  rights:
  - right: access
    text: access the personal data we hold about you and get a copy
  - right: correction
    text: correct data that is inaccurate
  - right: erasure
    text: have your data erased
  - right: restriction
    text: restrict processing in some cases
  - right: portability
    text: receive data you gave us in a machine-readable format and have it sent to another provider (portability)
  - right: objection
    text: object to processing based on our legitimate interest
  role:
    text: The controller of your personal data is [Legal entity name], tax ID [Tax ID (NIF or CIF)], with its registered address at [Registered address].
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and we do not use it for advertising.
  subprocessors:
    text: The subprocessors page lists each provider with its legal entity, location and transfer safeguards.
    url: null
  transfers:
  - mechanism: DPF
    text: These transfers rely on the EU-U.S. Data Privacy Framework, under the European Commission's adequacy decision of 10 July 2023, for providers certified under it.
  - mechanism: SCC
    text: Where a transfer is not covered by that framework, it relies on the Standard Contractual Clauses approved by the European Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Invokely
provenance_date: '2026-11-09'
provider_name: Invokely
provider_slug: invokely
slug: invokely-privacy-policy
source_date: '2026-11-09'
source_filename: invokely-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://invokely.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Invokely\naid: invokely\nurl: https://invokely.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller of your personal data is [Legal entity name], tax ID [Tax ID (NIF or CIF)], with its registered\n    address at [Registered address].\ndata_categories:\n- category: identifying\n  text: 'Account data: your email address. If you sign in with Google, also your name and your Google account identifier.'\n- category: financial\n  text: 'Billing data: your Stripe customer and subscription identifiers, your plan, billing period, and prepaid\n    credit balance and movements.'\n\
  - category: device\n  text: 'Technical data: IP address, requested path, user agent and time of each request, kept in our reverse proxy\n    logs.'\n- category: behavioral\n  text: 'Usage counts: the number of calls per account, day, channel (API or MCP) and operation, plus monthly totals\n    and credit use.'\n- category: communication\n  text: Messages you send us, for example support or privacy requests.\npurposes:\n- purpose: Account and service provision\n  text: To create and run your account, sign you in, issue API keys, connect MCP clients, meter usage and provide\n    paid plans and credits.\n- purpose: Transactional email\n  text: To send transactional email, such as sign-in links and messages about your account or billing.\n- purpose: Accounting and tax\n  text: To issue invoices and keep accounting and tax records.\n- purpose: Security and abuse prevention\n  text: To protect the service from abuse, enforce rate limits, run the anonymous MCP trial, check sign-in forms\n   \
  \ with Turnstile, investigate incidents, and keep backups.\nretention:\n- scope: Account data and usage counts\n  period: while your account is open\n  text: 'Account data, API key records, connected client records and usage counts: while your account is open.'\n- scope: Reverse proxy logs\n  period: 14 days\n  text: 'Reverse proxy logs: 14 days.'\n- scope: Backups\n  period: up to 5 weeks\n  text: 'Backups: encrypted database backups are kept for up to 5 weeks, then overwritten.'\n- scope: Billing records and invoices\n  period: 6 years after the end of the financial year they relate to\n  text: 'Billing records and invoices: 6 years after the end of the financial year they relate to, as required by\n    Article 30 of the Spanish Commercial Code.'\nresidency:\n- region: European Union\n  text: Our application and database run in the European Union.\ntransfers:\n- mechanism: DPF\n  text: These transfers rely on the EU-U.S. Data Privacy Framework, under the European Commission's adequacy\
  \ decision\n    of 10 July 2023, for providers certified under it.\n- mechanism: SCC\n  text: Where a transfer is not covered by that framework, it relies on the Standard Contractual Clauses approved\n    by the European Commission.\nsubprocessors:\n  url: null\n  text: The subprocessors page lists each provider with its legal entity, location and transfer safeguards.\ndpa:\n  available: true\n  url: null\n  text: 'They process it under data processing agreements and our instructions, except where noted:'\ndeletion:\n  route: Close your account; data deleted within 30 days\n  text: When you close your account, we delete them within 30 days.\nrights:\n- right: access\n  text: access the personal data we hold about you and get a copy\n- right: correction\n  text: correct data that is inaccurate\n- right: erasure\n  text: have your data erased\n- right: restriction\n  text: restrict processing in some cases\n- right: portability\n  text: receive data you gave us in a machine-readable format\
  \ and have it sent to another provider (portability)\n- right: objection\n  text: object to processing based on our legitimate interest\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and we do not use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/invokely/privacy/invokely-privacy-policy.yml
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
summary_line: 27 quoted statements, read from Invokely's own page on 2026-11-09.
synthetic: false
tags:
- Statistics
- Economic Data
- Public Data
- Data API
---
