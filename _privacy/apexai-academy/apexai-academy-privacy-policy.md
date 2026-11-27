---
api_specs:
- filename: apexai-academy-agents-api-openapi.yml
  format: yaml
  label: Apex AI Academy Agents API
  slug: apexai-academy-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-agents-api-openapi.yml
- filename: apexai-academy-courses-api-openapi.yml
  format: yaml
  label: Apex AI Academy Courses API
  slug: apexai-academy-courses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-courses-api-openapi.yml
- filename: apexai-academy-deep-dives-api-openapi.yml
  format: yaml
  label: Apex AI Academy Deep Dives API
  slug: apexai-academy-deep-dives-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-deep-dives-api-openapi.yml
- filename: apexai-academy-forum-api-openapi.yml
  format: yaml
  label: Apex AI Academy Forum API
  slug: apexai-academy-forum-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-forum-api-openapi.yml
- filename: apexai-academy-lessons-api-openapi.yml
  format: yaml
  label: Apex AI Academy Lessons API
  slug: apexai-academy-lessons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-lessons-api-openapi.yml
- filename: apexai-academy-news-api-openapi.yml
  format: yaml
  label: Apex AI Academy News API
  slug: apexai-academy-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-news-api-openapi.yml
- filename: apexai-academy-pricing-api-openapi.yml
  format: yaml
  label: Apex AI Academy Pricing API
  slug: apexai-academy-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-pricing-api-openapi.yml
- filename: apexai-academy-search-api-openapi.yml
  format: yaml
  label: Apex AI Academy Search API
  slug: apexai-academy-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-search-api-openapi.yml
- filename: apexai-academy-subscribe-link-api-openapi.yml
  format: yaml
  label: Apex AI Academy Subscribe Link API
  slug: apexai-academy-subscribe-link-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apexai-academy/openapi/apexai-academy-subscribe-link-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: your IP address and your browser's user-agent string
  - category: contact
    text: your email address and an optional name
  - category: financial
    text: 'What we store: your Stripe customer ID, your subscription ID, plan, status'
  - category: location
    text: Google says Analytics 4 uses it to estimate your approximate location and does not log or store it.
  - category: behavioral
    text: such as which pages are visited, including pages in the members area
  - category: device
    text: standard device and browser information
  - category: communication
    text: we store your name, email, topic and message
  deletion:
    route: Account page deletion
    text: you can delete your account from your account page
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account and subscription operation
    text: Providing Premium access and processing subscriptions through Stripe
  - purpose: Security and abuse prevention
    text: Security, abuse prevention, rate limiting and audit logs
  - purpose: Site usage measurement
    text: Apex uses Google Analytics 4 to measure site usage
  retention:
  - period: 14 days
    scope: Sessions
    text: Sessions expire after 14 days, and expired sessions are deleted.
  - period: until you delete your account
    scope: Account data
    text: 'Account data: kept until you delete your account.'
  - period: after account deletion
    scope: Billing records
    text: 'Billing records: kept after account deletion as required for accounting.'
  - period: 90 days
    scope: Hidden and removed forum posts
    text: Hidden, removed and author-deleted posts are kept for 90 days for moderation and appeals.
  rights:
  - right: Access and export
    text: you can download your account data, including your subscription history, from your account page.
  - right: Correction
    text: you can edit your name in your account page.
  - right: Other rights
    text: you may have more rights (such as objection, restriction, portability or complaint to a supervisory authority)
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal information.
  subprocessors:
    text: Stripe (payments and the billing portal). Our email delivery provider (Resend), for account emails.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Apex AI Academy
provenance_date: '2026-11-09'
provider_name: Apex AI Academy
provider_slug: apexai-academy
slug: apexai-academy-privacy-policy
source_date: '2026-11-09'
source_filename: apexai-academy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apexai.academy/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Apex AI Academy\naid: apexai-academy\nurl: https://apexai.academy/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your IP address and your browser's user-agent string\n- category: contact\n  text: your email address and an optional name\n- category: financial\n  text: 'What we store: your Stripe customer ID, your subscription ID, plan, status'\n- category: location\n  text: Google says Analytics 4 uses it to estimate your approximate location and does not log or store it.\n- category: behavioral\n  text: such as which pages\
  \ are visited, including pages in the members area\n- category: device\n  text: standard device and browser information\n- category: communication\n  text: we store your name, email, topic and message\npurposes:\n- purpose: Account and subscription operation\n  text: Providing Premium access and processing subscriptions through Stripe\n- purpose: Security and abuse prevention\n  text: Security, abuse prevention, rate limiting and audit logs\n- purpose: Site usage measurement\n  text: Apex uses Google Analytics 4 to measure site usage\nretention:\n- scope: Sessions\n  period: 14 days\n  text: Sessions expire after 14 days, and expired sessions are deleted.\n- scope: Account data\n  period: until you delete your account\n  text: 'Account data: kept until you delete your account.'\n- scope: Billing records\n  period: after account deletion\n  text: 'Billing records: kept after account deletion as required for accounting.'\n- scope: Hidden and removed forum posts\n  period: 90 days\n  text:\
  \ Hidden, removed and author-deleted posts are kept for 90 days for moderation and appeals.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Stripe (payments and the billing portal). Our email delivery provider (Resend), for account emails.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account page deletion\n  text: you can delete your account from your account page\nrights:\n- right: Access and export\n  text: you can download your account data, including your subscription history, from your account page.\n- right: Correction\n  text: you can edit your name in your account page.\n- right: Other rights\n  text: you may have more rights (such as objection, restriction, portability or complaint to a supervisory authority)\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/apexai-academy/privacy/apexai-academy-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Apex AI Academy's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Education
- Learning
- Agents
- Platform
---
