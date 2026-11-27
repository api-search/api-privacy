---
api_specs:
- filename: citoapi-bkfc-api-openapi.yml
  format: yaml
  label: Cito CS2 API BKFC API
  slug: citoapi-bkfc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citoapi/openapi/citoapi-bkfc-api-openapi.yml
- filename: citoapi-call-of-duty-api-openapi.yml
  format: yaml
  label: Cito CS2 API Call of Duty API
  slug: citoapi-call-of-duty-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citoapi/openapi/citoapi-call-of-duty-api-openapi.yml
- filename: citoapi-cs2-api-openapi.yml
  format: yaml
  label: Cito CS2 API CS2 API
  slug: citoapi-cs2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citoapi/openapi/citoapi-cs2-api-openapi.yml
- filename: citoapi-dota-2-api-openapi.yml
  format: yaml
  label: Cito CS2 API Dota 2 API
  slug: citoapi-dota-2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citoapi/openapi/citoapi-dota-2-api-openapi.yml
- filename: citoapi-fortnite-api-openapi.yml
  format: yaml
  label: Cito CS2 API Fortnite API
  slug: citoapi-fortnite-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citoapi/openapi/citoapi-fortnite-api-openapi.yml
- filename: citoapi-qr-code-api-openapi.yml
  format: yaml
  label: Cito CS2 API QR Code API
  slug: citoapi-qr-code-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citoapi/openapi/citoapi-qr-code-api-openapi.yml
- filename: citoapi-raf-wrestling-api-openapi.yml
  format: yaml
  label: Cito CS2 API RAF Wrestling API
  slug: citoapi-raf-wrestling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citoapi/openapi/citoapi-raf-wrestling-api-openapi.yml
- filename: citoapi-tennis-api-openapi.yml
  format: yaml
  label: Cito CS2 API Tennis API
  slug: citoapi-tennis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citoapi/openapi/citoapi-tennis-api-openapi.yml
- filename: citoapi-ufc-api-openapi.yml
  format: yaml
  label: Cito CS2 API UFC API
  slug: citoapi-ufc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citoapi/openapi/citoapi-ufc-api-openapi.yml
- filename: citoapi-utility-api-openapi.yml
  format: yaml
  label: Cito CS2 API Utility API
  slug: citoapi-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citoapi/openapi/citoapi-utility-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your email address and authentication information (via Google or GitHub OAuth)
  - category: financial
    text: We receive only the last 4 digits and expiration date for your records.
  - category: behavioral
    text: We collect data about your API usage, including request counts, endpoints accessed, and response times.
  deletion:
    route: email privacy@citoapi.com
    text: You can request deletion of your account and associated data by contacting us at privacy@citoapi.com. We will process requests within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service delivery
    text: We use your information to provide, maintain, and improve the Cito API service, including authenticating your API requests and tracking usage against your plan limits.
  - purpose: service emails
    text: We may send you service-related emails such as account verification, billing notifications, security alerts, and important updates.
  - purpose: analytics
    text: We use aggregated, anonymized usage data to understand how developers use our API and to prioritize new features and improvements.
  - purpose: advertising measurement
    text: We use Google Ads and Microsoft Advertising (Universal Event Tracking) tags to measure whether our ads lead to sign-ups and paid plans.
  retention:
  - period: as long as your account is active
    scope: account data
    text: We retain your account data for as long as your account is active.
  - period: up to 90 days
    scope: after account deletion
    text: After account deletion, we retain certain data for up to 90 days for legal and accounting purposes.
  - period: 30 days
    scope: API logs
    text: API request logs are retained for 30 days for debugging and analytics purposes, after which they are automatically deleted.
  rights:
  - right: access and export
    text: You can access and export your data at any time through your dashboard settings.
  - right: deletion
    text: You can request deletion of your account and associated data by contacting us at privacy@citoapi.com.
  - right: correction
    text: You can update your account information at any time through your dashboard.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or trade your personal information to third parties for marketing purposes.
  subprocessors:
    text: 'We use trusted third-party services: Firebase (authentication and hosting), Stripe (payments), and standard analytics tools.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cito CS2 API
provenance_date: '2026-11-09'
provider_name: Cito CS2 API
provider_slug: citoapi
slug: citoapi-privacy-policy
source_date: '2026-11-09'
source_filename: citoapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://citoapi.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cito CS2 API\naid: citoapi\nurl: https://citoapi.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we collect your email address and authentication information (via Google or GitHub OAuth)\n- category: financial\n  text: We receive only the last 4 digits and expiration date for your records.\n- category: behavioral\n  text: We collect data about your API usage, including request counts, endpoints accessed, and response times.\npurposes:\n- purpose: service delivery\n  text: We use your information to provide, maintain, and improve\
  \ the Cito API service, including authenticating\n    your API requests and tracking usage against your plan limits.\n- purpose: service emails\n  text: We may send you service-related emails such as account verification, billing notifications, security alerts,\n    and important updates.\n- purpose: analytics\n  text: We use aggregated, anonymized usage data to understand how developers use our API and to prioritize new\n    features and improvements.\n- purpose: advertising measurement\n  text: We use Google Ads and Microsoft Advertising (Universal Event Tracking) tags to measure whether our ads lead\n    to sign-ups and paid plans.\nretention:\n- scope: account data\n  period: as long as your account is active\n  text: We retain your account data for as long as your account is active.\n- scope: after account deletion\n  period: up to 90 days\n  text: After account deletion, we retain certain data for up to 90 days for legal and accounting purposes.\n- scope: API logs\n  period: 30 days\n\
  \  text: API request logs are retained for 30 days for debugging and analytics purposes, after which they are automatically\n    deleted.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We use trusted third-party services: Firebase (authentication and hosting), Stripe (payments), and standard\n    analytics tools.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email privacy@citoapi.com\n  text: You can request deletion of your account and associated data by contacting us at privacy@citoapi.com. We\n    will process requests within 30 days.\nrights:\n- right: access and export\n  text: You can access and export your data at any time through your dashboard settings.\n- right: deletion\n  text: You can request deletion of your account and associated data by contacting us at privacy@citoapi.com.\n- right: correction\n  text: You can update your account information at any time through your dashboard.\nsale_or_sharing:\n  stance: prohibited\n \
  \ text: We do not sell, rent, or trade your personal information to third parties for marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/citoapi/privacy/citoapi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Cito CS2 API's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Esports
- Gaming
- Data
---
