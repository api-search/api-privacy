---
api_specs:
- filename: cosmic-ephemeris-calculations-api-openapi.yml
  format: yaml
  label: Cosmic Ephemeris Calculations API
  slug: cosmic-ephemeris-calculations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmic-ephemeris/openapi/cosmic-ephemeris-calculations-api-openapi.yml
- filename: cosmic-ephemeris-interpretation-api-openapi.yml
  format: yaml
  label: Cosmic Ephemeris Interpretation API
  slug: cosmic-ephemeris-interpretation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmic-ephemeris/openapi/cosmic-ephemeris-interpretation-api-openapi.yml
- filename: cosmic-ephemeris-pro-timeline-api-openapi.yml
  format: yaml
  label: Cosmic Ephemeris Pro timeline API
  slug: cosmic-ephemeris-pro-timeline-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cosmic-ephemeris/openapi/cosmic-ephemeris-pro-timeline-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: We process your name, email address, password hash, account and plan status, Terms version and acceptance time, account timestamps, login timestamps, and mailbox-verification status.
  - category: device
    text: Web-server, application, security, and infrastructure logs may include IP address, requested path, browser user agent, referring origin, timestamp, generalized error information, and security signals.
  - category: financial
    text: Stripe processes payment-card and billing details on its hosted pages.
  - category: communication
    text: If you contact us, we process the email address, message, attachments, account details, and follow-up records you provide.
  - category: demographic
    text: Requests can include names, birth dates and times, selected or resolved timezones, latitude and longitude, place queries and country filters
  deletion:
    route: Account deletion or request to support@cosmicephemeris.com
    text: Account deletion removes the active user row and dependent API-key, environment-policy, saved-chart, saved-reading, saved-event-search, schedule, batch-job, webhook, session, verification, reset, and per-account current-quota records.
  dpa:
    available: false
    text: No public data-processing agreement is currently offered.
    url: null
  purposes:
  - purpose: Account creation and authentication
    text: to create, authenticate, and secure accounts, sessions, keys, workspaces, and webhooks
  - purpose: Performing requested calculations
    text: to perform requested calculations, place/timezone resolution, saved workflows, scheduled searches, jobs, exports, and deliveries
  - purpose: Billing administration
    text: to administer subscriptions, payments, cancellation, taxes, and billing reconciliation
  - purpose: Abuse prevention and security
    text: to measure usage, apply entitlements, prevent abuse, diagnose errors, and protect shared infrastructure
  residency:
  - region: United States
    text: Cosmic Ephemeris is based in the United States and is available to eligible users internationally where lawful.
  - region: No promised region
    text: The public Service does not promise a particular data-residency region.
  retention:
  - period: null
    scope: Account and saved-workflow records
    text: We retain account and saved-workflow records while the account or record exists, then delete or de-identify them subject to security, billing, legal, dispute, and backup needs.
  - period: 24 hours
    scope: Batch-job inputs and results
    text: Batch-job normalized inputs and results expire 24 hours after submission and are removed by bounded cleanup.
  - period: fourteen-day retention
    scope: Automated RDS backups
    text: Automated RDS backups are currently configured for fourteen-day retention.
  - period: seven days
    scope: Email-queue records that permanently failed
    text: Permanently failed email-queue records are removed by bounded cleanup after seven days
  rights:
  - right: Access, correction, deletion, portable copy
    text: you may have rights to know or access, correct, delete, or obtain a portable copy of personal information
  - right: Object, restrict, withdraw consent
    text: object to or restrict certain processing; withdraw consent
  - right: Opt out of sale, targeted advertising, sharing
    text: or opt out of sale, targeted advertising, sharing, or certain profiling
  - right: Appeal
    text: If applicable law gives you an appeal right, reply with the subject "Privacy appeal"
  role:
    text: Cosmic Ephemeris determines the purposes and means of processing account, authentication, security, usage, support, and billing-administration information.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not currently sell personal information, share it for cross-context behavioral advertising, use it for targeted advertising, or knowingly exchange it for monetary consideration.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cosmic Ephemeris
