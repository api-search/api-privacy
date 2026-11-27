---
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: the account owner's email address and name; organization legal name and mailing address; billing address
  - category: contact
    text: Customer's website URL(s); subscription tier
  - category: financial
    text: Facet does not receive or store payment card numbers; card and bank data are handled by Stripe, Inc.
  - category: location
    text: Individual visitor IP addresses are not stored, aggregated, or redistributed by Facet.
  - category: behavioral
    text: Facet collects anonymous page-view counts for product-improvement purposes
  - category: device
    text: session activity metadata (sign-in timestamp, IP address at sign-in, user-agent)
  - category: communication
    text: support and sales communications
  - category: professional
    text: Job title, employer on account-owner profile
  deletion:
    route: Email privacy@facet.llc
    text: Where Customer or a data subject requests deletion, Facet deletes the identifiable record from production within thirty (30) days and overwrites backups in the ordinary course within ninety (90) days, except for records subject to legal hold.
  dpa:
    available: true
    text: Customer is the Controller of this data; Facet Processes it on Customer's documented instructions under the Data Processing Agreement v2.1 at facet.llc/legal/dpa.html .
    url: facet.llc/legal/dpa.html
  purposes:
  - purpose: Operating the Services
    text: Operating the Services (authentication, routing, metering, signing, provenance generation)
  - purpose: Billing and tax recordkeeping
    text: Billing, tax recordkeeping, and financial-regulatory compliance
  - purpose: Security and anti-abuse
    text: Security, anti-abuse, fraud prevention, and platform integrity
  - purpose: Support
    text: Support and Customer success
  - purpose: Product improvement
    text: Product improvement using Aggregated or de-identified data only
  residency:
  - region: United States
    text: Facet's primary Processing location is the United States
  retention:
  - period: Seven (7) years after event
    scope: Audit logs
    text: Audit logs (admin sign-ins, configuration changes, key rotations, signature operations) Seven (7) years after event
  - period: Ninety (90) days
    scope: Raw agent-call metadata
    text: Raw agent-call metadata Ninety (90) days
  - period: Three (3) years after close
    scope: Support conversations
    text: Support conversations Three (3) years after close
  - period: Thirty (30) days rolling, then overwritten
    scope: Backups
    text: Backups Thirty (30) days rolling, then overwritten
  rights:
  - right: Access
    text: Obtain confirmation that we Process Personal Data about you, a copy of the Personal Data, and information about the Processing.
  - right: Rectification
    text: Have inaccurate Personal Data corrected or incomplete data completed.
  - right: Erasure
    text: Erasure / deletion (GDPR Art. 17; CCPA § 1798.105; state-law analogues, subject to exceptions).
  - right: Portability
    text: Receive Personal Data you provided in a structured, commonly used, machine-readable format and transmit it to another Controller.
  - right: Objection
    text: Object to Processing based on Art. 6(1)(e) or (f), including profiling
  - right: Withdrawal of consent
    text: Where Processing is based on Art. 6(1)(a) consent, withdraw at any time without affecting lawfulness of prior Processing.
  - right: Appeal
    text: Residents of Virginia, Colorado, Connecticut, Oregon, Texas, Montana, New Hampshire, New Jersey, Minnesota, Maryland, Tennessee, Iowa, Indiana, Delaware, Rhode Island, and Kentucky may additionally exercise the statutory appeal mechanism
  role:
    text: 'Facet acts in two distinct roles: Controller , for Facet''s own commercial-relationship data'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Facet does not sell Personal Information within the meaning of CCPA § 1798.140(ad)
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: EU Standard Contractual Clauses. The European Commission's Standard Contractual Clauses adopted by Implementing Decision (EU) 2021/914 of 4 June 2021
  - mechanism: DPF
    text: EU-US Data Privacy Framework. For Personal Data transferred to U.S. subprocessors that have self-certified
  - mechanism: adequacy
    text: Where an adequacy decision applies to a destination (for example, Japan private-sector adequacy, Republic of Korea adequacy, UK adequacy for Swiss/EU exports), Facet relies on the adequacy decision.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Facet
