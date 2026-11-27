---
api_specs:
- filename: carryo-io-health-api-openapi.yml
  format: yaml
  label: Carryo Health API
  slug: carryo-io-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carryo-io/openapi/carryo-io-health-api-openapi.yml
- filename: carryo-io-mcp-api-openapi.yml
  format: yaml
  label: Carryo MCP API
  slug: carryo-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carryo-io/openapi/carryo-io-mcp-api-openapi.yml
- filename: carryo-io-well-known-api-openapi.yml
  format: yaml
  label: Carryo .well Known API
  slug: carryo-io-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carryo-io/openapi/carryo-io-well-known-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: identifying
    text: Carryo uses Clerk for authentication. The authenticated account identifier, such as Clerk sub, is used to associate websites with their owner.
  - category: contact
    text: Verified email addresses are normalized and SHA-256 hashed before transmission; raw email addresses are not sent to OpenAI for this measurement.
  - category: communication
    text: Managed website forms When a website uses Carryo forms, Carryo processes the fields the visitor submits on behalf of the website owner.
  - category: device
    text: Viewer and operational data Carryo may process viewer access data and operational logs, including viewed-at timestamp, device type, country, referrer, and a generated viewer session identifier
  - category: behavioral
    text: Carryo may process product analytics events to understand signup, authentication, MCP connection, tool usage, publishing, draft, update, revocation, and billing-status flows.
  deletion:
    route: Account settings 'Delete account' option, or email tuomas@carryo.io and support requests
    text: You can delete your account by signing in to Carryo, opening your account settings, and selecting “Delete account”.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: authenticate users
    text: 'Carryo uses data to: authenticate users create and manage share links serve published websites'
  - purpose: measure advertising effectiveness
    text: measure the effectiveness of Carryo advertising
  - purpose: service reliability and abuse prevention
    text: service reliability troubleshooting abuse prevention basic analytics
  residency:
  - region: Europe
    text: We use Cloudflare's European regions to keep website data in Europe.
  retention:
  - period: 30 days
    scope: managed website form responses
    text: Responses are retained for the period disclosed beside the form, normally 30 days, and can be exported or deleted by an authorized website user.
  - period: 7 days
    scope: offline websites
    text: websites taken offline are permanently deleted after 7 days
  - period: 30 days
    scope: free websites without owner action
    text: free links go offline after 30 days without an owner action in Carryo; visitor views do not extend this period
  - period: seven days
    scope: undelivered ad payloads
    text: Undelivered payloads expire after seven days.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: Carryo does not state or offer any sale of personal data through this service.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Carryo
provenance_date: '2026-11-09'
provider_name: Carryo
provider_slug: carryo-io
slug: carryo-io-privacy-policy
source_date: '2026-11-09'
source_filename: carryo-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://carryo.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Carryo\naid: carryo-io\nurl: https://carryo.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Carryo uses Clerk for authentication. The authenticated account identifier, such as Clerk sub, is used to\n    associate websites with their owner.\n- category: contact\n  text: Verified email addresses are normalized and SHA-256 hashed before transmission; raw email addresses are\n    not sent to OpenAI for this measurement.\n- category: communication\n  text: Managed website forms When a website uses Carryo forms, Carryo processes the\
  \ fields the visitor submits\n    on behalf of the website owner.\n- category: device\n  text: Viewer and operational data Carryo may process viewer access data and operational logs, including viewed-at\n    timestamp, device type, country, referrer, and a generated viewer session identifier\n- category: behavioral\n  text: Carryo may process product analytics events to understand signup, authentication, MCP connection, tool usage,\n    publishing, draft, update, revocation, and billing-status flows.\npurposes:\n- purpose: authenticate users\n  text: 'Carryo uses data to: authenticate users create and manage share links serve published websites'\n- purpose: measure advertising effectiveness\n  text: measure the effectiveness of Carryo advertising\n- purpose: service reliability and abuse prevention\n  text: service reliability troubleshooting abuse prevention basic analytics\nretention:\n- scope: managed website form responses\n  period: 30 days\n  text: Responses are retained for the\
  \ period disclosed beside the form, normally 30 days, and can be exported or\n    deleted by an authorized website user.\n- scope: offline websites\n  period: 7 days\n  text: websites taken offline are permanently deleted after 7 days\n- scope: free websites without owner action\n  period: 30 days\n  text: free links go offline after 30 days without an owner action in Carryo; visitor views do not extend this\n    period\n- scope: undelivered ad payloads\n  period: seven days\n  text: Undelivered payloads expire after seven days.\nresidency:\n- region: Europe\n  text: We use Cloudflare's European regions to keep website data in Europe.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings 'Delete account' option, or email tuomas@carryo.io and support requests\n  text: You can delete your account by signing in to Carryo, opening your account settings, and selecting “Delete\n    account”.\nrights:\
  \ []\nsale_or_sharing:\n  stance: unstated\n  text: Carryo does not state or offer any sale of personal data through this service.\n"
source_yaml_url: https://artifacts.apis.io/carryo-io/privacy/carryo-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
summary_line: 14 quoted statements, read from Carryo's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Website Publishing
- Content Generation
- Software-as-a-Service
- Low-Code
---
