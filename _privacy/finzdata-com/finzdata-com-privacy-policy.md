---
api_specs:
- filename: finzdata-com-finzdata-api-openapi.yml
  format: yaml
  label: FinzData API
  slug: finzdata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finzdata-com/openapi/finzdata-com-finzdata-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account details: your email address and plan.'
  - category: contact
    text: 'Email brief: if you subscribe to the free daily brief, your email address and your confirmation and unsubscribe status.'
  - category: financial
    text: 'Payments: handled by Stripe. We receive your Stripe customer and subscription identifiers and payment status; we never see or store your full card number.'
  - category: location
    text: We record each sign-in, API request and file download with its time, IP address, approximate country and browser or client
  - category: device
    text: browser or client
  - category: communication
    text: 'Messages: anything you send to [email protected] .'
  deletion:
    route: email request
    text: You can ask to see, correct or delete your personal information, or to close your account, by emailing [email protected] from your account address.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run account and deliver data
    text: To run your account, issue keys and deliver the data your plan includes.
  - purpose: billing
    text: To bill you and manage your subscription.
  - purpose: enforce limits and security
    text: To enforce plan limits and protect the service from abuse.
  - purpose: service messages
    text: To send service messages, such as receipts, key changes, data incidents and changes to our terms.
  - purpose: answer questions
    text: To answer your questions.
  residency:
  - region: United States
    text: FinzData is operated from the United States, and your information is processed there.
  retention:
  - period: null
    scope: account and billing records
    text: 'Account and billing records: while your account is open and afterwards as long as tax and accounting law requires.'
  - period: up to 24 months
    scope: usage counts, access records and technical logs
    text: 'Usage counts, access records and technical logs: up to 24 months (download records for as long as the licence they relate to needs enforcing).'
  rights:
  - right: access, correction, deletion
    text: You can ask to see, correct or delete your personal information, or to close your account
  - right: object and restrict processing
    text: including to object to or restrict processing and to complain to a regulator.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your personal information, and we do not use it for third-party advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FinzData
provenance_date: '2026-11-09'
provider_name: FinzData
provider_slug: finzdata-com
slug: finzdata-com-privacy-policy
source_date: '2026-11-09'
source_filename: finzdata-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://finzdata.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FinzData\naid: finzdata-com\nurl: https://finzdata.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account details: your email address and plan.'\n- category: contact\n  text: 'Email brief: if you subscribe to the free daily brief, your email address and your confirmation and unsubscribe\n    status.'\n- category: financial\n  text: 'Payments: handled by Stripe. We receive your Stripe customer and subscription identifiers and payment status;\n    we never see or store your full card number.'\n- category: location\n  text: We\
  \ record each sign-in, API request and file download with its time, IP address, approximate country and\n    browser or client\n- category: device\n  text: browser or client\n- category: communication\n  text: 'Messages: anything you send to [email protected] .'\npurposes:\n- purpose: run account and deliver data\n  text: To run your account, issue keys and deliver the data your plan includes.\n- purpose: billing\n  text: To bill you and manage your subscription.\n- purpose: enforce limits and security\n  text: To enforce plan limits and protect the service from abuse.\n- purpose: service messages\n  text: To send service messages, such as receipts, key changes, data incidents and changes to our terms.\n- purpose: answer questions\n  text: To answer your questions.\nretention:\n- scope: account and billing records\n  period: null\n  text: 'Account and billing records: while your account is open and afterwards as long as tax and accounting law\n    requires.'\n- scope: usage counts, access\
  \ records and technical logs\n  period: up to 24 months\n  text: 'Usage counts, access records and technical logs: up to 24 months (download records for as long as the licence\n    they relate to needs enforcing).'\nresidency:\n- region: United States\n  text: FinzData is operated from the United States, and your information is processed there.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: You can ask to see, correct or delete your personal information, or to close your account, by emailing [email\n    protected] from your account address.\nrights:\n- right: access, correction, deletion\n  text: You can ask to see, correct or delete your personal information, or to close your account\n- right: object and restrict processing\n  text: including to object to or restrict processing and to complain to a regulator.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent\
  \ your personal information, and we do not use it for third-party advertising.\n"
source_yaml_url: https://artifacts.apis.io/finzdata-com/privacy/finzdata-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from FinzData's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Market Data
- Historical Data
- Python
---
