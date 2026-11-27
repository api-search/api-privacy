---
api_specs:
- filename: crela-io-openapi-generated.yml
  format: yaml
  label: Crela API
  slug: crela-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crela-io/openapi/_ae-authored/crela-io-openapi-generated.yml
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: email address password (hashed, never stored in plaintext)
  - category: contact
    text: name and billing address (for invoicing, VAT calculation and sanctions screening, section 5.9)
  - category: financial
    text: payment status (no direct storage of credit card data - exclusively processed by Stripe)
  - category: location
    text: the country of your IP address, as evidence of where you live
  - category: device
    text: device fingerprint (a hash of hardware characteristics; no directly identifying data)
  - category: behavioral
    text: we store how long it ran, how it ended (exit code) and its version, linked to your account
  deletion:
    route: Settings (Delete account) or email to privacy@crela.io
    text: You can delete your account at any time under Settings (Delete account), or ask us to delete it by writing to privacy@crela.io
  dpa:
    available: true
    text: Unless noted otherwise, they process personal data on our behalf under a data processing agreement pursuant to Art. 28 GDPR
    url: null
  purposes:
  - purpose: Authentication and platform features
    text: Authentication, provision of platform features (purchases, reviews, etc.)
  - purpose: Security analyses
    text: Delivery of the website, security analyses (defense against attacks)
  - purpose: Tax and accounting obligations
    text: Contract performance, invoicing, fulfillment of commercial and tax obligations.
  - purpose: Reach measurement
    text: reach and performance analysis (aggregated statistics)
  residency:
  - region: EU (Ireland) for database
    text: Data stored in the EU (Ireland); access from outside the EU (Singapore, USA) possible
  - region: Germany for server hosting
    text: stored within the server environment of our hosting provider (netcup, Germany)
  retention:
  - period: until your account is deleted
    scope: Account data
    text: 'Retention period : until your account is deleted.'
  - period: 10 years
    scope: Purchase and tax records
    text: Records of purchases, refunds, chargebacks and payouts are part of our books and tax records and are kept for 10 years
  - period: less than one day
    scope: Web server access logs
    text: access logs are kept for less than one day at current traffic
  - period: 30 days
    scope: Error reports
    text: 'Retention period : 30 days, then automatic deletion.'
  rights:
  - right: Access
    text: Right of access (Art. 15 GDPR)
  - right: Rectification
    text: Right to rectification (Art. 16 GDPR)
  - right: Erasure
    text: Right to erasure (Art. 17 GDPR)
  - right: Restriction
    text: Right to restriction of processing (Art. 18 GDPR)
  - right: Portability
    text: Right to data portability (Art. 20 GDPR)
  - right: Objection
    text: Right to object (Art. 21 GDPR)
  - right: Withdraw consent
    text: Right to withdraw consent (Art. 7 (3) GDPR)
  role:
    text: 'The controller within the meaning of Art. 4 (7) GDPR is: Crela UG (haftungsbeschränkt)'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: We use the following processors. Unless noted otherwise, they process personal data on our behalf under a data processing agreement pursuant to Art. 28 GDPR
    url: null
  transfers:
  - mechanism: DPF
    text: to recipients in the USA who are certified under the EU-US Data Privacy Framework (EU-US DPF; adequacy decision (EU) 2023/1795)
  - mechanism: SCC
    text: on the basis of the EU Standard Contractual Clauses (SCC, Art. 46 (2) (c) GDPR, decision (EU) 2021/914) in the data processing agreement of the provider
  - mechanism: adequacy
    text: to recipients in countries with an adequacy decision (Art. 45 GDPR)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Crela
provenance_date: '2026-11-09'
provider_name: Crela
provider_slug: crela-io
slug: crela-io-privacy-policy
source_date: '2026-11-09'
source_filename: crela-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://crela.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Crela\naid: crela-io\nurl: https://crela.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The controller within the meaning of Art. 4 (7) GDPR is: Crela UG (haftungsbeschränkt)'\ndata_categories:\n- category: identifying\n  text: email address password (hashed, never stored in plaintext)\n- category: contact\n  text: name and billing address (for invoicing, VAT calculation and sanctions screening, section 5.9)\n- category: financial\n  text: payment status (no direct storage of credit card data - exclusively processed by Stripe)\n- category: location\n  text: the country of your\
  \ IP address, as evidence of where you live\n- category: device\n  text: device fingerprint (a hash of hardware characteristics; no directly identifying data)\n- category: behavioral\n  text: we store how long it ran, how it ended (exit code) and its version, linked to your account\npurposes:\n- purpose: Authentication and platform features\n  text: Authentication, provision of platform features (purchases, reviews, etc.)\n- purpose: Security analyses\n  text: Delivery of the website, security analyses (defense against attacks)\n- purpose: Tax and accounting obligations\n  text: Contract performance, invoicing, fulfillment of commercial and tax obligations.\n- purpose: Reach measurement\n  text: reach and performance analysis (aggregated statistics)\nretention:\n- scope: Account data\n  period: until your account is deleted\n  text: 'Retention period : until your account is deleted.'\n- scope: Purchase and tax records\n  period: 10 years\n  text: Records of purchases, refunds, chargebacks\
  \ and payouts are part of our books and tax records and are kept\n    for 10 years\n- scope: Web server access logs\n  period: less than one day\n  text: access logs are kept for less than one day at current traffic\n- scope: Error reports\n  period: 30 days\n  text: 'Retention period : 30 days, then automatic deletion.'\nresidency:\n- region: EU (Ireland) for database\n  text: Data stored in the EU (Ireland); access from outside the EU (Singapore, USA) possible\n- region: Germany for server hosting\n  text: stored within the server environment of our hosting provider (netcup, Germany)\ntransfers:\n- mechanism: DPF\n  text: to recipients in the USA who are certified under the EU-US Data Privacy Framework (EU-US DPF; adequacy decision\n    (EU) 2023/1795)\n- mechanism: SCC\n  text: on the basis of the EU Standard Contractual Clauses (SCC, Art. 46 (2) (c) GDPR, decision (EU) 2021/914)\n    in the data processing agreement of the provider\n- mechanism: adequacy\n  text: to recipients in countries\
  \ with an adequacy decision (Art. 45 GDPR)\nsubprocessors:\n  url: null\n  text: We use the following processors. Unless noted otherwise, they process personal data on our behalf under\n    a data processing agreement pursuant to Art. 28 GDPR\ndpa:\n  available: true\n  url: null\n  text: Unless noted otherwise, they process personal data on our behalf under a data processing agreement pursuant\n    to Art. 28 GDPR\ndeletion:\n  route: Settings (Delete account) or email to privacy@crela.io\n  text: You can delete your account at any time under Settings (Delete account), or ask us to delete it by writing\n    to privacy@crela.io\nrights:\n- right: Access\n  text: Right of access (Art. 15 GDPR)\n- right: Rectification\n  text: Right to rectification (Art. 16 GDPR)\n- right: Erasure\n  text: Right to erasure (Art. 17 GDPR)\n- right: Restriction\n  text: Right to restriction of processing (Art. 18 GDPR)\n- right: Portability\n  text: Right to data portability (Art. 20 GDPR)\n- right: Objection\n\
  \  text: Right to object (Art. 21 GDPR)\n- right: Withdraw consent\n  text: Right to withdraw consent (Art. 7 (3) GDPR)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/crela-io/privacy/crela-io-privacy-policy.yml
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
summary_line: 30 quoted statements, read from Crela's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software Marketplace
- Desktop Software
- Independent Creators
- Software Distribution
- Security Review
- MCP
- REST API
---
