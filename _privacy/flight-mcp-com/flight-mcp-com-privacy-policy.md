---
api_specs:
- filename: flight-mcp-com-flights-api-openapi.yml
  format: yaml
  label: flight-mcp-com Flights API
  slug: flight-mcp-com-flights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flight-mcp-com/openapi/flight-mcp-com-flights-api-openapi.yml
- filename: flight-mcp-com-healthz-api-openapi.yml
  format: yaml
  label: flight-mcp-com Healthz API
  slug: flight-mcp-com-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flight-mcp-com/openapi/flight-mcp-com-healthz-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Google account identifier, name, email address, profile image, and account/session records required by Better Auth.
  - category: financial
    text: If paid plans are enabled, Stripe customer and subscription identifiers, plan, status, and billing-period dates.
  - category: behavioral
    text: Google Analytics receives page URLs, referrer, device and browser information, approximate location, and product interaction events.
  - category: communication
    text: Privacy requests can be sent to support@flight-mcp.com .
  deletion:
    route: contact support from the Google email associated with the account
    text: You may request access, correction, export, or deletion of account data by contacting support from the Google email associated with the account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authenticate accounts
    text: authenticate accounts and protect the dashboard
  - purpose: search and return flight offers
    text: search, normalize, cache, and return flight offers
  - purpose: manage subscriptions
    text: manage subscriptions when paid billing is enabled
  - purpose: website analytics with consent
    text: measure website traffic and product activation when analytics consent is granted
  retention:
  - period: while the account is active
    scope: account and entitlement records
    text: Account and entitlement records are retained while the account is active and as needed for security, dispute, tax, or legal obligations.
  - period: 30 days
    scope: authenticated API request and response logs
    text: Authenticated API request and response logs expire after 30 days.
  - period: up to three days
    scope: cached flight results
    text: Cached flight results expire according to the requested TTL and provider policy, up to three days.
  - period: up to 30 days
    scope: signup attribution cookie
    text: we may store a signed first-party cookie for up to 30 days
  rights:
  - right: access, correction, export, or deletion
    text: You may request access, correction, export, or deletion of account data by contacting support from the Google email associated with the account.
  - right: withdraw analytics consent
    text: You can withdraw or change that choice at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or use flight queries for targeted advertising.
  subprocessors:
    text: Flight MCP uses Cloudflare for hosting, networking, Containers, D1, and security; Upstash for Redis; Google for account authentication and consent-based Google Analytics; Stripe for paid billing when enabled; and Decodo as the configured network proxy for provider requests.
    url: null
  transfers:
  - mechanism: other
    text: These providers may process data in countries outside your residence under their own data-protection terms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: flight-mcp-com
provenance_date: '2026-11-09'
provider_name: flight-mcp-com
provider_slug: flight-mcp-com
slug: flight-mcp-com-privacy-policy
source_date: '2026-11-09'
source_filename: flight-mcp-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://flight-mcp.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: flight-mcp-com\naid: flight-mcp-com\nurl: https://flight-mcp.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Google account identifier, name, email address, profile image, and account/session records required by Better\n    Auth.\n- category: financial\n  text: If paid plans are enabled, Stripe customer and subscription identifiers, plan, status, and billing-period\n    dates.\n- category: behavioral\n  text: Google Analytics receives page URLs, referrer, device and browser information, approximate location, and\n    product\
  \ interaction events.\n- category: communication\n  text: Privacy requests can be sent to support@flight-mcp.com .\npurposes:\n- purpose: authenticate accounts\n  text: authenticate accounts and protect the dashboard\n- purpose: search and return flight offers\n  text: search, normalize, cache, and return flight offers\n- purpose: manage subscriptions\n  text: manage subscriptions when paid billing is enabled\n- purpose: website analytics with consent\n  text: measure website traffic and product activation when analytics consent is granted\nretention:\n- scope: account and entitlement records\n  period: while the account is active\n  text: Account and entitlement records are retained while the account is active and as needed for security, dispute,\n    tax, or legal obligations.\n- scope: authenticated API request and response logs\n  period: 30 days\n  text: Authenticated API request and response logs expire after 30 days.\n- scope: cached flight results\n  period: up to three days\n\
  \  text: Cached flight results expire according to the requested TTL and provider policy, up to three days.\n- scope: signup attribution cookie\n  period: up to 30 days\n  text: we may store a signed first-party cookie for up to 30 days\nresidency: []\ntransfers:\n- mechanism: other\n  text: These providers may process data in countries outside your residence under their own data-protection terms.\nsubprocessors:\n  url: null\n  text: Flight MCP uses Cloudflare for hosting, networking, Containers, D1, and security; Upstash for Redis; Google\n    for account authentication and consent-based Google Analytics; Stripe for paid billing when enabled; and Decodo\n    as the configured network proxy for provider requests.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact support from the Google email associated with the account\n  text: You may request access, correction, export, or deletion of account data by contacting support from the Google\n    email associated\
  \ with the account.\nrights:\n- right: access, correction, export, or deletion\n  text: You may request access, correction, export, or deletion of account data by contacting support from the Google\n    email associated with the account.\n- right: withdraw analytics consent\n  text: You can withdraw or change that choice at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or use flight queries for targeted advertising.\n"
source_yaml_url: https://artifacts.apis.io/flight-mcp-com/privacy/flight-mcp-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from flight-mcp-com's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- Flights
- MCP
- Search
---
