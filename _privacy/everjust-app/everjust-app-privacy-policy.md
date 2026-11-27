---
api_specs:
- filename: everjust-app-openapi-generated.yml
  format: yaml
  label: EVERJUST.APP API
  slug: everjust-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/everjust-app/openapi/_ae-authored/everjust-app-openapi-generated.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account details: your email, organization name, and workspace address, collected at signup to create and administer your workspace.'
  - category: financial
    text: we receive only subscription status and receipts metadata.
  - category: communication
    text: 'Workspace content: whatever your team puts in your workspace, including mail you receive or import.'
  - category: device
    text: 'Notification subscriptions, only if you turn notifications on: an address for each device that receives them.'
  - category: other
    text: 'Operational logs: standard server logs (IP, timestamp, request path) kept briefly for security and reliability.'
  deletion:
    route: data deletion page, or email for notification subscriptions
    text: Step by step instructions for deleting your data, including how to revoke access at Google and Microsoft, are on the data deletion page.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: create and administer workspace
    text: collected at signup to create and administer your workspace
  - purpose: provide the service
    text: processed only to provide the service
  - purpose: security and reliability
    text: kept briefly for security and reliability
  residency:
  - region: United States
    text: Amazon Web Services (United States) hosts the platform and every workspace database.
  - region: United States
    text: Processing happens in the United States.
  retention:
  - period: until you or an administrator delete it
    scope: Workspace content
    text: stays in your workspace until you or an administrator delete it
  - period: briefly
    scope: Operational logs
    text: kept briefly for security and reliability
  - period: 30 days
    scope: Import activity records
    text: records older than 30 days are deleted the next time anyone in your workspace lists the folders of an account to import
  - period: null
    scope: Connected account tokens
    text: Tokens are deleted when you disconnect the account and when the workspace is deleted.
  - period: null
    scope: Backups
    text: We do not expire these backups automatically
  rights:
  - right: access and export
    text: 'Access & export: export records from any list view, bulk-download files, export a mailbox as an .mbox file, or request a full export.'
  - right: correction and deletion
    text: 'Correction & deletion: edit or delete your data in the workspace anytime'
  - right: control of connections
    text: 'Control of connections: disconnect an account, or turn off notifications, whenever you like'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No selling, pooling, or mining of your data
  subprocessors:
    text: We use a small number of service providers to run EVERJUST.APP.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: EVERJUST.APP
provenance_date: '2026-11-09'
provider_name: EVERJUST.APP
provider_slug: everjust-app
slug: everjust-app-privacy-policy
source_date: '2026-11-09'
source_filename: everjust-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://everjust.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: EVERJUST.APP\naid: everjust-app\nurl: https://everjust.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Account details: your email, organization name, and workspace address, collected at signup to create and\n    administer your workspace.'\n- category: financial\n  text: we receive only subscription status and receipts metadata.\n- category: communication\n  text: 'Workspace content: whatever your team puts in your workspace, including mail you receive or import.'\n- category: device\n  text: 'Notification subscriptions, only\
  \ if you turn notifications on: an address for each device that receives\n    them.'\n- category: other\n  text: 'Operational logs: standard server logs (IP, timestamp, request path) kept briefly for security and reliability.'\npurposes:\n- purpose: create and administer workspace\n  text: collected at signup to create and administer your workspace\n- purpose: provide the service\n  text: processed only to provide the service\n- purpose: security and reliability\n  text: kept briefly for security and reliability\nretention:\n- scope: Workspace content\n  period: until you or an administrator delete it\n  text: stays in your workspace until you or an administrator delete it\n- scope: Operational logs\n  period: briefly\n  text: kept briefly for security and reliability\n- scope: Import activity records\n  period: 30 days\n  text: records older than 30 days are deleted the next time anyone in your workspace lists the folders of an account\n    to import\n- scope: Connected account tokens\n\
  \  period: null\n  text: Tokens are deleted when you disconnect the account and when the workspace is deleted.\n- scope: Backups\n  period: null\n  text: We do not expire these backups automatically\nresidency:\n- region: United States\n  text: Amazon Web Services (United States) hosts the platform and every workspace database.\n- region: United States\n  text: Processing happens in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use a small number of service providers to run EVERJUST.APP.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: data deletion page, or email for notification subscriptions\n  text: Step by step instructions for deleting your data, including how to revoke access at Google and Microsoft,\n    are on the data deletion page.\nrights:\n- right: access and export\n  text: 'Access & export: export records from any list view, bulk-download files, export a mailbox as an .mbox file,\n    or request a full export.'\n- right:\
  \ correction and deletion\n  text: 'Correction & deletion: edit or delete your data in the workspace anytime'\n- right: control of connections\n  text: 'Control of connections: disconnect an account, or turn off notifications, whenever you like'\nsale_or_sharing:\n  stance: prohibited\n  text: No selling, pooling, or mining of your data\n"
source_yaml_url: https://artifacts.apis.io/everjust-app/privacy/everjust-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from EVERJUST.APP's own page on 2026-11-09.
synthetic: false
tags:
- CRM
- Invoicing
- Project
- Payroll
- Workspace
---
