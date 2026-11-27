---
api_specs:
- filename: thrivecart-account-api-openapi.yml
  format: yaml
  label: ThriveCart Account API
  slug: thrivecart-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thrivecart/openapi/thrivecart-account-api-openapi.yml
- filename: thrivecart-affiliates-api-openapi.yml
  format: yaml
  label: ThriveCart Affiliates API
  slug: thrivecart-affiliates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thrivecart/openapi/thrivecart-affiliates-api-openapi.yml
- filename: thrivecart-bumps-api-openapi.yml
  format: yaml
  label: ThriveCart Bumps API
  slug: thrivecart-bumps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thrivecart/openapi/thrivecart-bumps-api-openapi.yml
- filename: thrivecart-customers-api-openapi.yml
  format: yaml
  label: ThriveCart Customers API
  slug: thrivecart-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thrivecart/openapi/thrivecart-customers-api-openapi.yml
- filename: thrivecart-downsells-api-openapi.yml
  format: yaml
  label: ThriveCart Downsells API
  slug: thrivecart-downsells-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thrivecart/openapi/thrivecart-downsells-api-openapi.yml
- filename: thrivecart-event-subscriptions-api-openapi.yml
  format: yaml
  label: ThriveCart Event subscriptions API
  slug: thrivecart-event-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thrivecart/openapi/thrivecart-event-subscriptions-api-openapi.yml
- filename: thrivecart-learn-api-openapi.yml
  format: yaml
  label: ThriveCart Learn API
  slug: thrivecart-learn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thrivecart/openapi/thrivecart-learn-api-openapi.yml
- filename: thrivecart-products-api-openapi.yml
  format: yaml
  label: ThriveCart Products API
  slug: thrivecart-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thrivecart/openapi/thrivecart-products-api-openapi.yml
- filename: thrivecart-subscriptions-api-openapi.yml
  format: yaml
  label: ThriveCart Subscriptions API
  slug: thrivecart-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thrivecart/openapi/thrivecart-subscriptions-api-openapi.yml
- filename: thrivecart-transactions-api-openapi.yml
  format: yaml
  label: ThriveCart Transactions API
  slug: thrivecart-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thrivecart/openapi/thrivecart-transactions-api-openapi.yml
- filename: thrivecart-upsells-api-openapi.yml
  format: yaml
  label: ThriveCart Upsells API
  slug: thrivecart-upsells-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thrivecart/openapi/thrivecart-upsells-api-openapi.yml
claim_count: 5
description: ''
doc:
  data_categories:
  - category: behavioral
    text: For the analysis, hCaptcha evaluates various information (e.g. IP address, how long the visitor has been on the website or app, or mouse movements made by the user).
  deletion:
    route: Cancel account/subscription; Content is deleted within a reasonable time
    text: All of your Content will be deleted from the Services within a reasonable time period from when you cancel your account/subscription.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Bot detection and fraud prevention
    text: Our vendors may optionally choose to use either Google reCAPTCHA or hCaptcha as browser-based bot detection tools to help prevent fraud.
  retention:
  - period: a reasonable time period
    scope: Customer Content after account cancellation
    text: All of your Content will be deleted from the Services within a reasonable time period from when you cancel your account/subscription.
  role:
    text: When accessing these pages, we are acting as a data processor in accordance with the instructions of our customer.
    value: processor
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
name: ThriveCart
provenance_date: '2026-11-10'
provider_name: ThriveCart
provider_slug: thrivecart
slug: thrivecart-privacy-policy
source_date: '2026-11-10'
source_filename: thrivecart-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://thrivecart.com/legal/thrivecart/?tab=privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ThriveCart\naid: thrivecart\nurl: https://thrivecart.com/legal/thrivecart/?tab=privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: When accessing these pages, we are acting as a data processor in accordance with the instructions of our\n    customer.\ndata_categories:\n- category: behavioral\n  text: For the analysis, hCaptcha evaluates various information (e.g. IP address, how long the visitor has been\n    on the website or app, or mouse movements made by the user).\npurposes:\n- purpose: Bot detection and fraud prevention\n  text: Our vendors may optionally choose to use either Google\
  \ reCAPTCHA or hCaptcha as browser-based bot detection\n    tools to help prevent fraud.\nretention:\n- scope: Customer Content after account cancellation\n  period: a reasonable time period\n  text: All of your Content will be deleted from the Services within a reasonable time period from when you cancel\n    your account/subscription.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Cancel account/subscription; Content is deleted within a reasonable time\n  text: All of your Content will be deleted from the Services within a reasonable time period from when you cancel\n    your account/subscription.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/thrivecart/privacy/thrivecart-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
summary_line: 5 quoted statements, read from ThriveCart's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Checkout
- Shopping Cart
- Payments
- E-Commerce
- Subscription
- Affiliate Marketing
- LMS
- Creator Economy
- Webhook
---
