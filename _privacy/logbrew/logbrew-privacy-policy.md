---
api_specs:
- filename: logbrew-account-api-openapi.yml
  format: yaml
  label: LogBrew Account API
  slug: logbrew-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-account-api-openapi.yml
- filename: logbrew-actions-api-openapi.yml
  format: yaml
  label: LogBrew Actions API
  slug: logbrew-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-actions-api-openapi.yml
- filename: logbrew-alerts-api-openapi.yml
  format: yaml
  label: LogBrew Alerts API
  slug: logbrew-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-alerts-api-openapi.yml
- filename: logbrew-billing-api-openapi.yml
  format: yaml
  label: LogBrew Billing API
  slug: logbrew-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-billing-api-openapi.yml
- filename: logbrew-connected-clients-api-openapi.yml
  format: yaml
  label: LogBrew Connected clients API
  slug: logbrew-connected-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-connected-clients-api-openapi.yml
- filename: logbrew-debug-files-api-openapi.yml
  format: yaml
  label: LogBrew Debug files API
  slug: logbrew-debug-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-debug-files-api-openapi.yml
- filename: logbrew-ingestion-api-openapi.yml
  format: yaml
  label: LogBrew Ingestion API
  slug: logbrew-ingestion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-ingestion-api-openapi.yml
- filename: logbrew-issues-api-openapi.yml
  format: yaml
  label: LogBrew Issues API
  slug: logbrew-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-issues-api-openapi.yml
- filename: logbrew-live-feed-api-openapi.yml
  format: yaml
  label: LogBrew Live feed API
  slug: logbrew-live-feed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-live-feed-api-openapi.yml
- filename: logbrew-logs-api-openapi.yml
  format: yaml
  label: LogBrew Logs API
  slug: logbrew-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-logs-api-openapi.yml
- filename: logbrew-metrics-api-openapi.yml
  format: yaml
  label: LogBrew Metrics API
  slug: logbrew-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-metrics-api-openapi.yml
- filename: logbrew-organizations-api-openapi.yml
  format: yaml
  label: LogBrew Organizations API
  slug: logbrew-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-organizations-api-openapi.yml
- filename: logbrew-product-analytics-api-openapi.yml
  format: yaml
  label: LogBrew Product analytics API
  slug: logbrew-product-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-product-analytics-api-openapi.yml
- filename: logbrew-projects-api-openapi.yml
  format: yaml
  label: LogBrew Projects API
  slug: logbrew-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-projects-api-openapi.yml
- filename: logbrew-releases-api-openapi.yml
  format: yaml
  label: LogBrew Releases API
  slug: logbrew-releases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-releases-api-openapi.yml
- filename: logbrew-support-api-openapi.yml
  format: yaml
  label: LogBrew Support API
  slug: logbrew-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-support-api-openapi.yml
- filename: logbrew-traces-api-openapi.yml
  format: yaml
  label: LogBrew Traces API
  slug: logbrew-traces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-traces-api-openapi.yml
- filename: logbrew-volume-api-openapi.yml
  format: yaml
  label: LogBrew Volume API
  slug: logbrew-volume-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logbrew/openapi/logbrew-volume-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create or open an account, LogBrew receives the account reference and profile information supplied by your sign-in provider.
  - category: behavioral
    text: LogBrew records service usage, feature interactions, plan limits, security events, and diagnostic information needed to operate and protect the service.
  - category: device
    text: This data can include service, environment, framework, runtime, device, session, and other technical context.
  - category: communication
    text: If you contact support, LogBrew receives the information that you include in the request.
  - category: financial
    text: LogBrew receives the related customer, subscription, invoice, and payment-status information needed to provide the plan.
  deletion:
    route: Account deletion request from the product; project deletion in the product
    text: You can review and edit profile information, manage preferences, delete projects, and request account deletion from the product.
  dpa:
    available: true
    text: Business customers who need a data processing agreement can request one at support@logbrew.co.
    url: support@logbrew.co
  purposes:
  - purpose: Provide the service and authenticate users
    text: LogBrew uses data to authenticate users, provide the workspace, receive and correlate telemetry, show investigations and analytics, enforce plan limits, answer support requests, secure the service, prevent abuse, improve reliability, meet legal duties, and communicate important account or service information.
  residency:
  - region: Germany
    text: Account data, project data, telemetry, and uploaded files are stored in Germany.
  retention:
  - period: 30 days
    scope: Telemetry on Free plan
    text: Telemetry is kept for your plan's retention window, which is 30 days on Free, 90 days on Pro, 365 days on Business
  - period: 90 days
    scope: Telemetry on Pro plan
    text: Telemetry is kept for your plan's retention window, which is 30 days on Free, 90 days on Pro, 365 days on Business
  - period: 24-hour restore window
    scope: Account deletion
    text: Account deletion disables access and provides a 24-hour restore window before permanent deletion proceeds.
  rights:
  - right: access
    text: Depending on applicable law, you can also ask for access, correction, deletion, restriction, portability, or objection, and you can complain to the relevant data-protection authority.
  - right: withdraw consent
    text: You can withdraw consent for future processing where consent is the basis, without affecting earlier lawful processing.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: LogBrew does not sell personal data.
  subprocessors:
    text: The subprocessor list below names each provider that processes customer data for LogBrew, the data it processes, and where.
    url: null
  transfers:
  - mechanism: other
    text: When required, LogBrew uses recognized safeguards for international transfers and applies the protections described in this policy regardless of processing location.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LogBrew
