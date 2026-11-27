---
api_specs:
- filename: back-market-backbox-api-openapi.yml
  format: yaml
  label: Back Market Backbox API
  slug: back-market-backbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-backbox-api-openapi.yml
- filename: back-market-backship-api-openapi.yml
  format: yaml
  label: Back Market Backship API
  slug: back-market-backship-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-backship-api-openapi.yml
- filename: back-market-care-api-openapi.yml
  format: yaml
  label: Back Market Care API
  slug: back-market-care-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-care-api-openapi.yml
- filename: back-market-categories-api-openapi.yml
  format: yaml
  label: Back Market Categories API
  slug: back-market-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-categories-api-openapi.yml
- filename: back-market-listings-api-openapi.yml
  format: yaml
  label: Back Market Listings API
  slug: back-market-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-listings-api-openapi.yml
- filename: back-market-orderline-api-openapi.yml
  format: yaml
  label: Back Market Orderline API
  slug: back-market-orderline-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-orderline-api-openapi.yml
- filename: back-market-orders-api-openapi.yml
  format: yaml
  label: Back Market Orders API
  slug: back-market-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-orders-api-openapi.yml
- filename: back-market-buy-back-api-openapi.yml
  format: yaml
  label: Back Market Buy Back API
  slug: back-market-buy-back-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-buy-back-api-openapi.yml
- filename: back-market-task-manager-api-openapi.yml
  format: yaml
  label: Back Market task manager API
  slug: back-market-task-manager-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-task-manager-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your last name, first name, e-mail address, phone number, delivery address and billing address
  - category: financial
    text: Your bank and payment details; however, only the payment service provider will have access to your full payment card details
  - category: device
    text: Device unique identifiers (such as IMEI or serial number) of devices you purchase or trade-in from our platform)
  - category: behavioral
    text: The data relating to your connection and browsing activity on the Platform (in particular IP address, pages and products viewed)
  - category: biometric
    text: This facial biometric verification system verifies automatically the authenticity of your ID and confirms it belongs to you by comparing the face on the ID with a selfie video you provide in the same flow.
  - category: communication
    text: Recording of your calls to our Customer Service, unless you object to it
  deletion:
    route: Delete account in My profile section
    text: 'You can directly and at any time : delete your Back Market customer account via the “My profile” section of your personal account.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Use of the services on the Platform
    text: Access to and browsing on the Platform
  - purpose: Direct marketing
    text: Direct marketing and email newsletters
  - purpose: Personalized ads
    text: Serving personalized online ads based on your preferences and browsing habits
  - purpose: Fraud prevention
    text: Preventing and fighting against fraud
  - purpose: Improving services
    text: Carrying out statistical analyses of the use of our Platform
  retention:
  - period: null
    scope: Personal data generally
    text: Your personal data will be stored in compliance with applicable data protection laws, and only for as long as necessary to fulfill the processing purposes described in this Privacy Policy.
  rights:
  - right: Access
    text: You may request access to and rectification or, where appropriate, erasure of your Personal Data.
  - right: Objection
    text: You may also, in certain cases, object to the Processing of your Personal Data or request that the Processing be restricted
  - right: Portability
    text: You also have the right to data portability .
  - right: Opt-out of targeted advertising
    text: Residents of certain states of the United States may also have the right to opt-out of the sale of personal information and the sharing of personal information for targeted advertising.
  role:
    text: 'Back Market collects and processes your Personal Data:'
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Please be reassured that we do not sell your information to third parties. However we may share your personal information to our advertising partners, for cross-context behavioral advertising
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Back Market
provenance_date: '2026-11-09'
provider_name: Back Market
provider_slug: back-market
slug: back-market-privacy-policy
source_date: '2026-11-09'
source_filename: back-market-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.backmarket.com/en-us/legal/data-protection
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Back Market\naid: back-market\nurl: https://www.backmarket.com/en-us/legal/data-protection\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Back Market collects and processes your Personal Data:'\ndata_categories:\n- category: identifying\n  text: Your last name, first name, e-mail address, phone number, delivery address and billing address\n- category: financial\n  text: Your bank and payment details; however, only the payment service provider will have access to your full\n    payment card details\n- category: device\n  text: Device unique identifiers (such as IMEI or serial number) of devices\
  \ you purchase or trade-in from our platform)\n- category: behavioral\n  text: The data relating to your connection and browsing activity on the Platform (in particular IP address, pages\n    and products viewed)\n- category: biometric\n  text: This facial biometric verification system verifies automatically the authenticity of your ID and confirms\n    it belongs to you by comparing the face on the ID with a selfie video you provide in the same flow.\n- category: communication\n  text: Recording of your calls to our Customer Service, unless you object to it\npurposes:\n- purpose: Use of the services on the Platform\n  text: Access to and browsing on the Platform\n- purpose: Direct marketing\n  text: Direct marketing and email newsletters\n- purpose: Personalized ads\n  text: Serving personalized online ads based on your preferences and browsing habits\n- purpose: Fraud prevention\n  text: Preventing and fighting against fraud\n- purpose: Improving services\n  text: Carrying out statistical\
  \ analyses of the use of our Platform\nretention:\n- scope: Personal data generally\n  period: null\n  text: Your personal data will be stored in compliance with applicable data protection laws, and only for as long\n    as necessary to fulfill the processing purposes described in this Privacy Policy.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account in My profile section\n  text: 'You can directly and at any time : delete your Back Market customer account via the “My profile” section\n    of your personal account.'\nrights:\n- right: Access\n  text: You may request access to and rectification or, where appropriate, erasure of your Personal Data.\n- right: Objection\n  text: You may also, in certain cases, object to the Processing of your Personal Data or request that the Processing\n    be restricted\n- right: Portability\n  text: You also have the right to data portability .\n\
  - right: Opt-out of targeted advertising\n  text: Residents of certain states of the United States may also have the right to opt-out of the sale of personal\n    information and the sharing of personal information for targeted advertising.\nsale_or_sharing:\n  stance: conditional\n  text: Please be reassured that we do not sell your information to third parties. However we may share your personal\n    information to our advertising partners, for cross-context behavioral advertising\n"
source_yaml_url: https://artifacts.apis.io/back-market/privacy/back-market-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Back Market's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Marketplace
- Retail
- Refurbished Electronics
- Circular Economy
- Order
- Listings
- Product Catalog
- Logistics
- Customer Service
---
