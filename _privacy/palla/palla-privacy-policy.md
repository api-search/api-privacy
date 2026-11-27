---
api_specs:
- filename: palla-accounts-api-openapi.yml
  format: yaml
  label: Palla Accounts API
  slug: palla-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/palla/openapi/palla-accounts-api-openapi.yml
- filename: palla-auth-api-openapi.yml
  format: yaml
  label: Palla Auth API
  slug: palla-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/palla/openapi/palla-auth-api-openapi.yml
- filename: palla-health-api-openapi.yml
  format: yaml
  label: Palla Health API
  slug: palla-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/palla/openapi/palla-health-api-openapi.yml
- filename: palla-links-api-openapi.yml
  format: yaml
  label: Palla Links API
  slug: palla-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/palla/openapi/palla-links-api-openapi.yml
- filename: palla-payment-methods-api-openapi.yml
  format: yaml
  label: Palla Payment Methods API
  slug: palla-payment-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/palla/openapi/palla-payment-methods-api-openapi.yml
- filename: palla-relationships-api-openapi.yml
  format: yaml
  label: Palla Relationships API
  slug: palla-relationships-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/palla/openapi/palla-relationships-api-openapi.yml
- filename: palla-transfers-api-openapi.yml
  format: yaml
  label: Palla Transfers API
  slug: palla-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/palla/openapi/palla-transfers-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Domestic and foreign government issued identification numbers such as driver's license, passport, visa, social security number or tax identification number
  - category: contact
    text: Date of birth, address, email address, occupation, employer, mobile number, nationality, country of birth, gender
  - category: financial
    text: Debit card information, such as the card number, issuer, expiration date, security code, and any bank account and account balances information
  - category: financial
    text: Transaction history
  - category: communication
    text: Phone conversations and email communications
  - category: device
    text: Internet protocol (IP) address, geo-location information, browser type, internet service provider (ISP), referring/exit pages, operating system, date/time stamp, and/or clickstream data
  - category: behavioral
    text: Transactional profile, monthly transaction amount, frequency of transfers, parties to transactions
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: everyday business purposes
    text: For our everyday business purposes - such as to process your transactions, maintain your account(s), respond to court orders and legal investigations, or report to credit bureaus
  - purpose: own marketing
    text: For our marketing purposes - to offer our products and services to you or send you marketing and promotional messages
  - purpose: targeted advertising and improving website
    text: contacting and corresponding with you, responding to your inquiries, improving our website, targeted advertising, offering media products you request
  residency:
  - region: United States and elsewhere
    text: You consent to our collection, transfer, and storage of information by computers or other transfer or storage devices in the United States and elsewhere.
  rights:
  - right: limit sharing
    text: Federal and certain state laws also give consumers the right to limit some but not all sharing.
  - right: opt out of targeted advertising sharing
    text: you may opt out of our sharing your personal information for targeted advertising purposes by submitting a request through the "Your Privacy Choices" link in our footer of our website.
  - right: withdraw cookie consent
    text: You may withdraw your consent at any time with effect for the future.
  - right: marketing opt-out
    text: If you do not want us to use your email address or contact information to receive marketing related emails or text messages from us going forward, you can opt-out
  role:
    text: Palla Financial Inc. ("Palla", "we", "us", or "our") takes privacy very seriously
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Currently, Palla does not sell information for marketing purposes to affiliates or non-affiliates.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Palla
provenance_date: '2026-11-10'
provider_name: Palla
provider_slug: palla
slug: palla-privacy-policy
source_date: '2026-11-10'
source_filename: palla-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.palla.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Palla\naid: palla\nurl: https://www.palla.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Palla Financial Inc. (\"Palla\", \"we\", \"us\", or \"our\") takes privacy very seriously\ndata_categories:\n- category: identifying\n  text: Domestic and foreign government issued identification numbers such as driver's license, passport, visa,\n    social security number or tax identification number\n- category: contact\n  text: Date of birth, address, email address, occupation, employer, mobile number, nationality, country of birth,\n    gender\n- category: financial\n  text: Debit\
  \ card information, such as the card number, issuer, expiration date, security code, and any bank account\n    and account balances information\n- category: financial\n  text: Transaction history\n- category: communication\n  text: Phone conversations and email communications\n- category: device\n  text: Internet protocol (IP) address, geo-location information, browser type, internet service provider (ISP),\n    referring/exit pages, operating system, date/time stamp, and/or clickstream data\n- category: behavioral\n  text: Transactional profile, monthly transaction amount, frequency of transfers, parties to transactions\npurposes:\n- purpose: everyday business purposes\n  text: For our everyday business purposes - such as to process your transactions, maintain your account(s), respond\n    to court orders and legal investigations, or report to credit bureaus\n- purpose: own marketing\n  text: For our marketing purposes - to offer our products and services to you or send you marketing\
  \ and promotional\n    messages\n- purpose: targeted advertising and improving website\n  text: contacting and corresponding with you, responding to your inquiries, improving our website, targeted advertising,\n    offering media products you request\nretention: []\nresidency:\n- region: United States and elsewhere\n  text: You consent to our collection, transfer, and storage of information by computers or other transfer or storage\n    devices in the United States and elsewhere.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: limit sharing\n  text: Federal and certain state laws also give consumers the right to limit some but not all sharing.\n- right: opt out of targeted advertising sharing\n  text: you may opt out of our sharing your personal information for targeted advertising purposes by submitting\n    a request through the \"Your Privacy Choices\" link in our\
  \ footer of our website.\n- right: withdraw cookie consent\n  text: You may withdraw your consent at any time with effect for the future.\n- right: marketing opt-out\n  text: If you do not want us to use your email address or contact information to receive marketing related emails\n    or text messages from us going forward, you can opt-out\nsale_or_sharing:\n  stance: conditional\n  text: Currently, Palla does not sell information for marketing purposes to affiliates or non-affiliates.\n"
source_yaml_url: https://artifacts.apis.io/palla/privacy/palla-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- residency
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Palla's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Cross-Border Payments
- Remittances
- P2P Payments
- Money Transfer
- Embedded Finance
---
