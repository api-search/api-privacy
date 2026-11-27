---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, work email, company, password (hashed), role
  - category: financial
    text: Billing contact, plan, invoices, tax details; card data is handled by our payment processor, not stored by Keld
  - category: location
    text: approximate location from IP
  - category: device
    text: browser/device, analytics events (only with consent)
  - category: behavioral
    text: Pages viewed
  - category: communication
    text: Messages to us, support tickets, sales enquiries, job applications
  - category: professional
    text: Name, work email, company, password (hashed), role
  deletion:
    route: Email request to privacy contact
    text: To exercise any of these, email [email protected] .
  dpa:
    available: true
    text: This payload data is governed by the customer's agreement with Keld and our Data Processing Agreement
    url: null
  purposes:
  - purpose: Account creation and service provision
    text: Create and secure your account; authenticate you; provide the service
  - purpose: Billing and fraud prevention
    text: Take payment, prevent fraud, meet tax/accounting duties
  - purpose: Marketplace operation
    text: Match and clear orders, show you spend and savings, run the marketplace
  - purpose: Site security and improvement
    text: Operate, secure and improve the site and console
  - purpose: Marketing
    text: Send updates you asked for; you can opt out anytime
  residency:
  - region: United States
    text: Keld is based in the United States
  retention:
  - period: null
    scope: Inference payloads
    text: Payloads are not retained after a job completes (Zero Data Retention).
  - period: seven years
    scope: Billing and tax records
    text: As a guide, we keep billing and tax records for seven years
  - period: up to 24 months
    scope: Inactive marketing contacts
    text: inactive marketing contacts for up to 24 months
  rights:
  - right: access
    text: you may have the right to access your data, correct it, delete it, object to or restrict processing, port it, and withdraw consent
  - right: know, delete, correct (California)
    text: You have the right to know, delete, correct and to non-discrimination for exercising these rights.
  role:
    text: For this data, Keld is the controller , we decide why and how it's used, and this Notice governs it.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Keld does not sell your personal information and does not share it for cross-context behavioral advertising.
  subprocessors:
    text: The current list, with name, purpose and location, is published at keld.co/subprocessors , and we email customers 30 days before we add or replace a sub-processor.
    url: https://keld.co/subprocessors
  transfers:
  - mechanism: SCC
    text: The European Commission's Standard Contractual Clauses , and the UK International Data Transfer Addendum for UK data
  - mechanism: DPF
    text: Keld is not currently certified under the EU-US or UK Data Privacy Framework; transfers rely on the safeguards above.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Keld
provenance_date: '2026-11-09'
provider_name: Keld
provider_slug: keld
slug: keld-privacy-policy
source_date: '2026-11-09'
source_filename: keld-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://keld.co/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Keld\naid: keld\nurl: https://keld.co/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For this data, Keld is the controller , we decide why and how it's used, and this Notice governs it.\ndata_categories:\n- category: identifying\n  text: Name, work email, company, password (hashed), role\n- category: financial\n  text: Billing contact, plan, invoices, tax details; card data is handled by our payment processor, not stored\n    by Keld\n- category: location\n  text: approximate location from IP\n- category: device\n  text: browser/device, analytics events (only with consent)\n- category: behavioral\n\
  \  text: Pages viewed\n- category: communication\n  text: Messages to us, support tickets, sales enquiries, job applications\n- category: professional\n  text: Name, work email, company, password (hashed), role\npurposes:\n- purpose: Account creation and service provision\n  text: Create and secure your account; authenticate you; provide the service\n- purpose: Billing and fraud prevention\n  text: Take payment, prevent fraud, meet tax/accounting duties\n- purpose: Marketplace operation\n  text: Match and clear orders, show you spend and savings, run the marketplace\n- purpose: Site security and improvement\n  text: Operate, secure and improve the site and console\n- purpose: Marketing\n  text: Send updates you asked for; you can opt out anytime\nretention:\n- scope: Inference payloads\n  period: null\n  text: Payloads are not retained after a job completes (Zero Data Retention).\n- scope: Billing and tax records\n  period: seven years\n  text: As a guide, we keep billing and tax records\
  \ for seven years\n- scope: Inactive marketing contacts\n  period: up to 24 months\n  text: inactive marketing contacts for up to 24 months\nresidency:\n- region: United States\n  text: Keld is based in the United States\ntransfers:\n- mechanism: SCC\n  text: The European Commission's Standard Contractual Clauses , and the UK International Data Transfer Addendum\n    for UK data\n- mechanism: DPF\n  text: Keld is not currently certified under the EU-US or UK Data Privacy Framework; transfers rely on the safeguards\n    above.\nsubprocessors:\n  url: https://keld.co/subprocessors\n  text: The current list, with name, purpose and location, is published at keld.co/subprocessors , and we email\n    customers 30 days before we add or replace a sub-processor.\ndpa:\n  available: true\n  url: null\n  text: This payload data is governed by the customer's agreement with Keld and our Data Processing Agreement\ndeletion:\n  route: Email request to privacy contact\n  text: To exercise any of these,\
  \ email [email protected] .\nrights:\n- right: access\n  text: you may have the right to access your data, correct it, delete it, object to or restrict processing, port\n    it, and withdraw consent\n- right: know, delete, correct (California)\n  text: You have the right to know, delete, correct and to non-discrimination for exercising these rights.\nsale_or_sharing:\n  stance: prohibited\n  text: Keld does not sell your personal information and does not share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/keld/privacy/keld-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Keld's own page on 2026-11-09.
synthetic: false
tags:
- Inference
- Marketplace
- Model Marketplace
- Enterprise AI
---
