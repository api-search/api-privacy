---
api_specs:
- filename: scanner-ad-hoc-queries-api-openapi.yml
  format: yaml
  label: Scanner Ad Hoc Queries API
  slug: scanner-ad-hoc-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-ad-hoc-queries-api-openapi.yml
- filename: scanner-detection-rules-api-openapi.yml
  format: yaml
  label: Scanner Detection Rules API
  slug: scanner-detection-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-detection-rules-api-openapi.yml
- filename: scanner-event-sinks-api-openapi.yml
  format: yaml
  label: Scanner Event Sinks API
  slug: scanner-event-sinks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-event-sinks-api-openapi.yml
- filename: scanner-indexes-api-openapi.yml
  format: yaml
  label: Scanner Indexes API
  slug: scanner-indexes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-indexes-api-openapi.yml
- filename: scanner-info-api-openapi.yml
  format: yaml
  label: Scanner Info API
  slug: scanner-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-info-api-openapi.yml
- filename: scanner-lookup-tables-api-openapi.yml
  format: yaml
  label: Scanner Lookup Tables API
  slug: scanner-lookup-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanner/openapi/scanner-lookup-tables-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers (excluding online identifiers) Contact details
  - category: device
    text: Device data Internet or Network Information
  - category: behavioral
    text: Online activity data
  - category: location
    text: Information about your precise location based on your device's GPS location
  - category: financial
    text: Commercial Information Profile data
  deletion:
    route: Account closure or data removal request
    text: Customers that wish to voluntarily close their account should download their data manually or via the API prior to closing their account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain and improve the Services
    text: Provide, maintain and improve the Services;
  - purpose: Customer support
    text: Respond to your comments, questions and requests, and provide customer support;
  - purpose: Fraud detection and protection
    text: Detect, investigate and prevent fraud and other illegal activities and protect the rights and property of Scanner and others;
  - purpose: Marketing communications
    text: Communicate with you about products, services, offers, promotions, rewards, and events offered by Scanner and others
  retention:
  - period: 30 days
    scope: Customer data in expired account
    text: Expired account data will be retained for 30 days.
  rights:
  - right: Access
    text: Access or Update Your Information.
  - right: Deletion
    text: Deletion. You can ask us to delete the Personal Information that we have collected from you.
  - right: Opt-out of sales
    text: Opt-out of sales. You can opt-out of any sale of your Personal Information.
  - right: Object to processing (GDPR)
    text: The right to object to our processing of your Personal Data;
  role:
    text: we use services that help deliver interest-based ads
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Our use of some of these services may be classified under California law as a “sale” of your Personal Information
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Your information, including Personal Data, may be transferred to and maintained on computers located outside of your state, province, country or other governmental jurisdiction
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Scanner
provenance_date: '2026-11-10'
provider_name: Scanner
provider_slug: scanner
slug: scanner-privacy-policy
source_date: '2026-11-10'
source_filename: scanner-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://scanner.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Scanner\naid: scanner\nurl: https://scanner.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: we use services that help deliver interest-based ads\ndata_categories:\n- category: identifying\n  text: Identifiers (excluding online identifiers) Contact details\n- category: device\n  text: Device data Internet or Network Information\n- category: behavioral\n  text: Online activity data\n- category: location\n  text: Information about your precise location based on your device's GPS location\n- category: financial\n  text: Commercial Information Profile data\npurposes:\n- purpose: Provide,\
  \ maintain and improve the Services\n  text: Provide, maintain and improve the Services;\n- purpose: Customer support\n  text: Respond to your comments, questions and requests, and provide customer support;\n- purpose: Fraud detection and protection\n  text: Detect, investigate and prevent fraud and other illegal activities and protect the rights and property of\n    Scanner and others;\n- purpose: Marketing communications\n  text: Communicate with you about products, services, offers, promotions, rewards, and events offered by Scanner\n    and others\nretention:\n- scope: Customer data in expired account\n  period: 30 days\n  text: Expired account data will be retained for 30 days.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Your information, including Personal Data, may be transferred to and maintained on computers located outside\n    of your state, province, country or other governmental jurisdiction\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n\
  \  url: null\n  text: null\ndeletion:\n  route: Account closure or data removal request\n  text: Customers that wish to voluntarily close their account should download their data manually or via the API\n    prior to closing their account.\nrights:\n- right: Access\n  text: Access or Update Your Information.\n- right: Deletion\n  text: Deletion. You can ask us to delete the Personal Information that we have collected from you.\n- right: Opt-out of sales\n  text: Opt-out of sales. You can opt-out of any sale of your Personal Information.\n- right: Object to processing (GDPR)\n  text: The right to object to our processing of your Personal Data;\nsale_or_sharing:\n  stance: conditional\n  text: Our use of some of these services may be classified under California law as a “sale” of your Personal Information\n"
source_yaml_url: https://artifacts.apis.io/scanner/privacy/scanner-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Scanner's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- SIEM
- Log Analytics
- Threat Detection
- Security Operations
- Observability
- MCP
---
