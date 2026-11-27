---
api_specs:
- filename: h-company-agents-api-openapi.yml
  format: yaml
  label: H Company Agents API
  slug: h-company-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-agents-api-openapi.yml
- filename: h-company-browser-profiles-api-openapi.yml
  format: yaml
  label: H Company Browser Profiles API
  slug: h-company-browser-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-browser-profiles-api-openapi.yml
- filename: h-company-environments-api-openapi.yml
  format: yaml
  label: H Company Environments API
  slug: h-company-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-environments-api-openapi.yml
- filename: h-company-quota-api-openapi.yml
  format: yaml
  label: H Company Quota API
  slug: h-company-quota-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-quota-api-openapi.yml
- filename: h-company-schedules-api-openapi.yml
  format: yaml
  label: H Company Schedules API
  slug: h-company-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-schedules-api-openapi.yml
- filename: h-company-sessions-api-openapi.yml
  format: yaml
  label: H Company Sessions API
  slug: h-company-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-sessions-api-openapi.yml
- filename: h-company-skills-api-openapi.yml
  format: yaml
  label: H Company Skills API
  slug: h-company-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-skills-api-openapi.yml
- filename: h-company-vaults-api-openapi.yml
  format: yaml
  label: H Company Vaults API
  slug: h-company-vaults-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-vaults-api-openapi.yml
