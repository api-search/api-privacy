---
api_specs:
- filename: puzaricloud-in-config-api-openapi.yml
  format: yaml
  label: puzaricloud-in Config API
  slug: puzaricloud-in-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/puzaricloud-in/openapi/puzaricloud-in-config-api-openapi.yml
- filename: puzaricloud-in-heartbeats-api-openapi.yml
  format: yaml
  label: puzaricloud-in Heartbeats API
  slug: puzaricloud-in-heartbeats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/puzaricloud-in/openapi/puzaricloud-in-heartbeats-api-openapi.yml
- filename: puzaricloud-in-licensing-api-openapi.yml
  format: yaml
  label: puzaricloud-in Licensing API
  slug: puzaricloud-in-licensing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/puzaricloud-in/openapi/puzaricloud-in-licensing-api-openapi.yml
- filename: puzaricloud-in-monitors-api-openapi.yml
  format: yaml
  label: puzaricloud-in Monitors API
  slug: puzaricloud-in-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/puzaricloud-in/openapi/puzaricloud-in-monitors-api-openapi.yml
- filename: puzaricloud-in-partner-api-api-openapi.yml
  format: yaml
  label: puzaricloud-in Partner API
  slug: puzaricloud-in-partner-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/puzaricloud-in/openapi/puzaricloud-in-partner-api-api-openapi.yml
- filename: puzaricloud-in-private-locations-api-openapi.yml
  format: yaml
  label: puzaricloud-in private locations API
  slug: puzaricloud-in-private-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/puzaricloud-in/openapi/puzaricloud-in-private-locations-api-openapi.yml
- filename: puzaricloud-in-resources-api-openapi.yml
  format: yaml
  label: puzaricloud-in Resources API
  slug: puzaricloud-in-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/puzaricloud-in/openapi/puzaricloud-in-resources-api-openapi.yml
- filename: puzaricloud-in-servers-api-openapi.yml
  format: yaml
  label: puzaricloud-in Servers API
  slug: puzaricloud-in-servers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/puzaricloud-in/openapi/puzaricloud-in-servers-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your email address, password hash (we never store passwords), Google or SSO identifiers if you sign in that way, and login times.'
  - category: behavioral
    text: check results (status codes, response times, extracted page text, response snippets kept as failure evidence)
  - category: financial
    text: 'Billing data: your plan, subscription status and Paddle customer id'
  - category: communication
    text: we store the tokens or addresses you give us and send alert content to those services
  deletion:
    route: delete monitors, servers or your account in the app, or email hello@puzaricloud.in to request erasure
    text: When you delete your workspace or ask us to erase your data, it is removed from the live database within 30 days and disappears from backups as they expire (at most 8 weeks).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run monitoring and alerts
    text: To run the monitoring you asked for, deliver alerts to the channels you chose, show you dashboards and reports, bill you, secure the service, and answer support requests.
  - purpose: no advertising use
    text: we do not use your data for advertising
  residency:
  - region: Germany (EU)
    text: Your data lives in our database on servers rented from Hetzner in Germany (EU).
  retention:
  - period: 7 to 365 days
    scope: check history and server metrics
    text: Check history and server metrics are kept for the period of your plan (7 to 365 days) and then deleted automatically.
  - period: up to 8 weeks
    scope: backups
    text: Backups are kept for up to 8 weeks.
  rights:
  - right: access, correct, export, erase
    text: You may also ask us to access, correct, export or erase your data by emailing hello@puzaricloud.in ; we respond within 30 days.
  - right: GDPR complaint
    text: If you are in the EU/UK you have the rights set out in the GDPR, including the right to complain to your supervisory authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and we do not use your data for advertising.
  subprocessors:
    text: Processors we rely on. Hetzner Online GmbH (server hosting, Germany), Paddle.com (payments and invoicing), Amazon Web Services (billing for subscriptions bought on AWS Marketplace), Brevo (transactional email), Google (optional Google Sign-In; optional AI incident analysis via the Gemini API, which receives incident evidence you explicitly ask to analyse).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: puzaricloud-in
provenance_date: '2026-11-10'
provider_name: puzaricloud-in
provider_slug: puzaricloud-in
slug: puzaricloud-in-privacy-policy
source_date: '2026-11-10'
source_filename: puzaricloud-in-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://puzaricloud.in/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: puzaricloud-in\naid: puzaricloud-in\nurl: https://puzaricloud.in/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account data: your email address, password hash (we never store passwords), Google or SSO identifiers if\n    you sign in that way, and login times.'\n- category: behavioral\n  text: check results (status codes, response times, extracted page text, response snippets kept as failure evidence)\n- category: financial\n  text: 'Billing data: your plan, subscription status and Paddle customer id'\n- category: communication\n\
  \  text: we store the tokens or addresses you give us and send alert content to those services\npurposes:\n- purpose: run monitoring and alerts\n  text: To run the monitoring you asked for, deliver alerts to the channels you chose, show you dashboards and reports,\n    bill you, secure the service, and answer support requests.\n- purpose: no advertising use\n  text: we do not use your data for advertising\nretention:\n- scope: check history and server metrics\n  period: 7 to 365 days\n  text: Check history and server metrics are kept for the period of your plan (7 to 365 days) and then deleted automatically.\n- scope: backups\n  period: up to 8 weeks\n  text: Backups are kept for up to 8 weeks.\nresidency:\n- region: Germany (EU)\n  text: Your data lives in our database on servers rented from Hetzner in Germany (EU).\ntransfers: []\nsubprocessors:\n  url: null\n  text: Processors we rely on. Hetzner Online GmbH (server hosting, Germany), Paddle.com (payments and invoicing),\n    Amazon\
  \ Web Services (billing for subscriptions bought on AWS Marketplace), Brevo (transactional email), Google\n    (optional Google Sign-In; optional AI incident analysis via the Gemini API, which receives incident evidence\n    you explicitly ask to analyse).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete monitors, servers or your account in the app, or email hello@puzaricloud.in to request erasure\n  text: When you delete your workspace or ask us to erase your data, it is removed from the live database within\n    30 days and disappears from backups as they expire (at most 8 weeks).\nrights:\n- right: access, correct, export, erase\n  text: You may also ask us to access, correct, export or erase your data by emailing hello@puzaricloud.in ; we\n    respond within 30 days.\n- right: GDPR complaint\n  text: If you are in the EU/UK you have the rights set out in the GDPR, including the right to complain to your\n    supervisory authority.\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We do not sell personal data and we do not use your data for advertising.\n"
source_yaml_url: https://artifacts.apis.io/puzaricloud-in/privacy/puzaricloud-in-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from puzaricloud-in's own page on 2026-11-10.
synthetic: false
tags:
- Monitoring
- Software-as-a-Service
- India
- Alerts
---
