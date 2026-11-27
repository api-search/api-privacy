---
api_specs:
- filename: adaptlypost-com-api-openapi.json
  format: json
  label: AdaptlyPost Public API API
  slug: adaptlypost-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/adaptlypost-com/openapi/_original/adaptlypost-com-api-openapi.json
claim_count: 32
description: ''
doc:
  data_categories:
  - category: contact
    text: Your name and contact details (email, phone)
  - category: financial
    text: Billing details (billing address, transaction history)
  - category: identifying
    text: Login credentials. Passwords are handled by our sign-in provider, WorkOS
  - category: device
    text: Device details (IP address, browser, operating system)
  - category: location
    text: Approximate location (based on IP address)
  - category: behavioral
    text: Activity data (pages viewed, features used, session duration)
  - category: communication
    text: Messages you send us (support emails, chat messages, feedback)
  deletion:
    route: Delete account in Settings or email contact@adaptlypost.com
    text: You can delete your account in Settings.
  dpa:
    available: true
    text: as a processor under our Data Processing Agreement
    url: null
  purposes:
  - purpose: Provide, run and support platform
    text: Provide, run and support our platform
  - purpose: Process payments and subscriptions
    text: Process your payments and subscriptions
  - purpose: Understand usage
    text: Understand how people use our service
  - purpose: Marketing emails with opt-in
    text: Send you marketing emails (only if you've opted in)
  residency:
  - region: EU
    text: Our servers, database and backups are in the EU (Hetzner, in Finland and Germany)
  retention:
  - period: while your account is active
    scope: Account data
    text: 'Account data: while your account is active.'
  - period: 14 days
    scope: Post media of failed posts
    text: Media of failed posts is removed after 14 days
  - period: 30 days
    scope: AI history
    text: Deleted AI history is purged after 30 days
  - period: up to 90 days
    scope: Service logs
    text: 'Service logs: up to 90 days'
  - period: 21 days
    scope: Backups
    text: 'Backups: deleted data leaves our backups within 21 days'
  - period: 5 years from the end of the tax year
    scope: Billing and invoice records
    text: 'Billing and invoice records: as long as Polish tax law requires, which is 5 years from the end of the tax year'
  rights:
  - right: Access
    text: 'Access your data: Get a copy of what we have about you'
  - right: Correct
    text: 'Correct your data: Fix anything that''s wrong or incomplete'
  - right: Delete
    text: 'Delete your data: Ask us to remove your information (with some exceptions).'
  - right: Restrict processing
    text: 'Restrict processing: Limit how we use your data'
  - right: Export
    text: Export your data
  - right: Object
    text: 'Object: Say no to certain uses, especially marketing'
  - right: Withdraw consent
    text: 'Withdraw consent: Change your mind about things you''ve agreed to'
  - right: File a complaint
    text: 'File a complaint: Contact your data protection authority if you''re unhappy'
  role:
    text: If you use AdaptlyPost to handle other people's personal data for your business, we process that data for you as a processor under our Data Processing Agreement .
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Our Sub-processors page lists each one
    url: https://adaptlypost.com/sub-processors
  transfers:
  - mechanism: DPF
    text: For those transfers we rely on the EU-US Data Privacy Framework where the provider is certified
  - mechanism: SCC
    text: otherwise on the Standard Contractual Clauses approved by the European Commission (2021/914)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AdaptlyPost
provenance_date: '2026-11-09'
provider_name: AdaptlyPost
provider_slug: adaptlypost-com
slug: adaptlypost-com-privacy-policy
source_date: '2026-11-09'
source_filename: adaptlypost-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://adaptlypost.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AdaptlyPost\naid: adaptlypost-com\nurl: https://adaptlypost.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: If you use AdaptlyPost to handle other people's personal data for your business, we process that data for\n    you as a processor under our Data Processing Agreement .\ndata_categories:\n- category: contact\n  text: Your name and contact details (email, phone)\n- category: financial\n  text: Billing details (billing address, transaction history)\n- category: identifying\n  text: Login credentials. Passwords are handled by our sign-in provider, WorkOS\n- category: device\n  text:\
  \ Device details (IP address, browser, operating system)\n- category: location\n  text: Approximate location (based on IP address)\n- category: behavioral\n  text: Activity data (pages viewed, features used, session duration)\n- category: communication\n  text: Messages you send us (support emails, chat messages, feedback)\npurposes:\n- purpose: Provide, run and support platform\n  text: Provide, run and support our platform\n- purpose: Process payments and subscriptions\n  text: Process your payments and subscriptions\n- purpose: Understand usage\n  text: Understand how people use our service\n- purpose: Marketing emails with opt-in\n  text: Send you marketing emails (only if you've opted in)\nretention:\n- scope: Account data\n  period: while your account is active\n  text: 'Account data: while your account is active.'\n- scope: Post media of failed posts\n  period: 14 days\n  text: Media of failed posts is removed after 14 days\n- scope: AI history\n  period: 30 days\n  text: Deleted\
  \ AI history is purged after 30 days\n- scope: Service logs\n  period: up to 90 days\n  text: 'Service logs: up to 90 days'\n- scope: Backups\n  period: 21 days\n  text: 'Backups: deleted data leaves our backups within 21 days'\n- scope: Billing and invoice records\n  period: 5 years from the end of the tax year\n  text: 'Billing and invoice records: as long as Polish tax law requires, which is 5 years from the end of the tax\n    year'\nresidency:\n- region: EU\n  text: Our servers, database and backups are in the EU (Hetzner, in Finland and Germany)\ntransfers:\n- mechanism: DPF\n  text: For those transfers we rely on the EU-US Data Privacy Framework where the provider is certified\n- mechanism: SCC\n  text: otherwise on the Standard Contractual Clauses approved by the European Commission (2021/914)\nsubprocessors:\n  url: https://adaptlypost.com/sub-processors\n  text: Our Sub-processors page lists each one\ndpa:\n  available: true\n  url: null\n  text: as a processor under our Data\
  \ Processing Agreement\ndeletion:\n  route: Delete account in Settings or email contact@adaptlypost.com\n  text: You can delete your account in Settings.\nrights:\n- right: Access\n  text: 'Access your data: Get a copy of what we have about you'\n- right: Correct\n  text: 'Correct your data: Fix anything that''s wrong or incomplete'\n- right: Delete\n  text: 'Delete your data: Ask us to remove your information (with some exceptions).'\n- right: Restrict processing\n  text: 'Restrict processing: Limit how we use your data'\n- right: Export\n  text: Export your data\n- right: Object\n  text: 'Object: Say no to certain uses, especially marketing'\n- right: Withdraw consent\n  text: 'Withdraw consent: Change your mind about things you''ve agreed to'\n- right: File a complaint\n  text: 'File a complaint: Contact your data protection authority if you''re unhappy'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/adaptlypost-com/privacy/adaptlypost-com-privacy-policy.yml
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
summary_line: 32 quoted statements, read from AdaptlyPost's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social Media
- Scheduling
- AI Agents
---
