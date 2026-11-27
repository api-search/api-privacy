---
api_specs:
- filename: openapi.json
  format: json
  label: Alloovium API
  slug: alloovium-api
  spec_type: OpenAPI
  url: https://api.alloovium.com/api/v2/openapi.json
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account and workspace information: your name, work email, phone number if supplied, organisation memberships, role, permissions and authentication/session identifiers.'
  - category: contact
    text: 'Account and workspace information: your name, work email, phone number if supplied, organisation memberships, role, permissions and authentication/session identifiers.'
  - category: financial
    text: 'Commercial information: customer contacts, plan and usage information, invoices and payment or transaction references when relevant to the customer relationship.'
  - category: location
    text: Project locations, drawing pins and work-area descriptions you enter become part of the relevant record.
  - category: behavioral
    text: Optional mobile diagnostics are described separately below.
  - category: device
    text: 'Technical information: IP addresses, device/browser and app versions, session and request identifiers, timestamps, service errors, security events and relevant activity records.'
  - category: communication
    text: 'Voice and communications: audio you choose to record, transcripts, assistant replies, feedback and support correspondence.'
  - category: health
    text: Avoid unnecessary health, identity-document or other sensitive information. Free-text records, photos and audio can contain it; we do not assume that such information cannot enter the service.
  - category: professional
    text: 'Project information: documents, drawings, specifications, email or meeting content, tasks, questions and answers, diary entries, defects, inspections, evidence photos, signatures, approvals and their dates, authors and change history.'
  deletion:
    route: Settings → Privacy and account → Delete my account, or the public Delete account page; or email support@alloovium.com
    text: To request account deletion, use Settings → Privacy and account → Delete my account, or the public Delete account page linked below.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authentication and account administration
    text: We use information to authenticate people, apply workspace permissions, retrieve requested material, answer questions, produce drafts, save and sync project records, and operate features you or your organisation enable.
  - purpose: Support, security and legal obligations
    text: We also use information to provide support, communicate service changes, administer the customer relationship, understand service performance, investigate abuse and security incidents, maintain records of actions and meet applicable legal obligations.
  residency:
  - region: Australia and overseas
    text: Information may be processed in Australia and overseas, including the United States, depending on the provider and feature.
  retention:
  - period: null
    scope: Account information
    text: Account information is held while needed to provide and administer access, then reviewed when access ends or deletion is requested.
  - period: null
    scope: Operational logs and support records
    text: Operational logs and support records are kept for their security, troubleshooting and support purposes.
  rights:
  - right: Access
    text: You can ask for access to personal information, correction of inaccurate information, withdrawal of optional consent, or deletion of your account and associated personal data.
  - right: Correction
    text: You can ask for access to personal information, correction of inaccurate information, withdrawal of optional consent, or deletion of your account and associated personal data.
  - right: Objection, restriction or portability
    text: Additional rights, such as objection, restriction or portability, may apply under the law relevant to you.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information or use the mobile app for cross-company advertising tracking.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: We assess overseas disclosures against the privacy law that applies to them.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Alloovium
provenance_date: '2026-11-09'
provider_name: Alloovium
provider_slug: alloovium
slug: alloovium-privacy-policy
source_date: '2026-11-09'
source_filename: alloovium-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://app.alloovium.com/docs/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Alloovium\naid: alloovium\nurl: https://app.alloovium.com/docs/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account and workspace information: your name, work email, phone number if supplied, organisation memberships,\n    role, permissions and authentication/session identifiers.'\n- category: contact\n  text: 'Account and workspace information: your name, work email, phone number if supplied, organisation memberships,\n    role, permissions and authentication/session identifiers.'\n- category: financial\n  text: 'Commercial\
  \ information: customer contacts, plan and usage information, invoices and payment or transaction\n    references when relevant to the customer relationship.'\n- category: location\n  text: Project locations, drawing pins and work-area descriptions you enter become part of the relevant record.\n- category: behavioral\n  text: Optional mobile diagnostics are described separately below.\n- category: device\n  text: 'Technical information: IP addresses, device/browser and app versions, session and request identifiers,\n    timestamps, service errors, security events and relevant activity records.'\n- category: communication\n  text: 'Voice and communications: audio you choose to record, transcripts, assistant replies, feedback and support\n    correspondence.'\n- category: health\n  text: Avoid unnecessary health, identity-document or other sensitive information. Free-text records, photos and\n    audio can contain it; we do not assume that such information cannot enter the service.\n- category:\
  \ professional\n  text: 'Project information: documents, drawings, specifications, email or meeting content, tasks, questions and\n    answers, diary entries, defects, inspections, evidence photos, signatures, approvals and their dates, authors\n    and change history.'\npurposes:\n- purpose: Authentication and account administration\n  text: We use information to authenticate people, apply workspace permissions, retrieve requested material, answer\n    questions, produce drafts, save and sync project records, and operate features you or your organisation enable.\n- purpose: Support, security and legal obligations\n  text: We also use information to provide support, communicate service changes, administer the customer relationship,\n    understand service performance, investigate abuse and security incidents, maintain records of actions and meet\n    applicable legal obligations.\nretention:\n- scope: Account information\n  period: null\n  text: Account information is held while needed\
  \ to provide and administer access, then reviewed when access ends\n    or deletion is requested.\n- scope: Operational logs and support records\n  period: null\n  text: Operational logs and support records are kept for their security, troubleshooting and support purposes.\nresidency:\n- region: Australia and overseas\n  text: Information may be processed in Australia and overseas, including the United States, depending on the provider\n    and feature.\ntransfers:\n- mechanism: other\n  text: We assess overseas disclosures against the privacy law that applies to them.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings → Privacy and account → Delete my account, or the public Delete account page; or email support@alloovium.com\n  text: To request account deletion, use Settings → Privacy and account → Delete my account, or the public Delete\n    account page linked below.\nrights:\n- right: Access\n  text: You can\
  \ ask for access to personal information, correction of inaccurate information, withdrawal of optional\n    consent, or deletion of your account and associated personal data.\n- right: Correction\n  text: You can ask for access to personal information, correction of inaccurate information, withdrawal of optional\n    consent, or deletion of your account and associated personal data.\n- right: Objection, restriction or portability\n  text: Additional rights, such as objection, restriction or portability, may apply under the law relevant to you.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information or use the mobile app for cross-company advertising tracking.\n"
source_yaml_url: https://artifacts.apis.io/alloovium/privacy/alloovium-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Alloovium's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Construction
- Document Intelligence
- Compliance
- Artificial Intelligence
- Construction Technology
- Documents
- MCP
---
