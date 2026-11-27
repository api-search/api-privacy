---
api_specs:
- filename: agent4-io-api-openapi.json
  format: json
  label: chatagent-platform Api API
  slug: chatagent-platform-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agent4-io/openapi/_original/agent4-io-api-openapi.json
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, password (stored only as a salted hash), preferred language, and any organisation details you provide.
  - category: financial
    text: Plan, subscription status, billing period, invoices and payment history.
  - category: device
    text: Token consumption against your quota, request volumes, feature usage, and the diagnostic records needed to operate the service (timestamps, IP address, user agent, error traces).
  - category: communication
    text: Messages you send us, and records of support and sales correspondence.
  - category: behavioral
    text: Knowledge base content — documents and text a customer uploads for their agents to answer from.
  - category: contact
    text: any contact details their agent is configured to collect
  deletion:
    route: Write to contact@agent4.io
    text: Write to contact@agent4.io .
  dpa:
    available: true
    text: Business customers subject to the GDPR or UK GDPR can request a Data Processing Agreement, including standard contractual clauses
    url: null
  purposes:
  - purpose: Providing the service
    text: Providing the service you signed up for Performance of a contract
  - purpose: Billing and invoicing
    text: Billing, invoicing and collecting payment Performance of a contract
  - purpose: Security and abuse prevention
    text: Security, abuse prevention, service integrity Legitimate interests
  - purpose: Product analytics and improvement
    text: Product analytics and improvement Legitimate interests
  - purpose: Marketing email
    text: Marketing email Consent, withdrawable at any time
  residency:
  - region: United States (us-west-2, Oregon)
    text: the platform is currently hosted on Amazon Web Services in the us-west-2 region (Oregon, United States)
  retention:
  - period: deleted or anonymised within 90 days of closure
    scope: Account data
    text: While the account exists, then deleted or anonymised within 90 days of closure
  - period: 30 days after account closure
    scope: Customer content
    text: Until the customer deletes it, or 30 days after account closure
  - period: 6–7 years
    scope: Billing and tax records
    text: As long as tax and accounting law requires, typically 6–7 years
  - period: up to 12 months
    scope: Security and diagnostic records
    text: Typically up to 12 months
  rights:
  - right: access
    text: access; correction; erasure; restriction of processing; portability in a machine-readable format
  - right: objection
    text: objection to processing based on legitimate interests
  - right: withdrawal of consent
    text: withdrawal of consent where consent was the basis
  role:
    text: We are the controller of data about our own customers
    value: both
  sale_or_sharing:
    stance: prohibited
    text: we do not sell or share personal information as those terms are defined
  subprocessors:
    text: A current list, and notice of changes, is available at contact@agent4.io .
    url: null
  transfers:
  - mechanism: SCC
    text: These transfers are made under the European Commission's standard contractual clauses — incorporated into the AWS GDPR Data Processing Addendum
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agent4.io
provenance_date: '2026-11-09'
provider_name: Agent4.io
provider_slug: agent4-io
slug: agent4-io-privacy-policy
source_date: '2026-11-09'
source_filename: agent4-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agent4.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agent4.io\naid: agent4-io\nurl: https://agent4.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are the controller of data about our own customers\ndata_categories:\n- category: identifying\n  text: Name, email address, password (stored only as a salted hash), preferred language, and any organisation details\n    you provide.\n- category: financial\n  text: Plan, subscription status, billing period, invoices and payment history.\n- category: device\n  text: Token consumption against your quota, request volumes, feature usage, and the diagnostic records needed\n    to operate the service\
  \ (timestamps, IP address, user agent, error traces).\n- category: communication\n  text: Messages you send us, and records of support and sales correspondence.\n- category: behavioral\n  text: Knowledge base content — documents and text a customer uploads for their agents to answer from.\n- category: contact\n  text: any contact details their agent is configured to collect\npurposes:\n- purpose: Providing the service\n  text: Providing the service you signed up for Performance of a contract\n- purpose: Billing and invoicing\n  text: Billing, invoicing and collecting payment Performance of a contract\n- purpose: Security and abuse prevention\n  text: Security, abuse prevention, service integrity Legitimate interests\n- purpose: Product analytics and improvement\n  text: Product analytics and improvement Legitimate interests\n- purpose: Marketing email\n  text: Marketing email Consent, withdrawable at any time\nretention:\n- scope: Account data\n  period: deleted or anonymised within 90\
  \ days of closure\n  text: While the account exists, then deleted or anonymised within 90 days of closure\n- scope: Customer content\n  period: 30 days after account closure\n  text: Until the customer deletes it, or 30 days after account closure\n- scope: Billing and tax records\n  period: 6–7 years\n  text: As long as tax and accounting law requires, typically 6–7 years\n- scope: Security and diagnostic records\n  period: up to 12 months\n  text: Typically up to 12 months\nresidency:\n- region: United States (us-west-2, Oregon)\n  text: the platform is currently hosted on Amazon Web Services in the us-west-2 region (Oregon, United States)\ntransfers:\n- mechanism: SCC\n  text: These transfers are made under the European Commission's standard contractual clauses — incorporated into\n    the AWS GDPR Data Processing Addendum\nsubprocessors:\n  url: null\n  text: A current list, and notice of changes, is available at contact@agent4.io .\ndpa:\n  available: true\n  url: null\n  text: Business\
  \ customers subject to the GDPR or UK GDPR can request a Data Processing Agreement, including standard\n    contractual clauses\ndeletion:\n  route: Write to contact@agent4.io\n  text: Write to contact@agent4.io .\nrights:\n- right: access\n  text: access; correction; erasure; restriction of processing; portability in a machine-readable format\n- right: objection\n  text: objection to processing based on legitimate interests\n- right: withdrawal of consent\n  text: withdrawal of consent where consent was the basis\nsale_or_sharing:\n  stance: prohibited\n  text: we do not sell or share personal information as those terms are defined\n"
source_yaml_url: https://artifacts.apis.io/agent4-io/privacy/agent4-io-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Agent4.io's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Customer Engagement
- Software-as-a-Service
- Agent Platform
---
