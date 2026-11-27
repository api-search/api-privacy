---
api_specs:
- filename: canopypay-io-openapi-generated.yml
  format: yaml
  label: canopypay-io API
  slug: canopypay-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/canopypay-io/openapi/_ae-authored/canopypay-io-openapi-generated.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: Google provides a unique account identifier, your email address and its verification status, and basic profile information such as your name and profile photo when available.
  - category: contact
    text: When you use the support form, we receive the name, email address and message you enter
  - category: financial
    text: When a deposit arrives, we record transaction hashes, sending and receiving addresses, token and amount, routing and settlement transactions, fees and the net amount delivered.
  - category: device
    text: Our page-view logging records the page path, referring site’s host, whether a request appears automated and a pseudonymous visitor identifier.
  - category: behavioral
    text: We use Vercel Analytics for website usage measurements.
  deletion:
    route: Email jack@canopypay.io or use the support form to request deletion
    text: To request deletion, contact us using section 10.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account sign-in and authentication
    text: Canopy links that authentication identity to your Canopy account and uses your authentication identifier and email address to recognize you, create or access your account, maintain your sign-in session and send account or service emails.
  - purpose: Deposit routing and settlement
    text: We use these records to detect deposits, route funds, reconcile payments and display account activity.
  - purpose: Support
    text: We use these to investigate and respond to your request.
  - purpose: Fraud and abuse prevention
    text: We also use it to deliver support and service emails, measure website use, troubleshoot the service, prevent fraud and abuse, protect accounts and meet legal obligations.
  residency:
  - region: Unspecified
    text: Canopy and its providers may process information in countries other than the country where you live.
  retention:
  - period: null
    scope: Closed account records
    text: There is currently no automatic erasure schedule for those closed-account records.
  - period: 60 seconds
    scope: Authorization codes
    text: Authorization codes expire after 60 seconds, access tokens after one hour and refresh tokens after 30 days, or earlier on revocation.
  - period: 15 minutes
    scope: Wallet verification sessions
    text: Wallet verification sessions expire after 15 minutes
  rights:
  - right: Access, correction, deletion
    text: you may have rights to access, correct or delete personal information, restrict or object to processing, request a portable copy, withdraw consent where processing relies on consent, or complain to a privacy regulator.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: 'Service providers process the information needed for their role: Supabase for database storage and authentication; Vercel and Railway for hosting and background services; Axiom for application logs; Vercel Analytics for website measurements; Upstash for rate limiting; Temporal for job orchestration; Resend for email delivery; and Openfort for embedded wallets.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: canopypay-io
provenance_date: '2026-11-09'
provider_name: canopypay-io
provider_slug: canopypay-io
slug: canopypay-io-privacy-policy
source_date: '2026-11-09'
source_filename: canopypay-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.canopypay.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: canopypay-io\naid: canopypay-io\nurl: https://www.canopypay.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Google provides a unique account identifier, your email address and its verification status, and basic profile\n    information such as your name and profile photo when available.\n- category: contact\n  text: When you use the support form, we receive the name, email address and message you enter\n- category: financial\n  text: When a deposit arrives, we record transaction hashes, sending and receiving addresses, token\
  \ and amount,\n    routing and settlement transactions, fees and the net amount delivered.\n- category: device\n  text: Our page-view logging records the page path, referring site’s host, whether a request appears automated\n    and a pseudonymous visitor identifier.\n- category: behavioral\n  text: We use Vercel Analytics for website usage measurements.\npurposes:\n- purpose: Account sign-in and authentication\n  text: Canopy links that authentication identity to your Canopy account and uses your authentication identifier\n    and email address to recognize you, create or access your account, maintain your sign-in session and send account\n    or service emails.\n- purpose: Deposit routing and settlement\n  text: We use these records to detect deposits, route funds, reconcile payments and display account activity.\n- purpose: Support\n  text: We use these to investigate and respond to your request.\n- purpose: Fraud and abuse prevention\n  text: We also use it to deliver support and service\
  \ emails, measure website use, troubleshoot the service, prevent\n    fraud and abuse, protect accounts and meet legal obligations.\nretention:\n- scope: Closed account records\n  period: null\n  text: There is currently no automatic erasure schedule for those closed-account records.\n- scope: Authorization codes\n  period: 60 seconds\n  text: Authorization codes expire after 60 seconds, access tokens after one hour and refresh tokens after 30 days,\n    or earlier on revocation.\n- scope: Wallet verification sessions\n  period: 15 minutes\n  text: Wallet verification sessions expire after 15 minutes\nresidency:\n- region: Unspecified\n  text: Canopy and its providers may process information in countries other than the country where you live.\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Service providers process the information needed for their role: Supabase for database storage and authentication;\n    Vercel and Railway for hosting and background services; Axiom for application\
  \ logs; Vercel Analytics for website\n    measurements; Upstash for rate limiting; Temporal for job orchestration; Resend for email delivery; and Openfort\n    for embedded wallets.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email jack@canopypay.io or use the support form to request deletion\n  text: To request deletion, contact us using section 10.\nrights:\n- right: Access, correction, deletion\n  text: you may have rights to access, correct or delete personal information, restrict or object to processing,\n    request a portable copy, withdraw consent where processing relies on consent, or complain to a privacy regulator.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/canopypay-io/privacy/canopypay-io-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from canopypay-io's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Cryptocurrency
- Payments
- Deposit
---