provenance_date: '2026-11-09'
provider_name: Cosmic Ephemeris
provider_slug: cosmic-ephemeris
slug: cosmic-ephemeris-privacy-policy
source_date: '2026-11-09'
source_filename: cosmic-ephemeris-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cosmicephemeris.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cosmic Ephemeris\naid: cosmic-ephemeris\nurl: https://cosmicephemeris.com/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Cosmic Ephemeris determines the purposes and means of processing account, authentication, security, usage,\n    support, and billing-administration information.\ndata_categories:\n- category: identifying\n  text: We process your name, email address, password hash, account and plan status, Terms version and acceptance\n    time, account timestamps, login timestamps, and mailbox-verification status.\n- category: device\n  text: Web-server, application, security,\
  \ and infrastructure logs may include IP address, requested path, browser\n    user agent, referring origin, timestamp, generalized error information, and security signals.\n- category: financial\n  text: Stripe processes payment-card and billing details on its hosted pages.\n- category: communication\n  text: If you contact us, we process the email address, message, attachments, account details, and follow-up records\n    you provide.\n- category: demographic\n  text: Requests can include names, birth dates and times, selected or resolved timezones, latitude and longitude,\n    place queries and country filters\npurposes:\n- purpose: Account creation and authentication\n  text: to create, authenticate, and secure accounts, sessions, keys, workspaces, and webhooks\n- purpose: Performing requested calculations\n  text: to perform requested calculations, place/timezone resolution, saved workflows, scheduled searches, jobs,\n    exports, and deliveries\n- purpose: Billing administration\n\
  \  text: to administer subscriptions, payments, cancellation, taxes, and billing reconciliation\n- purpose: Abuse prevention and security\n  text: to measure usage, apply entitlements, prevent abuse, diagnose errors, and protect shared infrastructure\nretention:\n- scope: Account and saved-workflow records\n  period: null\n  text: We retain account and saved-workflow records while the account or record exists, then delete or de-identify\n    them subject to security, billing, legal, dispute, and backup needs.\n- scope: Batch-job inputs and results\n  period: 24 hours\n  text: Batch-job normalized inputs and results expire 24 hours after submission and are removed by bounded cleanup.\n- scope: Automated RDS backups\n  period: fourteen-day retention\n  text: Automated RDS backups are currently configured for fourteen-day retention.\n- scope: Email-queue records that permanently failed\n  period: seven days\n  text: Permanently failed email-queue records are removed by bounded cleanup after\
  \ seven days\nresidency:\n- region: United States\n  text: Cosmic Ephemeris is based in the United States and is available to eligible users internationally where\n    lawful.\n- region: No promised region\n  text: The public Service does not promise a particular data-residency region.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: false\n  url: null\n  text: No public data-processing agreement is currently offered.\ndeletion:\n  route: Account deletion or request to support@cosmicephemeris.com\n  text: Account deletion removes the active user row and dependent API-key, environment-policy, saved-chart, saved-reading,\n    saved-event-search, schedule, batch-job, webhook, session, verification, reset, and per-account current-quota\n    records.\nrights:\n- right: Access, correction, deletion, portable copy\n  text: you may have rights to know or access, correct, delete, or obtain a portable copy of personal information\n- right: Object, restrict, withdraw\
  \ consent\n  text: object to or restrict certain processing; withdraw consent\n- right: Opt out of sale, targeted advertising, sharing\n  text: or opt out of sale, targeted advertising, sharing, or certain profiling\n- right: Appeal\n  text: If applicable law gives you an appeal right, reply with the subject \"Privacy appeal\"\nsale_or_sharing:\n  stance: prohibited\n  text: We do not currently sell personal information, share it for cross-context behavioral advertising, use it\n    for targeted advertising, or knowingly exchange it for monetary consideration.\n"
source_yaml_url: https://artifacts.apis.io/cosmic-ephemeris/privacy/cosmic-ephemeris-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from Cosmic Ephemeris's own page on 2026-11-09.
synthetic: false
tags:
- Astrology
- Developers
- Data
- U.S.-based
---
