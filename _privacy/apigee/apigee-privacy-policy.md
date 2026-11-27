---
api_specs:
- filename: apigee-hybrid-api-openapi.yml
  format: yaml
  label: Apigee Hybrid API
  slug: apigee-hybrid-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apigee/openapi/apigee-hybrid-api-openapi.yml
- filename: apigee-organizations-api-openapi.yml
  format: yaml
  label: Apigee Organizations API
  slug: apigee-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apigee/openapi/apigee-organizations-api-openapi.yml
- filename: apigee-projects-api-openapi.yml
  format: yaml
  label: Apigee Projects API
  slug: apigee-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apigee/openapi/apigee-projects-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information. We collect the data you or your organization provide when creating an account for Cloud Services or entering into a contract with us (username, names, contact details and job titles).
  - category: financial
    text: Cloud payments and transactions. We keep reasonable business records of charges, payments, and billing details and issues.
  - category: device
    text: This information includes device identifiers, identifiers from cookies or tokens, and IP addresses.
  - category: communication
    text: Your direct communications. We keep records of your communications and interactions with us and our partners (for example, when you provide feedback, ask questions or seek technical support).
  deletion:
    route: Deletion when no longer needed
    text: When we no longer need Service Data, we delete or anonymize it.
  dpa:
    available: true
    text: For more information about how we process Customer Data and Partner Data, see our Cloud Data Processing Addendum (Customers)
    url: null
  purposes:
  - purpose: Provide Cloud Services you request
    text: We use Service Data primarily to deliver the Cloud Services that you and our customers request.
  - purpose: Protect you, our users, customers, the public, and Google
    text: We use Service Data to detect, prevent and respond to fraud, abuse, security risks, and technical issues that could harm you, other users, our customers, the public, or Google.
  - purpose: Comply with legal obligations
    text: We use Service Data to comply with our legal obligations (for example, where we’re responding to legal process or an enforceable governmental request, or meeting our financial record-keeping obligations).
  residency:
  - region: global
    text: We maintain data centers around the world
  retention:
  - period: up to 180 days
    scope: most types of Service Data
    text: We retain most types of Service Data for a set period of up to 180 days (the exact number depends on the specific type of data).
  - period: a minimum of five years
    scope: transaction records for tax or accounting
    text: typically for a minimum of five years, as required for tax or accounting purposes, or to comply with applicable financial regulations.
  rights:
  - right: access, correct, delete and export
    text: you have certain rights, including the rights to access, correct, delete and export your Service Data
  - right: object or restrict processing
    text: and to object to or request that we restrict processing of your Service Data.
  - right: non-discrimination
    text: They also provide the right to not be discriminated against for exercising these privacy rights.
  role:
    text: Google Cloud EMEA Ltd will be the data controller responsible for your Service Data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your Service Data to any third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Apigee
provenance_date: '2026-11-09'
provider_name: Apigee
provider_slug: apigee
slug: apigee-privacy-policy
source_date: '2026-11-09'
source_filename: apigee-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cloud.google.com/terms/cloud-privacy-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Apigee\naid: apigee\nurl: https://cloud.google.com/terms/cloud-privacy-notice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: Google Cloud EMEA Ltd will be the data controller responsible for your Service Data.\ndata_categories:\n- category: identifying\n  text: Account information. We collect the data you or your organization provide when creating an account for Cloud\n    Services or entering into a contract with us (username, names, contact details and job titles).\n- category: financial\n  text: Cloud payments and transactions. We keep reasonable business records of charges,\
  \ payments, and billing details\n    and issues.\n- category: device\n  text: This information includes device identifiers, identifiers from cookies or tokens, and IP addresses.\n- category: communication\n  text: Your direct communications. We keep records of your communications and interactions with us and our partners\n    (for example, when you provide feedback, ask questions or seek technical support).\npurposes:\n- purpose: Provide Cloud Services you request\n  text: We use Service Data primarily to deliver the Cloud Services that you and our customers request.\n- purpose: Protect you, our users, customers, the public, and Google\n  text: We use Service Data to detect, prevent and respond to fraud, abuse, security risks, and technical issues\n    that could harm you, other users, our customers, the public, or Google.\n- purpose: Comply with legal obligations\n  text: We use Service Data to comply with our legal obligations (for example, where we’re responding to legal process\n \
  \   or an enforceable governmental request, or meeting our financial record-keeping obligations).\nretention:\n- scope: most types of Service Data\n  period: up to 180 days\n  text: We retain most types of Service Data for a set period of up to 180 days (the exact number depends on the\n    specific type of data).\n- scope: transaction records for tax or accounting\n  period: a minimum of five years\n  text: typically for a minimum of five years, as required for tax or accounting purposes, or to comply with applicable\n    financial regulations.\nresidency:\n- region: global\n  text: We maintain data centers around the world\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: For more information about how we process Customer Data and Partner Data, see our Cloud Data Processing\n    Addendum (Customers)\ndeletion:\n  route: Deletion when no longer needed\n  text: When we no longer need Service Data, we delete or anonymize it.\nrights:\n\
  - right: access, correct, delete and export\n  text: you have certain rights, including the rights to access, correct, delete and export your Service Data\n- right: object or restrict processing\n  text: and to object to or request that we restrict processing of your Service Data.\n- right: non-discrimination\n  text: They also provide the right to not be discriminated against for exercising these privacy rights.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your Service Data to any third parties.\n"
source_yaml_url: https://artifacts.apis.io/apigee/privacy/apigee-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Apigee's own page on 2026-11-09.
synthetic: false
tags:
- Apigee
- Advanced API Security
- AI Agents
- Analytics
- API Gateway
- API Governance
- API Hub
- API Management
- Developer Portal
- Enterprise
- Generative AI
- Hybrid
- Integration
- Microservices
- MCP
- Monetization
---
