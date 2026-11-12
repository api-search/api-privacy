---
api_specs:
- filename: codeqr-io-analytics-api-openapi.yml
  format: yaml
  label: CodeQR Analytics API
  slug: codeqr-io-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-analytics-api-openapi.yml
- filename: codeqr-io-domains-api-openapi.yml
  format: yaml
  label: CodeQR Domains API
  slug: codeqr-io-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-domains-api-openapi.yml
- filename: codeqr-io-events-api-openapi.yml
  format: yaml
  label: CodeQR Events API
  slug: codeqr-io-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-events-api-openapi.yml
- filename: codeqr-io-folders-api-openapi.yml
  format: yaml
  label: CodeQR Folders API
  slug: codeqr-io-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-folders-api-openapi.yml
- filename: codeqr-io-links-api-openapi.yml
  format: yaml
  label: CodeQR Links API
  slug: codeqr-io-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-links-api-openapi.yml
- filename: codeqr-io-projects-api-openapi.yml
  format: yaml
  label: CodeQR Projects API
  slug: codeqr-io-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-projects-api-openapi.yml
- filename: codeqr-io-qr-codes-api-openapi.yml
  format: yaml
  label: CodeQR QR Codes API
  slug: codeqr-io-qr-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-qr-codes-api-openapi.yml
- filename: codeqr-io-tags-api-openapi.yml
  format: yaml
  label: CodeQR Tags API
  slug: codeqr-io-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-tags-api-openapi.yml
- filename: codeqr-io-track-api-openapi.yml
  format: yaml
  label: CodeQR Track API
  slug: codeqr-io-track-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/codeqr-io/openapi/codeqr-io-track-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: name, email address and password, workspace and company name, and the settings you configure.'
  - category: financial
    text: 'Billing data: plan, subscription status and payment information, processed by our payment provider (Stripe).'
  - category: location
    text: Approximate location (country, city and region).
  - category: device
    text: User-agent information (device type, browser and operating system).
  - category: behavioral
    text: Referrer (the page that led to the click or visit).
  - category: communication
    text: 'Communications: messages you send to our support and privacy channels.'
  deletion:
    route: Contact contact@codeqr.io to exercise erasure rights
    text: Erasure — ask us to delete your personal data, under certain conditions.
  dpa:
    available: true
    text: Our Data Processing Agreement (DPA) is available at codeqr.io/legal/dpa and is incorporated by reference into our customer contracts.
    url: codeqr.io/legal/dpa
  purposes:
  - purpose: Provide and operate the Service
    text: Provide, operate and maintain the Service.
  - purpose: Analytics dashboards for customers
    text: Provide analytics dashboards and reports to our customers.
  - purpose: Payments and subscriptions
    text: Process payments and manage subscriptions.
  - purpose: Fraud and security
    text: Detect, prevent and respond to fraud, abuse and security incidents.
  - purpose: Marketing communications
    text: Send marketing communications where you have agreed to receive them.
  residency:
  - region: United States
    text: Our infrastructure is located primarily in the United States.
  retention:
  - period: up to 90 days
    scope: Event-level identifiers
    text: 'Retention commitment: event-level identifiers are retained for up to 90 days.'
  - period: up to 14 months
    scope: Mobile app usage events
    text: usage events for up to 14 months
  - period: 90 days
    scope: Mobile app crash and error reports
    text: Crash and error reports from the mobile app are kept for 90 days before deletion starts
  - period: null
    scope: Account data
    text: We keep account data for as long as your account exists and, after that, only for the periods required by law (for example, tax and accounting obligations).
  rights:
  - right: Access
    text: Access — request a copy of the personal data we hold about you.
  - right: Rectification
    text: Rectification — ask us to correct inaccurate or incomplete data.
  - right: Erasure
    text: Erasure — ask us to delete your personal data, under certain conditions.
  - right: Restriction
    text: Restriction — ask us to restrict the processing of your data, under certain conditions.
  - right: Objection
    text: Objection — object to processing based on legitimate interests.
  - right: Portability
    text: Portability — receive your data in a structured, machine-readable format.
  - right: Opt out of sale or sharing
    text: Opt out of the "sale" or "sharing" of personal data — we do not sell personal data.
  role:
    text: For account, billing, marketing and mobile app data, CodeQR is the controller. For visitor event data generated by our customers' links, QR codes and pages, CodeQR is a processor and the customer is the controller.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: The current list is available at codeqr.io/legal/subprocessors.
    url: codeqr.io/legal/subprocessors
  transfers:
  - mechanism: SCC
    text: Transfers of personal data from the European Union and the United Kingdom are covered by Standard Contractual Clauses (and, for the UK, the UK Addendum) entered into with our subprocessors.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CodeQR
