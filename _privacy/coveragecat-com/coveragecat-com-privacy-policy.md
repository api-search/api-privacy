---
api_specs:
- filename: coveragecat-com-agent-api-openapi.yml
  format: yaml
  label: Coverage Cat Agent API
  slug: coveragecat-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coveragecat-com/openapi/coveragecat-com-agent-api-openapi.yml
- filename: coveragecat-com-consumer-api-openapi.yml
  format: yaml
  label: Coverage Cat Consumer API
  slug: coveragecat-com-consumer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coveragecat-com/openapi/coveragecat-com-consumer-api-openapi.yml
- filename: coveragecat-com-intake-api-openapi.yml
  format: yaml
  label: Coverage Cat Intake API
  slug: coveragecat-com-intake-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coveragecat-com/openapi/coveragecat-com-intake-api-openapi.yml
- filename: coveragecat-com-tools-api-openapi.yml
  format: yaml
  label: Coverage Cat Tools API
  slug: coveragecat-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coveragecat-com/openapi/coveragecat-com-tools-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: identity and contact details
  - category: contact
    text: 'Personally identifiable information may include, but is not limited to: Email address First name and last name Phone number Address, State, Province, ZIP/Postal code, City'
  - category: financial
    text: household, marital, family, employment, income, asset and other financial information
  - category: location
    text: We may use and store information about your location if you give us permission to do so
  - category: device
    text: This Usage Data may include information such as your computer's Internet Protocol address (e.g. IP address)
  - category: demographic
    text: age and date of birth; sex or gender where relevant to the requested product
  - category: communication
    text: correspondence and chat content
  deletion:
    route: account deletion request
    text: If you request account deletion, Coverage Cat deletes covered application and service-delivery records and document references from its application database, subject to applicable exceptions.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and maintain our Service
    text: to provide and maintain our Service
  - purpose: marketing emails
    text: We may use your Personal Data to send email newsletters, marketing or promotional materials, and other information that may be of interest to you.
  - purpose: internal price-estimation model development
    text: to develop, validate, and improve Coverage Cat's internal insurance price-estimation models using selected historical application and quote attributes and resulting premiums
  residency:
  - region: United States
    text: we transfer the data, including Personal Data, to United States and process it there
  retention:
  - period: null
    scope: Personal Data
    text: We will retain your Personal Data only for as long as is necessary for the purposes set out in this Privacy Policy.
  - period: shorter period
    scope: Usage Data
    text: Usage Data is generally retained for a shorter period
  - period: 30 days
    scope: browser draft in local storage
    text: After 30 days the site no longer restores the draft
  - period: up to 60 days
    scope: application-resume record
    text: for up to 60 days so a returning browser can continue an application
  rights:
  - right: access, update or delete
    text: the right to access, update or to delete the information we have on you
  - right: rectification
    text: the right of rectification. You have the right to have your information rectified if that information is inaccurate or incomplete
  - right: object
    text: the right to object. You have the right to object to our processing of your Personal Data
  - right: restriction
    text: the right of restriction
  - right: portability
    text: the right to data portability
  - right: withdraw consent
    text: the right to withdraw consent
  role:
    text: For the purpose of this Privacy Policy, we are a Data Controller of your data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Coverage Cat's policy is not to sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Coverage Cat, Inc. will take all the steps reasonably necessary to ensure that your data is treated securely
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Coverage Cat
provenance_date: '2026-11-09'
provider_name: Coverage Cat
provider_slug: coveragecat-com
slug: coveragecat-com-privacy-policy
source_date: '2026-11-09'
source_filename: coveragecat-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.coveragecat.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Coverage Cat\naid: coveragecat-com\nurl: https://www.coveragecat.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: For the purpose of this Privacy Policy, we are a Data Controller of your data.\ndata_categories:\n- category: identifying\n  text: identity and contact details\n- category: contact\n  text: 'Personally identifiable information may include, but is not limited to: Email address First name and last\n    name Phone number Address, State, Province, ZIP/Postal code, City'\n- category: financial\n  text: household, marital, family, employment, income, asset and other\
  \ financial information\n- category: location\n  text: We may use and store information about your location if you give us permission to do so\n- category: device\n  text: This Usage Data may include information such as your computer's Internet Protocol address (e.g. IP address)\n- category: demographic\n  text: age and date of birth; sex or gender where relevant to the requested product\n- category: communication\n  text: correspondence and chat content\npurposes:\n- purpose: provide and maintain our Service\n  text: to provide and maintain our Service\n- purpose: marketing emails\n  text: We may use your Personal Data to send email newsletters, marketing or promotional materials, and other information\n    that may be of interest to you.\n- purpose: internal price-estimation model development\n  text: to develop, validate, and improve Coverage Cat's internal insurance price-estimation models using selected\n    historical application and quote attributes and resulting premiums\nretention:\n\
  - scope: Personal Data\n  period: null\n  text: We will retain your Personal Data only for as long as is necessary for the purposes set out in this Privacy\n    Policy.\n- scope: Usage Data\n  period: shorter period\n  text: Usage Data is generally retained for a shorter period\n- scope: browser draft in local storage\n  period: 30 days\n  text: After 30 days the site no longer restores the draft\n- scope: application-resume record\n  period: up to 60 days\n  text: for up to 60 days so a returning browser can continue an application\nresidency:\n- region: United States\n  text: we transfer the data, including Personal Data, to United States and process it there\ntransfers:\n- mechanism: other\n  text: Coverage Cat, Inc. will take all the steps reasonably necessary to ensure that your data is treated securely\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion request\n  text: If you request account deletion,\
  \ Coverage Cat deletes covered application and service-delivery records and\n    document references from its application database, subject to applicable exceptions.\nrights:\n- right: access, update or delete\n  text: the right to access, update or to delete the information we have on you\n- right: rectification\n  text: the right of rectification. You have the right to have your information rectified if that information is\n    inaccurate or incomplete\n- right: object\n  text: the right to object. You have the right to object to our processing of your Personal Data\n- right: restriction\n  text: the right of restriction\n- right: portability\n  text: the right to data portability\n- right: withdraw consent\n  text: the right to withdraw consent\nsale_or_sharing:\n  stance: prohibited\n  text: Coverage Cat's policy is not to sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/coveragecat-com/privacy/coveragecat-com-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Coverage Cat's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurance Broker
- Homeowners Insurance
- Umbrella Insurance
- Auto Insurance
- AI Agents
- MCP
---
