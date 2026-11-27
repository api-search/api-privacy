---
api_specs:
- filename: chirpie-ai-openapi-generated.yml
  format: yaml
  label: Chirpie API
  slug: chirpie-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chirpie-ai/openapi/_ae-authored/chirpie-ai-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: we collect your name, email address, and password (hashed, never stored in plaintext)
  - category: identifying
    text: we store your platform user ID, username, display name, and profile image URL
  - category: contact
    text: we collect your name, email address, and password
  - category: financial
    text: We store your Stripe customer ID and subscription ID but never store credit card numbers, CVVs, or full payment details on our servers.
  - category: behavioral
    text: We collect standard web analytics (page views, referrer) via privacy-friendly, cookie-free analytics.
  - category: communication
    text: We store the text of posts and threads you create through the Service, along with scheduling metadata and publishing status.
  deletion:
    route: 'In-app: Billing, then Delete account; or email privacy@chirpie.ai'
    text: 'You can delete your account yourself at any time from the dashboard: open Billing, then Delete account. Deletion is immediate and permanent.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: 'To provide the Service: posting content to social media platforms on your behalf'
  - purpose: Account and billing management
    text: To manage your account, subscriptions, and billing
  - purpose: Transactional emails
    text: To send transactional emails (verification, password reset, welcome)
  - purpose: Product emails
    text: 'To send occasional product emails: onboarding tips, usage notices, and product updates.'
  - purpose: Enforce usage limits
    text: To enforce usage limits per your subscription plan
  - purpose: Reliability and security
    text: To monitor and improve the reliability and security of the Service
  - purpose: Legal compliance
    text: To comply with legal obligations
  retention:
  - period: null
    scope: Account data
    text: We retain your account data for as long as your account is active.
  - period: null
    scope: Post content and analytics
    text: Post content and analytics are retained per your plan tier.
  - period: null
    scope: Billing records held by payment processor
    text: Billing records held by our payment processor are kept as long as the law requires.
  rights:
  - right: Access
    text: Access the personal data we hold about you
  - right: Correction
    text: Request correction of inaccurate data
  - right: Deletion
    text: Request deletion of your data
  - right: Portability
    text: Export your data in a portable format
  - right: Object or restrict
    text: Object to or restrict processing of your data
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: 'We share data only with: Connected social media platforms : to post content on your behalf, via their APIs using your authorized credentials Stripe : to process payments Resend : to send transactional emails Loops : to send product emails and manage your email preferences Sentry : to capture error reports for debugging (no personal content is sent) Vercel : our hosting provider Neon : our database provider'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Chirpie
provenance_date: '2026-11-09'
provider_name: Chirpie
provider_slug: chirpie-ai
slug: chirpie-ai-privacy-policy
source_date: '2026-11-09'
source_filename: chirpie-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://chirpie.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Chirpie\naid: chirpie-ai\nurl: https://chirpie.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: we collect your name, email address, and password (hashed, never stored in plaintext)\n- category: identifying\n  text: we store your platform user ID, username, display name, and profile image URL\n- category: contact\n  text: we collect your name, email address, and password\n- category: financial\n  text: We store your Stripe customer ID and subscription ID but never store credit card numbers, CVVs, or full\n    payment details on\
  \ our servers.\n- category: behavioral\n  text: We collect standard web analytics (page views, referrer) via privacy-friendly, cookie-free analytics.\n- category: communication\n  text: We store the text of posts and threads you create through the Service, along with scheduling metadata and\n    publishing status.\npurposes:\n- purpose: Provide the Service\n  text: 'To provide the Service: posting content to social media platforms on your behalf'\n- purpose: Account and billing management\n  text: To manage your account, subscriptions, and billing\n- purpose: Transactional emails\n  text: To send transactional emails (verification, password reset, welcome)\n- purpose: Product emails\n  text: 'To send occasional product emails: onboarding tips, usage notices, and product updates.'\n- purpose: Enforce usage limits\n  text: To enforce usage limits per your subscription plan\n- purpose: Reliability and security\n  text: To monitor and improve the reliability and security of the Service\n-\
  \ purpose: Legal compliance\n  text: To comply with legal obligations\nretention:\n- scope: Account data\n  period: null\n  text: We retain your account data for as long as your account is active.\n- scope: Post content and analytics\n  period: null\n  text: Post content and analytics are retained per your plan tier.\n- scope: Billing records held by payment processor\n  period: null\n  text: Billing records held by our payment processor are kept as long as the law requires.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We share data only with: Connected social media platforms : to post content on your behalf, via their APIs\n    using your authorized credentials Stripe : to process payments Resend : to send transactional emails Loops :\n    to send product emails and manage your email preferences Sentry : to capture error reports for debugging (no\n    personal content is sent) Vercel : our hosting provider Neon : our database provider'\ndpa:\n  available: null\n\
  \  url: null\n  text: null\ndeletion:\n  route: 'In-app: Billing, then Delete account; or email privacy@chirpie.ai'\n  text: 'You can delete your account yourself at any time from the dashboard: open Billing, then Delete account.\n    Deletion is immediate and permanent.'\nrights:\n- right: Access\n  text: Access the personal data we hold about you\n- right: Correction\n  text: Request correction of inaccurate data\n- right: Deletion\n  text: Request deletion of your data\n- right: Portability\n  text: Export your data in a portable format\n- right: Object or restrict\n  text: Object to or restrict processing of your data\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/chirpie-ai/privacy/chirpie-ai-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from Chirpie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social Media
- Social Media Posting
- Scheduling
- MCP
- AI Agents
- Analytics
---
