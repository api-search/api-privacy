---
api_specs:
- filename: alphabotpro-cloud-checkout-api-openapi.yml
  format: yaml
  label: AlphaBotPro Checkout API
  slug: alphabotpro-cloud-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphabotpro-cloud/openapi/alphabotpro-cloud-checkout-api-openapi.yml
- filename: alphabotpro-cloud-ea-api-openapi.yml
  format: yaml
  label: AlphaBotPro Ea API
  slug: alphabotpro-cloud-ea-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphabotpro-cloud/openapi/alphabotpro-cloud-ea-api-openapi.yml
- filename: alphabotpro-cloud-expert-advisors-api-openapi.yml
  format: yaml
  label: AlphaBotPro Expert Advisors API
  slug: alphabotpro-cloud-expert-advisors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphabotpro-cloud/openapi/alphabotpro-cloud-expert-advisors-api-openapi.yml
- filename: alphabotpro-cloud-mcp-api-openapi.yml
  format: yaml
  label: AlphaBotPro MCP API
  slug: alphabotpro-cloud-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphabotpro-cloud/openapi/alphabotpro-cloud-mcp-api-openapi.yml
- filename: alphabotpro-cloud-signals-api-openapi.yml
  format: yaml
  label: AlphaBotPro Signals API
  slug: alphabotpro-cloud-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphabotpro-cloud/openapi/alphabotpro-cloud-signals-api-openapi.yml
- filename: alphabotpro-cloud-stocks-api-openapi.yml
  format: yaml
  label: AlphaBotPro Stocks API
  slug: alphabotpro-cloud-stocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphabotpro-cloud/openapi/alphabotpro-cloud-stocks-api-openapi.yml
- filename: alphabotpro-cloud-warroom-api-openapi.yml
  format: yaml
  label: AlphaBotPro Warroom API
  slug: alphabotpro-cloud-warroom-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alphabotpro-cloud/openapi/alphabotpro-cloud-warroom-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: Name, email address, and password when you create an account.'
  - category: financial
    text: 'Payment information: Subscription and purchase transactions processed via Apple In-App Purchase (iOS) or Stripe (web).'
  - category: behavioral
    text: 'Usage data: App usage, pages visited, device type, and analytics data collected via Google Analytics and Microsoft Clarity.'
  - category: device
    text: 'Push notification token: Device token for delivering trading signal alerts.'
  - category: communication
    text: 'Communication data: Messages sent via our support email.'
  - category: other
    text: 'Profile data: Trader type and preferences you set in the app.'
  deletion:
    route: Request deletion via contact email
    text: Request deletion of your account and data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide signals and platform features
    text: To provide trading signals, MT5 bot tools, and platform features.
  - purpose: Process subscriptions
    text: To process subscriptions and send receipts and billing updates.
  - purpose: Push notifications
    text: To send push notifications for new signals and market alerts (with your permission).
  - purpose: Improve services
    text: To improve our app, website, and services.
  - purpose: Legal compliance
    text: To comply with legal obligations.
  retention:
  - period: as long as your account is active
    scope: Account data
    text: We retain your account data for as long as your account is active.
  - period: 30 days
    scope: Deleted account data
    text: If you delete your account, we remove your personal data within 30 days, except where required by law for financial records.
  rights:
  - right: Access
    text: Access, update, or correct your personal data.
  - right: Deletion
    text: Request deletion of your account and data.
  - right: Opt out of marketing
    text: Opt out of marketing communications.
  - right: Disable push notifications
    text: Disable push notifications via device settings.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AlphaBotPro
provenance_date: '2026-11-09'
provider_name: AlphaBotPro
provider_slug: alphabotpro-cloud
slug: alphabotpro-cloud-privacy-policy
source_date: '2026-11-09'
source_filename: alphabotpro-cloud-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://alphabotpro.cloud/pages/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AlphaBotPro\naid: alphabotpro-cloud\nurl: https://alphabotpro.cloud/pages/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account information: Name, email address, and password when you create an account.'\n- category: financial\n  text: 'Payment information: Subscription and purchase transactions processed via Apple In-App Purchase (iOS) or\n    Stripe (web).'\n- category: behavioral\n  text: 'Usage data: App usage, pages visited, device type, and analytics data collected via Google Analytics and\n    Microsoft Clarity.'\n- category:\
  \ device\n  text: 'Push notification token: Device token for delivering trading signal alerts.'\n- category: communication\n  text: 'Communication data: Messages sent via our support email.'\n- category: other\n  text: 'Profile data: Trader type and preferences you set in the app.'\npurposes:\n- purpose: Provide signals and platform features\n  text: To provide trading signals, MT5 bot tools, and platform features.\n- purpose: Process subscriptions\n  text: To process subscriptions and send receipts and billing updates.\n- purpose: Push notifications\n  text: To send push notifications for new signals and market alerts (with your permission).\n- purpose: Improve services\n  text: To improve our app, website, and services.\n- purpose: Legal compliance\n  text: To comply with legal obligations.\nretention:\n- scope: Account data\n  period: as long as your account is active\n  text: We retain your account data for as long as your account is active.\n- scope: Deleted account data\n  period:\
  \ 30 days\n  text: If you delete your account, we remove your personal data within 30 days, except where required by law for\n    financial records.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion via contact email\n  text: Request deletion of your account and data.\nrights:\n- right: Access\n  text: Access, update, or correct your personal data.\n- right: Deletion\n  text: Request deletion of your account and data.\n- right: Opt out of marketing\n  text: Opt out of marketing communications.\n- right: Disable push notifications\n  text: Disable push notifications via device settings.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/alphabotpro-cloud/privacy/alphabotpro-cloud-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from AlphaBotPro's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Trading
- Automation
- Signals
- MT5
- PropFirm
---
