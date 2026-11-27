---
api_specs:
- filename: aderlo-cloud-api-openapi.json
  format: json
  label: Aderlo Cloud public API API
  slug: aderlo-cloud-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aderlo-cloud/openapi/_original/aderlo-cloud-api-openapi.json
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identification data: first name, last name, company name,'
  - category: contact
    text: 'Contact data: e-mail address, phone number, Address data: residential / business address,'
  - category: financial
    text: 'Billing data: tax ID, invoice data (bill_to snapshot), payment history (no card numbers — stored exclusively by Stripe),'
  - category: device
    text: 'Technical data: IP address, session ID, browser information (user agent),'
  - category: behavioral
    text: Email delivery events (including opens and clicks)
  deletion:
    route: Request to support@aderlo.cloud
    text: 'Requests should be sent to: support@aderlo.cloud .'
  dpa:
    available: true
    text: Data Processing Agreement (DPA) , which forms an annex to the Terms of Service.
    url: null
  purposes:
  - purpose: Performance of hosting service agreement
    text: 'Purpose: account registration, service activation, service management, technical support, communication.'
  - purpose: Legal obligations (accounting, tax)
    text: 'Purpose: issuing invoices, maintaining accounting records, KSeF transmission.'
  - purpose: Security and audit logs
    text: 'Purpose: platform security, abuse detection, audit logs (IP addresses, operations performed).'
  - purpose: Direct marketing and newsletter
    text: 'Purpose: sending commercial information, news about services and promotions.'
  residency:
  - region: Germany (EU)
    text: Hetzner Online GmbH Web server (hosting), backup server Falkenstein, Germany (EU)
  - region: Ireland (EU)
    text: Supabase Inc. Client panel database eu-west-1, Ireland (EU)
  retention:
  - period: 5 tax years
    scope: Invoices and accounting documents
    text: Invoices and accounting documents 5 tax years
  - period: 24 months
    scope: Audit logs
    text: Audit logs (audit_log) 24 months
  - period: 12 months
    scope: Server logs
    text: Server logs (access/error) 12 months
  - period: 90 days
    scope: Email delivery events
    text: Email delivery events (including opens and clicks) 90 days
  rights:
  - right: Access
    text: a) Right of access (Article 15),
  - right: Rectification
    text: b) Right to rectification (Article 16),
  - right: Erasure
    text: c) Right to erasure (Article 17),
  - right: Restriction
    text: d) Right to restriction of processing (Article 18),
  - right: Portability
    text: e) Right to data portability (Article 20),
  - right: Object
    text: f) Right to object (Article 21),
  - right: Withdraw consent
    text: g) Right to withdraw consent (Article 7(3)),
  role:
    text: Aderlo as Data Controller — with respect to personal data of Aderlo Cloud platform Clients
    value: both
  sale_or_sharing:
    stance: prohibited
    text: The Controller does not sell personal data to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCC) adopted by the European Commission (Article 46(2)(c) GDPR)
  - mechanism: DPF
    text: including EU-US Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Aderlo Cloud
provenance_date: '2026-11-09'
provider_name: Aderlo Cloud
provider_slug: aderlo-cloud
slug: aderlo-cloud-privacy-policy
source_date: '2026-11-09'
source_filename: aderlo-cloud-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aderlo.cloud/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Aderlo Cloud\naid: aderlo-cloud\nurl: https://aderlo.cloud/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Aderlo as Data Controller — with respect to personal data of Aderlo Cloud platform Clients\ndata_categories:\n- category: identifying\n  text: 'Identification data: first name, last name, company name,'\n- category: contact\n  text: 'Contact data: e-mail address, phone number, Address data: residential / business address,'\n- category: financial\n  text: 'Billing data: tax ID, invoice data (bill_to snapshot), payment history (no card numbers — stored exclusively\n    by Stripe),'\n-\
  \ category: device\n  text: 'Technical data: IP address, session ID, browser information (user agent),'\n- category: behavioral\n  text: Email delivery events (including opens and clicks)\npurposes:\n- purpose: Performance of hosting service agreement\n  text: 'Purpose: account registration, service activation, service management, technical support, communication.'\n- purpose: Legal obligations (accounting, tax)\n  text: 'Purpose: issuing invoices, maintaining accounting records, KSeF transmission.'\n- purpose: Security and audit logs\n  text: 'Purpose: platform security, abuse detection, audit logs (IP addresses, operations performed).'\n- purpose: Direct marketing and newsletter\n  text: 'Purpose: sending commercial information, news about services and promotions.'\nretention:\n- scope: Invoices and accounting documents\n  period: 5 tax years\n  text: Invoices and accounting documents 5 tax years\n- scope: Audit logs\n  period: 24 months\n  text: Audit logs (audit_log) 24 months\n- scope:\
  \ Server logs\n  period: 12 months\n  text: Server logs (access/error) 12 months\n- scope: Email delivery events\n  period: 90 days\n  text: Email delivery events (including opens and clicks) 90 days\nresidency:\n- region: Germany (EU)\n  text: Hetzner Online GmbH Web server (hosting), backup server Falkenstein, Germany (EU)\n- region: Ireland (EU)\n  text: Supabase Inc. Client panel database eu-west-1, Ireland (EU)\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCC) adopted by the European Commission (Article 46(2)(c) GDPR)\n- mechanism: DPF\n  text: including EU-US Data Privacy Framework\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Data Processing Agreement (DPA) , which forms an annex to the Terms of Service.\ndeletion:\n  route: Request to support@aderlo.cloud\n  text: 'Requests should be sent to: support@aderlo.cloud .'\nrights:\n- right: Access\n  text: a) Right of access (Article 15),\n- right: Rectification\n  text:\
  \ b) Right to rectification (Article 16),\n- right: Erasure\n  text: c) Right to erasure (Article 17),\n- right: Restriction\n  text: d) Right to restriction of processing (Article 18),\n- right: Portability\n  text: e) Right to data portability (Article 20),\n- right: Object\n  text: f) Right to object (Article 21),\n- right: Withdraw consent\n  text: g) Right to withdraw consent (Article 7(3)),\nsale_or_sharing:\n  stance: prohibited\n  text: The Controller does not sell personal data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/aderlo-cloud/privacy/aderlo-cloud-privacy-policy.yml
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
summary_line: 28 quoted statements, read from Aderlo Cloud's own page on 2026-11-09.
synthetic: false
tags:
- Hosting
- WooCommerce
- WordPress
- EU
- Managed
- Cloud
---
