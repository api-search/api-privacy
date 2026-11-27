---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Email address (for authentication and user identification)
  - category: contact
    text: 'Contact records you create or import: email address, phone number, name, and any custom properties you add'
  - category: behavioral
    text: Pages visited and navigation patterns
  - category: device
    text: Browser type, version, and screen size
  - category: communication
    text: Email templates and campaign content (subject and body)
  - category: device
    text: Operating system type (macOS, Linux, Windows)
  deletion:
    route: Email request to privacy@wraps.dev
    text: You can request deletion of your data at any time by contacting privacy@wraps.dev
  dpa:
    available: null
    text: If your use requires a Data Processing Agreement, contact privacy@wraps.dev
    url: null
  purposes:
  - purpose: product analytics
    text: Product analytics across CLI, web dashboard, and marketing website.
  - purpose: identify automated opens
    text: identifying automated opens (privacy proxies, security scanners, link checkers) so they can be excluded from your open-rate metrics
  - purpose: authentication and account service
    text: Authenticate users
  residency:
  - region: United States
    text: This data is stored in a managed PostgreSQL database (Neon) hosted in the United States.
  - region: United States
    text: We use PostHog Cloud hosted in the US.
  retention:
  - period: 90 days
    scope: Telemetry events
    text: 'Telemetry events: Stored for 90 days, then automatically deleted'
  - period: 7 days
    scope: Server logs
    text: 'Server logs: Retained for 7 days'
  - period: while your account is active
    scope: Platform data (contacts, campaigns, send ledger)
    text: 'Platform data (contacts, campaigns, send ledger): Retained while your account is active; deleted on request or after account closure'
  rights:
  - right: Access
    text: You have the right to request a copy of your personal data.
  - right: Opt out of telemetry
    text: 'You can disable telemetry at any time:'
  - right: Opt out of web analytics
    text: 'For the web dashboard and website, you can opt out of PostHog analytics:'
  role:
    text: For this data, Wraps acts as a data processor and you remain the data controller
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Sell your data to third parties
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Your data may be processed in the United States or other countries where our service providers operate.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: wraps-dev
provenance_date: '2026-11-10'
provider_name: wraps-dev
provider_slug: wraps-dev
slug: wraps-dev-privacy-policy
source_date: '2026-11-10'
source_filename: wraps-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://wraps.dev/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: wraps-dev\naid: wraps-dev\nurl: https://wraps.dev/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For this data, Wraps acts as a data processor and you remain the data controller\ndata_categories:\n- category: identifying\n  text: Email address (for authentication and user identification)\n- category: contact\n  text: 'Contact records you create or import: email address, phone number, name, and any custom properties you\n    add'\n- category: behavioral\n  text: Pages visited and navigation patterns\n- category: device\n  text: Browser type, version, and screen size\n- category: communication\n\
  \  text: Email templates and campaign content (subject and body)\n- category: device\n  text: Operating system type (macOS, Linux, Windows)\npurposes:\n- purpose: product analytics\n  text: Product analytics across CLI, web dashboard, and marketing website.\n- purpose: identify automated opens\n  text: identifying automated opens (privacy proxies, security scanners, link checkers) so they can be excluded\n    from your open-rate metrics\n- purpose: authentication and account service\n  text: Authenticate users\nretention:\n- scope: Telemetry events\n  period: 90 days\n  text: 'Telemetry events: Stored for 90 days, then automatically deleted'\n- scope: Server logs\n  period: 7 days\n  text: 'Server logs: Retained for 7 days'\n- scope: Platform data (contacts, campaigns, send ledger)\n  period: while your account is active\n  text: 'Platform data (contacts, campaigns, send ledger): Retained while your account is active; deleted on request\n    or after account closure'\nresidency:\n- region:\
  \ United States\n  text: This data is stored in a managed PostgreSQL database (Neon) hosted in the United States.\n- region: United States\n  text: We use PostHog Cloud hosted in the US.\ntransfers:\n- mechanism: other\n  text: Your data may be processed in the United States or other countries where our service providers operate.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: If your use requires a Data Processing Agreement, contact privacy@wraps.dev\ndeletion:\n  route: Email request to privacy@wraps.dev\n  text: You can request deletion of your data at any time by contacting privacy@wraps.dev\nrights:\n- right: Access\n  text: You have the right to request a copy of your personal data.\n- right: Opt out of telemetry\n  text: 'You can disable telemetry at any time:'\n- right: Opt out of web analytics\n  text: 'For the web dashboard and website, you can opt out of PostHog analytics:'\nsale_or_sharing:\n  stance: prohibited\n  text: Sell your data\
  \ to third parties\n"
source_yaml_url: https://artifacts.apis.io/wraps-dev/privacy/wraps-dev-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from wraps-dev's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Amazon Web Services
- SES
- Infrastructure
- Platform
---
