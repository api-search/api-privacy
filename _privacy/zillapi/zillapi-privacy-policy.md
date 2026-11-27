---
api_specs:
- filename: zillapi-account-api-openapi.yml
  format: yaml
  label: Zillapi Account API
  slug: zillapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-account-api-openapi.yml
- filename: zillapi-buildings-api-openapi.yml
  format: yaml
  label: Zillapi Buildings API
  slug: zillapi-buildings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-buildings-api-openapi.yml
- filename: zillapi-jobs-api-openapi.yml
  format: yaml
  label: Zillapi Jobs API
  slug: zillapi-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-jobs-api-openapi.yml
- filename: zillapi-listings-api-openapi.yml
  format: yaml
  label: Zillapi Listings API
  slug: zillapi-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-listings-api-openapi.yml
- filename: zillapi-properties-api-openapi.yml
  format: yaml
  label: Zillapi Properties API
  slug: zillapi-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-properties-api-openapi.yml
- filename: zillapi-search-api-openapi.yml
  format: yaml
  label: Zillapi Search API
  slug: zillapi-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-search-api-openapi.yml
- filename: zillapi-webhooks-api-openapi.yml
  format: yaml
  label: Zillapi Webhooks API
  slug: zillapi-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zillapi/openapi/zillapi-webhooks-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign up we collect your first and last name, email address, password, what you plan to use the API for and, optionally, your company name.
  - category: contact
    text: We send one-time links by email to confirm your address and, if you ask, to reset your password.
  - category: device
    text: When you sign in, our authentication provider records the time, your IP address and your browser type, to keep your account secure.
  - category: behavioral
    text: It records page visits, the website that referred you, basic device details (screen size, language and time zone), how far you scroll and how long you stay, and a few actions, such as starting a sign-up.
  - category: financial
    text: We receive only a customer ID, the last four digits of the card, the brand, the country, the subscription plan, and invoice records.
  - category: communication
    text: If you email us we retain the message and any reply for support and recordkeeping purposes.
  deletion:
    route: email hello@zillapi.com
    text: To exercise any of these rights, email hello@zillapi.com from the address on your account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, operate, secure and improve the Service
    text: Provide, operate, secure, and improve the Service.
  - purpose: Authenticate and authorize API requests
    text: Authenticate you and authorize your API requests.
  - purpose: Meter usage and generate invoices
    text: Meter usage against your plan and generate invoices.
  - purpose: Fraud and abuse prevention
    text: Detect, investigate, and prevent fraud, abuse, and violations of our Terms.
  - purpose: Website and product analytics
    text: We use Google Analytics on every page of this site, including the dashboard, to measure visits.
  residency:
  - region: Main database
    text: Our main database is hosted by AWS in Oregon, USA.
  - region: Product analytics
    text: We use PostHog (EU cloud) for product analytics and session recordings.
  retention:
  - period: life of your account
    scope: account and usage records
    text: We currently keep account and usage records for the life of your account.
  - period: 7 years
    scope: invoices and tax records
    text: Invoices and tax records. Retained for 7 years as required by applicable tax and accounting law.
  - period: two years
    scope: DataBull visit and event data
    text: Visit and event data is kept for two years.
  rights:
  - right: Access
    text: Access the personal data we hold about you.
  - right: Correct
    text: Correct inaccurate data.
  - right: Delete
    text: Delete your data (“right to be forgotten”), subject to legal retention requirements above.
  - right: Export
    text: Export your data in a portable format.
  - right: Object or restrict
    text: Object to or restrict certain processing.
  - right: Withdraw consent
    text: Withdraw consent where processing is based on consent.
  role:
    text: We are based in the EU.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, and we do not use your account email or usage logs to train machine learning models.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: These transfers are protected by the EU-U.S. Data Privacy Framework where the provider is certified
  - mechanism: SCC
    text: otherwise by the European Commission’s Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Zillapi
provenance_date: '2026-11-10'
provider_name: Zillapi
provider_slug: zillapi
slug: zillapi-privacy-policy
source_date: '2026-11-10'
source_filename: zillapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://zillapi.com/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Zillapi\naid: zillapi\nurl: https://zillapi.com/legal/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are based in the EU.\ndata_categories:\n- category: identifying\n  text: When you sign up we collect your first and last name, email address, password, what you plan to use the\n    API for and, optionally, your company name.\n- category: contact\n  text: We send one-time links by email to confirm your address and, if you ask, to reset your password.\n- category: device\n  text: When you sign in, our authentication provider records the time, your IP address and your browser type,\
  \ to\n    keep your account secure.\n- category: behavioral\n  text: It records page visits, the website that referred you, basic device details (screen size, language and time\n    zone), how far you scroll and how long you stay, and a few actions, such as starting a sign-up.\n- category: financial\n  text: We receive only a customer ID, the last four digits of the card, the brand, the country, the subscription\n    plan, and invoice records.\n- category: communication\n  text: If you email us we retain the message and any reply for support and recordkeeping purposes.\npurposes:\n- purpose: Provide, operate, secure and improve the Service\n  text: Provide, operate, secure, and improve the Service.\n- purpose: Authenticate and authorize API requests\n  text: Authenticate you and authorize your API requests.\n- purpose: Meter usage and generate invoices\n  text: Meter usage against your plan and generate invoices.\n- purpose: Fraud and abuse prevention\n  text: Detect, investigate, and\
  \ prevent fraud, abuse, and violations of our Terms.\n- purpose: Website and product analytics\n  text: We use Google Analytics on every page of this site, including the dashboard, to measure visits.\nretention:\n- scope: account and usage records\n  period: life of your account\n  text: We currently keep account and usage records for the life of your account.\n- scope: invoices and tax records\n  period: 7 years\n  text: Invoices and tax records. Retained for 7 years as required by applicable tax and accounting law.\n- scope: DataBull visit and event data\n  period: two years\n  text: Visit and event data is kept for two years.\nresidency:\n- region: Main database\n  text: Our main database is hosted by AWS in Oregon, USA.\n- region: Product analytics\n  text: We use PostHog (EU cloud) for product analytics and session recordings.\ntransfers:\n- mechanism: DPF\n  text: These transfers are protected by the EU-U.S. Data Privacy Framework where the provider is certified\n- mechanism: SCC\n\
  \  text: otherwise by the European Commission’s Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@zillapi.com\n  text: To exercise any of these rights, email hello@zillapi.com from the address on your account.\nrights:\n- right: Access\n  text: Access the personal data we hold about you.\n- right: Correct\n  text: Correct inaccurate data.\n- right: Delete\n  text: Delete your data (“right to be forgotten”), subject to legal retention requirements above.\n- right: Export\n  text: Export your data in a portable format.\n- right: Object or restrict\n  text: Object to or restrict certain processing.\n- right: Withdraw consent\n  text: Withdraw consent where processing is based on consent.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, and we do not use your account email or usage logs to train machine\n    learning models.\n"
source_yaml_url: https://artifacts.apis.io/zillapi/privacy/zillapi-privacy-policy.yml
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
summary_line: 27 quoted statements, read from Zillapi's own page on 2026-11-10.
synthetic: false
tags:
- Real Estate
- PropTech
- Property Data
- Zillow
- Zestimate
- Valuation
- AVM
- Listings
- MCP
- AI Agents
- REST API
---
