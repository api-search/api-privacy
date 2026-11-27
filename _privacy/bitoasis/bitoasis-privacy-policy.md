---
api_specs:
- filename: bitoasis-market-data-api-openapi.yml
  format: yaml
  label: BitOasis Market Data API
  slug: bitoasis-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitoasis/openapi/bitoasis-market-data-api-openapi.yml
- filename: bitoasis-accounts-api-openapi.yml
  format: yaml
  label: BitOasis Accounts API
  slug: bitoasis-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitoasis/openapi/bitoasis-accounts-api-openapi.yml
- filename: bitoasis-banks-api-openapi.yml
  format: yaml
  label: BitOasis Banks API
  slug: bitoasis-banks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitoasis/openapi/bitoasis-banks-api-openapi.yml
- filename: bitoasis-deposit-api-openapi.yml
  format: yaml
  label: BitOasis Deposit API
  slug: bitoasis-deposit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitoasis/openapi/bitoasis-deposit-api-openapi.yml
- filename: bitoasis-error-responses-api-openapi.yml
  format: yaml
  label: BitOasis Error responses API
  slug: bitoasis-error-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitoasis/openapi/bitoasis-error-responses-api-openapi.yml
- filename: bitoasis-order-api-openapi.yml
  format: yaml
  label: BitOasis Order API
  slug: bitoasis-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitoasis/openapi/bitoasis-order-api-openapi.yml
- filename: bitoasis-withdrawal-api-openapi.yml
  format: yaml
  label: BitOasis Withdrawal API
  slug: bitoasis-withdrawal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitoasis/openapi/bitoasis-withdrawal-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, date of birth, nationality, gender, photograph, biometrics, video/liveness checks, video calls, passport/Emirates ID, email address, phone number, postal address
  - category: financial
    text: Bank account details, salary certificates, source of funds, credit/debit card numbers, PAN/tax identifiers, wallet addresses, trading data, transaction history, credit history
  - category: location
    text: Device identifiers, IP address, device OS, mobile carrier, geolocation, camera/microphone access
  - category: behavioral
    text: URL clickstream, page response times, session duration, viewed/searched items, browsing paths
  - category: device
    text: your mobile device’s unique ID number, your mobile device’s geographic location while the app is running
  deletion:
    route: Service request ticket to privacy@bitoasis.net or the email in section 16
    text: Upon your request, we will deactivate your account and remove your personal information from publicly available sections of the Platform.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing services and KYC/AML compliance
    text: We only process information provided by you for necessary and relevant purposes such as providing BitOasis Services
  - purpose: Marketing and user profiling
    text: improve our marketing and promotional efforts, analyze site usage, user profiling and disclose aggregated statistics
  - purpose: Investigating activities and enforcing terms
    text: We also use the information we collect about you to review and investigate your activities or transactions on our Platform, resolve disputes, troubleshoot problems, and enforce our Terms of Service Agreement.
  retention:
  - period: 8 years
    scope: Active account and dispute/legal purposes
    text: we retain any Personal Data for as long as your User Account is active, and for an additional time period of 8 years (in line with our policy)
  rights:
  - right: Access
    text: You have the right to obtain confirmation that your Personal Data is or is not being processed, to obtain access to that Personal Data
  - right: Correction
    text: You can rectify inaccurate personal data
  - right: Erasure
    text: Upon your request, we will deactivate your account and remove your personal information from publicly available sections of the Platform.
  - right: Restrict processing
    text: you also have the right to restrict the processing of your Personal Data
  - right: Object / stop processing
    text: you also have the right to stop processing of your Personal Data
  - right: Withdraw consent
    text: You have the right to withdraw your previous consent to the processing of your Personal Data.
  - right: Human review of automated decisions
    text: You have the right to request that decisions which significantly affect you and are made solely through automated processing without human involvement be reviewed by a human.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We will never sell your information
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: your Personal Data may be transferred to and stored in locations outside of UAE(“Alternate Country“) by us or our Affiliates/partners located in foreign jurisdictions
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BitOasis
provenance_date: '2026-11-09'
provider_name: BitOasis
provider_slug: bitoasis
slug: bitoasis-privacy-policy
source_date: '2026-11-09'
source_filename: bitoasis-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bitoasis.net/en/page/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BitOasis\naid: bitoasis\nurl: https://bitoasis.net/en/page/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name, date of birth, nationality, gender, photograph, biometrics, video/liveness checks, video calls, passport/Emirates\n    ID, email address, phone number, postal address\n- category: financial\n  text: Bank account details, salary certificates, source of funds, credit/debit card numbers, PAN/tax identifiers,\n    wallet addresses, trading data, transaction history, credit history\n- category: location\n  text: Device\
  \ identifiers, IP address, device OS, mobile carrier, geolocation, camera/microphone access\n- category: behavioral\n  text: URL clickstream, page response times, session duration, viewed/searched items, browsing paths\n- category: device\n  text: your mobile device’s unique ID number, your mobile device’s geographic location while the app is running\npurposes:\n- purpose: Providing services and KYC/AML compliance\n  text: We only process information provided by you for necessary and relevant purposes such as providing BitOasis\n    Services\n- purpose: Marketing and user profiling\n  text: improve our marketing and promotional efforts, analyze site usage, user profiling and disclose aggregated\n    statistics\n- purpose: Investigating activities and enforcing terms\n  text: We also use the information we collect about you to review and investigate your activities or transactions\n    on our Platform, resolve disputes, troubleshoot problems, and enforce our Terms of Service Agreement.\n\
  retention:\n- scope: Active account and dispute/legal purposes\n  period: 8 years\n  text: we retain any Personal Data for as long as your User Account is active, and for an additional time period\n    of 8 years (in line with our policy)\nresidency: []\ntransfers:\n- mechanism: other\n  text: your Personal Data may be transferred to and stored in locations outside of UAE(“Alternate Country“) by\n    us or our Affiliates/partners located in foreign jurisdictions\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Service request ticket to privacy@bitoasis.net or the email in section 16\n  text: Upon your request, we will deactivate your account and remove your personal information from publicly available\n    sections of the Platform.\nrights:\n- right: Access\n  text: You have the right to obtain confirmation that your Personal Data is or is not being processed, to obtain\n    access to that Personal Data\n- right: Correction\n\
  \  text: You can rectify inaccurate personal data\n- right: Erasure\n  text: Upon your request, we will deactivate your account and remove your personal information from publicly available\n    sections of the Platform.\n- right: Restrict processing\n  text: you also have the right to restrict the processing of your Personal Data\n- right: Object / stop processing\n  text: you also have the right to stop processing of your Personal Data\n- right: Withdraw consent\n  text: You have the right to withdraw your previous consent to the processing of your Personal Data.\n- right: Human review of automated decisions\n  text: You have the right to request that decisions which significantly affect you and are made solely through\n    automated processing without human involvement be reviewed by a human.\nsale_or_sharing:\n  stance: prohibited\n  text: We will never sell your information\n"
source_yaml_url: https://artifacts.apis.io/bitoasis/privacy/bitoasis-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from BitOasis's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Exchange
- Trading
- Digital Assets
- Bitcoin
- MENA
- Fintech
- MCP
---
