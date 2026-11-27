---
claim_count: 7
description: ''
doc:
  deletion:
    route: user self-service
    text: letting you see, export or delete every bit of your data at any time.
  dpa:
    available: null
    text: null
    url: null
  retention:
  - period: null
    scope: DNS query request and response data
    text: When answering a DNS query, the server discards all request and response data immediately after sending back the response to you.
  - period: null
    scope: logs
    text: If not specifically requested by the user, no data is logged.
  rights:
  - right: access and export
    text: letting you see, export or delete every bit of your data at any time.
  role:
    text: We use the following services as processors, as defined by the GDPR and similar regulations.
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: We do not (and will never) sell, license, sublicense or share any of the data submitted directly or indirectly by our users with any person or entity.
  subprocessors:
    text: We use the following services as processors, as defined by the GDPR and similar regulations. Stripe — for processing card payments PayPal — for processing PayPal payments BitPay — for processing cryptocurrency payments SendGrid — for sending transactional emails
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: NextDNS
provenance_date: '2026-11-10'
provider_name: NextDNS
provider_slug: nextdns
slug: nextdns-privacy-policy
source_date: '2026-11-10'
source_filename: nextdns-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://nextdns.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: NextDNS\naid: nextdns\nurl: https://nextdns.io/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: We use the following services as processors, as defined by the GDPR and similar regulations.\ndata_categories: []\npurposes: []\nretention:\n- scope: DNS query request and response data\n  period: null\n  text: When answering a DNS query, the server discards all request and response data immediately after sending\n    back the response to you.\n- scope: logs\n  period: null\n  text: If not specifically requested by the user, no data is logged.\nresidency: []\ntransfers: []\nsubprocessors:\n\
  \  url: null\n  text: We use the following services as processors, as defined by the GDPR and similar regulations. Stripe — for\n    processing card payments PayPal — for processing PayPal payments BitPay — for processing cryptocurrency payments\n    SendGrid — for sending transactional emails\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: user self-service\n  text: letting you see, export or delete every bit of your data at any time.\nrights:\n- right: access and export\n  text: letting you see, export or delete every bit of your data at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not (and will never) sell, license, sublicense or share any of the data submitted directly or indirectly\n    by our users with any person or entity.\n"
source_yaml_url: https://artifacts.apis.io/nextdns/privacy/nextdns-privacy-policy.yml
stated_fields:
- role
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 7 quoted statements, read from NextDNS's own page on 2026-11-10.
synthetic: false
tags:
- DNS
- Security
- Privacy
- Filtering
- Analytics
---
