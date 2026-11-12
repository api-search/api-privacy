---
api_specs:
- filename: convalytics-dev-ingest-api-openapi.yml
  format: yaml
  label: Convalytics Ingest API
  slug: convalytics-dev-ingest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convalytics-dev/openapi/convalytics-dev-ingest-api-openapi.yml
- filename: convalytics-dev-meta-api-openapi.yml
  format: yaml
  label: Convalytics Meta API
  slug: convalytics-dev-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convalytics-dev/openapi/convalytics-dev-meta-api-openapi.yml
- filename: convalytics-dev-provision-api-openapi.yml
  format: yaml
  label: Convalytics Provision API
  slug: convalytics-dev-provision-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convalytics-dev/openapi/convalytics-dev-provision-api-openapi.yml
- filename: convalytics-dev-verify-api-openapi.yml
  format: yaml
  label: Convalytics Verify API
  slug: convalytics-dev-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/convalytics-dev/openapi/convalytics-dev-verify-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: Whatever you pass to convalytics.identify() or the userEmail / userName fields on analytics.track()
  - category: device
    text: Viewport dimensions and user agent string
  - category: behavioral
    text: The URL and referrer of each page load on your site
  - category: contact
    text: Your Google account email and display name (via Google OAuth)
  - category: financial
    text: Billing information (handled by Stripe; we never receive card numbers)
  deletion:
    route: Email dancleary54@gmail.com or delete project in dashboard
    text: Request deletion of your account and all associated data by emailing dancleary54@gmail.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Display analytics dashboard
    text: We store and display these events in your dashboard.
  - purpose: Manage team and billing
    text: we store the minimum data needed to identify you and manage your team and billing.
  retention:
  - period: 90 days on Free, 1 year on Solo, 5 years on Pro
    scope: Event data
    text: 'Event data is retained for the duration specified by your plan: 90 days on Free, 1 year on Solo, 5 years on Pro.'
  rights:
  - right: Access and export
    text: Export your project's analytics data as CSV from the dashboard.
  - right: Delete
    text: Delete your entire project at any time, which removes all associated analytics data.
  - right: Statutory rights
    text: For GDPR, CCPA, or other statutory data rights, email us and we will honor requests within the statutory window.
  role:
    text: Owner and data controller Tethered Software Inc.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent any of the data described above
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Convalytics
provenance_date: '2026-11-09'
provider_name: Convalytics
provider_slug: convalytics-dev
slug: convalytics-dev-privacy-policy
source_date: '2026-11-09'
source_filename: convalytics-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://convalytics.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Convalytics\naid: convalytics-dev\nurl: https://convalytics.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Owner and data controller Tethered Software Inc.\ndata_categories:\n- category: identifying\n  text: Whatever you pass to convalytics.identify() or the userEmail / userName fields on analytics.track()\n- category: device\n  text: Viewport dimensions and user agent string\n- category: behavioral\n  text: The URL and referrer of each page load on your site\n- category: contact\n  text: Your Google account email and display name (via Google OAuth)\n- category: financial\n  text:\
  \ Billing information (handled by Stripe; we never receive card numbers)\npurposes:\n- purpose: Display analytics dashboard\n  text: We store and display these events in your dashboard.\n- purpose: Manage team and billing\n  text: we store the minimum data needed to identify you and manage your team and billing.\nretention:\n- scope: Event data\n  period: 90 days on Free, 1 year on Solo, 5 years on Pro\n  text: 'Event data is retained for the duration specified by your plan: 90 days on Free, 1 year on Solo, 5 years\n    on Pro.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email dancleary54@gmail.com or delete project in dashboard\n  text: Request deletion of your account and all associated data by emailing dancleary54@gmail.com .\nrights:\n- right: Access and export\n  text: Export your project's analytics data as CSV from the dashboard.\n- right: Delete\n  text: Delete your entire project\
  \ at any time, which removes all associated analytics data.\n- right: Statutory rights\n  text: For GDPR, CCPA, or other statutory data rights, email us and we will honor requests within the statutory\n    window.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent any of the data described above\n"
source_yaml_url: https://artifacts.apis.io/convalytics-dev/privacy/convalytics-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from Convalytics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Analytics
- Product Analytics
- Web Analytics
- Convex
- Event Tracking
- MCP
- Developer Tools
---
