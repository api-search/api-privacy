---
api_specs:
- filename: snap-render-com-extract-api-openapi.yml
  format: yaml
  label: snap-render-com Extract API
  slug: snap-render-com-extract-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snap-render-com/openapi/snap-render-com-extract-api-openapi.yml
- filename: snap-render-com-health-api-openapi.yml
  format: yaml
  label: snap-render-com Health API
  slug: snap-render-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snap-render-com/openapi/snap-render-com-health-api-openapi.yml
- filename: snap-render-com-schedules-api-openapi.yml
  format: yaml
  label: snap-render-com Schedules API
  slug: snap-render-com-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snap-render-com/openapi/snap-render-com-schedules-api-openapi.yml
- filename: snap-render-com-usage-api-openapi.yml
  format: yaml
  label: snap-render-com Usage API
  slug: snap-render-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snap-render-com/openapi/snap-render-com-usage-api-openapi.yml
- filename: snap-render-com-webhooks-api-openapi.yml
  format: yaml
  label: snap-render-com Webhooks API
  slug: snap-render-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snap-render-com/openapi/snap-render-com-webhooks-api-openapi.yml
- filename: snap-render-com-screenshot-api-openapi.yml
  format: yaml
  label: SnapRender Screenshot API
  slug: snap-render-com-screenshot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snap-render-com/openapi/snap-render-com-screenshot-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: Email address, name (optional), and hashed password when you register'
  - category: financial
    text: 'Payment information: Processed securely by Stripe. We do not store your card details.'
  - category: behavioral
    text: 'Usage data: API request counts, timestamps, and response times for quota tracking and service monitoring'
  - category: other
    text: 'URLs submitted: The URLs you submit for screenshots are processed to generate the screenshot and may be logged for debugging and abuse prevention'
  - category: device
    text: 'Technical data: IP addresses, request headers, and server logs for security and operational purposes'
  deletion:
    route: Delete account
    text: If you delete your account, we will delete your personal data within 30 days
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: Provide and maintain the Service
  - purpose: Process payments
    text: Process payments and manage subscriptions
  - purpose: Track usage against plan limits
    text: Track usage against your plan limits
  - purpose: Transactional emails
    text: Send transactional emails (verification codes, password resets, quota alerts)
  - purpose: Prevent abuse
    text: Prevent abuse and enforce our Terms of Service
  - purpose: Debug and improve
    text: Debug issues and improve the Service
  residency:
  - region: European Union
    text: Your data is stored on servers hosted in the European Union.
  retention:
  - period: as long as your account is active
    scope: Account data
    text: We retain your account data for as long as your account is active.
  - period: 30 days
    scope: Account deletion
    text: If you delete your account, we will delete your personal data within 30 days
  - period: up to 90 days
    scope: Usage logs
    text: Usage logs are retained for up to 90 days.
  - period: cache TTL
    scope: Cached screenshots
    text: Cached screenshots are automatically deleted after the cache TTL expires.
  rights:
  - right: Access
    text: Access the personal data we hold about you
  - right: Correction
    text: Request correction of inaccurate data
  - right: Deletion
    text: Request deletion of your data
  - right: Objection or restriction
    text: Object to or restrict processing of your data
  - right: Portability
    text: Request data portability
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
name: SnapRender
provenance_date: '2026-11-10'
provider_name: SnapRender
provider_slug: snap-render-com
slug: snap-render-com-privacy-policy
source_date: '2026-11-10'
source_filename: snap-render-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://snap-render.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SnapRender\naid: snap-render-com\nurl: https://snap-render.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account information: Email address, name (optional), and hashed password when you register'\n- category: financial\n  text: 'Payment information: Processed securely by Stripe. We do not store your card details.'\n- category: behavioral\n  text: 'Usage data: API request counts, timestamps, and response times for quota tracking and service monitoring'\n- category: other\n  text: 'URLs submitted: The URLs you submit for screenshots\
  \ are processed to generate the screenshot and may be\n    logged for debugging and abuse prevention'\n- category: device\n  text: 'Technical data: IP addresses, request headers, and server logs for security and operational purposes'\npurposes:\n- purpose: Provide and maintain the Service\n  text: Provide and maintain the Service\n- purpose: Process payments\n  text: Process payments and manage subscriptions\n- purpose: Track usage against plan limits\n  text: Track usage against your plan limits\n- purpose: Transactional emails\n  text: Send transactional emails (verification codes, password resets, quota alerts)\n- purpose: Prevent abuse\n  text: Prevent abuse and enforce our Terms of Service\n- purpose: Debug and improve\n  text: Debug issues and improve the Service\nretention:\n- scope: Account data\n  period: as long as your account is active\n  text: We retain your account data for as long as your account is active.\n- scope: Account deletion\n  period: 30 days\n  text: If you delete\
  \ your account, we will delete your personal data within 30 days\n- scope: Usage logs\n  period: up to 90 days\n  text: Usage logs are retained for up to 90 days.\n- scope: Cached screenshots\n  period: cache TTL\n  text: Cached screenshots are automatically deleted after the cache TTL expires.\nresidency:\n- region: European Union\n  text: Your data is stored on servers hosted in the European Union.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account\n  text: If you delete your account, we will delete your personal data within 30 days\nrights:\n- right: Access\n  text: Access the personal data we hold about you\n- right: Correction\n  text: Request correction of inaccurate data\n- right: Deletion\n  text: Request deletion of your data\n- right: Objection or restriction\n  text: Object to or restrict processing of your data\n- right: Portability\n  text: Request data portability\nsale_or_sharing:\n\
  \  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/snap-render-com/privacy/snap-render-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 22 quoted statements, read from SnapRender's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Screenshots
- Rendering
- Automation
- Cloud
---
