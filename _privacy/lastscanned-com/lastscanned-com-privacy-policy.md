---
api_specs:
- filename: lastscanned-com-account-api-openapi.yml
  format: yaml
  label: lastscanned Account API
  slug: lastscanned-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastscanned-com/openapi/lastscanned-com-account-api-openapi.yml
- filename: lastscanned-com-carriers-api-openapi.yml
  format: yaml
  label: lastscanned Carriers API
  slug: lastscanned-com-carriers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastscanned-com/openapi/lastscanned-com-carriers-api-openapi.yml
- filename: lastscanned-com-track-api-openapi.yml
  format: yaml
  label: lastscanned Track API
  slug: lastscanned-com-track-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastscanned-com/openapi/lastscanned-com-track-api-openapi.yml
- filename: lastscanned-com-tracking-api-openapi.yml
  format: yaml
  label: lastscanned Tracking API
  slug: lastscanned-com-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastscanned-com/openapi/lastscanned-com-tracking-api-openapi.yml
- filename: lastscanned-com-watches-api-openapi.yml
  format: yaml
  label: lastscanned Watches API
  slug: lastscanned-com-watches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastscanned-com/openapi/lastscanned-com-watches-api-openapi.yml
- filename: lastscanned-com-webhooks-api-openapi.yml
  format: yaml
  label: lastscanned Webhooks API
  slug: lastscanned-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lastscanned-com/openapi/lastscanned-com-webhooks-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information you give us, such as your email address.
  - category: behavioral
    text: Data you send to the service, such as the tracking numbers you look up and the results.
  - category: device
    text: Usage and technical information, such as requests made, IP address, browser and device details.
  - category: financial
    text: Billing information, handled by our payment processor. We do not store your full card details.
  deletion:
    route: Email support@lastscanned.com to request deletion or account closure
    text: You can ask to access, correct or delete your personal information, or close your account, by emailing support@lastscanned.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and improve service
    text: To provide, maintain and improve the service.
  - purpose: Account and payments
    text: To manage your account, process payments and send you service messages.
  - purpose: Abuse prevention and security
    text: To enforce limits, prevent abuse and keep the service secure.
  - purpose: Legal obligations
    text: To meet legal obligations.
  retention:
  - period: 30 days
    scope: Lookup logs
    text: Each lookup (the tracking number, carrier, result status, whether it was answered from cache, and the API key, sign-in or app it came from) is kept for 30 days, then deleted.
  - period: 5 minutes
    scope: Tracking results cache
    text: A carrier's answer is cached for 5 minutes (1 hour once delivered).
  - period: 2 days
    scope: Lookups without an account
    text: We count them by IP address, kept only as a salted hash and deleted after 2 days.
  - period: 90 days
    scope: Watches
    text: A watched tracking number is kept until the watch ends, then for 90 days.
  - period: 30 days
    scope: Webhook deliveries
    text: Webhook deliveries are kept for 30 days.
  - period: 90 days
    scope: Request logs
    text: Request logs. Records of requests (the page or API path, which can include a tracking number, the referring site, browser type, network and country, but not your IP address) are kept for 90 days.
  - period: 7 days
    scope: Authorization codes
    text: Authorization codes work for 5 minutes and are deleted within 7 days
  - period: 1 hour
    scope: Access tokens
    text: access tokens last 1 hour and refresh tokens 30 days
  - period: 30 days
    scope: Sign-in link request records
    text: Sign-in links work for 15 minutes; the record of each request (email address and IP address) is kept for 30 days.
  - period: 30 days
    scope: Sessions
    text: Sessions last 30 days.
  - period: null
    scope: Account information
    text: Account information is kept while your account is open, and longer only where the law requires it.
  rights:
  - right: Access, correction, deletion and account closure
    text: You can ask to access, correct or delete your personal information, or close your account, by emailing support@lastscanned.com .
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: lastscanned
provenance_date: '2026-11-09'
provider_name: lastscanned
provider_slug: lastscanned-com
slug: lastscanned-com-privacy-policy
source_date: '2026-11-09'
source_filename: lastscanned-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://lastscanned.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: lastscanned\naid: lastscanned-com\nurl: https://lastscanned.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information you give us, such as your email address.\n- category: behavioral\n  text: Data you send to the service, such as the tracking numbers you look up and the results.\n- category: device\n  text: Usage and technical information, such as requests made, IP address, browser and device details.\n- category: financial\n  text: Billing information, handled by our payment processor. We do not store your full card\
  \ details.\npurposes:\n- purpose: Provide and improve service\n  text: To provide, maintain and improve the service.\n- purpose: Account and payments\n  text: To manage your account, process payments and send you service messages.\n- purpose: Abuse prevention and security\n  text: To enforce limits, prevent abuse and keep the service secure.\n- purpose: Legal obligations\n  text: To meet legal obligations.\nretention:\n- scope: Lookup logs\n  period: 30 days\n  text: Each lookup (the tracking number, carrier, result status, whether it was answered from cache, and the API\n    key, sign-in or app it came from) is kept for 30 days, then deleted.\n- scope: Tracking results cache\n  period: 5 minutes\n  text: A carrier's answer is cached for 5 minutes (1 hour once delivered).\n- scope: Lookups without an account\n  period: 2 days\n  text: We count them by IP address, kept only as a salted hash and deleted after 2 days.\n- scope: Watches\n  period: 90 days\n  text: A watched tracking number\
  \ is kept until the watch ends, then for 90 days.\n- scope: Webhook deliveries\n  period: 30 days\n  text: Webhook deliveries are kept for 30 days.\n- scope: Request logs\n  period: 90 days\n  text: Request logs. Records of requests (the page or API path, which can include a tracking number, the referring\n    site, browser type, network and country, but not your IP address) are kept for 90 days.\n- scope: Authorization codes\n  period: 7 days\n  text: Authorization codes work for 5 minutes and are deleted within 7 days\n- scope: Access tokens\n  period: 1 hour\n  text: access tokens last 1 hour and refresh tokens 30 days\n- scope: Sign-in link request records\n  period: 30 days\n  text: Sign-in links work for 15 minutes; the record of each request (email address and IP address) is kept for\n    30 days.\n- scope: Sessions\n  period: 30 days\n  text: Sessions last 30 days.\n- scope: Account information\n  period: null\n  text: Account information is kept while your account is open, and\
  \ longer only where the law requires it.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email support@lastscanned.com to request deletion or account closure\n  text: You can ask to access, correct or delete your personal information, or close your account, by emailing support@lastscanned.com\n    .\nrights:\n- right: Access, correction, deletion and account closure\n  text: You can ask to access, correct or delete your personal information, or close your account, by emailing support@lastscanned.com\n    .\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/lastscanned-com/privacy/lastscanned-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from lastscanned's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Tracking
- Logistics
- MCP
---
