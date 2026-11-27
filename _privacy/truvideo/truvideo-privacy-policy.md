---
api_specs:
- filename: truvideo-authentication-api-openapi.yml
  format: yaml
  label: TruVideo Authentication API
  slug: truvideo-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truvideo/openapi/truvideo-authentication-api-openapi.yml
- filename: truvideo-chat-api-openapi.yml
  format: yaml
  label: TruVideo Chat API
  slug: truvideo-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truvideo/openapi/truvideo-chat-api-openapi.yml
- filename: truvideo-customers-api-openapi.yml
  format: yaml
  label: TruVideo Customers API
  slug: truvideo-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truvideo/openapi/truvideo-customers-api-openapi.yml
- filename: truvideo-dealers-api-openapi.yml
  format: yaml
  label: TruVideo Dealers API
  slug: truvideo-dealers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truvideo/openapi/truvideo-dealers-api-openapi.yml
- filename: truvideo-files-api-openapi.yml
  format: yaml
  label: TruVideo Files API
  slug: truvideo-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truvideo/openapi/truvideo-files-api-openapi.yml
- filename: truvideo-messages-api-openapi.yml
  format: yaml
  label: TruVideo Messages API
  slug: truvideo-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truvideo/openapi/truvideo-messages-api-openapi.yml
- filename: truvideo-repair-orders-api-openapi.yml
  format: yaml
  label: TruVideo Repair Orders API
  slug: truvideo-repair-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truvideo/openapi/truvideo-repair-orders-api-openapi.yml
- filename: truvideo-reports-api-openapi.yml
  format: yaml
  label: TruVideo Reports API
  slug: truvideo-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truvideo/openapi/truvideo-reports-api-openapi.yml
- filename: truvideo-support-api-openapi.yml
  format: yaml
  label: TruVideo Support API
  slug: truvideo-support-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truvideo/openapi/truvideo-support-api-openapi.yml
- filename: truvideo-users-api-openapi.yml
  format: yaml
  label: TruVideo Users API
  slug: truvideo-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truvideo/openapi/truvideo-users-api-openapi.yml
- filename: truvideo-videos-api-openapi.yml
  format: yaml
  label: TruVideo Videos API
  slug: truvideo-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/truvideo/openapi/truvideo-videos-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: Voluntarily provided information which may include your name, address, email address, billing and/or credit card information etc.
  - category: identifying
    text: Authentication tokens (JSON Web Tokens, including access tokens and refresh tokens) issued by TruVideo’s authentication service to maintain your authenticated session.
  - category: device
    text: We may also gather information about the type of browser you are using, IP address or type of operating system
  - category: behavioral
    text: Information automatically collected when visiting our application, which may include cookies, third party tracking technologies and server logs.
  deletion:
    route: Email request to security@truvideo.com
    text: You may request deletion of your data by contacting security@truvideo.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery and support
    text: to ensure delivery of the services you need and request
  - purpose: Appointment delivery
    text: to retrieve and display AIVA appointment information to authorized dealership personnel within their CDK/ADP workflows
  - purpose: Authentication and access control
    text: to authenticate users and maintain authenticated sessions with TruVideo services
  residency:
  - region: United States
    text: information processed by the Extension is stored and processed on infrastructure located in the United States
  retention:
  - period: null
    scope: AIVA Extension data
    text: Information is retained in accordance with TruVideo’s Data Management Policy and applicable contractual obligations with our dealership customers.
  rights:
  - right: Access
    text: 'Access: Request a copy of the personal information we hold about you.'
  - right: Correction
    text: 'Correction: Request correction of inaccurate personal information.'
  - right: Deletion
    text: 'Deletion: Request deletion of personal information, subject to legal and contractual retention obligations.'
  role:
    text: 'Data Controller: TruVideo, Inc.'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: TruVideo is not in the business of selling or renting your information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Please be aware that Personal Information and Content submitted to TruVideo will be transferred to a data center in the United States.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TruVideo
provenance_date: '2026-11-10'
provider_name: TruVideo
provider_slug: truvideo
slug: truvideo-privacy-policy
source_date: '2026-11-10'
source_filename: truvideo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://truvideo.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TruVideo\naid: truvideo\nurl: https://truvideo.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Data Controller: TruVideo, Inc.'\ndata_categories:\n- category: contact\n  text: Voluntarily provided information which may include your name, address, email address, billing and/or credit\n    card information etc.\n- category: identifying\n  text: Authentication tokens (JSON Web Tokens, including access tokens and refresh tokens) issued by TruVideo’s\n    authentication service to maintain your authenticated session.\n- category: device\n  text: We may also gather information\
  \ about the type of browser you are using, IP address or type of operating\n    system\n- category: behavioral\n  text: Information automatically collected when visiting our application, which may include cookies, third party\n    tracking technologies and server logs.\npurposes:\n- purpose: Service delivery and support\n  text: to ensure delivery of the services you need and request\n- purpose: Appointment delivery\n  text: to retrieve and display AIVA appointment information to authorized dealership personnel within their CDK/ADP\n    workflows\n- purpose: Authentication and access control\n  text: to authenticate users and maintain authenticated sessions with TruVideo services\nretention:\n- scope: AIVA Extension data\n  period: null\n  text: Information is retained in accordance with TruVideo’s Data Management Policy and applicable contractual\n    obligations with our dealership customers.\nresidency:\n- region: United States\n  text: information processed by the Extension is stored\
  \ and processed on infrastructure located in the United States\ntransfers:\n- mechanism: other\n  text: Please be aware that Personal Information and Content submitted to TruVideo will be transferred to a data\n    center in the United States.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to security@truvideo.com\n  text: You may request deletion of your data by contacting security@truvideo.com.\nrights:\n- right: Access\n  text: 'Access: Request a copy of the personal information we hold about you.'\n- right: Correction\n  text: 'Correction: Request correction of inaccurate personal information.'\n- right: Deletion\n  text: 'Deletion: Request deletion of personal information, subject to legal and contractual retention obligations.'\nsale_or_sharing:\n  stance: prohibited\n  text: TruVideo is not in the business of selling or renting your information.\n"
source_yaml_url: https://artifacts.apis.io/truvideo/privacy/truvideo-privacy-policy.yml
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
summary_line: 16 quoted statements, read from TruVideo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Commerce
- Video
- Messaging
- Automotive
- Communications
- SDK
- Video Intelligence
---
