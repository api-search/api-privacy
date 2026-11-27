---
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: we store your email address, your API key, your plan tier, and your usage counters (screenshots taken per billing period)
  - category: device
    text: standard request metadata (IP address, browser/device info)
  - category: behavioral
    text: pseudonymous usage events (page views, clicks)
  - category: financial
    text: we receive only your subscription status and plan from them via webhook
  - category: communication
    text: we only see the wallet address and payment amount, no other personal data is required
  deletion:
    route: email request
    text: You can ask us to access, correct, export, or delete your account data at any time by emailing [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: site analytics
    text: to help us understand how the site is used
  - purpose: authenticate requests and enforce plan limits
    text: needed to authenticate requests and enforce plan limits
  - purpose: abuse prevention, rate limiting and debugging
    text: for abuse prevention, rate-limit enforcement, and debugging
  - purpose: billing
    text: billing and subscription data
  retention:
  - period: null
    scope: account and usage data
    text: We keep account and usage data for as long as your account is active, plus a reasonable period afterward for billing records and legal compliance.
  - period: null
    scope: screenshot content
    text: The default cache TTL is 0 — a screenshot or PDF is generated, returned in the API response, and then discarded; we don't keep a copy.
  - period: null
    scope: operational logs
    text: We may briefly retain request metadata (the target URL, timestamp, and response status — not the rendered content)
  rights:
  - right: access, correct, export, delete
    text: You can ask us to access, correct, export, or delete your account data at any time
  - right: GDPR/UK GDPR rights
    text: If you're in the EU/EEA or UK, this includes the rights granted under GDPR/UK GDPR.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We don't sell your data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Some of these providers process data outside your home country. We only work with providers that offer an appropriate legal basis for that transfer under their own terms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: shotanvil-com
provenance_date: '2026-11-10'
provider_name: shotanvil-com
provider_slug: shotanvil-com
slug: shotanvil-com-privacy-policy
source_date: '2026-11-10'
source_filename: shotanvil-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://shotanvil.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: shotanvil-com\naid: shotanvil-com\nurl: https://shotanvil.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we store your email address, your API key, your plan tier, and your usage counters (screenshots taken per\n    billing period)\n- category: device\n  text: standard request metadata (IP address, browser/device info)\n- category: behavioral\n  text: pseudonymous usage events (page views, clicks)\n- category: financial\n  text: we receive only your subscription status and plan from them via webhook\n- category: communication\n\
  \  text: we only see the wallet address and payment amount, no other personal data is required\npurposes:\n- purpose: site analytics\n  text: to help us understand how the site is used\n- purpose: authenticate requests and enforce plan limits\n  text: needed to authenticate requests and enforce plan limits\n- purpose: abuse prevention, rate limiting and debugging\n  text: for abuse prevention, rate-limit enforcement, and debugging\n- purpose: billing\n  text: billing and subscription data\nretention:\n- scope: account and usage data\n  period: null\n  text: We keep account and usage data for as long as your account is active, plus a reasonable period afterward\n    for billing records and legal compliance.\n- scope: screenshot content\n  period: null\n  text: The default cache TTL is 0 — a screenshot or PDF is generated, returned in the API response, and then discarded;\n    we don't keep a copy.\n- scope: operational logs\n  period: null\n  text: We may briefly retain request metadata\
  \ (the target URL, timestamp, and response status — not the rendered\n    content)\nresidency: []\ntransfers:\n- mechanism: other\n  text: Some of these providers process data outside your home country. We only work with providers that offer an\n    appropriate legal basis for that transfer under their own terms.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: You can ask us to access, correct, export, or delete your account data at any time by emailing [email protected]\n    .\nrights:\n- right: access, correct, export, delete\n  text: You can ask us to access, correct, export, or delete your account data at any time\n- right: GDPR/UK GDPR rights\n  text: If you're in the EU/EEA or UK, this includes the rights granted under GDPR/UK GDPR.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell your data.\n"
source_yaml_url: https://artifacts.apis.io/shotanvil-com/privacy/shotanvil-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from shotanvil-com's own page on 2026-11-10.
synthetic: false
tags:
- API Management
- Integration
- Enterprise
- Security
- Scalability
---
