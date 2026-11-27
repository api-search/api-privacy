---
api_specs:
- filename: hustle-access-token-api-openapi.yml
  format: yaml
  label: Hustle Access Token API
  slug: hustle-access-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-access-token-api-openapi.yml
- filename: hustle-agents-api-openapi.yml
  format: yaml
  label: Hustle Agents API
  slug: hustle-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-agents-api-openapi.yml
- filename: hustle-custom-fields-api-openapi.yml
  format: yaml
  label: Hustle Custom Fields API
  slug: hustle-custom-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-custom-fields-api-openapi.yml
- filename: hustle-groups-api-openapi.yml
  format: yaml
  label: Hustle Groups API
  slug: hustle-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-groups-api-openapi.yml
- filename: hustle-integrations-api-openapi.yml
  format: yaml
  label: Hustle Integrations API
  slug: hustle-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-integrations-api-openapi.yml
- filename: hustle-leads-api-openapi.yml
  format: yaml
  label: Hustle Leads API
  slug: hustle-leads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-leads-api-openapi.yml
- filename: hustle-messages-api-openapi.yml
  format: yaml
  label: Hustle Messages API
  slug: hustle-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-messages-api-openapi.yml
- filename: hustle-organizations-api-openapi.yml
  format: yaml
  label: Hustle Organizations API
  slug: hustle-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-organizations-api-openapi.yml
- filename: hustle-tags-api-openapi.yml
  format: yaml
  label: Hustle Tags API
  slug: hustle-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-tags-api-openapi.yml
- filename: hustle-webhooks-api-openapi.yml
  format: yaml
  label: Hustle Webhooks API
  slug: hustle-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hustle/openapi/hustle-webhooks-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: the Recipient’s first name, last name, and telephone number
  - category: identifying
    text: name, email address, mobile phone number, your job title and company
  - category: device
    text: the equipment used to access our Service (including device ID)
  - category: location
    text: Details of Customer’s visits to and use of our Service, including traffic data, location data, logs
  - category: communication
    text: the content of messages Customers send and receive, message timestamps, message length, reply rates
  - category: behavioral
    text: information about Customers’ online activities over time and across third-party websites
  deletion:
    route: Customer contact via email; Recipients must contact the Hustle Customer
    text: We cannot delete a Customer’s personal information except by also deleting the Customer’s user account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing and improving the Service
    text: Providing, developing, customizing, and improving our Service and the services provided to Customers.
  - purpose: Data analysis and fraud prevention
    text: We use this Text Message Data for our internal purposes such as data analysis, fraud prevention, developing and improving our Service, and identifying usage trends.
  - purpose: Marketing contact
    text: We may also use Customers’ information to contact them about our other products and services that may be of interest to them.
  residency:
  - region: United States
    text: Hustle stores all data in the United States of America.
  retention:
  - period: null
    scope: Personal information
    text: We will retain a Customer’s personal information only for as long as reasonably necessary to provide our Service to such Customer, to meet legal and accounting obligations, and for the purposes described in this Policy.
  - period: Backups are preserved until a Customer requests the data be deleted
    scope: Backups
    text: Backups are preserved until a Customer requests the data be deleted.
  rights:
  - right: Access and correction
    text: Customers can review and change their personal information by logging into our Service and visiting their account profile page.
  - right: Know and delete (CCPA)
    text: Consumers have the right to request that we delete any of their personal information that we collected from the consumer and retained, subject to certain exceptions
  - right: Opt-out of targeted advertising and sales (state laws)
    text: Opt-out of personal data processing for targeted advertising and sales.
  - right: Data portability
    text: Obtain data in a portable format.
  role:
    text: Hustle is a business-to-business service provider
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Hustle does not sell any personal information or provide any personal information to any third party for resale.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Hustle
provenance_date: '2026-11-09'
provider_name: Hustle
provider_slug: hustle
slug: hustle-privacy-policy
source_date: '2026-11-09'
source_filename: hustle-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hustle.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Hustle\naid: hustle\nurl: https://hustle.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Hustle is a business-to-business service provider\ndata_categories:\n- category: contact\n  text: the Recipient’s first name, last name, and telephone number\n- category: identifying\n  text: name, email address, mobile phone number, your job title and company\n- category: device\n  text: the equipment used to access our Service (including device ID)\n- category: location\n  text: Details of Customer’s visits to and use of our Service, including traffic data, location data, logs\n- category:\
  \ communication\n  text: the content of messages Customers send and receive, message timestamps, message length, reply rates\n- category: behavioral\n  text: information about Customers’ online activities over time and across third-party websites\npurposes:\n- purpose: Providing and improving the Service\n  text: Providing, developing, customizing, and improving our Service and the services provided to Customers.\n- purpose: Data analysis and fraud prevention\n  text: We use this Text Message Data for our internal purposes such as data analysis, fraud prevention, developing\n    and improving our Service, and identifying usage trends.\n- purpose: Marketing contact\n  text: We may also use Customers’ information to contact them about our other products and services that may be\n    of interest to them.\nretention:\n- scope: Personal information\n  period: null\n  text: We will retain a Customer’s personal information only for as long as reasonably necessary to provide our\n    Service to\
  \ such Customer, to meet legal and accounting obligations, and for the purposes described in this Policy.\n- scope: Backups\n  period: Backups are preserved until a Customer requests the data be deleted\n  text: Backups are preserved until a Customer requests the data be deleted.\nresidency:\n- region: United States\n  text: Hustle stores all data in the United States of America.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Customer contact via email; Recipients must contact the Hustle Customer\n  text: We cannot delete a Customer’s personal information except by also deleting the Customer’s user account.\nrights:\n- right: Access and correction\n  text: Customers can review and change their personal information by logging into our Service and visiting their\n    account profile page.\n- right: Know and delete (CCPA)\n  text: Consumers have the right to request that we delete any of their personal information\
  \ that we collected from\n    the consumer and retained, subject to certain exceptions\n- right: Opt-out of targeted advertising and sales (state laws)\n  text: Opt-out of personal data processing for targeted advertising and sales.\n- right: Data portability\n  text: Obtain data in a portable format.\nsale_or_sharing:\n  stance: prohibited\n  text: Hustle does not sell any personal information or provide any personal information to any third party for\n    resale.\n"
source_yaml_url: https://artifacts.apis.io/hustle/privacy/hustle-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Hustle's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise
- Messaging
- SMS
- Peer-to-Peer Texting
- Communications
- Marketing
- Civic Engagement
- Webhook
- OAuth
- Authentication
---
