---
api_specs:
- filename: open-financial-accounts-api-openapi.yml
  format: yaml
  label: Open (open.money) Accounts API
  slug: open-financial-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/open-financial/openapi/open-financial-accounts-api-openapi.yml
- filename: open-financial-constants-api-openapi.yml
  format: yaml
  label: Open (open.money) Constants API
  slug: open-financial-constants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/open-financial/openapi/open-financial-constants-api-openapi.yml
- filename: open-financial-events-api-openapi.yml
  format: yaml
  label: Open (open.money) Events API
  slug: open-financial-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/open-financial/openapi/open-financial-events-api-openapi.yml
- filename: open-financial-icp-api-openapi.yml
  format: yaml
  label: Open (open.money) Icp API
  slug: open-financial-icp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/open-financial/openapi/open-financial-icp-api-openapi.yml
- filename: open-financial-kycs-api-openapi.yml
  format: yaml
  label: Open (open.money) Kycs API
  slug: open-financial-kycs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/open-financial/openapi/open-financial-kycs-api-openapi.yml
- filename: open-financial-pg-api-openapi.yml
  format: yaml
  label: Open (open.money) Pg API
  slug: open-financial-pg-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/open-financial/openapi/open-financial-pg-api-openapi.yml
- filename: open-financial-pg-settlements-api-openapi.yml
  format: yaml
  label: Open (open.money) Pg Settlements API
  slug: open-financial-pg-settlements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/open-financial/openapi/open-financial-pg-settlements-api-openapi.yml
- filename: open-financial-refund-api-openapi.yml
  format: yaml
  label: Open (open.money) Refund API
  slug: open-financial-refund-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/open-financial/openapi/open-financial-refund-api-openapi.yml
- filename: open-financial-transfers-api-openapi.yml
  format: yaml
  label: Open (open.money) Transfers API
  slug: open-financial-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/open-financial/openapi/open-financial-transfers-api-openapi.yml
- filename: open-financial-verifications-api-openapi.yml
  format: yaml
  label: Open (open.money) Verifications API
  slug: open-financial-verifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/open-financial/openapi/open-financial-verifications-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: Government-issued identifiers, including PAN and GST information;
  - category: contact
    text: Contact information (e.g., name, address, telephone, and email address).
  - category: financial
    text: Financial information, including bank account details, billing information, tax information and payroll information (as applicable);
  - category: demographic
    text: Personal information like date of birth, age, marital status, birthplace, nationality, mother tongue.
  - category: location
    text: the Platform accesses your Device location to validate banking transactions initiated using the Platform.
  - category: device
    text: Permission to access the Device's camera
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Determine eligibility and enable products/services
    text: In order to determine Your eligibility and enable the products/services offered on the Platform for You
  - purpose: Marketing and digital purposes
    text: We further process Your Personal Information for marketing and any other digital purpose to enhance Your user experience
  - purpose: Fraud prevention
    text: As a security measure and means to tackle fraud, the Platform accesses your Device location to validate banking transactions initiated using the Platform.
  - purpose: Legal compliance
    text: to comply with Our legal obligations
  retention:
  - period: null
    scope: Active account
    text: We will retain your information for as long as Your account is active or as needed to provide the Platform services.
  - period: null
    scope: After account cancellation
    text: We may retain Your information after You cancel/ deactivate/ unsubscribe Your account with Us for such period as may be required to ensure compliance with applicable laws.
  rights:
  - right: Withdraw consent
    text: You have the right to withdraw your consent at any time in writing by sending an e-mail to us at letstalk@open.money
  - right: Access, review, modify or correct
    text: You may write to us at letstalk@open.money to access, review, modify or correct your personal data or information
  role:
    text: We handle data in our own right and also for and on behalf of the Users.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Open (open.money)
provenance_date: '2026-11-10'
provider_name: Open (open.money)
provider_slug: open-financial
slug: open-financial-privacy-policy
source_date: '2026-11-10'
source_filename: open-financial-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://open.money/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Open (open.money)\naid: open-financial\nurl: https://open.money/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We handle data in our own right and also for and on behalf of the Users.\ndata_categories:\n- category: identifying\n  text: Government-issued identifiers, including PAN and GST information;\n- category: contact\n  text: Contact information (e.g., name, address, telephone, and email address).\n- category: financial\n  text: Financial information, including bank account details, billing information, tax information and payroll\n    information (as applicable);\n- category: demographic\n\
  \  text: Personal information like date of birth, age, marital status, birthplace, nationality, mother tongue.\n- category: location\n  text: the Platform accesses your Device location to validate banking transactions initiated using the Platform.\n- category: device\n  text: Permission to access the Device's camera\npurposes:\n- purpose: Determine eligibility and enable products/services\n  text: In order to determine Your eligibility and enable the products/services offered on the Platform for You\n- purpose: Marketing and digital purposes\n  text: We further process Your Personal Information for marketing and any other digital purpose to enhance Your\n    user experience\n- purpose: Fraud prevention\n  text: As a security measure and means to tackle fraud, the Platform accesses your Device location to validate\n    banking transactions initiated using the Platform.\n- purpose: Legal compliance\n  text: to comply with Our legal obligations\nretention:\n- scope: Active account\n  period:\
  \ null\n  text: We will retain your information for as long as Your account is active or as needed to provide the Platform\n    services.\n- scope: After account cancellation\n  period: null\n  text: We may retain Your information after You cancel/ deactivate/ unsubscribe Your account with Us for such period\n    as may be required to ensure compliance with applicable laws.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Withdraw consent\n  text: You have the right to withdraw your consent at any time in writing by sending an e-mail to us at letstalk@open.money\n- right: Access, review, modify or correct\n  text: You may write to us at letstalk@open.money to access, review, modify or correct your personal data or information\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/open-financial/privacy/open-financial-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- rights
summary_line: 15 quoted statements, read from Open (open.money)'s own page on 2026-11-10.
synthetic: false
tags:
- Connected Banking
- Neobank
- Small Business
- Embedded Finance
- Banking as a Service
- Payments
- Payouts
- UPI
- Accounting
- Payroll
- Expense Management
- India
- Fintech
---
