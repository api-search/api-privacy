---
api_specs:
- filename: ipwho-org-openapi-generated.yml
  format: yaml
  label: IPWho.org API
  slug: ipwho-org-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipwho-org/openapi/_ae-authored/ipwho-org-openapi-generated.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, email, company, credentials
  - category: financial
    text: billing details (processed by our payment provider — we do not store raw card numbers)
  - category: device
    text: device and network data such as IP address, browser, OS, and referring URLs
  - category: behavioral
    text: Dashboard and API usage telemetry, request volumes
  - category: communication
    text: your support communications
  deletion:
    route: Contact privacy@lavrox.com to exercise rights over account data
    text: To exercise rights over your account data , contact privacy@lavrox.com .
  dpa:
    available: true
    text: 'Processor: When your application sends your end-users’ data (e.g. an IP address sent to the IPWho API) to us, you are the controller and we act solely as your processor under our Data Processing Addendum .'
    url: null
  purposes:
  - purpose: Provide accounts, process payments, operate the platform
    text: Provide accounts, process payments, operate the platform
  - purpose: Prevent fraud and abuse, secure and debug the Service
    text: Prevent fraud/abuse, enforce limits, secure & debug the Service
  - purpose: Improve and develop the Service
    text: Improve and develop the Service
  - purpose: Direct marketing (with opt-out)
    text: Direct marketing (with opt-out)
  residency:
  - region: Global network
    text: Data may be routed to and processed at any origin server within our network (across North America, Europe, Asia Pacific, the Middle East, Latin America, and Africa, and future locations)
  retention:
  - period: 30–90 days
    scope: Identifiable infrastructure logs
    text: 'Identifiable infrastructure logs: 30–90 days, then deleted (except records held for an active security investigation or as law requires).'
  - period: for the life of your subscription and afterwards as needed for audit, tax, dispute-resolution, and enforcement purposes
    scope: Account & billing data
    text: 'Account & billing data: for the life of your subscription and afterwards as needed for audit, tax, dispute-resolution, and enforcement purposes, unless you request deletion and no legal exception applies.'
  rights:
  - right: access and correction (APPs)
    text: 'Australia (APPs): access and correction'
  - right: access, correction, deletion, portability, restriction, objection (GDPR)
    text: 'EU/UK (GDPR): access, correction, deletion, portability, restriction, and objection'
  - right: know, access, delete, correct (CCPA/CPRA)
    text: You have the right to know, access, delete, and correct, and to non-discrimination for exercising these rights.
  role:
    text: 'Controller: When you create a Lavrox account, enter billing details, or use our Dashboard/websites, we are the controller of that account and interaction data. Processor: When your application sends your end-users’ data (e.g. an IP address sent to the IPWho API) to us, you are the controller and we act solely as your processor under our Data Processing Addendum .'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share personal information for cross-context behavioural advertising.
  subprocessors:
    text: Subprocessors Notice for categories (hosting, edge/CDN/WAF, payments, email, analytics, contractors)
    url: null
  transfers:
  - mechanism: SCC
    text: We rely on appropriate safeguards, including Standard Contractual Clauses, for cross-border transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: IPWho.org
provenance_date: '2026-11-09'
provider_name: IPWho.org
provider_slug: ipwho-org
slug: ipwho-org-privacy-policy
source_date: '2026-11-09'
source_filename: ipwho-org-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://lavrox.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: IPWho.org\naid: ipwho-org\nurl: https://lavrox.com/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Controller: When you create a Lavrox account, enter billing details, or use our Dashboard/websites, we\n    are the controller of that account and interaction data. Processor: When your application sends your end-users’\n    data (e.g. an IP address sent to the IPWho API) to us, you are the controller and we act solely as your processor\n    under our Data Processing Addendum .'\ndata_categories:\n- category: identifying\n  text: name, email, company, credentials\n- category: financial\n\
  \  text: billing details (processed by our payment provider — we do not store raw card numbers)\n- category: device\n  text: device and network data such as IP address, browser, OS, and referring URLs\n- category: behavioral\n  text: Dashboard and API usage telemetry, request volumes\n- category: communication\n  text: your support communications\npurposes:\n- purpose: Provide accounts, process payments, operate the platform\n  text: Provide accounts, process payments, operate the platform\n- purpose: Prevent fraud and abuse, secure and debug the Service\n  text: Prevent fraud/abuse, enforce limits, secure & debug the Service\n- purpose: Improve and develop the Service\n  text: Improve and develop the Service\n- purpose: Direct marketing (with opt-out)\n  text: Direct marketing (with opt-out)\nretention:\n- scope: Identifiable infrastructure logs\n  period: 30–90 days\n  text: 'Identifiable infrastructure logs: 30–90 days, then deleted (except records held for an active security\n    investigation\
  \ or as law requires).'\n- scope: Account & billing data\n  period: for the life of your subscription and afterwards as needed for audit, tax, dispute-resolution, and enforcement\n    purposes\n  text: 'Account & billing data: for the life of your subscription and afterwards as needed for audit, tax, dispute-resolution,\n    and enforcement purposes, unless you request deletion and no legal exception applies.'\nresidency:\n- region: Global network\n  text: Data may be routed to and processed at any origin server within our network (across North America, Europe,\n    Asia Pacific, the Middle East, Latin America, and Africa, and future locations)\ntransfers:\n- mechanism: SCC\n  text: We rely on appropriate safeguards, including Standard Contractual Clauses, for cross-border transfers.\nsubprocessors:\n  url: null\n  text: Subprocessors Notice for categories (hosting, edge/CDN/WAF, payments, email, analytics, contractors)\ndpa:\n  available: true\n  url: null\n  text: 'Processor: When your\
  \ application sends your end-users’ data (e.g. an IP address sent to the IPWho API)\n    to us, you are the controller and we act solely as your processor under our Data Processing Addendum .'\ndeletion:\n  route: Contact privacy@lavrox.com to exercise rights over account data\n  text: To exercise rights over your account data , contact privacy@lavrox.com .\nrights:\n- right: access and correction (APPs)\n  text: 'Australia (APPs): access and correction'\n- right: access, correction, deletion, portability, restriction, objection (GDPR)\n  text: 'EU/UK (GDPR): access, correction, deletion, portability, restriction, and objection'\n- right: know, access, delete, correct (CCPA/CPRA)\n  text: You have the right to know, access, delete, and correct, and to non-discrimination for exercising these\n    rights.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share personal information for cross-context behavioural advertising.\n"
source_yaml_url: https://artifacts.apis.io/ipwho-org/privacy/ipwho-org-privacy-policy.yml
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
summary_line: 21 quoted statements, read from IPWho.org's own page on 2026-11-09.
synthetic: false
tags:
- Company
- IP Geolocation
- Free Tier
---
