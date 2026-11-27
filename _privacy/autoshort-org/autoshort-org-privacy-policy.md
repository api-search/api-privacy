---
api_specs:
- filename: autoshort-org-account-api-openapi.yml
  format: yaml
  label: AutoShort Account API
  slug: autoshort-org-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoshort-org/openapi/autoshort-org-account-api-openapi.yml
- filename: autoshort-org-catalog-api-openapi.yml
  format: yaml
  label: AutoShort Catalog API
  slug: autoshort-org-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoshort-org/openapi/autoshort-org-catalog-api-openapi.yml
- filename: autoshort-org-drafts-api-openapi.yml
  format: yaml
  label: AutoShort Drafts API
  slug: autoshort-org-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoshort-org/openapi/autoshort-org-drafts-api-openapi.yml
- filename: autoshort-org-motion-api-openapi.yml
  format: yaml
  label: AutoShort Motion API
  slug: autoshort-org-motion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoshort-org/openapi/autoshort-org-motion-api-openapi.yml
- filename: autoshort-org-pay-per-call-x402-api-openapi.yml
  format: yaml
  label: AutoShort Pay per call (x402) API
  slug: autoshort-org-pay-per-call-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoshort-org/openapi/autoshort-org-pay-per-call-x402-api-openapi.yml
- filename: autoshort-org-series-api-openapi.yml
  format: yaml
  label: AutoShort Series API
  slug: autoshort-org-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoshort-org/openapi/autoshort-org-series-api-openapi.yml
- filename: autoshort-org-videos-api-openapi.yml
  format: yaml
  label: AutoShort Videos API
  slug: autoshort-org-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoshort-org/openapi/autoshort-org-videos-api-openapi.yml
- filename: autoshort-org-webhooks-api-openapi.yml
  format: yaml
  label: AutoShort Webhooks API
  slug: autoshort-org-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autoshort-org/openapi/autoshort-org-webhooks-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address Name (if provided) Authentication credentials Profile information
  - category: behavioral
    text: Page and screen views, feature interactions, and referral information
  - category: device
    text: Browser, device, and operating system information
  - category: communication
    text: Session recordings used to understand and improve product experience
  - category: financial
    text: We do not store full payment card details; the provider processes payment and billing information under its own terms and privacy policy.
  deletion:
    route: Data Deletion page and privacy@autoshort.org
    text: To exercise these rights, contact us at privacy@autoshort.org . Step-by-step deletion instructions, including for data from connected platforms, are on our Data Deletion page .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve service
    text: Provide and improve our AI video generation service
  - purpose: Process payments
    text: Process your payments and manage subscriptions
  - purpose: Customer support
    text: Provide customer support and respond to inquiries
  - purpose: Fraud prevention and security
    text: Prevent fraud and ensure platform security
  - purpose: Legal compliance
    text: Comply with legal obligations
  residency:
  - region: Singapore
    text: Your data is stored on servers we rent from DigitalOcean in Singapore.
  retention:
  - period: Until you delete your account
    scope: Account data
    text: 'Account data: Until you delete your account'
  - period: Until you delete them or close your account
    scope: Generated videos
    text: 'Generated videos: Until you delete them or close your account'
  - period: Only as long as required by law
    scope: Payment records
    text: 'Payment records: Only as long as required by law'
  - period: 90 days
    scope: Moderation log
    text: For every image we check, we keep a log entry for 90 days
  rights:
  - right: Access
    text: Access - Request a copy of your personal data
  - right: Correction
    text: Correction - Update or correct inaccurate information
  - right: Deletion
    text: Deletion - Request deletion of your account and data
  - right: Export
    text: Export - Download your videos and content
  - right: Object
    text: Object - Opt-out of marketing communications
  - right: Portability
    text: Portability - Transfer your data to another service
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Opt-out of the sale of personal information (we do not sell your data)
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We ensure appropriate safeguards are in place to protect your data in compliance with applicable laws.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AutoShort
provenance_date: '2026-11-09'
provider_name: AutoShort
provider_slug: autoshort-org
slug: autoshort-org-privacy-policy
source_date: '2026-11-09'
source_filename: autoshort-org-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://autoshort.org/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AutoShort\naid: autoshort-org\nurl: https://autoshort.org/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address Name (if provided) Authentication credentials Profile information\n- category: behavioral\n  text: Page and screen views, feature interactions, and referral information\n- category: device\n  text: Browser, device, and operating system information\n- category: communication\n  text: Session recordings used to understand and improve product experience\n- category: financial\n  text: We do not store full payment\
  \ card details; the provider processes payment and billing information under\n    its own terms and privacy policy.\npurposes:\n- purpose: Provide and improve service\n  text: Provide and improve our AI video generation service\n- purpose: Process payments\n  text: Process your payments and manage subscriptions\n- purpose: Customer support\n  text: Provide customer support and respond to inquiries\n- purpose: Fraud prevention and security\n  text: Prevent fraud and ensure platform security\n- purpose: Legal compliance\n  text: Comply with legal obligations\nretention:\n- scope: Account data\n  period: Until you delete your account\n  text: 'Account data: Until you delete your account'\n- scope: Generated videos\n  period: Until you delete them or close your account\n  text: 'Generated videos: Until you delete them or close your account'\n- scope: Payment records\n  period: Only as long as required by law\n  text: 'Payment records: Only as long as required by law'\n- scope: Moderation log\n\
  \  period: 90 days\n  text: For every image we check, we keep a log entry for 90 days\nresidency:\n- region: Singapore\n  text: Your data is stored on servers we rent from DigitalOcean in Singapore.\ntransfers:\n- mechanism: other\n  text: We ensure appropriate safeguards are in place to protect your data in compliance with applicable laws.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Data Deletion page and privacy@autoshort.org\n  text: To exercise these rights, contact us at privacy@autoshort.org . Step-by-step deletion instructions, including\n    for data from connected platforms, are on our Data Deletion page .\nrights:\n- right: Access\n  text: Access - Request a copy of your personal data\n- right: Correction\n  text: Correction - Update or correct inaccurate information\n- right: Deletion\n  text: Deletion - Request deletion of your account and data\n- right: Export\n  text: Export - Download your videos and\
  \ content\n- right: Object\n  text: Object - Opt-out of marketing communications\n- right: Portability\n  text: Portability - Transfer your data to another service\nsale_or_sharing:\n  stance: prohibited\n  text: Opt-out of the sale of personal information (we do not sell your data)\n"
source_yaml_url: https://artifacts.apis.io/autoshort-org/privacy/autoshort-org-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from AutoShort's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Video Generation
- YouTube Shorts
- Automation
- Faceless Content
---
