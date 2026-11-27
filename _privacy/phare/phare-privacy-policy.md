---
api_specs:
- filename: phare-alert-rules-api-openapi.yml
  format: yaml
  label: Phare Alert Rules API
  slug: phare-alert-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-alert-rules-api-openapi.yml
- filename: phare-incidents-api-openapi.yml
  format: yaml
  label: Phare Incidents API
  slug: phare-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-incidents-api-openapi.yml
- filename: phare-integrations-api-openapi.yml
  format: yaml
  label: Phare Integrations API
  slug: phare-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-integrations-api-openapi.yml
- filename: phare-maintenance-windows-api-openapi.yml
  format: yaml
  label: Phare Maintenance Windows API
  slug: phare-maintenance-windows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-maintenance-windows-api-openapi.yml
- filename: phare-monitors-api-openapi.yml
  format: yaml
  label: Phare Monitors API
  slug: phare-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-monitors-api-openapi.yml
- filename: phare-platform-api-openapi.yml
  format: yaml
  label: Phare Platform API
  slug: phare-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-platform-api-openapi.yml
- filename: phare-projects-api-openapi.yml
  format: yaml
  label: Phare Projects API
  slug: phare-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-projects-api-openapi.yml
- filename: phare-reports-api-openapi.yml
  format: yaml
  label: Phare Reports API
  slug: phare-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-reports-api-openapi.yml
- filename: phare-status-pages-api-openapi.yml
  format: yaml
  label: Phare Status Pages API
  slug: phare-status-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-status-pages-api-openapi.yml
- filename: phare-users-api-openapi.yml
  format: yaml
  label: Phare Users API
  slug: phare-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phare/openapi/phare-users-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Phone number verification: When you optionally add a phone number to your account, Phare will send a one-time verification code to confirm ownership of that number.'
  deletion:
    route: Email support@phare.io
    text: 'All DSRs from the Users must be addressed at and answered from the following e-mail address: support@phare.io.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: SMS phone number verification
    text: 'Phone number verification: When you optionally add a phone number to your account, Phare will send a one-time verification code to confirm ownership of that number.'
  - purpose: Uptime alert notifications
    text: 'Uptime alert notifications: If you choose to configure SMS as a notification channel for uptime monitoring, Phare will send alert messages to your phone number based solely on the alerting rules you define.'
  - purpose: Affiliate attribution
    text: the affiliate code of the link is stored for 60 days in a first-party _klb cookie, for the sole purpose of affiliate attribution
  residency:
  - region: European Union
    text: Made and hosted in the European Union
  retention:
  - period: 60 days
    scope: Business-critical prolongations
    text: Business-critical prolongations up to 60 days (Privacy Manager approval required)
  - period: 60 days
    scope: Affiliate cookie
    text: the affiliate code of the link is stored for 60 days in a first-party _klb cookie
  rights:
  - right: Access
    text: learn if we process the Data Subject’s Personal Data
  - right: Erasure
    text: 'Data Subjects can request erasure when: Data is no longer necessary for collection purposes'
  - right: Data portability
    text: 'Data Subjects can request data portability in machine-readable format when data was collected for: Service provision (contract performance); or Based on consent.'
  - right: Objection
    text: Data Subjects can object to processing based on legitimate interests (e.g., marketing).
  - right: Withdraw consent
    text: Data Subjects can withdraw consent anytime.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Phare
provenance_date: '2026-11-10'
provider_name: Phare
provider_slug: phare
slug: phare-privacy-policy
source_date: '2026-11-10'
source_filename: phare-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://phare.io/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Phare\naid: phare\nurl: https://phare.io/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Phone number verification: When you optionally add a phone number to your account, Phare will send a one-time\n    verification code to confirm ownership of that number.'\npurposes:\n- purpose: SMS phone number verification\n  text: 'Phone number verification: When you optionally add a phone number to your account, Phare will send a one-time\n    verification code to confirm ownership of that number.'\n- purpose: Uptime alert notifications\n\
  \  text: 'Uptime alert notifications: If you choose to configure SMS as a notification channel for uptime monitoring,\n    Phare will send alert messages to your phone number based solely on the alerting rules you define.'\n- purpose: Affiliate attribution\n  text: the affiliate code of the link is stored for 60 days in a first-party _klb cookie, for the sole purpose\n    of affiliate attribution\nretention:\n- scope: Business-critical prolongations\n  period: 60 days\n  text: Business-critical prolongations up to 60 days (Privacy Manager approval required)\n- scope: Affiliate cookie\n  period: 60 days\n  text: the affiliate code of the link is stored for 60 days in a first-party _klb cookie\nresidency:\n- region: European Union\n  text: Made and hosted in the European Union\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@phare.io\n  text: 'All DSRs from the Users must be addressed at and answered\
  \ from the following e-mail address: support@phare.io.'\nrights:\n- right: Access\n  text: learn if we process the Data Subject’s Personal Data\n- right: Erasure\n  text: 'Data Subjects can request erasure when: Data is no longer necessary for collection purposes'\n- right: Data portability\n  text: 'Data Subjects can request data portability in machine-readable format when data was collected for: Service\n    provision (contract performance); or Based on consent.'\n- right: Objection\n  text: Data Subjects can object to processing based on legitimate interests (e.g., marketing).\n- right: Withdraw consent\n  text: Data Subjects can withdraw consent anytime.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/phare/privacy/phare-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 13 quoted statements, read from Phare's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Monitoring
- Incident Management
- Analytics
- European
---
