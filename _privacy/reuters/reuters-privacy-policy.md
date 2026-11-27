---
api_specs:
- filename: reuters-authentication-api-openapi.yml
  format: yaml
  label: Reuters Authentication API
  slug: reuters-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reuters/openapi/reuters-authentication-api-openapi.yml
- filename: reuters-channels-api-openapi.yml
  format: yaml
  label: Reuters Channels API
  slug: reuters-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reuters/openapi/reuters-channels-api-openapi.yml
- filename: reuters-items-api-openapi.yml
  format: yaml
  label: Reuters Items API
  slug: reuters-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reuters/openapi/reuters-items-api-openapi.yml
- filename: reuters-search-api-openapi.yml
  format: yaml
  label: Reuters Search API
  slug: reuters-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reuters/openapi/reuters-search-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, address, phone number, social media user ID, and email address
  - category: financial
    text: Payment and payment card information or bank account information, billing contact details, and ship-to and bill-to information
  - category: behavioral
    text: Usage, search, and browsing history; user journey history, including clicks, navigation, user actions, interactions, and session replays
  - category: location
    text: Region, country, state, and coarse and precise geolocation data
  - category: demographic
    text: Age; date of birth; marriage status; gender; physical characteristics; military status; political, religious, or philosophical beliefs; sexual orientation; racial or ethnic origin; and union membership
  - category: biometric
    text: Pictures, audio recordings, and video recordings.
  - category: communication
    text: the content of your queries on our Services, such as artificial intelligence prompts
  deletion:
    route: Data subject request portal, email, or phone
    text: To submit a request, you can contact us through our Data Subject Rights Portal , email us at privacy.enquiries@thomsonreuters.com , or call us at 866-633-7656.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Fulfill contractual obligations and provide Services
    text: To fulfill our contractual obligations, including registering your account and providing our Services
  - purpose: Send personalized and interest-based advertising and marketing
    text: Send you personalized and interest-based advertising and marketing
  - purpose: Develop new products and services
    text: Develop new products, services, content, and other offerings
  - purpose: Detect fraud and abuse
    text: Detect fraud and abuse, including for our Services, corporate networks and devices, offices, events, and related infrastructure
  residency:
  - region: United States
    text: Sensitive Government Personal Data and Government Customer Data is stored within the United States and will be protected and kept within our FedRAMP environment.
  retention:
  - period: null
    scope: General personal information
    text: We retain personal information as required by our enterprise records retention schedule, which varies by Service, business function, country, record classes, and record types.
  - period: null
    scope: Biometric data
    text: We take steps to permanently destroy any biometric data we maintain within the applicable timeframe specified by law or when it is no longer necessary to achieve the purpose for which it was collected or obtained, whichever occurs first.
  rights:
  - right: Right to withdraw consent
    text: Right to withdraw consent — when we process your personal data based on your consent
  - right: Right to confirm, access, correct, complete, and delete
    text: Right to confirm we process your personal information and, if so, to access — including, where possible, in a portable format — correct , complete , and delete your personal information.
  - right: Right to restrict or object to processing
    text: Right to restrict or object to the processing of certain personal information
  - right: Right to opt out of marketing emails
    text: Right to opt out of marketing emails from us
  role:
    text: Thomson Reuters acts as a controller of your personal information where we determine how and why personal information can be used
    value: both
  sale_or_sharing:
    stance: conditional
    text: Residents of certain U.S. states may also have the right to opt out of the use of their personal information for profiling or targeted advertising , including online behavioral advertising, and to opt out of the sale or sharing of their personal information
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: All U.S. entities and subsidiaries of the Thomson Reuters group of companies listed in our self-certification comply with the relevant EU-U.S. Data Privacy Framework (EU-U.S. DPF)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Reuters
provenance_date: '2026-11-10'
provider_name: Reuters
provider_slug: reuters
slug: reuters-privacy-policy
source_date: '2026-11-10'
source_filename: reuters-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.thomsonreuters.com/en/privacy-statement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Reuters\naid: reuters\nurl: https://www.thomsonreuters.com/en/privacy-statement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: Thomson Reuters acts as a controller of your personal information where we determine how and why personal\n    information can be used\ndata_categories:\n- category: identifying\n  text: Name, address, phone number, social media user ID, and email address\n- category: financial\n  text: Payment and payment card information or bank account information, billing contact details, and ship-to and\n    bill-to information\n- category: behavioral\n  text: Usage,\
  \ search, and browsing history; user journey history, including clicks, navigation, user actions, interactions,\n    and session replays\n- category: location\n  text: Region, country, state, and coarse and precise geolocation data\n- category: demographic\n  text: Age; date of birth; marriage status; gender; physical characteristics; military status; political, religious,\n    or philosophical beliefs; sexual orientation; racial or ethnic origin; and union membership\n- category: biometric\n  text: Pictures, audio recordings, and video recordings.\n- category: communication\n  text: the content of your queries on our Services, such as artificial intelligence prompts\npurposes:\n- purpose: Fulfill contractual obligations and provide Services\n  text: To fulfill our contractual obligations, including registering your account and providing our Services\n- purpose: Send personalized and interest-based advertising and marketing\n  text: Send you personalized and interest-based advertising\
  \ and marketing\n- purpose: Develop new products and services\n  text: Develop new products, services, content, and other offerings\n- purpose: Detect fraud and abuse\n  text: Detect fraud and abuse, including for our Services, corporate networks and devices, offices, events, and\n    related infrastructure\nretention:\n- scope: General personal information\n  period: null\n  text: We retain personal information as required by our enterprise records retention schedule, which varies by\n    Service, business function, country, record classes, and record types.\n- scope: Biometric data\n  period: null\n  text: We take steps to permanently destroy any biometric data we maintain within the applicable timeframe specified\n    by law or when it is no longer necessary to achieve the purpose for which it was collected or obtained, whichever\n    occurs first.\nresidency:\n- region: United States\n  text: Sensitive Government Personal Data and Government Customer Data is stored within the United\
  \ States and will\n    be protected and kept within our FedRAMP environment.\ntransfers:\n- mechanism: DPF\n  text: All U.S. entities and subsidiaries of the Thomson Reuters group of companies listed in our self-certification\n    comply with the relevant EU-U.S. Data Privacy Framework (EU-U.S. DPF)\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Data subject request portal, email, or phone\n  text: To submit a request, you can contact us through our Data Subject Rights Portal , email us at privacy.enquiries@thomsonreuters.com\n    , or call us at 866-633-7656.\nrights:\n- right: Right to withdraw consent\n  text: Right to withdraw consent — when we process your personal data based on your consent\n- right: Right to confirm, access, correct, complete, and delete\n  text: Right to confirm we process your personal information and, if so, to access — including, where possible,\n    in a portable format — correct , complete\
  \ , and delete your personal information.\n- right: Right to restrict or object to processing\n  text: Right to restrict or object to the processing of certain personal information\n- right: Right to opt out of marketing emails\n  text: Right to opt out of marketing emails from us\nsale_or_sharing:\n  stance: conditional\n  text: Residents of certain U.S. states may also have the right to opt out of the use of their personal information\n    for profiling or targeted advertising , including online behavioral advertising, and to opt out of the sale\n    or sharing of their personal information\n"
source_yaml_url: https://artifacts.apis.io/reuters/privacy/reuters-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Reuters's own page on 2026-11-10.
synthetic: false
tags:
- Business
- Finance
- Journalism
- Media
- News
- Wire Service
---
