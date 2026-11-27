---
api_specs:
- filename: offlineprotocol-com-openapi-generated.yml
  format: yaml
  label: offlineprotocol-com API
  slug: offlineprotocol-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/offlineprotocol-com/openapi/_ae-authored/offlineprotocol-com-openapi-generated.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: Name, email, company, role, use case, industry, fleet size, and timeline
  - category: identifying
    text: Email address
  - category: financial
    text: 'Billing: plan, subscription status, Stripe customer ID, invoices and usage charges'
  - category: location
    text: IP address, user agent, page requested, time
  - category: device
    text: push notification tokens with device model, OS, and app version
  - category: behavioral
    text: Pages and features you use in the portal and actions you take
  - category: communication
    text: Your email and what you write
  deletion:
    route: Delete the developer Account in the portal, or request via legal@offlineprotocol.com
    text: You can delete your developer Account in the portal. Deletion ends your access immediately, and we permanently delete your Account Data within 30 days
  dpa:
    available: true
    text: The measures that apply to Customer Data are listed in Annex 2 of the Data Processing Addendum
    url: null
  purposes:
  - purpose: Create and secure accounts, sign in, run the portal
    text: Create and secure your Account, sign you in, and run the portal
  - purpose: Provide hosted services to Customers
    text: Provide the hosted services to Customers and their apps
  - purpose: Meter usage, apply plans, bill
    text: Meter usage, apply Plans, bill, and collect payment
  - purpose: Protect the Services
    text: 'Protect the Services: rate limiting, abuse and fraud prevention, audit logs, error monitoring'
  residency:
  - region: Singapore
    text: Our databases and hosted services run on Railway in Singapore, and the relay also runs servers in the United States.
  - region: United States, European Union, India
    text: Our service providers process data in the United States, the European Union, India, and other countries
  retention:
  - period: 30 days
    scope: Developer Account
    text: we permanently delete your Account Data within 30 days
  - period: 7 years
    scope: Billing records
    text: Billing records (invoices, payment and usage records, and records of acceptance of the Developer Terms, including the IP address) 7 years, for tax, accounting, and dispute purposes
  - period: 10 minutes
    scope: Sign-in codes
    text: Sign-in codes 10 minutes, single use
  - period: 7 days
    scope: Relay messages
    text: Undelivered messages are queued for up to 7 days.
  - period: 30 days
    scope: Raw telemetry events
    text: Raw telemetry events 30 days
  rights:
  - right: access, correct, erase, restrict, port
    text: You have the right to access, correct, erase, restrict, and port your personal data
  - right: object and withdraw consent
    text: to object to processing based on legitimate interests, and to withdraw consent at any time
  - right: know, delete, portability, opt out of sale/sharing
    text: to know what personal information we collect and how we use and disclose it, to access, correct, and delete it, to receive a portable copy, and to opt out of sale, sharing for targeted advertising, and profiling
  role:
    text: 'Our role: controller or processor'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information and do not profile in ways that produce legal or similar effects.
  subprocessors:
    text: The full list, with what each receives and where, is on our subprocessors page
    url: https://www.offlineprotocol.com/subprocessors
  transfers:
  - mechanism: SCC
    text: we use the European Commission’s Standard Contractual Clauses, the UK Addendum, or another lawful transfer mechanism
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: offlineprotocol-com
provenance_date: '2026-11-10'
provider_name: offlineprotocol-com
provider_slug: offlineprotocol-com
slug: offlineprotocol-com-privacy-policy
source_date: '2026-11-10'
source_filename: offlineprotocol-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.offlineprotocol.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: offlineprotocol-com\naid: offlineprotocol-com\nurl: https://www.offlineprotocol.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Our role: controller or processor'\ndata_categories:\n- category: contact\n  text: Name, email, company, role, use case, industry, fleet size, and timeline\n- category: identifying\n  text: Email address\n- category: financial\n  text: 'Billing: plan, subscription status, Stripe customer ID, invoices and usage charges'\n- category: location\n  text: IP address, user agent, page requested, time\n- category: device\n  text: push notification tokens with device\
  \ model, OS, and app version\n- category: behavioral\n  text: Pages and features you use in the portal and actions you take\n- category: communication\n  text: Your email and what you write\npurposes:\n- purpose: Create and secure accounts, sign in, run the portal\n  text: Create and secure your Account, sign you in, and run the portal\n- purpose: Provide hosted services to Customers\n  text: Provide the hosted services to Customers and their apps\n- purpose: Meter usage, apply plans, bill\n  text: Meter usage, apply Plans, bill, and collect payment\n- purpose: Protect the Services\n  text: 'Protect the Services: rate limiting, abuse and fraud prevention, audit logs, error monitoring'\nretention:\n- scope: Developer Account\n  period: 30 days\n  text: we permanently delete your Account Data within 30 days\n- scope: Billing records\n  period: 7 years\n  text: Billing records (invoices, payment and usage records, and records of acceptance of the Developer Terms,\n    including the IP address)\
  \ 7 years, for tax, accounting, and dispute purposes\n- scope: Sign-in codes\n  period: 10 minutes\n  text: Sign-in codes 10 minutes, single use\n- scope: Relay messages\n  period: 7 days\n  text: Undelivered messages are queued for up to 7 days.\n- scope: Raw telemetry events\n  period: 30 days\n  text: Raw telemetry events 30 days\nresidency:\n- region: Singapore\n  text: Our databases and hosted services run on Railway in Singapore, and the relay also runs servers in the United\n    States.\n- region: United States, European Union, India\n  text: Our service providers process data in the United States, the European Union, India, and other countries\ntransfers:\n- mechanism: SCC\n  text: we use the European Commission’s Standard Contractual Clauses, the UK Addendum, or another lawful transfer\n    mechanism\nsubprocessors:\n  url: https://www.offlineprotocol.com/subprocessors\n  text: The full list, with what each receives and where, is on our subprocessors page\ndpa:\n  available: true\n\
  \  url: null\n  text: The measures that apply to Customer Data are listed in Annex 2 of the Data Processing Addendum\ndeletion:\n  route: Delete the developer Account in the portal, or request via legal@offlineprotocol.com\n  text: You can delete your developer Account in the portal. Deletion ends your access immediately, and we permanently\n    delete your Account Data within 30 days\nrights:\n- right: access, correct, erase, restrict, port\n  text: You have the right to access, correct, erase, restrict, and port your personal data\n- right: object and withdraw consent\n  text: to object to processing based on legitimate interests, and to withdraw consent at any time\n- right: know, delete, portability, opt out of sale/sharing\n  text: to know what personal information we collect and how we use and disclose it, to access, correct, and delete\n    it, to receive a portable copy, and to opt out of sale, sharing for targeted advertising, and profiling\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: We do not sell or share personal information and do not profile in ways that produce legal or similar effects.\n"
source_yaml_url: https://artifacts.apis.io/offlineprotocol-com/privacy/offlineprotocol-com-privacy-policy.yml
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
summary_line: 27 quoted statements, read from offlineprotocol-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Coordination
- Offline-First
- Mesh Networking
- IoT
---
