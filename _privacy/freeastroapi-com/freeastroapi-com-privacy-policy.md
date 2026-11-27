---
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Data: email, hashed password (managed by Supabase), optional company/project name.'
  - category: device
    text: 'API Usage: timestamp, endpoint, IP, user agent, request/response metadata for abuse prevention and reliability.'
  - category: financial
    text: 'Billing: Stripe customer ID, subscription details, invoices.'
  - category: communication
    text: 'Support: messages you send via forms or email.'
  deletion:
    route: Account deletion via the dashboard; or email support request
    text: Account deletion is available via the dashboard; backups purge within 30 days.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and secure the API service
    text: Provide and secure the API service, including rate limiting and abuse prevention.
  - purpose: Payments and subscriptions
    text: Process payments, invoices, and subscription management through Stripe.
  - purpose: Improve reliability and performance
    text: Improve reliability and performance through aggregate analytics.
  - purpose: Support
    text: Provide support and respond to requests.
  retention:
  - period: 90 days
    scope: Access logs
    text: 'Access logs: up to 90 days.'
  - period: 30 days
    scope: Request payload logs
    text: 'Request payload logs: 30 days (for debugging), then purged.'
  - period: 30 days
    scope: Backups
    text: 'Backups: rolling, purged within 30 days after deletion.'
  rights:
  - right: Access
    text: You can access, export, or delete your data.
  - right: Deletion
    text: Account deletion is available via the dashboard; backups purge within 30 days.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: 'We share data only with essential processors: Supabase (authentication), Stripe (billing), and analytics/monitoring for performance and error tracking.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: freeastroapi-com
provenance_date: '2026-11-09'
provider_name: freeastroapi-com
provider_slug: freeastroapi-com
slug: freeastroapi-com-privacy-policy
source_date: '2026-11-09'
source_filename: freeastroapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.freeastroapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: freeastroapi-com\naid: freeastroapi-com\nurl: https://www.freeastroapi.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Data: email, hashed password (managed by Supabase), optional company/project name.'\n- category: device\n  text: 'API Usage: timestamp, endpoint, IP, user agent, request/response metadata for abuse prevention and reliability.'\n- category: financial\n  text: 'Billing: Stripe customer ID, subscription details, invoices.'\n- category: communication\n  text: 'Support: messages you send via forms or email.'\n\
  purposes:\n- purpose: Provide and secure the API service\n  text: Provide and secure the API service, including rate limiting and abuse prevention.\n- purpose: Payments and subscriptions\n  text: Process payments, invoices, and subscription management through Stripe.\n- purpose: Improve reliability and performance\n  text: Improve reliability and performance through aggregate analytics.\n- purpose: Support\n  text: Provide support and respond to requests.\nretention:\n- scope: Access logs\n  period: 90 days\n  text: 'Access logs: up to 90 days.'\n- scope: Request payload logs\n  period: 30 days\n  text: 'Request payload logs: 30 days (for debugging), then purged.'\n- scope: Backups\n  period: 30 days\n  text: 'Backups: rolling, purged within 30 days after deletion.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We share data only with essential processors: Supabase (authentication), Stripe (billing), and analytics/monitoring\n    for performance and error tracking.'\n\
  dpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account deletion via the dashboard; or email support request\n  text: Account deletion is available via the dashboard; backups purge within 30 days.\nrights:\n- right: Access\n  text: You can access, export, or delete your data.\n- right: Deletion\n  text: Account deletion is available via the dashboard; backups purge within 30 days.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/freeastroapi-com/privacy/freeastroapi-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from freeastroapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Astrology
- Developers
- Data
---
