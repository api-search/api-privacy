---
api_specs:
- filename: cartviral-com-account-api-openapi.yml
  format: yaml
  label: CartViral Account API
  slug: cartviral-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cartviral-com/openapi/cartviral-com-account-api-openapi.yml
- filename: cartviral-com-carousels-api-openapi.yml
  format: yaml
  label: CartViral Carousels API
  slug: cartviral-com-carousels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cartviral-com/openapi/cartviral-com-carousels-api-openapi.yml
- filename: cartviral-com-characters-api-openapi.yml
  format: yaml
  label: CartViral Characters API
  slug: cartviral-com-characters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cartviral-com/openapi/cartviral-com-characters-api-openapi.yml
- filename: cartviral-com-clips-api-openapi.yml
  format: yaml
  label: CartViral Clips API
  slug: cartviral-com-clips-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cartviral-com/openapi/cartviral-com-clips-api-openapi.yml
- filename: cartviral-com-create-api-openapi.yml
  format: yaml
  label: CartViral Create API
  slug: cartviral-com-create-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cartviral-com/openapi/cartviral-com-create-api-openapi.yml
- filename: cartviral-com-creations-api-openapi.yml
  format: yaml
  label: CartViral Creations API
  slug: cartviral-com-creations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cartviral-com/openapi/cartviral-com-creations-api-openapi.yml
- filename: cartviral-com-media-api-openapi.yml
  format: yaml
  label: CartViral Media API
  slug: cartviral-com-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cartviral-com/openapi/cartviral-com-media-api-openapi.yml
- filename: cartviral-com-offers-api-openapi.yml
  format: yaml
  label: CartViral Offers API
  slug: cartviral-com-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cartviral-com/openapi/cartviral-com-offers-api-openapi.yml
- filename: cartviral-com-photos-api-openapi.yml
  format: yaml
  label: CartViral Photos API
  slug: cartviral-com-photos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cartviral-com/openapi/cartviral-com-photos-api-openapi.yml
- filename: cartviral-com-pitches-api-openapi.yml
  format: yaml
  label: CartViral Pitches API
  slug: cartviral-com-pitches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cartviral-com/openapi/cartviral-com-pitches-api-openapi.yml
- filename: cartviral-com-products-api-openapi.yml
  format: yaml
  label: CartViral Products API
  slug: cartviral-com-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cartviral-com/openapi/cartviral-com-products-api-openapi.yml
- filename: cartviral-com-static-ads-api-openapi.yml
  format: yaml
  label: CartViral Static Ads API
  slug: cartviral-com-static-ads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cartviral-com/openapi/cartviral-com-static-ads-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (for sign-in codes and service emails), your language, and for abuse prevention the sign-up IP address and a technical device fingerprint.
  - category: behavioral
    text: the channel that first brought you here (for example a utm_source tag or the referring site, kept 60 days so we know which channels work)
  - category: financial
    text: your plan and credit ledger. Card data is handled by Stripe and never reaches us.
  - category: financial
    text: payouts and the payout destination you provide (PayPal email or USDT address)
  - category: device
    text: the browser user agent
  - category: contact
    text: Your handle and the social accounts you choose to show brands
  deletion:
    route: Request deletion in Account settings or by email
    text: Request deletion in Account settings or by email; we erase your data within 30 days, after paying out any earned balance and keeping only what the law requires (for example payment records).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: sign-in and service emails
    text: Email address (for sign-in codes and service emails)
  - purpose: abuse prevention
    text: for abuse prevention the sign-up IP address and a technical device fingerprint
  - purpose: attribute sales
    text: CartViral processes this data on the brand's behalf to attribute sales.
  - purpose: block self-purchases by generators
    text: a one-way hash of the buyer's email - used only to block generators from buying through their own links
  retention:
  - period: null
    scope: account data
    text: We keep account data while your account exists.
  - period: 90 days
    scope: tracking memory
    text: Tracking memory expires after 90 days
  - period: 60 days
    scope: raw tracking events
    text: raw tracking events after 60 days
  - period: 10 minutes
    scope: sign-in codes
    text: Sign-in codes are stored hashed and expire in 10 minutes.
  - period: one hour
    scope: access tokens
    text: Access tokens last one hour and refresh tokens 90 days
  rights:
  - right: access
    text: You can ask for access to your data, correction, deletion, restriction or a copy, and object to processing.
  - right: complaint to data protection authority
    text: You can also complain to your data protection authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Who helps us run the service.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CartViral
provenance_date: '2026-11-09'
provider_name: CartViral
provider_slug: cartviral-com
slug: cartviral-com-privacy-policy
source_date: '2026-11-09'
source_filename: cartviral-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://app.cartviral.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CartViral\naid: cartviral-com\nurl: https://app.cartviral.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address (for sign-in codes and service emails), your language, and for abuse prevention the sign-up\n    IP address and a technical device fingerprint.\n- category: behavioral\n  text: the channel that first brought you here (for example a utm_source tag or the referring site, kept 60 days\n    so we know which channels work)\n- category: financial\n  text: your plan and credit ledger. Card data is handled by Stripe\
  \ and never reaches us.\n- category: financial\n  text: payouts and the payout destination you provide (PayPal email or USDT address)\n- category: device\n  text: the browser user agent\n- category: contact\n  text: Your handle and the social accounts you choose to show brands\npurposes:\n- purpose: sign-in and service emails\n  text: Email address (for sign-in codes and service emails)\n- purpose: abuse prevention\n  text: for abuse prevention the sign-up IP address and a technical device fingerprint\n- purpose: attribute sales\n  text: CartViral processes this data on the brand's behalf to attribute sales.\n- purpose: block self-purchases by generators\n  text: a one-way hash of the buyer's email - used only to block generators from buying through their own links\nretention:\n- scope: account data\n  period: null\n  text: We keep account data while your account exists.\n- scope: tracking memory\n  period: 90 days\n  text: Tracking memory expires after 90 days\n- scope: raw tracking events\n\
  \  period: 60 days\n  text: raw tracking events after 60 days\n- scope: sign-in codes\n  period: 10 minutes\n  text: Sign-in codes are stored hashed and expire in 10 minutes.\n- scope: access tokens\n  period: one hour\n  text: Access tokens last one hour and refresh tokens 90 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Who helps us run the service.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion in Account settings or by email\n  text: Request deletion in Account settings or by email; we erase your data within 30 days, after paying out any\n    earned balance and keeping only what the law requires (for example payment records).\nrights:\n- right: access\n  text: You can ask for access to your data, correction, deletion, restriction or a copy, and object to processing.\n- right: complaint to data protection authority\n  text: You can also complain to your data protection authority.\nsale_or_sharing:\n  stance: unstated\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/cartviral-com/privacy/cartviral-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 19 quoted statements, read from CartViral's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- E-Commerce
- Video Generation
- Marketing
---
