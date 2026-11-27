---
api_specs:
- filename: snaptrade-account-information-api-openapi.yml
  format: yaml
  label: SnapTrade Account Information API
  slug: snaptrade-account-information-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snaptrade/openapi/snaptrade-account-information-api-openapi.yml
- filename: snaptrade-api-status-api-openapi.yml
  format: yaml
  label: SnapTrade API Status API
  slug: snaptrade-api-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snaptrade/openapi/snaptrade-api-status-api-openapi.yml
- filename: snaptrade-authentication-api-openapi.yml
  format: yaml
  label: SnapTrade Authentication API
  slug: snaptrade-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snaptrade/openapi/snaptrade-authentication-api-openapi.yml
- filename: snaptrade-connections-api-openapi.yml
  format: yaml
  label: SnapTrade Connections API
  slug: snaptrade-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snaptrade/openapi/snaptrade-connections-api-openapi.yml
- filename: snaptrade-management-api-openapi.yml
  format: yaml
  label: SnapTrade Management API
  slug: snaptrade-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snaptrade/openapi/snaptrade-management-api-openapi.yml
- filename: snaptrade-reference-data-api-openapi.yml
  format: yaml
  label: SnapTrade Reference Data API
  slug: snaptrade-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snaptrade/openapi/snaptrade-reference-data-api-openapi.yml
- filename: snaptrade-trading-api-openapi.yml
  format: yaml
  label: SnapTrade Trading API
  slug: snaptrade-trading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snaptrade/openapi/snaptrade-trading-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name; Contact details; Name of employer; Job title and function;
  - category: behavioral
    text: we will process information such as log information, IP address, approximate location
  - category: device
    text: such as your Media Access Control (MAC) address, computer type (Windows or Mac), screen resolution, operating system name and version
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: manage partner contract
    text: We process this Personal Information to enter into and manage our contractual relationship with our Partners and for other legitimate business purposes.
  - purpose: analytics and trend reports
    text: To analyze or predict our users’ preferences in order to prepare aggregated trend reports on how our Service is used
  - purpose: marketing
    text: Providing you with our newsletter and/or other marketing materials.
  - purpose: fraud prevention
    text: For fraud prevention and fraud security monitoring purposes, for example, to detect and prevent cyberattacks or attempts to commit identity theft;
  residency:
  - region: any country where we have facilities or engage service providers
    text: Your Personal Information may be stored and processed in any country where we have facilities or in which we engage service providers
  retention:
  - period: null
    scope: general
    text: We retain Personal Information for as long as needed or permitted in light of the purpose(s) for which it was obtained and consistent with applicable law.
  rights:
  - right: view or update information
    text: You can request to view your information or update it by sending an email to support@snaptrade.com
  - right: opt out of marketing emails
    text: You may opt out from receiving marketing-related emails from us.
  role:
    text: we act as a service provider in this context
    value: processor
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: you understand that your information will be transferred to countries outside of your country of residence, including the United States
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SnapTrade
provenance_date: '2026-11-10'
provider_name: SnapTrade
provider_slug: snaptrade
slug: snaptrade-privacy-policy
source_date: '2026-11-10'
source_filename: snaptrade-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://snaptrade.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SnapTrade\naid: snaptrade\nurl: https://snaptrade.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: we act as a service provider in this context\ndata_categories:\n- category: identifying\n  text: Name; Contact details; Name of employer; Job title and function;\n- category: behavioral\n  text: we will process information such as log information, IP address, approximate location\n- category: device\n  text: such as your Media Access Control (MAC) address, computer type (Windows or Mac), screen resolution, operating\n    system name and version\npurposes:\n- purpose: manage partner\
  \ contract\n  text: We process this Personal Information to enter into and manage our contractual relationship with our Partners\n    and for other legitimate business purposes.\n- purpose: analytics and trend reports\n  text: To analyze or predict our users’ preferences in order to prepare aggregated trend reports on how our Service\n    is used\n- purpose: marketing\n  text: Providing you with our newsletter and/or other marketing materials.\n- purpose: fraud prevention\n  text: For fraud prevention and fraud security monitoring purposes, for example, to detect and prevent cyberattacks\n    or attempts to commit identity theft;\nretention:\n- scope: general\n  period: null\n  text: We retain Personal Information for as long as needed or permitted in light of the purpose(s) for which it\n    was obtained and consistent with applicable law.\nresidency:\n- region: any country where we have facilities or engage service providers\n  text: Your Personal Information may be stored and processed\
  \ in any country where we have facilities or in which\n    we engage service providers\ntransfers:\n- mechanism: other\n  text: you understand that your information will be transferred to countries outside of your country of residence,\n    including the United States\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: view or update information\n  text: You can request to view your information or update it by sending an email to support@snaptrade.com\n- right: opt out of marketing emails\n  text: You may opt out from receiving marketing-related emails from us.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/snaptrade/privacy/snaptrade-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- rights
summary_line: 13 quoted statements, read from SnapTrade's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Brokerage
- Trading
---
