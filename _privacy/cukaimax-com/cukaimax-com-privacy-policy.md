---
api_specs:
- filename: cukaimax-com-ask-api-openapi.yml
  format: yaml
  label: CukaiMax Ask API
  slug: cukaimax-com-ask-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cukaimax-com/openapi/cukaimax-com-ask-api-openapi.yml
- filename: cukaimax-com-capabilities-api-openapi.yml
  format: yaml
  label: CukaiMax Capabilities API
  slug: cukaimax-com-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cukaimax-com/openapi/cukaimax-com-capabilities-api-openapi.yml
- filename: cukaimax-com-tax-reliefs-api-openapi.yml
  format: yaml
  label: CukaiMax Tax Reliefs API
  slug: cukaimax-com-tax-reliefs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cukaimax-com/openapi/cukaimax-com-tax-reliefs-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and email address (for account creation)
  - category: financial
    text: Payment information (processed securely via third-party providers)
  - category: behavioral
    text: Usage data (pages visited, features used)
  - category: device
    text: Device information (IP address, browser type)
  - category: communication
    text: Forwarded emails containing receipts (parsed for attachments and receipt data only)
  deletion:
    route: request to privacy contact
    text: You may request earlier deletion, subject to legal obligations.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain service
    text: Provide and maintain the CukaiMax service
  - purpose: Service improvement
    text: Improve our service and develop new features
  - purpose: Legal compliance
    text: Comply with legal obligations (LHDN retention requirements)
  - purpose: Receipt AI processing
    text: This AI processing is used solely for providing the receipt scanning and tax categorization features of our service.
  retention:
  - period: 7 years from the date of upload
    scope: receipts and tax data
    text: In compliance with LHDN requirements, we retain your receipts and tax data for 7 years from the date of upload.
  rights:
  - right: Access
    text: Access your personal data
  - right: Correction
    text: Correct inaccurate data
  - right: Withdraw consent
    text: Withdraw consent (subject to legal obligations)
  - right: Deletion
    text: Request data deletion
  - right: Complaint
    text: Lodge a complaint with the Personal Data Protection Commissioner
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Supabase (data storage and authentication)
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CukaiMax
provenance_date: '2026-11-09'
provider_name: CukaiMax
provider_slug: cukaimax-com
slug: cukaimax-com-privacy-policy
source_date: '2026-11-09'
source_filename: cukaimax-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.cukaimax.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CukaiMax\naid: cukaimax-com\nurl: https://www.cukaimax.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name and email address (for account creation)\n- category: financial\n  text: Payment information (processed securely via third-party providers)\n- category: behavioral\n  text: Usage data (pages visited, features used)\n- category: device\n  text: Device information (IP address, browser type)\n- category: communication\n  text: Forwarded emails containing receipts (parsed for attachments and receipt data only)\npurposes:\n\
  - purpose: Provide and maintain service\n  text: Provide and maintain the CukaiMax service\n- purpose: Service improvement\n  text: Improve our service and develop new features\n- purpose: Legal compliance\n  text: Comply with legal obligations (LHDN retention requirements)\n- purpose: Receipt AI processing\n  text: This AI processing is used solely for providing the receipt scanning and tax categorization features of\n    our service.\nretention:\n- scope: receipts and tax data\n  period: 7 years from the date of upload\n  text: In compliance with LHDN requirements, we retain your receipts and tax data for 7 years from the date of\n    upload.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Supabase (data storage and authentication)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request to privacy contact\n  text: You may request earlier deletion, subject to legal obligations.\nrights:\n- right: Access\n  text: Access your personal data\n\
  - right: Correction\n  text: Correct inaccurate data\n- right: Withdraw consent\n  text: Withdraw consent (subject to legal obligations)\n- right: Deletion\n  text: Request data deletion\n- right: Complaint\n  text: Lodge a complaint with the Personal Data Protection Commissioner\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cukaimax-com/privacy/cukaimax-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 17 quoted statements, read from CukaiMax's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Tax
- Personal Finance
- Malaysia
- Receipts
- Efiling
- MCP
- AI Agents
---
