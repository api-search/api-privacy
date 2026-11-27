---
api_specs:
- filename: pinnodds-com-drops-api-openapi.yml
  format: yaml
  label: pinnodds-com Drops API
  slug: pinnodds-com-drops-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinnodds-com/openapi/pinnodds-com-drops-api-openapi.yml
- filename: pinnodds-com-health-api-openapi.yml
  format: yaml
  label: pinnodds-com Health API
  slug: pinnodds-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinnodds-com/openapi/pinnodds-com-health-api-openapi.yml
- filename: pinnodds-com-kit-api-openapi.yml
  format: yaml
  label: pinnodds-com Kit API
  slug: pinnodds-com-kit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinnodds-com/openapi/pinnodds-com-kit-api-openapi.yml
- filename: pinnodds-com-ping-api-openapi.yml
  format: yaml
  label: pinnodds-com Ping API
  slug: pinnodds-com-ping-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinnodds-com/openapi/pinnodds-com-ping-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address Signup, key recovery, purchase, support
  - category: identifying
    text: API key (stored as a one-way hash), plan, expiry, usage counters (requests per day per key)
  - category: financial
    text: 'Payment records: amount, currency, plan, provider transaction id, status'
  - category: behavioral
    text: Acquisition source (e.g. "google / organic", a referrer domain, or a campaign tag) captured on your first visit
  - category: communication
    text: Support conversations (chat widget, email, Telegram)
  - category: device
    text: 'Server logs: IP address, request path, timestamp, user agent'
  deletion:
    route: Email us to delete account
    text: To delete your account outright, email us — we remove the account and its key immediately and purge remaining data on the schedule above.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and operation
    text: Create and operate your account, deliver your API key, send transactional emails (verification, receipts, expiry reminders).
  - purpose: Authentication and plan enforcement
    text: Authenticate requests, enforce plan limits, billing reconciliation.
  - purpose: Fulfil purchase, accounting, fraud prevention
    text: Fulfil the purchase, accounting, fraud prevention.
  - purpose: Channel analysis
    text: Understand which channels bring customers.
  - purpose: Security and abuse prevention
    text: Security, abuse prevention, per-IP rate limiting, debugging.
  - purpose: Site analytics and ad measurement
    text: Understand site usage, session replays and heatmaps, measure ad campaigns.
  residency:
  - region: EU
    text: Hosting — our servers in the EU
  retention:
  - period: for the life of the account, then deleted or anonymised within 90 days of deletion
    scope: Account and key data
    text: 'Account and key data: for the life of the account, then deleted or anonymised within 90 days of deletion.'
  - period: 10 years
    scope: Payment records
    text: 'Payment records: 10 years where required by tax and accounting law.'
  - period: 30 days
    scope: Server logs
    text: 'Server logs: typically 30 days.'
  - period: 24 months
    scope: Support conversations
    text: 'Support conversations: up to 24 months.'
  - period: 14 months
    scope: Analytics data
    text: 'Analytics data: per each provider''s retention (GA4 is set to 14 months).'
  rights:
  - right: Access, correct, export, delete
    text: you can access, correct, export or delete your data, restrict or object to processing, and withdraw consent at any time
  - right: Complain to supervisory authority
    text: You may also complain to your local supervisory authority.
  role:
    text: The data controller is the operator of pinnodds.com.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data
  subprocessors:
    text: Hosting — our servers in the EU; Cloudflare (CDN, DDoS protection, TLS) in front of them.
    url: null
  transfers:
  - mechanism: DPF
    text: transfers rely on the EU-US Data Privacy Framework and/or Standard Contractual Clauses
  - mechanism: SCC
    text: transfers rely on the EU-US Data Privacy Framework and/or Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: pinnodds-com
provenance_date: '2026-11-10'
provider_name: pinnodds-com
provider_slug: pinnodds-com
slug: pinnodds-com-privacy-policy
source_date: '2026-11-10'
source_filename: pinnodds-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://pinnodds.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: pinnodds-com\naid: pinnodds-com\nurl: https://pinnodds.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The data controller is the operator of pinnodds.com.\ndata_categories:\n- category: contact\n  text: Email address Signup, key recovery, purchase, support\n- category: identifying\n  text: API key (stored as a one-way hash), plan, expiry, usage counters (requests per day per key)\n- category: financial\n  text: 'Payment records: amount, currency, plan, provider transaction id, status'\n- category: behavioral\n  text: Acquisition source (e.g. \"google / organic\", a referrer domain,\
  \ or a campaign tag) captured on your first\n    visit\n- category: communication\n  text: Support conversations (chat widget, email, Telegram)\n- category: device\n  text: 'Server logs: IP address, request path, timestamp, user agent'\npurposes:\n- purpose: Account creation and operation\n  text: Create and operate your account, deliver your API key, send transactional emails (verification, receipts,\n    expiry reminders).\n- purpose: Authentication and plan enforcement\n  text: Authenticate requests, enforce plan limits, billing reconciliation.\n- purpose: Fulfil purchase, accounting, fraud prevention\n  text: Fulfil the purchase, accounting, fraud prevention.\n- purpose: Channel analysis\n  text: Understand which channels bring customers.\n- purpose: Security and abuse prevention\n  text: Security, abuse prevention, per-IP rate limiting, debugging.\n- purpose: Site analytics and ad measurement\n  text: Understand site usage, session replays and heatmaps, measure ad campaigns.\nretention:\n\
  - scope: Account and key data\n  period: for the life of the account, then deleted or anonymised within 90 days of deletion\n  text: 'Account and key data: for the life of the account, then deleted or anonymised within 90 days of deletion.'\n- scope: Payment records\n  period: 10 years\n  text: 'Payment records: 10 years where required by tax and accounting law.'\n- scope: Server logs\n  period: 30 days\n  text: 'Server logs: typically 30 days.'\n- scope: Support conversations\n  period: 24 months\n  text: 'Support conversations: up to 24 months.'\n- scope: Analytics data\n  period: 14 months\n  text: 'Analytics data: per each provider''s retention (GA4 is set to 14 months).'\nresidency:\n- region: EU\n  text: Hosting — our servers in the EU\ntransfers:\n- mechanism: DPF\n  text: transfers rely on the EU-US Data Privacy Framework and/or Standard Contractual Clauses\n- mechanism: SCC\n  text: transfers rely on the EU-US Data Privacy Framework and/or Standard Contractual Clauses\nsubprocessors:\n\
  \  url: null\n  text: Hosting — our servers in the EU; Cloudflare (CDN, DDoS protection, TLS) in front of them.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email us to delete account\n  text: To delete your account outright, email us — we remove the account and its key immediately and purge remaining\n    data on the schedule above.\nrights:\n- right: Access, correct, export, delete\n  text: you can access, correct, export or delete your data, restrict or object to processing, and withdraw consent\n    at any time\n- right: Complain to supervisory authority\n  text: You may also complain to your local supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data\n"
source_yaml_url: https://artifacts.apis.io/pinnodds-com/privacy/pinnodds-com-privacy-policy.yml
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
- sale_or_sharing
summary_line: 26 quoted statements, read from pinnodds-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sports
- Odds
- Real-Time
- Pinnacle
---
