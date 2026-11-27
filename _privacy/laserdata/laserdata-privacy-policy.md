---
api_specs:
- filename: laserdata-account-api-openapi.yml
  format: yaml
  label: LaserData Account API
  slug: laserdata-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-account-api-openapi.yml
- filename: laserdata-api-keys-api-openapi.yml
  format: yaml
  label: LaserData API Keys API
  slug: laserdata-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-api-keys-api-openapi.yml
- filename: laserdata-audit-api-openapi.yml
  format: yaml
  label: LaserData Audit API
  slug: laserdata-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-audit-api-openapi.yml
- filename: laserdata-billing-api-openapi.yml
  format: yaml
  label: LaserData Billing API
  slug: laserdata-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-billing-api-openapi.yml
- filename: laserdata-cloud-accounts-api-openapi.yml
  format: yaml
  label: LaserData Cloud Accounts API
  slug: laserdata-cloud-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-cloud-accounts-api-openapi.yml
- filename: laserdata-clouds-api-openapi.yml
  format: yaml
  label: LaserData Clouds API
  slug: laserdata-clouds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-clouds-api-openapi.yml
- filename: laserdata-connectors-api-openapi.yml
  format: yaml
  label: LaserData Connectors API
  slug: laserdata-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-connectors-api-openapi.yml
- filename: laserdata-deployments-api-openapi.yml
  format: yaml
  label: LaserData Deployments API
  slug: laserdata-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-deployments-api-openapi.yml
- filename: laserdata-divisions-api-openapi.yml
  format: yaml
  label: LaserData Divisions API
  slug: laserdata-divisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-divisions-api-openapi.yml
- filename: laserdata-environments-api-openapi.yml
  format: yaml
  label: LaserData Environments API
  slug: laserdata-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-environments-api-openapi.yml
- filename: laserdata-invitations-api-openapi.yml
  format: yaml
  label: LaserData Invitations API
  slug: laserdata-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-invitations-api-openapi.yml
- filename: laserdata-members-api-openapi.yml
  format: yaml
  label: LaserData Members API
  slug: laserdata-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-members-api-openapi.yml
- filename: laserdata-notification-channels-api-openapi.yml
  format: yaml
  label: LaserData Notification Channels API
  slug: laserdata-notification-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-notification-channels-api-openapi.yml
- filename: laserdata-notification-subscriptions-api-openapi.yml
  format: yaml
  label: LaserData Notification Subscriptions API
  slug: laserdata-notification-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-notification-subscriptions-api-openapi.yml
- filename: laserdata-notifications-api-openapi.yml
  format: yaml
  label: LaserData Notifications API
  slug: laserdata-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-notifications-api-openapi.yml
- filename: laserdata-payments-api-openapi.yml
  format: yaml
  label: LaserData Payments API
  slug: laserdata-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-payments-api-openapi.yml
- filename: laserdata-roles-api-openapi.yml
  format: yaml
  label: LaserData Roles API
  slug: laserdata-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-roles-api-openapi.yml
