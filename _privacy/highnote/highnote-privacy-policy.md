---
api_specs:
- filename: highnote-graph-ql-api-openapi.yml
  format: yaml
  label: Highnote Graph QL API
  slug: highnote-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/highnote/openapi/highnote-graph-ql-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, we collect information such as your name, email address, social security number, date of birth, phone number, and residential address.
  - category: financial
    text: For business accounts, we may also collect your business name, address, and bank information.
  - category: financial
    text: 'Transaction Data: When you perform a transaction, we collect data such as the amount, date, and payment method to process it.'
  - category: device
    text: 'Automatically Collected Information: We automatically collect information when you use our Services, including your IP address, device information, browser type, and usage data through cookies and similar technologies.'
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide, maintain and improve services
    text: To provide, maintain, and improve our Services.
  - purpose: process transactions
    text: To process transactions and send you related information.
  - purpose: identity verification and fraud prevention
    text: To verify your identity and prevent fraud.
  - purpose: marketing communications
    text: To communicate with you about products, services, and offers.
  - purpose: legal compliance
    text: To comply with legal obligations and enforce our terms.
  retention:
  - period: duration of our business relationship
    scope: account information
    text: 'Account Information: We retain your account information for the duration of our business relationship.'
  - period: 7 years
    scope: cardholder data
    text: Upon account closure, cardholder data is retained for a period of 7 years to comply with legal and regulatory obligations, after which it is securely and automatically deleted.
  rights:
  - right: opt out of promotional emails
    text: You can opt out of receiving promotional emails from us by following the "unsubscribe" link in those emails.
  - right: limit some sharing of personal financial information (GLBA)
    text: Under the Gramm-Leach-Bliley Act (GLBA), you have the right to limit some, but not all, sharing of your personal financial information.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell your personal information to third parties for their promotional purposes.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Highnote
provenance_date: '2026-11-09'
provider_name: Highnote
provider_slug: highnote
slug: highnote-privacy-policy
source_date: '2026-11-09'
source_filename: highnote-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://highnote.com/agreements/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Highnote\naid: highnote\nurl: https://highnote.com/agreements/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account, we collect information such as your name, email address, social security number,\n    date of birth, phone number, and residential address.\n- category: financial\n  text: For business accounts, we may also collect your business name, address, and bank information.\n- category: financial\n  text: 'Transaction Data: When you perform a transaction, we collect data such as the amount, date, and payment\n\
  \    method to process it.'\n- category: device\n  text: 'Automatically Collected Information: We automatically collect information when you use our Services, including\n    your IP address, device information, browser type, and usage data through cookies and similar technologies.'\npurposes:\n- purpose: provide, maintain and improve services\n  text: To provide, maintain, and improve our Services.\n- purpose: process transactions\n  text: To process transactions and send you related information.\n- purpose: identity verification and fraud prevention\n  text: To verify your identity and prevent fraud.\n- purpose: marketing communications\n  text: To communicate with you about products, services, and offers.\n- purpose: legal compliance\n  text: To comply with legal obligations and enforce our terms.\nretention:\n- scope: account information\n  period: duration of our business relationship\n  text: 'Account Information: We retain your account information for the duration of our business\
  \ relationship.'\n- scope: cardholder data\n  period: 7 years\n  text: Upon account closure, cardholder data is retained for a period of 7 years to comply with legal and regulatory\n    obligations, after which it is securely and automatically deleted.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: opt out of promotional emails\n  text: You can opt out of receiving promotional emails from us by following the \"unsubscribe\" link in those emails.\n- right: limit some sharing of personal financial information (GLBA)\n  text: Under the Gramm-Leach-Bliley Act (GLBA), you have the right to limit some, but not all, sharing of your\n    personal financial information.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell your personal information to third parties for their promotional purposes.\n"
source_yaml_url: https://artifacts.apis.io/highnote/privacy/highnote-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from Highnote's own page on 2026-11-09.
synthetic: false
tags:
- Card Issuing
- Card Acquiring
- Embedded Finance
- Banking as a Service
- Fintech
- Payments
- GraphQL
- Ledger
- Credit
- Money Movement
- ACH
- KYC
- United States
---
