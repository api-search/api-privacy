---
api_specs:
- filename: infere-openapi-generated.yml
  format: yaml
  label: Snowball Studio Ltd. API
  slug: infere-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infere/openapi/_ae-authored/infere-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Data: name, email address, login credentials, organisation details.'
  - category: financial
    text: 'Billing Data: billing address, transaction data, payment references (processed via third-party payment providers).'
  - category: device
    text: 'Usage Data: IP address, device identifiers, timestamps, API usage metrics, routing data, logs.'
  - category: behavioral
    text: 'Cookie and device data: cookie identifiers, device and browser information, session information, preferences, and similar information collected through cookies or comparable technologies, subject to applicable consent requirements.'
  - category: communication
    text: 'Support and Communications Data: correspondence, support tickets, and feedback.'
  - category: other
    text: 'User Content: any Personal Data included in prompts, inputs, or outputs processed through the Service.'
  deletion:
    route: null
    text: null
  dpa:
    available: true
    text: Data Processing Agreement (DPA), its Annexes, and any applicable Order Form.
    url: null
  purposes:
  - purpose: Account creation and service provision
    text: Account creation, administration, and provision of the Service — performance of a contract or steps taken at the individual’s request before entering into a contract
  - purpose: Billing and payments
    text: Billing and payments — performance of a contract and compliance with applicable accounting, tax, and other legal obligations
  - purpose: Security and fraud prevention
    text: Security, fraud prevention, and abuse detection — Infere’s legitimate interests in protecting the Service, Users, and third parties
  - purpose: Service analytics and improvement
    text: Service analytics and improvement — Infere’s legitimate interests in understanding and improving the operation, performance, and security of the Service
  retention:
  - period: duration of account and legal retention periods
    scope: Account Data
    text: 'Account Data: duration of account and legal retention periods'
  - period: maximum 90 days unless otherwise agreed
    scope: Observability Data
    text: 'Observability Data: maximum 90 days unless otherwise agreed, unless a shorter period applies under User configuration or Applicable Law requires otherwise'
  - period: as required by financial regulations
    scope: Billing Data
    text: 'Billing Data: as required by financial regulations'
  rights:
  - right: access
    text: obtain access to their Personal Data
  - right: rectification
    text: request rectification of inaccurate Personal Data
  - right: erasure
    text: request erasure of Personal Data
  - right: restriction
    text: request restriction of processing
  - right: portability
    text: receive or request portability of Personal Data where applicable
  - right: objection
    text: object to processing based on legitimate interest and to processing for direct marketing purposes
  - right: complaint
    text: lodge a complaint with a competent supervisory authority
  role:
    text: 'Infere acts as Controller in relation to: account registration and management'
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Subprocessors and infrastructure providers: including cloud providers (e.g., AWS, Cloudflare), payment processors (e.g., Stripe), and analytics or infrastructure services.'
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCCs); adequacy decisions where applicable; supplementary measures where required.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Snowball Studio Ltd.
provenance_date: '2026-11-09'
provider_name: Snowball Studio Ltd.
provider_slug: infere
slug: infere-privacy-policy
source_date: '2026-11-09'
source_filename: infere-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://infere.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Snowball Studio Ltd.\naid: infere\nurl: https://infere.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Infere acts as Controller in relation to: account registration and management'\ndata_categories:\n- category: identifying\n  text: 'Account Data: name, email address, login credentials, organisation details.'\n- category: financial\n  text: 'Billing Data: billing address, transaction data, payment references (processed via third-party payment\n    providers).'\n- category: device\n  text: 'Usage Data: IP address, device identifiers, timestamps, API usage metrics, routing data,\
  \ logs.'\n- category: behavioral\n  text: 'Cookie and device data: cookie identifiers, device and browser information, session information, preferences,\n    and similar information collected through cookies or comparable technologies, subject to applicable consent\n    requirements.'\n- category: communication\n  text: 'Support and Communications Data: correspondence, support tickets, and feedback.'\n- category: other\n  text: 'User Content: any Personal Data included in prompts, inputs, or outputs processed through the Service.'\npurposes:\n- purpose: Account creation and service provision\n  text: Account creation, administration, and provision of the Service — performance of a contract or steps taken\n    at the individual’s request before entering into a contract\n- purpose: Billing and payments\n  text: Billing and payments — performance of a contract and compliance with applicable accounting, tax, and other\n    legal obligations\n- purpose: Security and fraud prevention\n  text:\
  \ Security, fraud prevention, and abuse detection — Infere’s legitimate interests in protecting the Service,\n    Users, and third parties\n- purpose: Service analytics and improvement\n  text: Service analytics and improvement — Infere’s legitimate interests in understanding and improving the operation,\n    performance, and security of the Service\nretention:\n- scope: Account Data\n  period: duration of account and legal retention periods\n  text: 'Account Data: duration of account and legal retention periods'\n- scope: Observability Data\n  period: maximum 90 days unless otherwise agreed\n  text: 'Observability Data: maximum 90 days unless otherwise agreed, unless a shorter period applies under User\n    configuration or Applicable Law requires otherwise'\n- scope: Billing Data\n  period: as required by financial regulations\n  text: 'Billing Data: as required by financial regulations'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs); adequacy\
  \ decisions where applicable; supplementary measures where required.\nsubprocessors:\n  url: null\n  text: 'Subprocessors and infrastructure providers: including cloud providers (e.g., AWS, Cloudflare), payment\n    processors (e.g., Stripe), and analytics or infrastructure services.'\ndpa:\n  available: true\n  url: null\n  text: Data Processing Agreement (DPA), its Annexes, and any applicable Order Form.\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: obtain access to their Personal Data\n- right: rectification\n  text: request rectification of inaccurate Personal Data\n- right: erasure\n  text: request erasure of Personal Data\n- right: restriction\n  text: request restriction of processing\n- right: portability\n  text: receive or request portability of Personal Data where applicable\n- right: objection\n  text: object to processing based on legitimate interest and to processing for direct marketing purposes\n- right: complaint\n  text: lodge a complaint\
  \ with a competent supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/infere/privacy/infere-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- rights
summary_line: 24 quoted statements, read from Snowball Studio Ltd.'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Observability
- Prompt Management
- LLM
---
