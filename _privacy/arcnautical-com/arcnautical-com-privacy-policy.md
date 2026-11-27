---
api_specs:
- filename: arcnautical-com-account-api-openapi.yml
  format: yaml
  label: ArcNautical Account API
  slug: arcnautical-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-account-api-openapi.yml
- filename: arcnautical-com-cargo-screening-api-openapi.yml
  format: yaml
  label: ArcNautical Cargo screening API
  slug: arcnautical-com-cargo-screening-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-cargo-screening-api-openapi.yml
- filename: arcnautical-com-corridor-monitors-api-openapi.yml
  format: yaml
  label: ArcNautical Corridor monitors API
  slug: arcnautical-com-corridor-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-corridor-monitors-api-openapi.yml
- filename: arcnautical-com-crew-placement-api-openapi.yml
  format: yaml
  label: ArcNautical Crew placement API
  slug: arcnautical-com-crew-placement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-crew-placement-api-openapi.yml
- filename: arcnautical-com-exports-api-openapi.yml
  format: yaml
  label: ArcNautical Exports API
  slug: arcnautical-com-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-exports-api-openapi.yml
- filename: arcnautical-com-fleets-api-openapi.yml
  format: yaml
  label: ArcNautical Fleets API
  slug: arcnautical-com-fleets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-fleets-api-openapi.yml
- filename: arcnautical-com-port-lookup-api-openapi.yml
  format: yaml
  label: ArcNautical Port lookup API
  slug: arcnautical-com-port-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-port-lookup-api-openapi.yml
- filename: arcnautical-com-public-vessel-check-api-openapi.yml
  format: yaml
  label: ArcNautical Public vessel check API
  slug: arcnautical-com-public-vessel-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-public-vessel-check-api-openapi.yml
- filename: arcnautical-com-vessel-monitors-api-openapi.yml
  format: yaml
  label: ArcNautical Vessel monitors API
  slug: arcnautical-com-vessel-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-vessel-monitors-api-openapi.yml
- filename: arcnautical-com-vessel-screening-api-openapi.yml
  format: yaml
  label: ArcNautical Vessel screening API
  slug: arcnautical-com-vessel-screening-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-vessel-screening-api-openapi.yml
- filename: arcnautical-com-voyage-assessments-api-openapi.yml
  format: yaml
  label: ArcNautical Voyage assessments API
  slug: arcnautical-com-voyage-assessments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-voyage-assessments-api-openapi.yml
- filename: arcnautical-com-webhooks-api-openapi.yml
  format: yaml
  label: ArcNautical Webhooks API
  slug: arcnautical-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arcnautical-com/openapi/arcnautical-com-webhooks-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you register, we collect your email address, company name, and password (stored as a salted cryptographic hash, never in plaintext).
  - category: behavioral
    text: We collect information about how you use the platform, including voyage queries, fleet configurations, alert settings, and report generation activity.
  - category: device
    text: 'API Access Logs: When you use our API, we log request metadata (endpoint, timestamp, IP address)'
  - category: communication
    text: When you request test access, we collect your work email, company, integration use case, optional assessment volume, optional test route, and source attribution
  - category: behavioral
    text: Through our analytics provider (PostHog), we collect page views, feature interactions, performance metrics, anonymized error diagnostics, and session replays
  deletion:
    route: Contact us at [email protected]
    text: Request deletion of your account and associated data
  dpa:
    available: true
    text: The mechanism, the transfer impact assessment and the full processing terms are in our Data Processing Addendum
    url: null
  purposes:
  - purpose: Provide and maintain the platform
    text: To provide and maintain the ArcNautical platform and its features
  - purpose: Compute voyage risk scores and threat intelligence
    text: To compute voyage risk scores, fleet assessments, and threat intelligence
  - purpose: Deliver alerts and webhooks
    text: To deliver alerts and webhook notifications you have configured
  - purpose: Prevent abuse and fraud
    text: To monitor and prevent abuse, fraud, and unauthorized access
  - purpose: Improve the platform
    text: To improve and optimize the platform based on aggregate usage patterns
  residency:
  - region: India
    text: Primary processing happens on Microsoft Azure in India.
  retention:
  - period: Retained for the lifetime of your account
    scope: Account data
    text: 'Account data: Retained for the lifetime of your account'
  - period: 90 days
    scope: Vessel position history
    text: 'Vessel position history: 90 days'
  - period: 7 days from creation
    scope: Session tokens
    text: 'Session tokens: 7 days from creation'
  - period: 12 months after the latest open request
    scope: API evaluation requests
    text: 'API evaluation requests: 12 months after the latest open request'
  rights:
  - right: Access
    text: Access the personal data we hold about you
  - right: Correct
    text: Correct inaccurate data
  - right: Deletion
    text: Request deletion of your account and associated data
  - right: Export
    text: Export your fleet configurations and alert settings
  - right: Withdraw consent
    text: Withdraw consent for non-essential data processing
  role:
    text: We do not sell, rent, or trade your personal information to third parties.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or trade your personal information to third parties.
  subprocessors:
    text: These are every third party that can reach your data, and what each one does.
    url: null
  transfers:
  - mechanism: SCC
    text: If you are in the EEA, the UK or Switzerland, that is a transfer to a country without an adequacy decision, and we make it under the European Commission Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ArcNautical
