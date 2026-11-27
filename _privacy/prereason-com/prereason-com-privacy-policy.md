---
api_specs:
- filename: prereason-com-agent-access-api-openapi.yml
  format: yaml
  label: prereason-com Agent access API
  slug: prereason-com-agent-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-agent-access-api-openapi.yml
- filename: prereason-com-company-briefings-api-openapi.yml
  format: yaml
  label: prereason-com Company Briefings API
  slug: prereason-com-company-briefings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-company-briefings-api-openapi.yml
- filename: prereason-com-context-api-openapi.yml
  format: yaml
  label: prereason-com Context API
  slug: prereason-com-context-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-context-api-openapi.yml
- filename: prereason-com-metrics-api-openapi.yml
  format: yaml
  label: prereason-com Metrics API
  slug: prereason-com-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-metrics-api-openapi.yml
- filename: prereason-com-short-urls-api-openapi.yml
  format: yaml
  label: prereason-com Short URLs API
  slug: prereason-com-short-urls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-short-urls-api-openapi.yml
- filename: prereason-com-system-api-openapi.yml
  format: yaml
  label: prereason-com System API
  slug: prereason-com-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-system-api-openapi.yml
- filename: prereason-com-treasury-holdings-api-openapi.yml
  format: yaml
  label: prereason-com Treasury Holdings API
  slug: prereason-com-treasury-holdings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-treasury-holdings-api-openapi.yml
- filename: prereason-com-webhooks-api-openapi.yml
  format: yaml
  label: prereason-com Webhooks API
  slug: prereason-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prereason-com/openapi/prereason-com-webhooks-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (for registered users)
  - category: identifying
    text: Username (optional)
  - category: contact
    text: Email address (for registered users)
  - category: device
    text: IP address User agent/browser information Request headers
  - category: financial
    text: we may collect your cryptocurrency wallet address and transaction identifiers for the purpose of processing payments and providing customer support
  - category: behavioral
    text: API requests made (endpoint, timestamp, response time)
  deletion:
    route: Account deletion request; contact privacy@prereason.com
    text: 'Account data: Retained until account deletion request'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service operation
    text: Rate limiting, abuse prevention, API access control
  - purpose: Analytics
    text: Improving service quality and performance
  - purpose: Communication
    text: Service updates, security alerts, support responses
  - purpose: Legal compliance
    text: Meeting regulatory requirements
  residency:
  - region: United States
    text: Our Service is operated from the United States.
  retention:
  - period: Retained until account deletion request
    scope: Account data
    text: 'Account data: Retained until account deletion request'
  - period: 90 days rolling retention
    scope: API logs
    text: 'API logs: 90 days rolling retention'
  - period: 12 months
    scope: Analytics data
    text: 'Analytics data: 12 months'
  rights:
  - right: Access
    text: 'Right of Access: Request a copy of your personal data'
  - right: Rectification
    text: 'Right to Rectification: Correct inaccurate data'
  - right: Erasure
    text: 'Right to Erasure: Request deletion of your data'
  - right: Portability
    text: 'Right to Data Portability: Export your data'
  - right: Object
    text: 'Right to Object: Object to certain processing activities'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: prereason-com
provenance_date: '2026-11-10'
provider_name: prereason-com
provider_slug: prereason-com
slug: prereason-com-privacy-policy
source_date: '2026-11-10'
source_filename: prereason-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.prereason.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: prereason-com\naid: prereason-com\nurl: https://www.prereason.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address (for registered users)\n- category: identifying\n  text: Username (optional)\n- category: contact\n  text: Email address (for registered users)\n- category: device\n  text: IP address User agent/browser information Request headers\n- category: financial\n  text: we may collect your cryptocurrency wallet address and transaction identifiers for the purpose of processing\n    payments and providing customer\
  \ support\n- category: behavioral\n  text: API requests made (endpoint, timestamp, response time)\npurposes:\n- purpose: Service operation\n  text: Rate limiting, abuse prevention, API access control\n- purpose: Analytics\n  text: Improving service quality and performance\n- purpose: Communication\n  text: Service updates, security alerts, support responses\n- purpose: Legal compliance\n  text: Meeting regulatory requirements\nretention:\n- scope: Account data\n  period: Retained until account deletion request\n  text: 'Account data: Retained until account deletion request'\n- scope: API logs\n  period: 90 days rolling retention\n  text: 'API logs: 90 days rolling retention'\n- scope: Analytics data\n  period: 12 months\n  text: 'Analytics data: 12 months'\nresidency:\n- region: United States\n  text: Our Service is operated from the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account\
  \ deletion request; contact privacy@prereason.com\n  text: 'Account data: Retained until account deletion request'\nrights:\n- right: Access\n  text: 'Right of Access: Request a copy of your personal data'\n- right: Rectification\n  text: 'Right to Rectification: Correct inaccurate data'\n- right: Erasure\n  text: 'Right to Erasure: Request deletion of your data'\n- right: Portability\n  text: 'Right to Data Portability: Export your data'\n- right: Object\n  text: 'Right to Object: Object to certain processing activities'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/prereason-com/privacy/prereason-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from prereason-com's own page on 2026-11-10.
synthetic: false
tags:
- Finance
- Markets
- Artificial Intelligence
- Data
- MCP
---
