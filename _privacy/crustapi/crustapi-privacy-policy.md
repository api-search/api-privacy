---
api_specs:
- filename: crustapi-demo-api-openapi.yml
  format: yaml
  label: CrustAPI Demo API
  slug: crustapi-demo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crustapi/openapi/crustapi-demo-api-openapi.yml
- filename: crustapi-search-api-openapi.yml
  format: yaml
  label: CrustAPI Search API
  slug: crustapi-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crustapi/openapi/crustapi-search-api-openapi.yml
- filename: crustapi-account-api-openapi.yml
  format: yaml
  label: CrustAPI Account API
  slug: crustapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crustapi/openapi/crustapi-account-api-openapi.yml
- filename: crustapi-linked-in-api-openapi.yml
  format: yaml
  label: CrustAPI Linked In API
  slug: crustapi-linked-in-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crustapi/openapi/crustapi-linked-in-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your first name, last name, email address, and a password.'
  - category: contact
    text: 'Account data: your first name, last name, email address, and a password.'
  - category: device
    text: 'Infrastructure logs: our hosting providers process your IP address transiently to deliver, rate-limit, and secure the service.'
  - category: financial
    text: 'Billing and purchase records: our payment provider handles card details.'
  - category: behavioral
    text: 'Usage metadata: for each API request we store its endpoint, timestamp, outcome, cost or legacy units, and submitted request parameters, including the query or profile or place identifier.'
  deletion:
    route: Email support@crustapi.com
    text: You can ask us to delete it at any time by emailing support@crustapi.com.
  dpa:
    available: null
    text: we have signed a data processing agreement with you that says so
    url: null
  purposes:
  - purpose: Provide the service
    text: 'To provide the service: create and run your account, issue API keys, meter usage and return results.'
  - purpose: Process payments and manage balances
    text: 'To process payments and manage balances: record deposits, saved rates, charges, allowances and adjustments, and keep billing records.'
  - purpose: Verify email
    text: 'To verify your email: to confirm you own the email address on the account.'
  - purpose: Security and fraud prevention
    text: 'To keep the service secure and prevent fraud: to rate-limit, lock out repeated failed logins, and protect against misuse.'
  - purpose: Improve the product
    text: 'To understand and improve the product: to analyze usage metadata.'
  - purpose: Legal duties
    text: 'To meet legal duties: for example tax and accounting rules.'
  residency:
  - region: United States
    text: We process data in the United States.
  retention:
  - period: while your account is open
    scope: Account data
    text: We keep your account data while your account is open.
  - period: null
    scope: Usage metadata
    text: We keep it while your account is open. We do not delete it on a fixed schedule
  - period: as long as the law requires
    scope: Billing and tax records
    text: We keep some records, for example billing and tax records, for as long as the law requires or for as long as we need them to resolve disputes or enforce our agreements.
  rights:
  - right: Access
    text: Access the personal data we hold about you.
  - right: Rectification
    text: Have inaccurate data corrected (rectification).
  - right: Erasure
    text: Have your data deleted (erasure).
  - right: Restriction
    text: Restrict how we process your data.
  - right: Objection
    text: Object to our processing.
  - right: Portability
    text: Data portability.
  - right: Withdraw consent
    text: Withdraw consent where we rely on it.
  - right: Complain to supervisory authority
    text: Complain to your local supervisory authority.
  - right: Opt out of sale or sharing (California)
    text: the right to opt out of the sale or sharing of personal information.
  role:
    text: For the personal data of website visitors and account holders (for example your name, email, and account records), we are the controller.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your personal data, and we do not share it for advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We rely on the transfer safeguards put in place by each of the service providers we use, and we will tell you which mechanism applies to a given provider if you ask.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CrustAPI
provenance_date: '2026-11-09'
provider_name: CrustAPI
provider_slug: crustapi
slug: crustapi-privacy-policy
source_date: '2026-11-09'
source_filename: crustapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://crustapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CrustAPI\naid: crustapi\nurl: https://crustapi.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: For the personal data of website visitors and account holders (for example your name, email, and account\n    records), we are the controller.\ndata_categories:\n- category: identifying\n  text: 'Account data: your first name, last name, email address, and a password.'\n- category: contact\n  text: 'Account data: your first name, last name, email address, and a password.'\n- category: device\n  text: 'Infrastructure logs: our hosting providers process your IP address transiently to deliver,\
  \ rate-limit,\n    and secure the service.'\n- category: financial\n  text: 'Billing and purchase records: our payment provider handles card details.'\n- category: behavioral\n  text: 'Usage metadata: for each API request we store its endpoint, timestamp, outcome, cost or legacy units, and\n    submitted request parameters, including the query or profile or place identifier.'\npurposes:\n- purpose: Provide the service\n  text: 'To provide the service: create and run your account, issue API keys, meter usage and return results.'\n- purpose: Process payments and manage balances\n  text: 'To process payments and manage balances: record deposits, saved rates, charges, allowances and adjustments,\n    and keep billing records.'\n- purpose: Verify email\n  text: 'To verify your email: to confirm you own the email address on the account.'\n- purpose: Security and fraud prevention\n  text: 'To keep the service secure and prevent fraud: to rate-limit, lock out repeated failed logins, and protect\n\
  \    against misuse.'\n- purpose: Improve the product\n  text: 'To understand and improve the product: to analyze usage metadata.'\n- purpose: Legal duties\n  text: 'To meet legal duties: for example tax and accounting rules.'\nretention:\n- scope: Account data\n  period: while your account is open\n  text: We keep your account data while your account is open.\n- scope: Usage metadata\n  period: null\n  text: We keep it while your account is open. We do not delete it on a fixed schedule\n- scope: Billing and tax records\n  period: as long as the law requires\n  text: We keep some records, for example billing and tax records, for as long as the law requires or for as long\n    as we need them to resolve disputes or enforce our agreements.\nresidency:\n- region: United States\n  text: We process data in the United States.\ntransfers:\n- mechanism: other\n  text: We rely on the transfer safeguards put in place by each of the service providers we use, and we will tell\n    you which mechanism\
  \ applies to a given provider if you ask.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: we have signed a data processing agreement with you that says so\ndeletion:\n  route: Email support@crustapi.com\n  text: You can ask us to delete it at any time by emailing support@crustapi.com.\nrights:\n- right: Access\n  text: Access the personal data we hold about you.\n- right: Rectification\n  text: Have inaccurate data corrected (rectification).\n- right: Erasure\n  text: Have your data deleted (erasure).\n- right: Restriction\n  text: Restrict how we process your data.\n- right: Objection\n  text: Object to our processing.\n- right: Portability\n  text: Data portability.\n- right: Withdraw consent\n  text: Withdraw consent where we rely on it.\n- right: Complain to supervisory authority\n  text: Complain to your local supervisory authority.\n- right: Opt out of sale or sharing (California)\n  text: the right to opt out of the sale or sharing of personal\
  \ information.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your personal data, and we do not share it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/crustapi/privacy/crustapi-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from CrustAPI's own page on 2026-11-09.
synthetic: false
tags:
- Search
- Google Maps
- LinkedIn
- SERP / Web Scraping
- Business & Lead Data
- People / Recruiting Data
- Data Enrichment
- AI Agents / MCP
- RAG
- Data
---
