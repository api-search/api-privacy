---
api_specs:
- filename: chathome-lu-agent-api-openapi.yml
  format: yaml
  label: ChatHome Protected Agent API
  slug: protected-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chathome-lu/openapi/chathome-lu-agent-api-openapi.yml
- filename: chathome-lu-agents-api-openapi.yml
  format: yaml
  label: ChatHome Agents API
  slug: chathome-lu-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chathome-lu/openapi/chathome-lu-agents-api-openapi.yml
- filename: chathome-lu-listings-api-openapi.yml
  format: yaml
  label: ChatHome Listings API
  slug: chathome-lu-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chathome-lu/openapi/chathome-lu-listings-api-openapi.yml
- filename: chathome-lu-market-data-api-openapi.yml
  format: yaml
  label: ChatHome Market data API
  slug: chathome-lu-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chathome-lu/openapi/chathome-lu-market-data-api-openapi.yml
- filename: chathome-lu-search-api-openapi.yml
  format: yaml
  label: ChatHome Search API
  slug: chathome-lu-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chathome-lu/openapi/chathome-lu-search-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: When you request a tool result or save a tool request, we collect your email, optional phone number, tool name, language, submission time and separate marketing choice.
  - category: behavioral
    text: page views, session duration, feature usage events
  - category: behavioral
    text: search history, saved listings, vibe profile
  - category: financial
    text: We save your rate, down payment, daily place, travel mode, household and offers to personalise costs, nearby places and travel on every home
  - category: device
    text: session tokens, authentication state, language preference, security cookies
  - category: communication
    text: Inquiry messages and any contact name or email you provide are stored and shared with the relevant chathome listing owner or agent.
  deletion:
    route: email request to hello@chathome.lu
    text: Contact hello@chathome.lu to request access, correction or deletion.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: personalise recommendations
    text: used to tailor AI recommendations
  - purpose: search quality, reliability and abuse prevention
    text: a monthly rotating pseudonym for search quality, reliability, and abuse prevention
  - purpose: email search alerts
    text: We send alerts only after your explicit consent (GDPR Art. 6(1)(a))
  retention:
  - period: 13 months
    scope: analytics event data
    text: Analytics event data is retained for a maximum of 13 months.
  - period: on logout
    scope: session data
    text: Session data is deleted on logout.
  - period: 30 days
    scope: pseudonymous search-operation records
    text: Pseudonymous search-operation records are automatically deleted after 30 days.
  - period: 30 days
    scope: account-free alert wording
    text: For an account-free alert, we may keep the wording you typed for up to 30 days
  - period: 90 days
    scope: MCP security audit records
    text: MCP security audit records are automatically deleted after 90 days.
  - period: null
    scope: lease analyses and inquiry conversations
    text: Lease analyses and inquiry conversations are retained while your account is active or until you request erasure.
  rights:
  - right: access, rectify, erase, restrict, port
    text: Under GDPR, you have the right to access, rectify, erase, restrict, and port your personal data.
  - right: withdraw consent
    text: You may also withdraw consent at any time via the Cookie Settings link in the footer.
  - right: complaint to CNPD
    text: You have the right to lodge a complaint with the CNPD
  role:
    text: 'AnalyticoTech is the data controller (contact: hello@chathome.lu).'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Our processors include Google Cloud/Firestore, Vertex AI, and, where enabled, Firebase Analytics.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ChatHome
provenance_date: '2026-11-09'
provider_name: ChatHome
provider_slug: chathome-lu
slug: chathome-lu-privacy-policy
source_date: '2026-11-09'
source_filename: chathome-lu-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://chathome.lu/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ChatHome\naid: chathome-lu\nurl: https://chathome.lu/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'AnalyticoTech is the data controller (contact: hello@chathome.lu).'\ndata_categories:\n- category: contact\n  text: When you request a tool result or save a tool request, we collect your email, optional phone number, tool\n    name, language, submission time and separate marketing choice.\n- category: behavioral\n  text: page views, session duration, feature usage events\n- category: behavioral\n  text: search history, saved listings, vibe profile\n- category: financial\n  text:\
  \ We save your rate, down payment, daily place, travel mode, household and offers to personalise costs, nearby\n    places and travel on every home\n- category: device\n  text: session tokens, authentication state, language preference, security cookies\n- category: communication\n  text: Inquiry messages and any contact name or email you provide are stored and shared with the relevant chathome\n    listing owner or agent.\npurposes:\n- purpose: personalise recommendations\n  text: used to tailor AI recommendations\n- purpose: search quality, reliability and abuse prevention\n  text: a monthly rotating pseudonym for search quality, reliability, and abuse prevention\n- purpose: email search alerts\n  text: We send alerts only after your explicit consent (GDPR Art. 6(1)(a))\nretention:\n- scope: analytics event data\n  period: 13 months\n  text: Analytics event data is retained for a maximum of 13 months.\n- scope: session data\n  period: on logout\n  text: Session data is deleted on logout.\n\
  - scope: pseudonymous search-operation records\n  period: 30 days\n  text: Pseudonymous search-operation records are automatically deleted after 30 days.\n- scope: account-free alert wording\n  period: 30 days\n  text: For an account-free alert, we may keep the wording you typed for up to 30 days\n- scope: MCP security audit records\n  period: 90 days\n  text: MCP security audit records are automatically deleted after 90 days.\n- scope: lease analyses and inquiry conversations\n  period: null\n  text: Lease analyses and inquiry conversations are retained while your account is active or until you request\n    erasure.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Our processors include Google Cloud/Firestore, Vertex AI, and, where enabled, Firebase Analytics.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to hello@chathome.lu\n  text: Contact hello@chathome.lu to request access, correction or deletion.\nrights:\n- right: access,\
  \ rectify, erase, restrict, port\n  text: Under GDPR, you have the right to access, rectify, erase, restrict, and port your personal data.\n- right: withdraw consent\n  text: You may also withdraw consent at any time via the Cookie Settings link in the footer.\n- right: complaint to CNPD\n  text: You have the right to lodge a complaint with the CNPD\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chathome-lu/privacy/chathome-lu-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 21 quoted statements, read from ChatHome's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Property Search
- Luxembourg
- Housing
- Property Valuation
- AI Agents
- MCP
- A2A
---
