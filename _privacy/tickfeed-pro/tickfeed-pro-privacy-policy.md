---
api_specs:
- filename: tickfeed-pro-account-api-openapi.yml
  format: yaml
  label: tickfeed-pro Account API
  slug: tickfeed-pro-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickfeed-pro/openapi/tickfeed-pro-account-api-openapi.yml
- filename: tickfeed-pro-market-data-api-openapi.yml
  format: yaml
  label: tickfeed-pro market data API
  slug: tickfeed-pro-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickfeed-pro/openapi/tickfeed-pro-market-data-api-openapi.yml
- filename: tickfeed-pro-system-api-openapi.yml
  format: yaml
  label: tickfeed-pro System API
  slug: tickfeed-pro-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickfeed-pro/openapi/tickfeed-pro-system-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address and whether you’ve confirmed it, password (stored only as a one-way scrypt hash, never in readable form), chosen currency, account status, sign-in session records.
  - category: financial
    text: Your balance and its history (top-ups, charges), invoices, and the Stripe customer reference.
  - category: device
    text: Records of failed sign-in attempts for an email address (kept for at most 24 hours). Your IP address is used briefly, in memory, to rate-limit requests and sign-ups; we don’t store it.
  - category: behavioral
    text: 'For each API or MCP request: which key made it, the time, the endpoint path, the result status and response time, and the amount charged.'
  - category: communication
    text: Support tickets you open in your dashboard (subject, category, messages) and our replies, plus any emails you send us.
  deletion:
    route: Email the privacy contact to request erasure
    text: To use any of these rights, email [email protected] from the address on your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Creating and running your account, authenticating requests
    text: Creating and running your account, authenticating requests, providing the data you ask for
  - purpose: Charging, invoicing and refunds
    text: Charging requests to your balance, processing top-ups, issuing invoices, handling refunds
  - purpose: Sending product news and offers
    text: Sending product news and offers (new markets, features and occasional credit offers), only if you opt in when you sign up or in your dashboard.
  - purpose: Understanding which websites bring customers
    text: Understanding which websites and links bring us customers (sign-up source, campaign links you open while signed in, and anonymous page-view counts)
  retention:
  - period: Deleted within 30 days of closure
    scope: Account details and API key records
    text: While your account is open. Deleted within 30 days of closure, except as below.
  - period: 6 years after the end of the financial year they relate to
    scope: Balance history, top-ups, invoices and other financial records
    text: 6 years after the end of the financial year they relate to, as UK tax law requires
  - period: 13 months
    scope: API request logs
    text: API request logs 13 months, then deleted automatically
  - period: 24 hours
    scope: Failed sign-in records
    text: Failed sign-in records 24 hours
  - period: Up to 2 years after the ticket is closed or resolved
    scope: Support tickets and correspondence
    text: Up to 2 years after the ticket is closed or resolved, then deleted automatically
  rights:
  - right: access
    text: access your personal data and get a copy
  - right: correction
    text: correct inaccurate data
  - right: erasure
    text: erase your data, where we no longer need it or have no other lawful reason to keep it
  - right: restriction or objection
    text: restrict or object to processing based on legitimate interests
  - right: portability
    text: receive data you gave us in a machine-readable format
  role:
    text: We are the controller of the personal data described here, under the UK General Data Protection Regulation (UK GDPR) and the Data Protection Act 2018.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell personal data, use it for advertising, or make decisions about you based solely on automated processing
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: the transfer is covered by UK adequacy regulations (including the UK–US data bridge for certified companies)
  - mechanism: other
    text: or by the UK International Data Transfer Agreement or Addendum, as appropriate.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: tickfeed-pro
provenance_date: '2026-11-10'
provider_name: tickfeed-pro
provider_slug: tickfeed-pro
slug: tickfeed-pro-privacy-policy
source_date: '2026-11-10'
source_filename: tickfeed-pro-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tickfeed.pro/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: tickfeed-pro\naid: tickfeed-pro\nurl: https://tickfeed.pro/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the controller of the personal data described here, under the UK General Data Protection Regulation\n    (UK GDPR) and the Data Protection Act 2018.\ndata_categories:\n- category: identifying\n  text: Email address and whether you’ve confirmed it, password (stored only as a one-way scrypt hash, never in\n    readable form), chosen currency, account status, sign-in session records.\n- category: financial\n  text: Your balance and its history (top-ups, charges), invoices,\
  \ and the Stripe customer reference.\n- category: device\n  text: Records of failed sign-in attempts for an email address (kept for at most 24 hours). Your IP address is\n    used briefly, in memory, to rate-limit requests and sign-ups; we don’t store it.\n- category: behavioral\n  text: 'For each API or MCP request: which key made it, the time, the endpoint path, the result status and response\n    time, and the amount charged.'\n- category: communication\n  text: Support tickets you open in your dashboard (subject, category, messages) and our replies, plus any emails\n    you send us.\npurposes:\n- purpose: Creating and running your account, authenticating requests\n  text: Creating and running your account, authenticating requests, providing the data you ask for\n- purpose: Charging, invoicing and refunds\n  text: Charging requests to your balance, processing top-ups, issuing invoices, handling refunds\n- purpose: Sending product news and offers\n  text: Sending product news and offers\
  \ (new markets, features and occasional credit offers), only if you opt in\n    when you sign up or in your dashboard.\n- purpose: Understanding which websites bring customers\n  text: Understanding which websites and links bring us customers (sign-up source, campaign links you open while\n    signed in, and anonymous page-view counts)\nretention:\n- scope: Account details and API key records\n  period: Deleted within 30 days of closure\n  text: While your account is open. Deleted within 30 days of closure, except as below.\n- scope: Balance history, top-ups, invoices and other financial records\n  period: 6 years after the end of the financial year they relate to\n  text: 6 years after the end of the financial year they relate to, as UK tax law requires\n- scope: API request logs\n  period: 13 months\n  text: API request logs 13 months, then deleted automatically\n- scope: Failed sign-in records\n  period: 24 hours\n  text: Failed sign-in records 24 hours\n- scope: Support tickets and\
  \ correspondence\n  period: Up to 2 years after the ticket is closed or resolved\n  text: Up to 2 years after the ticket is closed or resolved, then deleted automatically\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: the transfer is covered by UK adequacy regulations (including the UK–US data bridge for certified companies)\n- mechanism: other\n  text: or by the UK International Data Transfer Agreement or Addendum, as appropriate.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email the privacy contact to request erasure\n  text: To use any of these rights, email [email protected] from the address on your account.\nrights:\n- right: access\n  text: access your personal data and get a copy\n- right: correction\n  text: correct inaccurate data\n- right: erasure\n  text: erase your data, where we no longer need it or have no other lawful reason to keep it\n- right: restriction or objection\n  text: restrict\
  \ or object to processing based on legitimate interests\n- right: portability\n  text: receive data you gave us in a machine-readable format\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell personal data, use it for advertising, or make decisions about you based solely on automated\n    processing\n"
source_yaml_url: https://artifacts.apis.io/tickfeed-pro/privacy/tickfeed-pro-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from tickfeed-pro's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Market Data
- Foreign Exchange
- Gold
- MCP
---
