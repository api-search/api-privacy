---
api_specs:
- filename: siftwright-com-api-openapi.json
  format: json
  label: Siftwright API API
  slug: siftwright-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/siftwright-com/openapi/_original/siftwright-com-api-openapi.json
claim_count: 15
description: ''
doc:
  data_categories:
  - category: contact
    text: We keep your email address, Stripe customer and subscription IDs, plan, subscription status
  - category: device
    text: your country, browser and device type
  - category: communication
    text: The request, waitlist and newsletter forms send what you type to us by email.
  - category: behavioral
    text: a count of successful results used this period
  deletion:
    route: email support@siftwright.com
    text: To ask what we hold about you, or to have it deleted, email support@siftwright.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: analytics
    text: To count visits we use Cloudflare Web Analytics
  - purpose: demo limit enforcement
    text: To enforce the daily demo limit we keep a counter keyed to a one-way hash of your IP address
  - purpose: reply to messages
    text: we use your message and address only to reply and help you.
  - purpose: run and billing
    text: to run and bill the service.
  retention:
  - period: 24 hours
    scope: demo results cache
    text: the result may be cached for up to 24 hours
  - period: daily
    scope: demo limit counters
    text: we clear those counters daily
  - period: one hour
    scope: spam counter
    text: for up to one hour
  - period: 7 days
    scope: Apify run data
    text: keeps run data (including screenshot and PDF files) for up to 7 days
  rights:
  - right: access and deletion on request
    text: To ask what we hold about you, or to have it deleted
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: siftwright-com
provenance_date: '2026-11-10'
provider_name: siftwright-com
provider_slug: siftwright-com
slug: siftwright-com-privacy-policy
source_date: '2026-11-10'
source_filename: siftwright-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://siftwright.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: siftwright-com\naid: siftwright-com\nurl: https://siftwright.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: We keep your email address, Stripe customer and subscription IDs, plan, subscription status\n- category: device\n  text: your country, browser and device type\n- category: communication\n  text: The request, waitlist and newsletter forms send what you type to us by email.\n- category: behavioral\n  text: a count of successful results used this period\npurposes:\n- purpose: analytics\n  text: To count visits we use Cloudflare\
  \ Web Analytics\n- purpose: demo limit enforcement\n  text: To enforce the daily demo limit we keep a counter keyed to a one-way hash of your IP address\n- purpose: reply to messages\n  text: we use your message and address only to reply and help you.\n- purpose: run and billing\n  text: to run and bill the service.\nretention:\n- scope: demo results cache\n  period: 24 hours\n  text: the result may be cached for up to 24 hours\n- scope: demo limit counters\n  period: daily\n  text: we clear those counters daily\n- scope: spam counter\n  period: one hour\n  text: for up to one hour\n- scope: Apify run data\n  period: 7 days\n  text: keeps run data (including screenshot and PDF files) for up to 7 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@siftwright.com\n  text: To ask what we hold about you, or to have it deleted, email support@siftwright.com\nrights:\n- right: access\
  \ and deletion on request\n  text: To ask what we hold about you, or to have it deleted\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell data.\n"
source_yaml_url: https://artifacts.apis.io/siftwright-com/privacy/siftwright-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from siftwright-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data
- Artificial Intelligence
- Web Data
---
