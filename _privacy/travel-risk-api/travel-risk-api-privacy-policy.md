---
api_specs:
- filename: travel-risk-api-adb-api-openapi.yml
  format: yaml
  label: Travel Risk API Adb API
  slug: travel-risk-api-adb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/travel-risk-api/openapi/travel-risk-api-adb-api-openapi.yml
- filename: travel-risk-api-auth-api-openapi.yml
  format: yaml
  label: Travel Risk API Auth API
  slug: travel-risk-api-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/travel-risk-api/openapi/travel-risk-api-auth-api-openapi.yml
- filename: travel-risk-api-billing-api-openapi.yml
  format: yaml
  label: Travel Risk API Billing API
  slug: travel-risk-api-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/travel-risk-api/openapi/travel-risk-api-billing-api-openapi.yml
- filename: travel-risk-api-ext-api-openapi.yml
  format: yaml
  label: Travel Risk API Ext API
  slug: travel-risk-api-ext-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/travel-risk-api/openapi/travel-risk-api-ext-api-openapi.yml
- filename: travel-risk-api-public-data-api-openapi.yml
  format: yaml
  label: Travel Risk API Public Data API
  slug: travel-risk-api-public-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/travel-risk-api/openapi/travel-risk-api-public-data-api-openapi.yml
- filename: travel-risk-api-system-api-openapi.yml
  format: yaml
  label: Travel Risk API System API
  slug: travel-risk-api-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/travel-risk-api/openapi/travel-risk-api-system-api-openapi.yml
- filename: travel-risk-api-usage-api-openapi.yml
  format: yaml
  label: Travel Risk API Usage API
  slug: travel-risk-api-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/travel-risk-api/openapi/travel-risk-api-usage-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address when you create an API key or sign in to the dashboard
  - category: financial
    text: We receive a customer and subscription reference, plan, billing status and the details Stripe shares with merchants, such as country and the last four digits of a card.
  - category: device
    text: Our servers log standard technical information such as IP address, browser user agent and pages requested.
  - category: behavioral
    text: we record the key used, endpoint, method, response status, response time, date and time, and the IP address it came from
  - category: location
    text: collects information such as pages viewed and approximate location
  - category: communication
    text: Messages you send to us, and records of service emails we send you
  deletion:
    route: Email legal@travel-code.com from the address on your account
    text: To make a request, email legal@travel-code.com from the address on your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: to provide the Service, issue keys and authenticate requests
  - purpose: Usage measurement and billing
    text: to measure usage, enforce quotas and rate limits, and bill
  - purpose: Security and fraud prevention
    text: to secure the Service, detect and prevent fraud and abuse
  - purpose: Improvement and analytics
    text: to understand and improve the Service and the website
  - purpose: Legal compliance
    text: to comply with legal obligations and enforce our Terms of Service
  residency:
  - region: United States
    text: The Service is operated from the United States.
  retention:
  - period: up to 13 months
    scope: API usage logs including IP addresses
    text: 'API usage logs, including IP addresses: up to 13 months, then deleted.'
  - period: while your account is active, and afterwards as long as needed for tax, accounting and legal purposes
    scope: Account and billing records
    text: 'Account and billing records: while your account is active, and afterwards as long as needed for tax, accounting and legal purposes.'
  rights:
  - right: access, correct, delete or export
    text: you may have the right to access, correct, delete or export your personal information
  - right: object or restrict processing
    text: to object to or restrict certain processing
  - right: withdraw consent
    text: and to withdraw consent
  - right: lodge complaint
    text: You may also lodge a complaint with your local data protection authority.
  role:
    text: Travel Code is the controller of this information.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, and we do not share it for cross-context behavioural advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we rely on appropriate safeguards such as the European Commission's Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Travel Risk API
provenance_date: '2026-11-10'
provider_name: Travel Risk API
provider_slug: travel-risk-api
slug: travel-risk-api-privacy-policy
source_date: '2026-11-10'
source_filename: travel-risk-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://travelriskapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Travel Risk API\naid: travel-risk-api\nurl: https://travelriskapi.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Travel Code is the controller of this information.\ndata_categories:\n- category: identifying\n  text: Your email address when you create an API key or sign in to the dashboard\n- category: financial\n  text: We receive a customer and subscription reference, plan, billing status and the details Stripe shares with\n    merchants, such as country and the last four digits of a card.\n- category: device\n  text: Our servers log standard technical information such as IP address,\
  \ browser user agent and pages requested.\n- category: behavioral\n  text: we record the key used, endpoint, method, response status, response time, date and time, and the IP address\n    it came from\n- category: location\n  text: collects information such as pages viewed and approximate location\n- category: communication\n  text: Messages you send to us, and records of service emails we send you\npurposes:\n- purpose: Provide the Service\n  text: to provide the Service, issue keys and authenticate requests\n- purpose: Usage measurement and billing\n  text: to measure usage, enforce quotas and rate limits, and bill\n- purpose: Security and fraud prevention\n  text: to secure the Service, detect and prevent fraud and abuse\n- purpose: Improvement and analytics\n  text: to understand and improve the Service and the website\n- purpose: Legal compliance\n  text: to comply with legal obligations and enforce our Terms of Service\nretention:\n- scope: API usage logs including IP addresses\n\
  \  period: up to 13 months\n  text: 'API usage logs, including IP addresses: up to 13 months, then deleted.'\n- scope: Account and billing records\n  period: while your account is active, and afterwards as long as needed for tax, accounting and legal purposes\n  text: 'Account and billing records: while your account is active, and afterwards as long as needed for tax, accounting\n    and legal purposes.'\nresidency:\n- region: United States\n  text: The Service is operated from the United States.\ntransfers:\n- mechanism: SCC\n  text: Where required, we rely on appropriate safeguards such as the European Commission's Standard Contractual\n    Clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email legal@travel-code.com from the address on your account\n  text: To make a request, email legal@travel-code.com from the address on your account.\nrights:\n- right: access, correct, delete or export\n  text: you may have\
  \ the right to access, correct, delete or export your personal information\n- right: object or restrict processing\n  text: to object to or restrict certain processing\n- right: withdraw consent\n  text: and to withdraw consent\n- right: lodge complaint\n  text: You may also lodge a complaint with your local data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, and we do not share it for cross-context behavioural advertising.\n"
source_yaml_url: https://artifacts.apis.io/travel-risk-api/privacy/travel-risk-api-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Travel Risk API's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Travel Risk
- Travel Advisories
- Aviation
- Airports
- Risk Scoring
- Safety
- Disaster Alerts
---
