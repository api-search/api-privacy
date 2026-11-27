---
api_specs:
- filename: atako-ai-api-openapi.json
  format: json
  label: Atako API API
  slug: atako-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/atako-ai/openapi/_original/atako-ai-api-openapi.json
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Last name, first name, email address, encrypted password, role, company, job title
  - category: financial
    text: Stripe transaction and account identifiers, payment history, invoices (no full card data is retained by Atako)
  - category: device
    text: IP address, connection and event logs, suspicious attempts
  - category: behavioral
    text: Trackers, browsing data, session recordings (inputs masked; on the platform, all page text is masked)
  - category: communication
    text: Communications and tickets
  deletion:
    route: Written erasure request; data erased within 30 days
    text: Upon a request for erasure, the data is erased within 30 days, unless a legal retention obligation applies.
  dpa:
    available: true
    text: the data processing agreement annexed to the Terms of Use and Sale applies.
    url: null
  purposes:
  - purpose: Account creation and management
    text: Account creation and management
  - purpose: Support and customer relations
    text: Support and customer relations
  - purpose: Billing and payment
    text: Billing and payment
  - purpose: Security and fraud prevention
    text: Security, fraud prevention, technical logs
  - purpose: Marketing outreach
    text: Marketing outreach (direct marketing) to professionals and newsletter
  - purpose: Audience measurement
    text: Audience measurement and improvement of the website and platform
  - purpose: Service improvement
    text: Improvement of the Service Aggregated usage statistics (number of agents, features used, performance), excluding any content processed by the agents
  residency:
  - region: European Union
    text: Platform data — user accounts, agent names, messages exchanged between users and agents or between agents, session messages, and settings — is hosted in the European Union.
  - region: Outside the EU (agent VMs)
    text: 'The virtual machines in which the agents run may be located outside the European Union: Atako remains free to choose the provider and the region, and the region is not guaranteed.'
  retention:
  - period: duration of the contract
    scope: Agent data
    text: This data is retained for the duration of the contract.
  - period: 3 years after the last activity
    scope: Account data
    text: Duration of the account, then 3 years after the last activity
  - period: 30 days
    scope: Session recordings
    text: 'session recordings: 30 days'
  - period: 13 months maximum
    scope: Trackers
    text: 'Trackers: 13 months maximum'
  - period: 6 months
    scope: Cookie choice
    text: your choice is retained for 6 months
  rights:
  - right: access
    text: You have the rights of access, rectification, erasure, restriction of processing, objection
  - right: portability
    text: data portability, and withdrawal of your consent
  - right: objection to marketing
    text: including, at any time, to marketing outreach (direct marketing)
  - right: complaint to CNIL
    text: You may lodge a complaint with the CNIL ( www.cnil.fr ).
  role:
    text: Atako is the controller of the data required to manage its customers, prospective customers, and visitors, as described in Section 2. For the data that its customers entrust to their agents, as described in Section 3, Atako acts as a processor
    value: both
  sale_or_sharing:
    stance: prohibited
    text: It does not sell this data, does not use it for its own purposes, and never uses it to train models.
  subprocessors:
    text: The up-to-date list of service providers and their locations is provided upon request to privacy@atako.ai .
    url: null
  transfers:
  - mechanism: SCC
    text: These transfers are governed by the European Commission's Standard Contractual Clauses or, where one applies, by an adequacy decision, together with supplementary measures.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Atako
provenance_date: '2026-11-09'
provider_name: Atako
provider_slug: atako-ai
slug: atako-ai-privacy-policy
source_date: '2026-11-09'
source_filename: atako-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://atako.ai/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Atako\naid: atako-ai\nurl: https://atako.ai/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Atako is the controller of the data required to manage its customers, prospective customers, and visitors,\n    as described in Section 2. For the data that its customers entrust to their agents, as described in Section\n    3, Atako acts as a processor\ndata_categories:\n- category: identifying\n  text: Last name, first name, email address, encrypted password, role, company, job title\n- category: financial\n  text: Stripe transaction and account identifiers, payment history, invoices (no full\
  \ card data is retained by\n    Atako)\n- category: device\n  text: IP address, connection and event logs, suspicious attempts\n- category: behavioral\n  text: Trackers, browsing data, session recordings (inputs masked; on the platform, all page text is masked)\n- category: communication\n  text: Communications and tickets\npurposes:\n- purpose: Account creation and management\n  text: Account creation and management\n- purpose: Support and customer relations\n  text: Support and customer relations\n- purpose: Billing and payment\n  text: Billing and payment\n- purpose: Security and fraud prevention\n  text: Security, fraud prevention, technical logs\n- purpose: Marketing outreach\n  text: Marketing outreach (direct marketing) to professionals and newsletter\n- purpose: Audience measurement\n  text: Audience measurement and improvement of the website and platform\n- purpose: Service improvement\n  text: Improvement of the Service Aggregated usage statistics (number of agents, features\
  \ used, performance), excluding\n    any content processed by the agents\nretention:\n- scope: Agent data\n  period: duration of the contract\n  text: This data is retained for the duration of the contract.\n- scope: Account data\n  period: 3 years after the last activity\n  text: Duration of the account, then 3 years after the last activity\n- scope: Session recordings\n  period: 30 days\n  text: 'session recordings: 30 days'\n- scope: Trackers\n  period: 13 months maximum\n  text: 'Trackers: 13 months maximum'\n- scope: Cookie choice\n  period: 6 months\n  text: your choice is retained for 6 months\nresidency:\n- region: European Union\n  text: Platform data — user accounts, agent names, messages exchanged between users and agents or between agents,\n    session messages, and settings — is hosted in the European Union.\n- region: Outside the EU (agent VMs)\n  text: 'The virtual machines in which the agents run may be located outside the European Union: Atako remains free\n    to choose\
  \ the provider and the region, and the region is not guaranteed.'\ntransfers:\n- mechanism: SCC\n  text: These transfers are governed by the European Commission's Standard Contractual Clauses or, where one applies,\n    by an adequacy decision, together with supplementary measures.\nsubprocessors:\n  url: null\n  text: The up-to-date list of service providers and their locations is provided upon request to privacy@atako.ai\n    .\ndpa:\n  available: true\n  url: null\n  text: the data processing agreement annexed to the Terms of Use and Sale applies.\ndeletion:\n  route: Written erasure request; data erased within 30 days\n  text: Upon a request for erasure, the data is erased within 30 days, unless a legal retention obligation applies.\nrights:\n- right: access\n  text: You have the rights of access, rectification, erasure, restriction of processing, objection\n- right: portability\n  text: data portability, and withdrawal of your consent\n- right: objection to marketing\n  text: including,\
  \ at any time, to marketing outreach (direct marketing)\n- right: complaint to CNIL\n  text: You may lodge a complaint with the CNIL ( www.cnil.fr ).\nsale_or_sharing:\n  stance: prohibited\n  text: It does not sell this data, does not use it for its own purposes, and never uses it to train models.\n"
source_yaml_url: https://artifacts.apis.io/atako-ai/privacy/atako-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from Atako's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Autonomous Agents
- Platform
- Software-as-a-Service
- Workforce
---