- filename: h-company-webhooks-api-openapi.yml
  format: yaml
  label: H Company Webhooks API
  slug: h-company-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/h-company/openapi/h-company-webhooks-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: User's registration data (including first name, last name, email address, credentials including login and password, User ID, logs)
  - category: financial
    text: 'Order Data: includes subscribed Services designation, options, billing address, payment made, payments information, and reclamations if any'
  - category: behavioral
    text: 'Input Data: includes all input data, including prompts and instructions, comprising content of any kind - including, but not limited to, text, images, videos, screenshots of websites or of the User''s screen, etc.'
  - category: device
    text: browser extension or application version identifiers
  - category: contact
    text: 'Website Contact Data: includes first name, last name, professional email address, company name, job title'
  deletion:
    route: written request to privacy@hcompany.ai
    text: Right to erasure of Personal Data under the conditions and limitations established by law
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Services provision
    text: providing the agreed Services pursuant to ToCs, including hosting, options and ordered additional services until the Service termination
  - purpose: Services security
    text: Ensure the security and integrity of the Services' infrastructure and components
  - purpose: AI model training
    text: enabling H Company to train its own AI models, notably to answer questions, generate text, translate, compare, summarize and correct inputs, classify information, etc.
  - purpose: Marketing communications
    text: enabling H Company to send marketing messages, newsletters and proposals for new products or services (subject to prior consent, except for active users who may receive marketing communications pursuant to H Company's legitimate interest and subject to the User's right to object)
  residency:
  - region: United States
    text: Data transmissions to our U.S.-based infrastructure are encrypted in transit (TLS) and at rest.
  retention:
  - period: null
    scope: User and account data
    text: Such Personal Data is retained only for the duration of the User's use of the Services until the User's account is deleted, plus (i) in the case of a paid Service, for the duration of H Company's accounting and tax obligations
  - period: thirty (30) days
    scope: Input and output data (EEA users)
    text: Input and Output are deleted thirty (30) days for Users in the European Economic Area after the operation
  - period: ninety (90) days
    scope: Input and output data (non-EEA users)
    text: For non-European Economic Area Users, these are kept for ninety (90) days
  - period: six (6) months
    scope: Technical data for AI model training
    text: For H Company's AI model training purposes, Technical Data is retained for six (6) months following the operation on a pseudonymized basis
  - period: twelve (12) months
    scope: HoloWork beta data
    text: Beta data is retained for twelve (12) months after the end of the beta, or until an objection is processed
  - period: three (3) years
    scope: Marketing data
    text: for a maximum period of three (3) years from the User's last active action
  rights:
  - right: access
    text: Right of access to Personal Data processed concerning them
  - right: rectification
    text: Right to rectification of inaccurate, outdated or incomplete Personal Data
  - right: erasure
    text: Right to erasure of Personal Data under the conditions and limitations established by law
  - right: restriction
    text: Right to restriction of processing in the circumstances contemplated by regulation
  - right: portability
    text: Right to data portability in a structured, commonly used, and machine-readable format
  - right: objection
    text: Right to object to processing based on legitimate interests
  role:
    text: acts as the data controller with respect to all Personal Data processed through the Services
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Data is never sold, licensed, or shared with third parties except as contractually required by our service providers or compelled by lawful authority.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: While H Company has not executed specific Standard Contractual Clauses with service providers in such cases
  - mechanism: other
    text: applicable commercial terms of service incorporate confidentiality and security commitments, supplemented by technical safeguards
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: H Company
provenance_date: '2026-11-09'
provider_name: H Company
provider_slug: h-company
slug: h-company-privacy-policy
source_date: '2026-11-09'
source_filename: h-company-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hcompany.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: H Company\naid: h-company\nurl: https://hcompany.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: acts as the data controller with respect to all Personal Data processed through the Services\ndata_categories:\n- category: identifying\n  text: User's registration data (including first name, last name, email address, credentials including login and\n    password, User ID, logs)\n- category: financial\n  text: 'Order Data: includes subscribed Services designation, options, billing address, payment made, payments\n    information, and reclamations if any'\n- category: behavioral\n\
  \  text: 'Input Data: includes all input data, including prompts and instructions, comprising content of any kind\n    - including, but not limited to, text, images, videos, screenshots of websites or of the User''s screen, etc.'\n- category: device\n  text: browser extension or application version identifiers\n- category: contact\n  text: 'Website Contact Data: includes first name, last name, professional email address, company name, job title'\npurposes:\n- purpose: Services provision\n  text: providing the agreed Services pursuant to ToCs, including hosting, options and ordered additional services\n    until the Service termination\n- purpose: Services security\n  text: Ensure the security and integrity of the Services' infrastructure and components\n- purpose: AI model training\n  text: enabling H Company to train its own AI models, notably to answer questions, generate text, translate, compare,\n    summarize and correct inputs, classify information, etc.\n- purpose: Marketing communications\n\
  \  text: enabling H Company to send marketing messages, newsletters and proposals for new products or services (subject\n    to prior consent, except for active users who may receive marketing communications pursuant to H Company's legitimate\n    interest and subject to the User's right to object)\nretention:\n- scope: User and account data\n  period: null\n  text: Such Personal Data is retained only for the duration of the User's use of the Services until the User's\n    account is deleted, plus (i) in the case of a paid Service, for the duration of H Company's accounting and tax\n    obligations\n- scope: Input and output data (EEA users)\n  period: thirty (30) days\n  text: Input and Output are deleted thirty (30) days for Users in the European Economic Area after the operation\n- scope: Input and output data (non-EEA users)\n  period: ninety (90) days\n  text: For non-European Economic Area Users, these are kept for ninety (90) days\n- scope: Technical data for AI model training\n\
  \  period: six (6) months\n  text: For H Company's AI model training purposes, Technical Data is retained for six (6) months following the\n    operation on a pseudonymized basis\n- scope: HoloWork beta data\n  period: twelve (12) months\n  text: Beta data is retained for twelve (12) months after the end of the beta, or until an objection is processed\n- scope: Marketing data\n  period: three (3) years\n  text: for a maximum period of three (3) years from the User's last active action\nresidency:\n- region: United States\n  text: Data transmissions to our U.S.-based infrastructure are encrypted in transit (TLS) and at rest.\ntransfers:\n- mechanism: SCC\n  text: While H Company has not executed specific Standard Contractual Clauses with service providers in such cases\n- mechanism: other\n  text: applicable commercial terms of service incorporate confidentiality and security commitments, supplemented\n    by technical safeguards\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: written request to privacy@hcompany.ai\n  text: Right to erasure of Personal Data under the conditions and limitations established by law\nrights:\n- right: access\n  text: Right of access to Personal Data processed concerning them\n- right: rectification\n  text: Right to rectification of inaccurate, outdated or incomplete Personal Data\n- right: erasure\n  text: Right to erasure of Personal Data under the conditions and limitations established by law\n- right: restriction\n  text: Right to restriction of processing in the circumstances contemplated by regulation\n- right: portability\n  text: Right to data portability in a structured, commonly used, and machine-readable format\n- right: objection\n  text: Right to object to processing based on legitimate interests\nsale_or_sharing:\n  stance: prohibited\n  text: Data is never sold, licensed, or shared with third parties except as contractually required by our service\n    providers\
  \ or compelled by lawful authority.\n"
source_yaml_url: https://artifacts.apis.io/h-company/privacy/h-company-privacy-policy.yml
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
summary_line: 27 quoted statements, read from H Company's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Computer Use
- Automation
- Machine Learning
- Browser Automation
- LLM
- MCP
- Developer Tools
- Foundation Models
---
