---
api_specs:
- filename: octocrawl-dev-openapi-generated.yml
  format: yaml
  label: octocrawl-dev API
  slug: octocrawl-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/octocrawl-dev/openapi/_ae-authored/octocrawl-dev-openapi-generated.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: A random identifier, signed by the service, kept for a year.
  - category: contact
    text: 'Firebase keeps: your email address;'
  - category: location
    text: 'Google Cloud records each HTTP request: time, method, path and query, status, response time, your IP address, user agent and referring page.'
  - category: device
    text: 'Preview outcomes. For each preview: its state (for example success or blocked ), the diagnostic code, the host of the page you asked for (never its path or query), whether you set options, and the server time.'
  deletion:
    route: Settings in your dashboard or email us
    text: To delete your account, use Settings in your dashboard or email us.
  dpa:
    available: null
    text: null
    url: null
  residency:
  - region: Singapore
    text: The service runs on Google Cloud Run in Singapore.
  retention:
  - period: does not save
    scope: web preview result
    text: 'The service does not save the result: your recent runs live in the page and are gone when you leave it.'
  - period: ten minutes
    scope: hosted API call result
    text: The result of each call for ten minutes, so that GET /v1/scrapes/:id can return it, then deleted with any file it read.
  - period: 30 days
    scope: page events, preview outcomes and request log
    text: Events, outcomes and this request log are kept for 30 days and then deleted.
  - period: one day after the day they count
    scope: daily preview counters
    text: These counters are kept in Google Cloud Firestore and expire one day after the day they count;
  - period: a year
    scope: visitor cookie
    text: A random identifier, signed by the service, kept for a year.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Cloudflare passes requests along, and the service runs on Google Cloud in Singapore.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: octocrawl-dev
provenance_date: '2026-11-10'
provider_name: octocrawl-dev
provider_slug: octocrawl-dev
slug: octocrawl-dev-privacy-policy
source_date: '2026-11-10'
source_filename: octocrawl-dev-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://octocrawl.dev/docs/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: octocrawl-dev\naid: octocrawl-dev\nurl: https://octocrawl.dev/docs/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: A random identifier, signed by the service, kept for a year.\n- category: contact\n  text: 'Firebase keeps: your email address;'\n- category: location\n  text: 'Google Cloud records each HTTP request: time, method, path and query, status, response time, your IP address,\n    user agent and referring page.'\n- category: device\n  text: 'Preview outcomes. For each preview: its state (for example success or blocked ),\
  \ the diagnostic code, the\n    host of the page you asked for (never its path or query), whether you set options, and the server time.'\npurposes: []\nretention:\n- scope: web preview result\n  period: does not save\n  text: 'The service does not save the result: your recent runs live in the page and are gone when you leave it.'\n- scope: hosted API call result\n  period: ten minutes\n  text: The result of each call for ten minutes, so that GET /v1/scrapes/:id can return it, then deleted with any\n    file it read.\n- scope: page events, preview outcomes and request log\n  period: 30 days\n  text: Events, outcomes and this request log are kept for 30 days and then deleted.\n- scope: daily preview counters\n  period: one day after the day they count\n  text: These counters are kept in Google Cloud Firestore and expire one day after the day they count;\n- scope: visitor cookie\n  period: a year\n  text: A random identifier, signed by the service, kept for a year.\nresidency:\n- region:\
  \ Singapore\n  text: The service runs on Google Cloud Run in Singapore.\ntransfers: []\nsubprocessors:\n  url: null\n  text: Cloudflare passes requests along, and the service runs on Google Cloud in Singapore.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings in your dashboard or email us\n  text: To delete your account, use Settings in your dashboard or email us.\nrights: []\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/octocrawl-dev/privacy/octocrawl-dev-privacy-policy.yml
stated_fields:
- data_categories
- retention
- residency
- subprocessors
- deletion
summary_line: 12 quoted statements, read from octocrawl-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web Scraping
- Data Extraction
- Software-as-a-Service
- Automation
---
