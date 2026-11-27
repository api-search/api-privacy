---
api_specs:
- filename: yepapi-email-api-openapi.yml
  format: yaml
  label: YepAPI Email API
  slug: yepapi-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yepapi/openapi/yepapi-email-api-openapi.yml
- filename: yepapi-maps-api-openapi.yml
  format: yaml
  label: YepAPI Maps API
  slug: yepapi-maps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yepapi/openapi/yepapi-maps-api-openapi.yml
- filename: yepapi-seo-api-openapi.yml
  format: yaml
  label: YepAPI Seo API
  slug: yepapi-seo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yepapi/openapi/yepapi-seo-api-openapi.yml
- filename: yepapi-serp-api-openapi.yml
  format: yaml
  label: YepAPI Serp API
  slug: yepapi-serp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yepapi/openapi/yepapi-serp-api-openapi.yml
- filename: yepapi-tiktok-api-openapi.yml
  format: yaml
  label: YepAPI Tiktok API
  slug: yepapi-tiktok-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yepapi/openapi/yepapi-tiktok-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your email address and name (provided via Google or GitHub OAuth)
  - category: financial
    text: Billing information processed by our payment providers (Stripe for cards, Cryptomus for crypto payments, which also receives your account email with each crypto payment)
  - category: device
    text: IP addresses and basic device information from server logs
  - category: behavioral
    text: API usage data (endpoints called, timestamps, response codes)
  deletion:
    route: account deletion
    text: If you delete your account, we will remove your personal data within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain service
    text: Provide and maintain the YepAPI service
  - purpose: Billing and usage tracking
    text: Process billing and track API usage
  - purpose: Transactional emails
    text: Send transactional emails (billing receipts, account alerts)
  - purpose: Reliability and abuse detection
    text: Improve service reliability and detect abuse
  - purpose: Ad measurement
    text: We use measurement pixels from X (Twitter), Reddit, and OpenAI to see which of our ads lead to page visits, sign-ups, and credit top-ups.
  retention:
  - period: up to 30 days
    scope: short-term debugging logs
    text: We do not store the contents of your API request payloads or response bodies beyond what is necessary for real-time routing, billing, and short-term debugging logs (retained for up to 30 days).
  - period: as long as your account is active
    scope: account information
    text: We retain your account information for as long as your account is active.
  - period: up to 90 days
    scope: attribution cookie
    text: On your first visit we store a cookie for up to 90 days recording how you arrived
  rights:
  - right: Access
    text: Access the personal data we hold about you
  - right: Correction
    text: Request correction of inaccurate data
  - right: Deletion
    text: Request deletion of your account and associated data
  - right: Export
    text: Export your usage data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: YepAPI
provenance_date: '2026-11-10'
provider_name: YepAPI
provider_slug: yepapi
slug: yepapi-privacy-policy
source_date: '2026-11-10'
source_filename: yepapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.yepapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: YepAPI\naid: yepapi\nurl: https://www.yepapi.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we collect your email address and name (provided via Google or GitHub OAuth)\n- category: financial\n  text: Billing information processed by our payment providers (Stripe for cards, Cryptomus for crypto payments,\n    which also receives your account email with each crypto payment)\n- category: device\n  text: IP addresses and basic device information from server logs\n- category: behavioral\n  text: API usage data (endpoints called,\
  \ timestamps, response codes)\npurposes:\n- purpose: Provide and maintain service\n  text: Provide and maintain the YepAPI service\n- purpose: Billing and usage tracking\n  text: Process billing and track API usage\n- purpose: Transactional emails\n  text: Send transactional emails (billing receipts, account alerts)\n- purpose: Reliability and abuse detection\n  text: Improve service reliability and detect abuse\n- purpose: Ad measurement\n  text: We use measurement pixels from X (Twitter), Reddit, and OpenAI to see which of our ads lead to page visits,\n    sign-ups, and credit top-ups.\nretention:\n- scope: short-term debugging logs\n  period: up to 30 days\n  text: We do not store the contents of your API request payloads or response bodies beyond what is necessary for\n    real-time routing, billing, and short-term debugging logs (retained for up to 30 days).\n- scope: account information\n  period: as long as your account is active\n  text: We retain your account information for as\
  \ long as your account is active.\n- scope: attribution cookie\n  period: up to 90 days\n  text: On your first visit we store a cookie for up to 90 days recording how you arrived\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion\n  text: If you delete your account, we will remove your personal data within 30 days.\nrights:\n- right: Access\n  text: Access the personal data we hold about you\n- right: Correction\n  text: Request correction of inaccurate data\n- right: Deletion\n  text: Request deletion of your account and associated data\n- right: Export\n  text: Export your usage data\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your personal information.\n"
source_yaml_url: https://artifacts.apis.io/yepapi/privacy/yepapi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from YepAPI's own page on 2026-11-10.
synthetic: false
tags:
- SEO
- SERP
- Web Scraping
- AI Models
- Marketing
---
