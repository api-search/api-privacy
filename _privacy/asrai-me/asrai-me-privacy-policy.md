---
api_specs:
- filename: asrai-me-ai-api-openapi.yml
  format: yaml
  label: Asrai AI API
  slug: asrai-me-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asrai-me/openapi/asrai-me-ai-api-openapi.yml
- filename: asrai-me-cashflow-api-openapi.yml
  format: yaml
  label: Asrai Cashflow API
  slug: asrai-me-cashflow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asrai-me/openapi/asrai-me-cashflow-api-openapi.yml
- filename: asrai-me-market-data-api-openapi.yml
  format: yaml
  label: Asrai Market Data API
  slug: asrai-me-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asrai-me/openapi/asrai-me-market-data-api-openapi.yml
- filename: asrai-me-screeners-api-openapi.yml
  format: yaml
  label: Asrai Screeners API
  slug: asrai-me-screeners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asrai-me/openapi/asrai-me-screeners-api-openapi.yml
- filename: asrai-me-technical-api-openapi.yml
  format: yaml
  label: Asrai Technical API
  slug: asrai-me-technical-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/asrai-me/openapi/asrai-me-technical-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: email address, name, a hashed password (never the password itself)'
  - category: contact
    text: 'Telegram: your Telegram ID, name and username when you use our bot or connect Telegram to your account.'
  - category: financial
    text: 'Payments: the wallet address you pay from, transaction hashes, amount, token and network.'
  - category: device
    text: 'Technical and security data: IP address, browser and device type, a device identifier used to detect abuse, sign-in times and when you were last active.'
  - category: behavioral
    text: which pages and coin pages you open (counted per day)
  - category: location
    text: your country (from your IP address)
  - category: communication
    text: 'Chats: messages you send to the AI chat and the answers.'
  deletion:
    route: email to support address from account email
    text: 'Delete: email [email protected] from your account email to delete your account and data.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the service
    text: 'To provide the service: your account, signals, portfolio, chat, bot and API.'
  - purpose: payments
    text: To process and verify payments and keep your plan active.
  - purpose: security
    text: 'To keep Asrai safe: preventing fraud, spam sign-ups and people creating many accounts to abuse free plans.'
  - purpose: account emails
    text: 'To send account emails: verification, password reset and important service notices.'
  - purpose: analytics
    text: To understand which features help people and fix what doesn’t, using aggregated analytics.
  retention:
  - period: null
    scope: account data
    text: We keep your data while your account exists.
  - period: null
    scope: payment records
    text: We keep payment records as long as needed for accounting and to resolve disputes.
  rights:
  - right: access and export
    text: 'See and export: ask us for a copy of your data.'
  - right: correction
    text: 'Correct: update your details in Settings, or ask us.'
  - right: deletion
    text: 'Delete: email [email protected] from your account email to delete your account and data.'
  - right: objection and restriction
    text: you may also object to or restrict some processing and complain to your local data-protection authority.
  role:
    text: Asrai (“we”, “us”) runs the website and app at asrai.me
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell your personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Asrai
provenance_date: '2026-11-09'
provider_name: Asrai
provider_slug: asrai-me
slug: asrai-me-privacy-policy
source_date: '2026-11-09'
source_filename: asrai-me-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://asrai.me/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Asrai\naid: asrai-me\nurl: https://asrai.me/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Asrai (“we”, “us”) runs the website and app at asrai.me\ndata_categories:\n- category: identifying\n  text: 'Account: email address, name, a hashed password (never the password itself)'\n- category: contact\n  text: 'Telegram: your Telegram ID, name and username when you use our bot or connect Telegram to your account.'\n- category: financial\n  text: 'Payments: the wallet address you pay from, transaction hashes, amount, token and network.'\n- category: device\n  text: 'Technical and security\
  \ data: IP address, browser and device type, a device identifier used to detect abuse,\n    sign-in times and when you were last active.'\n- category: behavioral\n  text: which pages and coin pages you open (counted per day)\n- category: location\n  text: your country (from your IP address)\n- category: communication\n  text: 'Chats: messages you send to the AI chat and the answers.'\npurposes:\n- purpose: provide the service\n  text: 'To provide the service: your account, signals, portfolio, chat, bot and API.'\n- purpose: payments\n  text: To process and verify payments and keep your plan active.\n- purpose: security\n  text: 'To keep Asrai safe: preventing fraud, spam sign-ups and people creating many accounts to abuse free plans.'\n- purpose: account emails\n  text: 'To send account emails: verification, password reset and important service notices.'\n- purpose: analytics\n  text: To understand which features help people and fix what doesn’t, using aggregated analytics.\nretention:\n\
  - scope: account data\n  period: null\n  text: We keep your data while your account exists.\n- scope: payment records\n  period: null\n  text: We keep payment records as long as needed for accounting and to resolve disputes.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email to support address from account email\n  text: 'Delete: email [email protected] from your account email to delete your account and data.'\nrights:\n- right: access and export\n  text: 'See and export: ask us for a copy of your data.'\n- right: correction\n  text: 'Correct: update your details in Settings, or ask us.'\n- right: deletion\n  text: 'Delete: email [email protected] from your account email to delete your account and data.'\n- right: objection and restriction\n  text: you may also object to or restrict some processing and complain to your local data-protection authority.\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: We don’t sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/asrai-me/privacy/asrai-me-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Asrai's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Artificial Intelligence
- Trading
- Signals
- Telegram
- Analytics
---
