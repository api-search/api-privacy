---
api_specs:
- filename: door-access-management-api-openapi.yml
  format: yaml
  label: Door Access Management API
  slug: door-access-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/door/openapi/door-access-management-api-openapi.yml
- filename: door-buildings-api-openapi.yml
  format: yaml
  label: Door Buildings API
  slug: door-buildings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/door/openapi/door-buildings-api-openapi.yml
- filename: door-doors-and-keys-api-openapi.yml
  format: yaml
  label: Door Doors and Keys API
  slug: door-doors-and-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/door/openapi/door-doors-and-keys-api-openapi.yml
- filename: door-partner-authentication-api-openapi.yml
  format: yaml
  label: Door Partner Authentication API
  slug: door-partner-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/door/openapi/door-partner-authentication-api-openapi.yml
- filename: door-user-authentication-api-openapi.yml
  format: yaml
  label: Door User Authentication API
  slug: door-user-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/door/openapi/door-user-authentication-api-openapi.yml
- filename: door-users-api-openapi.yml
  format: yaml
  label: Door Users API
  slug: door-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/door/openapi/door-users-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, physical address, email, telephone number, username and password
  - category: location
    text: Your geolocation, with your permission
  - category: device
    text: unique device identifiers, network information, IP address, hardware model, operating system
  - category: behavioral
    text: Your use of our websites and applications, including behavior data.
  - category: financial
    text: Your payment history (for example, when you purchase products through our website
  deletion:
    route: In-app deletion link, or email to support@door.com; single-family users may also call a toll-free number
    text: you may request account deletion directly from us through the app by using the appropriate link, by emailing support@door.com or by calling our toll-free number +1 (888) 808-0670
  dpa:
    available: null
    text: We have data protection terms in place with every third party we engage for the provision of such services.
    url: null
  purposes:
  - purpose: provide products and services
    text: To provide you with products, services, or functionality;
  - purpose: safety and security of building
    text: To monitor the safety and security of a building that is under our property management;
  - purpose: analytics
    text: To analyze how you use and interact with the Products and Services;
  - purpose: marketing
    text: For marketing, promotional and advertising purposes;
  - purpose: develop new products
    text: To develop new products and services;
  residency:
  - region: United States and Canada
    text: The Products and Services are intended for use in the United States of America and Canada only.
  retention:
  - period: two (2) years
    scope: General users outside New York City, access logs
    text: For users located outside of New York City, we retain user authentication data (or user access event logs, including timestamps of when a user unlocked a DOOR or Latch access device), for two (2) years from the date of collection.
  - period: ninety (90) days
    scope: New York City residents of multi-family buildings
    text: we delete or anonymize user authentication data (or user access event logs, including timestamps showing when a user unlocked a DOOR or Latch access device) ninety (90) days from the date of collection.
  rights:
  - right: access and correction (Canada)
    text: be given access to their Personal Information, and be able to correct inaccurate Personal Information.
  - right: copy of personal information (Canada)
    text: including to receive a copy of your Personal Information
  - right: opt out of marketing communications
    text: You may opt out of receiving such communications at any time by following the instructions in the communication
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: we may store and process your Personal Information in any country where we have facilities or in which we engage third-party service providers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Door
provenance_date: '2026-11-09'
provider_name: Door
provider_slug: door
slug: door-privacy-policy
source_date: '2026-11-09'
source_filename: door-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://door.com/policy/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Door\naid: door\nurl: https://door.com/policy/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: your name, physical address, email, telephone number, username and password\n- category: location\n  text: Your geolocation, with your permission\n- category: device\n  text: unique device identifiers, network information, IP address, hardware model, operating system\n- category: behavioral\n  text: Your use of our websites and applications, including behavior data.\n- category: financial\n  text: Your payment history (for example, when\
  \ you purchase products through our website\npurposes:\n- purpose: provide products and services\n  text: To provide you with products, services, or functionality;\n- purpose: safety and security of building\n  text: To monitor the safety and security of a building that is under our property management;\n- purpose: analytics\n  text: To analyze how you use and interact with the Products and Services;\n- purpose: marketing\n  text: For marketing, promotional and advertising purposes;\n- purpose: develop new products\n  text: To develop new products and services;\nretention:\n- scope: General users outside New York City, access logs\n  period: two (2) years\n  text: For users located outside of New York City, we retain user authentication data (or user access event logs,\n    including timestamps of when a user unlocked a DOOR or Latch access device), for two (2) years from the date\n    of collection.\n- scope: New York City residents of multi-family buildings\n  period: ninety (90) days\n\
  \  text: we delete or anonymize user authentication data (or user access event logs, including timestamps showing\n    when a user unlocked a DOOR or Latch access device) ninety (90) days from the date of collection.\nresidency:\n- region: United States and Canada\n  text: The Products and Services are intended for use in the United States of America and Canada only.\ntransfers:\n- mechanism: other\n  text: we may store and process your Personal Information in any country where we have facilities or in which we\n    engage third-party service providers.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: We have data protection terms in place with every third party we engage for the provision of such services.\ndeletion:\n  route: In-app deletion link, or email to support@door.com; single-family users may also call a toll-free number\n  text: you may request account deletion directly from us through the app by using the appropriate link, by emailing\n\
  \    support@door.com or by calling our toll-free number +1 (888) 808-0670\nrights:\n- right: access and correction (Canada)\n  text: be given access to their Personal Information, and be able to correct inaccurate Personal Information.\n- right: copy of personal information (Canada)\n  text: including to receive a copy of your Personal Information\n- right: opt out of marketing communications\n  text: You may opt out of receiving such communications at any time by following the instructions in the communication\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/door/privacy/door-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
summary_line: 19 quoted statements, read from Door's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Access Control
- Smart Buildings
- PropTech
- Physical Security
- IoT
- Multifamily
- Real Estate
- Smart Lock
- Building Automation
---