provenance_date: '2026-11-09'
provider_name: LogBrew
provider_slug: logbrew
slug: logbrew-privacy-policy
source_date: '2026-11-09'
source_filename: logbrew-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://logbrew.co/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LogBrew\naid: logbrew\nurl: https://logbrew.co/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create or open an account, LogBrew receives the account reference and profile information supplied\n    by your sign-in provider.\n- category: behavioral\n  text: LogBrew records service usage, feature interactions, plan limits, security events, and diagnostic information\n    needed to operate and protect the service.\n- category: device\n  text: This data can include service, environment, framework, runtime, device, session,\
  \ and other technical context.\n- category: communication\n  text: If you contact support, LogBrew receives the information that you include in the request.\n- category: financial\n  text: LogBrew receives the related customer, subscription, invoice, and payment-status information needed to provide\n    the plan.\npurposes:\n- purpose: Provide the service and authenticate users\n  text: LogBrew uses data to authenticate users, provide the workspace, receive and correlate telemetry, show investigations\n    and analytics, enforce plan limits, answer support requests, secure the service, prevent abuse, improve reliability,\n    meet legal duties, and communicate important account or service information.\nretention:\n- scope: Telemetry on Free plan\n  period: 30 days\n  text: Telemetry is kept for your plan's retention window, which is 30 days on Free, 90 days on Pro, 365 days on\n    Business\n- scope: Telemetry on Pro plan\n  period: 90 days\n  text: Telemetry is kept for your plan's retention\
  \ window, which is 30 days on Free, 90 days on Pro, 365 days on\n    Business\n- scope: Account deletion\n  period: 24-hour restore window\n  text: Account deletion disables access and provides a 24-hour restore window before permanent deletion proceeds.\nresidency:\n- region: Germany\n  text: Account data, project data, telemetry, and uploaded files are stored in Germany.\ntransfers:\n- mechanism: other\n  text: When required, LogBrew uses recognized safeguards for international transfers and applies the protections\n    described in this policy regardless of processing location.\nsubprocessors:\n  url: null\n  text: The subprocessor list below names each provider that processes customer data for LogBrew, the data it processes,\n    and where.\ndpa:\n  available: true\n  url: support@logbrew.co\n  text: Business customers who need a data processing agreement can request one at support@logbrew.co.\ndeletion:\n  route: Account deletion request from the product; project deletion in the product\n\
  \  text: You can review and edit profile information, manage preferences, delete projects, and request account deletion\n    from the product.\nrights:\n- right: access\n  text: Depending on applicable law, you can also ask for access, correction, deletion, restriction, portability,\n    or objection, and you can complain to the relevant data-protection authority.\n- right: withdraw consent\n  text: You can withdraw consent for future processing where consent is the basis, without affecting earlier lawful\n    processing.\nsale_or_sharing:\n  stance: prohibited\n  text: LogBrew does not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/logbrew/privacy/logbrew-privacy-policy.yml
stated_fields:
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
summary_line: 17 quoted statements, read from LogBrew's own page on 2026-11-09.
synthetic: false
tags:
- Observability
- Logging
- Monitoring
- Analytics
- Error Tracking
---
