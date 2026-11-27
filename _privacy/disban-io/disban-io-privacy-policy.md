---
api_specs:
- filename: disban-io-auth-api-openapi.yml
  format: yaml
  label: disban-io Auth API
  slug: disban-io-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-auth-api-openapi.yml
- filename: disban-io-batch-api-openapi.yml
  format: yaml
  label: disban-io Batch API
  slug: disban-io-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-batch-api-openapi.yml
- filename: disban-io-check-api-openapi.yml
  format: yaml
  label: disban-io Check API
  slug: disban-io-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-check-api-openapi.yml
- filename: disban-io-features-api-openapi.yml
  format: yaml
  label: disban-io Features API
  slug: disban-io-features-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-features-api-openapi.yml
- filename: disban-io-keys-api-openapi.yml
  format: yaml
  label: disban-io Keys API
  slug: disban-io-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-keys-api-openapi.yml
- filename: disban-io-plans-api-openapi.yml
  format: yaml
  label: disban-io Plans API
  slug: disban-io-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-plans-api-openapi.yml
- filename: disban-io-referrals-api-openapi.yml
  format: yaml
  label: disban-io Referrals API
  slug: disban-io-referrals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-referrals-api-openapi.yml
- filename: disban-io-subscription-api-openapi.yml
  format: yaml
  label: disban-io Subscription API
  slug: disban-io-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-subscription-api-openapi.yml
- filename: disban-io-webhooks-api-openapi.yml
  format: yaml
  label: disban-io Webhooks API
  slug: disban-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/disban-io/openapi/disban-io-webhooks-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: We store your account name, sign-in email, plan, API-key records, sessions and usage counters to provide the service.
  - category: communication
    text: Support stores the subject, topic, messages, status and timestamps linked to your account.
  - category: behavioral
    text: we record account-linked signup, API-key creation, successful-check and daily-use milestones to improve onboarding.
  - category: device
    text: Google Analytics cookies (such as _ga) are set and Google receives page paths (never query strings), referring pages, device and browser details, approximate location derived from your IP address
  deletion:
    route: 'Account controls: delete activity or delete account after email verification'
    text: Account controls let you delete activity, sign out all sessions or delete your account after email verification.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: We store your account name, sign-in email, plan, API-key records, sessions and usage counters to provide the service.
  - purpose: Improve onboarding
    text: We record account-linked signup, API-key creation, successful-check and daily-use milestones to improve onboarding.
  - purpose: Website analytics
    text: With your consent, Disban uses Google Analytics 4 to understand how visitors find the site and move from a first visit to signup and API-key creation.
  retention:
  - period: 15 days
    scope: Account activity (Free plan)
    text: 'Activity follows your current plan: Free 15 days, Launch 30 days, Growth 60 days and Scale 90 days.'
  - period: 90 days
    scope: Resolved support tickets
    text: resolved tickets are deleted after 90 days by asynchronous cleanup.
  - period: up to 90 days
    scope: Product usage events
    text: Events are retained for up to 90 days and cleaned hourly while the service runs and on growth-dashboard access
  - period: 30 days
    scope: Acquisition-source cookie
    text: A first-party cookie remembers only a limited acquisition-source label (direct, organic, outreach or referral) for 30 days.
  rights:
  - right: Export activity
    text: Export activity from the dashboard.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: disban-io
provenance_date: '2026-11-09'
provider_name: disban-io
provider_slug: disban-io
slug: disban-io-privacy-policy
source_date: '2026-11-09'
source_filename: disban-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://disban.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: disban-io\naid: disban-io\nurl: https://disban.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We store your account name, sign-in email, plan, API-key records, sessions and usage counters to provide\n    the service.\n- category: communication\n  text: Support stores the subject, topic, messages, status and timestamps linked to your account.\n- category: behavioral\n  text: we record account-linked signup, API-key creation, successful-check and daily-use milestones to improve\n    onboarding.\n- category: device\n  text: Google\
  \ Analytics cookies (such as _ga) are set and Google receives page paths (never query strings), referring\n    pages, device and browser details, approximate location derived from your IP address\npurposes:\n- purpose: Provide the service\n  text: We store your account name, sign-in email, plan, API-key records, sessions and usage counters to provide\n    the service.\n- purpose: Improve onboarding\n  text: We record account-linked signup, API-key creation, successful-check and daily-use milestones to improve\n    onboarding.\n- purpose: Website analytics\n  text: With your consent, Disban uses Google Analytics 4 to understand how visitors find the site and move from\n    a first visit to signup and API-key creation.\nretention:\n- scope: Account activity (Free plan)\n  period: 15 days\n  text: 'Activity follows your current plan: Free 15 days, Launch 30 days, Growth 60 days and Scale 90 days.'\n- scope: Resolved support tickets\n  period: 90 days\n  text: resolved tickets are deleted\
  \ after 90 days by asynchronous cleanup.\n- scope: Product usage events\n  period: up to 90 days\n  text: Events are retained for up to 90 days and cleaned hourly while the service runs and on growth-dashboard\n    access\n- scope: Acquisition-source cookie\n  period: 30 days\n  text: A first-party cookie remembers only a limited acquisition-source label (direct, organic, outreach or referral)\n    for 30 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: 'Account controls: delete activity or delete account after email verification'\n  text: Account controls let you delete activity, sign out all sessions or delete your account after email verification.\nrights:\n- right: Export activity\n  text: Export activity from the dashboard.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/disban-io/privacy/disban-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 13 quoted statements, read from disban-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- Disposable Email
- Security
- Fraud Prevention
---
