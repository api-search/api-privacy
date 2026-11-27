---
api_specs:
- filename: aerocell-app-api-openapi.json
  format: json
  label: 'AeroCell: Affordable eSIMs — Read-only API API'
  slug: aerocell-affordable-esims-read-only-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aerocell-app/openapi/_original/aerocell-app-api-openapi.json
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account information, including your name, email address, password for email/password accounts, phone number, avatar URL, and Google account identity details if you choose Google Sign-In.
  - category: financial
    text: Billing and payment information, including billing name, billing email, billing address, order totals, payment status, and wallet transaction records.
  - category: location
    text: approximate country when provided by trusted infrastructure headers
  - category: device
    text: browser or app user agent
  - category: communication
    text: live support messages, image attachments you choose to upload, linked order or profile context, customer alerts, purchase emails, install-detail emails
  deletion:
    route: in-product account deletion flow
    text: Where you use an in-product account deletion flow, the current backend implementation removes your user record and related orders, wallet transactions, and alerts, subject to any legal or operational retention requirements that may apply outside the immediate product workflow.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account management and authentication
    text: To create and manage your account and authenticate you across our services.
  - purpose: process purchases and billing
    text: To process purchases, wallet deposits, top-ups, refunds, billing records, and account-related requests.
  - purpose: eSIM provisioning
    text: To provision eSIMs, deliver install details, support activation, and synchronize lifecycle or usage data from fulfillment providers.
  - purpose: customer support
    text: To provide customer support, including relaying support messages and image attachments to support operations.
  - purpose: security and fraud prevention
    text: To maintain security, prevent abuse, investigate fraud, troubleshoot failures, review account access metadata, enforce rate limits, and comply with legal obligations.
  retention:
  - period: null
    scope: account, billing, order, and usage records
    text: We retain account, billing, order, and usage records for as long as needed to operate the service, provide support, maintain business records, resolve disputes, prevent fraud, and satisfy legal, tax, accounting, or compliance obligations.
  - period: null
    scope: support messages and attachments
    text: Support messages and attachments may be retained while a thread is active and for a reasonable period afterward for continuity, audit, and dispute handling.
  - period: 14 rotated log files
    scope: web server technical access logs
    text: It is configured to rotate these logs daily and keep 14 rotated log files.
  rights:
  - right: access, correction, deletion, restriction, portability, objection
    text: Depending on where you live, you may also have legal rights to request access, correction, deletion, restriction, portability, or objection.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: does not use your account data for third-party ad targeting, does not track you across apps or websites owned by other companies, and does not share your data with data brokers.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Your information may therefore be transferred to or accessed from jurisdictions outside the country where you live, including wherever our infrastructure, payment, communication, support, or fulfillment providers operate.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AeroCell
provenance_date: '2026-11-09'
provider_name: AeroCell
provider_slug: aerocell-app
slug: aerocell-app-privacy-policy
source_date: '2026-11-09'
source_filename: aerocell-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aerocell.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AeroCell\naid: aerocell-app\nurl: https://aerocell.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account information, including your name, email address, password for email/password accounts, phone number,\n    avatar URL, and Google account identity details if you choose Google Sign-In.\n- category: financial\n  text: Billing and payment information, including billing name, billing email, billing address, order totals, payment\n    status, and wallet transaction records.\n- category: location\n  text: approximate country\
  \ when provided by trusted infrastructure headers\n- category: device\n  text: browser or app user agent\n- category: communication\n  text: live support messages, image attachments you choose to upload, linked order or profile context, customer\n    alerts, purchase emails, install-detail emails\npurposes:\n- purpose: account management and authentication\n  text: To create and manage your account and authenticate you across our services.\n- purpose: process purchases and billing\n  text: To process purchases, wallet deposits, top-ups, refunds, billing records, and account-related requests.\n- purpose: eSIM provisioning\n  text: To provision eSIMs, deliver install details, support activation, and synchronize lifecycle or usage data\n    from fulfillment providers.\n- purpose: customer support\n  text: To provide customer support, including relaying support messages and image attachments to support operations.\n- purpose: security and fraud prevention\n  text: To maintain security, prevent\
  \ abuse, investigate fraud, troubleshoot failures, review account access metadata,\n    enforce rate limits, and comply with legal obligations.\nretention:\n- scope: account, billing, order, and usage records\n  period: null\n  text: We retain account, billing, order, and usage records for as long as needed to operate the service, provide\n    support, maintain business records, resolve disputes, prevent fraud, and satisfy legal, tax, accounting, or\n    compliance obligations.\n- scope: support messages and attachments\n  period: null\n  text: Support messages and attachments may be retained while a thread is active and for a reasonable period afterward\n    for continuity, audit, and dispute handling.\n- scope: web server technical access logs\n  period: 14 rotated log files\n  text: It is configured to rotate these logs daily and keep 14 rotated log files.\nresidency: []\ntransfers:\n- mechanism: other\n  text: Your information may therefore be transferred to or accessed from jurisdictions\
  \ outside the country where\n    you live, including wherever our infrastructure, payment, communication, support, or fulfillment providers operate.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: in-product account deletion flow\n  text: Where you use an in-product account deletion flow, the current backend implementation removes your user\n    record and related orders, wallet transactions, and alerts, subject to any legal or operational retention requirements\n    that may apply outside the immediate product workflow.\nrights:\n- right: access, correction, deletion, restriction, portability, objection\n  text: Depending on where you live, you may also have legal rights to request access, correction, deletion, restriction,\n    portability, or objection.\nsale_or_sharing:\n  stance: prohibited\n  text: does not use your account data for third-party ad targeting, does not track you across apps or websites\n    owned by\
  \ other companies, and does not share your data with data brokers.\n"
source_yaml_url: https://artifacts.apis.io/aerocell-app/privacy/aerocell-app-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from AeroCell's own page on 2026-11-09.
synthetic: false
tags:
- Travel
- eSIM
- Mobile Data
- International
- Connectivity
- Telecommunications
---
