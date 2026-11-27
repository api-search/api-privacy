---
api_specs:
- filename: aipricinghub-com-changelog-api-openapi.yml
  format: yaml
  label: aipricinghub-com Changelog API
  slug: aipricinghub-com-changelog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aipricinghub-com/openapi/aipricinghub-com-changelog-api-openapi.yml
- filename: aipricinghub-com-freshness-api-openapi.yml
  format: yaml
  label: aipricinghub-com Freshness API
  slug: aipricinghub-com-freshness-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aipricinghub-com/openapi/aipricinghub-com-freshness-api-openapi.yml
- filename: aipricinghub-com-history-api-openapi.yml
  format: yaml
  label: aipricinghub-com History API
  slug: aipricinghub-com-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aipricinghub-com/openapi/aipricinghub-com-history-api-openapi.yml
- filename: aipricinghub-com-industry-api-openapi.yml
  format: yaml
  label: aipricinghub-com Industry API
  slug: aipricinghub-com-industry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aipricinghub-com/openapi/aipricinghub-com-industry-api-openapi.yml
- filename: aipricinghub-com-market-api-openapi.yml
  format: yaml
  label: aipricinghub-com Market API
  slug: aipricinghub-com-market-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aipricinghub-com/openapi/aipricinghub-com-market-api-openapi.yml
- filename: aipricinghub-com-models-api-openapi.yml
  format: yaml
  label: aipricinghub-com Models API
  slug: aipricinghub-com-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aipricinghub-com/openapi/aipricinghub-com-models-api-openapi.yml
- filename: aipricinghub-com-providers-api-openapi.yml
  format: yaml
  label: aipricinghub-com Providers API
  slug: aipricinghub-com-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aipricinghub-com/openapi/aipricinghub-com-providers-api-openapi.yml
- filename: aipricinghub-com-rankings-api-openapi.yml
  format: yaml
  label: aipricinghub-com Rankings API
  slug: aipricinghub-com-rankings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aipricinghub-com/openapi/aipricinghub-com-rankings-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: When you explicitly opt in, AI Pricing Hub stores your email address, selected locale, consent timestamp, privacy-policy version, and limited signup attribution to send launch and AI pricing updates.
  - category: behavioral
    text: The site may collect aggregate usage events to understand page views, feature use, filters, exports, alerts, and navigation quality.
  - category: device
    text: Static features may store preferences such as theme, language, experiment variant, saved explorer filters, calculator state, or alert configuration locally in the browser.
  deletion:
    route: Email request
    text: For privacy questions, consent withdrawal, or deletion requests, email [email protected] .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Send launch and pricing updates
    text: to send launch and AI pricing updates
  - purpose: Analytics
    text: The site may collect aggregate usage events to understand page views, feature use, filters, exports, alerts, and navigation quality.
  - purpose: Abuse prevention
    text: The signup endpoint validates requests and uses short-lived hashed network signals, timing checks, a honeypot, rate limits, and duplicate detection.
  retention:
  - period: null
    scope: Active waitlist records
    text: Active waitlist records are retained while launch and pricing updates remain relevant or until consent is withdrawn.
  - period: null
    scope: Anti-abuse counters
    text: Short-lived anti-abuse counters expire automatically.
  rights:
  - right: Withdraw consent
    text: For privacy questions, consent withdrawal, or deletion requests, email [email protected] .
  - right: Waitlist removal
    text: request waitlist removal by emailing [email protected]
  - right: Limit cookies
    text: Users can limit cookies, clear local storage, use browser privacy controls
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
name: aipricinghub-com
provenance_date: '2026-11-09'
provider_name: aipricinghub-com
provider_slug: aipricinghub-com
slug: aipricinghub-com-privacy-policy
source_date: '2026-11-09'
source_filename: aipricinghub-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aipricinghub.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: aipricinghub-com\naid: aipricinghub-com\nurl: https://aipricinghub.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: When you explicitly opt in, AI Pricing Hub stores your email address, selected locale, consent timestamp,\n    privacy-policy version, and limited signup attribution to send launch and AI pricing updates.\n- category: behavioral\n  text: The site may collect aggregate usage events to understand page views, feature use, filters, exports, alerts,\n    and navigation quality.\n- category: device\n  text: Static features\
  \ may store preferences such as theme, language, experiment variant, saved explorer filters,\n    calculator state, or alert configuration locally in the browser.\npurposes:\n- purpose: Send launch and pricing updates\n  text: to send launch and AI pricing updates\n- purpose: Analytics\n  text: The site may collect aggregate usage events to understand page views, feature use, filters, exports, alerts,\n    and navigation quality.\n- purpose: Abuse prevention\n  text: The signup endpoint validates requests and uses short-lived hashed network signals, timing checks, a honeypot,\n    rate limits, and duplicate detection.\nretention:\n- scope: Active waitlist records\n  period: null\n  text: Active waitlist records are retained while launch and pricing updates remain relevant or until consent is\n    withdrawn.\n- scope: Anti-abuse counters\n  period: null\n  text: Short-lived anti-abuse counters expire automatically.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\n\
  dpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request\n  text: For privacy questions, consent withdrawal, or deletion requests, email [email protected] .\nrights:\n- right: Withdraw consent\n  text: For privacy questions, consent withdrawal, or deletion requests, email [email protected] .\n- right: Waitlist removal\n  text: request waitlist removal by emailing [email protected]\n- right: Limit cookies\n  text: Users can limit cookies, clear local storage, use browser privacy controls\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aipricinghub-com/privacy/aipricinghub-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 12 quoted statements, read from aipricinghub-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Pricing
- Data
- Analytics
- Marketplace
- Comparison
---
