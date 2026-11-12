---
api_specs:
- filename: copyright01-com-api-keys-api-openapi.yml
  format: yaml
  label: Copyright01 Api Keys API
  slug: copyright01-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copyright01-com/openapi/copyright01-com-api-keys-api-openapi.yml
- filename: copyright01-com-deposits-api-openapi.yml
  format: yaml
  label: Copyright01 Deposits API
  slug: copyright01-com-deposits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copyright01-com/openapi/copyright01-com-deposits-api-openapi.yml
- filename: copyright01-com-me-api-openapi.yml
  format: yaml
  label: Copyright01 Me API
  slug: copyright01-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copyright01-com/openapi/copyright01-com-me-api-openapi.yml
- filename: copyright01-com-verify-api-openapi.yml
  format: yaml
  label: Copyright01 Verify API
  slug: copyright01-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copyright01-com/openapi/copyright01-com-verify-api-openapi.yml
- filename: copyright01-com-verify-hash-api-openapi.yml
  format: yaml
  label: Copyright01 Verify Hash API
  slug: copyright01-com-verify-hash-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/copyright01-com/openapi/copyright01-com-verify-hash-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Full name
  - category: contact
    text: Email address
  - category: location
    text: Country
  - category: professional
    text: Company name (optional)
  - category: device
    text: IP address (server logs)
  - category: behavioral
    text: Pages visited and visit duration
  - category: device
    text: Browser type and operating system
  deletion:
    route: Account deletion
    text: Upon account deletion, personal data and associated files are deleted immediately.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: 'Service delivery : account creation, deposit of creations, certificate generation'
  - purpose: Security
    text: 'Security : protection against unauthorized access, fraud prevention'
  - purpose: Communication
    text: 'Communication : notifications related to your account and deposits'
  - purpose: Service improvement
    text: 'Service improvement : anonymized usage statistics'
  retention:
  - period: null
    scope: Account data
    text: 'Account data : retained for the duration of account activity. Upon account deletion, personal data and associated files are deleted immediately.'
  - period: 12 months maximum
    scope: Technical logs
    text: 'Technical logs : 12 months maximum'
  - period: 10 years
    scope: Billing data
    text: 'Billing data : 10 years (legal obligation)'
  rights:
  - right: Access
    text: 'Right of access : obtain a copy of your personal data'
  - right: Rectification
    text: 'Right to rectification : correct inaccurate data'
  - right: Erasure
    text: 'Right to erasure : request the deletion of your data'
  - right: Portability
    text: 'Right to data portability : receive your data in a structured format'
  - right: Object
    text: 'Right to object : object to the processing of your data'
  - right: Restriction
    text: 'Right to restriction : restrict the processing of your data'
  role:
    text: 'Data Controller Controller : Copyright01'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Your data is never sold or shared for commercial purposes.
  subprocessors:
    text: 'OVH (France) : server hosting and S3 object storage'
    url: null
  transfers:
  - mechanism: SCC
    text: These transfers are governed by the European Commission's Standard Contractual Clauses (SCCs) and/or the EU-US Data Privacy Framework
  - mechanism: DPF
    text: These transfers are governed by the European Commission's Standard Contractual Clauses (SCCs) and/or the EU-US Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Copyright01
provenance_date: '2026-11-09'
provider_name: Copyright01
provider_slug: copyright01-com
slug: copyright01-com-privacy-policy
source_date: '2026-11-09'
source_filename: copyright01-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://copyright01.com/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Copyright01\naid: copyright01-com\nurl: https://copyright01.com/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Data Controller Controller : Copyright01'\ndata_categories:\n- category: identifying\n  text: Full name\n- category: contact\n  text: Email address\n- category: location\n  text: Country\n- category: professional\n  text: Company name (optional)\n- category: device\n  text: IP address (server logs)\n- category: behavioral\n  text: Pages visited and visit duration\n- category: device\n  text: Browser type and operating system\npurposes:\n- purpose: Service delivery\n  text:\
  \ 'Service delivery : account creation, deposit of creations, certificate generation'\n- purpose: Security\n  text: 'Security : protection against unauthorized access, fraud prevention'\n- purpose: Communication\n  text: 'Communication : notifications related to your account and deposits'\n- purpose: Service improvement\n  text: 'Service improvement : anonymized usage statistics'\nretention:\n- scope: Account data\n  period: null\n  text: 'Account data : retained for the duration of account activity. Upon account deletion, personal data and\n    associated files are deleted immediately.'\n- scope: Technical logs\n  period: 12 months maximum\n  text: 'Technical logs : 12 months maximum'\n- scope: Billing data\n  period: 10 years\n  text: 'Billing data : 10 years (legal obligation)'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: These transfers are governed by the European Commission's Standard Contractual Clauses (SCCs) and/or the\n    EU-US Data Privacy Framework\n- mechanism: DPF\n\
  \  text: These transfers are governed by the European Commission's Standard Contractual Clauses (SCCs) and/or the\n    EU-US Data Privacy Framework\nsubprocessors:\n  url: null\n  text: 'OVH (France) : server hosting and S3 object storage'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion\n  text: Upon account deletion, personal data and associated files are deleted immediately.\nrights:\n- right: Access\n  text: 'Right of access : obtain a copy of your personal data'\n- right: Rectification\n  text: 'Right to rectification : correct inaccurate data'\n- right: Erasure\n  text: 'Right to erasure : request the deletion of your data'\n- right: Portability\n  text: 'Right to data portability : receive your data in a structured format'\n- right: Object\n  text: 'Right to object : object to the processing of your data'\n- right: Restriction\n  text: 'Right to restriction : restrict the processing of your data'\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: Your data is never sold or shared for commercial purposes.\n"
source_yaml_url: https://artifacts.apis.io/copyright01-com/privacy/copyright01-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Copyright01's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Copyright
- Intellectual Property
- Timestamping
- Proof Of Authorship
- Certificates
- MCP
- REST API
---
