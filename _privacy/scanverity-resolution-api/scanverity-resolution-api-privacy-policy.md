---
api_specs:
- filename: scanverity-resolution-api-resolution-assessments-api-openapi.yml
  format: yaml
  label: Scanverity Resolution API Resolution assessments API
  slug: scanverity-resolution-api-resolution-assessments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanverity-resolution-api/openapi/scanverity-resolution-api-resolution-assessments-api-openapi.yml
- filename: scanverity-resolution-api-resolution-usage-api-openapi.yml
  format: yaml
  label: Scanverity Resolution API Resolution usage API
  slug: scanverity-resolution-api-resolution-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanverity-resolution-api/openapi/scanverity-resolution-api-resolution-usage-api-openapi.yml
- filename: scanverity-resolution-api-webhook-endpoints-api-openapi.yml
  format: yaml
  label: Scanverity Resolution API Webhook endpoints API
  slug: scanverity-resolution-api-webhook-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/scanverity-resolution-api/openapi/scanverity-resolution-api-webhook-endpoints-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: your email address, a securely hashed password (scrypt — we never store your password in readable form), display name, plan, account status'
  - category: contact
    text: 'Business-prospect data: an organisation''s name and domain, a publicly supplied corporate or role-based email address, and the public source URL'
  - category: financial
    text: 'Payment and subscription data: web purchases are processed by Stripe'
  - category: location
    text: 'Authentication & security data: session records, coarse IP prefix and a truncated user-agent for rate-limiting and abuse detection'
  - category: device
    text: 'Mobile notification data: an encrypted, account-bound Firebase Installation ID needed to route opted-in notifications, its one-way identity hash, app version, locale'
  - category: behavioral
    text: 'Usage data: which markets you analysed and when (report metadata scoped to your account), and per-plan quota counts.'
  deletion:
    route: Public account-deletion form or email to research@scanverity.com; saved reports can be deleted from the report or from Report history
    text: Request account deletion through the public deletion form or email research@scanverity.com ; we verify identity and act within the statutory period.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: To provide the Service — running analyses, enforcing quotas, showing your history (performance of contract).
  - purpose: Security and abuse prevention
    text: Security & abuse prevention — rate-limiting, audit logs (legitimate interests).
  - purpose: Billing
    text: Billing — verifying and managing subscriptions via Stripe or Google Play, as applicable (performance of contract / legal obligation).
  - purpose: Limited corporate outreach
    text: Limited corporate outreach — identifying a small number of legal entities whose publicly described professional work directly overlaps a current Scanverity finding
  retention:
  - period: 90 days
    scope: Saved reports
    text: We keep it for 90 days , after which it is deleted automatically by a scheduled cleanup.
  - period: 365 days
    scope: Security and audit events
    text: Security and audit events (sign-in, deletion, administrative actions) are kept for 365 days
  - period: 14 days
    scope: Failed analysis jobs
    text: Failed analysis jobs are kept for 14 days for diagnosis.
  - period: 30 days
    scope: Unverified public deletion-form requests
    text: An unverified request submitted through the public account-deletion form keeps its reply address encrypted for up to 30 days .
  - period: 90 days
    scope: Shared market analysis cache
    text: That cache is kept for up to 90 days and is removed sooner when no customer report refers to it.
  rights:
  - right: Access, correction, deletion, restriction, portability, objection
    text: you may request access, correction, deletion, restriction, portability, and object to processing based on legitimate interests
  - right: Lodge complaint with supervisory authority
    text: and lodge a complaint with your supervisory authority
  - right: Absolute right to object to direct marketing
    text: Your right to object to direct marketing is absolute.
  role:
    text: KotIQ OÜ, a private limited company registered in Estonia (registry code 16529665), of Sepapaja tn 6, Tallinn 15551, Estonia, VAT EE102595264 is the data controller for personal data processed through the Service
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, use it for third-party advertising, or build cross-site tracking profiles.
  subprocessors:
    text: Stripe — payment processing, invoicing, and tax determination.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Scanverity Resolution API
