---
api_specs:
- filename: innago-expenses-api-openapi.yml
  format: yaml
  label: Innago Expenses API
  slug: innago-expenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-expenses-api-openapi.yml
- filename: innago-external-references-api-openapi.yml
  format: yaml
  label: Innago External References API
  slug: innago-external-references-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-external-references-api-openapi.yml
- filename: innago-health-api-openapi.yml
  format: yaml
  label: Innago Health API
  slug: innago-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-health-api-openapi.yml
- filename: innago-invoices-api-openapi.yml
  format: yaml
  label: Innago Invoices API
  slug: innago-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-invoices-api-openapi.yml
- filename: innago-leases-api-openapi.yml
  format: yaml
  label: Innago Leases API
  slug: innago-leases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-leases-api-openapi.yml
- filename: innago-maintenance-api-openapi.yml
  format: yaml
  label: Innago Maintenance API
  slug: innago-maintenance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-maintenance-api-openapi.yml
- filename: innago-payments-api-openapi.yml
  format: yaml
  label: Innago Payments API
  slug: innago-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-payments-api-openapi.yml
- filename: innago-properties-api-openapi.yml
  format: yaml
  label: Innago Properties API
  slug: innago-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-properties-api-openapi.yml
- filename: innago-tenants-api-openapi.yml
  format: yaml
  label: Innago Tenants API
  slug: innago-tenants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/innago/openapi/innago-tenants-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, date of birth, e-mail address, physical address, business name, business address, business title, phone number
  - category: financial
    text: your bank account and routing numbers when collecting or delivering payment
  - category: location
    text: we may collect your precise location data
  - category: device
    text: hardware models and IDs, device type, operating system version
  - category: behavioral
    text: advertising that you click on
  - category: communication
    text: we may receive call data, including the date and time of the call or SMS message, the parties phone numbers, and the content of the SMS message
  - category: identifying
    text: we may also collect your social security number and your birth date
  deletion:
    route: email support@innago.com
    text: If you wish us to delete your account, please email us at support@innago.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate and provide services
    text: Operate and provide our Services
  - purpose: payments
    text: To facilitate payments to and from your bank account in coordination with our secure third party payment service provider
  - purpose: analytics and improvement
    text: Analyze, improve and manage our Services and operations
  - purpose: marketing
    text: Send you communications we think will be of interest to you, including information about our services, products, promotions, news, and events of Innago
  - purpose: fraud and security
    text: Protect, investigate, and deter against fraudulent, unauthorized use or illegal activity
  residency:
  - region: United States
    text: we may send and store your personal information outside of the country where you reside or are located, including to the United States
  retention:
  - period: at least 1 year
    scope: account information
    text: Following termination or deactivation of your account, we will retain information for at least 1 year
  - period: null
    scope: active accounts
    text: Unless you request that we delete certain information, we retain the information we collect for as long as your account is active or as needed to provide you services.
  rights:
  - right: access
    text: Right to Access Your Personal Data. You have the right to access information held about you
  - right: correction
    text: Right of Correction or Completion of Your Personal Data.
  - right: erasure
    text: Right of Erasure or Deletion of Your Personal Data.
  - right: objection or restriction
    text: Right to Object to or Restrict Processing of Your Personal Data.
  - right: portability
    text: Right to Data Portability or Transfer of Your Personal Data.
  - right: withdraw consent
    text: Right to Withdrawal of Consent.
  - right: complain
    text: Right to Complain. If you’re based in the EU, you can file a complaint with the supervisory authority in your Member State.
  role:
    text: The Data Controller for Innago is Innago, LLC
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information. We do not share personal information or cross context behavioral advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We are committed to protecting the privacy and confidentiality of personal information when it is transferred.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Innago
provenance_date: '2026-11-09'
provider_name: Innago
provider_slug: innago
slug: innago-privacy-policy
source_date: '2026-11-09'
source_filename: innago-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://auth.innago.com/privacypolicy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Innago\naid: innago\nurl: https://auth.innago.com/privacypolicy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The Data Controller for Innago is Innago, LLC\ndata_categories:\n- category: identifying\n  text: name, date of birth, e-mail address, physical address, business name, business address, business title,\n    phone number\n- category: financial\n  text: your bank account and routing numbers when collecting or delivering payment\n- category: location\n  text: we may collect your precise location data\n- category: device\n  text: hardware models and IDs, device type, operating system\
  \ version\n- category: behavioral\n  text: advertising that you click on\n- category: communication\n  text: we may receive call data, including the date and time of the call or SMS message, the parties phone numbers,\n    and the content of the SMS message\n- category: identifying\n  text: we may also collect your social security number and your birth date\npurposes:\n- purpose: operate and provide services\n  text: Operate and provide our Services\n- purpose: payments\n  text: To facilitate payments to and from your bank account in coordination with our secure third party payment\n    service provider\n- purpose: analytics and improvement\n  text: Analyze, improve and manage our Services and operations\n- purpose: marketing\n  text: Send you communications we think will be of interest to you, including information about our services, products,\n    promotions, news, and events of Innago\n- purpose: fraud and security\n  text: Protect, investigate, and deter against fraudulent, unauthorized\
  \ use or illegal activity\nretention:\n- scope: account information\n  period: at least 1 year\n  text: Following termination or deactivation of your account, we will retain information for at least 1 year\n- scope: active accounts\n  period: null\n  text: Unless you request that we delete certain information, we retain the information we collect for as long\n    as your account is active or as needed to provide you services.\nresidency:\n- region: United States\n  text: we may send and store your personal information outside of the country where you reside or are located,\n    including to the United States\ntransfers:\n- mechanism: other\n  text: We are committed to protecting the privacy and confidentiality of personal information when it is transferred.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@innago.com\n  text: If you wish us to delete your account, please email us at support@innago.com\nrights:\n\
  - right: access\n  text: Right to Access Your Personal Data. You have the right to access information held about you\n- right: correction\n  text: Right of Correction or Completion of Your Personal Data.\n- right: erasure\n  text: Right of Erasure or Deletion of Your Personal Data.\n- right: objection or restriction\n  text: Right to Object to or Restrict Processing of Your Personal Data.\n- right: portability\n  text: Right to Data Portability or Transfer of Your Personal Data.\n- right: withdraw consent\n  text: Right to Withdrawal of Consent.\n- right: complain\n  text: Right to Complain. If you’re based in the EU, you can file a complaint with the supervisory authority in\n    your Member State.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information. We do not share personal information or cross context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/innago/privacy/innago-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Innago's own page on 2026-11-09.
synthetic: false
tags:
- Property Management
- Real Estate
- Leases
- Rent Collection
- Maintenance
- Tenants
- Invoicing
- Payments
---
