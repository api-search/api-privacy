---
api_specs:
- filename: autofi-authorization-api-openapi.yml
  format: yaml
  label: AutoFi Authorization API
  slug: autofi-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autofi/openapi/autofi-authorization-api-openapi.yml
- filename: autofi-calculate-payment-api-openapi.yml
  format: yaml
  label: AutoFi Calculate Payment API
  slug: autofi-calculate-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autofi/openapi/autofi-calculate-payment-api-openapi.yml
- filename: autofi-dealers-api-openapi.yml
  format: yaml
  label: AutoFi Dealers API
  slug: autofi-dealers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autofi/openapi/autofi-dealers-api-openapi.yml
- filename: autofi-dealmaker-api-openapi.yml
  format: yaml
  label: AutoFi Dealmaker API
  slug: autofi-dealmaker-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autofi/openapi/autofi-dealmaker-api-openapi.yml
- filename: autofi-loan-applications-api-openapi.yml
  format: yaml
  label: AutoFi Loan Applications API
  slug: autofi-loan-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autofi/openapi/autofi-loan-applications-api-openapi.yml
- filename: autofi-prequalification-api-openapi.yml
  format: yaml
  label: AutoFi Prequalification API
  slug: autofi-prequalification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/autofi/openapi/autofi-prequalification-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Personal information may include your name, address, e-mail address, telephone number; age, date of birth, and social security number
  - category: financial
    text: financial information, including information concerning your assets, income, and bankruptcy history
  - category: financial
    text: billing details, such as credit card and bank account information and your billing address
  - category: device
    text: information about devices accessing the Website and Service, including the type of device, what operating system is used, device settings, application IDs, and unique device identifiers
  - category: behavioral
    text: metadata that provides additional context about the way you work and use the Service
  - category: professional
    text: employment and/or employment history information
  - category: health
    text: details of your health or disability, including information concerning your COVID-19 testing and vaccination status
  - category: demographic
    text: race, disability, marital status, sex, ethnicity, gender, and military or veteran status
  deletion:
    route: submit a request to privacy@autofi.com
    text: to request deletion of your personal information
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide the Service
    text: Broadly, we use any personal information we collect or receive to provide the Service or as may be permitted or required by law or regulation.
  - purpose: improve and develop products and services
    text: This may include creating or using aggregated, de-identified, or anonymized data to improve or develop products and services.
  retention:
  - period: null
    scope: personal information
    text: We retain personal information for no longer than necessary to fulfill the purposes for which it was collected and used
  rights:
  - right: access
    text: to request access to more details about the categories and specific pieces of personal information we may have collected about you in the last 12 months
  - right: deletion
    text: to request deletion of your personal information
  - right: data portability
    text: Data portability.
  - right: opt-out of profiling
    text: Opt-out of profiling in furtherance of decisions that produce legal or similarly significant effects.
  - right: appeal
    text: To appeal a decision regarding a consumer rights request, you must submit the appeal request to privacy@autofi.com.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent personal information and will not share your personal information with third parties for their own marketing or promotional purposes unless you ask us to or provide us your consent to do so.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AutoFi
provenance_date: '2026-11-09'
provider_name: AutoFi
provider_slug: autofi
slug: autofi-privacy-policy
source_date: '2026-11-09'
source_filename: autofi-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.autofi.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AutoFi\naid: autofi\nurl: https://www.autofi.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Personal information may include your name, address, e-mail address, telephone number; age, date of birth,\n    and social security number\n- category: financial\n  text: financial information, including information concerning your assets, income, and bankruptcy history\n- category: financial\n  text: billing details, such as credit card and bank account information and your billing address\n- category: device\n  text: information\
  \ about devices accessing the Website and Service, including the type of device, what operating\n    system is used, device settings, application IDs, and unique device identifiers\n- category: behavioral\n  text: metadata that provides additional context about the way you work and use the Service\n- category: professional\n  text: employment and/or employment history information\n- category: health\n  text: details of your health or disability, including information concerning your COVID-19 testing and vaccination\n    status\n- category: demographic\n  text: race, disability, marital status, sex, ethnicity, gender, and military or veteran status\npurposes:\n- purpose: provide the Service\n  text: Broadly, we use any personal information we collect or receive to provide the Service or as may be permitted\n    or required by law or regulation.\n- purpose: improve and develop products and services\n  text: This may include creating or using aggregated, de-identified, or anonymized data\
  \ to improve or develop products\n    and services.\nretention:\n- scope: personal information\n  period: null\n  text: We retain personal information for no longer than necessary to fulfill the purposes for which it was collected\n    and used\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: submit a request to privacy@autofi.com\n  text: to request deletion of your personal information\nrights:\n- right: access\n  text: to request access to more details about the categories and specific pieces of personal information we may\n    have collected about you in the last 12 months\n- right: deletion\n  text: to request deletion of your personal information\n- right: data portability\n  text: Data portability.\n- right: opt-out of profiling\n  text: Opt-out of profiling in furtherance of decisions that produce legal or similarly significant effects.\n- right: appeal\n  text: To appeal a decision\
  \ regarding a consumer rights request, you must submit the appeal request to privacy@autofi.com.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal information and will not share your personal information with third parties\n    for their own marketing or promotional purposes unless you ask us to or provide us your consent to do so.\n"
source_yaml_url: https://artifacts.apis.io/autofi/privacy/autofi-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from AutoFi's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automotive
- Fintech
- Digital Retail
- Auto Finance
- Dealership
- Sales Enablement
- Software-as-a-Service
- Lending
- Loan Origination
- Credit Decisioning
- Payment Calculation
- Prequalification
---
