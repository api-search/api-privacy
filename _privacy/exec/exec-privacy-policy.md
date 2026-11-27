---
api_specs:
- filename: exec-collections-api-openapi.yml
  format: yaml
  label: Exec Collections API
  slug: exec-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-collections-api-openapi.yml
- filename: exec-knowledge-hub-folders-api-openapi.yml
  format: yaml
  label: Exec Knowledge Hub - Folders API
  slug: exec-knowledge-hub-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-knowledge-hub-folders-api-openapi.yml
- filename: exec-knowledge-hub-pages-api-openapi.yml
  format: yaml
  label: Exec Knowledge Hub - Pages API
  slug: exec-knowledge-hub-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-knowledge-hub-pages-api-openapi.yml
- filename: exec-knowledge-hub-sources-api-openapi.yml
  format: yaml
  label: Exec Knowledge Hub - Sources API
  slug: exec-knowledge-hub-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-knowledge-hub-sources-api-openapi.yml
- filename: exec-scenario-studio-api-openapi.yml
  format: yaml
  label: Exec Scenario Studio API
  slug: exec-scenario-studio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-scenario-studio-api-openapi.yml
- filename: exec-scenarios-api-openapi.yml
  format: yaml
  label: Exec Scenarios API
  slug: exec-scenarios-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-scenarios-api-openapi.yml
- filename: exec-sessions-api-openapi.yml
  format: yaml
  label: Exec Sessions API
  slug: exec-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-sessions-api-openapi.yml
- filename: exec-skills-api-openapi.yml
  format: yaml
  label: Exec Skills API
  slug: exec-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-skills-api-openapi.yml
- filename: exec-workspace-api-openapi.yml
  format: yaml
  label: Exec Workspace API
  slug: exec-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exec/openapi/exec-workspace-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: device
    text: Internet Protocol addresses, device and browser types and identifiers
  - category: contact
    text: Contact person's name, email, and phone number
  - category: financial
    text: Billing information
  - category: professional
    text: Professional qualifications and experience
  - category: behavioral
    text: Pages visited and time spent on each page
  deletion:
    route: Request to privacy contact email
    text: Request deletion of your personal information
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Improve website performance
    text: To improve website performance and user experience
  - purpose: Billing and account management
    text: For billing and account management
  - purpose: Targeted advertising
    text: place cookies on your browser for targeted advertising purposes
  residency:
  - region: United States
    text: Your data may be stored and processed in the United States or any other country where we or our service providers maintain facilities.
  retention:
  - period: null
    scope: general
    text: We retain your personal data for as long as necessary to provide our services and for legitimate and essential business purposes
  rights:
  - right: Access
    text: Request a copy of your personal data.
  - right: Erasure
    text: Request deletion of your data under certain circumstances.
  - right: Objection
    text: Object to the processing of your data for certain purposes.
  role:
    text: For participant data, we typically act as a data processor on behalf of our customers (organizations).
    value: both
  sale_or_sharing:
    stance: unstated
    text: We do not sell your personal information to third parties.
  subprocessors:
    text: Due to confidentiality restrictions, we cannot disclose the names of subprocessors we use.
    url: null
  transfers:
  - mechanism: SCC
    text: We use EU-approved Standard Contractual Clauses for data transfers out of the EEA.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Exec
provenance_date: '2026-11-09'
provider_name: Exec
provider_slug: exec
slug: exec-privacy-policy
source_date: '2026-11-09'
source_filename: exec-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.exec.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Exec\naid: exec\nurl: https://www.exec.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For participant data, we typically act as a data processor on behalf of our customers (organizations).\ndata_categories:\n- category: device\n  text: Internet Protocol addresses, device and browser types and identifiers\n- category: contact\n  text: Contact person's name, email, and phone number\n- category: financial\n  text: Billing information\n- category: professional\n  text: Professional qualifications and experience\n- category: behavioral\n  text: Pages visited and time spent on each\
  \ page\npurposes:\n- purpose: Improve website performance\n  text: To improve website performance and user experience\n- purpose: Billing and account management\n  text: For billing and account management\n- purpose: Targeted advertising\n  text: place cookies on your browser for targeted advertising purposes\nretention:\n- scope: general\n  period: null\n  text: We retain your personal data for as long as necessary to provide our services and for legitimate and essential\n    business purposes\nresidency:\n- region: United States\n  text: Your data may be stored and processed in the United States or any other country where we or our service\n    providers maintain facilities.\ntransfers:\n- mechanism: SCC\n  text: We use EU-approved Standard Contractual Clauses for data transfers out of the EEA.\nsubprocessors:\n  url: null\n  text: Due to confidentiality restrictions, we cannot disclose the names of subprocessors we use.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n\
  \  route: Request to privacy contact email\n  text: Request deletion of your personal information\nrights:\n- right: Access\n  text: Request a copy of your personal data.\n- right: Erasure\n  text: Request deletion of your data under certain circumstances.\n- right: Objection\n  text: Object to the processing of your data for certain purposes.\nsale_or_sharing:\n  stance: unstated\n  text: We do not sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/exec/privacy/exec-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 17 quoted statements, read from Exec's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Sales Enablement
- Training
- Roleplay
- Coaching
- Learning
- Knowledge Management
- LMS
---
