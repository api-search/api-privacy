---
api_specs:
- filename: monacloud-apps-api-openapi.yml
  format: yaml
  label: The MONA Group Apps API
  slug: monacloud-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monacloud/openapi/monacloud-apps-api-openapi.yml
- filename: monacloud-auth-api-openapi.yml
  format: yaml
  label: The MONA Group Auth API
  slug: monacloud-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monacloud/openapi/monacloud-auth-api-openapi.yml
- filename: monacloud-billing-api-openapi.yml
  format: yaml
  label: The MONA Group Billing API
  slug: monacloud-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monacloud/openapi/monacloud-billing-api-openapi.yml
- filename: monacloud-databases-api-openapi.yml
  format: yaml
  label: The MONA Group Databases API
  slug: monacloud-databases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monacloud/openapi/monacloud-databases-api-openapi.yml
- filename: monacloud-jobs-api-openapi.yml
  format: yaml
  label: The MONA Group Jobs API
  slug: monacloud-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monacloud/openapi/monacloud-jobs-api-openapi.yml
- filename: monacloud-lxc-api-openapi.yml
  format: yaml
  label: The MONA Group Lxc API
  slug: monacloud-lxc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monacloud/openapi/monacloud-lxc-api-openapi.yml
- filename: monacloud-prices-api-openapi.yml
  format: yaml
  label: The MONA Group Prices API
  slug: monacloud-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monacloud/openapi/monacloud-prices-api-openapi.yml
- filename: monacloud-sandbox-api-openapi.yml
  format: yaml
  label: The MONA Group Sandbox API
  slug: monacloud-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monacloud/openapi/monacloud-sandbox-api-openapi.yml
- filename: monacloud-services-api-openapi.yml
  format: yaml
  label: The MONA Group Services API
  slug: monacloud-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/monacloud/openapi/monacloud-services-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account via MONA Pass, we store your email address and display name.
  - category: financial
    text: The data includes the deposit amount, time of execution, transfer note, and bank transaction code.
  - category: device
    text: Technically, the system logs your IP address.
  - category: communication
    text: The content of emails you send via the API is also processed.
  - category: behavioral
    text: Build logs and application deployment processes are also recorded.
  deletion:
    route: Request account deletion
    text: You also have the right to request us to delete your account when you no longer need the service.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate services
    text: We primarily use your data to provide and operate services within the MONA Cloud ecosystem.
  - purpose: Security and fraud prevention
    text: We use data to ensure system security and prevent fraudulent activities.
  - purpose: Payment confirmation
    text: Payment data is used to automatically confirm deposit transactions.
  - purpose: Technical support
    text: Technical data helps us detect software errors.
  residency:
  - region: Vietnam
    text: MONA Cloud servers are located in secure data centers in Vietnam.
  - region: Hong Kong, Singapore, Australia, United States
    text: These regions include Hong Kong, Singapore, Australia, or the United States.
  retention:
  - period: until you request account deletion
    scope: Account data
    text: Your account data is kept on the system until you request account deletion.
  - period: 10 years
    scope: Payment receipts and VAT invoices
    text: payment receipts and VAT invoices will be retained for 10 years.
  - period: 90 days
    scope: Technical system logs
    text: Technical system logs are stored for a maximum period of 90 days.
  - period: 24 hours
    scope: Temporary sandbox data
    text: For data in temporary sandbox environments, it will be automatically deleted after 24 hours.
  rights:
  - right: Access and modify personal data
    text: You have the right to access the system to view and modify your personal data at any time.
  - right: Download information
    text: You can also download the information you have provided to us.
  - right: Withdraw marketing consent
    text: If you previously agreed to receive marketing messages, you have the right to withdraw this consent.
  role:
    text: The MONA Group acts as the data controller.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We strictly commit to never selling your data to any individual or organization.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: The MONA Group
provenance_date: '2026-11-10'
provider_name: The MONA Group
provider_slug: monacloud
slug: monacloud-privacy-policy
source_date: '2026-11-10'
source_filename: monacloud-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://monacloud.vn/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: The MONA Group\naid: monacloud\nurl: https://monacloud.vn/en/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The MONA Group acts as the data controller.\ndata_categories:\n- category: identifying\n  text: When you create an account via MONA Pass, we store your email address and display name.\n- category: financial\n  text: The data includes the deposit amount, time of execution, transfer note, and bank transaction code.\n- category: device\n  text: Technically, the system logs your IP address.\n- category: communication\n  text: The content of emails you send via the API is also processed.\n\
  - category: behavioral\n  text: Build logs and application deployment processes are also recorded.\npurposes:\n- purpose: Provide and operate services\n  text: We primarily use your data to provide and operate services within the MONA Cloud ecosystem.\n- purpose: Security and fraud prevention\n  text: We use data to ensure system security and prevent fraudulent activities.\n- purpose: Payment confirmation\n  text: Payment data is used to automatically confirm deposit transactions.\n- purpose: Technical support\n  text: Technical data helps us detect software errors.\nretention:\n- scope: Account data\n  period: until you request account deletion\n  text: Your account data is kept on the system until you request account deletion.\n- scope: Payment receipts and VAT invoices\n  period: 10 years\n  text: payment receipts and VAT invoices will be retained for 10 years.\n- scope: Technical system logs\n  period: 90 days\n  text: Technical system logs are stored for a maximum period of 90 days.\n\
  - scope: Temporary sandbox data\n  period: 24 hours\n  text: For data in temporary sandbox environments, it will be automatically deleted after 24 hours.\nresidency:\n- region: Vietnam\n  text: MONA Cloud servers are located in secure data centers in Vietnam.\n- region: Hong Kong, Singapore, Australia, United States\n  text: These regions include Hong Kong, Singapore, Australia, or the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request account deletion\n  text: You also have the right to request us to delete your account when you no longer need the service.\nrights:\n- right: Access and modify personal data\n  text: You have the right to access the system to view and modify your personal data at any time.\n- right: Download information\n  text: You can also download the information you have provided to us.\n- right: Withdraw marketing consent\n  text: If you previously agreed to receive\
  \ marketing messages, you have the right to withdraw this consent.\nsale_or_sharing:\n  stance: prohibited\n  text: We strictly commit to never selling your data to any individual or organization.\n"
source_yaml_url: https://artifacts.apis.io/monacloud/privacy/monacloud-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from The MONA Group's own page on 2026-11-10.
synthetic: false
tags:
- Cloud
- Hosting
- Developer Tools
- Vietnamese
- Artificial Intelligence
---
