---
api_specs:
- filename: apizone-io-status-api-openapi.yml
  format: yaml
  label: apizone-io Status API
  slug: apizone-io-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apizone-io/openapi/apizone-io-status-api-openapi.yml
- filename: apizone-io-uptime-api-openapi.yml
  format: yaml
  label: apizone-io Uptime API
  slug: apizone-io-uptime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apizone-io/openapi/apizone-io-uptime-api-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: identifying
    text: Standard server logs (IP address, user agent, pages requested) are processed by our hosting provider (Vercel)
  - category: contact
    text: we store your email address, the category you chose, and the time you confirmed
  - category: financial
    text: We store only the Stripe customer and subscription identifiers needed to match a payment to your alert subscription.
  - category: behavioral
    text: Vercel Web Analytics (privacy-friendly, cookieless page-view counts) and Google Analytics to understand how the site is used
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: serve the site and prevent abuse
    text: Standard server logs (IP address, user agent, pages requested) are processed by our hosting provider (Vercel) to serve the site and prevent abuse.
  - purpose: deliver outage alerts
    text: If you add the webhook add-on, we also store the Slack, Discord, or Microsoft Teams webhook URLs you provide so we can deliver alerts to them.
  - purpose: understand site usage
    text: We use Vercel Web Analytics (privacy-friendly, cookieless page-view counts) and Google Analytics to understand how the site is used.
  - purpose: show advertising
    text: We use Google AdSense to show ads.
  retention:
  - period: a few days
    scope: reports from the status button
    text: reports are deleted after a few days
  - period: null
    scope: rate-limit IPs
    text: those IPs are held in memory only and are not stored
  rights:
  - right: access
    text: To access, correct, or delete anything we hold about you
  - right: correction
    text: To access, correct, or delete anything we hold about you
  - right: deletion
    text: you can ask us to delete your data at any time
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
name: apizone-io
provenance_date: '2026-11-09'
provider_name: apizone-io
provider_slug: apizone-io
slug: apizone-io-privacy-policy
source_date: '2026-11-09'
source_filename: apizone-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apizone.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: apizone-io\naid: apizone-io\nurl: https://apizone.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Standard server logs (IP address, user agent, pages requested) are processed by our hosting provider (Vercel)\n- category: contact\n  text: we store your email address, the category you chose, and the time you confirmed\n- category: financial\n  text: We store only the Stripe customer and subscription identifiers needed to match a payment to your alert subscription.\n- category: behavioral\n  text: Vercel Web Analytics (privacy-friendly,\
  \ cookieless page-view counts) and Google Analytics to understand\n    how the site is used\npurposes:\n- purpose: serve the site and prevent abuse\n  text: Standard server logs (IP address, user agent, pages requested) are processed by our hosting provider (Vercel)\n    to serve the site and prevent abuse.\n- purpose: deliver outage alerts\n  text: If you add the webhook add-on, we also store the Slack, Discord, or Microsoft Teams webhook URLs you provide\n    so we can deliver alerts to them.\n- purpose: understand site usage\n  text: We use Vercel Web Analytics (privacy-friendly, cookieless page-view counts) and Google Analytics to understand\n    how the site is used.\n- purpose: show advertising\n  text: We use Google AdSense to show ads.\nretention:\n- scope: reports from the status button\n  period: a few days\n  text: reports are deleted after a few days\n- scope: rate-limit IPs\n  period: null\n  text: those IPs are held in memory only and are not stored\nresidency: []\ntransfers:\
  \ []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: To access, correct, or delete anything we hold about you\n- right: correction\n  text: To access, correct, or delete anything we hold about you\n- right: deletion\n  text: you can ask us to delete your data at any time\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apizone-io/privacy/apizone-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- rights
summary_line: 13 quoted statements, read from apizone-io's own page on 2026-11-09.
synthetic: false
tags:
- API Monitoring
- Status
- Uptime
- Developer Tools
- MCP
---
