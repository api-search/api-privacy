---
api_specs:
- filename: activtrak-administration-api-openapi.yml
  format: yaml
  label: ActivTrak Administration API
  slug: activtrak-administration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/activtrak/openapi/activtrak-administration-api-openapi.yml
- filename: activtrak-administration-scim-api-openapi.yml
  format: yaml
  label: ActivTrak Administration - SCIM API
  slug: activtrak-administration-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/activtrak/openapi/activtrak-administration-scim-api-openapi.yml
- filename: activtrak-bulk-import-api-openapi.yml
  format: yaml
  label: ActivTrak Bulk Import API
  slug: activtrak-bulk-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/activtrak/openapi/activtrak-bulk-import-api-openapi.yml
- filename: activtrak-reports-api-openapi.yml
  format: yaml
  label: ActivTrak Reports API
  slug: activtrak-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/activtrak/openapi/activtrak-reports-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers, such as your name and email address
  - category: contact
    text: This includes your name, work email address, the country you work in, and telephone number.
  - category: location
    text: Geolocation Data (approximate only)
  - category: device
    text: your browser, operating system, hardware, and mobile network information
  - category: behavioral
    text: the areas within our Site that you visit and your activities there
  - category: financial
    text: Commercial Information, such as your purchase history
  deletion:
    route: Deletion request form
    text: (2) request deletion of your personal information
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain, assess, and improve our Services
    text: Provide, maintain, assess, and improve our Services;
  - purpose: Targeted advertising
    text: Personalize the advertisements you see on third-party platforms and websites
  - purpose: Security and fraud prevention
    text: Detect, investigate, and prevent security incidents and other malicious, deceptive, fraudulent, or illegal activity
  residency:
  - region: United States
    text: ActivTrak is headquartered in the United States and has operations and vendors in the United States and other countries.
  retention:
  - period: null
    scope: While relationship with ActivTrak continues
    text: We will retain your personal information while you have a relationship with ActivTrak
  rights:
  - right: Access and portability
    text: request to know more about and access your personal information, including in a portable format
  - right: Correction
    text: request correction of inaccurate personal information
  - right: Restriction of processing
    text: request restriction of processing of your personal information
  - right: Objection
    text: object to the processing of your personal information for certain purposes
  - right: Opt out of targeted advertising, sharing, and sales
    text: Depending on where you reside, you may have the right to opt out of targeted advertising, sharing, and sales of your personal information.
  role:
    text: ActivTrak processes End User data on behalf of its Customers
    value: both
  sale_or_sharing:
    stance: conditional
    text: Depending on where you reside, you may have the right to opt out of targeted advertising, sharing, and sales of your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: executing Standard Contractual Clauses
  - mechanism: adequacy
    text: relying on the European Commission’s adequacy decisions
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ActivTrak
provenance_date: '2026-11-09'
provider_name: ActivTrak
provider_slug: activtrak
slug: activtrak-privacy-policy
source_date: '2026-11-09'
source_filename: activtrak-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.activtrak.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ActivTrak\naid: activtrak\nurl: https://www.activtrak.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: ActivTrak processes End User data on behalf of its Customers\ndata_categories:\n- category: identifying\n  text: Identifiers, such as your name and email address\n- category: contact\n  text: This includes your name, work email address, the country you work in, and telephone number.\n- category: location\n  text: Geolocation Data (approximate only)\n- category: device\n  text: your browser, operating system, hardware, and mobile network information\n- category: behavioral\n  text:\
  \ the areas within our Site that you visit and your activities there\n- category: financial\n  text: Commercial Information, such as your purchase history\npurposes:\n- purpose: Provide, maintain, assess, and improve our Services\n  text: Provide, maintain, assess, and improve our Services;\n- purpose: Targeted advertising\n  text: Personalize the advertisements you see on third-party platforms and websites\n- purpose: Security and fraud prevention\n  text: Detect, investigate, and prevent security incidents and other malicious, deceptive, fraudulent, or illegal\n    activity\nretention:\n- scope: While relationship with ActivTrak continues\n  period: null\n  text: We will retain your personal information while you have a relationship with ActivTrak\nresidency:\n- region: United States\n  text: ActivTrak is headquartered in the United States and has operations and vendors in the United States and\n    other countries.\ntransfers:\n- mechanism: SCC\n  text: executing Standard Contractual\
  \ Clauses\n- mechanism: adequacy\n  text: relying on the European Commission’s adequacy decisions\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Deletion request form\n  text: (2) request deletion of your personal information\nrights:\n- right: Access and portability\n  text: request to know more about and access your personal information, including in a portable format\n- right: Correction\n  text: request correction of inaccurate personal information\n- right: Restriction of processing\n  text: request restriction of processing of your personal information\n- right: Objection\n  text: object to the processing of your personal information for certain purposes\n- right: Opt out of targeted advertising, sharing, and sales\n  text: Depending on where you reside, you may have the right to opt out of targeted advertising, sharing, and sales\n    of your personal information.\nsale_or_sharing:\n  stance: conditional\n  text:\
  \ Depending on where you reside, you may have the right to opt out of targeted advertising, sharing, and sales\n    of your personal information.\n"
source_yaml_url: https://artifacts.apis.io/activtrak/privacy/activtrak-privacy-policy.yml
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
summary_line: 21 quoted statements, read from ActivTrak's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Workforce Analytics
- Productivity
- Employee Monitoring
- Workforce Management
- SCIM
- Reporting
---
