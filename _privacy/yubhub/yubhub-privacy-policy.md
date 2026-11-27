---
api_specs:
- filename: yubhub-openapi-generated.yml
  format: yaml
  label: YubHub API
  slug: yubhub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yubhub/openapi/_ae-authored/yubhub-openapi-generated.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: email address and name, provided via our authentication provider (Clerk)
  - category: financial
    text: payment details are processed directly by Stripe and are never stored on our servers
  - category: behavioral
    text: 'Usage data: feed configurations, job counts, and feature usage to operate the Service'
  deletion:
    route: delete account
    text: When you delete your account, all associated data (feeds, jobs, usage records) is permanently removed.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate the Service
    text: We collect the minimum data necessary to provide the Service
  retention:
  - period: as long as your account is active
    scope: account data
    text: We retain your account data for as long as your account is active.
  - period: null
    scope: billing records
    text: Stripe may retain billing records as required by law.
  rights:
  - right: access
    text: Access the personal data we hold about you
  - right: correction
    text: Request correction of inaccurate data
  - right: deletion
    text: Request deletion of your data
  - right: objection
    text: Object to processing of your data
  - right: portability
    text: Request data portability
  role:
    text: YubHub is operated by Houtini Ltd (company number 16683235)
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not display, sell, or share your personal data with third parties for marketing purposes.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: YubHub
provenance_date: '2026-11-10'
provider_name: YubHub
provider_slug: yubhub
slug: yubhub-privacy-policy
source_date: '2026-11-10'
source_filename: yubhub-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://yubhub.co/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: YubHub\naid: yubhub\nurl: https://yubhub.co/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: YubHub is operated by Houtini Ltd (company number 16683235)\ndata_categories:\n- category: contact\n  text: email address and name, provided via our authentication provider (Clerk)\n- category: financial\n  text: payment details are processed directly by Stripe and are never stored on our servers\n- category: behavioral\n  text: 'Usage data: feed configurations, job counts, and feature usage to operate the Service'\npurposes:\n- purpose: operate the Service\n  text: We collect the minimum data\
  \ necessary to provide the Service\nretention:\n- scope: account data\n  period: as long as your account is active\n  text: We retain your account data for as long as your account is active.\n- scope: billing records\n  period: null\n  text: Stripe may retain billing records as required by law.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete account\n  text: When you delete your account, all associated data (feeds, jobs, usage records) is permanently removed.\nrights:\n- right: access\n  text: Access the personal data we hold about you\n- right: correction\n  text: Request correction of inaccurate data\n- right: deletion\n  text: Request deletion of your data\n- right: objection\n  text: Object to processing of your data\n- right: portability\n  text: Request data portability\nsale_or_sharing:\n  stance: prohibited\n  text: We do not display, sell, or share your personal data with third\
  \ parties for marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/yubhub/privacy/yubhub-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from YubHub's own page on 2026-11-10.
synthetic: false
tags:
- JobFeed
- Recruiting
- United Kingdom
- Data Enrichment
---