provenance_date: '2026-11-10'
provider_name: Scanverity Resolution API
provider_slug: scanverity-resolution-api
slug: scanverity-resolution-api-privacy-policy
source_date: '2026-11-10'
source_filename: scanverity-resolution-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://scanverity.com/en/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Scanverity Resolution API\naid: scanverity-resolution-api\nurl: https://scanverity.com/en/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: KotIQ OÜ, a private limited company registered in Estonia (registry code 16529665), of Sepapaja tn 6, Tallinn\n    15551, Estonia, VAT EE102595264 is the data controller for personal data processed through the Service\ndata_categories:\n- category: identifying\n  text: 'Account data: your email address, a securely hashed password (scrypt — we never store your password in\n    readable form), display name, plan, account status'\n- category: contact\n\
  \  text: 'Business-prospect data: an organisation''s name and domain, a publicly supplied corporate or role-based\n    email address, and the public source URL'\n- category: financial\n  text: 'Payment and subscription data: web purchases are processed by Stripe'\n- category: location\n  text: 'Authentication & security data: session records, coarse IP prefix and a truncated user-agent for rate-limiting\n    and abuse detection'\n- category: device\n  text: 'Mobile notification data: an encrypted, account-bound Firebase Installation ID needed to route opted-in\n    notifications, its one-way identity hash, app version, locale'\n- category: behavioral\n  text: 'Usage data: which markets you analysed and when (report metadata scoped to your account), and per-plan\n    quota counts.'\npurposes:\n- purpose: Provide the Service\n  text: To provide the Service — running analyses, enforcing quotas, showing your history (performance of contract).\n- purpose: Security and abuse prevention\n  text:\
  \ Security & abuse prevention — rate-limiting, audit logs (legitimate interests).\n- purpose: Billing\n  text: Billing — verifying and managing subscriptions via Stripe or Google Play, as applicable (performance of\n    contract / legal obligation).\n- purpose: Limited corporate outreach\n  text: Limited corporate outreach — identifying a small number of legal entities whose publicly described professional\n    work directly overlaps a current Scanverity finding\nretention:\n- scope: Saved reports\n  period: 90 days\n  text: We keep it for 90 days , after which it is deleted automatically by a scheduled cleanup.\n- scope: Security and audit events\n  period: 365 days\n  text: Security and audit events (sign-in, deletion, administrative actions) are kept for 365 days\n- scope: Failed analysis jobs\n  period: 14 days\n  text: Failed analysis jobs are kept for 14 days for diagnosis.\n- scope: Unverified public deletion-form requests\n  period: 30 days\n  text: An unverified request submitted\
  \ through the public account-deletion form keeps its reply address encrypted\n    for up to 30 days .\n- scope: Shared market analysis cache\n  period: 90 days\n  text: That cache is kept for up to 90 days and is removed sooner when no customer report refers to it.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Stripe — payment processing, invoicing, and tax determination.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Public account-deletion form or email to research@scanverity.com; saved reports can be deleted from the\n    report or from Report history\n  text: Request account deletion through the public deletion form or email research@scanverity.com ; we verify identity\n    and act within the statutory period.\nrights:\n- right: Access, correction, deletion, restriction, portability, objection\n  text: you may request access, correction, deletion, restriction, portability, and object to processing based on\n    legitimate interests\n\
  - right: Lodge complaint with supervisory authority\n  text: and lodge a complaint with your supervisory authority\n- right: Absolute right to object to direct marketing\n  text: Your right to object to direct marketing is absolute.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, use it for third-party advertising, or build cross-site tracking profiles.\n"
source_yaml_url: https://artifacts.apis.io/scanverity-resolution-api/privacy/scanverity-resolution-api-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Scanverity Resolution API's own page on 2026-11-10.
synthetic: false
tags:
- Prediction Markets
- Resolution Risk
- Market Intelligence
- Due Diligence
- Webhook
- OpenAPI
- Fintech
- Risk Analytics
- Polymarket
- Event Contracts
---
