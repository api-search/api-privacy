---
claim_count: 12
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: email address and password hash (authentication is handled by Supabase).'
  - category: financial
    text: ASRM stores Stripe customer and subscription identifiers, never card numbers.
  - category: behavioral
    text: 'Usage analytics: page views and product events (for example, scan completed, trial started) tied to your account id'
  - category: device
    text: a salted hash of your IP address for rate limiting (never the raw address)
  - category: contact
    text: if you unlock a report, your email address.
  deletion:
    route: contact support
    text: To request deletion, contact support.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: operate the service
    text: To run the service, deliver reports and emails you request, prevent abuse, and improve the product.
  - purpose: operate and improve the service
    text: used to operate and improve the service.
  retention:
  - period: null
    scope: Account data
    text: Account data persists while the account exists.
  - period: null
    scope: Free-scan rows and leads
    text: Free-scan rows and leads may be retained for rate limiting and abuse prevention.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Third parties Supabase (database and authentication), Stripe (payments), Resend (email), Vercel (hosting and analytics), and the AI engine providers we query on your behalf (OpenAI, Anthropic, Perplexity, Google).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ASRM
provenance_date: '2026-11-09'
provider_name: ASRM
provider_slug: asrm-ai
slug: asrm-ai-privacy-policy
source_date: '2026-11-09'
source_filename: asrm-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://asrm.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ASRM\naid: asrm-ai\nurl: https://asrm.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account data: email address and password hash (authentication is handled by Supabase).'\n- category: financial\n  text: ASRM stores Stripe customer and subscription identifiers, never card numbers.\n- category: behavioral\n  text: 'Usage analytics: page views and product events (for example, scan completed, trial started) tied to your\n    account id'\n- category: device\n  text: a salted hash of your IP address for rate limiting (never the\
  \ raw address)\n- category: contact\n  text: if you unlock a report, your email address.\npurposes:\n- purpose: operate the service\n  text: To run the service, deliver reports and emails you request, prevent abuse, and improve the product.\n- purpose: operate and improve the service\n  text: used to operate and improve the service.\nretention:\n- scope: Account data\n  period: null\n  text: Account data persists while the account exists.\n- scope: Free-scan rows and leads\n  period: null\n  text: Free-scan rows and leads may be retained for rate limiting and abuse prevention.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Third parties Supabase (database and authentication), Stripe (payments), Resend (email), Vercel (hosting\n    and analytics), and the AI engine providers we query on your behalf (OpenAI, Anthropic, Perplexity, Google).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact support\n  text: To request deletion, contact support.\n\
  rights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/asrm-ai/privacy/asrm-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- sale_or_sharing
summary_line: 12 quoted statements, read from ASRM's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- SEO
- Monitoring
- Visibility
- Search
---
