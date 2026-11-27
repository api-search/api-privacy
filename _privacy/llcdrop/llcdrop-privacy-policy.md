---
api_specs:
- filename: llcdrop-account-api-openapi.yml
  format: yaml
  label: LLCDrop Account API
  slug: llcdrop-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-account-api-openapi.yml
- filename: llcdrop-businesses-api-openapi.yml
  format: yaml
  label: LLCDrop Businesses API
  slug: llcdrop-businesses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-businesses-api-openapi.yml
- filename: llcdrop-counties-and-stats-api-openapi.yml
  format: yaml
  label: LLCDrop Counties and stats API
  slug: llcdrop-counties-and-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-counties-and-stats-api-openapi.yml
- filename: llcdrop-datasets-api-openapi.yml
  format: yaml
  label: LLCDrop Datasets API
  slug: llcdrop-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-datasets-api-openapi.yml
- filename: llcdrop-filings-api-openapi.yml
  format: yaml
  label: LLCDrop Filings API
  slug: llcdrop-filings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-filings-api-openapi.yml
- filename: llcdrop-parcels-api-openapi.yml
  format: yaml
  label: LLCDrop Parcels API
  slug: llcdrop-parcels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-parcels-api-openapi.yml
- filename: llcdrop-reference-lists-api-openapi.yml
  format: yaml
  label: LLCDrop Reference lists API
  slug: llcdrop-reference-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llcdrop/openapi/llcdrop-reference-lists-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Account information Name, email address, password (hashed), company name, role, team membership
  - category: financial
    text: Billing information Billing name and address, last four card digits, subscriptions, credit purchases, transaction history
  - category: device
    text: Usage and device data IP address, browser and device type, pages and features used, free-preview counts, timestamps, error logs.
  - category: professional
    text: Public-records business data (Lead Data) business name, Florida document number, filing and status dates, principal and mailing addresses, registered agent, names and titles of officers, managers and authorized persons
  deletion:
    route: Email privacy@llcdrop.com or use account settings; Lead Data removal via llcdrop.com/remove or remove@llcdrop.com
    text: ask us to delete your personal information, subject to legal exceptions
  dpa:
    available: true
    text: as set out in our agreement with them and our Data Processing Addendum
    url: Data Processing Addendum (linked from page)
  purposes:
  - purpose: Provide and manage account and Service
    text: create and manage your account, and provide the features you ask for
  - purpose: Process payments
    text: process payments, send receipts and manage subscriptions
  - purpose: Security and abuse prevention
    text: keep the Service secure, including detecting, investigating and preventing fraud, abuse, spam and security incidents
  - purpose: Publish and sell business leads
    text: We make Lead Data available to paying subscribers, who use it to find and contact newly formed businesses by email and postal mail.
  residency:
  - region: United States
    text: We are based in the United States, and your information is processed there.
  retention:
  - period: 30 days
    scope: Account information and customer content
    text: While your account is active, then deleted within 30 days of closure
  - period: 5 years
    scope: Outreach opt-out records
    text: opt-out, bounce and complaint records for up to 5 years so they keep being honored
  - period: 7 years
    scope: Billing and tax records
    text: Billing and tax records 7 years, as required by tax law
  - period: 12 months
    scope: Security and access logs
    text: Security and access logs Up to 12 months
  - period: 3 years
    scope: Support communications
    text: Support communications Up to 3 years after the request is resolved
  - period: 35 days
    scope: Encrypted backups
    text: Encrypted backups Up to 35 days on a rolling basis
  rights:
  - right: Access
    text: access and update most account information in your account settings
  - right: Portability
    text: ask for a copy of your personal information in a portable format
  - right: Correction
    text: ask us to correct inaccurate information
  - right: Deletion
    text: ask us to delete your personal information, subject to legal exceptions
  - right: Opt out of marketing
    text: unsubscribe from marketing emails using the link in any of them.
  role:
    text: For personal information we collect to run our own business, such as account, billing and website data, we are the "controller" (or "business") responsible for it.
    value: both
  sale_or_sharing:
    stance: conditional
    text: We make business records available to paying subscribers , which some state laws treat as a sale.
  subprocessors:
    text: The current list, with each provider's purpose and location, is on our Sub-processors page.
    url: Sub-processors page (linked from page)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: LLCDrop
