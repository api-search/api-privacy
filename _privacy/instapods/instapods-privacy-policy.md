---
api_specs:
- filename: instapods-openapi-generated.yml
  format: yaml
  label: ExpressTech Systems API
  slug: instapods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/instapods/openapi/_ae-authored/instapods-openapi-generated.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you create an account, we collect your name and email address.
  - category: financial
    text: Payment processing is handled entirely by Stripe. We do not store your credit card number, CVC, or other card details on our servers.
  - category: behavioral
    text: Pod creation and management activity API usage and request logs
  - category: device
    text: Resource consumption metrics (CPU, memory, storage)
  - category: location
    text: your country, browser, operating system and screen size
  deletion:
    route: Delete pod or account; account deletion request
    text: Pod files are deleted when you delete a pod.
  dpa:
    available: true
    text: If you need a Data Processing Agreement for the personal data you host with us, you can find ours at /legal/dpa/ . It applies automatically, with no signature needed.
    url: /legal/dpa/
  purposes:
  - purpose: Provide and operate hosting services
    text: Provide, operate, and maintain our hosting services
  - purpose: Process transactions and manage accounts
    text: Process your transactions and manage your account
  - purpose: Monitor usage and enforce plan limits
    text: Monitor resource usage and enforce plan limits
  - purpose: Service communications
    text: Send service-related communications (account alerts, billing, downtime notices)
  - purpose: Improve platform
    text: Improve our platform and develop new features
  - purpose: Abuse and fraud prevention
    text: Detect and prevent abuse, fraud, or security incidents
  residency:
  - region: EU
    text: 'Your pods run in the region you choose when you create them: France for the EU region, or Canada and the United States for the North America region.'
  - region: Germany
    text: Pod backups are stored in Germany.
  - region: Finland
    text: Our control plane, which holds account data (name, email, billing records) and pod configuration, runs in Finland.
  retention:
  - period: null
    scope: Account data
    text: Retained while your account is active. Deleted upon account deletion request.
  - period: 14 days
    scope: Pod data
    text: Its backups are deleted 14 days later; the grace period lets you undo an accidental delete.
  - period: 30 days
    scope: Usage metrics
    text: 'Usage metrics: Retained for up to 30 days for billing and operational purposes.'
  - period: 30 days
    scope: Website session recordings
    text: recordings are deleted automatically after 30 days.
  - period: null
    scope: Billing records
    text: 'Billing records: Retained as required by applicable tax and financial regulations.'
  rights:
  - right: Access
    text: Access the personal data we hold about you
  - right: Rectify
    text: Rectify inaccurate or incomplete information
  - right: Delete
    text: Delete your personal data and account
  - right: Export
    text: Export your data in a standard format
  - right: Cancel account
    text: Cancel your account at any time
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or trade your personal information to any third party.
  subprocessors:
    text: The providers behind each location are listed on our sub-processors page .
    url: https://instapods.com/sub-processors/
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ExpressTech Systems
provenance_date: '2026-11-09'
provider_name: ExpressTech Systems
provider_slug: instapods
slug: instapods-privacy-policy
source_date: '2026-11-09'
source_filename: instapods-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://instapods.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ExpressTech Systems\naid: instapods\nurl: https://instapods.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: When you create an account, we collect your name and email address.\n- category: financial\n  text: Payment processing is handled entirely by Stripe. We do not store your credit card number, CVC, or other\n    card details on our servers.\n- category: behavioral\n  text: Pod creation and management activity API usage and request logs\n- category: device\n  text: Resource consumption metrics (CPU, memory, storage)\n- category:\
  \ location\n  text: your country, browser, operating system and screen size\npurposes:\n- purpose: Provide and operate hosting services\n  text: Provide, operate, and maintain our hosting services\n- purpose: Process transactions and manage accounts\n  text: Process your transactions and manage your account\n- purpose: Monitor usage and enforce plan limits\n  text: Monitor resource usage and enforce plan limits\n- purpose: Service communications\n  text: Send service-related communications (account alerts, billing, downtime notices)\n- purpose: Improve platform\n  text: Improve our platform and develop new features\n- purpose: Abuse and fraud prevention\n  text: Detect and prevent abuse, fraud, or security incidents\nretention:\n- scope: Account data\n  period: null\n  text: Retained while your account is active. Deleted upon account deletion request.\n- scope: Pod data\n  period: 14 days\n  text: Its backups are deleted 14 days later; the grace period lets you undo an accidental delete.\n\
  - scope: Usage metrics\n  period: 30 days\n  text: 'Usage metrics: Retained for up to 30 days for billing and operational purposes.'\n- scope: Website session recordings\n  period: 30 days\n  text: recordings are deleted automatically after 30 days.\n- scope: Billing records\n  period: null\n  text: 'Billing records: Retained as required by applicable tax and financial regulations.'\nresidency:\n- region: EU\n  text: 'Your pods run in the region you choose when you create them: France for the EU region, or Canada and the\n    United States for the North America region.'\n- region: Germany\n  text: Pod backups are stored in Germany.\n- region: Finland\n  text: Our control plane, which holds account data (name, email, billing records) and pod configuration, runs in\n    Finland.\ntransfers: []\nsubprocessors:\n  url: https://instapods.com/sub-processors/\n  text: The providers behind each location are listed on our sub-processors page .\ndpa:\n  available: true\n  url: /legal/dpa/\n  text:\
  \ If you need a Data Processing Agreement for the personal data you host with us, you can find ours at /legal/dpa/\n    . It applies automatically, with no signature needed.\ndeletion:\n  route: Delete pod or account; account deletion request\n  text: Pod files are deleted when you delete a pod.\nrights:\n- right: Access\n  text: Access the personal data we hold about you\n- right: Rectify\n  text: Rectify inaccurate or incomplete information\n- right: Delete\n  text: Delete your personal data and account\n- right: Export\n  text: Export your data in a standard format\n- right: Cancel account\n  text: Cancel your account at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or trade your personal information to any third party.\n"
source_yaml_url: https://artifacts.apis.io/instapods/privacy/instapods-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from ExpressTech Systems's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Deployment
- Cloud
- AI Integration
- Developer Tools
---
