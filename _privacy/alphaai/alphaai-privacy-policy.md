---
api_specs:
- filename: alphaai-calendar-api-openapi.yml
  format: yaml
  label: AlphaAI Calendar API
  slug: alphaai-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaai/openapi/alphaai-calendar-api-openapi.yml
- filename: alphaai-news-api-openapi.yml
  format: yaml
  label: AlphaAI News API
  slug: alphaai-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaai/openapi/alphaai-news-api-openapi.yml
- filename: alphaai-symbols-api-openapi.yml
  format: yaml
  label: AlphaAI Symbols API
  slug: alphaai-symbols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaai/openapi/alphaai-symbols-api-openapi.yml
- filename: alphaai-coverage-api-openapi.yml
  format: yaml
  label: AlphaAI Coverage API
  slug: alphaai-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaai/openapi/alphaai-coverage-api-openapi.yml
- filename: alphaai-radar-api-openapi.yml
  format: yaml
  label: AlphaAI Radar API
  slug: alphaai-radar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaai/openapi/alphaai-radar-api-openapi.yml
- filename: alphaai-stories-api-openapi.yml
  format: yaml
  label: AlphaAI Stories API
  slug: alphaai-stories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphaai/openapi/alphaai-stories-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: email, full name, and (if provided) a profile avatar.'
  - category: financial
    text: 'Payment data: handled entirely by Stripe — we never store card details, only your Stripe customer and subscription IDs.'
  - category: device
    text: 'Technical data: IP address, browser and device information, and server logs.'
  - category: contact
    text: 'Sales inquiries: if you submit the /contact form, we keep your name, email, use case, expected volume, and referral source to respond.'
  deletion:
    route: email info@alphai.io
    text: To exercise any of these, email info@alphai.io with the subject "Data Protection Request"; we respond within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account management and authentication
    text: Create and manage your account and authenticate access.
  - purpose: News and developer access
    text: Provide AI-curated financial news and developer access (REST API, MCP server).
  - purpose: Subscriptions and payments
    text: Process subscriptions and payments via Stripe.
  retention:
  - period: 30 days
    scope: Account data
    text: 'Account data: kept while your account is active; deleted within 30 days of a deletion request (aggregated, non-identifying analytics may remain).'
  - period: about 90 days
    scope: API and MCP request logs
    text: 'API and MCP request logs: about 90 days.'
  - period: up to 12 months
    scope: Technical logs
    text: 'Technical logs: up to 12 months.'
  - period: 7 years
    scope: Payment data
    text: 'Payment data: retained as required by financial law (typically 7 years).'
  rights:
  - right: Access, rectify, erase, restrict, port
    text: You have the right to access, rectify, erase, restrict, or port your data, to object to processing based on legitimate interests, and to withdraw consent at any time.
  - right: Lodge a complaint
    text: You may also lodge a complaint with the Bulgarian Commission for Personal Data Protection (cpdp.bg) or your local supervisory authority.
  role:
    text: We act as the data controller under the GDPR and applicable Bulgarian law.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'We share data only with providers needed to run the Service:'
    url: null
  transfers:
  - mechanism: SCC
    text: Where data is processed outside the European Economic Area (EEA), we rely on appropriate safeguards — Standard Contractual Clauses or European Commission adequacy decisions.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AlphaAI
provenance_date: '2026-11-09'
provider_name: AlphaAI
provider_slug: alphaai
slug: alphaai-privacy-policy
source_date: '2026-11-09'
source_filename: alphaai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://alphai.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AlphaAI\naid: alphaai\nurl: https://alphai.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We act as the data controller under the GDPR and applicable Bulgarian law.\ndata_categories:\n- category: identifying\n  text: 'Account data: email, full name, and (if provided) a profile avatar.'\n- category: financial\n  text: 'Payment data: handled entirely by Stripe — we never store card details, only your Stripe customer and subscription\n    IDs.'\n- category: device\n  text: 'Technical data: IP address, browser and device information, and server logs.'\n- category: contact\n  text: 'Sales\
  \ inquiries: if you submit the /contact form, we keep your name, email, use case, expected volume,\n    and referral source to respond.'\npurposes:\n- purpose: Account management and authentication\n  text: Create and manage your account and authenticate access.\n- purpose: News and developer access\n  text: Provide AI-curated financial news and developer access (REST API, MCP server).\n- purpose: Subscriptions and payments\n  text: Process subscriptions and payments via Stripe.\nretention:\n- scope: Account data\n  period: 30 days\n  text: 'Account data: kept while your account is active; deleted within 30 days of a deletion request (aggregated,\n    non-identifying analytics may remain).'\n- scope: API and MCP request logs\n  period: about 90 days\n  text: 'API and MCP request logs: about 90 days.'\n- scope: Technical logs\n  period: up to 12 months\n  text: 'Technical logs: up to 12 months.'\n- scope: Payment data\n  period: 7 years\n  text: 'Payment data: retained as required by financial\
  \ law (typically 7 years).'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where data is processed outside the European Economic Area (EEA), we rely on appropriate safeguards — Standard\n    Contractual Clauses or European Commission adequacy decisions.\nsubprocessors:\n  url: null\n  text: 'We share data only with providers needed to run the Service:'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email info@alphai.io\n  text: To exercise any of these, email info@alphai.io with the subject \"Data Protection Request\"; we respond within\n    30 days.\nrights:\n- right: Access, rectify, erase, restrict, port\n  text: You have the right to access, rectify, erase, restrict, or port your data, to object to processing based\n    on legitimate interests, and to withdraw consent at any time.\n- right: Lodge a complaint\n  text: You may also lodge a complaint with the Bulgarian Commission for Personal Data Protection (cpdp.bg) or your\n    local supervisory authority.\n\
  sale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/alphaai/privacy/alphaai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 17 quoted statements, read from AlphaAI's own page on 2026-11-09.
synthetic: false
tags:
- Financial News
- Stock Market
- SEC Filings
- Insider Trading
- Fintech
- Market Data
- Sentiment
- AI Agents
- MCP
- LLM
- Trading
---
