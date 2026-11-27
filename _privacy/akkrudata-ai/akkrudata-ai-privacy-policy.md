---
api_specs:
- filename: akkrudata-ai-openapi-generated.yml
  format: yaml
  label: AkkruData API
  slug: akkrudata-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/akkrudata-ai/openapi/_ae-authored/akkrudata-ai-openapi-generated.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information you provide: email address, password (stored only as a salted hash), and any profile data you supply.'
  - category: contact
    text: 'Contact form: when you write to us through the Contact Sales form, we collect your name, work email, company, how you heard about us, your message, and the IP address it was sent from.'
  - category: financial
    text: 'Payment information when you purchase a plan or credit pack: handled by Stripe, Inc. as our payment processor.'
  - category: device
    text: 'Technical metadata necessary to operate the Service: IP address (used to rate-limit, prevent abuse, and detect suspicious activity), browser user-agent, and request timestamps.'
  - category: behavioral
    text: 'API and tool usage logs: which endpoint or MCP tool was called, the channel (API key, MCP, CLI, or web app), the API key name used (never the key value), credits charged, and a UTC timestamp.'
  deletion:
    route: delete your account from the dashboard, or email the privacy contact
    text: delete your account at any time
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate, authenticate, secure, bill, and improve the Service
    text: We use this information to operate, authenticate, secure, bill, and improve the Service
  - purpose: advertising measurement
    text: If you accept advertising cookies, Google Ads measures whether our advertising led to a sign-up, under Google's privacy policy.
  residency:
  - region: United States
    text: The Service is hosted on infrastructure located in the United States.
  retention:
  - period: until you delete your account
    scope: account data
    text: Account data (email, profile, hashed password, OAuth links) — until you delete your account.
  - period: 90 days
    scope: API and tool usage logs
    text: These rows are retained for 90 days, then automatically deleted.
  - period: 90 days
    scope: contact form
    text: delete them after 90 days
  - period: typically 7 years in the United States
    scope: payment and billing records
    text: Payment and billing records — as required by tax and accounting law (typically 7 years in the United States).
  - period: 90 days
    scope: security event logs
    text: Security event logs (including IP addresses) — 90 days, then automatically deleted.
  rights:
  - right: access, correction, deletion, portability, restriction
    text: To exercise rights to access, correction, deletion, portability, or restriction under applicable law (including the California Consumer Privacy Act), email [email protected] .
  - right: view and update profile
    text: You can view and update your profile from the dashboard, generate or revoke API keys, view your 90-day usage history, and delete your account at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: If you access the Service from another country, you consent to your information being transferred to and processed in the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AkkruData
provenance_date: '2026-11-09'
provider_name: AkkruData
provider_slug: akkrudata-ai
slug: akkrudata-ai-privacy-policy
source_date: '2026-11-09'
source_filename: akkrudata-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.akkrudata.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AkkruData\naid: akkrudata-ai\nurl: https://www.akkrudata.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account information you provide: email address, password (stored only as a salted hash), and any profile\n    data you supply.'\n- category: contact\n  text: 'Contact form: when you write to us through the Contact Sales form, we collect your name, work email, company,\n    how you heard about us, your message, and the IP address it was sent from.'\n- category: financial\n  text: 'Payment information when you purchase a plan\
  \ or credit pack: handled by Stripe, Inc. as our payment processor.'\n- category: device\n  text: 'Technical metadata necessary to operate the Service: IP address (used to rate-limit, prevent abuse, and\n    detect suspicious activity), browser user-agent, and request timestamps.'\n- category: behavioral\n  text: 'API and tool usage logs: which endpoint or MCP tool was called, the channel (API key, MCP, CLI, or web\n    app), the API key name used (never the key value), credits charged, and a UTC timestamp.'\npurposes:\n- purpose: operate, authenticate, secure, bill, and improve the Service\n  text: We use this information to operate, authenticate, secure, bill, and improve the Service\n- purpose: advertising measurement\n  text: If you accept advertising cookies, Google Ads measures whether our advertising led to a sign-up, under Google's\n    privacy policy.\nretention:\n- scope: account data\n  period: until you delete your account\n  text: Account data (email, profile, hashed password,\
  \ OAuth links) — until you delete your account.\n- scope: API and tool usage logs\n  period: 90 days\n  text: These rows are retained for 90 days, then automatically deleted.\n- scope: contact form\n  period: 90 days\n  text: delete them after 90 days\n- scope: payment and billing records\n  period: typically 7 years in the United States\n  text: Payment and billing records — as required by tax and accounting law (typically 7 years in the United States).\n- scope: security event logs\n  period: 90 days\n  text: Security event logs (including IP addresses) — 90 days, then automatically deleted.\nresidency:\n- region: United States\n  text: The Service is hosted on infrastructure located in the United States.\ntransfers:\n- mechanism: other\n  text: If you access the Service from another country, you consent to your information being transferred to and\n    processed in the United States.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n\
  \  route: delete your account from the dashboard, or email the privacy contact\n  text: delete your account at any time\nrights:\n- right: access, correction, deletion, portability, restriction\n  text: To exercise rights to access, correction, deletion, portability, or restriction under applicable law (including\n    the California Consumer Privacy Act), email [email protected] .\n- right: view and update profile\n  text: You can view and update your profile from the dashboard, generate or revoke API keys, view your 90-day usage\n    history, and delete your account at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal information.\n"
source_yaml_url: https://artifacts.apis.io/akkrudata-ai/privacy/akkrudata-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from AkkruData's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Data
- Artificial Intelligence
- Filings
---
