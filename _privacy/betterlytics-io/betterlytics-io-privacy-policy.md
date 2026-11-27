---
api_specs:
- filename: betterlytics-io-openapi-generated.yml
  format: yaml
  label: Betterlytics API
  slug: betterlytics-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/betterlytics-io/openapi/_ae-authored/betterlytics-io-openapi-generated.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Email address: Required to create an account, send you essential service communications, and provide customer support.'
  - category: identifying
    text: 'Authentication data: Secure session tokens to keep you logged in to your dashboard.'
  - category: device
    text: We parse the user agent string to determine browser type, operating system, and device category (mobile, tablet, desktop, laptop).
  - category: location
    text: We determine the visitor's country from their IP address using a GeoIP database.
  - category: behavioral
    text: We track which pages are visited and navigation patterns to help website owners understand how their content is being consumed.
  deletion:
    route: Account deletion, or email privacy@betterlytics.io
    text: You always have the right to immediate deletion of all data.
  dpa:
    available: true
    text: For more details, please see our Terms of Service and Data Processing Agreement.
    url: null
  purposes:
  - purpose: Count unique visitors
    text: This allows us to count unique visitors without tracking individuals.
  - purpose: Improve service and support
    text: 'Usage data: How you use our dashboard to improve our service and provide support.'
  - purpose: Count active self-hosted installations
    text: we count active installations and see which versions are in use, so we can prioritise support and security fixes.
  residency:
  - region: EU
    text: All data is processed and stored on servers located within the European Union, ensuring GDPR compliance.
  - region: EU (Hetzner)
    text: the data is stored on our servers at Hetzner in the EU and is not shared with anyone else.
  retention:
  - period: immediately
    scope: Account deletion
    text: When you delete your account, ALL data is permanently deleted immediately
  - period: up to 1 month
    scope: Cancelled subscription with account kept
    text: we retain your analytics data for up to 1 month in case you decide to reactivate
  - period: 30 minutes
    scope: Visitor sessions
    text: automatically expire after 30 minutes of inactivity and are stored only in server memory
  - period: 365 days
    scope: Self-hosted telemetry records
    text: each daily record is deleted 365 days after its date.
  rights:
  - right: Access
    text: 'Right of access: Request a copy of your personal data'
  - right: Erasure
    text: 'Right to erasure: Request deletion of your personal data'
  - right: Object
    text: 'Right to object: Object to processing based on legitimate interests'
  role:
    text: In such cases, Betterlytics acts as a data processor of the received data and processes it solely according to our standard procedures.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: 'We promise we never sell your data: never have, never will.'
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Betterlytics
provenance_date: '2026-11-09'
provider_name: Betterlytics
provider_slug: betterlytics-io
slug: betterlytics-io-privacy-policy
source_date: '2026-11-09'
source_filename: betterlytics-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://betterlytics.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Betterlytics\naid: betterlytics-io\nurl: https://betterlytics.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: In such cases, Betterlytics acts as a data processor of the received data and processes it solely according\n    to our standard procedures.\ndata_categories:\n- category: contact\n  text: 'Email address: Required to create an account, send you essential service communications, and provide customer\n    support.'\n- category: identifying\n  text: 'Authentication data: Secure session tokens to keep you logged in to your dashboard.'\n- category: device\n  text: We parse the user\
  \ agent string to determine browser type, operating system, and device category (mobile,\n    tablet, desktop, laptop).\n- category: location\n  text: We determine the visitor's country from their IP address using a GeoIP database.\n- category: behavioral\n  text: We track which pages are visited and navigation patterns to help website owners understand how their content\n    is being consumed.\npurposes:\n- purpose: Count unique visitors\n  text: This allows us to count unique visitors without tracking individuals.\n- purpose: Improve service and support\n  text: 'Usage data: How you use our dashboard to improve our service and provide support.'\n- purpose: Count active self-hosted installations\n  text: we count active installations and see which versions are in use, so we can prioritise support and security\n    fixes.\nretention:\n- scope: Account deletion\n  period: immediately\n  text: When you delete your account, ALL data is permanently deleted immediately\n- scope: Cancelled subscription\
  \ with account kept\n  period: up to 1 month\n  text: we retain your analytics data for up to 1 month in case you decide to reactivate\n- scope: Visitor sessions\n  period: 30 minutes\n  text: automatically expire after 30 minutes of inactivity and are stored only in server memory\n- scope: Self-hosted telemetry records\n  period: 365 days\n  text: each daily record is deleted 365 days after its date.\nresidency:\n- region: EU\n  text: All data is processed and stored on servers located within the European Union, ensuring GDPR compliance.\n- region: EU (Hetzner)\n  text: the data is stored on our servers at Hetzner in the EU and is not shared with anyone else.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: For more details, please see our Terms of Service and Data Processing Agreement.\ndeletion:\n  route: Account deletion, or email privacy@betterlytics.io\n  text: You always have the right to immediate deletion of all data.\nrights:\n\
  - right: Access\n  text: 'Right of access: Request a copy of your personal data'\n- right: Erasure\n  text: 'Right to erasure: Request deletion of your personal data'\n- right: Object\n  text: 'Right to object: Object to processing based on legitimate interests'\nsale_or_sharing:\n  stance: prohibited\n  text: 'We promise we never sell your data: never have, never will.'\n"
source_yaml_url: https://artifacts.apis.io/betterlytics-io/privacy/betterlytics-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Betterlytics's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Session Replay
- Error Tracking
- Core Web Vitals
- Uptime Monitoring
- Open Source
---
