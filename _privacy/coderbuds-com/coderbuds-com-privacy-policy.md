---
api_specs:
- filename: coderbuds-com-openapi-generated.yml
  format: yaml
  label: Coderbuds API
  slug: coderbuds-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderbuds-com/openapi/_ae-authored/coderbuds-com-openapi-generated.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: GitHub or BitBucket account information (username, email, avatar)
  - category: professional
    text: Repository access permissions
  - category: device
    text: IP addresses and device information
  - category: behavioral
    text: Usage patterns and feature interactions
  - category: behavioral
    text: Pull request metadata and code review information
  - category: other
    text: Each tool call records the tool's name, the arguments your agent sent with it, and the agent's name and version.
  deletion:
    route: Request deletion of personal information
    text: 'Deletion: Request deletion of your personal information'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: To provide DORA metrics, PR analytics, and team insights
  - purpose: Product improvement
    text: To enhance features and user experience
  - purpose: Communication
    text: To send important updates and support responses
  - purpose: Security
    text: To protect against fraud and unauthorized access
  retention:
  - period: 180 days
    scope: Tool call log
    text: The tool call log is deleted after 180 days
  - period: 30 days
    scope: Account data
    text: Account data is typically deleted within 30 days of account closure, unless longer retention is required by law.
  rights:
  - right: Access
    text: 'Access: Request access to your personal information'
  - right: Correction
    text: 'Correction: Request correction of inaccurate information'
  - right: Deletion
    text: 'Deletion: Request deletion of your personal information'
  - right: Portability
    text: 'Portability: Request export of your data'
  - right: Objection
    text: 'Objection: Object to processing in certain circumstances'
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
name: Coderbuds
provenance_date: '2026-11-09'
provider_name: Coderbuds
provider_slug: coderbuds-com
slug: coderbuds-com-privacy-policy
source_date: '2026-11-09'
source_filename: coderbuds-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://coderbuds.com/docs/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Coderbuds\naid: coderbuds-com\nurl: https://coderbuds.com/docs/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: GitHub or BitBucket account information (username, email, avatar)\n- category: professional\n  text: Repository access permissions\n- category: device\n  text: IP addresses and device information\n- category: behavioral\n  text: Usage patterns and feature interactions\n- category: behavioral\n  text: Pull request metadata and code review information\n- category: other\n  text: Each tool call records the tool's name, the\
  \ arguments your agent sent with it, and the agent's name and\n    version.\npurposes:\n- purpose: Service delivery\n  text: To provide DORA metrics, PR analytics, and team insights\n- purpose: Product improvement\n  text: To enhance features and user experience\n- purpose: Communication\n  text: To send important updates and support responses\n- purpose: Security\n  text: To protect against fraud and unauthorized access\nretention:\n- scope: Tool call log\n  period: 180 days\n  text: The tool call log is deleted after 180 days\n- scope: Account data\n  period: 30 days\n  text: Account data is typically deleted within 30 days of account closure, unless longer retention is required\n    by law.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion of personal information\n  text: 'Deletion: Request deletion of your personal information'\nrights:\n- right: Access\n  text: 'Access:\
  \ Request access to your personal information'\n- right: Correction\n  text: 'Correction: Request correction of inaccurate information'\n- right: Deletion\n  text: 'Deletion: Request deletion of your personal information'\n- right: Portability\n  text: 'Portability: Request export of your data'\n- right: Objection\n  text: 'Objection: Object to processing in certain circumstances'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coderbuds-com/privacy/coderbuds-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 18 quoted statements, read from Coderbuds's own page on 2026-11-09.
synthetic: false
tags:
- Company
- DORA Metrics
- Engineering Metrics
- Developer Productivity
- Code Review
- AI Agents
- MCP
- Software Engineering Intelligence
---
