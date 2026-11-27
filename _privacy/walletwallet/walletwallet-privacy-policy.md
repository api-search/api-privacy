---
api_specs:
- filename: walletwallet-openapi-generated.yml
  format: yaml
  label: WalletWallet API
  slug: walletwallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/walletwallet/openapi/_ae-authored/walletwallet-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address (the only personal detail required to sign up).
  - category: financial
    text: Your card details and billing address are collected and held by our payment provider
  - category: behavioral
    text: API usage counts (per month and cumulative), timestamps, and the API operations you perform.
  - category: device
    text: IP address, device and browser information, and analytics events when you use our website and dashboard.
  - category: communication
    text: Apple Wallet error logs that devices send us (retained briefly).
  deletion:
    route: Contact founder@walletwallet.dev
    text: To exercise these rights, contact us at founder@walletwallet.dev
  dpa:
    available: true
    text: under the data-processing terms in our Terms & Conditions (Section 8)
    url: null
  purposes:
  - purpose: Provide the Service
    text: 'Provide the Service: generate, host, update, revoke passes'
  - purpose: Understand and improve product usage
    text: Understand and improve product usage (analytics)
  - purpose: No sale or advertising
    text: We do not sell personal data and do not use it for third-party advertising.
  residency:
  - region: European Union
    text: the primary database and the object store holding pass content and signed pass files both run in Cloudflare’s EU location, with no replicas outside it.
  - region: Global edge
    text: Request processing runs on Cloudflare’s global edge network, so compute is not EU only
  retention:
  - period: while your account is active
    scope: Account data and pass content
    text: 'Account data: kept while your account is active.'
  - period: 30 days
    scope: Account deletion
    text: on your request we delete your account and associated personal data within 30 days
  - period: 7 days
    scope: Apple Wallet error logs
    text: 'Apple Wallet error logs: retained for up to 7 days.'
  - period: within minutes
    scope: Verification codes and rate-limit data
    text: 'Verification codes and rate-limit data: expire automatically within minutes.'
  rights:
  - right: Access, rectify, erase, restrict, object
    text: the right to access, rectify, erase, restrict, or object to the processing of your personal data
  - right: Data portability
    text: the right to data portability
  - right: Withdraw consent
    text: the right to withdraw consent where processing is based on consent
  - right: Complaint to supervisory authority
    text: You also have the right to lodge a complaint with a supervisory authority.
  role:
    text: WalletWallet acts in two capacities
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and do not use it for third-party advertising.
  subprocessors:
    text: The authoritative sub-processor list, with a dated changelog and advance notice of changes, is published at /trust/subprocessors/
    url: /trust/subprocessors/
  transfers:
  - mechanism: SCC
    text: we rely on Standard Contractual Clauses for international transfers
  - mechanism: DPF
    text: Apple terms (SCCs / EU-US DPF)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: WalletWallet
provenance_date: '2026-11-10'
provider_name: WalletWallet
provider_slug: walletwallet
slug: walletwallet-privacy-policy
source_date: '2026-11-10'
source_filename: walletwallet-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.walletwallet.dev/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: WalletWallet\naid: walletwallet\nurl: https://www.walletwallet.dev/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: WalletWallet acts in two capacities\ndata_categories:\n- category: contact\n  text: Email address (the only personal detail required to sign up).\n- category: financial\n  text: Your card details and billing address are collected and held by our payment provider\n- category: behavioral\n  text: API usage counts (per month and cumulative), timestamps, and the API operations you perform.\n- category: device\n  text: IP address, device and browser information, and analytics events\
  \ when you use our website and dashboard.\n- category: communication\n  text: Apple Wallet error logs that devices send us (retained briefly).\npurposes:\n- purpose: Provide the Service\n  text: 'Provide the Service: generate, host, update, revoke passes'\n- purpose: Understand and improve product usage\n  text: Understand and improve product usage (analytics)\n- purpose: No sale or advertising\n  text: We do not sell personal data and do not use it for third-party advertising.\nretention:\n- scope: Account data and pass content\n  period: while your account is active\n  text: 'Account data: kept while your account is active.'\n- scope: Account deletion\n  period: 30 days\n  text: on your request we delete your account and associated personal data within 30 days\n- scope: Apple Wallet error logs\n  period: 7 days\n  text: 'Apple Wallet error logs: retained for up to 7 days.'\n- scope: Verification codes and rate-limit data\n  period: within minutes\n  text: 'Verification codes and rate-limit\
  \ data: expire automatically within minutes.'\nresidency:\n- region: European Union\n  text: the primary database and the object store holding pass content and signed pass files both run in Cloudflare’s\n    EU location, with no replicas outside it.\n- region: Global edge\n  text: Request processing runs on Cloudflare’s global edge network, so compute is not EU only\ntransfers:\n- mechanism: SCC\n  text: we rely on Standard Contractual Clauses for international transfers\n- mechanism: DPF\n  text: Apple terms (SCCs / EU-US DPF)\nsubprocessors:\n  url: /trust/subprocessors/\n  text: The authoritative sub-processor list, with a dated changelog and advance notice of changes, is published\n    at /trust/subprocessors/\ndpa:\n  available: true\n  url: null\n  text: under the data-processing terms in our Terms & Conditions (Section 8)\ndeletion:\n  route: Contact founder@walletwallet.dev\n  text: To exercise these rights, contact us at founder@walletwallet.dev\nrights:\n- right: Access, rectify,\
  \ erase, restrict, object\n  text: the right to access, rectify, erase, restrict, or object to the processing of your personal data\n- right: Data portability\n  text: the right to data portability\n- right: Withdraw consent\n  text: the right to withdraw consent where processing is based on consent\n- right: Complaint to supervisory authority\n  text: You also have the right to lodge a complaint with a supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and do not use it for third-party advertising.\n"
source_yaml_url: https://artifacts.apis.io/walletwallet/privacy/walletwallet-privacy-policy.yml
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
summary_line: 25 quoted statements, read from WalletWallet's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Wallets
- Passes
- Digital
---
