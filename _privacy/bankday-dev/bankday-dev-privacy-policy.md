---
api_specs:
- filename: bankday-dev-account-api-openapi.yml
  format: yaml
  label: bankday-dev Account API
  slug: bankday-dev-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-account-api-openapi.yml
- filename: bankday-dev-ach-api-openapi.yml
  format: yaml
  label: bankday-dev Ach API
  slug: bankday-dev-ach-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-ach-api-openapi.yml
- filename: bankday-dev-business-day-api-openapi.yml
  format: yaml
  label: bankday-dev Business Day API
  slug: bankday-dev-business-day-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-business-day-api-openapi.yml
- filename: bankday-dev-business-days-api-openapi.yml
  format: yaml
  label: bankday-dev Business Days API
  slug: bankday-dev-business-days-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-business-days-api-openapi.yml
- filename: bankday-dev-calendars-api-openapi.yml
  format: yaml
  label: bankday-dev Calendars API
  slug: bankday-dev-calendars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-calendars-api-openapi.yml
- filename: bankday-dev-fx-api-openapi.yml
  format: yaml
  label: bankday-dev Fx API
  slug: bankday-dev-fx-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-fx-api-openapi.yml
- filename: bankday-dev-holidays-api-openapi.yml
  format: yaml
  label: bankday-dev Holidays API
  slug: bankday-dev-holidays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-holidays-api-openapi.yml
- filename: bankday-dev-minimum-wage-api-openapi.yml
  format: yaml
  label: bankday-dev Minimum Wage API
  slug: bankday-dev-minimum-wage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-minimum-wage-api-openapi.yml
- filename: bankday-dev-payroll-api-openapi.yml
  format: yaml
  label: bankday-dev Payroll API
  slug: bankday-dev-payroll-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-payroll-api-openapi.yml
- filename: bankday-dev-today-api-openapi.yml
  format: yaml
  label: bankday-dev Today API
  slug: bankday-dev-today-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankday-dev/openapi/bankday-dev-today-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account data: your email address and, for paid plans, billing details handled by Stripe (we never see full card numbers).'
  - category: financial
    text: billing details handled by Stripe (we never see full card numbers)
  - category: behavioral
    text: 'Usage data: request counts per API key per month, used for quotas and billing.'
  - category: identifying
    text: 'Playground: a salted hash of your IP address for 7 days to enforce the daily demo limit.'
  - category: location
    text: the places you chose
  deletion:
    route: email hello@bankday.dev
    text: To delete your account email hello@bankday.dev .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: quotas and billing
    text: 'Usage data: request counts per API key per month, used for quotas and billing.'
  - purpose: enforce daily demo limit
    text: 'Playground: a salted hash of your IP address for 7 days to enforce the daily demo limit.'
  - purpose: send minimum wage alerts
    text: We use them only to send those alerts, after you confirm, and you can stop them with the link in every email.
  - purpose: website analytics
    text: 'Website analytics: privacy-friendly, cookie-free aggregate analytics.'
  retention:
  - period: 7 days
    scope: playground IP hash
    text: a salted hash of your IP address for 7 days
  - period: null
    scope: query logs
    text: We do not log the dates or parameters you query beyond short-lived operational logs.
  - period: null
    scope: alert send record
    text: We keep a record of which alerts we sent so none goes out twice.
  rights:
  - right: stop minimum wage alerts
    text: you can stop them with the link in every email
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell personal data.
  subprocessors:
    text: 'Processors: Cloudflare (hosting), Stripe (payments), Resend (transactional email).'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: bankday-dev
provenance_date: '2026-11-09'
provider_name: bankday-dev
provider_slug: bankday-dev
slug: bankday-dev-privacy-policy
source_date: '2026-11-09'
source_filename: bankday-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bankday.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: bankday-dev\naid: bankday-dev\nurl: https://bankday.dev/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Account data: your email address and, for paid plans, billing details handled by Stripe (we never see full\n    card numbers).'\n- category: financial\n  text: billing details handled by Stripe (we never see full card numbers)\n- category: behavioral\n  text: 'Usage data: request counts per API key per month, used for quotas and billing.'\n- category: identifying\n  text: 'Playground: a salted hash of your IP address for 7 days to\
  \ enforce the daily demo limit.'\n- category: location\n  text: the places you chose\npurposes:\n- purpose: quotas and billing\n  text: 'Usage data: request counts per API key per month, used for quotas and billing.'\n- purpose: enforce daily demo limit\n  text: 'Playground: a salted hash of your IP address for 7 days to enforce the daily demo limit.'\n- purpose: send minimum wage alerts\n  text: We use them only to send those alerts, after you confirm, and you can stop them with the link in every email.\n- purpose: website analytics\n  text: 'Website analytics: privacy-friendly, cookie-free aggregate analytics.'\nretention:\n- scope: playground IP hash\n  period: 7 days\n  text: a salted hash of your IP address for 7 days\n- scope: query logs\n  period: null\n  text: We do not log the dates or parameters you query beyond short-lived operational logs.\n- scope: alert send record\n  period: null\n  text: We keep a record of which alerts we sent so none goes out twice.\nresidency: []\ntransfers:\
  \ []\nsubprocessors:\n  url: null\n  text: 'Processors: Cloudflare (hosting), Stripe (payments), Resend (transactional email).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@bankday.dev\n  text: To delete your account email hello@bankday.dev .\nrights:\n- right: stop minimum wage alerts\n  text: you can stop them with the link in every email\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/bankday-dev/privacy/bankday-dev-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from bankday-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Calendar
- Payments
---
