---
api_specs:
- filename: quantsonar-com-default-api-openapi.yml
  format: yaml
  label: quantsonar-com 分红送股 API
  slug: quantsonar-com-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quantsonar-com/openapi/quantsonar-com-default-api-openapi.yml
- filename: quantsonar-com-etf-api-openapi.yml
  format: yaml
  label: quantsonar-com ETF API
  slug: quantsonar-com-etf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quantsonar-com/openapi/quantsonar-com-etf-api-openapi.yml
- filename: quantsonar-com-health-api-openapi.yml
  format: yaml
  label: quantsonar-com Health API
  slug: quantsonar-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/quantsonar-com/openapi/quantsonar-com-health-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account : email and password (stored as a salted hash — we never see the plaintext)'
  - category: device
    text: 'Usage : API call counts (aggregated by key, endpoint, date), sign-in times, registration IP (anti-abuse)'
  - category: financial
    text: 'Payment : handled by Stripe; we store only order and access-period status plus a customer id — we never touch or store card numbers'
  deletion:
    route: Write to support@quantsonar.com
    text: Export or delete your account data, or correct your email, anytime — write to support@quantsonar.com; we respond within 7 business days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operating the service
    text: 'Operating the service: quotas, rate limits, billing'
  - purpose: Transactional email
    text: Transactional email only (password reset, expiry reminders) — no marketing mail
  - purpose: Abuse prevention
    text: 'Abuse prevention: detecting bulk registration and anomalous traffic'
  retention:
  - period: 30 days
    scope: Account data
    text: Account data is deleted within 30 days of account closure, except records we must retain by law.
  rights:
  - right: Export or delete account data
    text: Export or delete your account data, or correct your email, anytime
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Beyond what these services require to operate, we never sell or share your personal data.
  subprocessors:
    text: Stripe (payments, PCI-DSS compliant); Alibaba Cloud (servers, database, email delivery).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: quantsonar-com
provenance_date: '2026-11-10'
provider_name: quantsonar-com
provider_slug: quantsonar-com
slug: quantsonar-com-privacy-policy
source_date: '2026-11-10'
source_filename: quantsonar-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://quantsonar.com/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: quantsonar-com\naid: quantsonar-com\nurl: https://quantsonar.com/en/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account : email and password (stored as a salted hash — we never see the plaintext)'\n- category: device\n  text: 'Usage : API call counts (aggregated by key, endpoint, date), sign-in times, registration IP (anti-abuse)'\n- category: financial\n  text: 'Payment : handled by Stripe; we store only order and access-period status plus a customer id — we never\n    touch or store card numbers'\npurposes:\n- purpose: Operating\
  \ the service\n  text: 'Operating the service: quotas, rate limits, billing'\n- purpose: Transactional email\n  text: Transactional email only (password reset, expiry reminders) — no marketing mail\n- purpose: Abuse prevention\n  text: 'Abuse prevention: detecting bulk registration and anomalous traffic'\nretention:\n- scope: Account data\n  period: 30 days\n  text: Account data is deleted within 30 days of account closure, except records we must retain by law.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Stripe (payments, PCI-DSS compliant); Alibaba Cloud (servers, database, email delivery).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to support@quantsonar.com\n  text: Export or delete your account data, or correct your email, anytime — write to support@quantsonar.com; we\n    respond within 7 business days.\nrights:\n- right: Export or delete account data\n  text: Export or delete your account data, or correct your email, anytime\n\
  sale_or_sharing:\n  stance: prohibited\n  text: Beyond what these services require to operate, we never sell or share your personal data.\n"
source_yaml_url: https://artifacts.apis.io/quantsonar-com/privacy/quantsonar-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 11 quoted statements, read from quantsonar-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Data
- China
- Stock Market
---
