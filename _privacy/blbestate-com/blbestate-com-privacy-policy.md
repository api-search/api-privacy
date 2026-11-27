---
api_specs:
- filename: blbestate-com-agent-api-openapi.yml
  format: yaml
  label: SalesSwipe Agent API
  slug: blbestate-com-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blbestate-com/openapi/blbestate-com-agent-api-openapi.yml
- filename: blbestate-com-mcp-api-openapi.yml
  format: yaml
  label: SalesSwipe MCP API
  slug: blbestate-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blbestate-com/openapi/blbestate-com-mcp-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address, optional name, account creation and last-login timestamps, sign-in method, marketing choice, plan and entitlement identifiers.
  - category: behavioral
    text: Pages viewed, button interactions, referrer and device/browser context, browser analytics identifiers from PostHog and Cloudflare Web Analytics
  - category: location
    text: IP/network metadata, request time, route, rate-limit counters, authentication tokens, and search parameters such as an owner name, address, parcel, county, state or map bounds that you submit.
  - category: financial
    text: Stripe processes payment details.
  - category: identifying
    text: Source and harvest details plus parcel IDs, owner names, situs and mailing addresses, property coordinates
  - category: communication
    text: support questions, and contact messages you choose to send
  deletion:
    route: account deletion request or workspace endpoint
    text: You can delete a synced blob through the authenticated workspace endpoint, and you can request account deletion.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service provision
    text: Provide accounts, sign-in, product access, search, maps, optional sync, support and billing management.
  - purpose: newsletters
    text: Deliver confirmed newsletters and transactional email, honor unsubscribes, and prevent repeat sends to suppressed addresses.
  - purpose: security and analytics
    text: Secure the services, rate-limit abuse, diagnose errors, measure page and purchase-intent performance, and maintain audit records.
  retention:
  - period: while an account or subscription is active and for a reasonable period afterward
    scope: account and entitlement records
    text: We keep account and entitlement records while an account or subscription is active and for a reasonable period afterward for security, tax, dispute and fulfillment needs.
  - period: 30 days
    scope: session cookie
    text: The session cookie expires after 30 days unless cleared earlier.
  - period: until deleted by the authenticated user or removed with the associated service account
    scope: synced workspace blobs
    text: Synced workspace blobs remain until deleted by the authenticated user or removed with the associated service account, subject to backup and integrity cycles.
  rights:
  - right: access, correction, deletion
    text: request access, correction or deletion of account-related information by using the privacy contact
  - right: unsubscribe
    text: every Estate Brief has a signed one-click unsubscribe link.
  - right: public-record suppression
    text: any person may use the non-login-gated record-removal channel
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell account, billing, contact, workspace or support data, and we do not share those categories for cross-context behavioral advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SalesSwipe
provenance_date: '2026-11-09'
provider_name: SalesSwipe
provider_slug: blbestate-com
slug: blbestate-com-privacy-policy
source_date: '2026-11-09'
source_filename: blbestate-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://blbestate.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SalesSwipe\naid: blbestate-com\nurl: https://blbestate.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Email address, optional name, account creation and last-login timestamps, sign-in method, marketing choice,\n    plan and entitlement identifiers.\n- category: behavioral\n  text: Pages viewed, button interactions, referrer and device/browser context, browser analytics identifiers from\n    PostHog and Cloudflare Web Analytics\n- category: location\n  text: IP/network metadata, request time, route, rate-limit counters, authentication\
  \ tokens, and search parameters\n    such as an owner name, address, parcel, county, state or map bounds that you submit.\n- category: financial\n  text: Stripe processes payment details.\n- category: identifying\n  text: Source and harvest details plus parcel IDs, owner names, situs and mailing addresses, property coordinates\n- category: communication\n  text: support questions, and contact messages you choose to send\npurposes:\n- purpose: service provision\n  text: Provide accounts, sign-in, product access, search, maps, optional sync, support and billing management.\n- purpose: newsletters\n  text: Deliver confirmed newsletters and transactional email, honor unsubscribes, and prevent repeat sends to suppressed\n    addresses.\n- purpose: security and analytics\n  text: Secure the services, rate-limit abuse, diagnose errors, measure page and purchase-intent performance, and\n    maintain audit records.\nretention:\n- scope: account and entitlement records\n  period: while an account\
  \ or subscription is active and for a reasonable period afterward\n  text: We keep account and entitlement records while an account or subscription is active and for a reasonable\n    period afterward for security, tax, dispute and fulfillment needs.\n- scope: session cookie\n  period: 30 days\n  text: The session cookie expires after 30 days unless cleared earlier.\n- scope: synced workspace blobs\n  period: until deleted by the authenticated user or removed with the associated service account\n  text: Synced workspace blobs remain until deleted by the authenticated user or removed with the associated service\n    account, subject to backup and integrity cycles.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion request or workspace endpoint\n  text: You can delete a synced blob through the authenticated workspace endpoint, and you can request account deletion.\nrights:\n- right:\
  \ access, correction, deletion\n  text: request access, correction or deletion of account-related information by using the privacy contact\n- right: unsubscribe\n  text: every Estate Brief has a signed one-click unsubscribe link.\n- right: public-record suppression\n  text: any person may use the non-login-gated record-removal channel\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell account, billing, contact, workspace or support data, and we do not share those categories\n    for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/blbestate-com/privacy/blbestate-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from SalesSwipe's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Platform
- Property
- Sales
- Software-as-a-Service
---
