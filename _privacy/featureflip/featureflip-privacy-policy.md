---
api_specs:
- filename: featureflip-client-sdk-api-openapi.yml
  format: yaml
  label: Featureflip Client SDK API
  slug: featureflip-client-sdk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/featureflip/openapi/featureflip-client-sdk-api-openapi.yml
- filename: featureflip-environments-api-openapi.yml
  format: yaml
  label: Featureflip Environments API
  slug: featureflip-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/featureflip/openapi/featureflip-environments-api-openapi.yml
- filename: featureflip-feature-flags-api-openapi.yml
  format: yaml
  label: Featureflip Feature Flags API
  slug: featureflip-feature-flags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/featureflip/openapi/featureflip-feature-flags-api-openapi.yml
- filename: featureflip-me-api-openapi.yml
  format: yaml
  label: Featureflip Me API
  slug: featureflip-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/featureflip/openapi/featureflip-me-api-openapi.yml
- filename: featureflip-organizations-api-openapi.yml
  format: yaml
  label: Featureflip Organizations API
  slug: featureflip-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/featureflip/openapi/featureflip-organizations-api-openapi.yml
- filename: featureflip-projects-api-openapi.yml
  format: yaml
  label: Featureflip Projects API
  slug: featureflip-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/featureflip/openapi/featureflip-projects-api-openapi.yml
- filename: featureflip-sdk-keys-api-openapi.yml
  format: yaml
  label: Featureflip SDK Keys API
  slug: featureflip-sdk-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/featureflip/openapi/featureflip-sdk-keys-api-openapi.yml
- filename: featureflip-server-sdk-api-openapi.yml
  format: yaml
  label: Featureflip Server SDK API
  slug: featureflip-server-sdk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/featureflip/openapi/featureflip-server-sdk-api-openapi.yml
- filename: featureflip-user-segments-api-openapi.yml
  format: yaml
  label: Featureflip User Segments API
  slug: featureflip-user-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/featureflip/openapi/featureflip-user-segments-api-openapi.yml
- filename: featureflip-webhooks-api-openapi.yml
  format: yaml
  label: Featureflip Webhooks API
  slug: featureflip-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/featureflip/openapi/featureflip-webhooks-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: Your name, email address, and hashed password when you create an account.'
  - category: financial
    text: 'Billing information: If you subscribe to a paid plan, payment processing is handled by Stripe.'
  - category: behavioral
    text: 'Usage analytics: With your consent, we run Google Analytics both on our marketing site and inside the Featureflip app, and we run Microsoft Clarity on the marketing site alone, to see how visitors move through each.'
  - category: other
    text: 'Evaluation context: When your applications evaluate feature flags through our SDKs, you may pass user attributes (such as user IDs or email addresses) as evaluation context.'
  - category: other
    text: 'Audit logs: We record administrative actions (flag changes, environment updates) for security and compliance purposes.'
  deletion:
    route: 'Account settings: request account deletion'
    text: 'Delete your data: Request account deletion from your account settings.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and maintain service
    text: To provide and maintain the Featureflip service
  - purpose: process payments
    text: To process payments through Stripe
  - purpose: product improvement analytics
    text: To improve our product through aggregated usage analytics
  residency:
  - region: European Union
    text: Our infrastructure is hosted in the European Union (Hetzner Cloud, EU region).
  - region: European Union
    text: Regardless of where you access Featureflip from, your data is stored and processed in the EU.
  retention:
  - period: as long as your account is active
    scope: personal data of active accounts
    text: We retain your personal data for as long as your account is active.
  - period: 30-day grace period
    scope: deleted accounts
    text: When you delete your account, personal data is permanently removed after a 30-day grace period (during which you can recover your account).
  - period: null
    scope: audit logs
    text: Audit logs are anonymized upon account deletion.
  rights:
  - right: access
    text: 'Access your data: Export a copy of your personal data from your account settings.'
  - right: deletion
    text: 'Delete your data: Request account deletion from your account settings.'
  - right: opt out of analytics
    text: 'Opt out of analytics: Withdraw consent at any time'
  - right: correction
    text: 'Correct your data: Update your name and email from your profile page.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Hetzner — Cloud infrastructure and self-hosted PostgreSQL database (EU region)
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Featureflip
provenance_date: '2026-11-09'
provider_name: Featureflip
provider_slug: featureflip
slug: featureflip-privacy-policy
source_date: '2026-11-09'
source_filename: featureflip-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://featureflip.io/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Featureflip\naid: featureflip\nurl: https://featureflip.io/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account information: Your name, email address, and hashed password when you create an account.'\n- category: financial\n  text: 'Billing information: If you subscribe to a paid plan, payment processing is handled by Stripe.'\n- category: behavioral\n  text: 'Usage analytics: With your consent, we run Google Analytics both on our marketing site and inside the Featureflip\n    app, and we run Microsoft Clarity on the marketing\
  \ site alone, to see how visitors move through each.'\n- category: other\n  text: 'Evaluation context: When your applications evaluate feature flags through our SDKs, you may pass user attributes\n    (such as user IDs or email addresses) as evaluation context.'\n- category: other\n  text: 'Audit logs: We record administrative actions (flag changes, environment updates) for security and compliance\n    purposes.'\npurposes:\n- purpose: provide and maintain service\n  text: To provide and maintain the Featureflip service\n- purpose: process payments\n  text: To process payments through Stripe\n- purpose: product improvement analytics\n  text: To improve our product through aggregated usage analytics\nretention:\n- scope: personal data of active accounts\n  period: as long as your account is active\n  text: We retain your personal data for as long as your account is active.\n- scope: deleted accounts\n  period: 30-day grace period\n  text: When you delete your account, personal data is permanently\
  \ removed after a 30-day grace period (during which\n    you can recover your account).\n- scope: audit logs\n  period: null\n  text: Audit logs are anonymized upon account deletion.\nresidency:\n- region: European Union\n  text: Our infrastructure is hosted in the European Union (Hetzner Cloud, EU region).\n- region: European Union\n  text: Regardless of where you access Featureflip from, your data is stored and processed in the EU.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Hetzner — Cloud infrastructure and self-hosted PostgreSQL database (EU region)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: 'Account settings: request account deletion'\n  text: 'Delete your data: Request account deletion from your account settings.'\nrights:\n- right: access\n  text: 'Access your data: Export a copy of your personal data from your account settings.'\n- right: deletion\n  text: 'Delete your data: Request account deletion from your account settings.'\n- right:\
  \ opt out of analytics\n  text: 'Opt out of analytics: Withdraw consent at any time'\n- right: correction\n  text: 'Correct your data: Update your name and email from your profile page.'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/featureflip/privacy/featureflip-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
summary_line: 19 quoted statements, read from Featureflip's own page on 2026-11-09.
synthetic: false
tags:
- Feature Flags
- Feature Management
- feature flag cleanup
- Progressive Delivery
- Experimentation
- feature flags as code
- OpenFeature
- MCP
- Developer Tools
- DevOps/CI-CD
---
