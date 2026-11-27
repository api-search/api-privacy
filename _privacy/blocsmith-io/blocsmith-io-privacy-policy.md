---
claim_count: 28
description: ''
doc:
  data_categories:
  - category: contact
    text: we collect your email address and optionally your name
  - category: behavioral
    text: We collect information about how you use the service, including AI prompts sent, pages created, and features used.
  - category: device
    text: browser fingerprints (for bot protection during free trials), and country of origin
  - category: identifying
    text: We collect IP addresses (hashed for rate limiting)
  - category: financial
    text: We store your Stripe customer ID and subscription status but never see or store your card details.
  - category: behavioral
    text: we collect anonymous page view data (page path, device type, referrer, country) for your analytics dashboard
  - category: communication
    text: we store a record of that connection (which app, when you approved it and when it was last used) and securely hashed access tokens
  deletion:
    route: Email privacy@blocsmith.io to request erasure
    text: To exercise any of these rights, email privacy@blocsmith.io . We will respond within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate the service
    text: To provide and operate the Blocsmith service
  - purpose: Authentication
    text: To authenticate you via magic link emails
  - purpose: Payments
    text: To process payments and manage your subscription
  - purpose: Transactional emails
    text: To send transactional emails (account confirmations, subscription changes, site unpublish notices)
  - purpose: Abuse prevention
    text: To prevent abuse and bot accounts during free trials
  - purpose: Product improvement
    text: To improve the product based on aggregate usage patterns
  residency:
  - region: EU
    text: Data is stored in EU-based infrastructure (Neon PostgreSQL, Vercel).
  retention:
  - period: while your account is active
    scope: Account data
    text: 'Account data : retained while your account is active. Deleted on request.'
  - period: while your account is active
    scope: Project data
    text: 'Project data : retained while your account is active, including after subscription cancellation (so you can resubscribe).'
  - period: monthly
    scope: Rate limit hashes
    text: 'Rate limit hashes : automatically purged monthly.'
  - period: 3 years
    scope: Cookie consent records
    text: 'Cookie consent records : retained for 3 years per GDPR requirements, then pruned.'
  - period: 90 days
    scope: Analytics data
    text: 'Analytics data : aggregated daily, raw events purged after 90 days.'
  - period: while your account is active
    scope: Connected-app records
    text: 'Connected-app records : kept while your account is active.'
  rights:
  - right: Access
    text: Access your personal data
  - right: Rectify
    text: Rectify inaccurate data
  - right: Erase
    text: Erase your data ("right to be forgotten")
  - right: Portability
    text: Port your data to another service
  - right: Object
    text: Object to processing
  - right: Withdraw consent
    text: Withdraw consent at any time
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Blocsmith
provenance_date: '2026-11-09'
provider_name: Blocsmith
provider_slug: blocsmith-io
slug: blocsmith-io-privacy-policy
source_date: '2026-11-09'
source_filename: blocsmith-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.blocsmith.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Blocsmith\naid: blocsmith-io\nurl: https://www.blocsmith.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: we collect your email address and optionally your name\n- category: behavioral\n  text: We collect information about how you use the service, including AI prompts sent, pages created, and features\n    used.\n- category: device\n  text: browser fingerprints (for bot protection during free trials), and country of origin\n- category: identifying\n  text: We collect IP addresses (hashed for rate limiting)\n- category: financial\n\
  \  text: We store your Stripe customer ID and subscription status but never see or store your card details.\n- category: behavioral\n  text: we collect anonymous page view data (page path, device type, referrer, country) for your analytics dashboard\n- category: communication\n  text: we store a record of that connection (which app, when you approved it and when it was last used) and securely\n    hashed access tokens\npurposes:\n- purpose: Provide and operate the service\n  text: To provide and operate the Blocsmith service\n- purpose: Authentication\n  text: To authenticate you via magic link emails\n- purpose: Payments\n  text: To process payments and manage your subscription\n- purpose: Transactional emails\n  text: To send transactional emails (account confirmations, subscription changes, site unpublish notices)\n- purpose: Abuse prevention\n  text: To prevent abuse and bot accounts during free trials\n- purpose: Product improvement\n  text: To improve the product based on aggregate\
  \ usage patterns\nretention:\n- scope: Account data\n  period: while your account is active\n  text: 'Account data : retained while your account is active. Deleted on request.'\n- scope: Project data\n  period: while your account is active\n  text: 'Project data : retained while your account is active, including after subscription cancellation (so you\n    can resubscribe).'\n- scope: Rate limit hashes\n  period: monthly\n  text: 'Rate limit hashes : automatically purged monthly.'\n- scope: Cookie consent records\n  period: 3 years\n  text: 'Cookie consent records : retained for 3 years per GDPR requirements, then pruned.'\n- scope: Analytics data\n  period: 90 days\n  text: 'Analytics data : aggregated daily, raw events purged after 90 days.'\n- scope: Connected-app records\n  period: while your account is active\n  text: 'Connected-app records : kept while your account is active.'\nresidency:\n- region: EU\n  text: Data is stored in EU-based infrastructure (Neon PostgreSQL, Vercel).\n\
  transfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@blocsmith.io to request erasure\n  text: To exercise any of these rights, email privacy@blocsmith.io . We will respond within 30 days.\nrights:\n- right: Access\n  text: Access your personal data\n- right: Rectify\n  text: Rectify inaccurate data\n- right: Erase\n  text: Erase your data (\"right to be forgotten\")\n- right: Portability\n  text: Port your data to another service\n- right: Object\n  text: Object to processing\n- right: Withdraw consent\n  text: Withdraw consent at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/blocsmith-io/privacy/blocsmith-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from Blocsmith's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Website Builder
- No-Code
- Software-as-a-Service
- Automation
---