provenance_date: '2026-11-09'
provider_name: ArcNautical
provider_slug: arcnautical-com
slug: arcnautical-com-privacy-policy
source_date: '2026-11-09'
source_filename: arcnautical-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://arcnautical.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ArcNautical\naid: arcnautical-com\nurl: https://arcnautical.com/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We do not sell, rent, or trade your personal information to third parties.\ndata_categories:\n- category: identifying\n  text: When you register, we collect your email address, company name, and password (stored as a salted cryptographic\n    hash, never in plaintext).\n- category: behavioral\n  text: We collect information about how you use the platform, including voyage queries, fleet configurations, alert\n    settings, and report generation activity.\n- category:\
  \ device\n  text: 'API Access Logs: When you use our API, we log request metadata (endpoint, timestamp, IP address)'\n- category: communication\n  text: When you request test access, we collect your work email, company, integration use case, optional assessment\n    volume, optional test route, and source attribution\n- category: behavioral\n  text: Through our analytics provider (PostHog), we collect page views, feature interactions, performance metrics,\n    anonymized error diagnostics, and session replays\npurposes:\n- purpose: Provide and maintain the platform\n  text: To provide and maintain the ArcNautical platform and its features\n- purpose: Compute voyage risk scores and threat intelligence\n  text: To compute voyage risk scores, fleet assessments, and threat intelligence\n- purpose: Deliver alerts and webhooks\n  text: To deliver alerts and webhook notifications you have configured\n- purpose: Prevent abuse and fraud\n  text: To monitor and prevent abuse, fraud, and unauthorized\
  \ access\n- purpose: Improve the platform\n  text: To improve and optimize the platform based on aggregate usage patterns\nretention:\n- scope: Account data\n  period: Retained for the lifetime of your account\n  text: 'Account data: Retained for the lifetime of your account'\n- scope: Vessel position history\n  period: 90 days\n  text: 'Vessel position history: 90 days'\n- scope: Session tokens\n  period: 7 days from creation\n  text: 'Session tokens: 7 days from creation'\n- scope: API evaluation requests\n  period: 12 months after the latest open request\n  text: 'API evaluation requests: 12 months after the latest open request'\nresidency:\n- region: India\n  text: Primary processing happens on Microsoft Azure in India.\ntransfers:\n- mechanism: SCC\n  text: If you are in the EEA, the UK or Switzerland, that is a transfer to a country without an adequacy decision,\n    and we make it under the European Commission Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: These\
  \ are every third party that can reach your data, and what each one does.\ndpa:\n  available: true\n  url: null\n  text: The mechanism, the transfer impact assessment and the full processing terms are in our Data Processing Addendum\ndeletion:\n  route: Contact us at [email protected]\n  text: Request deletion of your account and associated data\nrights:\n- right: Access\n  text: Access the personal data we hold about you\n- right: Correct\n  text: Correct inaccurate data\n- right: Deletion\n  text: Request deletion of your account and associated data\n- right: Export\n  text: Export your fleet configurations and alert settings\n- right: Withdraw consent\n  text: Withdraw consent for non-essential data processing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or trade your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/arcnautical-com/privacy/arcnautical-com-privacy-policy.yml
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
summary_line: 26 quoted statements, read from ArcNautical's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Maritime
- Compliance
- Data
- Screening
---
