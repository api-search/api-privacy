---
api_specs:
- filename: bitculator-alarms-api-openapi.yml
  format: yaml
  label: Bitculator Alarms API
  slug: bitculator-alarms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-alarms-api-openapi.yml
- filename: bitculator-calculators-api-openapi.yml
  format: yaml
  label: Bitculator Calculators API
  slug: bitculator-calculators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-calculators-api-openapi.yml
- filename: bitculator-coins-api-openapi.yml
  format: yaml
  label: Bitculator Coins API
  slug: bitculator-coins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-coins-api-openapi.yml
- filename: bitculator-conversion-api-openapi.yml
  format: yaml
  label: Bitculator Conversion API
  slug: bitculator-conversion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-conversion-api-openapi.yml
- filename: bitculator-editorial-api-openapi.yml
  format: yaml
  label: Bitculator Editorial API
  slug: bitculator-editorial-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-editorial-api-openapi.yml
- filename: bitculator-exchanges-api-openapi.yml
  format: yaml
  label: Bitculator Exchanges API
  slug: bitculator-exchanges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-exchanges-api-openapi.yml
- filename: bitculator-global-market-api-openapi.yml
  format: yaml
  label: Bitculator Global Market API
  slug: bitculator-global-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-global-market-api-openapi.yml
- filename: bitculator-indicators-api-openapi.yml
  format: yaml
  label: Bitculator Indicators API
  slug: bitculator-indicators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-indicators-api-openapi.yml
- filename: bitculator-liquidations-api-openapi.yml
  format: yaml
  label: Bitculator Liquidations API
  slug: bitculator-liquidations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-liquidations-api-openapi.yml
- filename: bitculator-markets-api-openapi.yml
  format: yaml
  label: Bitculator Markets API
  slug: bitculator-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-markets-api-openapi.yml
- filename: bitculator-meta-api-openapi.yml
  format: yaml
  label: Bitculator Meta API
  slug: bitculator-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-meta-api-openapi.yml
- filename: bitculator-prices-api-openapi.yml
  format: yaml
  label: Bitculator Prices API
  slug: bitculator-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-prices-api-openapi.yml
- filename: bitculator-sentiment-api-openapi.yml
  format: yaml
  label: Bitculator Sentiment API
  slug: bitculator-sentiment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-sentiment-api-openapi.yml
- filename: bitculator-wallets-api-openapi.yml
  format: yaml
  label: Bitculator Wallets API
  slug: bitculator-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-wallets-api-openapi.yml
