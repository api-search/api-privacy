---
api_specs:
- filename: idrive-reseller-api-openapi.yml
  format: yaml
  label: IDrive Reseller API
  slug: idrive-reseller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idrive/openapi/idrive-reseller-api-openapi.yml
- filename: idrive-subusers-api-openapi.yml
  format: yaml
  label: IDrive Subusers API
  slug: idrive-subusers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/idrive/openapi/idrive-subusers-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: we must collect personal information from users during the registration process including first and last names, a valid credit card to process payment for service, home and/or business postal addresses, an email address, mobile number, and a password
  - category: device
    text: Device Internet Protocol ("IP") address, browser type, Device name and/or identification number
  - category: behavioral
    text: we may conduct surveys and ask users to voluntarily provide feedback regarding our products and services
  - category: communication
    text: you may grant the app permission to access your SMS (messages), Call logs, and Calendar events for the sole purpose of backup
  deletion:
    route: Close account or contact privacy@idrive.com
    text: When you close your account, your stored data is permanently deleted from our systems within 10 days, unless a longer retention period is required by law.
  dpa:
    available: true
    text: Processing of customer personal data under our service agreements is governed by the IDrive Data Processing Addendum ( DPA )
    url: null
  purposes:
  - purpose: provide and improve service
    text: (i) to provide and improve our Service
  - purpose: analytics and security
    text: We may collect and process IP addresses for purposes such as system administration, service security, analytics, and to help detect or prevent misuse of our Services.
  - purpose: marketing communications
    text: We may send SMS/emails/push notifications to update you on any product reminders, updates, events, and promotions we may be running.
  - purpose: legal compliance
    text: Legal obligation – when we are required to comply with applicable laws, such as tax or law enforcement requests.
  residency:
  - region: United States
    text: IDrive, Inc. is based in the United States.
  retention:
  - period: 10 days
    scope: account data after closure
    text: When you close your account, your stored data is permanently deleted from our systems within 10 days, unless a longer retention period is required by law.
  rights:
  - right: access
    text: You have the right to request access to all personal information IDrive ® collects about you by contacting privacy@idrive.com .
  - right: correct or amend
    text: where you can correct, amend, or delete information related to your account.
  - right: delete
    text: Right to delete – Request deletion of personal information we hold about you, subject to certain exceptions (e.g., billing, legal compliance, or security).
  - right: opt out of sale or sharing
    text: Right to opt out – Direct us not to sell or share your personal information for cross-context behavioral advertising.
  - right: withdraw consent
    text: You may also withdraw your consent for us to disclose and/or process your personal information
  - right: object to legitimate interests processing
    text: You have the right to object to processing based on legitimate interests
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell personal information and do not share it for third-party direct marketing.
  subprocessors:
    text: For a current list of our service providers and sub-processors, please visit our Sub-processor Page .
    url: null
  transfers:
  - mechanism: DPF
    text: IDrive Inc. complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF) and the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework
  - mechanism: SCC
    text: Where a transfer is not covered by these frameworks, we rely on the European Commission's Standard Contractual Clauses (SCCs), together with the UK Addendum where applicable.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: IDrive
provenance_date: '2026-11-09'
provider_name: IDrive
provider_slug: idrive
slug: idrive-privacy-policy
source_date: '2026-11-09'
source_filename: idrive-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.idrive.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: IDrive\naid: idrive\nurl: https://www.idrive.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we must collect personal information from users during the registration process including first and last\n    names, a valid credit card to process payment for service, home and/or business postal addresses, an email address,\n    mobile number, and a password\n- category: device\n  text: Device Internet Protocol (\"IP\") address, browser type, Device name and/or identification number\n- category: behavioral\n  text: we may conduct surveys\
  \ and ask users to voluntarily provide feedback regarding our products and services\n- category: communication\n  text: you may grant the app permission to access your SMS (messages), Call logs, and Calendar events for the sole\n    purpose of backup\npurposes:\n- purpose: provide and improve service\n  text: (i) to provide and improve our Service\n- purpose: analytics and security\n  text: We may collect and process IP addresses for purposes such as system administration, service security, analytics,\n    and to help detect or prevent misuse of our Services.\n- purpose: marketing communications\n  text: We may send SMS/emails/push notifications to update you on any product reminders, updates, events, and promotions\n    we may be running.\n- purpose: legal compliance\n  text: Legal obligation – when we are required to comply with applicable laws, such as tax or law enforcement requests.\nretention:\n- scope: account data after closure\n  period: 10 days\n  text: When you close your account,\
  \ your stored data is permanently deleted from our systems within 10 days, unless\n    a longer retention period is required by law.\nresidency:\n- region: United States\n  text: IDrive, Inc. is based in the United States.\ntransfers:\n- mechanism: DPF\n  text: IDrive Inc. complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF) and the UK Extension to the EU-U.S.\n    DPF, and the Swiss-U.S. Data Privacy Framework\n- mechanism: SCC\n  text: Where a transfer is not covered by these frameworks, we rely on the European Commission's Standard Contractual\n    Clauses (SCCs), together with the UK Addendum where applicable.\nsubprocessors:\n  url: null\n  text: For a current list of our service providers and sub-processors, please visit our Sub-processor Page .\ndpa:\n  available: true\n  url: null\n  text: Processing of customer personal data under our service agreements is governed by the IDrive Data Processing\n    Addendum ( DPA )\ndeletion:\n  route: Close account or contact privacy@idrive.com\n\
  \  text: When you close your account, your stored data is permanently deleted from our systems within 10 days, unless\n    a longer retention period is required by law.\nrights:\n- right: access\n  text: You have the right to request access to all personal information IDrive ® collects about you by contacting\n    privacy@idrive.com .\n- right: correct or amend\n  text: where you can correct, amend, or delete information related to your account.\n- right: delete\n  text: Right to delete – Request deletion of personal information we hold about you, subject to certain exceptions\n    (e.g., billing, legal compliance, or security).\n- right: opt out of sale or sharing\n  text: Right to opt out – Direct us not to sell or share your personal information for cross-context behavioral\n    advertising.\n- right: withdraw consent\n  text: You may also withdraw your consent for us to disclose and/or process your personal information\n- right: object to legitimate interests processing\n  text: You\
  \ have the right to object to processing based on legitimate interests\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell personal information and do not share it for third-party direct marketing.\n"
source_yaml_url: https://artifacts.apis.io/idrive/privacy/idrive-privacy-policy.yml
stated_fields:
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
summary_line: 22 quoted statements, read from IDrive's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Object Storage
- S3 Compatible
- Cloud Storage
- Backup
- Reseller
- MCP
---
