---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address Name (optional) Password (hashed with bcrypt, never stored in plain text)
  - category: contact
    text: Email address
  - category: device
    text: Browser type and operating system (from user-agent header)
  - category: location
    text: IP address
  - category: financial
    text: 'We only receive from Stripe: your subscription status, plan, and billing period dates.'
  - category: behavioral
    text: Login and last activity timestamps
  deletion:
    route: Delete account
    text: When you delete your account, all personal data and monitoring data is permanently deleted from our database immediately.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide monitoring service
    text: Provide the monitoring service (perform health checks, send alerts)
  - purpose: Manage account and subscription
    text: Manage your account and subscription
  - purpose: Transactional emails
    text: Send transactional emails (welcome, password reset, alert notifications, billing)
  - purpose: Improve the Service
    text: Improve the Service (anonymized analytics, performance optimization)
  - purpose: Security
    text: Ensure security (fraud detection, rate limiting, audit logging)
  residency:
  - region: France
    text: Our servers are hosted by OVH in Roubaix, France. All data is stored and processed in France.
  retention:
  - period: 30 days
    scope: Monitoring data, Starter plan
    text: 'Starter: 30 days'
  - period: 90 days
    scope: Monitoring data, Pro plan
    text: 'Pro: 90 days'
  - period: 365 days
    scope: Monitoring data, Enterprise plan
    text: 'Enterprise: 365 days'
  - period: indefinitely
    scope: Anonymized aggregate data
    text: Anonymized aggregate data may be retained indefinitely.
  rights:
  - right: Access
    text: Access — request a copy of your personal data
  - right: Rectification
    text: Rectification — correct inaccurate or incomplete data
  - right: Erasure
    text: Erasure — request deletion of your data (“right to be forgotten”)
  - right: Portability
    text: Portability — receive your data in a structured, machine-readable format
  - right: Restriction
    text: Restriction — limit how we process your data
  - right: Objection
    text: Objection — object to data processing based on legitimate interests
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ThirdWatch
provenance_date: '2026-11-10'
provider_name: ThirdWatch
provider_slug: thirdwatch
slug: thirdwatch-privacy-policy
source_date: '2026-11-10'
source_filename: thirdwatch-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://thirdwatch.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ThirdWatch\naid: thirdwatch\nurl: https://thirdwatch.app/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Email address Name (optional) Password (hashed with bcrypt, never stored in plain text)\n- category: contact\n  text: Email address\n- category: device\n  text: Browser type and operating system (from user-agent header)\n- category: location\n  text: IP address\n- category: financial\n  text: 'We only receive from Stripe: your subscription status, plan, and billing period dates.'\n- category: behavioral\n  text: Login and last\
  \ activity timestamps\npurposes:\n- purpose: Provide monitoring service\n  text: Provide the monitoring service (perform health checks, send alerts)\n- purpose: Manage account and subscription\n  text: Manage your account and subscription\n- purpose: Transactional emails\n  text: Send transactional emails (welcome, password reset, alert notifications, billing)\n- purpose: Improve the Service\n  text: Improve the Service (anonymized analytics, performance optimization)\n- purpose: Security\n  text: Ensure security (fraud detection, rate limiting, audit logging)\nretention:\n- scope: Monitoring data, Starter plan\n  period: 30 days\n  text: 'Starter: 30 days'\n- scope: Monitoring data, Pro plan\n  period: 90 days\n  text: 'Pro: 90 days'\n- scope: Monitoring data, Enterprise plan\n  period: 365 days\n  text: 'Enterprise: 365 days'\n- scope: Anonymized aggregate data\n  period: indefinitely\n  text: Anonymized aggregate data may be retained indefinitely.\nresidency:\n- region: France\n  text:\
  \ Our servers are hosted by OVH in Roubaix, France. All data is stored and processed in France.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account\n  text: When you delete your account, all personal data and monitoring data is permanently deleted from our database\n    immediately.\nrights:\n- right: Access\n  text: Access — request a copy of your personal data\n- right: Rectification\n  text: Rectification — correct inaccurate or incomplete data\n- right: Erasure\n  text: Erasure — request deletion of your data (“right to be forgotten”)\n- right: Portability\n  text: Portability — receive your data in a structured, machine-readable format\n- right: Restriction\n  text: Restriction — limit how we process your data\n- right: Objection\n  text: Objection — object to data processing based on legitimate interests\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data to\
  \ third parties.\n"
source_yaml_url: https://artifacts.apis.io/thirdwatch/privacy/thirdwatch-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from ThirdWatch's own page on 2026-11-10.
synthetic: false
tags:
- API Monitoring
- OAuth
- JWT
- OpenAPI
- Alerting
- Performance Dashboard
- Multi‑organization
- Anomaly Detection
- Authentication
---
