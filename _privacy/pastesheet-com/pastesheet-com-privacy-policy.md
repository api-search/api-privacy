---
api_specs:
- filename: pastesheet-com-openapi-generated.yml
  format: yaml
  label: pastesheet-com API
  slug: pastesheet-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pastesheet-com/openapi/_ae-authored/pastesheet-com-openapi-generated.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you register with an email address and password, we collect your name, email address, and a securely hashed (bcrypt) password.
  - category: identifying
    text: we instead receive your name, email address, a link to your Google profile photo, and a unique Google account identifier from Google
  - category: behavioral
    text: We record the number of requests made to each of your endpoints per day in order to enforce plan limits and to power your in-app Usage dashboard.
  - category: device
    text: We also store your session's IP address and browser user-agent string, which is standard practice for keeping your login session secure.
  - category: financial
    text: We do not collect or store your payment card details — Polar handles that as the merchant of record.
  - category: other
    text: we store the OAuth refresh and access tokens Google issues for that connection. These tokens are stored encrypted at rest
  deletion:
    route: Settings → Security account deletion; dashboard Google disconnect
    text: You can permanently delete your account at any time from Settings → Security, which removes your account and associated endpoints, API keys, and usage records.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, operate, and maintain the Service
    text: Provide, operate, and maintain the Service, including your API and MCP endpoints.
  - purpose: Authenticate and secure accounts
    text: Authenticate you and keep your account secure.
  - purpose: Enforce plan limits
    text: Enforce the request, row, and feature limits associated with your plan.
  - purpose: Transactional email and onboarding
    text: Send you transactional email (email verification, password resets) and a short onboarding email series when you first sign up.
  - purpose: Payments and subscriptions
    text: Process payments and manage subscriptions through Polar.sh.
  - purpose: Diagnose problems and prevent abuse
    text: Diagnose problems, prevent abuse, and improve the Service.
  retention:
  - period: null
    scope: Account and endpoint data
    text: We retain your account and endpoint data for as long as your account is active.
  - period: null
    scope: Billing history and billing webhook logs
    text: Some records, such as billing history required for accounting or legal purposes, or logs of billing-provider webhook events, may be retained for a limited period after deletion where necessary to comply with our legal obligations or resolve disputes.
  - period: null
    scope: Cached sheet row data
    text: The actual row data from your connected sheet is fetched from Google and cached temporarily to serve your API and MCP endpoints quickly; it is not stored in our primary database as a permanent record.
  rights:
  - right: Access or review Google connection
    text: You may also review or revoke PasteSheet's access independently at any time from your Google account's security settings.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to anyone.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: pastesheet-com
provenance_date: '2026-11-10'
provider_name: pastesheet-com
provider_slug: pastesheet-com
slug: pastesheet-com-privacy-policy
source_date: '2026-11-10'
source_filename: pastesheet-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://pastesheet.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: pastesheet-com\naid: pastesheet-com\nurl: https://pastesheet.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you register with an email address and password, we collect your name, email address, and a securely\n    hashed (bcrypt) password.\n- category: identifying\n  text: we instead receive your name, email address, a link to your Google profile photo, and a unique Google account\n    identifier from Google\n- category: behavioral\n  text: We record the number of requests made to each of your endpoints per day in order\
  \ to enforce plan limits\n    and to power your in-app Usage dashboard.\n- category: device\n  text: We also store your session's IP address and browser user-agent string, which is standard practice for keeping\n    your login session secure.\n- category: financial\n  text: We do not collect or store your payment card details — Polar handles that as the merchant of record.\n- category: other\n  text: we store the OAuth refresh and access tokens Google issues for that connection. These tokens are stored\n    encrypted at rest\npurposes:\n- purpose: Provide, operate, and maintain the Service\n  text: Provide, operate, and maintain the Service, including your API and MCP endpoints.\n- purpose: Authenticate and secure accounts\n  text: Authenticate you and keep your account secure.\n- purpose: Enforce plan limits\n  text: Enforce the request, row, and feature limits associated with your plan.\n- purpose: Transactional email and onboarding\n  text: Send you transactional email (email verification,\
  \ password resets) and a short onboarding email series when\n    you first sign up.\n- purpose: Payments and subscriptions\n  text: Process payments and manage subscriptions through Polar.sh.\n- purpose: Diagnose problems and prevent abuse\n  text: Diagnose problems, prevent abuse, and improve the Service.\nretention:\n- scope: Account and endpoint data\n  period: null\n  text: We retain your account and endpoint data for as long as your account is active.\n- scope: Billing history and billing webhook logs\n  period: null\n  text: Some records, such as billing history required for accounting or legal purposes, or logs of billing-provider\n    webhook events, may be retained for a limited period after deletion where necessary to comply with our legal\n    obligations or resolve disputes.\n- scope: Cached sheet row data\n  period: null\n  text: The actual row data from your connected sheet is fetched from Google and cached temporarily to serve your\n    API and MCP endpoints quickly; it\
  \ is not stored in our primary database as a permanent record.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings → Security account deletion; dashboard Google disconnect\n  text: You can permanently delete your account at any time from Settings → Security, which removes your account\n    and associated endpoints, API keys, and usage records.\nrights:\n- right: Access or review Google connection\n  text: You may also review or revoke PasteSheet's access independently at any time from your Google account's security\n    settings.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to anyone.\n"
source_yaml_url: https://artifacts.apis.io/pastesheet-com/privacy/pastesheet-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from pastesheet-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Google Sheets
- No-Code
- Artificial Intelligence
---
