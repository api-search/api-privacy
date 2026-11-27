---
api_specs:
- filename: aggrometer-com-openapi.yml
  format: yaml
  label: Aggrometer API
  slug: aggrometer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aggrometer-com/openapi/aggrometer-com-openapi.yml
claim_count: 13
description: ''
doc:
  data_categories:
  - category: contact
    text: the email address and Stripe customer id created at checkout (processed by Stripe)
  - category: identifying
    text: your API key identifier (we store only a hash of the key itself)
  - category: behavioral
    text: per-key daily usage counts for quota enforcement and billing
  - category: device
    text: Standard server logs at our infrastructure provider (Cloudflare) may include IP addresses for security and abuse prevention.
  - category: identifying
    text: our datasets include publicly visible gaming identifiers such as channel and streamer names from platform interfaces
  deletion:
    route: email support@aggrometer.com
    text: Email support@aggrometer.com to access, correct, or delete your customer data, or to remove a public identifier from our outputs.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: quota enforcement and billing
    text: per-key daily usage counts for quota enforcement and billing
  - purpose: security and abuse prevention
    text: may include IP addresses for security and abuse prevention
  residency:
  - region: United States
    text: with primary jurisdiction in the United States
  rights:
  - right: access
    text: Email support@aggrometer.com to access, correct, or delete your customer data
  - right: correction
    text: Email support@aggrometer.com to access, correct, or delete your customer data
  - right: removal of public identifier
    text: To request removal of an identifier that refers to you, email support@aggrometer.com.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell customer personal information, run ads, or share customer data with third parties except processors (Stripe, Cloudflare) needed to run the Service.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Aggrometer
provenance_date: '2026-11-09'
provider_name: Aggrometer
provider_slug: aggrometer-com
slug: aggrometer-com-privacy-policy
source_date: '2026-11-09'
source_filename: aggrometer-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aggrometer.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Aggrometer\naid: aggrometer-com\nurl: https://aggrometer.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: the email address and Stripe customer id created at checkout (processed by Stripe)\n- category: identifying\n  text: your API key identifier (we store only a hash of the key itself)\n- category: behavioral\n  text: per-key daily usage counts for quota enforcement and billing\n- category: device\n  text: Standard server logs at our infrastructure provider (Cloudflare) may include IP addresses for security and\n    abuse prevention.\n\
  - category: identifying\n  text: our datasets include publicly visible gaming identifiers such as channel and streamer names from platform\n    interfaces\npurposes:\n- purpose: quota enforcement and billing\n  text: per-key daily usage counts for quota enforcement and billing\n- purpose: security and abuse prevention\n  text: may include IP addresses for security and abuse prevention\nretention: []\nresidency:\n- region: United States\n  text: with primary jurisdiction in the United States\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@aggrometer.com\n  text: Email support@aggrometer.com to access, correct, or delete your customer data, or to remove a public identifier\n    from our outputs.\nrights:\n- right: access\n  text: Email support@aggrometer.com to access, correct, or delete your customer data\n- right: correction\n  text: Email support@aggrometer.com to access, correct, or delete\
  \ your customer data\n- right: removal of public identifier\n  text: To request removal of an identifier that refers to you, email support@aggrometer.com.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell customer personal information, run ads, or share customer data with third parties except\n    processors (Stripe, Cloudflare) needed to run the Service.\n"
source_yaml_url: https://artifacts.apis.io/aggrometer-com/privacy/aggrometer-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 13 quoted statements, read from Aggrometer's own page on 2026-11-09.
synthetic: false
tags:
- Gaming
- Data
- Analytics
- Software-as-a-Service
---
