---
api_specs:
- filename: recal-organization-api-openapi.yml
  format: yaml
  label: Recal Organization API
  slug: recal-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recal/openapi/recal-organization-api-openapi.yml
- filename: recal-organization-scheduling-api-openapi.yml
  format: yaml
  label: Recal Organization Scheduling API
  slug: recal-organization-scheduling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recal/openapi/recal-organization-scheduling-api-openapi.yml
- filename: recal-organizations-calendar-api-openapi.yml
  format: yaml
  label: Recal Organizations Calendar API
  slug: recal-organizations-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recal/openapi/recal-organizations-calendar-api-openapi.yml
- filename: recal-user-calendar-api-openapi.yml
  format: yaml
  label: Recal User Calendar API
  slug: recal-user-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recal/openapi/recal-user-calendar-api-openapi.yml
- filename: recal-user-oauth-api-openapi.yml
  format: yaml
  label: Recal User OAuth API
  slug: recal-user-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recal/openapi/recal-user-oauth-api-openapi.yml
- filename: recal-user-scheduling-api-openapi.yml
  format: yaml
  label: Recal User Scheduling API
  slug: recal-user-scheduling-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recal/openapi/recal-user-scheduling-api-openapi.yml
- filename: recal-users-api-openapi.yml
  format: yaml
  label: Recal Users API
  slug: recal-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recal/openapi/recal-users-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Truncated IP address
  - category: contact
    text: E-mail address
  - category: behavioral
    text: page views, click paths
  - category: device
    text: User agent string
  - category: identifying
    text: pseudonymised user ID
  - category: other
    text: optional profile data
  deletion:
    route: null
    text: We delete the data once the purpose has been fulfilled and no statutory retention periods apply.
  dpa:
    available: true
    text: Data-Processing Agreement
    url: null
  purposes:
  - purpose: technical functionality and security analysis
    text: 'Purpose: technical functionality and security analysis (Art. 6 (1) f GDPR).'
  - purpose: user account management
    text: 'Purpose: user account management (Art. 6 (1) b GDPR)'
  - purpose: statistical analysis and product improvement
    text: 'Purpose: statistical analysis and product improvement (Art. 6 (1) f GDPR)'
  residency:
  - region: Germany
    text: Our web application is hosted exclusively on servers located in Germany.
  retention:
  - period: null
    scope: personal data
    text: We delete personal data as soon as its purpose is fulfilled and no statutory retention periods prevent deletion.
  - period: 12 months
    scope: Analytics cookies
    text: Analytics Usage statistics (PostHog) Art. 6 (1) a GDPR 12 months
  rights:
  - right: access, rectify, erase, restrict, object
    text: You have the right to access, rectify, erase, restrict or object to processing, and to data portability (Art. 15–21 GDPR).
  - right: lodge complaint
    text: You may lodge a complaint with any supervisory authority
  role:
    text: 1. Controller Recal GbR – represented by Jona Schwarz & Torben Köhler
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: EU-US Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Recal
provenance_date: '2026-11-10'
provider_name: Recal
provider_slug: recal
slug: recal-privacy-policy
source_date: '2026-11-10'
source_filename: recal-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://recal.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Recal\naid: recal\nurl: https://recal.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 1. Controller Recal GbR – represented by Jona Schwarz & Torben Köhler\ndata_categories:\n- category: identifying\n  text: Truncated IP address\n- category: contact\n  text: E-mail address\n- category: behavioral\n  text: page views, click paths\n- category: device\n  text: User agent string\n- category: identifying\n  text: pseudonymised user ID\n- category: other\n  text: optional profile data\npurposes:\n- purpose: technical functionality and security analysis\n  text: 'Purpose: technical functionality\
  \ and security analysis (Art. 6 (1) f GDPR).'\n- purpose: user account management\n  text: 'Purpose: user account management (Art. 6 (1) b GDPR)'\n- purpose: statistical analysis and product improvement\n  text: 'Purpose: statistical analysis and product improvement (Art. 6 (1) f GDPR)'\nretention:\n- scope: personal data\n  period: null\n  text: We delete personal data as soon as its purpose is fulfilled and no statutory retention periods prevent deletion.\n- scope: Analytics cookies\n  period: 12 months\n  text: Analytics Usage statistics (PostHog) Art. 6 (1) a GDPR 12 months\nresidency:\n- region: Germany\n  text: Our web application is hosted exclusively on servers located in Germany.\ntransfers:\n- mechanism: DPF\n  text: EU-US Data Privacy Framework\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Data-Processing Agreement\ndeletion:\n  route: null\n  text: We delete the data once the purpose has been fulfilled and no statutory retention periods\
  \ apply.\nrights:\n- right: access, rectify, erase, restrict, object\n  text: You have the right to access, rectify, erase, restrict or object to processing, and to data portability\n    (Art. 15–21 GDPR).\n- right: lodge complaint\n  text: You may lodge a complaint with any supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/recal/privacy/recal-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
summary_line: 18 quoted statements, read from Recal's own page on 2026-11-10.
synthetic: false
tags:
- Calendar API
- Scheduling
- SDK
- Multi-Tenant
- Recruiting
- Marketplace
- AI Agents
---
