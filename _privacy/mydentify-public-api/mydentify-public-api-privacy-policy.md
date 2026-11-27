---
api_specs:
- filename: mydentify-public-api-directories-api-openapi.yml
  format: yaml
  label: Mydentify Public API Directories API
  slug: mydentify-public-api-directories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mydentify-public-api/openapi/mydentify-public-api-directories-api-openapi.yml
- filename: mydentify-public-api-directories-json-api-openapi.yml
  format: yaml
  label: Mydentify Public API Directories.json API
  slug: mydentify-public-api-directories-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mydentify-public-api/openapi/mydentify-public-api-directories-json-api-openapi.yml
- filename: mydentify-public-api-imports-api-openapi.yml
  format: yaml
  label: Mydentify Public API Imports API
  slug: mydentify-public-api-imports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mydentify-public-api/openapi/mydentify-public-api-imports-api-openapi.yml
- filename: mydentify-public-api-leaderboards-api-openapi.yml
  format: yaml
  label: Mydentify Public API Leaderboards API
  slug: mydentify-public-api-leaderboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mydentify-public-api/openapi/mydentify-public-api-leaderboards-api-openapi.yml
- filename: mydentify-public-api-leaderboards-json-api-openapi.yml
  format: yaml
  label: Mydentify Public API Leaderboards.json API
  slug: mydentify-public-api-leaderboards-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mydentify-public-api/openapi/mydentify-public-api-leaderboards-json-api-openapi.yml
- filename: mydentify-public-api-product-categories-json-api-openapi.yml
  format: yaml
  label: Mydentify Public API Product Categories.json API
  slug: mydentify-public-api-product-categories-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mydentify-public-api/openapi/mydentify-public-api-product-categories-json-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: email address, name, profile photo, provider account identifier, and—when you use X—your username.'
  - category: financial
    text: 'Sponsorship and transaction records: company and contact details, selected placement, order status, Stripe customer or transaction references, and billing status.'
  - category: device
    text: 'Technical and usage information: request information, device and browser details, referral paths, page activity, approximate network information, security events, and a first-party session identifier stored in your browser.'
  - category: behavioral
    text: 'Community activity: signals, nominations, leaderboard participation, placements, badges, and related timestamps.'
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authentication
    text: We use information to authenticate members and builders; publish and maintain product profiles;
  - purpose: payments
    text: process and reconcile payments;
  - purpose: fraud prevention
    text: prevent fraud and abuse;
  - purpose: measurement
    text: measure whether the service is useful;
  residency:
  - region: United States and other locations
    text: Information may be processed in the United States and other locations where our providers operate, subject to applicable safeguards.
  retention:
  - period: null
    scope: account and transaction records
    text: We retain account and transaction records while they are needed to provide the service, maintain public leaderboard history, resolve disputes, prevent abuse, and meet legal or accounting obligations.
  rights:
  - right: access, correct, delete
    text: ask us to access, correct, or delete account information.
  - right: decline optional analytics
    text: You may decline optional analytics, revoke Mydentify’s access from Google or X, cancel an eligible paid service
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or use your account information for targeted advertising.
  subprocessors:
    text: Current providers include Railway for hosting and databases, Stripe for payments, ImageKit for image storage and delivery, Sentry for error monitoring, Google Analytics and Ahrefs Web Analytics when you grant analytics consent, and Google or X when you choose their sign-in method.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Mydentify Public API
provenance_date: '2026-11-10'
provider_name: Mydentify Public API
provider_slug: mydentify-public-api
slug: mydentify-public-api-privacy-policy
source_date: '2026-11-10'
source_filename: mydentify-public-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mydentify.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Mydentify Public API\naid: mydentify-public-api\nurl: https://mydentify.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account information: email address, name, profile photo, provider account identifier, and—when you use\n    X—your username.'\n- category: financial\n  text: 'Sponsorship and transaction records: company and contact details, selected placement, order status, Stripe\n    customer or transaction references, and billing status.'\n- category: device\n  text: 'Technical and usage information: request information,\
  \ device and browser details, referral paths, page\n    activity, approximate network information, security events, and a first-party session identifier stored in your\n    browser.'\n- category: behavioral\n  text: 'Community activity: signals, nominations, leaderboard participation, placements, badges, and related timestamps.'\npurposes:\n- purpose: authentication\n  text: We use information to authenticate members and builders; publish and maintain product profiles;\n- purpose: payments\n  text: process and reconcile payments;\n- purpose: fraud prevention\n  text: prevent fraud and abuse;\n- purpose: measurement\n  text: measure whether the service is useful;\nretention:\n- scope: account and transaction records\n  period: null\n  text: We retain account and transaction records while they are needed to provide the service, maintain public\n    leaderboard history, resolve disputes, prevent abuse, and meet legal or accounting obligations.\nresidency:\n- region: United States and other\
  \ locations\n  text: Information may be processed in the United States and other locations where our providers operate, subject\n    to applicable safeguards.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Current providers include Railway for hosting and databases, Stripe for payments, ImageKit for image storage\n    and delivery, Sentry for error monitoring, Google Analytics and Ahrefs Web Analytics when you grant analytics\n    consent, and Google or X when you choose their sign-in method.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access, correct, delete\n  text: ask us to access, correct, or delete account information.\n- right: decline optional analytics\n  text: You may decline optional analytics, revoke Mydentify’s access from Google or X, cancel an eligible paid\n    service\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or use your account information for targeted advertising.\n"
source_yaml_url: https://artifacts.apis.io/mydentify-public-api/privacy/mydentify-public-api-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from Mydentify Public API's own page on 2026-11-10.
synthetic: false
tags:
- Product Discovery
- startup directories
- Leaderboards
- Research
- Software-as-a-Service
- Developer Tools
- Agent-Native
- Llms.txt
- Agent Skills
- Directories
---
