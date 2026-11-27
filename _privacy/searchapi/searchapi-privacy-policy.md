---
api_specs:
- filename: searchapi-search-api-openapi.yml
  format: yaml
  label: SearchApi SERP API
  slug: searchapi-serp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searchapi/openapi/searchapi-search-api-openapi.yml
- filename: searchapi-account-api-openapi.yml
  format: yaml
  label: SearchApi Account & Analytics API
  slug: searchapi-account-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searchapi/openapi/searchapi-account-api-openapi.yml
- filename: searchapi-analytics-api-openapi.yml
  format: yaml
  label: SearchApi Analytics API
  slug: searchapi-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/searchapi/openapi/searchapi-analytics-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: we typically ask for identifying information such as your name, email address, and maybe a company name
  - category: financial
    text: we ask for your credit card and billing address
  - category: location
    text: We log all access to all accounts by full IP address
  - category: device
    text: your browser automatically shares certain information such as which operating system and browser version you are using
  - category: behavioral
    text: We track that information, along with the pages you are visiting, page load timing, and which website referred you for statistical purposes like conversion rates and to test new designs
  - category: communication
    text: When you write SearchApi with a question or to ask for help, we keep that correspondence, including the email address
  deletion:
    route: email support@searchapi.io
    text: If you want your account-level data deleted, contact us at support@searchapi.io and we will delete it within 30 days of your request.
  dpa:
    available: true
    text: For more details on data deletion and return, see our Data Processing Agreement .
    url: null
  purposes:
  - purpose: provide requested products or services
    text: To provide products or services you’ve requested .
  - purpose: billing and invoicing
    text: That’s so we can charge you for service, calculate taxes due, and send you invoices.
  - purpose: account security
    text: We log all access to all accounts by full IP address so that we can always verify no unauthorized access has happened.
  - purpose: web analytics
    text: for statistical purposes like conversion rates and to test new designs
  - purpose: bot and spam prevention
    text: We use Google reCAPTCHA across our application to mitigate brute force logins and prevent spam.
  residency:
  - region: United States
    text: Our products and other web properties are operated in the United States.
  retention:
  - period: as long as your product account is active
    scope: login data
    text: We keep this login data for as long as your product account is active.
  - period: 30 days
    scope: web analytics data
    text: We blind all of these individual identifiers after 30 days.
  - period: null
    scope: account-level data after cancellation
    text: Account-level data (your name, email address, billing records, and API usage history) is retained for legitimate business purposes such as tax compliance, fraud prevention, and account reactivation.
  rights:
  - right: Right to Know
    text: You have the right to know what personal information is collected, used, shared or sold.
  - right: Right of Access
    text: This includes your right to access the personal information we gather about you
  - right: Right to Correction
    text: You have the right to request correction of your personal information.
  - right: Right to Erasure
    text: This is your right to request, subject to certain limitations under applicable law, that your personal information be erased from our possession and, by extension, all of our service providers.
  - right: Right to Complain
    text: You have the right to make a complaint regarding our handling of your personal information with the appropriate supervisory authority.
  - right: Right to Restrict Processing
    text: This is your right to request restriction of how and why your personal information is used or processed, including opting out of sale of personal information.
  - right: Right to Object
    text: You have the right, in certain situations, to object to how or why your personal information is processed.
  - right: Right to Portability
    text: You have the right to receive the personal information we have about you and the right to transmit it to another party.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: 'We promise we never sell your data: never have, never will.'
  subprocessors:
    text: You can view the list of third-party services we use in each product here .
    url: null
  transfers:
  - mechanism: SCC
    text: For international transfers, we rely on Standard Contractual Clauses (SCCs)
  - mechanism: DPF
    text: and the EU-US Data Privacy Framework as described in our Data Processing Agreement
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SearchApi
provenance_date: '2026-11-10'
provider_name: SearchApi
provider_slug: searchapi
slug: searchapi-privacy-policy
source_date: '2026-11-10'
source_filename: searchapi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.searchapi.io/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SearchApi\naid: searchapi\nurl: https://www.searchapi.io/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we typically ask for identifying information such as your name, email address, and maybe a company name\n- category: financial\n  text: we ask for your credit card and billing address\n- category: location\n  text: We log all access to all accounts by full IP address\n- category: device\n  text: your browser automatically shares certain information such as which operating system and browser version\n    you are using\n\
  - category: behavioral\n  text: We track that information, along with the pages you are visiting, page load timing, and which website referred\n    you for statistical purposes like conversion rates and to test new designs\n- category: communication\n  text: When you write SearchApi with a question or to ask for help, we keep that correspondence, including the\n    email address\npurposes:\n- purpose: provide requested products or services\n  text: To provide products or services you’ve requested .\n- purpose: billing and invoicing\n  text: That’s so we can charge you for service, calculate taxes due, and send you invoices.\n- purpose: account security\n  text: We log all access to all accounts by full IP address so that we can always verify no unauthorized access\n    has happened.\n- purpose: web analytics\n  text: for statistical purposes like conversion rates and to test new designs\n- purpose: bot and spam prevention\n  text: We use Google reCAPTCHA across our application to mitigate\
  \ brute force logins and prevent spam.\nretention:\n- scope: login data\n  period: as long as your product account is active\n  text: We keep this login data for as long as your product account is active.\n- scope: web analytics data\n  period: 30 days\n  text: We blind all of these individual identifiers after 30 days.\n- scope: account-level data after cancellation\n  period: null\n  text: Account-level data (your name, email address, billing records, and API usage history) is retained for legitimate\n    business purposes such as tax compliance, fraud prevention, and account reactivation.\nresidency:\n- region: United States\n  text: Our products and other web properties are operated in the United States.\ntransfers:\n- mechanism: SCC\n  text: For international transfers, we rely on Standard Contractual Clauses (SCCs)\n- mechanism: DPF\n  text: and the EU-US Data Privacy Framework as described in our Data Processing Agreement\nsubprocessors:\n  url: null\n  text: You can view the list\
  \ of third-party services we use in each product here .\ndpa:\n  available: true\n  url: null\n  text: For more details on data deletion and return, see our Data Processing Agreement .\ndeletion:\n  route: email support@searchapi.io\n  text: If you want your account-level data deleted, contact us at support@searchapi.io and we will delete it within\n    30 days of your request.\nrights:\n- right: Right to Know\n  text: You have the right to know what personal information is collected, used, shared or sold.\n- right: Right of Access\n  text: This includes your right to access the personal information we gather about you\n- right: Right to Correction\n  text: You have the right to request correction of your personal information.\n- right: Right to Erasure\n  text: This is your right to request, subject to certain limitations under applicable law, that your personal information\n    be erased from our possession and, by extension, all of our service providers.\n- right: Right to Complain\n\
  \  text: You have the right to make a complaint regarding our handling of your personal information with the appropriate\n    supervisory authority.\n- right: Right to Restrict Processing\n  text: This is your right to request restriction of how and why your personal information is used or processed,\n    including opting out of sale of personal information.\n- right: Right to Object\n  text: You have the right, in certain situations, to object to how or why your personal information is processed.\n- right: Right to Portability\n  text: You have the right to receive the personal information we have about you and the right to transmit it to\n    another party.\nsale_or_sharing:\n  stance: prohibited\n  text: 'We promise we never sell your data: never have, never will.'\n"
source_yaml_url: https://artifacts.apis.io/searchapi/privacy/searchapi-privacy-policy.yml
stated_fields:
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
summary_line: 29 quoted statements, read from SearchApi's own page on 2026-11-10.
synthetic: false
tags:
- Search
- SERP
- Google Search
- Web Scraping
- Search data
- Market Intelligence
- SEO
- MCP
- Agent-Native
---
