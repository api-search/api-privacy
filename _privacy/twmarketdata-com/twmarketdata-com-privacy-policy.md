---
api_specs:
- filename: twmarketdata-com-capital-flow-api-openapi.yml
  format: yaml
  label: twmarketdata-com Capital Flow API
  slug: twmarketdata-com-capital-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twmarketdata-com/openapi/twmarketdata-com-capital-flow-api-openapi.yml
- filename: twmarketdata-com-datasets-api-openapi.yml
  format: yaml
  label: twmarketdata-com Datasets API
  slug: twmarketdata-com-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twmarketdata-com/openapi/twmarketdata-com-datasets-api-openapi.yml
- filename: twmarketdata-com-fundamentals-api-openapi.yml
  format: yaml
  label: twmarketdata-com Fundamentals API
  slug: twmarketdata-com-fundamentals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twmarketdata-com/openapi/twmarketdata-com-fundamentals-api-openapi.yml
- filename: twmarketdata-com-market-prices-api-openapi.yml
  format: yaml
  label: twmarketdata-com Market Prices API
  slug: twmarketdata-com-market-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twmarketdata-com/openapi/twmarketdata-com-market-prices-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: contact and professional information (name, email, company, job title)
  - category: identifying
    text: account information (login identifier, username)
  - category: financial
    text: transaction information (hashed payment identifiers, billing address)
  - category: device
    text: device information (browser, operating system, language)
  - category: location
    text: city- or country-level location inferred from IP — we do not collect precise location
  - category: behavioral
    text: usage information (page views, clicks, searches, errors, timestamps)
  deletion:
    route: contact us through "Contact us" on the Site
    text: To exercise a right , please contact us through “ Contact us ” on the Site
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and maintain Services
    text: To provide, operate and maintain the Services (including troubleshooting and upgrades)
  - purpose: product development
    text: for product development and improvement
  - purpose: customer support
    text: to provide customer support
  - purpose: account management and billing
    text: for account management and billing
  - purpose: fraud and security
    text: to detect, prevent and respond to fraud, abuse and security threats
  retention:
  - period: null
    scope: personal information
    text: We retain personal information only for as long as is necessary to meet our legal and contractual obligations, for legitimate operational purposes (such as tax and accounting), to resolve disputes and to exercise our rights.
  rights:
  - right: access
    text: to access and obtain a copy
  - right: rectification
    text: to rectification
  - right: restriction
    text: to restriction of processing
  - right: erasure
    text: to erasure
  - right: portability
    text: to data portability
  - right: withdraw consent
    text: to withdraw consent
  - right: complain to supervisory authority
    text: to complain to a supervisory authority about our processing
  role:
    text: TWMD is the data controller for the personal information processed under this Policy.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: the full list is in the subprocessor table in the Trust Centre
    url: null
  transfers:
  - mechanism: SCC
    text: such as standard contractual clauses or other lawful mechanisms
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: twmarketdata-com
provenance_date: '2026-11-10'
provider_name: twmarketdata-com
provider_slug: twmarketdata-com
slug: twmarketdata-com-privacy-policy
source_date: '2026-11-10'
source_filename: twmarketdata-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://twmarketdata.com/en/legal/privacy-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: twmarketdata-com\naid: twmarketdata-com\nurl: https://twmarketdata.com/en/legal/privacy-notice\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: TWMD is the data controller for the personal information processed under this Policy.\ndata_categories:\n- category: contact\n  text: contact and professional information (name, email, company, job title)\n- category: identifying\n  text: account information (login identifier, username)\n- category: financial\n  text: transaction information (hashed payment identifiers, billing address)\n- category: device\n  text: device information (browser, operating\
  \ system, language)\n- category: location\n  text: city- or country-level location inferred from IP — we do not collect precise location\n- category: behavioral\n  text: usage information (page views, clicks, searches, errors, timestamps)\npurposes:\n- purpose: provide and maintain Services\n  text: To provide, operate and maintain the Services (including troubleshooting and upgrades)\n- purpose: product development\n  text: for product development and improvement\n- purpose: customer support\n  text: to provide customer support\n- purpose: account management and billing\n  text: for account management and billing\n- purpose: fraud and security\n  text: to detect, prevent and respond to fraud, abuse and security threats\nretention:\n- scope: personal information\n  period: null\n  text: We retain personal information only for as long as is necessary to meet our legal and contractual obligations,\n    for legitimate operational purposes (such as tax and accounting), to resolve disputes\
  \ and to exercise our rights.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: such as standard contractual clauses or other lawful mechanisms\nsubprocessors:\n  url: null\n  text: the full list is in the subprocessor table in the Trust Centre\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact us through \"Contact us\" on the Site\n  text: To exercise a right , please contact us through “ Contact us ” on the Site\nrights:\n- right: access\n  text: to access and obtain a copy\n- right: rectification\n  text: to rectification\n- right: restriction\n  text: to restriction of processing\n- right: erasure\n  text: to erasure\n- right: portability\n  text: to data portability\n- right: withdraw consent\n  text: to withdraw consent\n- right: complain to supervisory authority\n  text: to complain to a supervisory authority about our processing\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/twmarketdata-com/privacy/twmarketdata-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
summary_line: 23 quoted statements, read from twmarketdata-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Market Data
- Taiwan
---
