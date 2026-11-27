---
api_specs:
- filename: factline-dev-free-api-openapi.yml
  format: yaml
  label: factline-dev Free API
  slug: factline-dev-free-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/factline-dev/openapi/factline-dev-free-api-openapi.yml
- filename: factline-dev-paid-x402-api-openapi.yml
  format: yaml
  label: factline-dev Paid (x402) API
  slug: factline-dev-paid-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/factline-dev/openapi/factline-dev-paid-x402-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'API key holders: name, email, company and use case you enter, and usage per month'
  - category: contact
    text: Emails you send us (hello@, support@, check@) and our replies
  - category: financial
    text: 'x402 payments: transaction hash, paying wallet, amount, country of the request'
  - category: location
    text: A hashed IP address (one-way, truncated)
  - category: device
    text: 'Page views (cookieless Cloudflare Web Analytics: page, referrer, country, browser)'
  - category: behavioral
    text: Request counts per endpoint and per AI client name (for example claude-ai, cursor)
  - category: communication
    text: 'Watches: the names, companies or plates you watch, your email or webhook, and alert history'
  deletion:
    route: Email hello@factline.dev, or delete client files and stop watches through the API
    text: 'Access, correction or deletion: email hello@factline.dev; we answer within 30 days, within legal retention limits (payment records).'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run requested checks
    text: To run the check you asked for
  - purpose: Issue API key, quota and service emails
    text: Issuing the key, quota, service emails (welcome, usage, monthly screening log)
  - purpose: Sanctions and PEP screening
    text: To answer PEP screening we keep an extract of public Wikidata data on politically exposed persons in their public role
  - purpose: Usage statistics and capacity
    text: Knowing which pages are used
  - purpose: Bookkeeping
    text: Bookkeeping and statements
  retention:
  - period: 7 days
    scope: Tool and API inputs
    text: company lookups and reports 7 days
  - period: 7 years
    scope: Receipts
    text: Receipts keep a hash of the answer, the route, the time and the payer (wallet or key id), not the input or the answer itself, for 7 years (bookkeeping).
  - period: null
    scope: Hashed IP address
    text: A hashed IP address (one-way, truncated)
  - period: null
    scope: Watches
    text: Until you stop the watch (link in every email) or it expires
  - period: 12 months
    scope: Supplier onboarding links
    text: 12 months; unused links 60 days
  - period: 7 years
    scope: x402 payment records
    text: Bookkeeping and statements 7 years (Dutch tax law)
  rights:
  - right: Access, correction or deletion
    text: 'Access, correction or deletion: email hello@factline.dev; we answer within 30 days'
  - right: Object to legitimate-interest processing
    text: You can object to processing based on legitimate interest
  - right: Complain to supervisory authority
    text: complain to the Dutch data protection authority (Autoriteit Persoonsgegevens)
  - right: Unsubscribe from service emails
    text: Every service email has an unsubscribe link
  role:
    text: Factline (factline.dev) is the controller for the data below.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent data and do not use it for advertising.
  subprocessors:
    text: 'Service providers : Cloudflare (hosting, database, analytics), Resend (sending email), Google (our mailbox), Dodo Payments (merchant of record for card and iDEAL payments; we receive the status and what was bought, not your card details), Coinbase and other x402 facilitators (settling USDC payments on Base or Solana). No one else.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: factline-dev
provenance_date: '2026-11-09'
provider_name: factline-dev
provider_slug: factline-dev
slug: factline-dev-privacy-policy
source_date: '2026-11-09'
source_filename: factline-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://factline.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: factline-dev\naid: factline-dev\nurl: https://factline.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Factline (factline.dev) is the controller for the data below.\ndata_categories:\n- category: identifying\n  text: 'API key holders: name, email, company and use case you enter, and usage per month'\n- category: contact\n  text: Emails you send us (hello@, support@, check@) and our replies\n- category: financial\n  text: 'x402 payments: transaction hash, paying wallet, amount, country of the request'\n- category: location\n  text: A hashed IP address (one-way, truncated)\n- category:\
  \ device\n  text: 'Page views (cookieless Cloudflare Web Analytics: page, referrer, country, browser)'\n- category: behavioral\n  text: Request counts per endpoint and per AI client name (for example claude-ai, cursor)\n- category: communication\n  text: 'Watches: the names, companies or plates you watch, your email or webhook, and alert history'\npurposes:\n- purpose: Run requested checks\n  text: To run the check you asked for\n- purpose: Issue API key, quota and service emails\n  text: Issuing the key, quota, service emails (welcome, usage, monthly screening log)\n- purpose: Sanctions and PEP screening\n  text: To answer PEP screening we keep an extract of public Wikidata data on politically exposed persons in their\n    public role\n- purpose: Usage statistics and capacity\n  text: Knowing which pages are used\n- purpose: Bookkeeping\n  text: Bookkeeping and statements\nretention:\n- scope: Tool and API inputs\n  period: 7 days\n  text: company lookups and reports 7 days\n- scope:\
  \ Receipts\n  period: 7 years\n  text: Receipts keep a hash of the answer, the route, the time and the payer (wallet or key id), not the input\n    or the answer itself, for 7 years (bookkeeping).\n- scope: Hashed IP address\n  period: null\n  text: A hashed IP address (one-way, truncated)\n- scope: Watches\n  period: null\n  text: Until you stop the watch (link in every email) or it expires\n- scope: Supplier onboarding links\n  period: 12 months\n  text: 12 months; unused links 60 days\n- scope: x402 payment records\n  period: 7 years\n  text: Bookkeeping and statements 7 years (Dutch tax law)\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Service providers : Cloudflare (hosting, database, analytics), Resend (sending email), Google (our mailbox),\n    Dodo Payments (merchant of record for card and iDEAL payments; we receive the status and what was bought, not\n    your card details), Coinbase and other x402 facilitators (settling USDC payments on Base or Solana).\
  \ No one\n    else.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email hello@factline.dev, or delete client files and stop watches through the API\n  text: 'Access, correction or deletion: email hello@factline.dev; we answer within 30 days, within legal retention\n    limits (payment records).'\nrights:\n- right: Access, correction or deletion\n  text: 'Access, correction or deletion: email hello@factline.dev; we answer within 30 days'\n- right: Object to legitimate-interest processing\n  text: You can object to processing based on legitimate interest\n- right: Complain to supervisory authority\n  text: complain to the Dutch data protection authority (Autoriteit Persoonsgegevens)\n- right: Unsubscribe from service emails\n  text: Every service email has an unsubscribe link\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent data and do not use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/factline-dev/privacy/factline-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from factline-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Compliance
- KYB
---
