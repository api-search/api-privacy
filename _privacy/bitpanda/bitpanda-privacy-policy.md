---
api_specs:
- filename: bitpanda-assets-api-openapi.yml
  format: yaml
  label: Bitpanda Assets API
  slug: bitpanda-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpanda/openapi/bitpanda-assets-api-openapi.yml
- filename: bitpanda-market-data-api-openapi.yml
  format: yaml
  label: Bitpanda Market Data API
  slug: bitpanda-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpanda/openapi/bitpanda-market-data-api-openapi.yml
- filename: bitpanda-transactions-api-openapi.yml
  format: yaml
  label: Bitpanda Transactions API
  slug: bitpanda-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpanda/openapi/bitpanda-transactions-api-openapi.yml
- filename: bitpanda-wallets-api-openapi.yml
  format: yaml
  label: Bitpanda Wallets API
  slug: bitpanda-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpanda/openapi/bitpanda-wallets-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, address, telephone number, email, date of birth, photo for the account, etc.
  - category: financial
    text: bank details (IBAN, BIC), payment service provider information, payment details, transaction-ID, and other sensitive payment data
  - category: biometric
    text: biometric data for verification (see point 7)
  - category: device
    text: IP-address, transaction data, deposit and withdrawal address, computer or mobile device information
  - category: behavioral
    text: consumer's behaviour, interests and preferences
  - category: location
    text: places
  deletion:
    route: Erasure on request under Art 17 GDPR, subject to exceptions
    text: You can at any time ask us to delete the personal data we have stored about you, which we will act upon unless there is an overriding exception.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: performance of contractual obligations
    text: For the performance of contractual obligations (Art 6 para 1 lit b GDPR)
  - purpose: compliance with legal obligations
    text: For compliance with legal obligations (Art 6 para 1 lit c GDPR)
  - purpose: legitimate interests
    text: To protect legitimate interests (Art 6 para 1 lit f GDPR)
  - purpose: consent-based processing
    text: Based on your consent (Art 6 para 1 lit a GDPR)
  residency:
  - region: European Economic Area
    text: Bitpanda will process your personal data in general within the European Economic Area.
  retention:
  - period: five year period
    scope: Custody user data
    text: The data processed will be stored for a five year period according to the 5th Anti-Money-Laundering Directive (AMLD5).
  - period: 3 years
    scope: Biometric data
    text: The biometric data will be processed solely by our service providers and will be erased completely within 3 years after performing the identification.
  - period: null
    scope: General
    text: We retain and process your personal data only as long as absolutely necessary.
  rights:
  - right: access
    text: 'Right of access (Art 15 GDPR) : You have the right to request confirmation from us as to whether we are processing personal data concerning you'
  - right: rectification
    text: 'Right to rectification (Art 16 GDPR) : You can at any time request to rectify incorrect data'
  - right: erasure
    text: Right to erasure (Art 17 GDPR)
  - right: restriction
    text: Right to restriction of processing (Art 18 GDPR)
  - right: portability
    text: Right to data portability (Art 20 GDPR)
  - right: object
    text: Right to object (Art 21 GDPR)
  - right: withdraw consent
    text: Right to withdraw consent (Art 7(3) GDPR)
  role:
    text: Generally, each company of the Bitpanda Group is a Controller pursuant to Art 4 para 7 GDPR and therefore responsible for the processing of personal data in connection with the services provided by the specific company
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: personal data that we collect concerning you will neither be sold by us nor otherwise disclosed to third parties
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: 'an adequacy decision by the European Commission (Eg.: EU-US Privacy Framework)'
  - mechanism: SCC
    text: standard contractual clauses as published by the European Commission
  - mechanism: BCR
    text: binding corporate rules
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bitpanda
provenance_date: '2026-11-09'
provider_name: Bitpanda
provider_slug: bitpanda
slug: bitpanda-privacy-policy
source_date: '2026-11-09'
source_filename: bitpanda-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bitpanda.com/en/legal/bitpanda-group-privacy-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bitpanda\naid: bitpanda\nurl: https://www.bitpanda.com/en/legal/bitpanda-group-privacy-notice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: Generally, each company of the Bitpanda Group is a Controller pursuant to Art 4 para 7 GDPR and therefore\n    responsible for the processing of personal data in connection with the services provided by the specific company\ndata_categories:\n- category: identifying\n  text: name, address, telephone number, email, date of birth, photo for the account, etc.\n- category: financial\n  text: bank details (IBAN, BIC), payment service provider\
  \ information, payment details, transaction-ID, and other\n    sensitive payment data\n- category: biometric\n  text: biometric data for verification (see point 7)\n- category: device\n  text: IP-address, transaction data, deposit and withdrawal address, computer or mobile device information\n- category: behavioral\n  text: consumer's behaviour, interests and preferences\n- category: location\n  text: places\npurposes:\n- purpose: performance of contractual obligations\n  text: For the performance of contractual obligations (Art 6 para 1 lit b GDPR)\n- purpose: compliance with legal obligations\n  text: For compliance with legal obligations (Art 6 para 1 lit c GDPR)\n- purpose: legitimate interests\n  text: To protect legitimate interests (Art 6 para 1 lit f GDPR)\n- purpose: consent-based processing\n  text: Based on your consent (Art 6 para 1 lit a GDPR)\nretention:\n- scope: Custody user data\n  period: five year period\n  text: The data processed will be stored for a five year period\
  \ according to the 5th Anti-Money-Laundering Directive\n    (AMLD5).\n- scope: Biometric data\n  period: 3 years\n  text: The biometric data will be processed solely by our service providers and will be erased completely within\n    3 years after performing the identification.\n- scope: General\n  period: null\n  text: We retain and process your personal data only as long as absolutely necessary.\nresidency:\n- region: European Economic Area\n  text: Bitpanda will process your personal data in general within the European Economic Area.\ntransfers:\n- mechanism: adequacy\n  text: 'an adequacy decision by the European Commission (Eg.: EU-US Privacy Framework)'\n- mechanism: SCC\n  text: standard contractual clauses as published by the European Commission\n- mechanism: BCR\n  text: binding corporate rules\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Erasure on request under Art 17 GDPR, subject to exceptions\n  text: You\
  \ can at any time ask us to delete the personal data we have stored about you, which we will act upon\n    unless there is an overriding exception.\nrights:\n- right: access\n  text: 'Right of access (Art 15 GDPR) : You have the right to request confirmation from us as to whether we are\n    processing personal data concerning you'\n- right: rectification\n  text: 'Right to rectification (Art 16 GDPR) : You can at any time request to rectify incorrect data'\n- right: erasure\n  text: Right to erasure (Art 17 GDPR)\n- right: restriction\n  text: Right to restriction of processing (Art 18 GDPR)\n- right: portability\n  text: Right to data portability (Art 20 GDPR)\n- right: object\n  text: Right to object (Art 21 GDPR)\n- right: withdraw consent\n  text: Right to withdraw consent (Art 7(3) GDPR)\nsale_or_sharing:\n  stance: prohibited\n  text: personal data that we collect concerning you will neither be sold by us nor otherwise disclosed to third\n    parties\n"
source_yaml_url: https://artifacts.apis.io/bitpanda/privacy/bitpanda-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from Bitpanda's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Fintech
- Trading
- Investing
- Stocks
- ETFs
- Precious Metals
- Portfolio
- Market Data
- MCP
- Agent Skills
---
