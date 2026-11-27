---
api_specs:
- filename: starling-bank-atm-api-openapi.yml
  format: yaml
  label: Starling Bank ATM API
  slug: starling-bank-atm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starling-bank/openapi/starling-bank-atm-api-openapi.yml
- filename: starling-bank-bca-api-openapi.yml
  format: yaml
  label: Starling Bank BCA API
  slug: starling-bank-bca-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starling-bank/openapi/starling-bank-bca-api-openapi.yml
- filename: starling-bank-branch-api-openapi.yml
  format: yaml
  label: Starling Bank Branch API
  slug: starling-bank-branch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starling-bank/openapi/starling-bank-branch-api-openapi.yml
- filename: starling-bank-ccc-api-openapi.yml
  format: yaml
  label: Starling Bank CCC API
  slug: starling-bank-ccc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starling-bank/openapi/starling-bank-ccc-api-openapi.yml
- filename: starling-bank-pca-api-openapi.yml
  format: yaml
  label: Starling Bank PCA API
  slug: starling-bank-pca-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starling-bank/openapi/starling-bank-pca-api-openapi.yml
- filename: starling-bank-sme-api-openapi.yml
  format: yaml
  label: Starling Bank SME API
  slug: starling-bank-sme-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starling-bank/openapi/starling-bank-sme-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name and date of birth your photograph ID
  - category: contact
    text: email address, and phone number
  - category: financial
    text: transactional and financial information, including information about your income
  - category: biometric
    text: We use data scanned from the images and audio in the videos you upload, and from your identity documents.
  - category: location
    text: We collect information about your location by using details like your IP address or GPS sensors.
  - category: device
    text: 'We collect technical information from your device, including: IP address login information browser type and version'
  - category: behavioral
    text: 'We collect information on how you use our websites, including: the URLs you click to get to, from, and around our website'
  - category: communication
    text: We also collect information from phone conversations we have with you
  deletion:
    route: message us in the app or email privacy@starlingbank.com
    text: To ask us to delete your information, message us in the app or email us at privacy@starlingbank.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate as a bank
    text: running your accounts and allowing you to make and receive payments
  - purpose: connect to Marketplace providers
    text: To connect you to other providers through our Marketplace
  - purpose: research and improve services
    text: measuring how effective, accessible, and commercial our products and services are
  - purpose: automated decisions and fraud
    text: detect fraud or money-laundering, and take action against it
  residency:
  - region: UK and EEA
    text: Where we can, we store and process your information using servers in the UK and European Economic Area (EEA).
  retention:
  - period: six years
    scope: general customer data
    text: We usually keep your information for six years from the date you stop using Starling products or services
  - period: six months
    scope: other uses
    text: for other uses we may delete data after a much shorter period of time, such as after six months
  rights:
  - right: access
    text: You have the right to access information we have about you.
  - right: delete
    text: You have the right to ask us to delete your information, but we might not always be able to for legal reasons.
  - right: restrict processing
    text: You can ask us to limit how we use your information.
  - right: object
    text: You can ask us to stop using all or some of your information
  - right: transfer
    text: You can ask us to transfer information we have about you to somewhere else.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Starling Bank
provenance_date: '2026-11-10'
provider_name: Starling Bank
provider_slug: starling-bank
slug: starling-bank-privacy-policy
source_date: '2026-11-10'
source_filename: starling-bank-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.starlingbank.com/legal/privacy-notice/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Starling Bank\naid: starling-bank\nurl: https://www.starlingbank.com/legal/privacy-notice/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your name and date of birth your photograph ID\n- category: contact\n  text: email address, and phone number\n- category: financial\n  text: transactional and financial information, including information about your income\n- category: biometric\n  text: We use data scanned from the images and audio in the videos you upload, and from your identity documents.\n- category: location\n  text: We collect information\
  \ about your location by using details like your IP address or GPS sensors.\n- category: device\n  text: 'We collect technical information from your device, including: IP address login information browser type\n    and version'\n- category: behavioral\n  text: 'We collect information on how you use our websites, including: the URLs you click to get to, from, and\n    around our website'\n- category: communication\n  text: We also collect information from phone conversations we have with you\npurposes:\n- purpose: operate as a bank\n  text: running your accounts and allowing you to make and receive payments\n- purpose: connect to Marketplace providers\n  text: To connect you to other providers through our Marketplace\n- purpose: research and improve services\n  text: measuring how effective, accessible, and commercial our products and services are\n- purpose: automated decisions and fraud\n  text: detect fraud or money-laundering, and take action against it\nretention:\n- scope: general\
  \ customer data\n  period: six years\n  text: We usually keep your information for six years from the date you stop using Starling products or services\n- scope: other uses\n  period: six months\n  text: for other uses we may delete data after a much shorter period of time, such as after six months\nresidency:\n- region: UK and EEA\n  text: Where we can, we store and process your information using servers in the UK and European Economic Area (EEA).\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: message us in the app or email privacy@starlingbank.com\n  text: To ask us to delete your information, message us in the app or email us at privacy@starlingbank.com .\nrights:\n- right: access\n  text: You have the right to access information we have about you.\n- right: delete\n  text: You have the right to ask us to delete your information, but we might not always be able to for legal reasons.\n- right: restrict\
  \ processing\n  text: You can ask us to limit how we use your information.\n- right: object\n  text: You can ask us to stop using all or some of your information\n- right: transfer\n  text: You can ask us to transfer information we have about you to somewhere else.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/starling-bank/privacy/starling-bank-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 21 quoted statements, read from Starling Bank's own page on 2026-11-10.
synthetic: false
tags:
- Financial Services
- Banking
- Open Banking
- PSD2
- OBIE
- United Kingdom
- Payments
- Account Information
- Challenger Bank
- Fintech
- FAPI
- Consumer Banking
---
