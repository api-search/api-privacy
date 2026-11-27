---
api_specs:
- filename: candor-money-conversations-api-openapi.yml
  format: yaml
  label: Candor Finance Conversations API
  slug: candor-money-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/candor-money/openapi/candor-money-conversations-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: email address; name if you provide one; authentication identifiers and email verification status
  - category: financial
    text: transactions, dates, amounts, merchants, descriptions, categories, pending or posted status, and related details
  - category: location
    text: property addresses and types, ownership shares, mortgage links, paid-off status
  - category: behavioral
    text: frontend interaction metadata such as page views, clicks, form submissions, and masked UI element metadata
  - category: device
    text: device and online identifiers, such as cookie identifiers, advertising and ad click identifiers, IP address, and browser and device information
  - category: communication
    text: emails and messages you send us; security reports; feedback, troubleshooting details, and related information
  deletion:
    route: Delete your Candor data through Candor controls, or email privacy@candor.money
    text: Data deletion immediately revokes active OAuth access and removes provider credentials, then deletes the deletable online financial workspace, including financial records, agent- and user-authored workspace state, raw source records, and user-visible action history.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and secure the service
    text: provide, secure, debug, and improve Candor
  - purpose: Advertising and measurement
    text: advertise Candor, measure and improve our ads, and show them to people who may be interested, without using financial data
  - purpose: Analytics
    text: measure public site, waitlist, onboarding, and hosted control-plane usage
  - purpose: Legal compliance
    text: comply with legal, regulatory, contractual, and provider obligations
  residency:
  - region: United States and other countries
    text: your information may be processed in the United States and other countries where our service providers operate
  retention:
  - period: null
    scope: Financial records
    text: Financial records are kept while your Candor account is active.
  - period: 7 days
    scope: Encrypted operation receipts and deletion-progress receipts
    text: encrypted operation receipts and completed deletion-progress receipts become eligible for deletion after 7 days
  - period: 90 days
    scope: Sanitized maintenance and operational logs
    text: sanitized maintenance and operational logs are retained for up to 90 days
  - period: 14 days
    scope: Managed database backups
    text: managed database backups expire on provider schedules of up to 14 days
  rights:
  - right: access
    text: you may have rights to access, correct, delete, export, restrict, or object to certain processing of your personal information
  - right: opt out of sharing via Global Privacy Control
    text: You may opt out by enabling Global Privacy Control in your browser or by emailing privacy@candor.money.
  role:
    text: '"Candor", "we", "us", and "our" mean the Candor service and the organization that provides it'
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not sell your personal information for money. We do not sell your financial information or share it for targeted advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Candor Finance
provenance_date: '2026-11-09'
provider_name: Candor Finance
provider_slug: candor-money
slug: candor-money-privacy-policy
source_date: '2026-11-09'
source_filename: candor-money-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://candor.money/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Candor Finance\naid: candor-money\nurl: https://candor.money/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: '\"Candor\", \"we\", \"us\", and \"our\" mean the Candor service and the organization that provides it'\ndata_categories:\n- category: identifying\n  text: email address; name if you provide one; authentication identifiers and email verification status\n- category: financial\n  text: transactions, dates, amounts, merchants, descriptions, categories, pending or posted status, and related\n    details\n- category: location\n  text: property addresses and types, ownership shares,\
  \ mortgage links, paid-off status\n- category: behavioral\n  text: frontend interaction metadata such as page views, clicks, form submissions, and masked UI element metadata\n- category: device\n  text: device and online identifiers, such as cookie identifiers, advertising and ad click identifiers, IP address,\n    and browser and device information\n- category: communication\n  text: emails and messages you send us; security reports; feedback, troubleshooting details, and related information\npurposes:\n- purpose: Provide and secure the service\n  text: provide, secure, debug, and improve Candor\n- purpose: Advertising and measurement\n  text: advertise Candor, measure and improve our ads, and show them to people who may be interested, without using\n    financial data\n- purpose: Analytics\n  text: measure public site, waitlist, onboarding, and hosted control-plane usage\n- purpose: Legal compliance\n  text: comply with legal, regulatory, contractual, and provider obligations\nretention:\n\
  - scope: Financial records\n  period: null\n  text: Financial records are kept while your Candor account is active.\n- scope: Encrypted operation receipts and deletion-progress receipts\n  period: 7 days\n  text: encrypted operation receipts and completed deletion-progress receipts become eligible for deletion after\n    7 days\n- scope: Sanitized maintenance and operational logs\n  period: 90 days\n  text: sanitized maintenance and operational logs are retained for up to 90 days\n- scope: Managed database backups\n  period: 14 days\n  text: managed database backups expire on provider schedules of up to 14 days\nresidency:\n- region: United States and other countries\n  text: your information may be processed in the United States and other countries where our service providers operate\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your Candor data through Candor controls, or email privacy@candor.money\n\
  \  text: Data deletion immediately revokes active OAuth access and removes provider credentials, then deletes the\n    deletable online financial workspace, including financial records, agent- and user-authored workspace state,\n    raw source records, and user-visible action history.\nrights:\n- right: access\n  text: you may have rights to access, correct, delete, export, restrict, or object to certain processing of your\n    personal information\n- right: opt out of sharing via Global Privacy Control\n  text: You may opt out by enabling Global Privacy Control in your browser or by emailing privacy@candor.money.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell your personal information for money. We do not sell your financial information or share it\n    for targeted advertising.\n"
source_yaml_url: https://artifacts.apis.io/candor-money/privacy/candor-money-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Candor Finance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Artificial Intelligence
- Personal Finance
- Budgeting
---
