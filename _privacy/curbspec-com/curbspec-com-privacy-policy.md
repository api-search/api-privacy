---
claim_count: 11
description: ''
doc:
  data_categories:
  - category: identifying
    text: You paste a VIN, a listing, or what you know, plus a stated mileage when it is not in the paste.
  - category: contact
    text: Stripe collects your email on Checkout. We store that email on the report so we can send you the report URL.
  - category: device
    text: Vercel hosts the app and may record page views (path, referrer, country, device) so we can see whether the preview converts.
  deletion:
    route: Email joe@swantron.com
    text: To ask that a report or email be removed, write joe@swantron.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Decode vehicle and look up campaigns
    text: We send a VIN (when we have one) to NHTSA to decode the vehicle and look up year/make/model campaigns.
  - purpose: Research known issues
    text: Most reports send the identified vehicle (year, make, model, engine) to Google's Gemini API to research known issues.
  - purpose: Send report URL
    text: We store that email on the report so we can send you the report URL.
  - purpose: Measure preview conversion
    text: may record page views (path, referrer, country, device) so we can see whether the preview converts.
  retention:
  - period: null
    scope: Vehicle snapshot
    text: We store that snapshot in Postgres so the same URL keeps working.
  - period: null
    scope: Unpaid previews
    text: Unpaid previews may be deleted later so the table is not all tire-kickers.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell email lists or VIN data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CurbSpec
provenance_date: '2026-11-09'
provider_name: CurbSpec
provider_slug: curbspec-com
slug: curbspec-com-privacy-policy
source_date: '2026-11-09'
source_filename: curbspec-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://curbspec.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CurbSpec\naid: curbspec-com\nurl: https://curbspec.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: You paste a VIN, a listing, or what you know, plus a stated mileage when it is not in the paste.\n- category: contact\n  text: Stripe collects your email on Checkout. We store that email on the report so we can send you the report\n    URL.\n- category: device\n  text: Vercel hosts the app and may record page views (path, referrer, country, device) so we can see whether the\n    preview converts.\npurposes:\n- purpose: Decode vehicle\
  \ and look up campaigns\n  text: We send a VIN (when we have one) to NHTSA to decode the vehicle and look up year/make/model campaigns.\n- purpose: Research known issues\n  text: Most reports send the identified vehicle (year, make, model, engine) to Google's Gemini API to research\n    known issues.\n- purpose: Send report URL\n  text: We store that email on the report so we can send you the report URL.\n- purpose: Measure preview conversion\n  text: may record page views (path, referrer, country, device) so we can see whether the preview converts.\nretention:\n- scope: Vehicle snapshot\n  period: null\n  text: We store that snapshot in Postgres so the same URL keeps working.\n- scope: Unpaid previews\n  period: null\n  text: Unpaid previews may be deleted later so the table is not all tire-kickers.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email joe@swantron.com\n  text: To ask that\
  \ a report or email be removed, write joe@swantron.com .\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell email lists or VIN data.\n"
source_yaml_url: https://artifacts.apis.io/curbspec-com/privacy/curbspec-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 11 quoted statements, read from CurbSpec's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Automotive
- Used Vehicles
- VIN
- Vehicle History
- Vehicle Recalls
- Maintenance
- MCP
---