provenance_date: '2026-11-09'
provider_name: Facet
provider_slug: facet-llc
slug: facet-llc-privacy-policy
source_date: '2026-11-09'
source_filename: facet-llc-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://facet.llc/legal/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Facet\naid: facet-llc\nurl: https://facet.llc/legal/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Facet acts in two distinct roles: Controller , for Facet''s own commercial-relationship data'\ndata_categories:\n- category: identifying\n  text: the account owner's email address and name; organization legal name and mailing address; billing address\n- category: contact\n  text: Customer's website URL(s); subscription tier\n- category: financial\n  text: Facet does not receive or store payment card numbers; card and bank data are handled by Stripe, Inc.\n- category: location\n  text:\
  \ Individual visitor IP addresses are not stored, aggregated, or redistributed by Facet.\n- category: behavioral\n  text: Facet collects anonymous page-view counts for product-improvement purposes\n- category: device\n  text: session activity metadata (sign-in timestamp, IP address at sign-in, user-agent)\n- category: communication\n  text: support and sales communications\n- category: professional\n  text: Job title, employer on account-owner profile\npurposes:\n- purpose: Operating the Services\n  text: Operating the Services (authentication, routing, metering, signing, provenance generation)\n- purpose: Billing and tax recordkeeping\n  text: Billing, tax recordkeeping, and financial-regulatory compliance\n- purpose: Security and anti-abuse\n  text: Security, anti-abuse, fraud prevention, and platform integrity\n- purpose: Support\n  text: Support and Customer success\n- purpose: Product improvement\n  text: Product improvement using Aggregated or de-identified data only\nretention:\n\
  - scope: Audit logs\n  period: Seven (7) years after event\n  text: Audit logs (admin sign-ins, configuration changes, key rotations, signature operations) Seven (7) years\n    after event\n- scope: Raw agent-call metadata\n  period: Ninety (90) days\n  text: Raw agent-call metadata Ninety (90) days\n- scope: Support conversations\n  period: Three (3) years after close\n  text: Support conversations Three (3) years after close\n- scope: Backups\n  period: Thirty (30) days rolling, then overwritten\n  text: Backups Thirty (30) days rolling, then overwritten\nresidency:\n- region: United States\n  text: Facet's primary Processing location is the United States\ntransfers:\n- mechanism: SCC\n  text: EU Standard Contractual Clauses. The European Commission's Standard Contractual Clauses adopted by Implementing\n    Decision (EU) 2021/914 of 4 June 2021\n- mechanism: DPF\n  text: EU-US Data Privacy Framework. For Personal Data transferred to U.S. subprocessors that have self-certified\n- mechanism:\
  \ adequacy\n  text: Where an adequacy decision applies to a destination (for example, Japan private-sector adequacy, Republic\n    of Korea adequacy, UK adequacy for Swiss/EU exports), Facet relies on the adequacy decision.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: facet.llc/legal/dpa.html\n  text: Customer is the Controller of this data; Facet Processes it on Customer's documented instructions under\n    the Data Processing Agreement v2.1 at facet.llc/legal/dpa.html .\ndeletion:\n  route: Email privacy@facet.llc\n  text: Where Customer or a data subject requests deletion, Facet deletes the identifiable record from production\n    within thirty (30) days and overwrites backups in the ordinary course within ninety (90) days, except for records\n    subject to legal hold.\nrights:\n- right: Access\n  text: Obtain confirmation that we Process Personal Data about you, a copy of the Personal Data, and information\n    about the Processing.\n- right: Rectification\n\
  \  text: Have inaccurate Personal Data corrected or incomplete data completed.\n- right: Erasure\n  text: Erasure / deletion (GDPR Art. 17; CCPA § 1798.105; state-law analogues, subject to exceptions).\n- right: Portability\n  text: Receive Personal Data you provided in a structured, commonly used, machine-readable format and transmit\n    it to another Controller.\n- right: Objection\n  text: Object to Processing based on Art. 6(1)(e) or (f), including profiling\n- right: Withdrawal of consent\n  text: Where Processing is based on Art. 6(1)(a) consent, withdraw at any time without affecting lawfulness of\n    prior Processing.\n- right: Appeal\n  text: Residents of Virginia, Colorado, Connecticut, Oregon, Texas, Montana, New Hampshire, New Jersey, Minnesota,\n    Maryland, Tennessee, Iowa, Indiana, Delaware, Rhode Island, and Kentucky may additionally exercise the statutory\n    appeal mechanism\nsale_or_sharing:\n  stance: prohibited\n  text: Facet does not sell Personal Information\
  \ within the meaning of CCPA § 1798.140(ad)\n"
source_yaml_url: https://artifacts.apis.io/facet-llc/privacy/facet-llc-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 32 quoted statements, read from Facet's own page on 2026-11-09.
synthetic: false
tags:
- Commerce
- Payments
- Artificial Intelligence
- Agentic Commerce
- Marketplace
---
