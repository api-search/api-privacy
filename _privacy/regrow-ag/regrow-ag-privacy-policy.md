---
api_specs:
- filename: regrow-ag-ogc-api-general-api-openapi.yml
  format: yaml
  label: Regrow OGC API - General API
  slug: regrow-ag-ogc-api-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regrow-ag/openapi/regrow-ag-ogc-api-general-api-openapi.yml
- filename: regrow-ag-ogc-api-processes-api-openapi.yml
  format: yaml
  label: Regrow OGC API - Processes API
  slug: regrow-ag-ogc-api-processes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regrow-ag/openapi/regrow-ag-ogc-api-processes-api-openapi.yml
- filename: regrow-ag-v0-explore-api-intervention-api-openapi.yml
  format: yaml
  label: Regrow V0 Explore API - Intervention API
  slug: regrow-ag-v0-explore-api-intervention-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regrow-ag/openapi/regrow-ag-v0-explore-api-intervention-api-openapi.yml
- filename: regrow-ag-v0-measure-api-intervention-api-openapi.yml
  format: yaml
  label: Regrow V0 Measure API - Intervention API
  slug: regrow-ag-v0-measure-api-intervention-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regrow-ag/openapi/regrow-ag-v0-measure-api-intervention-api-openapi.yml
- filename: regrow-ag-v0-measure-api-inventory-api-openapi.yml
  format: yaml
  label: Regrow V0 Measure API - Inventory API
  slug: regrow-ag-v0-measure-api-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regrow-ag/openapi/regrow-ag-v0-measure-api-inventory-api-openapi.yml
- filename: regrow-ag-v1-measure-api-enteric-api-openapi.yml
  format: yaml
  label: Regrow V1 Measure API - Enteric API
  slug: regrow-ag-v1-measure-api-enteric-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/regrow-ag/openapi/regrow-ag-v1-measure-api-enteric-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: email address, phone number, mailing address and contact details
  - category: financial
    text: billing contact name, address, and payment information
  - category: device
    text: IP address and other unique identifiers, general location information, browser type
  - category: behavioral
    text: information about the links clicked, searches, features used, pages viewed, time spent, and files uploaded
  - category: location
    text: With your permission, we may collect your device’s location information.
  - category: communication
    text: we collect and maintain a record of your contact details, contact preferences, communications, and our responses
  - category: professional
    text: your name, email address, phone number, and occupation
  - category: other
    text: agricultural and operational data such as farm boundaries, field data, satellite imagery inputs, agronomic data, soil data, and yield estimates
  deletion:
    route: account deletion, or email to privacy@regrow.ag
    text: If you request that we delete your personal information, we may do so by deleting your account(s) with us.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Providing services and support
    text: To provide and operate our Services and Site, communicate with you about your use of the Services and Site
  - purpose: Analytics and improvement
    text: To better understand how users access and use the Services and Site
  - purpose: Advertising services
    text: To promote Regrow’s products and services on third-party websites
  - purpose: Marketing
    text: For marketing purposes, including to send you newsletters, updates, alerts, and promotional information
  - purpose: Security and protection of rights
    text: To protect the Services and our business operations, including to prevent and detect fraud, misuse, and unauthorized activities
  residency:
  - region: United States
    text: Regrow is headquartered in the United States and operates globally.
  retention:
  - period: as long as necessary
    scope: Personal information (own processing)
    text: we retain your personal information for as long as necessary to fulfill the purposes for which it was collected
  - period: null
    scope: Customer Data (as processor)
    text: our business customers instruct us on how long to retain Customer Data, which we handle as a data processor
  rights:
  - right: Access
    text: To confirm whether we are processing your personal information and to receive a copy of that personal information
  - right: Correction
    text: To request that we correct any personal information we hold about you that is inaccurate or incomplete.
  - right: Erasure
    text: To request that we delete your personal information under certain circumstances
  - right: Portability
    text: To receive a copy of personal information we have obtained from you in a structured, commonly used, and machine-readable format
  - right: Opt out of sales and sharing (California)
    text: The right to opt-out of our sale and sharing of their personal information.
  role:
    text: This Policy applies to the extent we process personal information on our own behalf, as a controller or business.
    value: both
  sale_or_sharing:
    stance: allowed
    text: we may “sell” or “share” (as defined by the CCPA) Identifiers and Usage Data to third-party advertising networks, analytics providers, and social networks.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: transfers of your personal information to third countries will be conducted pursuant to mechanisms approved by the EUropean Commission, such as Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Regrow
