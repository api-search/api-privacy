---
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: email address and password (stored as a hashed value — we never store your plain-text password)'
  - category: contact
    text: 'Account data: email address and password (stored as a hashed value — we never store your plain-text password)'
  - category: financial
    text: 'Billing data: payment processing is handled entirely by Stripe. We store your Stripe customer ID but never your card number or billing details'
  - category: device
    text: 'Usage data: standard server logs including IP addresses, request paths, and timestamps'
  - category: other
    text: 'Product data: product names, website URLs, API docs URLs, and descriptions you provide when generating an MCP server'
  deletion:
    route: Delete account, or email request
    text: If you delete your account, we delete your data within 30 days, except where required by law (e.g., billing records).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account management
    text: To create and manage your account
  - purpose: Hosting MCP endpoints
    text: To generate and host your MCP server endpoints
  - purpose: Payments
    text: To process payments and manage your subscription
  - purpose: Transactional email
    text: To send transactional emails (account confirmation, billing receipts)
  - purpose: Error diagnosis and improvement
    text: To diagnose errors and improve the service
  retention:
  - period: as long as your account is active
    scope: Account and product data
    text: We retain your account and product data for as long as your account is active.
  - period: 30 days
    scope: Deleted account data
    text: If you delete your account, we delete your data within 30 days, except where required by law (e.g., billing records).
  rights:
  - right: Access
    text: You may request access to, correction of, or deletion of your personal data at any time by emailing
  - right: Correction
    text: You may request access to, correction of, or deletion of your personal data at any time by emailing
  - right: Deletion
    text: You may request access to, correction of, or deletion of your personal data at any time by emailing
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: agentramp-io
provenance_date: '2026-11-09'
provider_name: agentramp-io
provider_slug: agentramp-io
slug: agentramp-io-privacy-policy
source_date: '2026-11-09'
source_filename: agentramp-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentramp.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: agentramp-io\naid: agentramp-io\nurl: https://agentramp.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account data: email address and password (stored as a hashed value — we never store your plain-text password)'\n- category: contact\n  text: 'Account data: email address and password (stored as a hashed value — we never store your plain-text password)'\n- category: financial\n  text: 'Billing data: payment processing is handled entirely by Stripe. We store your Stripe customer ID but never\n    your card number or billing\
  \ details'\n- category: device\n  text: 'Usage data: standard server logs including IP addresses, request paths, and timestamps'\n- category: other\n  text: 'Product data: product names, website URLs, API docs URLs, and descriptions you provide when generating\n    an MCP server'\npurposes:\n- purpose: Account management\n  text: To create and manage your account\n- purpose: Hosting MCP endpoints\n  text: To generate and host your MCP server endpoints\n- purpose: Payments\n  text: To process payments and manage your subscription\n- purpose: Transactional email\n  text: To send transactional emails (account confirmation, billing receipts)\n- purpose: Error diagnosis and improvement\n  text: To diagnose errors and improve the service\nretention:\n- scope: Account and product data\n  period: as long as your account is active\n  text: We retain your account and product data for as long as your account is active.\n- scope: Deleted account data\n  period: 30 days\n  text: If you delete your\
  \ account, we delete your data within 30 days, except where required by law (e.g., billing\n    records).\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account, or email request\n  text: If you delete your account, we delete your data within 30 days, except where required by law (e.g., billing\n    records).\nrights:\n- right: Access\n  text: You may request access to, correction of, or deletion of your personal data at any time by emailing\n- right: Correction\n  text: You may request access to, correction of, or deletion of your personal data at any time by emailing\n- right: Deletion\n  text: You may request access to, correction of, or deletion of your personal data at any time by emailing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/agentramp-io/privacy/agentramp-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from agentramp-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- MCP
- API Management
- Monitoring
- Proxy
- Developer Tools
---
