---
api_specs:
- filename: caliuapp-com-api-keys-api-openapi.yml
  format: yaml
  label: Caliu API Keys API
  slug: caliuapp-com-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-api-keys-api-openapi.yml
- filename: caliuapp-com-attachments-api-openapi.yml
  format: yaml
  label: Caliu Attachments API
  slug: caliuapp-com-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-attachments-api-openapi.yml
- filename: caliuapp-com-auth-api-openapi.yml
  format: yaml
  label: Caliu Auth API
  slug: caliuapp-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-auth-api-openapi.yml
- filename: caliuapp-com-devices-api-openapi.yml
  format: yaml
  label: Caliu Devices API
  slug: caliuapp-com-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-devices-api-openapi.yml
- filename: caliuapp-com-export-api-openapi.yml
  format: yaml
  label: Caliu Export API
  slug: caliuapp-com-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-export-api-openapi.yml
- filename: caliuapp-com-notes-api-openapi.yml
  format: yaml
  label: Caliu Notes API
  slug: caliuapp-com-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-notes-api-openapi.yml
- filename: caliuapp-com-reminders-api-openapi.yml
  format: yaml
  label: Caliu Reminders API
  slug: caliuapp-com-reminders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-reminders-api-openapi.yml
- filename: caliuapp-com-subscription-api-openapi.yml
  format: yaml
  label: Caliu Subscription API
  slug: caliuapp-com-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-subscription-api-openapi.yml
- filename: caliuapp-com-tags-api-openapi.yml
  format: yaml
  label: Caliu Tags API
  slug: caliuapp-com-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caliuapp-com/openapi/caliuapp-com-tags-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account information: email address, name, and password (hashed with bcrypt).'
  - category: device
    text: 'Device information: Web Push subscription tokens if you enable notifications.'
  - category: behavioral
    text: 'Usage data: anonymized analytics events (page views, feature usage) collected via Mixpanel, hosted in the EU.'
  - category: location
    text: an approximate location derived from your IP address
  - category: other
    text: 'Notes and content: the notes, tags, attachments, and reminders you create within Caliu.'
  deletion:
    route: email hola@caliuapp.com
    text: To exercise any of these rights, email us at hola@caliuapp.com .
  dpa:
    available: true
    text: Each processes data on our behalf under appropriate data processing agreements
    url: null
  purposes:
  - purpose: Provide, maintain and sync notes
    text: To provide, maintain, and sync your notes across devices.
  - purpose: Authentication and account security
    text: To authenticate your identity and secure your account.
  - purpose: Transactional email
    text: To send transactional emails (email verification, password resets).
  - purpose: Error monitoring and reliability
    text: To monitor errors and improve the reliability of the service.
  - purpose: Usage analytics
    text: To understand how the service is used so we can improve it.
  residency:
  - region: EU
    text: Data is hosted in the EU (EU data residency).
  retention:
  - period: as long as your account is active
    scope: Account data
    text: 'Account data: retained for as long as your account is active.'
  - period: 30 days
    scope: Deleted notes
    text: 'Deleted notes: soft-deleted items are permanently purged after 30 days.'
  - period: 30 days
    scope: Sessions
    text: 'Sessions: expire after 30 days and are cleaned up automatically.'
  rights:
  - right: Access
    text: Access your personal data and obtain a copy.
  - right: Rectify
    text: Rectify inaccurate or incomplete data.
  - right: Erase
    text: Erase your data (“right to be forgotten”).
  - right: Restrict processing
    text: Restrict processing in certain circumstances.
  - right: Data portability
    text: Data portability — receive your data in a structured, machine-readable format.
  - right: Object
    text: Object to processing based on legitimate interest.
  - right: Withdraw consent
    text: Withdraw consent at any time (e.g., push notifications).
  role:
    text: Caliu is operated by Marc Torrelles, an individual based in Spain.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: We use the following third-party services to operate Caliu.
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on EU-approved mechanisms such as Standard Contractual Clauses (SCCs) or adequacy decisions
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Caliu
provenance_date: '2026-11-09'
provider_name: Caliu
provider_slug: caliuapp-com
slug: caliuapp-com-privacy-policy
source_date: '2026-11-09'
source_filename: caliuapp-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://caliuapp.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Caliu\naid: caliuapp-com\nurl: https://caliuapp.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Caliu is operated by Marc Torrelles, an individual based in Spain.\ndata_categories:\n- category: identifying\n  text: 'Account information: email address, name, and password (hashed with bcrypt).'\n- category: device\n  text: 'Device information: Web Push subscription tokens if you enable notifications.'\n- category: behavioral\n  text: 'Usage data: anonymized analytics events (page views, feature usage) collected via Mixpanel, hosted in the\n    EU.'\n- category: location\n  text: an\
  \ approximate location derived from your IP address\n- category: other\n  text: 'Notes and content: the notes, tags, attachments, and reminders you create within Caliu.'\npurposes:\n- purpose: Provide, maintain and sync notes\n  text: To provide, maintain, and sync your notes across devices.\n- purpose: Authentication and account security\n  text: To authenticate your identity and secure your account.\n- purpose: Transactional email\n  text: To send transactional emails (email verification, password resets).\n- purpose: Error monitoring and reliability\n  text: To monitor errors and improve the reliability of the service.\n- purpose: Usage analytics\n  text: To understand how the service is used so we can improve it.\nretention:\n- scope: Account data\n  period: as long as your account is active\n  text: 'Account data: retained for as long as your account is active.'\n- scope: Deleted notes\n  period: 30 days\n  text: 'Deleted notes: soft-deleted items are permanently purged after 30 days.'\n\
  - scope: Sessions\n  period: 30 days\n  text: 'Sessions: expire after 30 days and are cleaned up automatically.'\nresidency:\n- region: EU\n  text: Data is hosted in the EU (EU data residency).\ntransfers:\n- mechanism: SCC\n  text: we rely on EU-approved mechanisms such as Standard Contractual Clauses (SCCs) or adequacy decisions\nsubprocessors:\n  url: null\n  text: We use the following third-party services to operate Caliu.\ndpa:\n  available: true\n  url: null\n  text: Each processes data on our behalf under appropriate data processing agreements\ndeletion:\n  route: email hola@caliuapp.com\n  text: To exercise any of these rights, email us at hola@caliuapp.com .\nrights:\n- right: Access\n  text: Access your personal data and obtain a copy.\n- right: Rectify\n  text: Rectify inaccurate or incomplete data.\n- right: Erase\n  text: Erase your data (“right to be forgotten”).\n- right: Restrict processing\n  text: Restrict processing in certain circumstances.\n- right: Data portability\n\
  \  text: Data portability — receive your data in a structured, machine-readable format.\n- right: Object\n  text: Object to processing based on legitimate interest.\n- right: Withdraw consent\n  text: Withdraw consent at any time (e.g., push notifications).\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/caliuapp-com/privacy/caliuapp-com-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Caliu's own page on 2026-11-09.
synthetic: false
tags:
- Note Taking
- Privacy
- Local-First
- Markdown
- Cross-Platform
---
