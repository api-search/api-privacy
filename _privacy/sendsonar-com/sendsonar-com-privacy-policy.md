---
api_specs:
- filename: sendsonar-com-accounts-api-openapi.yml
  format: yaml
  label: Sonar Accounts API
  slug: sendsonar-com-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendsonar-com/openapi/sendsonar-com-accounts-api-openapi.yml
- filename: sendsonar-com-campaigns-api-openapi.yml
  format: yaml
  label: Sonar Campaigns API
  slug: sendsonar-com-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendsonar-com/openapi/sendsonar-com-campaigns-api-openapi.yml
- filename: sendsonar-com-conversations-api-openapi.yml
  format: yaml
  label: Sonar Conversations API
  slug: sendsonar-com-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendsonar-com/openapi/sendsonar-com-conversations-api-openapi.yml
- filename: sendsonar-com-customers-api-openapi.yml
  format: yaml
  label: Sonar Customers API
  slug: sendsonar-com-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendsonar-com/openapi/sendsonar-com-customers-api-openapi.yml
- filename: sendsonar-com-events-api-openapi.yml
  format: yaml
  label: Sonar Events API
  slug: sendsonar-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendsonar-com/openapi/sendsonar-com-events-api-openapi.yml
- filename: sendsonar-com-messages-api-openapi.yml
  format: yaml
  label: Sonar Messages API
  slug: sendsonar-com-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendsonar-com/openapi/sendsonar-com-messages-api-openapi.yml
- filename: sendsonar-com-phone-numbers-api-openapi.yml
  format: yaml
  label: Sonar Phone Numbers API
  slug: sendsonar-com-phone-numbers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendsonar-com/openapi/sendsonar-com-phone-numbers-api-openapi.yml
- filename: sendsonar-com-roles-api-openapi.yml
  format: yaml
  label: Sonar Roles API
  slug: sendsonar-com-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendsonar-com/openapi/sendsonar-com-roles-api-openapi.yml
- filename: sendsonar-com-users-api-openapi.yml
  format: yaml
  label: Sonar Users API
  slug: sendsonar-com-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendsonar-com/openapi/sendsonar-com-users-api-openapi.yml
- filename: sendsonar-com-webhooks-api-openapi.yml
  format: yaml
  label: Sonar Webhooks API
  slug: sendsonar-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sendsonar-com/openapi/sendsonar-com-webhooks-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Full name
  - category: contact
    text: Email address
  - category: contact
    text: Phone Number with country code
  - category: financial
    text: Credit or debit card expiration date
  - category: device
    text: IP Address of the computer you used to access our website and/or the Services
  - category: behavioral
    text: Views and interactions with pages/features on the Sonar Services
  - category: communication
    text: Messages you send/receive within the Sonar Services
  - category: health
    text: Sensitive information includes information or an opinion (that is also personal information) about an individual’s health
  deletion:
    route: contact@sendsonar.com
    text: If requested, we will delete your personal data unless we are legally allowed or required to keep certain personal information.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide access to the Sonar Service
    text: To provide access to the Sonar Service
  - purpose: fraud detection
    text: To detect and prevent fraudulent sign-ups and activity
  - purpose: usage analytics
    text: To track your usage of the Sonar website and/or Services to understand how and which features are being used
  retention:
  - period: only as long as necessary
    scope: general personal information
    text: Sonar keeps your personal information only as long as necessary to provide you with the best service and for legitimate business purposes.
  - period: as long as you are a user of the Services
    scope: personal data such as full name
    text: We keep some of your personal data for as long as you are a user of the Services, such as your full name.
  rights:
  - right: access
    text: You have the right to access your personal data in Sonar
  - right: rectification
    text: You have the right to correct your personal data in Sonar
  - right: erasure
    text: You have the right to request that we delete any personal information pertaining to you.
  - right: data portability
    text: You have the right to request a copy of your Personal Information in a readable and useable format.
  - right: opt-out of sale or sharing
    text: You have the right to opt-out of the sale of Personal Information and/or the sharing of Personal Information for cross-context behavioral or targeted advertising purposes
  role:
    text: If we store your Personal Information as a service provider and/or processor for one or more of our client(s), we will provide you with their information so that you can submit your request to them directly.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not rent or sell your personal information to any third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Sonar
provenance_date: '2026-11-10'
provider_name: Sonar
provider_slug: sendsonar-com
slug: sendsonar-com-privacy-policy
source_date: '2026-11-10'
source_filename: sendsonar-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://sendsonar.com/privacy-policy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Sonar\naid: sendsonar-com\nurl: https://sendsonar.com/privacy-policy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: If we store your Personal Information as a service provider and/or processor for one or more of our client(s),\n    we will provide you with their information so that you can submit your request to them directly.\ndata_categories:\n- category: identifying\n  text: Full name\n- category: contact\n  text: Email address\n- category: contact\n  text: Phone Number with country code\n- category: financial\n  text: Credit or debit card expiration date\n- category: device\n  text: IP\
  \ Address of the computer you used to access our website and/or the Services\n- category: behavioral\n  text: Views and interactions with pages/features on the Sonar Services\n- category: communication\n  text: Messages you send/receive within the Sonar Services\n- category: health\n  text: Sensitive information includes information or an opinion (that is also personal information) about an individual’s\n    health\npurposes:\n- purpose: provide access to the Sonar Service\n  text: To provide access to the Sonar Service\n- purpose: fraud detection\n  text: To detect and prevent fraudulent sign-ups and activity\n- purpose: usage analytics\n  text: To track your usage of the Sonar website and/or Services to understand how and which features are being\n    used\nretention:\n- scope: general personal information\n  period: only as long as necessary\n  text: Sonar keeps your personal information only as long as necessary to provide you with the best service and\n    for legitimate business\
  \ purposes.\n- scope: personal data such as full name\n  period: as long as you are a user of the Services\n  text: We keep some of your personal data for as long as you are a user of the Services, such as your full name.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact@sendsonar.com\n  text: If requested, we will delete your personal data unless we are legally allowed or required to keep certain\n    personal information.\nrights:\n- right: access\n  text: You have the right to access your personal data in Sonar\n- right: rectification\n  text: You have the right to correct your personal data in Sonar\n- right: erasure\n  text: You have the right to request that we delete any personal information pertaining to you.\n- right: data portability\n  text: You have the right to request a copy of your Personal Information in a readable and useable format.\n- right: opt-out of sale or sharing\n\
  \  text: You have the right to opt-out of the sale of Personal Information and/or the sharing of Personal Information\n    for cross-context behavioral or targeted advertising purposes\nsale_or_sharing:\n  stance: prohibited\n  text: We do not rent or sell your personal information to any third parties.\n"
source_yaml_url: https://artifacts.apis.io/sendsonar-com/privacy/sendsonar-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Sonar's own page on 2026-11-10.
synthetic: false
tags:
- Company
- SMS
- Messaging
- Sales
- Automation
---
