---
api_specs:
- filename: etlworks-openapi-generated.yml
  format: yaml
  label: Etlworks API
  slug: etlworks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/etlworks/openapi/_ae-authored/etlworks-openapi-generated.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: contact
    text: name, work email, company name, job title (when you submit a form, request a demo, or sign up for a trial)
  - category: device
    text: IP address, device type, browser type, pages visited, referring URL, time on page
  - category: financial
    text: 'Billing data: company billing details, invoices, payment history.'
  - category: professional
    text: 'Account data: name, email, company, role, password (hashed, so we can''t see it).'
  - category: communication
    text: 'Support data: the contents of support tickets you open and the conversations that follow.'
  deletion:
    route: Email legal@etlworks.com to exercise any of these rights.
    text: Delete your data (subject to legal retention requirements like billing records).
  dpa:
    available: true
    text: If you're an enterprise customer, see our Data Processing Addendum (DPA), or request a counter-signed copy at legal@etlworks.com .
    url: null
  purposes:
  - purpose: Provide the service
    text: Provide the service. Run the platform, process your payments, deliver support.
  - purpose: Improve the service
    text: Improve the service. Aggregate usage data tells us which features matter and which don't.
  - purpose: Security and fraud prevention
    text: Stay secure. Detect fraud, prevent abuse, investigate security incidents.
  - purpose: Legal obligations
    text: Meet legal obligations. Tax records, regulatory requests, court orders.
  residency:
  - region: US
    text: Marketing website data is stored in the US.
  - region: Enterprise region of choice
    text: Enterprise plans run on a dedicated instance in the region you choose.
  retention:
  - period: 14 months
    scope: Marketing website analytics
    text: Marketing website analytics 14 months (Google Analytics default), then aggregated
  - period: 24 months from last contact
    scope: Sales inquiry data
    text: Sales inquiry data 24 months from last contact, then deleted unless you become a customer
  - period: 30 days after account closure
    scope: Customer account data
    text: Customer account data Active for the life of the account; deleted 30 days after account closure
  - period: 36 months from ticket close
    scope: Support tickets
    text: Support tickets 36 months from ticket close
  - period: 7 years
    scope: Billing records
    text: Billing records 7 years (legal requirement)
  - period: 30 days rolling
    scope: Backup snapshots
    text: Backup snapshots 30 days rolling
  rights:
  - right: Access
    text: Access the data we hold about you.
  - right: Correct
    text: Correct data that's inaccurate.
  - right: Export
    text: Export your data in a portable format.
  - right: Object
    text: Object to our processing of your data.
  - right: Restrict processing (GDPR)
    text: Restrict our processing of your data in certain circumstances.
  - right: Data portability (GDPR)
    text: 'Data portability: receive your data in a machine-readable format.'
  role:
    text: 'This policy covers personal data we collect through: Our marketing website at etlworks.com'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Specifically, we don't sell your data, train AI models on it (including our own AI agent), share it with third parties beyond our published sub-processors, or access it without your permission.
  subprocessors:
    text: 'We use a small set of trusted third parties to deliver the service. The current list:'
    url: null
  transfers:
  - mechanism: SCC
    text: For transfers from the EU, UK, or Switzerland, we rely on Standard Contractual Clauses (SCCs) approved by the European Commission, available as part of our DPA.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Etlworks
provenance_date: '2026-11-09'
provider_name: Etlworks
provider_slug: etlworks
slug: etlworks-privacy-policy
source_date: '2026-11-09'
source_filename: etlworks-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://etlworks.com/privacy-policy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Etlworks\naid: etlworks\nurl: https://etlworks.com/privacy-policy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'This policy covers personal data we collect through: Our marketing website at etlworks.com'\ndata_categories:\n- category: contact\n  text: name, work email, company name, job title (when you submit a form, request a demo, or sign up for a trial)\n- category: device\n  text: IP address, device type, browser type, pages visited, referring URL, time on page\n- category: financial\n  text: 'Billing data: company billing details, invoices, payment history.'\n- category: professional\n\
  \  text: 'Account data: name, email, company, role, password (hashed, so we can''t see it).'\n- category: communication\n  text: 'Support data: the contents of support tickets you open and the conversations that follow.'\npurposes:\n- purpose: Provide the service\n  text: Provide the service. Run the platform, process your payments, deliver support.\n- purpose: Improve the service\n  text: Improve the service. Aggregate usage data tells us which features matter and which don't.\n- purpose: Security and fraud prevention\n  text: Stay secure. Detect fraud, prevent abuse, investigate security incidents.\n- purpose: Legal obligations\n  text: Meet legal obligations. Tax records, regulatory requests, court orders.\nretention:\n- scope: Marketing website analytics\n  period: 14 months\n  text: Marketing website analytics 14 months (Google Analytics default), then aggregated\n- scope: Sales inquiry data\n  period: 24 months from last contact\n  text: Sales inquiry data 24 months from last contact,\
  \ then deleted unless you become a customer\n- scope: Customer account data\n  period: 30 days after account closure\n  text: Customer account data Active for the life of the account; deleted 30 days after account closure\n- scope: Support tickets\n  period: 36 months from ticket close\n  text: Support tickets 36 months from ticket close\n- scope: Billing records\n  period: 7 years\n  text: Billing records 7 years (legal requirement)\n- scope: Backup snapshots\n  period: 30 days rolling\n  text: Backup snapshots 30 days rolling\nresidency:\n- region: US\n  text: Marketing website data is stored in the US.\n- region: Enterprise region of choice\n  text: Enterprise plans run on a dedicated instance in the region you choose.\ntransfers:\n- mechanism: SCC\n  text: For transfers from the EU, UK, or Switzerland, we rely on Standard Contractual Clauses (SCCs) approved by\n    the European Commission, available as part of our DPA.\nsubprocessors:\n  url: null\n  text: 'We use a small set of trusted\
  \ third parties to deliver the service. The current list:'\ndpa:\n  available: true\n  url: null\n  text: If you're an enterprise customer, see our Data Processing Addendum (DPA), or request a counter-signed copy\n    at legal@etlworks.com .\ndeletion:\n  route: Email legal@etlworks.com to exercise any of these rights.\n  text: Delete your data (subject to legal retention requirements like billing records).\nrights:\n- right: Access\n  text: Access the data we hold about you.\n- right: Correct\n  text: Correct data that's inaccurate.\n- right: Export\n  text: Export your data in a portable format.\n- right: Object\n  text: Object to our processing of your data.\n- right: Restrict processing (GDPR)\n  text: Restrict our processing of your data in certain circumstances.\n- right: Data portability (GDPR)\n  text: 'Data portability: receive your data in a machine-readable format.'\nsale_or_sharing:\n  stance: prohibited\n  text: Specifically, we don't sell your data, train AI models on it\
  \ (including our own AI agent), share it with\n    third parties beyond our published sub-processors, or access it without your permission.\n"
source_yaml_url: https://artifacts.apis.io/etlworks/privacy/etlworks-privacy-policy.yml
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
summary_line: 29 quoted statements, read from Etlworks's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Integration
- ETL
- Cloud
---
