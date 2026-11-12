---
api_specs:
- filename: counselor-guide-openapi.yml
  format: yaml
  label: Bicycle Guide Registry API
  slug: guide-registry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/counselor-guide/openapi/counselor-guide-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: If you create an account, we store the email address you sign in with.
  - category: financial
    text: We keep a record of what you bought so we can keep delivering it
  - category: device
    text: Your browser, device type, operating system, screen size and language
  - category: location
    text: Your approximate location (country and city), which Google works out from your IP address.
  - category: behavioral
    text: The pages you view, when you view them, and roughly how long you stay
  deletion:
    route: Email mike@peopleanalyst.com
    text: If you want your account and its data deleted, say so and it will be.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: sign-in and purchase receipts
    text: We use your address to deliver sign-in links, purchase receipts, and, if you request one, a note when a book guide you asked for is ready.
  - purpose: honor ownership and calculate refunds
    text: That log exists to honor your ownership and to calculate fair refunds — not to profile your reading.
  - purpose: operating the site
    text: Our hosting provider (Vercel) keeps standard server logs — requests, timestamps, IP addresses — used for operating the site.
  residency:
  - region: United States
    text: Google LLC runs Google Analytics for us as a service provider and may process the data in the United States.
  retention:
  - period: 14 months
    scope: Google Analytics event and user data
    text: Google Analytics keeps event and user data for 14 months, then deletes it.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: we don’t sell or share reader data with advertisers. Ever.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Counselor Guide
provenance_date: '2026-11-09'
provider_name: Counselor Guide
provider_slug: counselor-guide
slug: counselor-guide-privacy-policy
source_date: '2026-11-09'
source_filename: counselor-guide-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://counselor.guide/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Counselor Guide\naid: counselor-guide\nurl: https://counselor.guide/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: If you create an account, we store the email address you sign in with.\n- category: financial\n  text: We keep a record of what you bought so we can keep delivering it\n- category: device\n  text: Your browser, device type, operating system, screen size and language\n- category: location\n  text: Your approximate location (country and city), which Google works out from your IP address.\n- category: behavioral\n  text:\
  \ The pages you view, when you view them, and roughly how long you stay\npurposes:\n- purpose: sign-in and purchase receipts\n  text: We use your address to deliver sign-in links, purchase receipts, and, if you request one, a note when a\n    book guide you asked for is ready.\n- purpose: honor ownership and calculate refunds\n  text: That log exists to honor your ownership and to calculate fair refunds — not to profile your reading.\n- purpose: operating the site\n  text: Our hosting provider (Vercel) keeps standard server logs — requests, timestamps, IP addresses — used for\n    operating the site.\nretention:\n- scope: Google Analytics event and user data\n  period: 14 months\n  text: Google Analytics keeps event and user data for 14 months, then deletes it.\nresidency:\n- region: United States\n  text: Google LLC runs Google Analytics for us as a service provider and may process the data in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: Email mike@peopleanalyst.com\n  text: If you want your account and its data deleted, say so and it will be.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: we don’t sell or share reader data with advertisers. Ever.\n"
source_yaml_url: https://artifacts.apis.io/counselor-guide/privacy/counselor-guide-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- sale_or_sharing
summary_line: 12 quoted statements, read from Counselor Guide's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Counseling
- Psychotherapy
- Mental Health
- Education
- Professional Development
- Books
- MCP
---
