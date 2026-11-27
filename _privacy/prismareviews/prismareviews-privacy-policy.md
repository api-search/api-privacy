---
api_specs:
- filename: prismareviews-connections-api-openapi.yml
  format: yaml
  label: Prisma Reviews Connections API
  slug: prismareviews-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prismareviews/openapi/prismareviews-connections-api-openapi.yml
- filename: prismareviews-locations-api-openapi.yml
  format: yaml
  label: Prisma Reviews Locations API
  slug: prismareviews-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prismareviews/openapi/prismareviews-locations-api-openapi.yml
- filename: prismareviews-platforms-api-openapi.yml
  format: yaml
  label: Prisma Reviews Platforms API
  slug: prismareviews-platforms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prismareviews/openapi/prismareviews-platforms-api-openapi.yml
- filename: prismareviews-replies-api-openapi.yml
  format: yaml
  label: Prisma Reviews Replies API
  slug: prismareviews-replies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prismareviews/openapi/prismareviews-replies-api-openapi.yml
- filename: prismareviews-reviews-api-openapi.yml
  format: yaml
  label: Prisma Reviews Reviews API
  slug: prismareviews-reviews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prismareviews/openapi/prismareviews-reviews-api-openapi.yml
- filename: prismareviews-stats-api-openapi.yml
  format: yaml
  label: Prisma Reviews Stats API
  slug: prismareviews-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prismareviews/openapi/prismareviews-stats-api-openapi.yml
- filename: prismareviews-usage-api-openapi.yml
  format: yaml
  label: Prisma Reviews Usage API
  slug: prismareviews-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prismareviews/openapi/prismareviews-usage-api-openapi.yml
- filename: prismareviews-webhooks-api-openapi.yml
  format: yaml
  label: Prisma Reviews Webhooks API
  slug: prismareviews-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prismareviews/openapi/prismareviews-webhooks-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, password (stored only as a hash by our authentication system, never in plain text)
  - category: contact
    text: Name, email address, password (stored only as a hash by our authentication system, never in plain text)
  - category: financial
    text: Billing name, address, VAT number, payment status (card details are handled by Stripe, not by us)
  - category: location
    text: approximate location (country, region, city from your connection, never your IP address)
  - category: behavioral
    text: Pages you view on prismareviews.com, how you arrived (search engine, AI assistant, website or campaign link), clicks on buttons and code examples, time on page, scroll depth
  - category: device
    text: IP address, request timestamps, endpoints called, error codes, request IDs
  - category: communication
    text: The text of the replies you publish through Prisma and their dates
  - category: professional
    text: Company and role, if you shared them with us (for example in our former early-access form, billing or support)
  - category: other
    text: Review content Rating, review text, reviewer display name, review date, review URL
  deletion:
    route: Email privacy@prismareviews.com from the address on your account, or disconnect a location with the API (DELETE /v1/connections/{id})
    text: To close your account and delete all your data, email privacy@prismareviews.com from the address on your account.
  dpa:
    available: true
    text: our Data Processing Agreement applies
    url: null
  purposes:
  - purpose: Create and run your account
    text: verify your email address, sign you in and keep you signed in, reset your password, issue and roll your API keys, and send account emails
  - purpose: Publish replies
    text: Publish, update and delete replies you request.
  - purpose: Billing and security
    text: Bill per connected location, prevent abuse, debug errors and secure the service.
  - purpose: Website analytics
    text: Understand who signs up and how they found us (onboarding answers and sign-up origin), to improve the product and measure our own marketing.
  residency:
  - region: European Union
    text: We store data in the European Union.
  retention:
  - period: Until you disconnect the location or app, or close your account
    scope: OAuth tokens and platform credentials
    text: Until you disconnect the location or app, or close your account. Then revoked and deleted immediately.
  - period: While the location is connected
    scope: Location metadata, reviews and replies
    text: While the location is connected. Deleted within 30 days after disconnection or account closure.
  - period: 7 to 90 days, depending on your plan
    scope: API and security logs
    text: API and security logs 7 to 90 days, depending on your plan.
  - period: 6 years
    scope: Invoices
    text: Invoices 6 years, as required by Spanish commercial law.
  - period: Overwritten within 30 days
    scope: Backups
    text: Backups Overwritten within 30 days.
  rights:
  - right: access
    text: you can request access, rectification, erasure, restriction, portability, and object to processing, and withdraw consent at any time
  - right: appeal
    text: review a decision we made about your request (appeal)
  - right: correction
    text: correct inaccurate personal information
  role:
    text: Controller (a “business” under US state privacy laws) for the data of our own customers and website visitors
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We don’t sell or share personal information.
  subprocessors:
    text: Subprocessors that host and run Prisma, listed on our Security page
    url: https://prismareviews.com/security
  transfers:
  - mechanism: DPF
    text: For those transfers we rely on the EU-US Data Privacy Framework where the provider is certified
  - mechanism: SCC
    text: or on the European Commission’s Standard Contractual Clauses plus supplementary measures.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Prisma Reviews
