---
api_specs:
- filename: p2flux-api-cancellation-api-openapi.yml
  format: yaml
  label: P2Flux API Cancellation API
  slug: p2flux-api-cancellation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/p2flux-api/openapi/p2flux-api-cancellation-api-openapi.yml
- filename: p2flux-api-one-time-payments-api-openapi.yml
  format: yaml
  label: P2Flux API One-time payments API
  slug: p2flux-api-one-time-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/p2flux-api/openapi/p2flux-api-one-time-payments-api-openapi.yml
- filename: p2flux-api-recurring-payments-api-openapi.yml
  format: yaml
  label: P2Flux API Recurring payments API
  slug: p2flux-api-recurring-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/p2flux-api/openapi/p2flux-api-recurring-payments-api-openapi.yml
- filename: p2flux-api-refunds-api-openapi.yml
  format: yaml
  label: P2Flux API Refunds API
  slug: p2flux-api-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/p2flux-api/openapi/p2flux-api-refunds-api-openapi.yml
- filename: p2flux-api-service-api-openapi.yml
  format: yaml
  label: P2Flux API Service API
  slug: p2flux-api-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/p2flux-api/openapi/p2flux-api-service-api-openapi.yml
- filename: p2flux-api-subscriptions-api-openapi.yml
  format: yaml
  label: P2Flux API Subscriptions API
  slug: p2flux-api-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/p2flux-api/openapi/p2flux-api-subscriptions-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: name; work email; company; website or product URL; product type
  - category: financial
    text: approximate monthly payment volume, if you provide it
  - category: location
    text: IP addresses and security logs
  - category: device
    text: the browser user agent
  - category: communication
    text: your message
  - category: identifying
    text: wallet addresses involved in processing a payment
  deletion:
    route: contact contact@p2flux.com
    text: To exercise a right, contact contact@p2flux.com .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: evaluate and respond to integration enquiries
    text: We use this information to evaluate the enquiry, understand the integration and respond to you.
  - purpose: operate, secure, monitor and troubleshoot the Services
    text: processed to provide, secure, monitor and troubleshoot the Services and to report transaction status back to the integrating system
  - purpose: sanctions screening
    text: it checks the wallet address paying and the merchant’s receiving wallet address against the public U.S. OFAC Specially Designated Nationals list
  - purpose: admitting paying Telegram channel members
    text: 'We process this to perform the service the channel owner and the subscriber asked for: admitting paying members and removing them when the subscription stops (contract).'
  retention:
  - period: 14 days
    scope: web server logs
    text: Those server logs are kept for 14 days and then deleted.
  - period: up to 24 months after the last substantive communication
    scope: enquiry correspondence
    text: Enquiry correspondence is normally retained for up to 24 months after the last substantive communication.
  - period: 90 days
    scope: encrypted backups of service configuration
    text: Encrypted backups of service configuration are kept for 90 days.
  - period: 30 days after the subscription ended
    scope: subscription records
    text: A subscription record is deleted from P2Flux’s active systems 30 days after the subscription ended
  rights:
  - right: access, correct, delete, restrict or object
    text: applicable data-protection law may give you rights to access, correct, delete, restrict or object to certain processing of personal information we hold about you
  - right: complain to supervisory authority
    text: or to complain to a competent supervisory authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: P2Flux does not sell personal information to advertisers.
  subprocessors:
    text: Today that means server hosting (Vultr), email delivery for the enquiry form and operational alerts (Resend), business email for the addresses shown on this site (Google Workspace), and encrypted off-site backups of service configuration (Backblaze B2).
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: P2Flux API
provenance_date: '2026-11-10'
provider_name: P2Flux API
provider_slug: p2flux-api
slug: p2flux-api-privacy-policy
source_date: '2026-11-10'
source_filename: p2flux-api-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://p2flux.com/privacy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: P2Flux API\naid: p2flux-api\nurl: https://p2flux.com/privacy.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: name; work email; company; website or product URL; product type\n- category: financial\n  text: approximate monthly payment volume, if you provide it\n- category: location\n  text: IP addresses and security logs\n- category: device\n  text: the browser user agent\n- category: communication\n  text: your message\n- category: identifying\n  text: wallet addresses involved in processing a payment\npurposes:\n- purpose: evaluate\
  \ and respond to integration enquiries\n  text: We use this information to evaluate the enquiry, understand the integration and respond to you.\n- purpose: operate, secure, monitor and troubleshoot the Services\n  text: processed to provide, secure, monitor and troubleshoot the Services and to report transaction status back\n    to the integrating system\n- purpose: sanctions screening\n  text: it checks the wallet address paying and the merchant’s receiving wallet address against the public U.S.\n    OFAC Specially Designated Nationals list\n- purpose: admitting paying Telegram channel members\n  text: 'We process this to perform the service the channel owner and the subscriber asked for: admitting paying\n    members and removing them when the subscription stops (contract).'\nretention:\n- scope: web server logs\n  period: 14 days\n  text: Those server logs are kept for 14 days and then deleted.\n- scope: enquiry correspondence\n  period: up to 24 months after the last substantive communication\n\
  \  text: Enquiry correspondence is normally retained for up to 24 months after the last substantive communication.\n- scope: encrypted backups of service configuration\n  period: 90 days\n  text: Encrypted backups of service configuration are kept for 90 days.\n- scope: subscription records\n  period: 30 days after the subscription ended\n  text: A subscription record is deleted from P2Flux’s active systems 30 days after the subscription ended\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: Today that means server hosting (Vultr), email delivery for the enquiry form and operational alerts (Resend),\n    business email for the addresses shown on this site (Google Workspace), and encrypted off-site backups of service\n    configuration (Backblaze B2).\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: contact contact@p2flux.com\n  text: To exercise a right, contact contact@p2flux.com .\nrights:\n- right: access, correct, delete, restrict or object\n\
  \  text: applicable data-protection law may give you rights to access, correct, delete, restrict or object to certain\n    processing of personal information we hold about you\n- right: complain to supervisory authority\n  text: or to complain to a competent supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: P2Flux does not sell personal information to advertisers.\n"
source_yaml_url: https://artifacts.apis.io/p2flux-api/privacy/p2flux-api-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from P2Flux API's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Payment API
- Cryptocurrency
- Stablecoins
- USDC
- Base
- Recurring Payments
- Subscription
- Refunds
- Non-Custodial
---
