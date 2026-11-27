---
api_specs:
- filename: email-verifier-api-verification-api-openapi.yml
  format: yaml
  label: Email Verifier API Verification API
  slug: email-verifier-api-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/email-verifier-api/openapi/email-verifier-api-verification-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect personal information (such as name, email address, and billing info) only when voluntarily submitted during registration or order placement.
  - category: device
    text: We may collect technical information about your connection to our site, including browser type, operating system, and Internet Service Provider (ISP) details to improve service performance.
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Customer service
    text: Information helps us respond to support needs more efficiently.
  - purpose: Process payments
    text: Billing info is used only to provide the requested service.
  - purpose: Periodic emails
    text: Your email is used for order updates and technical notifications.
  - purpose: Service improvement and marketing analytics
    text: We may share generic aggregated demographic information, not linked to any personal data, with trusted affiliates and partners for the purposes of service improvement and marketing analytics.
  retention:
  - period: 30 days
    scope: Hashed email fingerprints
    text: These hashes are automatically deleted after 30 days.
  - period: null
    scope: Raw email addresses submitted for verification
    text: All raw email data is purged from our active processing environment immediately following the completion of the 16-point check.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, trade, or rent your personal identification information to others.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Email Verifier API
provenance_date: '2026-11-09'
provider_name: Email Verifier API
provider_slug: email-verifier-api
slug: email-verifier-api-privacy-policy
source_date: '2026-11-09'
source_filename: email-verifier-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://emailverifierapi.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Email Verifier API\naid: email-verifier-api\nurl: https://emailverifierapi.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We collect personal information (such as name, email address, and billing info) only when voluntarily submitted\n    during registration or order placement.\n- category: device\n  text: We may collect technical information about your connection to our site, including browser type, operating\n    system, and Internet Service Provider (ISP) details to improve service performance.\npurposes:\n- purpose:\
  \ Customer service\n  text: Information helps us respond to support needs more efficiently.\n- purpose: Process payments\n  text: Billing info is used only to provide the requested service.\n- purpose: Periodic emails\n  text: Your email is used for order updates and technical notifications.\n- purpose: Service improvement and marketing analytics\n  text: We may share generic aggregated demographic information, not linked to any personal data, with trusted affiliates\n    and partners for the purposes of service improvement and marketing analytics.\nretention:\n- scope: Hashed email fingerprints\n  period: 30 days\n  text: These hashes are automatically deleted after 30 days.\n- scope: Raw email addresses submitted for verification\n  period: null\n  text: All raw email data is purged from our active processing environment immediately following the completion\n    of the 16-point check.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n\
  \  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, trade, or rent your personal identification information to others.\n"
source_yaml_url: https://artifacts.apis.io/email-verifier-api/privacy/email-verifier-api-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- sale_or_sharing
summary_line: 9 quoted statements, read from Email Verifier API's own page on 2026-11-09.
synthetic: false
tags:
- Email Verification
- Deliverability
- SMTP Check
- Bounce Prevention
- Lead Validation
- Disposable Detection
- Spam Trap Detection
- Catch-All Detection
- Greylisting
- Role Account Detection
- Typo Suggestion
- B2B Lead Scoring
---