provenance_date: '2026-11-09'
provider_name: CodeQR
provider_slug: codeqr-io
slug: codeqr-io-privacy-policy
source_date: '2026-11-09'
source_filename: codeqr-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://codeqr.io/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CodeQR\naid: codeqr-io\nurl: https://codeqr.io/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For account, billing, marketing and mobile app data, CodeQR is the controller. For visitor event data generated\n    by our customers' links, QR codes and pages, CodeQR is a processor and the customer is the controller.\ndata_categories:\n- category: identifying\n  text: 'Account data: name, email address and password, workspace and company name, and the settings you configure.'\n- category: financial\n  text: 'Billing data: plan, subscription status and payment information, processed by our\
  \ payment provider (Stripe).'\n- category: location\n  text: Approximate location (country, city and region).\n- category: device\n  text: User-agent information (device type, browser and operating system).\n- category: behavioral\n  text: Referrer (the page that led to the click or visit).\n- category: communication\n  text: 'Communications: messages you send to our support and privacy channels.'\npurposes:\n- purpose: Provide and operate the Service\n  text: Provide, operate and maintain the Service.\n- purpose: Analytics dashboards for customers\n  text: Provide analytics dashboards and reports to our customers.\n- purpose: Payments and subscriptions\n  text: Process payments and manage subscriptions.\n- purpose: Fraud and security\n  text: Detect, prevent and respond to fraud, abuse and security incidents.\n- purpose: Marketing communications\n  text: Send marketing communications where you have agreed to receive them.\nretention:\n- scope: Event-level identifiers\n  period: up to\
  \ 90 days\n  text: 'Retention commitment: event-level identifiers are retained for up to 90 days.'\n- scope: Mobile app usage events\n  period: up to 14 months\n  text: usage events for up to 14 months\n- scope: Mobile app crash and error reports\n  period: 90 days\n  text: Crash and error reports from the mobile app are kept for 90 days before deletion starts\n- scope: Account data\n  period: null\n  text: We keep account data for as long as your account exists and, after that, only for the periods required by\n    law (for example, tax and accounting obligations).\nresidency:\n- region: United States\n  text: Our infrastructure is located primarily in the United States.\ntransfers:\n- mechanism: SCC\n  text: Transfers of personal data from the European Union and the United Kingdom are covered by Standard Contractual\n    Clauses (and, for the UK, the UK Addendum) entered into with our subprocessors.\nsubprocessors:\n  url: codeqr.io/legal/subprocessors\n  text: The current list is available\
  \ at codeqr.io/legal/subprocessors.\ndpa:\n  available: true\n  url: codeqr.io/legal/dpa\n  text: Our Data Processing Agreement (DPA) is available at codeqr.io/legal/dpa and is incorporated by reference\n    into our customer contracts.\ndeletion:\n  route: Contact contact@codeqr.io to exercise erasure rights\n  text: Erasure — ask us to delete your personal data, under certain conditions.\nrights:\n- right: Access\n  text: Access — request a copy of the personal data we hold about you.\n- right: Rectification\n  text: Rectification — ask us to correct inaccurate or incomplete data.\n- right: Erasure\n  text: Erasure — ask us to delete your personal data, under certain conditions.\n- right: Restriction\n  text: Restriction — ask us to restrict the processing of your data, under certain conditions.\n- right: Objection\n  text: Objection — object to processing based on legitimate interests.\n- right: Portability\n  text: Portability — receive your data in a structured, machine-readable format.\n\
  - right: Opt out of sale or sharing\n  text: Opt out of the \"sale\" or \"sharing\" of personal data — we do not sell personal data.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/codeqr-io/privacy/codeqr-io-privacy-policy.yml
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
summary_line: 29 quoted statements, read from CodeQR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- QR Codes
- Short Links
- URL Shortener
- Link Management
- Analytics
- Marketing
- MCP
---
