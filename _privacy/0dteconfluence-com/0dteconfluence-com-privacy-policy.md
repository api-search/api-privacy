---
api_specs:
- filename: 0dteconfluence-com-openapi-generated.yml
  format: yaml
  label: 0DTE Confluence API
  slug: 0dteconfluence-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0dteconfluence-com/openapi/_ae-authored/0dteconfluence-com-openapi-generated.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: email address, a salted password hash, login timestamps, session tokens
  - category: financial
    text: We receive your email, customer and subscription identifiers, plan, and subscription status from Stripe — not your full card number.
  - category: contact
    text: if you purchase the SMS alerts add-on (or hold a Lifetime plan) and activate texts, we collect your mobile phone number and your written consent to receive alerts
  - category: device
    text: IP address, user-agent, requested URL, timestamp and response status for requests to our site and API
  - category: financial
    text: SnapTrade returns your positions, account balances and order history (symbol, quantity, price, time, status).
  - category: behavioral
    text: usage data such as pages viewed, device/browser, approximate location and conversion events
  deletion:
    route: email request to privacy contact or Your Privacy Choices page
    text: You can ask us to delete your data sooner (section 11).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide subscription service and alerts
    text: We use the information above to provide the subscription service, authenticate you, deliver alerts, enforce plan limits, respond to support requests
  - purpose: advertising measurement
    text: pay affiliates, measure our marketing, and meet legal obligations
  - purpose: brokerage positions display
    text: to show your own positions next to the Desk and MCP context
  retention:
  - period: up to seven years afterward
    scope: Account, billing and Terms-acceptance records
    text: Account, billing and Terms-acceptance records are kept while your account is open and for up to seven years afterward for tax, dispute and compliance purposes.
  - period: up to 13 months
    scope: MCP usage and server logs
    text: MCP usage and server logs are kept for up to 13 months.
  - period: about 90 seconds
    scope: Brokerage snapshots
    text: brokerage snapshots are cached for about 90 seconds to serve the Desk and MCP and are then discarded or overwritten
  - period: null
    scope: Brokerage connection record
    text: the connection record is kept while the link is active and deleted within 30 days after you disconnect or close your account.
  rights:
  - right: access
    text: You can ask us to access the personal data we hold about you, receive a copy of it, correct inaccuracies, delete it, or opt out of advertising “sharing.”
  - right: object or restrict processing
    text: including rights to object to or restrict certain processing, to appeal a decision, and to complain to a data-protection authority
  role:
    text: Signal Technologies LLC (“we,” “us”) is the data controller for the website signaltechtrading.com
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Google Ads conversion tags and Google Analytics may be considered “sharing” of personal information for cross-context behavioral advertising under U.S. state privacy laws (identifiers, device and browsing data). You can opt out at any time on Your Privacy Choices
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 0DTE Confluence
provenance_date: '2026-11-09'
provider_name: 0DTE Confluence
provider_slug: 0dteconfluence-com
slug: 0dteconfluence-com-privacy-policy
source_date: '2026-11-09'
source_filename: 0dteconfluence-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://0dteconfluence.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 0DTE Confluence\naid: 0dteconfluence-com\nurl: https://0dteconfluence.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Signal Technologies LLC (“we,” “us”) is the data controller for the website signaltechtrading.com\ndata_categories:\n- category: identifying\n  text: email address, a salted password hash, login timestamps, session tokens\n- category: financial\n  text: We receive your email, customer and subscription identifiers, plan, and subscription status from Stripe\n    — not your full card number.\n- category: contact\n  text: if you purchase the SMS alerts add-on (or hold\
  \ a Lifetime plan) and activate texts, we collect your mobile\n    phone number and your written consent to receive alerts\n- category: device\n  text: IP address, user-agent, requested URL, timestamp and response status for requests to our site and API\n- category: financial\n  text: SnapTrade returns your positions, account balances and order history (symbol, quantity, price, time, status).\n- category: behavioral\n  text: usage data such as pages viewed, device/browser, approximate location and conversion events\npurposes:\n- purpose: provide subscription service and alerts\n  text: We use the information above to provide the subscription service, authenticate you, deliver alerts, enforce\n    plan limits, respond to support requests\n- purpose: advertising measurement\n  text: pay affiliates, measure our marketing, and meet legal obligations\n- purpose: brokerage positions display\n  text: to show your own positions next to the Desk and MCP context\nretention:\n- scope: Account, billing\
  \ and Terms-acceptance records\n  period: up to seven years afterward\n  text: Account, billing and Terms-acceptance records are kept while your account is open and for up to seven years\n    afterward for tax, dispute and compliance purposes.\n- scope: MCP usage and server logs\n  period: up to 13 months\n  text: MCP usage and server logs are kept for up to 13 months.\n- scope: Brokerage snapshots\n  period: about 90 seconds\n  text: brokerage snapshots are cached for about 90 seconds to serve the Desk and MCP and are then discarded or\n    overwritten\n- scope: Brokerage connection record\n  period: null\n  text: the connection record is kept while the link is active and deleted within 30 days after you disconnect or\n    close your account.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to privacy contact or Your Privacy Choices page\n  text: You can ask us to delete your\
  \ data sooner (section 11).\nrights:\n- right: access\n  text: You can ask us to access the personal data we hold about you, receive a copy of it, correct inaccuracies,\n    delete it, or opt out of advertising “sharing.”\n- right: object or restrict processing\n  text: including rights to object to or restrict certain processing, to appeal a decision, and to complain to a\n    data-protection authority\nsale_or_sharing:\n  stance: conditional\n  text: Google Ads conversion tags and Google Analytics may be considered “sharing” of personal information for\n    cross-context behavioral advertising under U.S. state privacy laws (identifiers, device and browsing data).\n    You can opt out at any time on Your Privacy Choices\n"
source_yaml_url: https://artifacts.apis.io/0dteconfluence-com/privacy/0dteconfluence-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from 0DTE Confluence's own page on 2026-11-09.
synthetic: false
tags:
- Trading
- Options
- Market Data
- Analytics
- Finance
- Company
---
