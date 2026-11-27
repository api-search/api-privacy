---
api_specs:
- filename: bilinc-space-openapi-generated.yml
  format: yaml
  label: Bilinc API
  slug: bilinc-space-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bilinc-space/openapi/_ae-authored/bilinc-space-openapi-generated.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: contact
    text: Account information, such as your email address and workspace and project details.
  - category: identifying
    text: Credentials and security information, such as API-key identifiers; API keys themselves are stored only in hashed form.
  - category: device
    text: Usage and device information, such as the features and API endpoints you use, request records, and approximate network information needed for security.
  - category: financial
    text: Billing information, such as your plan and subscription status; payment card details are collected and processed by our payment processor (or by AWS if you subscribe through AWS Marketplace), not stored by us.
  - category: communication
    text: Communications you send to us, such as support requests.
  - category: other
    text: Content you submit to Bilinc Cloud, such as memory entries and their metadata.
  deletion:
    route: Email bilincsupport@rearclabs.com; deletion requests completed within 30 days, or use forget/purge in the API, SDK or CLI
    text: To delete a workspace or your account sooner, email bilincsupport@rearclabs.com; we complete deletion requests within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and operate Bilinc Cloud
    text: We use personal information to provide, operate, and maintain Bilinc Cloud
  - purpose: authentication and security
    text: to authenticate users and secure accounts
  - purpose: payments
    text: to process subscriptions and payments
  - purpose: support and service messages
    text: to respond to support requests and send service-related messages
  - purpose: aggregate usage understanding
    text: to understand in aggregate how Bilinc is used so we can improve it
  - purpose: legal compliance
    text: and to comply with legal obligations
  residency:
  - region: United States
    text: We are based in the United States, and our service providers may process personal information in the United States and other countries.
  retention:
  - period: as long as your account is active
    scope: account information
    text: We keep account information for as long as your account is active.
  - period: 30 days
    scope: deleted data, active systems
    text: Deleted data is removed from our active systems within 30 days and from our encrypted backups within 90 days.
  - period: 90 days
    scope: deleted data, encrypted backups
    text: Deleted data is removed from our active systems within 30 days and from our encrypted backups within 90 days.
  - period: generally no longer than 30 days
    scope: security and operational logs
    text: security and operational logs for a limited period, generally no longer than 30 days
  - period: 30 days without use
    scope: refresh tokens
    text: refresh tokens expire after 30 days without use and at most 180 days after you connect
  - period: 7 days
    scope: access tokens
    text: Access tokens expire after 7 days
  - period: null
    scope: archived workspaces
    text: Starting November 2, 2026, an archived workspace's memories, checkpoints and audit trail are removed from our active systems 30 days after it is archived.
  rights:
  - right: access, correct, delete, receive a copy
    text: you may have the right to access, correct, delete, or receive a copy of your personal information
  - right: object or restrict processing
    text: and to object to or restrict certain processing
  - right: complain to data protection authority
    text: You may also complain to your local data protection authority.
  - right: non-discrimination
    text: We will not discriminate against you for exercising your rights.
  role:
    text: When an organization uses Bilinc Cloud, it controls the content its members submit to its workspaces, and we process that content on its behalf.
    value: both
  sale_or_sharing:
    stance: unstated
    text: We do not sell your personal information.
  subprocessors:
    text: The service providers we use are listed on our Subprocessors page.
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on our providers’ data processing terms, including Standard Contractual Clauses or other recognized safeguards where applicable.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bilinc
provenance_date: '2026-11-09'
provider_name: Bilinc
provider_slug: bilinc-space
slug: bilinc-space-privacy-policy
source_date: '2026-11-09'
source_filename: bilinc-space-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://bilinc.space/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bilinc\naid: bilinc-space\nurl: https://bilinc.space/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: When an organization uses Bilinc Cloud, it controls the content its members submit to its workspaces, and\n    we process that content on its behalf.\ndata_categories:\n- category: contact\n  text: Account information, such as your email address and workspace and project details.\n- category: identifying\n  text: Credentials and security information, such as API-key identifiers; API keys themselves are stored only in\n    hashed form.\n- category: device\n  text: Usage and device information,\
  \ such as the features and API endpoints you use, request records, and approximate\n    network information needed for security.\n- category: financial\n  text: Billing information, such as your plan and subscription status; payment card details are collected and processed\n    by our payment processor (or by AWS if you subscribe through AWS Marketplace), not stored by us.\n- category: communication\n  text: Communications you send to us, such as support requests.\n- category: other\n  text: Content you submit to Bilinc Cloud, such as memory entries and their metadata.\npurposes:\n- purpose: provide and operate Bilinc Cloud\n  text: We use personal information to provide, operate, and maintain Bilinc Cloud\n- purpose: authentication and security\n  text: to authenticate users and secure accounts\n- purpose: payments\n  text: to process subscriptions and payments\n- purpose: support and service messages\n  text: to respond to support requests and send service-related messages\n- purpose:\
  \ aggregate usage understanding\n  text: to understand in aggregate how Bilinc is used so we can improve it\n- purpose: legal compliance\n  text: and to comply with legal obligations\nretention:\n- scope: account information\n  period: as long as your account is active\n  text: We keep account information for as long as your account is active.\n- scope: deleted data, active systems\n  period: 30 days\n  text: Deleted data is removed from our active systems within 30 days and from our encrypted backups within 90\n    days.\n- scope: deleted data, encrypted backups\n  period: 90 days\n  text: Deleted data is removed from our active systems within 30 days and from our encrypted backups within 90\n    days.\n- scope: security and operational logs\n  period: generally no longer than 30 days\n  text: security and operational logs for a limited period, generally no longer than 30 days\n- scope: refresh tokens\n  period: 30 days without use\n  text: refresh tokens expire after 30 days without\
  \ use and at most 180 days after you connect\n- scope: access tokens\n  period: 7 days\n  text: Access tokens expire after 7 days\n- scope: archived workspaces\n  period: null\n  text: Starting November 2, 2026, an archived workspace's memories, checkpoints and audit trail are removed from\n    our active systems 30 days after it is archived.\nresidency:\n- region: United States\n  text: We are based in the United States, and our service providers may process personal information in the United\n    States and other countries.\ntransfers:\n- mechanism: SCC\n  text: we rely on our providers’ data processing terms, including Standard Contractual Clauses or other recognized\n    safeguards where applicable.\nsubprocessors:\n  url: null\n  text: The service providers we use are listed on our Subprocessors page.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email bilincsupport@rearclabs.com; deletion requests completed within 30 days, or use forget/purge in the\n \
  \   API, SDK or CLI\n  text: To delete a workspace or your account sooner, email bilincsupport@rearclabs.com; we complete deletion requests\n    within 30 days.\nrights:\n- right: access, correct, delete, receive a copy\n  text: you may have the right to access, correct, delete, or receive a copy of your personal information\n- right: object or restrict processing\n  text: and to object to or restrict certain processing\n- right: complain to data protection authority\n  text: You may also complain to your local data protection authority.\n- right: non-discrimination\n  text: We will not discriminate against you for exercising your rights.\nsale_or_sharing:\n  stance: unstated\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/bilinc-space/privacy/bilinc-space-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 28 quoted statements, read from Bilinc's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Memory
- Platform
- Developer Tools
- Cloud
---
