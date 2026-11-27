---
api_specs:
- filename: postonce-accounts-api-openapi.yml
  format: yaml
  label: PostOnce Accounts API
  slug: postonce-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postonce/openapi/postonce-accounts-api-openapi.yml
- filename: postonce-drafts-api-openapi.yml
  format: yaml
  label: PostOnce Drafts API
  slug: postonce-drafts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postonce/openapi/postonce-drafts-api-openapi.yml
- filename: postonce-media-api-openapi.yml
  format: yaml
  label: PostOnce Media API
  slug: postonce-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postonce/openapi/postonce-media-api-openapi.yml
- filename: postonce-posts-api-openapi.yml
  format: yaml
  label: PostOnce Posts API
  slug: postonce-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postonce/openapi/postonce-posts-api-openapi.yml
- filename: postonce-workflows-api-openapi.yml
  format: yaml
  label: PostOnce Workflows API
  slug: postonce-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/postonce/openapi/postonce-workflows-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name, email address, profile image, account settings, subscription status, and related account information.
  - category: financial
    text: Payment, subscription, invoice, and billing details processed by Stripe.
  - category: communication
    text: Posts, captions, media files, thumbnails, links, hashtags, drafts, scheduled posts, workflow rules, account selections, and other content or settings you submit to the Service.
  - category: behavioral
    text: Log data, browser type, device information, IP address, referral URLs, page views, product events, crash/error reports, and similar information used for security, analytics, support, and product improvement.
  - category: device
    text: Cookies, localStorage, and similar technologies used to keep you signed in, remember preferences, protect sessions, measure performance, and improve the Service.
  deletion:
    route: Request deletion by contacting support@postonce.to
    text: You can request deletion of all data associated with your PostOnce account by contacting support@postonce.to .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account management
    text: Create and manage your PostOnce account.
  - purpose: Publishing and crossposting
    text: Upload, schedule, publish, crosspost, sync, and manage content based on your settings.
  - purpose: Billing
    text: Process subscriptions, trials, payments, refunds, invoices, and account limits.
  - purpose: Product improvement
    text: Measure product usage, improve performance, and develop new features.
  residency:
  - region: Canada
    text: PostOnce operates from Canada and uses service providers that may process data in Canada, the United States, the European Union, and other locations where those providers operate.
  retention:
  - period: 30 days
    scope: Account deletion
    text: When your account is deleted, stored account data, submitted content, workflow data, and OAuth tokens are deleted or de-identified within 30 days unless retention is required for security, billing, legal, tax, or compliance reasons.
  - period: null
    scope: Backups
    text: Copies may remain temporarily in encrypted backups until the applicable backup-rotation period expires.
  rights:
  - right: Revoke access
    text: You may revoke PostOnce's access to your YouTube data at any time directly from your Google account
  - right: Disconnect accounts
    text: You may also revoke or disconnect other connected social accounts through PostOnce or through the third-party platform's own account settings.
  - right: Cookie control
    text: You can control cookies through your browser settings, but disabling cookies may prevent parts of the Service from working correctly.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data, OAuth tokens, submitted content, or YouTube API Data.
  subprocessors:
    text: 'We use trusted third-party processors solely as needed: Hetzner (infrastructure hosting) Supabase (database) Stripe (payments) PostHog (product analytics) Vercel Analytics and Speed Insights (site analytics and performance) RefGrow (affiliate program) Plunk (email and product communication events) Meta (conversion measurement, where enabled)'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PostOnce
provenance_date: '2026-11-10'
provider_name: PostOnce
provider_slug: postonce
slug: postonce-privacy-policy
source_date: '2026-11-10'
source_filename: postonce-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://postonce.to/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PostOnce\naid: postonce\nurl: https://postonce.to/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Your name, email address, profile image, account settings, subscription status, and related account information.\n- category: financial\n  text: Payment, subscription, invoice, and billing details processed by Stripe.\n- category: communication\n  text: Posts, captions, media files, thumbnails, links, hashtags, drafts, scheduled posts, workflow rules, account\n    selections, and other content or settings you submit to the Service.\n\
  - category: behavioral\n  text: Log data, browser type, device information, IP address, referral URLs, page views, product events, crash/error\n    reports, and similar information used for security, analytics, support, and product improvement.\n- category: device\n  text: Cookies, localStorage, and similar technologies used to keep you signed in, remember preferences, protect\n    sessions, measure performance, and improve the Service.\npurposes:\n- purpose: Account management\n  text: Create and manage your PostOnce account.\n- purpose: Publishing and crossposting\n  text: Upload, schedule, publish, crosspost, sync, and manage content based on your settings.\n- purpose: Billing\n  text: Process subscriptions, trials, payments, refunds, invoices, and account limits.\n- purpose: Product improvement\n  text: Measure product usage, improve performance, and develop new features.\nretention:\n- scope: Account deletion\n  period: 30 days\n  text: When your account is deleted, stored account\
  \ data, submitted content, workflow data, and OAuth tokens are\n    deleted or de-identified within 30 days unless retention is required for security, billing, legal, tax, or compliance\n    reasons.\n- scope: Backups\n  period: null\n  text: Copies may remain temporarily in encrypted backups until the applicable backup-rotation period expires.\nresidency:\n- region: Canada\n  text: PostOnce operates from Canada and uses service providers that may process data in Canada, the United States,\n    the European Union, and other locations where those providers operate.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We use trusted third-party processors solely as needed: Hetzner (infrastructure hosting) Supabase (database)\n    Stripe (payments) PostHog (product analytics) Vercel Analytics and Speed Insights (site analytics and performance)\n    RefGrow (affiliate program) Plunk (email and product communication events) Meta (conversion measurement, where\n    enabled)'\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion by contacting support@postonce.to\n  text: You can request deletion of all data associated with your PostOnce account by contacting support@postonce.to\n    .\nrights:\n- right: Revoke access\n  text: You may revoke PostOnce's access to your YouTube data at any time directly from your Google account\n- right: Disconnect accounts\n  text: You may also revoke or disconnect other connected social accounts through PostOnce or through the third-party\n    platform's own account settings.\n- right: Cookie control\n  text: You can control cookies through your browser settings, but disabling cookies may prevent parts of the Service\n    from working correctly.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data, OAuth tokens, submitted content, or YouTube API Data.\n"
source_yaml_url: https://artifacts.apis.io/postonce/privacy/postonce-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from PostOnce's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social Media
- Automation
- Marketing
---
