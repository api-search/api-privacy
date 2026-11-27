---
claim_count: 7
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'log request metadata for operational monitoring: timestamp, client IP address, tool name, dataset dimensions'
  - category: financial
    text: Card payments are processed by Stripe via the Machine Payments Protocol . When you pay by card, Stripe receives the payment amount and your card or payment-method token.
  deletion:
    route: automatic
    text: Temporary files used during processing are deleted immediately when the request completes, whether it succeeds or fails.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operational monitoring
    text: We log request metadata for operational monitoring
  retention:
  - period: 90 days
    scope: request logs
    text: Logs are retained for 90 days and then automatically deleted.
  - period: null
    scope: submitted files
    text: the file is loaded into memory, analyzed, and discarded. We do not store your files, cache their contents, or write them to persistent storage.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: Caliper does not share submitted file data with third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: caliper-fit
provenance_date: '2026-11-09'
provider_name: caliper-fit
provider_slug: caliper-fit
slug: caliper-fit-privacy-policy
source_date: '2026-11-09'
source_filename: caliper-fit-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://caliper.fit/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: caliper-fit\naid: caliper-fit\nurl: https://caliper.fit/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'log request metadata for operational monitoring: timestamp, client IP address, tool name, dataset dimensions'\n- category: financial\n  text: Card payments are processed by Stripe via the Machine Payments Protocol . When you pay by card, Stripe receives\n    the payment amount and your card or payment-method token.\npurposes:\n- purpose: operational monitoring\n  text: We log request metadata for operational monitoring\nretention:\n\
  - scope: request logs\n  period: 90 days\n  text: Logs are retained for 90 days and then automatically deleted.\n- scope: submitted files\n  period: null\n  text: the file is loaded into memory, analyzed, and discarded. We do not store your files, cache their contents,\n    or write them to persistent storage.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: automatic\n  text: Temporary files used during processing are deleted immediately when the request completes, whether it succeeds\n    or fails.\nrights: []\nsale_or_sharing:\n  stance: conditional\n  text: Caliper does not share submitted file data with third parties.\n"
source_yaml_url: https://artifacts.apis.io/caliper-fit/privacy/caliper-fit-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 7 quoted statements, read from caliper-fit's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Geometry
- CAD
- Metadata
- MCP
---
