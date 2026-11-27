---
api_specs:
- filename: clearlist-me-account-api-openapi.yml
  format: yaml
  label: ClearList Account API
  slug: clearlist-me-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearlist-me/openapi/clearlist-me-account-api-openapi.yml
- filename: clearlist-me-jobs-api-openapi.yml
  format: yaml
  label: ClearList Jobs API
  slug: clearlist-me-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearlist-me/openapi/clearlist-me-jobs-api-openapi.yml
- filename: clearlist-me-listings-api-openapi.yml
  format: yaml
  label: ClearList Listings API
  slug: clearlist-me-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearlist-me/openapi/clearlist-me-listings-api-openapi.yml
- filename: clearlist-me-onboarding-api-openapi.yml
  format: yaml
  label: ClearList Onboarding API
  slug: clearlist-me-onboarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearlist-me/openapi/clearlist-me-onboarding-api-openapi.yml
- filename: clearlist-me-orders-api-openapi.yml
  format: yaml
  label: ClearList Orders API
  slug: clearlist-me-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearlist-me/openapi/clearlist-me-orders-api-openapi.yml
- filename: clearlist-me-publishing-api-openapi.yml
  format: yaml
  label: ClearList Publishing API
  slug: clearlist-me-publishing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearlist-me/openapi/clearlist-me-publishing-api-openapi.yml
- filename: clearlist-me-scheduling-api-openapi.yml
  format: yaml
  label: ClearList Scheduling API
  slug: clearlist-me-scheduling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearlist-me/openapi/clearlist-me-scheduling-api-openapi.yml
- filename: clearlist-me-system-api-openapi.yml
  format: yaml
  label: ClearList System API
  slug: clearlist-me-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clearlist-me/openapi/clearlist-me-system-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account information: Email address for authentication and communication.'
  - category: location
    text: 'Location data: City and state you provide when publishing your sale page.'
  - category: communication
    text: 'Reservation data: Buyer email addresses and reservation details for item pickups.'
  - category: behavioral
    text: 'Usage data: How you interact with the app to improve our services'
  - category: other
    text: 'Listing data: Photos, descriptions, and pricing for items you list for sale.'
  deletion:
    route: account deletion request
    text: You may request complete deletion of your account and all associated data at any time.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Manage seller account
    text: To create and manage your seller account.
  - purpose: Generate listings
    text: To generate listings from your photos using automated analysis.
  - purpose: Reservations and communication
    text: To facilitate reservations and buyer-seller communication.
  - purpose: Make sale pages findable
    text: To make live sale pages findable by city.
  - purpose: Transactional email
    text: To send transactional emails (reservation confirmations, pickup scheduling).
  - purpose: Payments
    text: To process payments for premium features.
  retention:
  - period: duration of your active account
    scope: Account data
    text: Your data is retained for the duration of your active account.
  - period: 12 months
    scope: Analytics data (PostHog)
    text: Analytics data (PostHog) is automatically deleted after 12 months.
  - period: 90 days
    scope: Error reports (Sentry)
    text: Error reports (Sentry) are automatically deleted after 90 days.
  rights:
  - right: Access
    text: Access the personal data we hold about you.
  - right: Correction
    text: Request correction of inaccurate data.
  - right: Deletion
    text: Request deletion of your data and account.
  - right: Objection
    text: Decline analytics cookies (the platform works without them).
  - right: Portability
    text: You can also request data portability or restriction of processing.
  - right: Export
    text: Export your listing data.
  - right: Complaint
    text: Lodge a complaint with your local data protection authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: ClearList does not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: These providers use standard contractual clauses approved by the European Commission.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ClearList
provenance_date: '2026-11-09'
provider_name: ClearList
provider_slug: clearlist-me
slug: clearlist-me-privacy-policy
source_date: '2026-11-09'
source_filename: clearlist-me-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://clearlist.me/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ClearList\naid: clearlist-me\nurl: https://clearlist.me/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Account information: Email address for authentication and communication.'\n- category: location\n  text: 'Location data: City and state you provide when publishing your sale page.'\n- category: communication\n  text: 'Reservation data: Buyer email addresses and reservation details for item pickups.'\n- category: behavioral\n  text: 'Usage data: How you interact with the app to improve our services'\n- category: other\n  text: 'Listing\
  \ data: Photos, descriptions, and pricing for items you list for sale.'\npurposes:\n- purpose: Manage seller account\n  text: To create and manage your seller account.\n- purpose: Generate listings\n  text: To generate listings from your photos using automated analysis.\n- purpose: Reservations and communication\n  text: To facilitate reservations and buyer-seller communication.\n- purpose: Make sale pages findable\n  text: To make live sale pages findable by city.\n- purpose: Transactional email\n  text: To send transactional emails (reservation confirmations, pickup scheduling).\n- purpose: Payments\n  text: To process payments for premium features.\nretention:\n- scope: Account data\n  period: duration of your active account\n  text: Your data is retained for the duration of your active account.\n- scope: Analytics data (PostHog)\n  period: 12 months\n  text: Analytics data (PostHog) is automatically deleted after 12 months.\n- scope: Error reports (Sentry)\n  period: 90 days\n  text:\
  \ Error reports (Sentry) are automatically deleted after 90 days.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: These providers use standard contractual clauses approved by the European Commission.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion request\n  text: You may request complete deletion of your account and all associated data at any time.\nrights:\n- right: Access\n  text: Access the personal data we hold about you.\n- right: Correction\n  text: Request correction of inaccurate data.\n- right: Deletion\n  text: Request deletion of your data and account.\n- right: Objection\n  text: Decline analytics cookies (the platform works without them).\n- right: Portability\n  text: You can also request data portability or restriction of processing.\n- right: Export\n  text: Export your listing data.\n- right: Complaint\n  text: Lodge a complaint with your local data protection authority.\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: ClearList does not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/clearlist-me/privacy/clearlist-me-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from ClearList's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Resale
- Marketplace
- Automation
- E-Commerce
- Company
---
