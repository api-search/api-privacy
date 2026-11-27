---
api_specs:
- filename: equibles-equibles-api-api-openapi.yml
  format: yaml
  label: Equibles Equibles API
  slug: equibles-equibles-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-equibles-api-api-openapi.yml
- filename: equibles-etfs-api-openapi.yml
  format: yaml
  label: Equibles Etfs API
  slug: equibles-etfs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-etfs-api-openapi.yml
- filename: equibles-fda-api-openapi.yml
  format: yaml
  label: Equibles Fda API
  slug: equibles-fda-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-fda-api-openapi.yml
- filename: equibles-funds-api-openapi.yml
  format: yaml
  label: Equibles Funds API
  slug: equibles-funds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-funds-api-openapi.yml
- filename: equibles-investment-advisers-api-openapi.yml
  format: yaml
  label: Equibles Investment Advisers API
  slug: equibles-investment-advisers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-investment-advisers-api-openapi.yml
- filename: equibles-ipos-api-openapi.yml
  format: yaml
  label: Equibles Ipos API
  slug: equibles-ipos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-ipos-api-openapi.yml
- filename: equibles-short-interest-api-openapi.yml
  format: yaml
  label: Equibles Short Interest API
  slug: equibles-short-interest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-short-interest-api-openapi.yml
- filename: equibles-short-volume-api-openapi.yml
  format: yaml
  label: Equibles Short Volume API
  slug: equibles-short-volume-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-short-volume-api-openapi.yml
- filename: equibles-stocks-api-openapi.yml
  format: yaml
  label: Equibles Stocks API
  slug: equibles-stocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equibles/openapi/equibles-stocks-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address, name, internal account identifier, authentication and login records
  - category: contact
    text: Billing name, email, address, any tax ID
  - category: financial
    text: limited payment-method details such as card brand, last four digits, and expiry
  - category: location
    text: the country each address is located in
  - category: behavioral
    text: Page views, clicks, scrolling, heatmaps, performance measurements, browser errors, and session recordings after you accept analytics
  - category: device
    text: IP address, browser and device details, operating system, pages and features used
  - category: communication
    text: Email preferences, messages sent to or from us, delivery and support history
  deletion:
    route: Erasure request via support email
    text: Send a request to support [at] equibles [dot] com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Create and authenticate accounts and provide the Service
    text: Create and authenticate accounts; provide website, ALVIS, API, MCP, support, and subscription functionality
  - purpose: Process subscriptions and payments
    text: Process subscriptions, payments, invoices, refunds, and accounting records.
  - purpose: Security and fraud prevention
    text: Secure the Service, prevent fraud and abuse, investigate errors, maintain audit records, and establish or defend legal claims.
  - purpose: Browser analytics with consent
    text: Run PostHog browser analytics and session recording, and enable Google Analytics storage. Your consent, which you can withdraw at any time.
  residency:
  - region: European Union
    text: PostHog is hosted in the European Union for this Service.
  - region: Portugal
    text: We primarily operate from Portugal and use providers that may process data in the European Economic Area and other countries.
  retention:
  - period: 100 calls per client
    scope: MCP raw argument history
    text: The raw argument history for MCP tools is bounded to the most recent 100 calls per client
  - period: up to 12 months
    scope: PostHog event data
    text: PostHog event data is generally retained for up to 12 months
  - period: approximately one month
    scope: PostHog session recordings
    text: session recordings for approximately one month under our current service configuration
  - period: null
    scope: Account records
    text: Account, profile, authentication, subscription, and workspace records are generally retained while the account is active and then deleted, anonymized, or restricted after a verified closure or erasure request
  rights:
  - right: access
    text: access personal data we hold about you and obtain a copy
  - right: rectify
    text: rectify inaccurate or incomplete personal data
  - right: erase
    text: erase personal data
  - right: restrict processing
    text: restrict processing in certain circumstances
  - right: portability
    text: receive or transmit portable data where the right applies
  - right: object
    text: object to processing based on legitimate interests and object at any time to direct marketing
  - right: withdraw consent
    text: withdraw consent at any time without affecting earlier lawful processing
  - right: complain
    text: complain to Portugal's Comissão Nacional de Proteção de Dados (CNPD)
  role:
    text: Equibles is the controller of the personal data described in this Policy unless another notice says otherwise.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on an approved transfer mechanism such as the European Commission's Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Equibles
