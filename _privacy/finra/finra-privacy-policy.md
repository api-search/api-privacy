---
api_specs:
- filename: finra-async-api-openapi.yml
  format: yaml
  label: FINRA Async API
  slug: finra-async-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finra/openapi/finra-async-api-openapi.yml
- filename: finra-datasets-api-openapi.yml
  format: yaml
  label: FINRA Datasets API
  slug: finra-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finra/openapi/finra-datasets-api-openapi.yml
- filename: finra-metadata-api-openapi.yml
  format: yaml
  label: FINRA Metadata API
  slug: finra-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finra/openapi/finra-metadata-api-openapi.yml
- filename: finra-partitions-api-openapi.yml
  format: yaml
  label: FINRA Partitions API
  slug: finra-partitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finra/openapi/finra-partitions-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: Names, dates of birth, and contact information (e.g., home and business addresses; email addresses; mobile/landline business/personal telephone numbers; etc.)
  - category: identifying
    text: Government-issued identification numbers (e.g., passport number, social security number)
  - category: device
    text: IP addresses
  - category: behavioral
    text: Internet activity or network activity related to your use of our Sites, including information from applications or forms you complete or partially complete
  - category: financial
    text: Information related to billing and payment
  - category: professional
    text: Professional or employment-related information
  - category: other
    text: Criminal record, civil litigation history, or other sensitive information
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: regulatory purposes
    text: 'We use your Personal Information for regulatory purposes, including, but not limited to those related to:'
  - purpose: fraud prevention
    text: The Prevention, detection, and investigation of fraud
  - purpose: site personalization and improvement
    text: The personalization and improvement in the usability of FINRA Sites.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: FINRA does not sell your personal information to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FINRA
provenance_date: '2026-11-09'
provider_name: FINRA
provider_slug: finra
slug: finra-privacy-policy
source_date: '2026-11-09'
source_filename: finra-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.finra.org/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FINRA\naid: finra\nurl: https://www.finra.org/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Names, dates of birth, and contact information (e.g., home and business addresses; email addresses; mobile/landline\n    business/personal telephone numbers; etc.)\n- category: identifying\n  text: Government-issued identification numbers (e.g., passport number, social security number)\n- category: device\n  text: IP addresses\n- category: behavioral\n  text: Internet activity or network activity related to your use of our Sites,\
  \ including information from applications\n    or forms you complete or partially complete\n- category: financial\n  text: Information related to billing and payment\n- category: professional\n  text: Professional or employment-related information\n- category: other\n  text: Criminal record, civil litigation history, or other sensitive information\npurposes:\n- purpose: regulatory purposes\n  text: 'We use your Personal Information for regulatory purposes, including, but not limited to those related to:'\n- purpose: fraud prevention\n  text: The Prevention, detection, and investigation of fraud\n- purpose: site personalization and improvement\n  text: The personalization and improvement in the usability of FINRA Sites.\nretention: []\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: FINRA does not sell your personal\
  \ information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/finra/privacy/finra-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- sale_or_sharing
summary_line: 11 quoted statements, read from FINRA's own page on 2026-11-09.
synthetic: false
tags:
- Compliance
- Finance
- Regulations
- Securities
- Market Data
---
