---
api_specs:
- filename: tempmailgrab-byod-api-openapi.yml
  format: yaml
  label: TempMailGrab API Byod API
  slug: tempmailgrab-byod-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tempmailgrab/openapi/tempmailgrab-byod-api-openapi.yml
- filename: tempmailgrab-inbox-api-openapi.yml
  format: yaml
  label: TempMailGrab API Inbox API
  slug: tempmailgrab-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tempmailgrab/openapi/tempmailgrab-inbox-api-openapi.yml
- filename: tempmailgrab-messages-api-openapi.yml
  format: yaml
  label: TempMailGrab API Messages API
  slug: tempmailgrab-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tempmailgrab/openapi/tempmailgrab-messages-api-openapi.yml
- filename: tempmailgrab-tempmailgrab-api-api-openapi.yml
  format: yaml
  label: TempMailGrab API TempMailGrab API
  slug: tempmailgrab-tempmailgrab-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tempmailgrab/openapi/tempmailgrab-tempmailgrab-api-api-openapi.yml
- filename: tempmailgrab-webhooks-api-openapi.yml
  format: yaml
  label: TempMailGrab API Webhooks API
  slug: tempmailgrab-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tempmailgrab/openapi/tempmailgrab-webhooks-api-openapi.yml
claim_count: 9
description: ''
doc:
  data_categories:
  - category: communication
    text: Disposable inboxes & messages — the address you generate and any email it receives, kept only until the inbox's time-to-live (TTL) expires, then permanently purged.
  - category: device
    text: A session cookie — an HMAC-signed, httpOnly cookie that privately ties inboxes to your browser so only you can read them. It holds no personal data.
  - category: contact
    text: if you create an API account, we store your email address (or GitHub identifier) and a salted password hash.
  - category: other
    text: Abuse-prevention metadata — transient request data used only to rate-limit and stop abuse, not to profile you.
  deletion:
    route: Delete an inbox from the homepage or let it expire
    text: You can delete an inbox at any time from the homepage, or simply let it expire.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: abuse prevention
    text: transient request data used only to rate-limit and stop abuse, not to profile you
  - purpose: convenience extraction
    text: one-time passcodes and verification links are extracted for convenience
  retention:
  - period: until the inbox's time-to-live (TTL) expires
    scope: disposable inboxes and messages
    text: kept only until the inbox's time-to-live (TTL) expires, then permanently purged.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: No selling, renting, or sharing of personal data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TempMailGrab API
provenance_date: '2026-11-10'
provider_name: TempMailGrab API
provider_slug: tempmailgrab
slug: tempmailgrab-privacy-policy
source_date: '2026-11-10'
source_filename: tempmailgrab-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tempmailgrab.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TempMailGrab API\naid: tempmailgrab\nurl: https://tempmailgrab.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: communication\n  text: Disposable inboxes & messages — the address you generate and any email it receives, kept only until the\n    inbox's time-to-live (TTL) expires, then permanently purged.\n- category: device\n  text: A session cookie — an HMAC-signed, httpOnly cookie that privately ties inboxes to your browser so only you\n    can read them. It holds no personal data.\n- category: contact\n  text: if you create an API account, we store\
  \ your email address (or GitHub identifier) and a salted password hash.\n- category: other\n  text: Abuse-prevention metadata — transient request data used only to rate-limit and stop abuse, not to profile\n    you.\npurposes:\n- purpose: abuse prevention\n  text: transient request data used only to rate-limit and stop abuse, not to profile you\n- purpose: convenience extraction\n  text: one-time passcodes and verification links are extracted for convenience\nretention:\n- scope: disposable inboxes and messages\n  period: until the inbox's time-to-live (TTL) expires\n  text: kept only until the inbox's time-to-live (TTL) expires, then permanently purged.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete an inbox from the homepage or let it expire\n  text: You can delete an inbox at any time from the homepage, or simply let it expire.\nrights: []\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: No selling, renting, or sharing of personal data.\n"
source_yaml_url: https://artifacts.apis.io/tempmailgrab/privacy/tempmailgrab-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- sale_or_sharing
summary_line: 9 quoted statements, read from TempMailGrab API's own page on 2026-11-10.
synthetic: false
tags:
- Email
- temporary-email
- Disposable Email
- OTP
- Webhook
- QA
- Testing
- Playwright
- Cypress
- Developer Tools
- Email Testing
- CI
---