provenance_date: '2026-11-10'
provider_name: Prisma Reviews
provider_slug: prismareviews
slug: prismareviews-privacy-policy
source_date: '2026-11-10'
source_filename: prismareviews-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://prismareviews.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Prisma Reviews\naid: prismareviews\nurl: https://prismareviews.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Controller (a “business” under US state privacy laws) for the data of our own customers and website visitors\ndata_categories:\n- category: identifying\n  text: Name, email address, password (stored only as a hash by our authentication system, never in plain text)\n- category: contact\n  text: Name, email address, password (stored only as a hash by our authentication system, never in plain text)\n- category: financial\n  text: Billing name, address, VAT number, payment status\
  \ (card details are handled by Stripe, not by us)\n- category: location\n  text: approximate location (country, region, city from your connection, never your IP address)\n- category: behavioral\n  text: Pages you view on prismareviews.com, how you arrived (search engine, AI assistant, website or campaign link),\n    clicks on buttons and code examples, time on page, scroll depth\n- category: device\n  text: IP address, request timestamps, endpoints called, error codes, request IDs\n- category: communication\n  text: The text of the replies you publish through Prisma and their dates\n- category: professional\n  text: Company and role, if you shared them with us (for example in our former early-access form, billing or support)\n- category: other\n  text: Review content Rating, review text, reviewer display name, review date, review URL\npurposes:\n- purpose: Create and run your account\n  text: verify your email address, sign you in and keep you signed in, reset your password, issue and\
  \ roll your\n    API keys, and send account emails\n- purpose: Publish replies\n  text: Publish, update and delete replies you request.\n- purpose: Billing and security\n  text: Bill per connected location, prevent abuse, debug errors and secure the service.\n- purpose: Website analytics\n  text: Understand who signs up and how they found us (onboarding answers and sign-up origin), to improve the product\n    and measure our own marketing.\nretention:\n- scope: OAuth tokens and platform credentials\n  period: Until you disconnect the location or app, or close your account\n  text: Until you disconnect the location or app, or close your account. Then revoked and deleted immediately.\n- scope: Location metadata, reviews and replies\n  period: While the location is connected\n  text: While the location is connected. Deleted within 30 days after disconnection or account closure.\n- scope: API and security logs\n  period: 7 to 90 days, depending on your plan\n  text: API and security logs 7\
  \ to 90 days, depending on your plan.\n- scope: Invoices\n  period: 6 years\n  text: Invoices 6 years, as required by Spanish commercial law.\n- scope: Backups\n  period: Overwritten within 30 days\n  text: Backups Overwritten within 30 days.\nresidency:\n- region: European Union\n  text: We store data in the European Union.\ntransfers:\n- mechanism: DPF\n  text: For those transfers we rely on the EU-US Data Privacy Framework where the provider is certified\n- mechanism: SCC\n  text: or on the European Commission’s Standard Contractual Clauses plus supplementary measures.\nsubprocessors:\n  url: https://prismareviews.com/security\n  text: Subprocessors that host and run Prisma, listed on our Security page\ndpa:\n  available: true\n  url: null\n  text: our Data Processing Agreement applies\ndeletion:\n  route: Email privacy@prismareviews.com from the address on your account, or disconnect a location with the API\n    (DELETE /v1/connections/{id})\n  text: To close your account and delete\
  \ all your data, email privacy@prismareviews.com from the address on your\n    account.\nrights:\n- right: access\n  text: you can request access, rectification, erasure, restriction, portability, and object to processing, and\n    withdraw consent at any time\n- right: appeal\n  text: review a decision we made about your request (appeal)\n- right: correction\n  text: correct inaccurate personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We don’t sell or share personal information.\n"
source_yaml_url: https://artifacts.apis.io/prismareviews/privacy/prismareviews-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from Prisma Reviews's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Reviews
- Software-as-a-Service
- GDPR
- Spain
---
