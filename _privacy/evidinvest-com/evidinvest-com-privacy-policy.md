---
api_specs:
- filename: evidinvest-com-calculations-api-openapi.yml
  format: yaml
  label: evidinvest-com Calculations API
  slug: evidinvest-com-calculations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidinvest-com/openapi/evidinvest-com-calculations-api-openapi.yml
- filename: evidinvest-com-financial-data-api-openapi.yml
  format: yaml
  label: evidinvest-com Financial Data API
  slug: evidinvest-com-financial-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidinvest-com/openapi/evidinvest-com-financial-data-api-openapi.yml
- filename: evidinvest-com-machine-payments-api-openapi.yml
  format: yaml
  label: evidinvest-com Machine Payments API
  slug: evidinvest-com-machine-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidinvest-com/openapi/evidinvest-com-machine-payments-api-openapi.yml
- filename: evidinvest-com-market-data-api-openapi.yml
  format: yaml
  label: evidinvest-com Market Data API
  slug: evidinvest-com-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidinvest-com/openapi/evidinvest-com-market-data-api-openapi.yml
- filename: evidinvest-com-portfolio-api-openapi.yml
  format: yaml
  label: evidinvest-com Portfolio API
  slug: evidinvest-com-portfolio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidinvest-com/openapi/evidinvest-com-portfolio-api-openapi.yml
- filename: evidinvest-com-sec-filings-api-openapi.yml
  format: yaml
  label: evidinvest-com SEC Filings API
  slug: evidinvest-com-sec-filings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidinvest-com/openapi/evidinvest-com-sec-filings-api-openapi.yml
- filename: evidinvest-com-user-lists-api-openapi.yml
  format: yaml
  label: evidinvest-com User Lists API
  slug: evidinvest-com-user-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidinvest-com/openapi/evidinvest-com-user-lists-api-openapi.yml
- filename: evidinvest-com-valuation-api-openapi.yml
  format: yaml
  label: evidinvest-com Valuation API
  slug: evidinvest-com-valuation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evidinvest-com/openapi/evidinvest-com-valuation-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information — your email address, your name if you give one, and which sign-in method you used.
  - category: financial
    text: Credit ledger — the credits you bought or were granted and the credits you spent.
  - category: financial
    text: Payment information — card details are collected and processed directly by Stripe and never reach our servers.
  - category: device
    text: 'Usage logs — one record per API or MCP call: the tool called, the timestamp, which API key or connection made the call, the response status and latency, the IP address and user agent the call came from, and any error message.'
  - category: behavioral
    text: First-touch attribution — the UTM parameters and landing page from the visit on which you first arrived, so we can tell which marketing works.
  - category: communication
    text: Email preferences — your settings for the newsletter, feature updates, tips, and system update emails.
  deletion:
    route: Email info@evidinvest.com from your account address
    text: To access, export, or delete your account and its data, email info@evidinvest.com from your account address
  dpa:
    available: true
    text: each under a data processing agreement
    url: null
  purposes:
  - purpose: Providing platform, API and MCP server
    text: Providing the platform, API, and MCP server to you; authentication
  - purpose: Payments and invoicing
    text: Taking payment, metering credits, issuing invoices
  - purpose: Security and fraud prevention
    text: Security, rate limiting, abuse and fraud prevention
  - purpose: Debugging and product improvement
    text: Debugging, measuring, and improving the product
  - purpose: Advertising measurement
    text: Advertising and analytics cookies in the EEA, UK, and Switzerland
  residency:
  - region: US and EU
    text: Vercel Website and app hosting, edge delivery, aggregate traffic analytics EU / US
  - region: US (us-east-1)
    text: Amazon Web Services Application database and the API / MCP gateway US (us-east-1)
  retention:
  - period: within 30 days
    scope: Account data, saved work, keys, and connections
    text: kept until you delete them or close your account, then deleted within 30 days.
  - period: seven years
    scope: Invoices and accounting records
    text: Invoices and accounting records — kept for seven years, as the Swedish Bookkeeping Act (bokföringslagen) requires.
  - period: within 24 hours
    scope: MCP activation key
    text: is erased when you claim it or within 24 hours, whichever comes first.
  rights:
  - right: Access
    text: Access the personal data we hold about you
  - right: Correct
    text: Correct inaccurate or incomplete data
  - right: Delete
    text: Delete your personal data ("right to be forgotten")
  - right: Export
    text: Export your data in a portable format
  - right: Object or restrict
    text: Object to or restrict processing based on our legitimate interests
  - right: Withdraw consent
    text: Withdraw consent at any time, without affecting processing already carried out
  role:
    text: We are the data controller for the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: Provider What it does for us Where it processes Vercel Website and app hosting, edge delivery, aggregate traffic analytics EU / US Amazon Web Services Application database and the API / MCP gateway US (us-east-1) Clerk Authentication and account management US Stripe Payments, invoicing, tax EU / US Upstash Redis cache and rate-limit counters EU / US Resend, Amazon SES Transactional and newsletter email delivery EU / US Anthropic, and OpenAI on failover
    url: null
  transfers:
  - mechanism: SCC
    text: Those transfers rely on the European Commission's Standard Contractual Clauses
  - mechanism: DPF
    text: and where applicable the EU–US Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: evidinvest-com
