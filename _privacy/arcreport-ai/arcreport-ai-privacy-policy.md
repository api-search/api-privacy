---
claim_count: 13
description: ''
doc:
  data_categories:
  - category: contact
    text: Account data — your email address (used for sign-in and to contact you)
  - category: device
    text: Technical data — basic request logs used to run the service, prevent abuse, and rate-limit free scans
  - category: location
    text: the visitor’s country (a two-letter code from our host, Vercel)
  - category: financial
    text: Older accounts may still have Stripe customer identifiers on file
  deletion:
    route: email request to arcreport@mail.grokbot.com
    text: You can ask us to access or delete your data at any time by emailing arcreport@mail.grokbot.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run scans and deliver results
    text: To run your scans and deliver results, sign-in links, and (if you opt in) monitoring alerts.
  - purpose: operate, secure and improve service
    text: To operate, secure, and improve the service, and to prevent abuse.
  retention:
  - period: while your account is active
    scope: account and scan data
    text: We keep account and scan data while your account is active.
  - period: 30 days
    scope: hashed caller id
    text: We also keep a hashed caller id (an HMAC of the network address, not the raw IP) for 30 days
  - period: 30 days
    scope: ref label and precheck records
    text: deleted after 30 days
  rights:
  - right: access and deletion
    text: You can ask us to access or delete your data at any time by emailing arcreport@mail.grokbot.com
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data
  subprocessors:
    text: We use a small set of processors strictly to run ARC
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: arcreport-ai
provenance_date: '2026-11-09'
provider_name: arcreport-ai
provider_slug: arcreport-ai
slug: arcreport-ai-privacy-policy
source_date: '2026-11-09'
source_filename: arcreport-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.arcreport.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: arcreport-ai\naid: arcreport-ai\nurl: https://www.arcreport.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Account data — your email address (used for sign-in and to contact you)\n- category: device\n  text: Technical data — basic request logs used to run the service, prevent abuse, and rate-limit free scans\n- category: location\n  text: the visitor’s country (a two-letter code from our host, Vercel)\n- category: financial\n  text: Older accounts may still have Stripe customer identifiers on file\npurposes:\n- purpose: run scans\
  \ and deliver results\n  text: To run your scans and deliver results, sign-in links, and (if you opt in) monitoring alerts.\n- purpose: operate, secure and improve service\n  text: To operate, secure, and improve the service, and to prevent abuse.\nretention:\n- scope: account and scan data\n  period: while your account is active\n  text: We keep account and scan data while your account is active.\n- scope: hashed caller id\n  period: 30 days\n  text: We also keep a hashed caller id (an HMAC of the network address, not the raw IP) for 30 days\n- scope: ref label and precheck records\n  period: 30 days\n  text: deleted after 30 days\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: We use a small set of processors strictly to run ARC\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to arcreport@mail.grokbot.com\n  text: You can ask us to access or delete your data at any time by emailing arcreport@mail.grokbot.com\nrights:\n- right:\
  \ access and deletion\n  text: You can ask us to access or delete your data at any time by emailing arcreport@mail.grokbot.com\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data\n"
source_yaml_url: https://artifacts.apis.io/arcreport-ai/privacy/arcreport-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from arcreport-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- E-Commerce
- Analytics
- Checkout
---
