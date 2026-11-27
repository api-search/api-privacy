---
api_specs:
- filename: evervault-core-api-openapi.yml
  format: yaml
  label: Evervault Core API
  slug: evervault-core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evervault/openapi/evervault-core-api-openapi.yml
- filename: evervault-payments-api-openapi.yml
  format: yaml
  label: Evervault Payments API
  slug: evervault-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evervault/openapi/evervault-payments-api-openapi.yml
- filename: evervault-webhooks-api-openapi.yml
  format: yaml
  label: Evervault Webhooks API
  slug: evervault-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evervault/openapi/evervault-webhooks-api-openapi.yml
- filename: evervault-evervault-api-api-openapi.yml
  format: yaml
  label: Evervault API
  slug: evervault-evervault-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/evervault/openapi/evervault-evervault-api-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity & Contact Data (e.g. name, email, phone, roles specific professional information)
  - category: financial
    text: Financial & Transaction Data
  - category: device
    text: Usage, Profile, and Device Data
  - category: behavioral
    text: Marketing Preferences and Feedback Data
  deletion:
    route: privacy@evervault.com
    text: 'Contact: privacy@evervault.com to exercise any of the above.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve services
    text: Provide and improve our services
  - purpose: Personalization
    text: Personalize user experiences
  - purpose: Comply with legal obligations
    text: Comply with legal obligations
  - purpose: Research, training, and quality control
    text: Conduct research, training, and quality control
  - purpose: Marketing
    text: Perform marketing within appropriate legal mechanism
  - purpose: Hiring
    text: Assess candidates for hiring
  retention:
  - period: null
    scope: personal data
    text: Data is retained as long as required for service delivery, legal compliance, or legitimate interests in alignment with relevant regulatory requirements.
  - period: null
    scope: HIPAA data
    text: HIPAA related data is never stored persistently by Evervault.
  rights:
  - right: Access, correct, or delete
    text: Access, correct, or delete personal data
  - right: Restrict or object to processing
    text: Restrict or object to processing
  - right: Withdraw consent
    text: Withdraw consent
  - right: Port data
    text: Port your data
  - right: Lodge a complaint
    text: Lodge a complaint with your regulator
  - right: Opt-out of sharing (CCPA)
    text: opt-out of sharing your personal information for targeted advertising
  role:
    text: Evervault (Data Processor & Controller)
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: We provide relevant customers 60 days’ notice before onboarding new sub-processors in our production stack.
    url: null
  transfers:
  - mechanism: SCC
    text: Such transfers will comply with applicable data protection regulations and rely on adequate safeguards, including Standard Contractual Clauses or adequacy decisions.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Evervault
provenance_date: '2026-11-09'
provider_name: Evervault
provider_slug: evervault
slug: evervault-privacy-policy
source_date: '2026-11-09'
source_filename: evervault-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://evervault.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Evervault\naid: evervault\nurl: https://evervault.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Evervault (Data Processor & Controller)\ndata_categories:\n- category: identifying\n  text: Identity & Contact Data (e.g. name, email, phone, roles specific professional information)\n- category: financial\n  text: Financial & Transaction Data\n- category: device\n  text: Usage, Profile, and Device Data\n- category: behavioral\n  text: Marketing Preferences and Feedback Data\npurposes:\n- purpose: Provide and improve services\n  text: Provide and improve our services\n- purpose: Personalization\n\
  \  text: Personalize user experiences\n- purpose: Comply with legal obligations\n  text: Comply with legal obligations\n- purpose: Research, training, and quality control\n  text: Conduct research, training, and quality control\n- purpose: Marketing\n  text: Perform marketing within appropriate legal mechanism\n- purpose: Hiring\n  text: Assess candidates for hiring\nretention:\n- scope: personal data\n  period: null\n  text: Data is retained as long as required for service delivery, legal compliance, or legitimate interests in\n    alignment with relevant regulatory requirements.\n- scope: HIPAA data\n  period: null\n  text: HIPAA related data is never stored persistently by Evervault.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Such transfers will comply with applicable data protection regulations and rely on adequate safeguards,\n    including Standard Contractual Clauses or adequacy decisions.\nsubprocessors:\n  url: null\n  text: We provide relevant customers 60 days’ notice\
  \ before onboarding new sub-processors in our production stack.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: privacy@evervault.com\n  text: 'Contact: privacy@evervault.com to exercise any of the above.'\nrights:\n- right: Access, correct, or delete\n  text: Access, correct, or delete personal data\n- right: Restrict or object to processing\n  text: Restrict or object to processing\n- right: Withdraw consent\n  text: Withdraw consent\n- right: Port data\n  text: Port your data\n- right: Lodge a complaint\n  text: Lodge a complaint with your regulator\n- right: Opt-out of sharing (CCPA)\n  text: opt-out of sharing your personal information for targeted advertising\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/evervault/privacy/evervault-privacy-policy.yml
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
summary_line: 23 quoted statements, read from Evervault's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data
- Security
- Encryption
- Payments
- PCI Compliance
- Tokenization
- Cards
- Developer Tools
---