- filename: bitculator-webhooks-api-openapi.yml
  format: yaml
  label: Bitculator Webhooks API
  slug: bitculator-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitculator/openapi/bitculator-webhooks-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account , we hold your username, your email address, your password (stored only as a one-way hash)
  - category: location
    text: the country your connection comes from
  - category: behavioral
    text: what you search for on the site
  - category: financial
    text: We keep your Stripe customer reference, the card brand and last four digits, what you bought, what you paid and when it renews.
  - category: communication
    text: When you write to us , by email or through the contact form, we keep your message and your email address
  - category: device
    text: your browser's identification string
  deletion:
    route: Self-service deletion in profile settings, with 30-day restore window
    text: You can delete your account yourself in your profile settings.
  dpa:
    available: true
    text: Service providers process data on our behalf, each under a data processing agreement
    url: null
  purposes:
  - purpose: Provide account and paid services
    text: To run your account and provide what you use or paid for
  - purpose: Service security
    text: To keep the service secure and working - filtering bots and attacks, rate-limiting, the account change log and the error log.
  - purpose: Site usage statistics
    text: To understand how the site is used - the visit statistics described above
  - purpose: Marketing email with consent
    text: To send marketing email - only with your consent (Art. 6(1)(a))
  - purpose: Legal obligations
    text: To meet legal duties - bookkeeping, tax and requests from authorities.
  residency:
  - region: Denmark / EU
    text: Bitculator is run from Denmark, so Danish and EU data protection law applies.
  - region: Frankfurt (file storage)
    text: Our file storage is in Frankfurt and our email provider stores mail in the EU.
  retention:
  - period: until you delete it
    scope: Account and created content
    text: Your account and what you create in it - until you delete it, or delete an item yourself.
  - period: 90 days
    scope: Visit statistics
    text: Visit statistics - page visits and per-minute counts 90 days
  - period: 180 days
    scope: Account change log
    text: Account change log - 180 days.
  - period: five years from the end of the financial year
    scope: Purchase and payout records
    text: Purchase and payout records - five years from the end of the financial year they belong to, as the Danish Bookkeeping Act requires.
  rights:
  - right: access
    text: access the data we hold about you and receive a copy
  - right: correction
    text: have it corrected
  - right: erasure
    text: have it erased
  - right: restriction
    text: restrict what we do with it
  - right: portability
    text: receive the data you gave us in a machine-readable format and have it passed to another provider
  - right: objection
    text: object to processing we base on our legitimate interests
  - right: withdraw consent
    text: withdraw consent at any time, without affecting what we did before
  role:
    text: The data controller - the person responsible for your data - is named at the top of this page.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, we do not build advertising profiles, and we do not use third-party advertising or analytics trackers.
  subprocessors:
    text: 'Service providers process data on our behalf, each under a data processing agreement and only for the job we give them: Stripe - payments, invoices and receipts.'
    url: null
  transfers:
  - mechanism: DPF
    text: transfers to a US company certified under the EU-US Data Privacy Framework rely on the European Commission's adequacy decision for that framework
  - mechanism: SCC
    text: all other transfers rely on the Commission's standard contractual clauses in the provider's data processing terms
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bitculator
provenance_date: '2026-11-09'
provider_name: Bitculator
provider_slug: bitculator
slug: bitculator-privacy-policy
source_date: '2026-11-09'
source_filename: bitculator-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bitculator.com/en/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bitculator\naid: bitculator\nurl: https://bitculator.com/en/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller - the person responsible for your data - is named at the top of this page.\ndata_categories:\n- category: identifying\n  text: When you create an account , we hold your username, your email address, your password (stored only as a\n    one-way hash)\n- category: location\n  text: the country your connection comes from\n- category: behavioral\n  text: what you search for on the site\n- category: financial\n  text: We keep your Stripe customer reference,\
  \ the card brand and last four digits, what you bought, what you paid\n    and when it renews.\n- category: communication\n  text: When you write to us , by email or through the contact form, we keep your message and your email address\n- category: device\n  text: your browser's identification string\npurposes:\n- purpose: Provide account and paid services\n  text: To run your account and provide what you use or paid for\n- purpose: Service security\n  text: To keep the service secure and working - filtering bots and attacks, rate-limiting, the account change log\n    and the error log.\n- purpose: Site usage statistics\n  text: To understand how the site is used - the visit statistics described above\n- purpose: Marketing email with consent\n  text: To send marketing email - only with your consent (Art. 6(1)(a))\n- purpose: Legal obligations\n  text: To meet legal duties - bookkeeping, tax and requests from authorities.\nretention:\n- scope: Account and created content\n  period: until\
  \ you delete it\n  text: Your account and what you create in it - until you delete it, or delete an item yourself.\n- scope: Visit statistics\n  period: 90 days\n  text: Visit statistics - page visits and per-minute counts 90 days\n- scope: Account change log\n  period: 180 days\n  text: Account change log - 180 days.\n- scope: Purchase and payout records\n  period: five years from the end of the financial year\n  text: Purchase and payout records - five years from the end of the financial year they belong to, as the Danish\n    Bookkeeping Act requires.\nresidency:\n- region: Denmark / EU\n  text: Bitculator is run from Denmark, so Danish and EU data protection law applies.\n- region: Frankfurt (file storage)\n  text: Our file storage is in Frankfurt and our email provider stores mail in the EU.\ntransfers:\n- mechanism: DPF\n  text: transfers to a US company certified under the EU-US Data Privacy Framework rely on the European Commission's\n    adequacy decision for that framework\n\
  - mechanism: SCC\n  text: all other transfers rely on the Commission's standard contractual clauses in the provider's data processing\n    terms\nsubprocessors:\n  url: null\n  text: 'Service providers process data on our behalf, each under a data processing agreement and only for the job\n    we give them: Stripe - payments, invoices and receipts.'\ndpa:\n  available: true\n  url: null\n  text: Service providers process data on our behalf, each under a data processing agreement\ndeletion:\n  route: Self-service deletion in profile settings, with 30-day restore window\n  text: You can delete your account yourself in your profile settings.\nrights:\n- right: access\n  text: access the data we hold about you and receive a copy\n- right: correction\n  text: have it corrected\n- right: erasure\n  text: have it erased\n- right: restriction\n  text: restrict what we do with it\n- right: portability\n  text: receive the data you gave us in a machine-readable format and have it passed to another\
  \ provider\n- right: objection\n  text: object to processing we base on our legitimate interests\n- right: withdraw consent\n  text: withdraw consent at any time, without affecting what we did before\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, we do not build advertising profiles, and we do not use third-party advertising\n    or analytics trackers.\n"
source_yaml_url: https://artifacts.apis.io/bitculator/privacy/bitculator-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 31 quoted statements, read from Bitculator's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- crypto-market-data
- Blockchain
- Finance
- Fintech
- Web3
- Trading
- Exchange Data
- Wallets
- Sentiment
- Indicators
---
