---
api_specs:
- filename: transcript-yt-com-languages-api-openapi.yml
  format: yaml
  label: transcript-yt-com Languages API
  slug: transcript-yt-com-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcript-yt-com/openapi/transcript-yt-com-languages-api-openapi.yml
- filename: transcript-yt-com-playlist-api-openapi.yml
  format: yaml
  label: transcript-yt-com Playlist API
  slug: transcript-yt-com-playlist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcript-yt-com/openapi/transcript-yt-com-playlist-api-openapi.yml
- filename: transcript-yt-com-search-api-openapi.yml
  format: yaml
  label: transcript-yt-com Search API
  slug: transcript-yt-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcript-yt-com/openapi/transcript-yt-com-search-api-openapi.yml
- filename: transcript-yt-com-summary-api-openapi.yml
  format: yaml
  label: transcript-yt-com Summary API
  slug: transcript-yt-com-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcript-yt-com/openapi/transcript-yt-com-summary-api-openapi.yml
- filename: transcript-yt-com-transcript-api-openapi.yml
  format: yaml
  label: transcript-yt-com Transcript API
  slug: transcript-yt-com-transcript-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcript-yt-com/openapi/transcript-yt-com-transcript-api-openapi.yml
- filename: transcript-yt-com-transcripts-api-openapi.yml
  format: yaml
  label: transcript-yt-com Transcripts API
  slug: transcript-yt-com-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcript-yt-com/openapi/transcript-yt-com-transcripts-api-openapi.yml
- filename: transcript-yt-com-usage-api-openapi.yml
  format: yaml
  label: transcript-yt-com Usage API
  slug: transcript-yt-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcript-yt-com/openapi/transcript-yt-com-usage-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign in with Google, we receive your name, email address, profile image, and Google account identifier.
  - category: financial
    text: We receive billing details needed to provide access, including your email, plan, payment or customer identifiers, subscription status, and payment-event records.
  - category: location
    text: Our own first-party analytics record each page view with the referring site, approximate location from your IP address, and device type
  - category: device
    text: device type, under an identifier derived from your IP address and browser that changes every day
  - category: behavioral
    text: For every API request, we record the video ID, requested language, response status, cache status, response time, and proxy-bandwidth measurements.
  deletion:
    route: Email aadit@techiseasy.co.in to request deletion of account data, subject to records we must retain.
    text: you may request access, correction, or deletion of your account data by emailing aadit@techiseasy.co.in
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service and enforce quotas
    text: This helps us provide the Service, enforce quotas, prevent abuse, and diagnose faults.
  - purpose: Billing
    text: Dodo Payments handles checkout.
  - purpose: Error monitoring
    text: We also use Sentry to receive technical error and performance reports
  retention:
  - period: seven days
    scope: Redis transcript caches
    text: Redis transcript caches expire after seven days
  - period: 30 days
    scope: Database cache entries
    text: database cache entries are treated as stale after 30 days
  - period: null
    scope: Account, usage, and security records
    text: Account, usage, and security records are generally kept while your account is active.
  rights:
  - right: Access
    text: you may request access, correction, or deletion of your account data by emailing aadit@techiseasy.co.in
  - right: Correction
    text: you may request access, correction, or deletion of your account data by emailing aadit@techiseasy.co.in
  - right: Deletion
    text: you may request access, correction, or deletion of your account data by emailing aadit@techiseasy.co.in
  - right: Revoke API keys
    text: You can revoke API keys at any time from your dashboard.
  role:
    text: The Service is operated by Aadit Shah , a sole proprietor based in India ("we" and "us"), who is responsible for your data.
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent personal information.
  subprocessors:
    text: Google (authentication and translation), Dodo Payments (billing), Upstash (caching and rate limiting), Neon (database hosting), Vercel (application hosting and aggregated analytics), DeepInfra and Groq (speech-to-text for videos without captions, and AI summaries), DataImpulse (network proxy for retrieving public YouTube data), PostHog (cookieless analytics), and Sentry (error monitoring).
    url: null
  transfers:
  - mechanism: other
    text: These providers may process information in countries other than yours under their own terms and privacy practices.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: transcript-yt-com
provenance_date: '2026-11-10'
provider_name: transcript-yt-com
provider_slug: transcript-yt-com
slug: transcript-yt-com-privacy-policy
source_date: '2026-11-10'
source_filename: transcript-yt-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://transcript-yt.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: transcript-yt-com\naid: transcript-yt-com\nurl: https://transcript-yt.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: The Service is operated by Aadit Shah , a sole proprietor based in India (\"we\" and \"us\"), who is responsible\n    for your data.\ndata_categories:\n- category: identifying\n  text: When you sign in with Google, we receive your name, email address, profile image, and Google account identifier.\n- category: financial\n  text: We receive billing details needed to provide access, including your email, plan, payment or customer identifiers,\n    subscription status,\
  \ and payment-event records.\n- category: location\n  text: Our own first-party analytics record each page view with the referring site, approximate location from your\n    IP address, and device type\n- category: device\n  text: device type, under an identifier derived from your IP address and browser that changes every day\n- category: behavioral\n  text: For every API request, we record the video ID, requested language, response status, cache status, response\n    time, and proxy-bandwidth measurements.\npurposes:\n- purpose: Provide the Service and enforce quotas\n  text: This helps us provide the Service, enforce quotas, prevent abuse, and diagnose faults.\n- purpose: Billing\n  text: Dodo Payments handles checkout.\n- purpose: Error monitoring\n  text: We also use Sentry to receive technical error and performance reports\nretention:\n- scope: Redis transcript caches\n  period: seven days\n  text: Redis transcript caches expire after seven days\n- scope: Database cache entries\n \
  \ period: 30 days\n  text: database cache entries are treated as stale after 30 days\n- scope: Account, usage, and security records\n  period: null\n  text: Account, usage, and security records are generally kept while your account is active.\nresidency: []\ntransfers:\n- mechanism: other\n  text: These providers may process information in countries other than yours under their own terms and privacy\n    practices.\nsubprocessors:\n  url: null\n  text: Google (authentication and translation), Dodo Payments (billing), Upstash (caching and rate limiting), Neon\n    (database hosting), Vercel (application hosting and aggregated analytics), DeepInfra and Groq (speech-to-text\n    for videos without captions, and AI summaries), DataImpulse (network proxy for retrieving public YouTube data),\n    PostHog (cookieless analytics), and Sentry (error monitoring).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email aadit@techiseasy.co.in to request deletion of account data,\
  \ subject to records we must retain.\n  text: you may request access, correction, or deletion of your account data by emailing aadit@techiseasy.co.in\nrights:\n- right: Access\n  text: you may request access, correction, or deletion of your account data by emailing aadit@techiseasy.co.in\n- right: Correction\n  text: you may request access, correction, or deletion of your account data by emailing aadit@techiseasy.co.in\n- right: Deletion\n  text: you may request access, correction, or deletion of your account data by emailing aadit@techiseasy.co.in\n- right: Revoke API keys\n  text: You can revoke API keys at any time from your dashboard.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal information.\n"
source_yaml_url: https://artifacts.apis.io/transcript-yt-com/privacy/transcript-yt-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from transcript-yt-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- YouTube
- Transcript
- MCP
---
