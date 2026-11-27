---
api_specs:
- filename: tessie-driver-management-api-openapi.yml
  format: yaml
  label: Tessie Driver Management API
  slug: tessie-driver-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tessie/openapi/tessie-driver-management-api-openapi.yml
- filename: tessie-telemetry-configuration-api-openapi.yml
  format: yaml
  label: Tessie Telemetry Configuration API
  slug: tessie-telemetry-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tessie/openapi/tessie-telemetry-configuration-api-openapi.yml
- filename: tessie-vehicle-commands-api-openapi.yml
  format: yaml
  label: Tessie Vehicle Commands API
  slug: tessie-vehicle-commands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tessie/openapi/tessie-vehicle-commands-api-openapi.yml
- filename: tessie-vehicle-data-api-openapi.yml
  format: yaml
  label: Tessie Vehicle Data API
  slug: tessie-vehicle-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tessie/openapi/tessie-vehicle-data-api-openapi.yml
claim_count: 10
description: ''
doc:
  data_categories:
  - category: identifying
    text: Tessie collects Vehicle Identification Numbers (VINs) and your email address, for the sole purpose of providing you with an account.
  - category: location
    text: You agree to allow us to obtain your location for use within the app.
  deletion:
    route: account deletion request or visiting the privacy page
    text: Upon your request to delete your account, we will deactivate or delete your account and information from our active databases.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide account
    text: for the sole purpose of providing you with an account
  - purpose: fleet-level benchmarks
    text: Tessie may use aggregated vehicle data to generate fleet-level performance benchmarks, such as battery, driving and charging comparisons.
  - purpose: support requests
    text: When you contact Tessie for help, our support team may access relevant information associated with your account so we can resolve your request.
  retention:
  - period: null
    scope: personal information
    text: We will only keep your personal information for as long as it is necessary to provide you an account, unless a longer retention period is required or permitted by law (such as tax, accounting or other legal requirements).
  rights:
  - right: export
    text: You own all of your data and can view, use, export, or delete it at any time.
  - right: complain to supervisory authority
    text: If you are resident in the European Economic Area and you believe we are unlawfully processing your personal information, you also have the right to complain to your local data protection supervisory authority.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Tessie takes user privacy very seriously, and will never sell, rent, or share personal information with any third party, unless we are legally forced to share it.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Tessie
provenance_date: '2026-11-10'
provider_name: Tessie
provider_slug: tessie
slug: tessie-privacy-policy
source_date: '2026-11-10'
source_filename: tessie-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.tessie.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Tessie\naid: tessie\nurl: https://www.tessie.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Tessie collects Vehicle Identification Numbers (VINs) and your email address, for the sole purpose of providing\n    you with an account.\n- category: location\n  text: You agree to allow us to obtain your location for use within the app.\npurposes:\n- purpose: provide account\n  text: for the sole purpose of providing you with an account\n- purpose: fleet-level benchmarks\n  text: Tessie may use aggregated vehicle data to generate fleet-level\
  \ performance benchmarks, such as battery,\n    driving and charging comparisons.\n- purpose: support requests\n  text: When you contact Tessie for help, our support team may access relevant information associated with your\n    account so we can resolve your request.\nretention:\n- scope: personal information\n  period: null\n  text: We will only keep your personal information for as long as it is necessary to provide you an account, unless\n    a longer retention period is required or permitted by law (such as tax, accounting or other legal requirements).\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion request or visiting the privacy page\n  text: Upon your request to delete your account, we will deactivate or delete your account and information from\n    our active databases.\nrights:\n- right: export\n  text: You own all of your data and can view, use, export, or delete\
  \ it at any time.\n- right: complain to supervisory authority\n  text: If you are resident in the European Economic Area and you believe we are unlawfully processing your personal\n    information, you also have the right to complain to your local data protection supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: Tessie takes user privacy very seriously, and will never sell, rent, or share personal information with\n    any third party, unless we are legally forced to share it.\n"
source_yaml_url: https://artifacts.apis.io/tessie/privacy/tessie-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 10 quoted statements, read from Tessie's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Tesla
- Fleet Management
- Automotive
---
