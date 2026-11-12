---
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address
  - category: device
    text: Standard web-server logs (IP address, user agent, requested URL)
  deletion:
    route: Automatic daily job; or open an issue on GitHub for sooner removal
    text: Deletion happens automatically (daily job). To have your demo account removed sooner, open an issue on GitHub
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Delivering sign-in link
    text: Delivering the link you asked for.
  - purpose: Operating OAuth 2.1 flow
    text: Operating the OAuth 2.1 flow
  - purpose: Pseudonymized auditing
    text: Demonstrating pseudonymized auditing (hashed identifiers, no raw email)
  - purpose: Security and operations
    text: Standard web-server logs (IP address, user agent, requested URL) are kept for up to 14 days for security and operations, then rotated away.
  - purpose: Aggregate traffic statistics
    text: Aggregate traffic statistics are derived server-side from those logs
  residency:
  - region: EU
    text: Everything is hosted in the EU.
  retention:
  - period: 14 days
    scope: Web-server logs
    text: Standard web-server logs (IP address, user agent, requested URL) are kept for up to 14 days for security and operations, then rotated away.
  - period: 15 minutes
    scope: Pending sign-in link
    text: Link expires in 15 minutes; the row is deleted within 1 day
  - period: 90 days
    scope: Email address
    text: Deleted after 90 days without sign-in (with all tokens, sessions and consents)
  - period: 7 days
    scope: OAuth artifacts
    text: Expired items removed within 7 days of expiry; all removed with the account
  - period: 90 days
    scope: Gateway audit trail
    text: Gateway audit trail Demonstrating pseudonymized auditing (hashed identifiers, no raw email) 90 days
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No data is sold, shared or used for advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cortex Gateway
provenance_date: '2026-11-09'
provider_name: Cortex Gateway
provider_slug: cortex-gateway-dev
slug: cortex-gateway-dev-privacy-policy
source_date: '2026-11-09'
source_filename: cortex-gateway-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cortex-gateway.dev/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cortex Gateway\naid: cortex-gateway-dev\nurl: https://cortex-gateway.dev/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address\n- category: device\n  text: Standard web-server logs (IP address, user agent, requested URL)\npurposes:\n- purpose: Delivering sign-in link\n  text: Delivering the link you asked for.\n- purpose: Operating OAuth 2.1 flow\n  text: Operating the OAuth 2.1 flow\n- purpose: Pseudonymized auditing\n  text: Demonstrating pseudonymized auditing (hashed identifiers, no raw email)\n- purpose: Security and\
  \ operations\n  text: Standard web-server logs (IP address, user agent, requested URL) are kept for up to 14 days for security\n    and operations, then rotated away.\n- purpose: Aggregate traffic statistics\n  text: Aggregate traffic statistics are derived server-side from those logs\nretention:\n- scope: Web-server logs\n  period: 14 days\n  text: Standard web-server logs (IP address, user agent, requested URL) are kept for up to 14 days for security\n    and operations, then rotated away.\n- scope: Pending sign-in link\n  period: 15 minutes\n  text: Link expires in 15 minutes; the row is deleted within 1 day\n- scope: Email address\n  period: 90 days\n  text: Deleted after 90 days without sign-in (with all tokens, sessions and consents)\n- scope: OAuth artifacts\n  period: 7 days\n  text: Expired items removed within 7 days of expiry; all removed with the account\n- scope: Gateway audit trail\n  period: 90 days\n  text: Gateway audit trail Demonstrating pseudonymized auditing (hashed\
  \ identifiers, no raw email) 90 days\nresidency:\n- region: EU\n  text: Everything is hosted in the EU.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Automatic daily job; or open an issue on GitHub for sooner removal\n  text: Deletion happens automatically (daily job). To have your demo account removed sooner, open an issue on GitHub\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: No data is sold, shared or used for advertising.\n"
source_yaml_url: https://artifacts.apis.io/cortex-gateway-dev/privacy/cortex-gateway-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- sale_or_sharing
summary_line: 15 quoted statements, read from Cortex Gateway's own page on 2026-11-09.
synthetic: false
tags:
- Company
- MCP
- MCP Gateway
- Open Source
- OAuth 2.1
- AI Agents
- Identity
- Authorization
- Self-Hosted
---
