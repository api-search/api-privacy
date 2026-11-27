---
api_specs:
- filename: marketsdk-buyers-api-openapi.yml
  format: yaml
  label: MarketSDK Buyers API
  slug: marketsdk-buyers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketsdk/openapi/marketsdk-buyers-api-openapi.yml
- filename: marketsdk-categories-api-openapi.yml
  format: yaml
  label: MarketSDK Categories API
  slug: marketsdk-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketsdk/openapi/marketsdk-categories-api-openapi.yml
- filename: marketsdk-listings-api-openapi.yml
  format: yaml
  label: MarketSDK Listings API
  slug: marketsdk-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketsdk/openapi/marketsdk-listings-api-openapi.yml
- filename: marketsdk-marketplace-api-openapi.yml
  format: yaml
  label: MarketSDK Marketplace API
  slug: marketsdk-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketsdk/openapi/marketsdk-marketplace-api-openapi.yml
- filename: marketsdk-moderation-api-openapi.yml
  format: yaml
  label: MarketSDK Moderation API
  slug: marketsdk-moderation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketsdk/openapi/marketsdk-moderation-api-openapi.yml
- filename: marketsdk-orders-api-openapi.yml
  format: yaml
  label: MarketSDK Orders API
  slug: marketsdk-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketsdk/openapi/marketsdk-orders-api-openapi.yml
- filename: marketsdk-payments-api-openapi.yml
  format: yaml
  label: MarketSDK Payments API
  slug: marketsdk-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketsdk/openapi/marketsdk-payments-api-openapi.yml
- filename: marketsdk-reputation-api-openapi.yml
  format: yaml
  label: MarketSDK Reputation API
  slug: marketsdk-reputation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketsdk/openapi/marketsdk-reputation-api-openapi.yml
- filename: marketsdk-reviews-api-openapi.yml
  format: yaml
  label: MarketSDK Reviews API
  slug: marketsdk-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketsdk/openapi/marketsdk-reviews-api-openapi.yml
- filename: marketsdk-search-api-openapi.yml
  format: yaml
  label: MarketSDK Search API
  slug: marketsdk-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketsdk/openapi/marketsdk-search-api-openapi.yml
- filename: marketsdk-sellers-api-openapi.yml
  format: yaml
  label: MarketSDK Sellers API
  slug: marketsdk-sellers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketsdk/openapi/marketsdk-sellers-api-openapi.yml
- filename: marketsdk-trust-api-openapi.yml
  format: yaml
  label: MarketSDK Trust API
  slug: marketsdk-trust-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketsdk/openapi/marketsdk-trust-api-openapi.yml
- filename: marketsdk-webhooks-api-openapi.yml
  format: yaml
  label: MarketSDK Webhooks API
  slug: marketsdk-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketsdk/openapi/marketsdk-webhooks-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: We collect your email address when you sign in
  - category: financial
    text: your billing country, postal code, and optional tax id when you subscribe
  - category: identifying
    text: If your identity is checked, the check is done by Stripe. We keep the result.
  deletion:
    route: email hello@marketsdk.com
    text: Email hello@marketsdk.com and we will act within thirty days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: providing the service
    text: Each handles data only to provide its service to us.
  retention:
  - period: as long as the workspace exists
    scope: active workspace
    text: We keep a workspace's data for as long as the workspace exists.
  - period: 90 days
    scope: after cancellation
    text: After cancellation we keep it for 90 days.
  - period: 7 days after deletion is requested
    scope: deleted workspace
    text: A deleted workspace is removed 7 days after deletion is requested.
  rights:
  - right: access
    text: You can ask what we hold about you
  - right: correction
    text: ask us to correct it
  - right: deletion
    text: ask us to delete it
  role:
    text: It controls that data, and we act on its instructions.
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share data with anyone for marketing.
  subprocessors:
    text: 'We use a small number of providers to run the service: Railway for hosting and the database, Cloudflare for DNS and file storage, Vercel for this website, Resend for email, and Stripe for payments.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MarketSDK
provenance_date: '2026-11-10'
provider_name: MarketSDK
provider_slug: marketsdk
slug: marketsdk-privacy-policy
source_date: '2026-11-10'
source_filename: marketsdk-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://marketsdk.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MarketSDK\naid: marketsdk\nurl: https://marketsdk.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: It controls that data, and we act on its instructions.\ndata_categories:\n- category: contact\n  text: We collect your email address when you sign in\n- category: financial\n  text: your billing country, postal code, and optional tax id when you subscribe\n- category: identifying\n  text: If your identity is checked, the check is done by Stripe. We keep the result.\npurposes:\n- purpose: providing the service\n  text: Each handles data only to provide its service to us.\nretention:\n\
  - scope: active workspace\n  period: as long as the workspace exists\n  text: We keep a workspace's data for as long as the workspace exists.\n- scope: after cancellation\n  period: 90 days\n  text: After cancellation we keep it for 90 days.\n- scope: deleted workspace\n  period: 7 days after deletion is requested\n  text: A deleted workspace is removed 7 days after deletion is requested.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We use a small number of providers to run the service: Railway for hosting and the database, Cloudflare\n    for DNS and file storage, Vercel for this website, Resend for email, and Stripe for payments.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@marketsdk.com\n  text: Email hello@marketsdk.com and we will act within thirty days.\nrights:\n- right: access\n  text: You can ask what we hold about you\n- right: correction\n  text: ask us to correct it\n- right: deletion\n  text: ask us to delete\
  \ it\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share data with anyone for marketing.\n"
source_yaml_url: https://artifacts.apis.io/marketsdk/privacy/marketsdk-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from MarketSDK's own page on 2026-11-10.
synthetic: false
tags:
- Marketplace
- Software-as-a-Service
- Payments
- Trust
---
