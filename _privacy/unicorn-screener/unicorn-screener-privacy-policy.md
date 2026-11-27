---
api_specs:
- filename: unicorn-screener-agent-api-openapi.yml
  format: yaml
  label: Unicorn Screener Agent API
  slug: unicorn-screener-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unicorn-screener/openapi/unicorn-screener-agent-api-openapi.yml
- filename: unicorn-screener-autocomplete-api-openapi.yml
  format: yaml
  label: Unicorn Screener Autocomplete API
  slug: unicorn-screener-autocomplete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unicorn-screener/openapi/unicorn-screener-autocomplete-api-openapi.yml
- filename: unicorn-screener-request-report-api-openapi.yml
  format: yaml
  label: Unicorn Screener Request Report API
  slug: unicorn-screener-request-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unicorn-screener/openapi/unicorn-screener-request-report-api-openapi.yml
- filename: unicorn-screener-screen-status-api-openapi.yml
  format: yaml
  label: Unicorn Screener Screen Status API
  slug: unicorn-screener-screen-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unicorn-screener/openapi/unicorn-screener-screen-status-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Email address: When you request a report, we collect your email to deliver the PDF.'
  - category: identifying
    text: 'Contact form submissions: Name, email, and message content when you contact us.'
  - category: financial
    text: 'Payment information: Processed by Lemon Squeezy (our Merchant of Record).'
  - category: device
    text: 'Browser fingerprint: A privacy-preserving hash used solely for rate limiting (one free report per user).'
  - category: professional
    text: FounderMeet uses LinkedIn sign-in, the email supplied by LinkedIn or an email you verify when LinkedIn supplies none, your LinkedIn profile photo, your declared professional profile and a website when supplied.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Deliver PDF reports and opt-in product updates
    text: 'Email: To deliver PDF reports and, if you opt in, occasional product updates.'
  - purpose: Rate limiting and abuse prevention
    text: 'IP + Fingerprint: Rate limiting only (1 free report per user, abuse prevention on paid checkouts).'
  - purpose: Research pipeline input
    text: 'Startup name / website: Used as input to our research pipeline (Serper Google search, Jina Reader content extraction, Google Gemini 2.5 Flash synthesis).'
  - purpose: Aggregate analytics
    text: 'Analytics: To understand aggregate traffic, product reliability and feature usage.'
  retention:
  - period: 24-hour TTL
    scope: Cached analyses
    text: Generated reports are cached in Redis with a 24-hour TTL so paying customers can receive their PDF immediately after checkout.
  - period: 30-day TTL
    scope: Payment records
    text: 'Payment records: Stored in Redis with a 30-day TTL for order reconciliation and idempotency.'
  - period: 12 months of inactivity
    scope: Active FounderMeet profiles
    text: Active profiles are retained while you use FounderMeet and expire after 12 months of inactivity.
  - period: 1 hour
    scope: Hourly analysis rate limits
    text: Hourly analysis rate limits expire after 1 hour.
  - period: null
    scope: Newsletter emails
    text: 'Newsletter emails: Stored until you unsubscribe.'
  rights:
  - right: Access
    text: Request access to your personal data.
  - right: Deletion
    text: Request deletion of your personal data.
  - right: Withdraw newsletter consent
    text: Withdraw consent for newsletter emails at any time.
  - right: Data portability
    text: Request data portability.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or share your data with advertisers.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Unicorn Screener
provenance_date: '2026-11-10'
provider_name: Unicorn Screener
provider_slug: unicorn-screener
slug: unicorn-screener-privacy-policy
source_date: '2026-11-10'
source_filename: unicorn-screener-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://unicornscreener.vc/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Unicorn Screener\naid: unicorn-screener\nurl: https://unicornscreener.vc/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: 'Email address: When you request a report, we collect your email to deliver the PDF.'\n- category: identifying\n  text: 'Contact form submissions: Name, email, and message content when you contact us.'\n- category: financial\n  text: 'Payment information: Processed by Lemon Squeezy (our Merchant of Record).'\n- category: device\n  text: 'Browser fingerprint: A privacy-preserving hash used solely for rate limiting\
  \ (one free report per user).'\n- category: professional\n  text: FounderMeet uses LinkedIn sign-in, the email supplied by LinkedIn or an email you verify when LinkedIn supplies\n    none, your LinkedIn profile photo, your declared professional profile and a website when supplied.\npurposes:\n- purpose: Deliver PDF reports and opt-in product updates\n  text: 'Email: To deliver PDF reports and, if you opt in, occasional product updates.'\n- purpose: Rate limiting and abuse prevention\n  text: 'IP + Fingerprint: Rate limiting only (1 free report per user, abuse prevention on paid checkouts).'\n- purpose: Research pipeline input\n  text: 'Startup name / website: Used as input to our research pipeline (Serper Google search, Jina Reader content\n    extraction, Google Gemini 2.5 Flash synthesis).'\n- purpose: Aggregate analytics\n  text: 'Analytics: To understand aggregate traffic, product reliability and feature usage.'\nretention:\n- scope: Cached analyses\n  period: 24-hour TTL\n  text:\
  \ Generated reports are cached in Redis with a 24-hour TTL so paying customers can receive their PDF immediately\n    after checkout.\n- scope: Payment records\n  period: 30-day TTL\n  text: 'Payment records: Stored in Redis with a 30-day TTL for order reconciliation and idempotency.'\n- scope: Active FounderMeet profiles\n  period: 12 months of inactivity\n  text: Active profiles are retained while you use FounderMeet and expire after 12 months of inactivity.\n- scope: Hourly analysis rate limits\n  period: 1 hour\n  text: Hourly analysis rate limits expire after 1 hour.\n- scope: Newsletter emails\n  period: null\n  text: 'Newsletter emails: Stored until you unsubscribe.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: Request access to your personal data.\n- right: Deletion\n  text: Request deletion of your personal data.\n- right: Withdraw\
  \ newsletter consent\n  text: Withdraw consent for newsletter emails at any time.\n- right: Data portability\n  text: Request data portability.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or share your data with advertisers.\n"
source_yaml_url: https://artifacts.apis.io/unicorn-screener/privacy/unicorn-screener-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Unicorn Screener's own page on 2026-11-10.
synthetic: false
tags:
- Venture Capital
- Startups
- Company Research
- Screening
- Investing
- AI Agents
---