provenance_date: '2026-11-09'
provider_name: LLCDrop
provider_slug: llcdrop
slug: llcdrop-privacy-policy
source_date: '2026-11-09'
source_filename: llcdrop-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://llcdrop.com/marketing/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: LLCDrop\naid: llcdrop\nurl: https://llcdrop.com/marketing/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For personal information we collect to run our own business, such as account, billing and website data,\n    we are the \"controller\" (or \"business\") responsible for it.\ndata_categories:\n- category: contact\n  text: Account information Name, email address, password (hashed), company name, role, team membership\n- category: financial\n  text: Billing information Billing name and address, last four card digits, subscriptions, credit purchases, transaction\n    history\n- category:\
  \ device\n  text: Usage and device data IP address, browser and device type, pages and features used, free-preview counts,\n    timestamps, error logs.\n- category: professional\n  text: Public-records business data (Lead Data) business name, Florida document number, filing and status dates,\n    principal and mailing addresses, registered agent, names and titles of officers, managers and authorized persons\npurposes:\n- purpose: Provide and manage account and Service\n  text: create and manage your account, and provide the features you ask for\n- purpose: Process payments\n  text: process payments, send receipts and manage subscriptions\n- purpose: Security and abuse prevention\n  text: keep the Service secure, including detecting, investigating and preventing fraud, abuse, spam and security\n    incidents\n- purpose: Publish and sell business leads\n  text: We make Lead Data available to paying subscribers, who use it to find and contact newly formed businesses\n    by email and postal\
  \ mail.\nretention:\n- scope: Account information and customer content\n  period: 30 days\n  text: While your account is active, then deleted within 30 days of closure\n- scope: Outreach opt-out records\n  period: 5 years\n  text: opt-out, bounce and complaint records for up to 5 years so they keep being honored\n- scope: Billing and tax records\n  period: 7 years\n  text: Billing and tax records 7 years, as required by tax law\n- scope: Security and access logs\n  period: 12 months\n  text: Security and access logs Up to 12 months\n- scope: Support communications\n  period: 3 years\n  text: Support communications Up to 3 years after the request is resolved\n- scope: Encrypted backups\n  period: 35 days\n  text: Encrypted backups Up to 35 days on a rolling basis\nresidency:\n- region: United States\n  text: We are based in the United States, and your information is processed there.\ntransfers: []\nsubprocessors:\n  url: Sub-processors page (linked from page)\n  text: The current list,\
  \ with each provider's purpose and location, is on our Sub-processors page.\ndpa:\n  available: true\n  url: Data Processing Addendum (linked from page)\n  text: as set out in our agreement with them and our Data Processing Addendum\ndeletion:\n  route: Email privacy@llcdrop.com or use account settings; Lead Data removal via llcdrop.com/remove or remove@llcdrop.com\n  text: ask us to delete your personal information, subject to legal exceptions\nrights:\n- right: Access\n  text: access and update most account information in your account settings\n- right: Portability\n  text: ask for a copy of your personal information in a portable format\n- right: Correction\n  text: ask us to correct inaccurate information\n- right: Deletion\n  text: ask us to delete your personal information, subject to legal exceptions\n- right: Opt out of marketing\n  text: unsubscribe from marketing emails using the link in any of them.\nsale_or_sharing:\n  stance: conditional\n  text: We make business records available\
  \ to paying subscribers , which some state laws treat as a sale.\n"
source_yaml_url: https://artifacts.apis.io/llcdrop/privacy/llcdrop-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from LLCDrop's own page on 2026-11-09.
synthetic: false
tags:
- Lead Generation
- Business Data
- Marketing
- Real Estate
---
