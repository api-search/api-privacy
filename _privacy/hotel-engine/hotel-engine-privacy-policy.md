---
api_specs:
- filename: hotel-engine-catalogservice-api-openapi.yml
  format: yaml
  label: Engine Catalog Service API
  slug: hotel-engine-catalogservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hotel-engine/openapi/hotel-engine-catalogservice-api-openapi.yml
- filename: hotel-engine-lodgingbookingservice-api-openapi.yml
  format: yaml
  label: Engine Lodging Booking Service API
  slug: hotel-engine-lodgingbookingservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hotel-engine/openapi/hotel-engine-lodgingbookingservice-api-openapi.yml
- filename: hotel-engine-lodgingshoppingservice-api-openapi.yml
  format: yaml
  label: Engine Lodging Shopping Service API
  slug: hotel-engine-lodgingshoppingservice-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hotel-engine/openapi/hotel-engine-lodgingshoppingservice-api-openapi.yml
- filename: hotel-engine-content-service-api-openapi.yml
  format: yaml
  label: Engine Content Service API
  slug: hotel-engine-content-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hotel-engine/openapi/hotel-engine-content-service-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: such as your name, contact information, and password
  - category: financial
    text: If you elect to connect a bank account to the Services, we collect information about that account
  - category: location
    text: While the App is in use, it may collect your precise location using GPS on your mobile device
  - category: behavioral
    text: we may collect information about your interests to show you relevant advertisements on third party websites and information services
  - category: device
    text: device and browser information, IP address, referring web page, navigation history
  - category: health
    text: Individual health conditions, treatment, diseases, diagnosis, or dietary restrictions in the context of a booking, event registration, or emergency contact form
  - category: communication
    text: we will collect your name, any contact information accompanying the communication, and your communication contents
  - category: demographic
    text: nationality, gender, driver’s license, or other identification card information
  deletion:
    route: phone or email request to Engine
    text: To exercise any of the other rights described above, please submit your request by calling us at 855-567-4683 or emailing us
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Deliver the Services and manage bookings
    text: to make and manage bookings you make through the Services
  - purpose: Marketing
    text: For our marketing purposes, such as developing and providing promotional and advertising materials
  - purpose: Compliance and legal claims
    text: For compliance purposes, including enforcing our legal rights or defending against legal claims.
  - purpose: Fraud prevention and security
    text: detecting, investigating, and preventing fraud and unauthorized access to accounts and Agent connections
  residency:
  - region: United States or the Philippines
    text: your personal data will be stored and processed in the United States or the Philippines, where our systems are located.
  retention:
  - period: twelve (12) months
    scope: Identified MCP Server request logs
    text: We retain identified MCP Server request logs for twelve (12) months.
  - period: ten (10) years
    scope: Acceptance records for AI Integration Terms
    text: We retain acceptance records, which identify the user who accepted the AI Integration Terms and that user’s role, for ten (10) years.
  - period: null
    scope: Booking records
    text: We keep booking records for as long as needed to meet tax, accounting, and dispute obligations
  - period: null
    scope: Bank account connection information
    text: we retain such information for the duration of your active connection to the account
  rights:
  - right: Access
    text: the right to confirm whether we process your personal data and to access a copy
  - right: Correction
    text: the right to the correction of inaccurate personal data
  - right: Deletion
    text: the right to the deletion of your personal data
  - right: Opt-out of targeted advertising, sales, or profiling
    text: the right to opt-out of the use of personal data for targeted advertising, personal data sales, or profiling resulting in significant consequences
  - right: Limit use of sensitive personal information
    text: the right to restrict the processing of sensitive personal information to uses which are necessary to perform the Services
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: the right to opt out of “sale” (as that term is defined in the law) or the sharing of personal data for cross-contextual behavioral advertising purposes
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: If we transfer personal data to the United States from another jurisdiction, we will do so in a way that complies with applicable legal requirements.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Engine
provenance_date: '2026-11-09'
provider_name: Engine
provider_slug: hotel-engine
slug: hotel-engine-privacy-policy
source_date: '2026-11-09'
source_filename: hotel-engine-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://engine.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Engine\naid: hotel-engine\nurl: https://engine.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: such as your name, contact information, and password\n- category: financial\n  text: If you elect to connect a bank account to the Services, we collect information about that account\n- category: location\n  text: While the App is in use, it may collect your precise location using GPS on your mobile device\n- category: behavioral\n  text: we may collect information about your interests to show you relevant advertisements on\
  \ third party websites\n    and information services\n- category: device\n  text: device and browser information, IP address, referring web page, navigation history\n- category: health\n  text: Individual health conditions, treatment, diseases, diagnosis, or dietary restrictions in the context of\n    a booking, event registration, or emergency contact form\n- category: communication\n  text: we will collect your name, any contact information accompanying the communication, and your communication\n    contents\n- category: demographic\n  text: nationality, gender, driver’s license, or other identification card information\npurposes:\n- purpose: Deliver the Services and manage bookings\n  text: to make and manage bookings you make through the Services\n- purpose: Marketing\n  text: For our marketing purposes, such as developing and providing promotional and advertising materials\n- purpose: Compliance and legal claims\n  text: For compliance purposes, including enforcing our legal rights\
  \ or defending against legal claims.\n- purpose: Fraud prevention and security\n  text: detecting, investigating, and preventing fraud and unauthorized access to accounts and Agent connections\nretention:\n- scope: Identified MCP Server request logs\n  period: twelve (12) months\n  text: We retain identified MCP Server request logs for twelve (12) months.\n- scope: Acceptance records for AI Integration Terms\n  period: ten (10) years\n  text: We retain acceptance records, which identify the user who accepted the AI Integration Terms and that user’s\n    role, for ten (10) years.\n- scope: Booking records\n  period: null\n  text: We keep booking records for as long as needed to meet tax, accounting, and dispute obligations\n- scope: Bank account connection information\n  period: null\n  text: we retain such information for the duration of your active connection to the account\nresidency:\n- region: United States or the Philippines\n  text: your personal data will be stored and processed\
  \ in the United States or the Philippines, where our systems\n    are located.\ntransfers:\n- mechanism: other\n  text: If we transfer personal data to the United States from another jurisdiction, we will do so in a way that\n    complies with applicable legal requirements.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: phone or email request to Engine\n  text: To exercise any of the other rights described above, please submit your request by calling us at 855-567-4683\n    or emailing us\nrights:\n- right: Access\n  text: the right to confirm whether we process your personal data and to access a copy\n- right: Correction\n  text: the right to the correction of inaccurate personal data\n- right: Deletion\n  text: the right to the deletion of your personal data\n- right: Opt-out of targeted advertising, sales, or profiling\n  text: the right to opt-out of the use of personal data for targeted advertising, personal data\
  \ sales, or profiling\n    resulting in significant consequences\n- right: Limit use of sensitive personal information\n  text: the right to restrict the processing of sensitive personal information to uses which are necessary to perform\n    the Services\nsale_or_sharing:\n  stance: conditional\n  text: the right to opt out of “sale” (as that term is defined in the law) or the sharing of personal data for\n    cross-contextual behavioral advertising purposes\n"
source_yaml_url: https://artifacts.apis.io/hotel-engine/privacy/hotel-engine-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Engine's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Business Travel
- Lodging
- Hotels
- Booking
- Travel Management
- Expense Management
- Payments
- gRPC
- Protobuf
- Partner API
---
