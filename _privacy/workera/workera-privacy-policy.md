---
api_specs:
- filename: workera-audit-events-api-openapi.yml
  format: yaml
  label: Workera Audit Events API
  slug: workera-audit-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workera/openapi/workera-audit-events-api-openapi.yml
- filename: workera-benchmarks-api-openapi.yml
  format: yaml
  label: Workera Benchmarks API
  slug: workera-benchmarks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workera/openapi/workera-benchmarks-api-openapi.yml
- filename: workera-capability-api-openapi.yml
  format: yaml
  label: Workera Capability API
  slug: workera-capability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workera/openapi/workera-capability-api-openapi.yml
- filename: workera-domains-api-openapi.yml
  format: yaml
  label: Workera Domains API
  slug: workera-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workera/openapi/workera-domains-api-openapi.yml
- filename: workera-ping-api-openapi.yml
  format: yaml
  label: Workera Ping API
  slug: workera-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workera/openapi/workera-ping-api-openapi.yml
- filename: workera-programs-api-openapi.yml
  format: yaml
  label: Workera Programs API
  slug: workera-programs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workera/openapi/workera-programs-api-openapi.yml
- filename: workera-scores-api-openapi.yml
  format: yaml
  label: Workera Scores API
  slug: workera-scores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workera/openapi/workera-scores-api-openapi.yml
- filename: workera-self-ratings-api-openapi.yml
  format: yaml
  label: Workera Self Ratings API
  slug: workera-self-ratings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workera/openapi/workera-self-ratings-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: To create an account for the Services, we require your first name, last name, and email.
  - category: location
    text: We may also collect company name, job role, and location if you choose to provide it.
  - category: financial
    text: we will collect your billing details, including billing address, amount, currency and method of payment.
  - category: behavioral
    text: We also generate inferences (like your skills and proficiency level) from this data
  - category: communication
    text: we may collect a recording of your voice and the transcription results.
  - category: device
    text: Log data includes your internet protocol (IP) address, browser type and settings, the date and time of your request
  deletion:
    route: request via privacy@workera.ai
    text: If you request that your information be removed from our databases, we will delete your information provided
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service operation
    text: To provide the Site and Services (which may include Services provided to the Customer if you are a Workera Enterprise User).
  - purpose: targeted advertising
    text: Create targeted advertising to promote the Services and engage our users.
  - purpose: security
    text: To protect, investigate and deter against fraudulent, unauthorized or illegal activity
  residency:
  - region: United States
    text: Our Company is based in the United States.
  retention:
  - period: null
    scope: user information
    text: We will retain your information for as long as needed to fulfill the purpose for which we collected it and for a reasonable period thereafter
  - period: indefinitely
    scope: aggregated or de-identified data
    text: We may retain aggregated or de-identified data indefinitely or to the extent allowed by applicable law.
  rights:
  - right: access
    text: The right to access certain information about you that we process
  - right: correction
    text: The right to have us correct or update any personal information
  - right: erasure
    text: The right to have certain personal information erased
  - right: portability
    text: The right to have personal information exported into common machine-readable format
  - right: objection
    text: The right to object to our processing of personal information in cases of direct marketing
  role:
    text: Workera processes information on behalf of a Customer to provide contracted Services, we do so in accordance with the terms of the Customer Agreement
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not collect Personal Information for the purpose of sale of such information in a way that specifically identifies the individual (i.e., we do not sell customer information).
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: by using the Services you consent to the transfer of information to countries outside of your country of residence, including the United States
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Workera
provenance_date: '2026-11-10'
provider_name: Workera
provider_slug: workera
slug: workera-privacy-policy
source_date: '2026-11-10'
source_filename: workera-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.workera.ai/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Workera\naid: workera\nurl: https://www.workera.ai/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Workera processes information on behalf of a Customer to provide contracted Services, we do so in accordance\n    with the terms of the Customer Agreement\ndata_categories:\n- category: identifying\n  text: To create an account for the Services, we require your first name, last name, and email.\n- category: location\n  text: We may also collect company name, job role, and location if you choose to provide it.\n- category: financial\n  text: we will collect your billing details,\
  \ including billing address, amount, currency and method of payment.\n- category: behavioral\n  text: We also generate inferences (like your skills and proficiency level) from this data\n- category: communication\n  text: we may collect a recording of your voice and the transcription results.\n- category: device\n  text: Log data includes your internet protocol (IP) address, browser type and settings, the date and time of your\n    request\npurposes:\n- purpose: service operation\n  text: To provide the Site and Services (which may include Services provided to the Customer if you are a Workera\n    Enterprise User).\n- purpose: targeted advertising\n  text: Create targeted advertising to promote the Services and engage our users.\n- purpose: security\n  text: To protect, investigate and deter against fraudulent, unauthorized or illegal activity\nretention:\n- scope: user information\n  period: null\n  text: We will retain your information for as long as needed to fulfill the purpose for\
  \ which we collected it and\n    for a reasonable period thereafter\n- scope: aggregated or de-identified data\n  period: indefinitely\n  text: We may retain aggregated or de-identified data indefinitely or to the extent allowed by applicable law.\nresidency:\n- region: United States\n  text: Our Company is based in the United States.\ntransfers:\n- mechanism: other\n  text: by using the Services you consent to the transfer of information to countries outside of your country of\n    residence, including the United States\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request via privacy@workera.ai\n  text: If you request that your information be removed from our databases, we will delete your information provided\nrights:\n- right: access\n  text: The right to access certain information about you that we process\n- right: correction\n  text: The right to have us correct or update any personal information\n- right: erasure\n\
  \  text: The right to have certain personal information erased\n- right: portability\n  text: The right to have personal information exported into common machine-readable format\n- right: objection\n  text: The right to object to our processing of personal information in cases of direct marketing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not collect Personal Information for the purpose of sale of such information in a way that specifically\n    identifies the individual (i.e., we do not sell customer information).\n"
source_yaml_url: https://artifacts.apis.io/workera/privacy/workera-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Workera's own page on 2026-11-10.
synthetic: false
tags:
- Skills Intelligence
- Skills Assessment
- Human Resources
- Learning and Development
- Talent Management
- Workforce Analytics
- Artificial Intelligence
- Benchmarking
- Enterprise Software
- MCP
- Company
---
