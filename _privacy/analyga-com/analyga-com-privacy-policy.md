---
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: tenant name and slug, username, hashed password, email (if provided for the dashboard or billing), and API key hashes.'
  - category: contact
    text: email (if provided for the dashboard or billing)
  - category: behavioral
    text: 'Analytics events: page views and custom events you send, including the website id, event name, timestamp, referrer, page path, and any event properties you attach.'
  - category: location
    text: 'Derived visitor signals: approximate location, browser, device, and operating system inferred from the request.'
  - category: financial
    text: 'Billing data: handled by Stripe; we do not store full card details.'
  deletion:
    route: dashboard or CLI
    text: You can delete data via the dashboard or CLI.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide analytics, funnels, and network rollups
    text: to provide analytics, funnels, and network rollups to you
  - purpose: authenticate requests and enforce quotas
    text: to authenticate requests and enforce plan quotas and rate limits
  - purpose: process billing
    text: to process billing via Stripe
  - purpose: secure, maintain, and improve the Service
    text: to secure, maintain, and improve the Service
  retention:
  - period: 30 days on Free
    scope: analytics data
    text: Analytics data is retained according to your plan's data-retention window (for example, 30 days on Free, longer on paid plans).
  - period: for the life of your tenant and for a reasonable period afterwards
    scope: account data
    text: Account data is retained for the life of your tenant and for a reasonable period afterwards to meet legal and accounting obligations.
  rights:
  - right: access, correct, delete, port
    text: you may have the right to access, correct, delete, or port your personal data
  - right: object or restrict processing
    text: to object to or restrict processing
  - right: lodge complaint
    text: to lodge a complaint with a supervisory authority
  role:
    text: For account data (your tenant, users, API keys, and billing) we act as a data controller
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data
  subprocessors:
    text: Stripe Payment processing for paid plans
    url: null
  transfers:
  - mechanism: SCC
    text: Where we transfer personal data internationally, we use appropriate safeguards such as Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: analyga
provenance_date: '2026-11-09'
provider_name: analyga
provider_slug: analyga-com
slug: analyga-com-privacy-policy
source_date: '2026-11-09'
source_filename: analyga-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://analyga.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: analyga\naid: analyga-com\nurl: https://analyga.com/privacy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For account data (your tenant, users, API keys, and billing) we act as a data controller\ndata_categories:\n- category: identifying\n  text: 'Account data: tenant name and slug, username, hashed password, email (if provided for the dashboard or\n    billing), and API key hashes.'\n- category: contact\n  text: email (if provided for the dashboard or billing)\n- category: behavioral\n  text: 'Analytics events: page views and custom events you send, including the website id, event name, timestamp,\n\
  \    referrer, page path, and any event properties you attach.'\n- category: location\n  text: 'Derived visitor signals: approximate location, browser, device, and operating system inferred from the\n    request.'\n- category: financial\n  text: 'Billing data: handled by Stripe; we do not store full card details.'\npurposes:\n- purpose: provide analytics, funnels, and network rollups\n  text: to provide analytics, funnels, and network rollups to you\n- purpose: authenticate requests and enforce quotas\n  text: to authenticate requests and enforce plan quotas and rate limits\n- purpose: process billing\n  text: to process billing via Stripe\n- purpose: secure, maintain, and improve the Service\n  text: to secure, maintain, and improve the Service\nretention:\n- scope: analytics data\n  period: 30 days on Free\n  text: Analytics data is retained according to your plan's data-retention window (for example, 30 days on Free,\n    longer on paid plans).\n- scope: account data\n  period: for\
  \ the life of your tenant and for a reasonable period afterwards\n  text: Account data is retained for the life of your tenant and for a reasonable period afterwards to meet legal\n    and accounting obligations.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Where we transfer personal data internationally, we use appropriate safeguards such as Standard Contractual\n    Clauses.\nsubprocessors:\n  url: null\n  text: Stripe Payment processing for paid plans\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: dashboard or CLI\n  text: You can delete data via the dashboard or CLI.\nrights:\n- right: access, correct, delete, port\n  text: you may have the right to access, correct, delete, or port your personal data\n- right: object or restrict processing\n  text: to object to or restrict processing\n- right: lodge complaint\n  text: to lodge a complaint with a supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data\n"
source_yaml_url: https://artifacts.apis.io/analyga-com/privacy/analyga-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from analyga's own page on 2026-11-09.
synthetic: false
tags:
- AI-native
- Software-as-a-Service
- Revenue Analytics
- Dashboards
- MCP
---
