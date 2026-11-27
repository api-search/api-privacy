---
api_specs:
- filename: capable-run-openapi-generated.yml
  format: yaml
  label: Capable API
  slug: capable-run-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capable-run/openapi/_ae-authored/capable-run-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email, profile image, organisation, role
  - category: financial
    text: Billing Plan, billing contact, billing address, VAT / tax IDs, invoices, payment status
  - category: communication
    text: Transcripts and recording links from the meeting recorder
  - category: behavioral
    text: Cookieless, metadata-minimized usage signals — for example which MCP tool was called, latency, error class, page views
  deletion:
    route: Delete the related activity in Capable, or contact hello@capable.run
    text: deleting the related activity in Capable purges the stored content
  dpa:
    available: true
    text: Our processing of Customer Data is governed by our Data Processing Agreement
    url: null
  purposes:
  - purpose: Provide, operate, and support the Services
    text: Provide, operate, and support the Services; authenticate users; administer accounts and Workspaces
  - purpose: Product analytics
    text: Cookieless product analytics to understand and improve how the Services are used
  - purpose: Security and abuse prevention
    text: Securing the Services, preventing abuse, and maintaining audit logs
  residency:
  - region: European Union
    text: store Customer Data primarily in the European Union
  - region: United States
    text: Enterprise single sign-on and directory sync through WorkOS process identity, organisation and directory data in the United States
  - region: France
    text: Unipile identifies hosting in France and onward proxy/support processing
  retention:
  - period: six months
    scope: Meeting recordings
    text: video and audio are deleted six months after the call
  - period: immediately
    scope: Uploaded files
    text: Uploaded files are removed from storage immediately when the attachment or its record is deleted.
  - period: 180 days
    scope: Product events receipts
    text: receipt records are purged after 180 days
  - period: up to seven years
    scope: Account and billing records
    text: generally up to seven years for accounting records
  rights:
  - right: access
    text: access your personal data
  - right: erasure
    text: erase data
  - right: restriction
    text: restrict processing
  - right: portability
    text: data portability
  - right: objection
    text: object to processing based on legitimate interests (including direct marketing)
  role:
    text: we act as a processor on the customer's behalf
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and do not share it for cross-context behavioural advertising
  subprocessors:
    text: The current list, with purpose and location, is at legal/subprocessors.md
    url: legal/subprocessors.md
  transfers:
  - mechanism: SCC
    text: the Standard Contractual Clauses (EU SCCs) adopted by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Capable
provenance_date: '2026-11-09'
provider_name: Capable
provider_slug: capable-run
slug: capable-run-privacy-policy
source_date: '2026-11-09'
source_filename: capable-run-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://capable.run/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Capable\naid: capable-run\nurl: https://capable.run/legal/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we act as a processor on the customer's behalf\ndata_categories:\n- category: identifying\n  text: Name, email, profile image, organisation, role\n- category: financial\n  text: Billing Plan, billing contact, billing address, VAT / tax IDs, invoices, payment status\n- category: communication\n  text: Transcripts and recording links from the meeting recorder\n- category: behavioral\n  text: Cookieless, metadata-minimized usage signals — for example which MCP tool was called, latency,\
  \ error class,\n    page views\npurposes:\n- purpose: Provide, operate, and support the Services\n  text: Provide, operate, and support the Services; authenticate users; administer accounts and Workspaces\n- purpose: Product analytics\n  text: Cookieless product analytics to understand and improve how the Services are used\n- purpose: Security and abuse prevention\n  text: Securing the Services, preventing abuse, and maintaining audit logs\nretention:\n- scope: Meeting recordings\n  period: six months\n  text: video and audio are deleted six months after the call\n- scope: Uploaded files\n  period: immediately\n  text: Uploaded files are removed from storage immediately when the attachment or its record is deleted.\n- scope: Product events receipts\n  period: 180 days\n  text: receipt records are purged after 180 days\n- scope: Account and billing records\n  period: up to seven years\n  text: generally up to seven years for accounting records\nresidency:\n- region: European Union\n  text:\
  \ store Customer Data primarily in the European Union\n- region: United States\n  text: Enterprise single sign-on and directory sync through WorkOS process identity, organisation and directory\n    data in the United States\n- region: France\n  text: Unipile identifies hosting in France and onward proxy/support processing\ntransfers:\n- mechanism: SCC\n  text: the Standard Contractual Clauses (EU SCCs) adopted by the European Commission\nsubprocessors:\n  url: legal/subprocessors.md\n  text: The current list, with purpose and location, is at legal/subprocessors.md\ndpa:\n  available: true\n  url: null\n  text: Our processing of Customer Data is governed by our Data Processing Agreement\ndeletion:\n  route: Delete the related activity in Capable, or contact hello@capable.run\n  text: deleting the related activity in Capable purges the stored content\nrights:\n- right: access\n  text: access your personal data\n- right: erasure\n  text: erase data\n- right: restriction\n  text: restrict\
  \ processing\n- right: portability\n  text: data portability\n- right: objection\n  text: object to processing based on legitimate interests (including direct marketing)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and do not share it for cross-context behavioural advertising\n"
source_yaml_url: https://artifacts.apis.io/capable-run/privacy/capable-run-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Capable's own page on 2026-11-09.
synthetic: false
tags:
- CRM
- Artificial Intelligence
- MCP
- Software-as-a-Service
- Sales
---
