---
api_specs:
- filename: wufoo-webhooks-asyncapi.yml
  format: yaml
  label: Wufoo Webhooks
  slug: wufoo-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/wufoo/asyncapi/wufoo-webhooks-asyncapi.yml
- filename: wufoo-comments-api-openapi.yml
  format: yaml
  label: Wufoo Comments API
  slug: wufoo-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wufoo/openapi/wufoo-comments-api-openapi.yml
- filename: wufoo-entries-api-openapi.yml
  format: yaml
  label: Wufoo Entries API
  slug: wufoo-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wufoo/openapi/wufoo-entries-api-openapi.yml
- filename: wufoo-fields-api-openapi.yml
  format: yaml
  label: Wufoo Fields API
  slug: wufoo-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wufoo/openapi/wufoo-fields-api-openapi.yml
- filename: wufoo-forms-api-openapi.yml
  format: yaml
  label: Wufoo Forms API
  slug: wufoo-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wufoo/openapi/wufoo-forms-api-openapi.yml
- filename: wufoo-login-api-openapi.yml
  format: yaml
  label: Wufoo Login API
  slug: wufoo-login-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wufoo/openapi/wufoo-login-api-openapi.yml
- filename: wufoo-reports-api-openapi.yml
  format: yaml
  label: Wufoo Reports API
  slug: wufoo-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wufoo/openapi/wufoo-reports-api-openapi.yml
- filename: wufoo-users-api-openapi.yml
  format: yaml
  label: Wufoo Users API
  slug: wufoo-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wufoo/openapi/wufoo-users-api-openapi.yml
- filename: wufoo-webhooks-api-openapi.yml
  format: yaml
  label: Wufoo Webhooks API
  slug: wufoo-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wufoo/openapi/wufoo-webhooks-api-openapi.yml
- filename: wufoo-widgets-api-openapi.yml
  format: yaml
  label: Wufoo Widgets API
  slug: wufoo-widgets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wufoo/openapi/wufoo-widgets-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: 'You might provide us with your contact information (for example: name or email address)'
  - category: financial
    text: a name, address, email address and financial information corresponding to your selected method of payment
  - category: device
    text: Device data mainly means your IP address, operating system version, device type, device ID/MAC address, system and performance information, browser type
  - category: location
    text: We also infer your geographic location based on your IP address.
  - category: behavioral
    text: We collect usage information about you whenever you interact with our websites and services.
  - category: communication
    text: We also record the content of Customer Support, Customer Success, and Sales calls.
  deletion:
    route: Cancel Wufoo account from account management page
    text: You can cancel your Wufoo account at any time through your account management page.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service troubleshooting and improvement
    text: We use device data both to troubleshoot problems with our service and to make improvements to it.
  - purpose: model training
    text: we use de-identified response data to train our models
  - purpose: marketing
    text: We use contact information to respond to your inquiries, send you information as part of the services, and send you marketing information.
  residency:
  - region: United States
    text: Your information and data may be processed in and transferred or disclosed in the United States
  retention:
  - period: up to 90 days
    scope: Wufoo backup and archival copies after cancellation
    text: we may for a time retain residual information in our backup and/or archival copies of our database for up to 90 days.
  - period: null
    scope: Creator account data
    text: we generally do not delete the data in your account as long as your account is active
  rights:
  - right: access
    text: you are entitled to a copy of all Personal Data which we hold in relation to you
  - right: correct or delete
    text: to correct, update or delete that information
  - right: restrict or object
    text: You also may be entitled to request that we restrict how we use your data or object to some aspect of our treatment of your data.
  role:
    text: that Creator is the controller of your data, and SurveyMonkey is the processor of that data.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We will also not sell your form data to anyone.
  subprocessors:
    text: You can find more information in our Subprocessor Statement
    url: null
  transfers:
  - mechanism: DPF
    text: SurveyMonkey Inc. has self-certified its compliance under the EU-U.S. Data Privacy Framework, the UK Extension and the Swiss-U.S. DPF Principles.
  - mechanism: SCC
    text: for instance by entering into the appropriate back-to-back agreements with standard contractual clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Wufoo
provenance_date: '2026-11-10'
provider_name: Wufoo
provider_slug: wufoo
slug: wufoo-privacy-policy
source_date: '2026-11-10'
source_filename: wufoo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.surveymonkey.com/mp/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Wufoo\naid: wufoo\nurl: https://www.surveymonkey.com/mp/legal/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: that Creator is the controller of your data, and SurveyMonkey is the processor of that data.\ndata_categories:\n- category: contact\n  text: 'You might provide us with your contact information (for example: name or email address)'\n- category: financial\n  text: a name, address, email address and financial information corresponding to your selected method of payment\n- category: device\n  text: Device data mainly means your IP address, operating system version, device type, device\
  \ ID/MAC address,\n    system and performance information, browser type\n- category: location\n  text: We also infer your geographic location based on your IP address.\n- category: behavioral\n  text: We collect usage information about you whenever you interact with our websites and services.\n- category: communication\n  text: We also record the content of Customer Support, Customer Success, and Sales calls.\npurposes:\n- purpose: service troubleshooting and improvement\n  text: We use device data both to troubleshoot problems with our service and to make improvements to it.\n- purpose: model training\n  text: we use de-identified response data to train our models\n- purpose: marketing\n  text: We use contact information to respond to your inquiries, send you information as part of the services, and\n    send you marketing information.\nretention:\n- scope: Wufoo backup and archival copies after cancellation\n  period: up to 90 days\n  text: we may for a time retain residual information\
  \ in our backup and/or archival copies of our database for up\n    to 90 days.\n- scope: Creator account data\n  period: null\n  text: we generally do not delete the data in your account as long as your account is active\nresidency:\n- region: United States\n  text: Your information and data may be processed in and transferred or disclosed in the United States\ntransfers:\n- mechanism: DPF\n  text: SurveyMonkey Inc. has self-certified its compliance under the EU-U.S. Data Privacy Framework, the UK Extension\n    and the Swiss-U.S. DPF Principles.\n- mechanism: SCC\n  text: for instance by entering into the appropriate back-to-back agreements with standard contractual clauses\nsubprocessors:\n  url: null\n  text: You can find more information in our Subprocessor Statement\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Cancel Wufoo account from account management page\n  text: You can cancel your Wufoo account at any time through your account management page.\n\
  rights:\n- right: access\n  text: you are entitled to a copy of all Personal Data which we hold in relation to you\n- right: correct or delete\n  text: to correct, update or delete that information\n- right: restrict or object\n  text: You also may be entitled to request that we restrict how we use your data or object to some aspect of our\n    treatment of your data.\nsale_or_sharing:\n  stance: prohibited\n  text: We will also not sell your form data to anyone.\n"
source_yaml_url: https://artifacts.apis.io/wufoo/privacy/wufoo-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Wufoo's own page on 2026-11-10.
synthetic: false
tags:
- Forms
- Form Builder
- Surveys
- Data Collection
- Webhook
- Payments
- SurveyMonkey
---
