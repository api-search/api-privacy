---
api_specs:
- filename: blockreq-com-build-openapi-generated.yml
  format: yaml
  label: BlockReq build API
  slug: build-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockreq-com/openapi/_ae-authored/blockreq-com-build-openapi-generated.yml
- filename: blockreq-com-getting-started-openapi-generated.yml
  format: yaml
  label: BlockReq Getting Started API
  slug: getting-started-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockreq-com/openapi/_ae-authored/blockreq-com-getting-started-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account details: your email address and, if you sign in with Google or GitHub, the name, email address, and profile picture those services share.'
  - category: financial
    text: 'Payment details: Stripe processes all payments. We receive and keep the amount, the payment method type, and for cards the brand, last four digits, and expiry date.'
  - category: device
    text: 'Sign-in records: for each sign-in session we keep the IP address and browser user agent, to protect your account.'
  - category: other
    text: we record the time, network, method, status, duration, client IP address, and the request body up to 15,000 bytes.
  - category: behavioral
    text: 'Website analytics: how pages on blockreq.com are used, collected with PostHog and Google Analytics as described under Cookies below.'
  - category: communication
    text: 'Support and forms: what you send us by email or support ticket, and what you enter in forms such as Developer Boost (name, email, and GitHub repository).'
  deletion:
    route: Ask to delete account by email to support@blockreq.com
    text: When you ask us to delete your account, we delete or anonymize your data, except records the law requires us to keep.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account and sign-in
    text: To create and secure your account and sign you in.
  - purpose: RPC service
    text: 'To run the RPC service: routing requests, applying rate limits and plan quotas, and preventing abuse.'
  - purpose: billing
    text: To bill you, keep payment records, and send receipts and usage alerts.
  - purpose: support
    text: To answer support requests.
  - purpose: analytics
    text: To understand how the site is used and improve it.
  retention:
  - period: up to 3 months
    scope: Request logs
    text: 'Request logs: up to 3 months.'
  - period: while your account exists
    scope: Account data
    text: 'Account data: while your account exists.'
  - period: 15-second counts for 24 hours, then daily totals for 60 days
    scope: Usage counts
    text: 'Usage counts: 15-second counts for 24 hours, then daily totals for 60 days.'
  - period: 90 days
    scope: Developer Boost applications
    text: 'Developer Boost applications: 90 days.'
  rights:
  - right: access
    text: give you a copy of the personal data we hold about you
  - right: correction
    text: correct it
  - right: deletion
    text: delete it, including your account
  - right: restriction or objection
    text: restrict or object to how we use it
  role:
    text: BLOCKREQ TECHNOLOGY LIMITED, a company registered in Hong Kong, runs BlockReq and is responsible for the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data
  subprocessors:
    text: 'Hosting and infrastructure providers: website hosting, content delivery, databases, email delivery, request log storage, and the servers that run our RPC service.'
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the safeguards our providers offer, such as the European Commission's Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BlockReq
provenance_date: '2026-11-09'
provider_name: BlockReq
provider_slug: blockreq-com
slug: blockreq-com-privacy-policy
source_date: '2026-11-09'
source_filename: blockreq-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://blockreq.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BlockReq\naid: blockreq-com\nurl: https://blockreq.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: BLOCKREQ TECHNOLOGY LIMITED, a company registered in Hong Kong, runs BlockReq and is responsible for the\n    personal data described here.\ndata_categories:\n- category: contact\n  text: 'Account details: your email address and, if you sign in with Google or GitHub, the name, email address,\n    and profile picture those services share.'\n- category: financial\n  text: 'Payment details: Stripe processes all payments. We receive and keep the amount, the payment method type,\n    and\
  \ for cards the brand, last four digits, and expiry date.'\n- category: device\n  text: 'Sign-in records: for each sign-in session we keep the IP address and browser user agent, to protect your\n    account.'\n- category: other\n  text: we record the time, network, method, status, duration, client IP address, and the request body up to 15,000\n    bytes.\n- category: behavioral\n  text: 'Website analytics: how pages on blockreq.com are used, collected with PostHog and Google Analytics as described\n    under Cookies below.'\n- category: communication\n  text: 'Support and forms: what you send us by email or support ticket, and what you enter in forms such as Developer\n    Boost (name, email, and GitHub repository).'\npurposes:\n- purpose: account and sign-in\n  text: To create and secure your account and sign you in.\n- purpose: RPC service\n  text: 'To run the RPC service: routing requests, applying rate limits and plan quotas, and preventing abuse.'\n- purpose: billing\n  text: To bill\
  \ you, keep payment records, and send receipts and usage alerts.\n- purpose: support\n  text: To answer support requests.\n- purpose: analytics\n  text: To understand how the site is used and improve it.\nretention:\n- scope: Request logs\n  period: up to 3 months\n  text: 'Request logs: up to 3 months.'\n- scope: Account data\n  period: while your account exists\n  text: 'Account data: while your account exists.'\n- scope: Usage counts\n  period: 15-second counts for 24 hours, then daily totals for 60 days\n  text: 'Usage counts: 15-second counts for 24 hours, then daily totals for 60 days.'\n- scope: Developer Boost applications\n  period: 90 days\n  text: 'Developer Boost applications: 90 days.'\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we rely on the safeguards our providers offer, such as the European Commission's Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: 'Hosting and infrastructure providers: website hosting, content delivery, databases, email\
  \ delivery, request\n    log storage, and the servers that run our RPC service.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Ask to delete account by email to support@blockreq.com\n  text: When you ask us to delete your account, we delete or anonymize your data, except records the law requires\n    us to keep.\nrights:\n- right: access\n  text: give you a copy of the personal data we hold about you\n- right: correction\n  text: correct it\n- right: deletion\n  text: delete it, including your account\n- right: restriction or objection\n  text: restrict or object to how we use it\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data\n"
source_yaml_url: https://artifacts.apis.io/blockreq-com/privacy/blockreq-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from BlockReq's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Blockchain
- RPC
- EVM
- Infrastructure
- Developer Tools
---
