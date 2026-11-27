---
api_specs:
- filename: salesgraph-audit-api-openapi.yml
  format: yaml
  label: Salesgraph Audit API
  slug: salesgraph-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesgraph/openapi/salesgraph-audit-api-openapi.yml
- filename: salesgraph-commands-api-openapi.yml
  format: yaml
  label: Salesgraph Commands API
  slug: salesgraph-commands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesgraph/openapi/salesgraph-commands-api-openapi.yml
- filename: salesgraph-runs-api-openapi.yml
  format: yaml
  label: Salesgraph Runs API
  slug: salesgraph-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesgraph/openapi/salesgraph-runs-api-openapi.yml
- filename: salesgraph-oms-api-openapi.yml
  format: yaml
  label: Salesgraph OMS API
  slug: salesgraph-oms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesgraph/openapi/salesgraph-oms-api-openapi.yml
- filename: salesgraph-status-api-openapi.yml
  format: yaml
  label: Salesgraph Status API
  slug: salesgraph-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesgraph/openapi/salesgraph-status-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and business information, such as names, work email addresses, company names, titles, billing details, and administrator settings.
  - category: device
    text: Website and product usage information, such as IP address, browser and device details, session activity, pages viewed, referring URLs
  - category: communication
    text: Integration data from tools a customer connects to Antinuous, which may include CRM records, contacts, accounts, opportunities, tasks, notes, emails, calendar events, meeting metadata, call recordings, transcripts, chat messages
  - category: behavioral
    text: usage signals from sales or support systems
  deletion:
    route: privacy requests to the business customer or legal@salesgraph.com
    text: Depending on your location and applicable law, you may have rights to access, correct, delete, restrict, object to, or port certain personal data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service operation and improvement
    text: Provide, operate, secure, maintain, and improve Antinuous and related services.
  - purpose: customer-requested insights
    text: Sync with third-party systems, process customer data, and generate insights, summaries, automations, and recommendations requested by customers or users.
  - purpose: marketing communications
    text: Communicate about service updates, security notices, support matters, events, and, where permitted, marketing communications.
  - purpose: aggregated analytics
    text: Create aggregated or de-identified analytics to understand product performance, market demand, and system reliability.
  retention:
  - period: null
    scope: personal information
    text: We retain personal information for as long as needed for the purposes described in this policy, to provide the service, to comply with legal obligations, to resolve disputes, and to enforce our agreements.
  rights:
  - right: access
    text: you may have rights to access, correct, delete, restrict, object to, or port certain personal data
  - right: opt out of promotional emails
    text: You may opt out of promotional emails using the unsubscribe link in the message.
  role:
    text: Where Antinuous processes customer data on behalf of a business customer, we generally act as a service provider or processor and handle that data under our agreement with the customer.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: With service providers and subprocessors that help us host, secure, monitor, support, and operate the service.
    url: null
  transfers:
  - mechanism: other
    text: When required, we use appropriate safeguards for cross-border data transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Salesgraph
provenance_date: '2026-11-10'
provider_name: Salesgraph
provider_slug: salesgraph
slug: salesgraph-privacy-policy
source_date: '2026-11-10'
source_filename: salesgraph-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://salesgraph.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Salesgraph\naid: salesgraph\nurl: https://salesgraph.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Where Antinuous processes customer data on behalf of a business customer, we generally act as a service\n    provider or processor and handle that data under our agreement with the customer.\ndata_categories:\n- category: identifying\n  text: Account and business information, such as names, work email addresses, company names, titles, billing details,\n    and administrator settings.\n- category: device\n  text: Website and product usage information, such as IP address, browser and device\
  \ details, session activity,\n    pages viewed, referring URLs\n- category: communication\n  text: Integration data from tools a customer connects to Antinuous, which may include CRM records, contacts, accounts,\n    opportunities, tasks, notes, emails, calendar events, meeting metadata, call recordings, transcripts, chat messages\n- category: behavioral\n  text: usage signals from sales or support systems\npurposes:\n- purpose: service operation and improvement\n  text: Provide, operate, secure, maintain, and improve Antinuous and related services.\n- purpose: customer-requested insights\n  text: Sync with third-party systems, process customer data, and generate insights, summaries, automations, and\n    recommendations requested by customers or users.\n- purpose: marketing communications\n  text: Communicate about service updates, security notices, support matters, events, and, where permitted, marketing\n    communications.\n- purpose: aggregated analytics\n  text: Create aggregated\
  \ or de-identified analytics to understand product performance, market demand, and system\n    reliability.\nretention:\n- scope: personal information\n  period: null\n  text: We retain personal information for as long as needed for the purposes described in this policy, to provide\n    the service, to comply with legal obligations, to resolve disputes, and to enforce our agreements.\nresidency: []\ntransfers:\n- mechanism: other\n  text: When required, we use appropriate safeguards for cross-border data transfers.\nsubprocessors:\n  url: null\n  text: With service providers and subprocessors that help us host, secure, monitor, support, and operate the service.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: privacy requests to the business customer or legal@salesgraph.com\n  text: Depending on your location and applicable law, you may have rights to access, correct, delete, restrict,\n    object to, or port certain personal data.\nrights:\n- right: access\n  text:\
  \ you may have rights to access, correct, delete, restrict, object to, or port certain personal data\n- right: opt out of promotional emails\n  text: You may opt out of promotional emails using the unsubscribe link in the message.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/salesgraph/privacy/salesgraph-privacy-policy.yml
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
summary_line: 16 quoted statements, read from Salesgraph's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sales
- Revenue Automation
- Go-To-Market
- AI Agents
- MCP
- Sales Intelligence
- Competitive Intelligence
- Research
- Enterprise Sales
- A2A
---