provenance_date: '2026-11-10'
provider_name: Regrow
provider_slug: regrow-ag
slug: regrow-ag-privacy-policy
source_date: '2026-11-10'
source_filename: regrow-ag-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.regrow.ag/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Regrow\naid: regrow-ag\nurl: https://www.regrow.ag/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: This Policy applies to the extent we process personal information on our own behalf, as a controller or\n    business.\ndata_categories:\n- category: contact\n  text: email address, phone number, mailing address and contact details\n- category: financial\n  text: billing contact name, address, and payment information\n- category: device\n  text: IP address and other unique identifiers, general location information, browser type\n- category: behavioral\n  text: information\
  \ about the links clicked, searches, features used, pages viewed, time spent, and files uploaded\n- category: location\n  text: With your permission, we may collect your device’s location information.\n- category: communication\n  text: we collect and maintain a record of your contact details, contact preferences, communications, and our responses\n- category: professional\n  text: your name, email address, phone number, and occupation\n- category: other\n  text: agricultural and operational data such as farm boundaries, field data, satellite imagery inputs, agronomic\n    data, soil data, and yield estimates\npurposes:\n- purpose: Providing services and support\n  text: To provide and operate our Services and Site, communicate with you about your use of the Services and Site\n- purpose: Analytics and improvement\n  text: To better understand how users access and use the Services and Site\n- purpose: Advertising services\n  text: To promote Regrow’s products and services on third-party\
  \ websites\n- purpose: Marketing\n  text: For marketing purposes, including to send you newsletters, updates, alerts, and promotional information\n- purpose: Security and protection of rights\n  text: To protect the Services and our business operations, including to prevent and detect fraud, misuse, and\n    unauthorized activities\nretention:\n- scope: Personal information (own processing)\n  period: as long as necessary\n  text: we retain your personal information for as long as necessary to fulfill the purposes for which it was collected\n- scope: Customer Data (as processor)\n  period: null\n  text: our business customers instruct us on how long to retain Customer Data, which we handle as a data processor\nresidency:\n- region: United States\n  text: Regrow is headquartered in the United States and operates globally.\ntransfers:\n- mechanism: SCC\n  text: transfers of your personal information to third countries will be conducted pursuant to mechanisms approved\n    by the EUropean\
  \ Commission, such as Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion, or email to privacy@regrow.ag\n  text: If you request that we delete your personal information, we may do so by deleting your account(s) with us.\nrights:\n- right: Access\n  text: To confirm whether we are processing your personal information and to receive a copy of that personal information\n- right: Correction\n  text: To request that we correct any personal information we hold about you that is inaccurate or incomplete.\n- right: Erasure\n  text: To request that we delete your personal information under certain circumstances\n- right: Portability\n  text: To receive a copy of personal information we have obtained from you in a structured, commonly used, and\n    machine-readable format\n- right: Opt out of sales and sharing (California)\n  text: The right to opt-out of our sale and sharing of their\
  \ personal information.\nsale_or_sharing:\n  stance: allowed\n  text: we may “sell” or “share” (as defined by the CCPA) Identifiers and Usage Data to third-party advertising\n    networks, analytics providers, and social networks.\n"
source_yaml_url: https://artifacts.apis.io/regrow-ag/privacy/regrow-ag-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Regrow's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Agriculture
- Sustainability
- Greenhouse Gas Emissions
- Carbon
- Regenerative Agriculture
- Remote Sensing
- Climate
---
