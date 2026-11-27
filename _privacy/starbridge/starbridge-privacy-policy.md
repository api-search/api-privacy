---
api_specs:
- filename: starbridge-bridges-api-openapi.yml
  format: yaml
  label: Starbridge Bridges API
  slug: starbridge-bridges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starbridge/openapi/starbridge-bridges-api-openapi.yml
- filename: starbridge-buyer-api-openapi.yml
  format: yaml
  label: Starbridge Buyer API
  slug: starbridge-buyer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starbridge/openapi/starbridge-buyer-api-openapi.yml
- filename: starbridge-columns-api-openapi.yml
  format: yaml
  label: Starbridge Columns API
  slug: starbridge-columns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starbridge/openapi/starbridge-columns-api-openapi.yml
- filename: starbridge-external-mcp-api-openapi.yml
  format: yaml
  label: Starbridge External MCP API
  slug: starbridge-external-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starbridge/openapi/starbridge-external-mcp-api-openapi.yml
- filename: starbridge-signal-api-openapi.yml
  format: yaml
  label: Starbridge Signal API
  slug: starbridge-signal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/starbridge/openapi/starbridge-signal-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name
  - category: contact
    text: Email address
  - category: professional
    text: Job title
  - category: device
    text: IP address
  - category: behavioral
    text: Pages visited, time spent, and referring URLs
  - category: communication
    text: Any information submitted through forms, surveys, or chat
  deletion:
    route: Email support@starbridge.ai
    text: You can request access to, correction of, or deletion of your extension data, or withdraw consent where processing relies on consent, by contacting support@starbridge.ai .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve the platform
    text: To provide and improve the Starbridge.ai platform
  - purpose: Marketing campaigns
    text: To run marketing campaigns, including targeted and retargeted ads
  - purpose: Respond to inquiries
    text: To respond to inquiries and support requests
  - purpose: Comply with legal obligations
    text: To comply with legal obligations
  residency:
  - region: United States and other countries
    text: Extension data may be processed in the United States and other countries.
  retention:
  - period: null
    scope: Personal data
    text: We retain personal data only as long as necessary to provide services, comply with legal obligations, or support business operations.
  - period: one hour
    scope: Extension local detection cache
    text: Local account-detection results are treated as stale after one hour for lookups with no matching account or six hours for matching results.
  rights:
  - right: Access
    text: Access your personal data
  - right: Correct
    text: Correct inaccurate information
  - right: Delete
    text: Delete your data
  - right: Opt out of targeted advertising
    text: Opt out of targeted advertising
  - right: Data portability
    text: Request a copy of your data (data portability)
  - right: Object
    text: Object to processing based on legitimate interests
  - right: Restrict
    text: Restrict processing of your data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: 'We do not sell personal data. However, we may share information with: a. Service Providers'
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs) approved by the European Commission
  - mechanism: other
    text: The UK International Data Transfer Agreement (IDTA) or UK Addendum to the EU SCCs, as applicable
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Starbridge
provenance_date: '2026-11-10'
provider_name: Starbridge
provider_slug: starbridge
slug: starbridge-privacy-policy
source_date: '2026-11-10'
source_filename: starbridge-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://starbridge.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Starbridge\naid: starbridge\nurl: https://starbridge.ai/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name\n- category: contact\n  text: Email address\n- category: professional\n  text: Job title\n- category: device\n  text: IP address\n- category: behavioral\n  text: Pages visited, time spent, and referring URLs\n- category: communication\n  text: Any information submitted through forms, surveys, or chat\npurposes:\n- purpose: Provide and improve the platform\n  text: To provide and improve the Starbridge.ai platform\n\
  - purpose: Marketing campaigns\n  text: To run marketing campaigns, including targeted and retargeted ads\n- purpose: Respond to inquiries\n  text: To respond to inquiries and support requests\n- purpose: Comply with legal obligations\n  text: To comply with legal obligations\nretention:\n- scope: Personal data\n  period: null\n  text: We retain personal data only as long as necessary to provide services, comply with legal obligations, or\n    support business operations.\n- scope: Extension local detection cache\n  period: one hour\n  text: Local account-detection results are treated as stale after one hour for lookups with no matching account\n    or six hours for matching results.\nresidency:\n- region: United States and other countries\n  text: Extension data may be processed in the United States and other countries.\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) approved by the European Commission\n- mechanism: other\n  text: The UK International Data Transfer\
  \ Agreement (IDTA) or UK Addendum to the EU SCCs, as applicable\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@starbridge.ai\n  text: You can request access to, correction of, or deletion of your extension data, or withdraw consent where\n    processing relies on consent, by contacting support@starbridge.ai .\nrights:\n- right: Access\n  text: Access your personal data\n- right: Correct\n  text: Correct inaccurate information\n- right: Delete\n  text: Delete your data\n- right: Opt out of targeted advertising\n  text: Opt out of targeted advertising\n- right: Data portability\n  text: Request a copy of your data (data portability)\n- right: Object\n  text: Object to processing based on legitimate interests\n- right: Restrict\n  text: Restrict processing of your data\nsale_or_sharing:\n  stance: conditional\n  text: 'We do not sell personal data. However, we may share information with: a. Service Providers'\n"
source_yaml_url: https://artifacts.apis.io/starbridge/privacy/starbridge-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Starbridge's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Sales Intelligence
- Go-To-Market
- Public Sector
- Education
- Government
- Procurement
- Buyer Intelligence
- MCP
- A2A
---
