---
api_specs:
- filename: fundamental-research-labs-authentication-api-openapi.yml
  format: yaml
  label: Fundamental Research Labs Authentication API
  slug: fundamental-research-labs-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundamental-research-labs/openapi/fundamental-research-labs-authentication-api-openapi.yml
- filename: fundamental-research-labs-spreadsheets-api-openapi.yml
  format: yaml
  label: Fundamental Research Labs Spreadsheets API
  slug: fundamental-research-labs-spreadsheets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundamental-research-labs/openapi/fundamental-research-labs-spreadsheets-api-openapi.yml
- filename: fundamental-research-labs-usage-api-openapi.yml
  format: yaml
  label: Fundamental Research Labs Usage API
  slug: fundamental-research-labs-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fundamental-research-labs/openapi/fundamental-research-labs-usage-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name
  - category: contact
    text: Contact details (email)
  - category: device
    text: IP address, browser type, and device information
  - category: behavioral
    text: Usage analytics (For Pro users)
  - category: communication
    text: 'Gmail: If you connect Gmail, we access the messages and threads you ask Shortcut to search or read, including their content, headers, and sender and recipient addresses.'
  deletion:
    route: Email privacy@fundamentalresearchlabs.com
    text: To request data deletion, please email your request to privacy@fundamentalresearchlabs.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: 'Service Delivery: Authentication, session management, and enabling product features'
  - purpose: Customer support
    text: 'Customer Support: Troubleshooting and addressing user inquiries'
  - purpose: Security and fraud prevention
    text: 'Security & Fraud Prevention: Monitoring via real-time threat detection, anomaly logging, API call monitoring, and rate limiting'
  - purpose: Model training
    text: While it is on, your conversations with the agent and their related artifacts may be retained by the Shortcut team to test, debug, and improve our models and products, including by training our AI models.
  residency:
  - region: United States
    text: All data is currently processed in US-based data centers
  retention:
  - period: null
    scope: User session data
    text: 'User session data: Retained for Pro and Teams Users'
  - period: up to 30 days
    scope: AI model API calls
    text: 'AI model API calls: Retained by providers up to 30 days (for safety monitoring)'
  - period: null
    scope: Google Sheet data
    text: 'Google Sheet Data: We do not permanently store the content of your Google Sheets'
  - period: null
    scope: Account data
    text: We retain your Google-provided account information (name, email) for as long as you have an active Shortcut account
  rights:
  - right: Access
    text: Access your data
  - right: Correction
    text: Request correction
  - right: Deletion
    text: Request deletion ("Right to be Forgotten")
  - right: Restrict processing
    text: Restrict processing
  - right: Portability
    text: Data portability
  - right: Object
    text: Object to processing (including marketing)
  - right: Withdraw consent
    text: Withdraw consent
  role:
    text: null
    value: unstated
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
name: Fundamental Research Labs
provenance_date: '2026-11-09'
provider_name: Fundamental Research Labs
provider_slug: fundamental-research-labs
slug: fundamental-research-labs-privacy-policy
source_date: '2026-11-09'
source_filename: fundamental-research-labs-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://shortcut.ai/privacy/policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Fundamental Research Labs\naid: fundamental-research-labs\nurl: https://shortcut.ai/privacy/policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Name\n- category: contact\n  text: Contact details (email)\n- category: device\n  text: IP address, browser type, and device information\n- category: behavioral\n  text: Usage analytics (For Pro users)\n- category: communication\n  text: 'Gmail: If you connect Gmail, we access the messages and threads you ask Shortcut to search or read, including\n    their content, headers, and sender and recipient\
  \ addresses.'\npurposes:\n- purpose: Service delivery\n  text: 'Service Delivery: Authentication, session management, and enabling product features'\n- purpose: Customer support\n  text: 'Customer Support: Troubleshooting and addressing user inquiries'\n- purpose: Security and fraud prevention\n  text: 'Security & Fraud Prevention: Monitoring via real-time threat detection, anomaly logging, API call monitoring,\n    and rate limiting'\n- purpose: Model training\n  text: While it is on, your conversations with the agent and their related artifacts may be retained by the Shortcut\n    team to test, debug, and improve our models and products, including by training our AI models.\nretention:\n- scope: User session data\n  period: null\n  text: 'User session data: Retained for Pro and Teams Users'\n- scope: AI model API calls\n  period: up to 30 days\n  text: 'AI model API calls: Retained by providers up to 30 days (for safety monitoring)'\n- scope: Google Sheet data\n  period: null\n  text:\
  \ 'Google Sheet Data: We do not permanently store the content of your Google Sheets'\n- scope: Account data\n  period: null\n  text: We retain your Google-provided account information (name, email) for as long as you have an active Shortcut\n    account\nresidency:\n- region: United States\n  text: All data is currently processed in US-based data centers\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@fundamentalresearchlabs.com\n  text: To request data deletion, please email your request to privacy@fundamentalresearchlabs.com.\nrights:\n- right: Access\n  text: Access your data\n- right: Correction\n  text: Request correction\n- right: Deletion\n  text: Request deletion (\"Right to be Forgotten\")\n- right: Restrict processing\n  text: Restrict processing\n- right: Portability\n  text: Data portability\n- right: Object\n  text: Object to processing (including marketing)\n- right: Withdraw\
  \ consent\n  text: Withdraw consent\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fundamental-research-labs/privacy/fundamental-research-labs-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 22 quoted statements, read from Fundamental Research Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Spreadsheets
- Excel
- Financial Modeling
- Agents
- Automation
- Productivity
- Data Analysis
---
