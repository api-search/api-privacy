---
api_specs:
- filename: aeoinspector-com-api-openapi.json
  format: json
  label: AEO Inspector Api API
  slug: aeo-inspector-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aeoinspector-com/openapi/_original/aeoinspector-com-api-openapi.json
claim_count: 18
description: ''
doc:
  data_categories:
  - category: device
    text: Daily counters keyed by a SHA-256 hash of your IP address (for IPv6, the /64), of your network (/24 or /48) and of your browser's random ID.
  - category: contact
    text: The tracked URL, the email address you gave, the weekly results, and a log of the alert emails we sent
  - category: behavioral
    text: The URL you checked and what we found on that site (scores, checks, fixes, crawled page data)
  deletion:
    route: email hello@aeoinspector.com
    text: To have a result, tracking record or email address deleted before it expires, email hello@aeoinspector.com with the link.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Free-check rate limiting
    text: so we can count 1 free check a day per browser.
  - purpose: Delivering pages
    text: Like any web host, it processes your IP address to deliver pages.
  - purpose: Tracking alert emails
    text: Tracking alert emails are sent through Cloudflare's email service
  retention:
  - period: 30 days, then deleted automatically
    scope: Check and report results
    text: 30 days, then deleted automatically
  - period: 24 hours
    scope: Re-check cache
    text: 24 hours
  - period: 30 days after the last check of that domain
    scope: Badge record
    text: 30 days after the last check of that domain
  - period: Deleted within 48 hours
    scope: Free-check counters
    text: Deleted within 48 hours
  - period: 400 days in your browser (you can delete it any time)
    scope: Cookie aeo_fc
    text: 400 days in your browser (you can delete it any time)
  - period: 120 days after the last update
    scope: Weekly tracking
    text: 120 days after the last update
  - period: Kept as daily totals
    scope: Usage stats
    text: Kept as daily totals
  - period: Up to 7 days
    scope: Service logs
    text: Up to 7 days
  rights:
  - right: Stop tracking emails
    text: Every tracking email has a link to stop emails.
  - right: Early deletion on request
    text: To have a result, tracking record or email address deleted before it expires, email hello@aeoinspector.com with the link.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Cloudflare hosts the site and stores the data above (Workers, KV and Durable Objects).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AEO Inspector
provenance_date: '2026-11-09'
provider_name: AEO Inspector
provider_slug: aeoinspector-com
slug: aeoinspector-com-privacy-policy
source_date: '2026-11-09'
source_filename: aeoinspector-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aeoinspector.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AEO Inspector\naid: aeoinspector-com\nurl: https://aeoinspector.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: device\n  text: Daily counters keyed by a SHA-256 hash of your IP address (for IPv6, the /64), of your network (/24 or /48)\n    and of your browser's random ID.\n- category: contact\n  text: The tracked URL, the email address you gave, the weekly results, and a log of the alert emails we sent\n- category: behavioral\n  text: The URL you checked and what we found on that site (scores, checks, fixes, crawled page data)\npurposes:\n- purpose:\
  \ Free-check rate limiting\n  text: so we can count 1 free check a day per browser.\n- purpose: Delivering pages\n  text: Like any web host, it processes your IP address to deliver pages.\n- purpose: Tracking alert emails\n  text: Tracking alert emails are sent through Cloudflare's email service\nretention:\n- scope: Check and report results\n  period: 30 days, then deleted automatically\n  text: 30 days, then deleted automatically\n- scope: Re-check cache\n  period: 24 hours\n  text: 24 hours\n- scope: Badge record\n  period: 30 days after the last check of that domain\n  text: 30 days after the last check of that domain\n- scope: Free-check counters\n  period: Deleted within 48 hours\n  text: Deleted within 48 hours\n- scope: Cookie aeo_fc\n  period: 400 days in your browser (you can delete it any time)\n  text: 400 days in your browser (you can delete it any time)\n- scope: Weekly tracking\n  period: 120 days after the last update\n  text: 120 days after the last update\n- scope: Usage\
  \ stats\n  period: Kept as daily totals\n  text: Kept as daily totals\n- scope: Service logs\n  period: Up to 7 days\n  text: Up to 7 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare hosts the site and stores the data above (Workers, KV and Durable Objects).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email hello@aeoinspector.com\n  text: To have a result, tracking record or email address deleted before it expires, email hello@aeoinspector.com\n    with the link.\nrights:\n- right: Stop tracking emails\n  text: Every tracking email has a link to stop emails.\n- right: Early deletion on request\n  text: To have a result, tracking record or email address deleted before it expires, email hello@aeoinspector.com\n    with the link.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aeoinspector-com/privacy/aeoinspector-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 18 quoted statements, read from AEO Inspector's own page on 2026-11-09.
synthetic: false
tags:
- AI crawler optimization
- Answer Engine Optimization
- SEO
- Agent‑Ready Checks
- Structured Data
---
