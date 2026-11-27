---
api_specs:
- filename: bookmyhost-public-openapi.json
  format: json
  label: BookMyHost API
  slug: bookmyhost-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bookmyhost/openapi/_original/bookmyhost-public-openapi.json
- filename: openapi.json
  format: json
  label: BookMyHost AI API (LiteLLM proxy)
  slug: bookmyhost-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bookmyhost/openapi/_original/openapi.json
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data — name, email, phone, company details, addresses, GSTIN.
  - category: identifying
    text: Identity verification (KYC) — for Indian individuals, name, masked Aadhaar number, date of birth, gender, address and photograph received from DigiLocker with your consent
  - category: financial
    text: Billing data — orders, invoices, wallet ledger, and payment references from our payment gateway.
  - category: device
    text: Technical data — IP addresses, login and API activity, service allocation records, and resource-usage metering.
  - category: communication
    text: Support data — tickets and correspondence.
  deletion:
    route: support ticket
    text: You can ask for earlier deletion through a support ticket; we delete it within 7 days and confirm by email.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service provision and billing
    text: To provide, meter and bill the services you order (performance of contract).
  - purpose: security
    text: 'To secure the platform: fraud prevention, abuse detection, login protection.'
  - purpose: marketing
    text: Marketing mail is sent only with consent and always with an opt-out.
  - purpose: AI phone call records
    text: Calls with our AI phone agent are recorded as a transcript and summary, which we keep with your support and sales records.
  residency:
  - region: India
    text: Your account data, KYC records, logs and hosted content are stored on our own infrastructure located in India.
  retention:
  - period: 180 days
    scope: System, access and API logs
    text: System, access and API logs — 180 days (CERT-In direction).
  - period: 5 years after account closure
    scope: Subscriber identity, KYC and service-allocation records
    text: Subscriber identity, KYC and service-allocation records — 5 years after account closure (CERT-In direction).
  - period: 8 years
    scope: Invoices and financial ledgers
    text: Invoices and financial ledgers — 8 years (GST and Companies Act requirements).
  - period: up to 90 days
    scope: Terminated cloud server disks
    text: We keep an encrypted copy of a terminated cloud server's disks for up to 90 days so that you can recover it
  rights:
  - right: access
    text: you may access a summary of your personal data
  - right: correction
    text: correct or update it (most of it directly in the panel)
  - right: withdraw consent
    text: withdraw consent
  - right: erasure
    text: request erasure — which we honour except for records we must keep under clause 4
  role:
    text: the data fiduciary under the Digital Personal Data Protection Act, 2023
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: It is shared only with processors needed to run the service
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Blazing Bullet Private Limited
provenance_date: '2026-11-09'
provider_name: Blazing Bullet Private Limited
provider_slug: bookmyhost
slug: bookmyhost-privacy-policy
source_date: '2026-11-09'
source_filename: bookmyhost-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bookmyhost.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Blazing Bullet Private Limited\naid: bookmyhost\nurl: https://bookmyhost.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: the data fiduciary under the Digital Personal Data Protection Act, 2023\ndata_categories:\n- category: identifying\n  text: Account data — name, email, phone, company details, addresses, GSTIN.\n- category: identifying\n  text: Identity verification (KYC) — for Indian individuals, name, masked Aadhaar number, date of birth, gender,\n    address and photograph received from DigiLocker with your consent\n- category: financial\n  text: Billing data — orders, invoices,\
  \ wallet ledger, and payment references from our payment gateway.\n- category: device\n  text: Technical data — IP addresses, login and API activity, service allocation records, and resource-usage metering.\n- category: communication\n  text: Support data — tickets and correspondence.\npurposes:\n- purpose: service provision and billing\n  text: To provide, meter and bill the services you order (performance of contract).\n- purpose: security\n  text: 'To secure the platform: fraud prevention, abuse detection, login protection.'\n- purpose: marketing\n  text: Marketing mail is sent only with consent and always with an opt-out.\n- purpose: AI phone call records\n  text: Calls with our AI phone agent are recorded as a transcript and summary, which we keep with your support\n    and sales records.\nretention:\n- scope: System, access and API logs\n  period: 180 days\n  text: System, access and API logs — 180 days (CERT-In direction).\n- scope: Subscriber identity, KYC and service-allocation\
  \ records\n  period: 5 years after account closure\n  text: Subscriber identity, KYC and service-allocation records — 5 years after account closure (CERT-In direction).\n- scope: Invoices and financial ledgers\n  period: 8 years\n  text: Invoices and financial ledgers — 8 years (GST and Companies Act requirements).\n- scope: Terminated cloud server disks\n  period: up to 90 days\n  text: We keep an encrypted copy of a terminated cloud server's disks for up to 90 days so that you can recover\n    it\nresidency:\n- region: India\n  text: Your account data, KYC records, logs and hosted content are stored on our own infrastructure located in\n    India.\ntransfers: []\nsubprocessors:\n  url: null\n  text: It is shared only with processors needed to run the service\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: support ticket\n  text: You can ask for earlier deletion through a support ticket; we delete it within 7 days and confirm by email.\nrights:\n- right: access\n\
  \  text: you may access a summary of your personal data\n- right: correction\n  text: correct or update it (most of it directly in the panel)\n- right: withdraw consent\n  text: withdraw consent\n- right: erasure\n  text: request erasure — which we honour except for records we must keep under clause 4\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/bookmyhost/privacy/bookmyhost-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Blazing Bullet Private Limited's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud
- Hosting
- VPS
- India
---