provenance_date: '2026-11-09'
provider_name: evidinvest-com
provider_slug: evidinvest-com
slug: evidinvest-com-privacy-policy
source_date: '2026-11-09'
source_filename: evidinvest-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://evidinvest.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: evidinvest-com\naid: evidinvest-com\nurl: https://evidinvest.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the data controller for the personal data described here.\ndata_categories:\n- category: identifying\n  text: Account information — your email address, your name if you give one, and which sign-in method you used.\n- category: financial\n  text: Credit ledger — the credits you bought or were granted and the credits you spent.\n- category: financial\n  text: Payment information — card details are collected and processed directly by Stripe and never reach our\
  \ servers.\n- category: device\n  text: 'Usage logs — one record per API or MCP call: the tool called, the timestamp, which API key or connection\n    made the call, the response status and latency, the IP address and user agent the call came from, and any error\n    message.'\n- category: behavioral\n  text: First-touch attribution — the UTM parameters and landing page from the visit on which you first arrived,\n    so we can tell which marketing works.\n- category: communication\n  text: Email preferences — your settings for the newsletter, feature updates, tips, and system update emails.\npurposes:\n- purpose: Providing platform, API and MCP server\n  text: Providing the platform, API, and MCP server to you; authentication\n- purpose: Payments and invoicing\n  text: Taking payment, metering credits, issuing invoices\n- purpose: Security and fraud prevention\n  text: Security, rate limiting, abuse and fraud prevention\n- purpose: Debugging and product improvement\n  text: Debugging,\
  \ measuring, and improving the product\n- purpose: Advertising measurement\n  text: Advertising and analytics cookies in the EEA, UK, and Switzerland\nretention:\n- scope: Account data, saved work, keys, and connections\n  period: within 30 days\n  text: kept until you delete them or close your account, then deleted within 30 days.\n- scope: Invoices and accounting records\n  period: seven years\n  text: Invoices and accounting records — kept for seven years, as the Swedish Bookkeeping Act (bokföringslagen)\n    requires.\n- scope: MCP activation key\n  period: within 24 hours\n  text: is erased when you claim it or within 24 hours, whichever comes first.\nresidency:\n- region: US and EU\n  text: Vercel Website and app hosting, edge delivery, aggregate traffic analytics EU / US\n- region: US (us-east-1)\n  text: Amazon Web Services Application database and the API / MCP gateway US (us-east-1)\ntransfers:\n- mechanism: SCC\n  text: Those transfers rely on the European Commission's Standard\
  \ Contractual Clauses\n- mechanism: DPF\n  text: and where applicable the EU–US Data Privacy Framework\nsubprocessors:\n  url: null\n  text: Provider What it does for us Where it processes Vercel Website and app hosting, edge delivery, aggregate\n    traffic analytics EU / US Amazon Web Services Application database and the API / MCP gateway US (us-east-1)\n    Clerk Authentication and account management US Stripe Payments, invoicing, tax EU / US Upstash Redis cache and\n    rate-limit counters EU / US Resend, Amazon SES Transactional and newsletter email delivery EU / US Anthropic,\n    and OpenAI on failover\ndpa:\n  available: true\n  url: null\n  text: each under a data processing agreement\ndeletion:\n  route: Email info@evidinvest.com from your account address\n  text: To access, export, or delete your account and its data, email info@evidinvest.com from your account address\nrights:\n- right: Access\n  text: Access the personal data we hold about you\n- right: Correct\n  text: Correct\
  \ inaccurate or incomplete data\n- right: Delete\n  text: Delete your personal data (\"right to be forgotten\")\n- right: Export\n  text: Export your data in a portable format\n- right: Object or restrict\n  text: Object to or restrict processing based on our legitimate interests\n- right: Withdraw consent\n  text: Withdraw consent at any time, without affecting processing already carried out\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/evidinvest-com/privacy/evidinvest-com-privacy-policy.yml
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
summary_line: 29 quoted statements, read from evidinvest-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Valuation
- Data
---
