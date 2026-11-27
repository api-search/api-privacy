---
api_specs:
- filename: chartlink-app-account-api-openapi.yml
  format: yaml
  label: Chartlink Account API
  slug: chartlink-app-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-account-api-openapi.yml
- filename: chartlink-app-asset-types-api-openapi.yml
  format: yaml
  label: Chartlink Asset Types API
  slug: chartlink-app-asset-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-asset-types-api-openapi.yml
- filename: chartlink-app-assets-api-openapi.yml
  format: yaml
  label: Chartlink Assets API
  slug: chartlink-app-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-assets-api-openapi.yml
- filename: chartlink-app-billing-api-openapi.yml
  format: yaml
  label: Chartlink Billing API
  slug: chartlink-app-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-billing-api-openapi.yml
- filename: chartlink-app-billing-info-api-openapi.yml
  format: yaml
  label: Chartlink Billing Info API
  slug: chartlink-app-billing-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-billing-info-api-openapi.yml
- filename: chartlink-app-brands-api-openapi.yml
  format: yaml
  label: Chartlink Brands API
  slug: chartlink-app-brands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-brands-api-openapi.yml
- filename: chartlink-app-checkout-link-api-openapi.yml
  format: yaml
  label: Chartlink Checkout Link API
  slug: chartlink-app-checkout-link-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-checkout-link-api-openapi.yml
- filename: chartlink-app-data-api-openapi.yml
  format: yaml
  label: Chartlink Data API
  slug: chartlink-app-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-data-api-openapi.yml
- filename: chartlink-app-feedback-api-openapi.yml
  format: yaml
  label: Chartlink Feedback API
  slug: chartlink-app-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-feedback-api-openapi.yml
- filename: chartlink-app-fonts-api-openapi.yml
  format: yaml
  label: Chartlink Fonts API
  slug: chartlink-app-fonts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-fonts-api-openapi.yml
- filename: chartlink-app-geographies-api-openapi.yml
  format: yaml
  label: Chartlink Geographies API
  slug: chartlink-app-geographies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-geographies-api-openapi.yml
- filename: chartlink-app-invites-api-openapi.yml
  format: yaml
  label: Chartlink Invites API
  slug: chartlink-app-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-invites-api-openapi.yml
- filename: chartlink-app-keys-api-openapi.yml
  format: yaml
  label: Chartlink Keys API
  slug: chartlink-app-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-keys-api-openapi.yml
- filename: chartlink-app-oembed-api-openapi.yml
  format: yaml
  label: Chartlink Oembed API
  slug: chartlink-app-oembed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-oembed-api-openapi.yml
- filename: chartlink-app-signup-api-openapi.yml
  format: yaml
  label: Chartlink Signup API
  slug: chartlink-app-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-signup-api-openapi.yml
- filename: chartlink-app-try-api-openapi.yml
  format: yaml
  label: Chartlink Try API
  slug: chartlink-app-try-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-try-api-openapi.yml
- filename: chartlink-app-whoami-api-openapi.yml
  format: yaml
  label: Chartlink Whoami API
  slug: chartlink-app-whoami-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-whoami-api-openapi.yml
- filename: chartlink-app-workspace-api-openapi.yml
  format: yaml
  label: Chartlink Workspace API
  slug: chartlink-app-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chartlink-app/openapi/chartlink-app-workspace-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: your email address and, if you give one, your name
  - category: contact
    text: your email address and, if you give one, your name
  - category: device
    text: standard server logs including IP addresses, kept for operations and abuse prevention
  - category: behavioral
    text: events (which workspace did what, when)
  - category: financial
    text: We never see card numbers or payment details — payments are processed entirely by Paddle.com as merchant of record
  deletion:
    route: email support@chartlink.app from the address you sign in with
    text: 'You can ask for a copy of your data or for your account and workspaces to be deleted at any time: email support@chartlink.app from the address you sign in with.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the service
    text: We look at a workspace's brands and charts, drafts included, only to run the service
  - purpose: operations and abuse prevention
    text: standard server logs including IP addresses, kept for operations and abuse prevention
  - purpose: sign-in
    text: Signing in is by a link sent to that address or with Google
  retention:
  - period: up to 30 days
    scope: session cookie
    text: a session cookie keeps you signed in (for up to 30 days)
  - period: null
    scope: AI request records
    text: We do not keep what you sent.
  rights:
  - right: access and copy
    text: You can ask for a copy of your data
  - right: deletion
    text: or for your account and workspaces to be deleted at any time
  - right: complaint to supervisory authority
    text: 'EU/EEA users have the rights provided by the GDPR, including complaint to a supervisory authority (in Sweden: IMY).'
  role:
    text: chartlink.app is operated by Oscar Österberg, sole proprietor, Sweden.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: No advertising, no sale of data, no profiles.
  subprocessors:
    text: Who processes data for us Vercel (hosting and CDN), Neon (database), Resend (sign-in emails), Google (if you sign in with it), OpenRouter and the AI model providers it routes to (the AI features), and Paddle (payments).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Chartlink
provenance_date: '2026-11-09'
provider_name: Chartlink
provider_slug: chartlink-app
slug: chartlink-app-privacy-policy
source_date: '2026-11-09'
source_filename: chartlink-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://chartlink.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Chartlink\naid: chartlink-app\nurl: https://chartlink.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: chartlink.app is operated by Oscar Österberg, sole proprietor, Sweden.\ndata_categories:\n- category: identifying\n  text: your email address and, if you give one, your name\n- category: contact\n  text: your email address and, if you give one, your name\n- category: device\n  text: standard server logs including IP addresses, kept for operations and abuse prevention\n- category: behavioral\n  text: events (which workspace did what, when)\n- category: financial\n  text: We never\
  \ see card numbers or payment details — payments are processed entirely by Paddle.com as merchant\n    of record\npurposes:\n- purpose: run the service\n  text: We look at a workspace's brands and charts, drafts included, only to run the service\n- purpose: operations and abuse prevention\n  text: standard server logs including IP addresses, kept for operations and abuse prevention\n- purpose: sign-in\n  text: Signing in is by a link sent to that address or with Google\nretention:\n- scope: session cookie\n  period: up to 30 days\n  text: a session cookie keeps you signed in (for up to 30 days)\n- scope: AI request records\n  period: null\n  text: We do not keep what you sent.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Who processes data for us Vercel (hosting and CDN), Neon (database), Resend (sign-in emails), Google (if\n    you sign in with it), OpenRouter and the AI model providers it routes to (the AI features), and Paddle (payments).\ndpa:\n  available: null\n\
  \  url: null\n  text: null\ndeletion:\n  route: email support@chartlink.app from the address you sign in with\n  text: 'You can ask for a copy of your data or for your account and workspaces to be deleted at any time: email\n    support@chartlink.app from the address you sign in with.'\nrights:\n- right: access and copy\n  text: You can ask for a copy of your data\n- right: deletion\n  text: or for your account and workspaces to be deleted at any time\n- right: complaint to supervisory authority\n  text: 'EU/EEA users have the rights provided by the GDPR, including complaint to a supervisory authority (in Sweden:\n    IMY).'\nsale_or_sharing:\n  stance: prohibited\n  text: No advertising, no sale of data, no profiles.\n"
source_yaml_url: https://artifacts.apis.io/chartlink-app/privacy/chartlink-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Chartlink's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Charts
- Branding
- Artificial Intelligence
- Marketing
- Visualization
---
