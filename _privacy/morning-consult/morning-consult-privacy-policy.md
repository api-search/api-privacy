---
api_specs:
- filename: morning-consult-ai-api-openapi.yml
  format: yaml
  label: Morning Consult AI API
  slug: morning-consult-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morning-consult/openapi/morning-consult-ai-api-openapi.yml
- filename: morning-consult-authentication-api-openapi.yml
  format: yaml
  label: Morning Consult Authentication API
  slug: morning-consult-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morning-consult/openapi/morning-consult-authentication-api-openapi.yml
- filename: morning-consult-data-api-openapi.yml
  format: yaml
  label: Morning Consult Data API
  slug: morning-consult-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morning-consult/openapi/morning-consult-data-api-openapi.yml
- filename: morning-consult-lookup-api-openapi.yml
  format: yaml
  label: Morning Consult Lookup API
  slug: morning-consult-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/morning-consult/openapi/morning-consult-lookup-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: (e.g., your name, job title, organizational affiliation, and email address)
  - category: device
    text: device identifier, IP address, browser type, or operating system
  - category: location
    text: general location data
  - category: behavioral
    text: including a history of the pages you view
  - category: financial
    text: credit or debit card information, billing address, name, email address, etc.
  - category: professional
    text: work and educational history
  - category: demographic
    text: racial, ethnic, or origin identity, gender, whether you identify as part of the LGBTQ+ community, disability status, veteran status
  - category: other
    text: collects and records certain sensory information from you during the course of audiovisual calls we conduct with you
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  retention:
  - period: thirty (30) days
    scope: MCP Connector request logs and authentication credentials
    text: for a period of thirty (30) days following the date of the applicable request
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
name: Morning Consult
provenance_date: '2026-11-10'
provider_name: Morning Consult
provider_slug: morning-consult
slug: morning-consult-privacy-policy
source_date: '2026-11-10'
source_filename: morning-consult-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://morningconsult.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Morning Consult\naid: morning-consult\nurl: https://morningconsult.com/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: (e.g., your name, job title, organizational affiliation, and email address)\n- category: device\n  text: device identifier, IP address, browser type, or operating system\n- category: location\n  text: general location data\n- category: behavioral\n  text: including a history of the pages you view\n- category: financial\n  text: credit or debit card information, billing address, name,\
  \ email address, etc.\n- category: professional\n  text: work and educational history\n- category: demographic\n  text: racial, ethnic, or origin identity, gender, whether you identify as part of the LGBTQ+ community, disability\n    status, veteran status\n- category: other\n  text: collects and records certain sensory information from you during the course of audiovisual calls we conduct\n    with you\npurposes: []\nretention:\n- scope: MCP Connector request logs and authentication credentials\n  period: thirty (30) days\n  text: for a period of thirty (30) days following the date of the applicable request\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/morning-consult/privacy/morning-consult-privacy-policy.yml
stated_fields:
- data_categories
- retention
summary_line: 9 quoted statements, read from Morning Consult's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Market Research
- Survey Data
- Consumer Intelligence
- Brand Tracking
- Decision Intelligence
- Public Opinion
- Analytics
- Data
- Artificial Intelligence
---
