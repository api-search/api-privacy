---
api_specs:
- filename: bizmoon-ai-read-api-openapi.yml
  format: yaml
  label: Bizmoon Read API
  slug: bizmoon-ai-read-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizmoon-ai/openapi/bizmoon-ai-read-api-openapi.yml
- filename: bizmoon-ai-write-api-openapi.yml
  format: yaml
  label: Bizmoon Write API
  slug: bizmoon-ai-write-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bizmoon-ai/openapi/bizmoon-ai-write-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account we collect your name and email address via Google OAuth.
  - category: financial
    text: We do not store credit card numbers.
  - category: device
    text: We automatically collect IP addresses, browser type, pages visited, and timestamps to operate and improve the service.
  - category: communication
    text: We retain full conversation history with our AI assistant, including your messages, assistant responses, and any file attachments you include.
  - category: professional
    text: You may provide your company name, industry, NAICS codes, and policy watchlist keywords so we can deliver relevant analyses and alerts.
  - category: other
    text: You may upload images (PNG, JPEG, GIF, WebP), PDFs, and text/CSV files up to 10 MB per file.
  deletion:
    route: account deletion
    text: If you delete your account, we remove your personal data within 30 days, except where retention is required by law.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Deliver policy analyses and regulatory alerts
    text: Deliver policy analyses and regulatory alerts
  - purpose: Draft grant application documents using AI
    text: Draft grant application documents using AI based on your answers and organization profile
  - purpose: Process payments and manage subscriptions
    text: Process payments and manage subscriptions
  - purpose: Track API usage and enforce rate limits
    text: Track API usage and enforce rate limits for API customers
  - purpose: Improve and secure the platform
    text: Improve and secure the platform
  retention:
  - period: for the life of your account
    scope: account data
    text: We retain account data for the life of your account.
  - period: for the life of your account
    scope: AI conversations
    text: 'AI conversations : Retained for the life of your account.'
  - period: 12 months
    scope: audit logs
    text: 'Audit logs : Retained for a minimum of 12 months for security purposes.'
  - period: null
    scope: API usage records
    text: 'API usage records : Retained for billing and compliance purposes.'
  rights:
  - right: CCPA access, deletion, opt out of sale
    text: California residents may request access to, deletion of, or opt out of the sale of personal information.
  - right: GDPR access, rectification, erasure, restriction, portability
    text: you have the right to access, rectify, erase, restrict processing, or port your data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information to any third party.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bizmoon
provenance_date: '2026-11-09'
provider_name: Bizmoon
provider_slug: bizmoon-ai
slug: bizmoon-ai-privacy-policy
source_date: '2026-11-09'
source_filename: bizmoon-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bizmoon.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bizmoon\naid: bizmoon-ai\nurl: https://bizmoon.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account we collect your name and email address via Google OAuth.\n- category: financial\n  text: We do not store credit card numbers.\n- category: device\n  text: We automatically collect IP addresses, browser type, pages visited, and timestamps to operate and improve\n    the service.\n- category: communication\n  text: We retain full conversation history with our AI assistant, including your messages, assistant\
  \ responses,\n    and any file attachments you include.\n- category: professional\n  text: You may provide your company name, industry, NAICS codes, and policy watchlist keywords so we can deliver\n    relevant analyses and alerts.\n- category: other\n  text: You may upload images (PNG, JPEG, GIF, WebP), PDFs, and text/CSV files up to 10 MB per file.\npurposes:\n- purpose: Deliver policy analyses and regulatory alerts\n  text: Deliver policy analyses and regulatory alerts\n- purpose: Draft grant application documents using AI\n  text: Draft grant application documents using AI based on your answers and organization profile\n- purpose: Process payments and manage subscriptions\n  text: Process payments and manage subscriptions\n- purpose: Track API usage and enforce rate limits\n  text: Track API usage and enforce rate limits for API customers\n- purpose: Improve and secure the platform\n  text: Improve and secure the platform\nretention:\n- scope: account data\n  period: for the life of\
  \ your account\n  text: We retain account data for the life of your account.\n- scope: AI conversations\n  period: for the life of your account\n  text: 'AI conversations : Retained for the life of your account.'\n- scope: audit logs\n  period: 12 months\n  text: 'Audit logs : Retained for a minimum of 12 months for security purposes.'\n- scope: API usage records\n  period: null\n  text: 'API usage records : Retained for billing and compliance purposes.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion\n  text: If you delete your account, we remove your personal data within 30 days, except where retention is required\n    by law.\nrights:\n- right: CCPA access, deletion, opt out of sale\n  text: California residents may request access to, deletion of, or opt out of the sale of personal information.\n- right: GDPR access, rectification, erasure, restriction, portability\n  text:\
  \ you have the right to access, rectify, erase, restrict processing, or port your data.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information to any third party.\n"
source_yaml_url: https://artifacts.apis.io/bizmoon-ai/privacy/bizmoon-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Bizmoon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Compliance
- Grants
- Small Business
---
