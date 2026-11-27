---
api_specs:
- filename: grabbit-live-account-api-openapi.yml
  format: yaml
  label: grabbit-live Account API
  slug: grabbit-live-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grabbit-live/openapi/grabbit-live-account-api-openapi.yml
- filename: grabbit-live-grabs-api-openapi.yml
  format: yaml
  label: grabbit-live Grabs API
  slug: grabbit-live-grabs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grabbit-live/openapi/grabbit-live-grabs-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: we store your email address and a unique user identifier, plus the team name you choose
  - category: contact
    text: we store your email address and a unique user identifier
  - category: financial
    text: We store Stripe customer and subscription identifiers and a ledger of your credit transactions.
  - category: location
    text: the IP address the request came from
  - category: device
    text: the environment used (test or live)
  - category: behavioral
    text: the target URL and request parameters (viewport, format, and similar options)
  - category: other
    text: The images captured at your direction are stored in our cloud storage and served from public, unguessable URLs.
  deletion:
    route: email request to support@grabbit.live
    text: You can request access to, correction of, or deletion of your account data and your captured screenshots by emailing support@grabbit.live .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide and operate the service
    text: provide and operate the service, including capturing and serving screenshots
  - purpose: authentication and security
    text: authenticate you and secure your account
  - purpose: payments and credit usage
    text: process payments and account for credit usage
  - purpose: abuse and fraud prevention
    text: enforce rate limits and detect and prevent abuse and fraud
  - purpose: support
    text: respond to support requests
  - purpose: legal compliance
    text: comply with legal obligations
  residency:
  - region: United States
    text: data is processed and stored in the United States (primarily in the AWS US West region)
  retention:
  - period: 24 hours
    scope: idempotency records
    text: Idempotency records are deleted automatically after 24 hours.
  - period: until you delete them or ask us to
    scope: captured screenshots
    text: Captured screenshots are stored until you delete them or ask us to; they are not automatically deleted.
  - period: null
    scope: account records
    text: Account records are kept while your account is active and deleted on request after closure.
  - period: null
    scope: revoked API keys
    text: their hashed records are retained for audit purposes.
  rights:
  - right: access
    text: You can request access to, correction of, or deletion of your account data
  - right: correction
    text: You can request access to, correction of, or deletion of your account data
  - right: deletion
    text: or deletion of your account data and your captured screenshots
  role:
    text: For your account, usage, and billing data, we decide how the data is processed and act as the data controller. For the content of web pages you direct the service to capture, we act as a processor on your behalf
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, and we do not "share" it for cross-context behavioral advertising as defined under California law.
  subprocessors:
    text: Supabase Database, authentication, and file storage (hosted on AWS, US West region)
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: grabbit-live
provenance_date: '2026-11-09'
provider_name: grabbit-live
provider_slug: grabbit-live
slug: grabbit-live-privacy-policy
source_date: '2026-11-09'
source_filename: grabbit-live-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.grabbit.live/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: grabbit-live\naid: grabbit-live\nurl: https://www.grabbit.live/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For your account, usage, and billing data, we decide how the data is processed and act as the data controller.\n    For the content of web pages you direct the service to capture, we act as a processor on your behalf\ndata_categories:\n- category: identifying\n  text: we store your email address and a unique user identifier, plus the team name you choose\n- category: contact\n  text: we store your email address and a unique user identifier\n- category: financial\n  text: We store\
  \ Stripe customer and subscription identifiers and a ledger of your credit transactions.\n- category: location\n  text: the IP address the request came from\n- category: device\n  text: the environment used (test or live)\n- category: behavioral\n  text: the target URL and request parameters (viewport, format, and similar options)\n- category: other\n  text: The images captured at your direction are stored in our cloud storage and served from public, unguessable\n    URLs.\npurposes:\n- purpose: provide and operate the service\n  text: provide and operate the service, including capturing and serving screenshots\n- purpose: authentication and security\n  text: authenticate you and secure your account\n- purpose: payments and credit usage\n  text: process payments and account for credit usage\n- purpose: abuse and fraud prevention\n  text: enforce rate limits and detect and prevent abuse and fraud\n- purpose: support\n  text: respond to support requests\n- purpose: legal compliance\n  text:\
  \ comply with legal obligations\nretention:\n- scope: idempotency records\n  period: 24 hours\n  text: Idempotency records are deleted automatically after 24 hours.\n- scope: captured screenshots\n  period: until you delete them or ask us to\n  text: Captured screenshots are stored until you delete them or ask us to; they are not automatically deleted.\n- scope: account records\n  period: null\n  text: Account records are kept while your account is active and deleted on request after closure.\n- scope: revoked API keys\n  period: null\n  text: their hashed records are retained for audit purposes.\nresidency:\n- region: United States\n  text: data is processed and stored in the United States (primarily in the AWS US West region)\ntransfers: []\nsubprocessors:\n  url: null\n  text: Supabase Database, authentication, and file storage (hosted on AWS, US West region)\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to support@grabbit.live\n  text: You can\
  \ request access to, correction of, or deletion of your account data and your captured screenshots\n    by emailing support@grabbit.live .\nrights:\n- right: access\n  text: You can request access to, correction of, or deletion of your account data\n- right: correction\n  text: You can request access to, correction of, or deletion of your account data\n- right: deletion\n  text: or deletion of your account data and your captured screenshots\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, and we do not \"share\" it for cross-context behavioral advertising as\n    defined under California law.\n"
source_yaml_url: https://artifacts.apis.io/grabbit-live/privacy/grabbit-live-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from grabbit-live's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Screenshots
- AI Agents
- Automation
- Visual
---