provenance_date: '2026-11-09'
provider_name: Equibles
provider_slug: equibles
slug: equibles-privacy-policy
source_date: '2026-11-09'
source_filename: equibles-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://equibles.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Equibles\naid: equibles\nurl: https://equibles.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Equibles is the controller of the personal data described in this Policy unless another notice says otherwise.\ndata_categories:\n- category: identifying\n  text: Email address, name, internal account identifier, authentication and login records\n- category: contact\n  text: Billing name, email, address, any tax ID\n- category: financial\n  text: limited payment-method details such as card brand, last four digits, and expiry\n- category: location\n  text: the country each address\
  \ is located in\n- category: behavioral\n  text: Page views, clicks, scrolling, heatmaps, performance measurements, browser errors, and session recordings\n    after you accept analytics\n- category: device\n  text: IP address, browser and device details, operating system, pages and features used\n- category: communication\n  text: Email preferences, messages sent to or from us, delivery and support history\npurposes:\n- purpose: Create and authenticate accounts and provide the Service\n  text: Create and authenticate accounts; provide website, ALVIS, API, MCP, support, and subscription functionality\n- purpose: Process subscriptions and payments\n  text: Process subscriptions, payments, invoices, refunds, and accounting records.\n- purpose: Security and fraud prevention\n  text: Secure the Service, prevent fraud and abuse, investigate errors, maintain audit records, and establish or\n    defend legal claims.\n- purpose: Browser analytics with consent\n  text: Run PostHog browser analytics\
  \ and session recording, and enable Google Analytics storage. Your consent,\n    which you can withdraw at any time.\nretention:\n- scope: MCP raw argument history\n  period: 100 calls per client\n  text: The raw argument history for MCP tools is bounded to the most recent 100 calls per client\n- scope: PostHog event data\n  period: up to 12 months\n  text: PostHog event data is generally retained for up to 12 months\n- scope: PostHog session recordings\n  period: approximately one month\n  text: session recordings for approximately one month under our current service configuration\n- scope: Account records\n  period: null\n  text: Account, profile, authentication, subscription, and workspace records are generally retained while the account\n    is active and then deleted, anonymized, or restricted after a verified closure or erasure request\nresidency:\n- region: European Union\n  text: PostHog is hosted in the European Union for this Service.\n- region: Portugal\n  text: We primarily\
  \ operate from Portugal and use providers that may process data in the European Economic Area\n    and other countries.\ntransfers:\n- mechanism: SCC\n  text: we rely on an approved transfer mechanism such as the European Commission's Standard Contractual Clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Erasure request via support email\n  text: Send a request to support [at] equibles [dot] com .\nrights:\n- right: access\n  text: access personal data we hold about you and obtain a copy\n- right: rectify\n  text: rectify inaccurate or incomplete personal data\n- right: erase\n  text: erase personal data\n- right: restrict processing\n  text: restrict processing in certain circumstances\n- right: portability\n  text: receive or transmit portable data where the right applies\n- right: object\n  text: object to processing based on legitimate interests and object at any time to direct marketing\n- right: withdraw consent\n\
  \  text: withdraw consent at any time without affecting earlier lawful processing\n- right: complain\n  text: complain to Portugal's Comissão Nacional de Proteção de Dados (CNPD)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/equibles/privacy/equibles-privacy-policy.yml
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
summary_line: 29 quoted statements, read from Equibles's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Data
- Stocks
---
