---
api_specs:
- filename: threadsnoop-com-account-api-openapi.yml
  format: yaml
  label: threadsnoop-com Account API
  slug: threadsnoop-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threadsnoop-com/openapi/threadsnoop-com-account-api-openapi.yml
- filename: threadsnoop-com-comments-api-openapi.yml
  format: yaml
  label: threadsnoop-com Comments API
  slug: threadsnoop-com-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threadsnoop-com/openapi/threadsnoop-com-comments-api-openapi.yml
- filename: threadsnoop-com-posts-api-openapi.yml
  format: yaml
  label: threadsnoop-com Posts API
  slug: threadsnoop-com-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threadsnoop-com/openapi/threadsnoop-com-posts-api-openapi.yml
- filename: threadsnoop-com-subreddits-api-openapi.yml
  format: yaml
  label: threadsnoop-com Subreddits API
  slug: threadsnoop-com-subreddits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threadsnoop-com/openapi/threadsnoop-com-subreddits-api-openapi.yml
- filename: threadsnoop-com-users-api-openapi.yml
  format: yaml
  label: threadsnoop-com Users API
  slug: threadsnoop-com-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/threadsnoop-com/openapi/threadsnoop-com-users-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: To create an account we collect your email address and a password.
  - category: financial
    text: On our side we keep a Stripe customer ID, a ledger of credit grants and top-ups, and the dollar amounts charged
  - category: device
    text: Signing in sets a single session cookie; see “Cookies” below.
  - category: behavioral
    text: 'Every API call is logged for metering and support: the endpoint you called, the HTTP status, credits charged, and latency.'
  deletion:
    route: self-serve account deletion from developer dashboard
    text: You can delete your account yourself, at any time, from your developer dashboard — it's a genuine hard delete, not a deactivation flag
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: billing and balance
    text: so we can answer billing questions and keep your balance accurate
  - purpose: metering and support
    text: Every API call is logged for metering and support
  - purpose: abuse prevention
    text: We use IP addresses to slow down abuse — signup/login throttling and free-credit-farming detection.
  - purpose: transactional email
    text: We send transactional email — verification, password reset, and billing receipts
  residency:
  - region: United States
    text: ThreadSnoop is a small, independently run product, hosted in the United States.
  retention:
  - period: as long as your account is active
    scope: account data
    text: We keep your account data for as long as your account is active.
  - period: until we invite you or you ask us to remove it
    scope: waitlist email
    text: If you only joined our waitlist, we keep your email address until we invite you or you ask us to remove it.
  rights:
  - right: access, deletion, correction
    text: We aim to honor the spirit of GDPR/CCPA-style rights (access, deletion, correction) for anyone who asks, regardless of location
  role:
    text: we collect your email address and a password
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We never sell your personal data to anyone, for any reason.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: threadsnoop-com
provenance_date: '2026-11-10'
provider_name: threadsnoop-com
provider_slug: threadsnoop-com
slug: threadsnoop-com-privacy-policy
source_date: '2026-11-10'
source_filename: threadsnoop-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://threadsnoop.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: threadsnoop-com\naid: threadsnoop-com\nurl: https://threadsnoop.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: we collect your email address and a password\ndata_categories:\n- category: identifying\n  text: To create an account we collect your email address and a password.\n- category: financial\n  text: On our side we keep a Stripe customer ID, a ledger of credit grants and top-ups, and the dollar amounts\n    charged\n- category: device\n  text: Signing in sets a single session cookie; see “Cookies” below.\n- category: behavioral\n  text: 'Every API call is logged for metering\
  \ and support: the endpoint you called, the HTTP status, credits charged,\n    and latency.'\npurposes:\n- purpose: billing and balance\n  text: so we can answer billing questions and keep your balance accurate\n- purpose: metering and support\n  text: Every API call is logged for metering and support\n- purpose: abuse prevention\n  text: We use IP addresses to slow down abuse — signup/login throttling and free-credit-farming detection.\n- purpose: transactional email\n  text: We send transactional email — verification, password reset, and billing receipts\nretention:\n- scope: account data\n  period: as long as your account is active\n  text: We keep your account data for as long as your account is active.\n- scope: waitlist email\n  period: until we invite you or you ask us to remove it\n  text: If you only joined our waitlist, we keep your email address until we invite you or you ask us to remove\n    it.\nresidency:\n- region: United States\n  text: ThreadSnoop is a small, independently\
  \ run product, hosted in the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: self-serve account deletion from developer dashboard\n  text: You can delete your account yourself, at any time, from your developer dashboard — it's a genuine hard delete,\n    not a deactivation flag\nrights:\n- right: access, deletion, correction\n  text: We aim to honor the spirit of GDPR/CCPA-style rights (access, deletion, correction) for anyone who asks,\n    regardless of location\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your personal data to anyone, for any reason.\n"
source_yaml_url: https://artifacts.apis.io/threadsnoop-com/privacy/threadsnoop-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from threadsnoop-com's own page on 2026-11-10.
synthetic: false
tags:
- Reddit
- Artificial Intelligence
- MCP
- Read Only
---
