---
api_specs:
- filename: amazap-com-basics-api-openapi.yml
  format: yaml
  label: Amazap Basics API
  slug: amazap-com-basics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/amazap-com/openapi/amazap-com-basics-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: API keys, L402 macaroons, MCP and OAuth session and client identifiers, account IDs, balance and spend caps, and your email address if you give it to us.
  - category: financial
    text: Lightning invoices, payment hashes and preimages, amounts in sats, timestamps, the BTC/USD rate used, and your Credits ledger (top-ups, purchases, re-credits).
  - category: communication
    text: What you send us by email or through claims and reports (for example, claim_failed_call or report_sku ).
  - category: device
    text: IP address, user agent, request time, pages and endpoints accessed, and error logs.
  - category: contact
    text: Shipping name, address, phone number and email (phone and email may be optional), order details, and the Lightning destination you provide for refunds.
  deletion:
    route: Email privacy@amazap.com to request deletion or account closure
    text: You can ask us to access, correct, or delete your personal information, or close your account, by emailing privacy@amazap.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the Services
    text: 'We use personal information to: provide the Services: open accounts, take top-ups, process purchases, deliver calls, route physical orders, and issue receipts'
  - purpose: run Credits and claims
    text: 'run Credits: track balances, re-credit failed calls, and handle claims'
  - purpose: fraud and security
    text: prevent fraud, abuse, and security incidents, enforce limits, and screen for sanctions
  - purpose: improve the Services
    text: improve the Services using aggregated or de-identified data
  residency:
  - region: United States
    text: we're based in the U.S. and process data there and wherever our providers operate.
  retention:
  - period: 90 days
    scope: Call logs, receipts, Amazap Basics inputs and outputs
    text: Call logs, receipts, and Amazap Basics inputs and outputs 90 days
  - period: 30 days
    scope: Server and security logs
    text: Server and security logs (including IP addresses) 30 days, longer if needed to investigate an incident
  - period: 7 years
    scope: Payment records, Credits ledger, and tax records
    text: Payment records, Credits ledger, and tax records 7 years
  - period: 2 years
    scope: Support messages
    text: Support messages 2 years
  rights:
  - right: access, correct, delete
    text: You can ask us to access, correct, or delete your personal information, or close your account, by emailing privacy@amazap.com.
  - right: portability
    text: 'Your rights: access, rectification, erasure, restriction, portability, objection to processing based on legitimate interests, and withdrawal of consent.'
  - right: opt out of sale or sharing
    text: to opt out of sale or sharing (we don't do either)
  role:
    text: 'Jesse Shrader, doing business as Amazap, 411 Walnut Street #23192, Green Cove Springs, FL 32043 ("Amazap," "we," "us") is responsible for the personal information described here.'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal information and don't share it for cross-context behavioral advertising.
  subprocessors:
    text: 'Lightning payment infrastructure: the node software, payment providers, and encrypted messaging relays we use to send and receive Lightning payments (these may change over time); DigitalOcean: hosting; Resend (email delivery for sign-in and service email): support and service email'
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we rely on safeguards such as the European Commission's Standard Contractual Clauses and the UK Addendum.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Amazap
provenance_date: '2026-11-09'
provider_name: Amazap
provider_slug: amazap-com
slug: amazap-com-privacy-policy
source_date: '2026-11-09'
source_filename: amazap-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://amazap.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Amazap\naid: amazap-com\nurl: https://amazap.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Jesse Shrader, doing business as Amazap, 411 Walnut Street #23192, Green Cove Springs, FL 32043 (\"Amazap,\"\n    \"we,\" \"us\") is responsible for the personal information described here.'\ndata_categories:\n- category: identifying\n  text: API keys, L402 macaroons, MCP and OAuth session and client identifiers, account IDs, balance and spend caps,\n    and your email address if you give it to us.\n- category: financial\n  text: Lightning invoices, payment hashes and preimages, amounts\
  \ in sats, timestamps, the BTC/USD rate used, and\n    your Credits ledger (top-ups, purchases, re-credits).\n- category: communication\n  text: What you send us by email or through claims and reports (for example, claim_failed_call or report_sku ).\n- category: device\n  text: IP address, user agent, request time, pages and endpoints accessed, and error logs.\n- category: contact\n  text: Shipping name, address, phone number and email (phone and email may be optional), order details, and the\n    Lightning destination you provide for refunds.\npurposes:\n- purpose: provide the Services\n  text: 'We use personal information to: provide the Services: open accounts, take top-ups, process purchases, deliver\n    calls, route physical orders, and issue receipts'\n- purpose: run Credits and claims\n  text: 'run Credits: track balances, re-credit failed calls, and handle claims'\n- purpose: fraud and security\n  text: prevent fraud, abuse, and security incidents, enforce limits, and screen for\
  \ sanctions\n- purpose: improve the Services\n  text: improve the Services using aggregated or de-identified data\nretention:\n- scope: Call logs, receipts, Amazap Basics inputs and outputs\n  period: 90 days\n  text: Call logs, receipts, and Amazap Basics inputs and outputs 90 days\n- scope: Server and security logs\n  period: 30 days\n  text: Server and security logs (including IP addresses) 30 days, longer if needed to investigate an incident\n- scope: Payment records, Credits ledger, and tax records\n  period: 7 years\n  text: Payment records, Credits ledger, and tax records 7 years\n- scope: Support messages\n  period: 2 years\n  text: Support messages 2 years\nresidency:\n- region: United States\n  text: we're based in the U.S. and process data there and wherever our providers operate.\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on safeguards such as the European Commission's Standard Contractual Clauses and\n    the UK Addendum.\nsubprocessors:\n  url: null\n\
  \  text: 'Lightning payment infrastructure: the node software, payment providers, and encrypted messaging relays\n    we use to send and receive Lightning payments (these may change over time); DigitalOcean: hosting; Resend (email\n    delivery for sign-in and service email): support and service email'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@amazap.com to request deletion or account closure\n  text: You can ask us to access, correct, or delete your personal information, or close your account, by emailing\n    privacy@amazap.com.\nrights:\n- right: access, correct, delete\n  text: You can ask us to access, correct, or delete your personal information, or close your account, by emailing\n    privacy@amazap.com.\n- right: portability\n  text: 'Your rights: access, rectification, erasure, restriction, portability, objection to processing based on\n    legitimate interests, and withdrawal of consent.'\n- right: opt out of sale or sharing\n  text:\
  \ to opt out of sale or sharing (we don't do either)\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal information and don't share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/amazap-com/privacy/amazap-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Amazap's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Micropayments
- Lightning
- Marketplace
---