- filename: laserdata-tenants-api-openapi.yml
  format: yaml
  label: LaserData Tenants API
  slug: laserdata-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserdata/openapi/laserdata-tenants-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: account and contact information such as name, business email address, phone number, company name, job title or role
  - category: financial
    text: limited payment method details provided by our payment processor, such as card brand, last four digits, expiration month/year, and payment token
  - category: device
    text: IP address, device identifiers, browser type, operating system, referring pages, pages viewed
  - category: location
    text: approximate location derived from IP address
  - category: communication
    text: message contents, attachments, diagnostic information, support tickets, call notes
  - category: behavioral
    text: feature usage, session duration, error reports, performance metrics, security events, usage volumes
  deletion:
    route: contact privacy address
    text: To exercise rights, contact [email protected] .
  dpa:
    available: true
    text: any applicable Data Processing Addendum
    url: null
  purposes:
  - purpose: account management and authentication
    text: create and manage accounts, authenticate users, provide dashboards, APIs, connectors, and platform functionality
  - purpose: security and abuse prevention
    text: monitoring for unauthorized access, credential compromise, fraud, malware, abuse, spam, and security threats
  - purpose: billing
    text: processing payments, generating invoices, managing subscriptions, applying credits, calculating usage and overages
  - purpose: sales and marketing
    text: We may use Account Data for sales and marketing, including providing requested demos or information, sending newsletters or product announcements
  residency:
  - region: United States and other countries
    text: LaserData may process and store information in the United States and other countries where we, our affiliates, service providers, or subprocessors operate.
  retention:
  - period: 14 consecutive days of inactivity
    scope: Free Tier accounts
    text: Free Tier accounts may be deleted after 14 consecutive days of inactivity.
  - period: null
    scope: marketing information
    text: marketing information is retained until you opt out or request deletion, subject to legal exceptions
  rights:
  - right: access
    text: access your Personal Information, correct inaccurate information, delete Personal Information
  - right: portability
    text: receive a copy of Personal Information in portable format
  - right: objection and restriction
    text: object to or restrict certain processing
  - right: withdraw consent
    text: withdraw consent where processing is based on consent
  - right: opt out of marketing
    text: opt out of marketing communications
  - right: appeal
    text: appeal a denial of a privacy request where applicable
  role:
    text: For Customer Data, LaserData generally acts as a processor, service provider, or similar role on behalf of the customer.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: LaserData does not sell Customer Data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: such as standard contractual clauses, data processing agreements, adequacy decisions, or other lawful transfer mechanisms
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LaserData
provenance_date: '2026-11-09'
provider_name: LaserData
provider_slug: laserdata
slug: laserdata-privacy-policy
source_date: '2026-11-09'
source_filename: laserdata-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://laserdata.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LaserData\naid: laserdata\nurl: https://laserdata.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For Customer Data, LaserData generally acts as a processor, service provider, or similar role on behalf\n    of the customer.\ndata_categories:\n- category: identifying\n  text: account and contact information such as name, business email address, phone number, company name, job title\n    or role\n- category: financial\n  text: limited payment method details provided by our payment processor, such as card brand, last four digits,\n    expiration month/year, and payment token\n- category:\
  \ device\n  text: IP address, device identifiers, browser type, operating system, referring pages, pages viewed\n- category: location\n  text: approximate location derived from IP address\n- category: communication\n  text: message contents, attachments, diagnostic information, support tickets, call notes\n- category: behavioral\n  text: feature usage, session duration, error reports, performance metrics, security events, usage volumes\npurposes:\n- purpose: account management and authentication\n  text: create and manage accounts, authenticate users, provide dashboards, APIs, connectors, and platform functionality\n- purpose: security and abuse prevention\n  text: monitoring for unauthorized access, credential compromise, fraud, malware, abuse, spam, and security threats\n- purpose: billing\n  text: processing payments, generating invoices, managing subscriptions, applying credits, calculating usage and\n    overages\n- purpose: sales and marketing\n  text: We may use Account Data for\
  \ sales and marketing, including providing requested demos or information, sending\n    newsletters or product announcements\nretention:\n- scope: Free Tier accounts\n  period: 14 consecutive days of inactivity\n  text: Free Tier accounts may be deleted after 14 consecutive days of inactivity.\n- scope: marketing information\n  period: null\n  text: marketing information is retained until you opt out or request deletion, subject to legal exceptions\nresidency:\n- region: United States and other countries\n  text: LaserData may process and store information in the United States and other countries where we, our affiliates,\n    service providers, or subprocessors operate.\ntransfers:\n- mechanism: SCC\n  text: such as standard contractual clauses, data processing agreements, adequacy decisions, or other lawful transfer\n    mechanisms\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: any applicable Data Processing Addendum\ndeletion:\n  route: contact\
  \ privacy address\n  text: To exercise rights, contact [email protected] .\nrights:\n- right: access\n  text: access your Personal Information, correct inaccurate information, delete Personal Information\n- right: portability\n  text: receive a copy of Personal Information in portable format\n- right: objection and restriction\n  text: object to or restrict certain processing\n- right: withdraw consent\n  text: withdraw consent where processing is based on consent\n- right: opt out of marketing\n  text: opt out of marketing communications\n- right: appeal\n  text: appeal a denial of a privacy request where applicable\nsale_or_sharing:\n  stance: prohibited\n  text: LaserData does not sell Customer Data.\n"
source_yaml_url: https://artifacts.apis.io/laserdata/privacy/laserdata-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from LaserData's own page on 2026-11-09.
synthetic: false
tags:
- Streaming
- Message Streaming
- Event Streaming
- Data Infrastructure
- Real-Time
- Apache Iggy
- Rust
- Cloud Infrastructure
- AI Agents
- Observability
- Company
---
