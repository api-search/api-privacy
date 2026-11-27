---
api_specs:
- filename: xoomar-com-companies-api-openapi.yml
  format: yaml
  label: XOOMAR Companies API
  slug: xoomar-com-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xoomar-com/openapi/xoomar-com-companies-api-openapi.yml
- filename: xoomar-com-crypto-api-openapi.yml
  format: yaml
  label: XOOMAR Crypto API
  slug: xoomar-com-crypto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xoomar-com/openapi/xoomar-com-crypto-api-openapi.yml
- filename: xoomar-com-macro-api-openapi.yml
  format: yaml
  label: XOOMAR Macro API
  slug: xoomar-com-macro-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xoomar-com/openapi/xoomar-com-macro-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, a name if you give one, a password (stored as a hash)
  - category: contact
    text: Your email address, your confirmation, your preferences and whether you unsubscribed.
  - category: financial
    text: we receive the plan, the amounts, the invoice, the last four digits of the card and a customer reference
  - category: device
    text: IP address and request headers, used in memory for rate limits and security and written to server logs
  - category: behavioral
    text: the number of requests each key makes per endpoint per day, the plan on the key, and the last time it was used
  - category: communication
    text: What you send through the contact and services forms, with your name, email and, to stop abuse, your IP address.
  deletion:
    route: 'Account page: Profile, then "Delete account"'
    text: Delete your account yourself; its personal data is erased within thirty days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run the Service
    text: 'To run the Service you asked for (contract): sign-in, keys, limits, plans, invoices, alerts, webhooks, answers to your messages.'
  - purpose: Security and fraud prevention
    text: 'To keep the Service secure and fair (legitimate interests): rate limits, abuse prevention, fraud checks on payments, logs, backups.'
  - purpose: Analytics and improvement
    text: 'To understand and improve the Service (legitimate interests, or consent where cookies require it): aggregate statistics, analytics.'
  - purpose: Newsletter and service emails
    text: the newsletter (consent, given with the box at signup or the subscribe form, withdrawn with one click)
  - purpose: Advertising
    text: To show ads (consent in the EEA, the UK and Switzerland; legitimate interests elsewhere, with the opt-out in section 6).
  retention:
  - period: Twenty-four months
    scope: Usage counts per key
    text: Usage counts per key Twenty-four months.
  - period: at most thirty days
    scope: Server logs
    text: Rotated automatically, kept for at most thirty days.
  - period: Seven years
    scope: Billing records
    text: Billing records Seven years, as tax law requires.
  - period: One minute and one day
    scope: Rate-limit counters
    text: Rate-limit counters One minute and one day, in memory, then gone.
  - period: Twenty-four months
    scope: Contact and service messages
    text: Contact and service messages Twenty-four months. The sender's IP address, kept only to stop abuse, is cleared after ninety days.
  rights:
  - right: access, rectification, erasure, restriction, portability, objection
    text: If you are in the EEA, the UK or Switzerland you also have the rights to access, rectification, erasure, restriction, portability and objection
  - right: know, delete and correct (US state)
    text: you have the rights to know, delete and correct, to opt out of the sale or sharing of personal data
  - right: withdraw consent
    text: to withdraw consent at any time without affecting earlier processing
  - right: complain to authority
    text: and to complain to your supervisory authority
  role:
    text: XOOMAR ("we", "us") operates xoomar.com, the XOOMAR API, the client libraries and the hosted MCP server (the "Service") and is the controller of the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and we do not share it for money.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: Where data leaves the EEA, the UK or Switzerland, we rely on an adequacy decision
  - mechanism: SCC
    text: on the European Commission's standard contractual clauses (and the UK addendum) in our providers' contracts
  - mechanism: DPF
    text: or on a provider's certification under the EU-US Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: XOOMAR
provenance_date: '2026-11-10'
provider_name: XOOMAR
provider_slug: xoomar-com
slug: xoomar-com-privacy-policy
source_date: '2026-11-10'
source_filename: xoomar-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://xoomar.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: XOOMAR\naid: xoomar-com\nurl: https://xoomar.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: XOOMAR (\"we\", \"us\") operates xoomar.com, the XOOMAR API, the client libraries and the hosted MCP server\n    (the \"Service\") and is the controller of the personal data described here.\ndata_categories:\n- category: identifying\n  text: Email address, a name if you give one, a password (stored as a hash)\n- category: contact\n  text: Your email address, your confirmation, your preferences and whether you unsubscribed.\n- category: financial\n  text: we receive the plan, the amounts,\
  \ the invoice, the last four digits of the card and a customer reference\n- category: device\n  text: IP address and request headers, used in memory for rate limits and security and written to server logs\n- category: behavioral\n  text: the number of requests each key makes per endpoint per day, the plan on the key, and the last time it was\n    used\n- category: communication\n  text: What you send through the contact and services forms, with your name, email and, to stop abuse, your IP\n    address.\npurposes:\n- purpose: Run the Service\n  text: 'To run the Service you asked for (contract): sign-in, keys, limits, plans, invoices, alerts, webhooks,\n    answers to your messages.'\n- purpose: Security and fraud prevention\n  text: 'To keep the Service secure and fair (legitimate interests): rate limits, abuse prevention, fraud checks\n    on payments, logs, backups.'\n- purpose: Analytics and improvement\n  text: 'To understand and improve the Service (legitimate interests, or consent\
  \ where cookies require it): aggregate\n    statistics, analytics.'\n- purpose: Newsletter and service emails\n  text: the newsletter (consent, given with the box at signup or the subscribe form, withdrawn with one click)\n- purpose: Advertising\n  text: To show ads (consent in the EEA, the UK and Switzerland; legitimate interests elsewhere, with the opt-out\n    in section 6).\nretention:\n- scope: Usage counts per key\n  period: Twenty-four months\n  text: Usage counts per key Twenty-four months.\n- scope: Server logs\n  period: at most thirty days\n  text: Rotated automatically, kept for at most thirty days.\n- scope: Billing records\n  period: Seven years\n  text: Billing records Seven years, as tax law requires.\n- scope: Rate-limit counters\n  period: One minute and one day\n  text: Rate-limit counters One minute and one day, in memory, then gone.\n- scope: Contact and service messages\n  period: Twenty-four months\n  text: Contact and service messages Twenty-four months. The sender's\
  \ IP address, kept only to stop abuse, is cleared\n    after ninety days.\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: Where data leaves the EEA, the UK or Switzerland, we rely on an adequacy decision\n- mechanism: SCC\n  text: on the European Commission's standard contractual clauses (and the UK addendum) in our providers' contracts\n- mechanism: DPF\n  text: or on a provider's certification under the EU-US Data Privacy Framework.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: 'Account page: Profile, then \"Delete account\"'\n  text: Delete your account yourself; its personal data is erased within thirty days.\nrights:\n- right: access, rectification, erasure, restriction, portability, objection\n  text: If you are in the EEA, the UK or Switzerland you also have the rights to access, rectification, erasure,\n    restriction, portability and objection\n- right: know, delete and correct (US state)\n  text:\
  \ you have the rights to know, delete and correct, to opt out of the sale or sharing of personal data\n- right: withdraw consent\n  text: to withdraw consent at any time without affecting earlier processing\n- right: complain to authority\n  text: and to complain to your supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and we do not share it for money.\n"
source_yaml_url: https://artifacts.apis.io/xoomar-com/privacy/xoomar-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from XOOMAR's own page on 2026-11-10.
synthetic: false
tags:
- Capital Markets
- Data
- Financial Services
- Software
---
