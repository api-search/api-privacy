---
api_specs:
- filename: billdog-io-openapi-generated.yml
  format: yaml
  label: BillDog API
  slug: billdog-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billdog-io/openapi/_ae-authored/billdog-io-openapi-generated.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name and email address
  - category: contact
    text: 'Sign-in identifiers: the email address, phone number, or username a user signs in with'
  - category: financial
    text: Payment information (processed securely by third-party providers)
  - category: device
    text: Device information and IP addresses
  - category: behavioral
    text: Analytics data about how you use our services
  - category: other
    text: 'Credential material: password hashes (Argon2id, combined with a server-side pepper held outside the database), TOTP secrets, single-use backup codes, and passkey public keys.'
  deletion:
    route: Contact privacy officer at privacy@billdog.io
    text: To exercise any of these rights, please contact our privacy officer at privacy@billdog.io.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, maintain, and improve services
    text: Provide, maintain, and improve our services
  - purpose: Process transactions
    text: Process transactions and send related information
  - purpose: Fraud and abuse prevention
    text: Detect and prevent fraud and abuse
  - purpose: Legal compliance
    text: Comply with legal obligations
  residency:
  - region: United States
    text: Authentication data — password hashes, MFA secrets, passkey public keys, refresh tokens, and signing keys — is stored in the United States for every project, whatever data region that project has selected.
  - region: Singapore (Asia cluster)
    text: This aligns with our Singapore-based Asia data residency cluster.
  retention:
  - period: 540 days
    scope: In-product analytics events
    text: In-product analytics event retention defaults to 540 days unless a shorter window is configured in your project settings.
  - period: 90 days
    scope: Soft-deleted relational records
    text: Soft-deleted relational records are purged within 90 days.
  rights:
  - right: access
    text: you have the right to access, rectify, or erase your account data, object to or restrict processing, request data portability, and withdraw consent.
  - right: complaint to supervisory authority
    text: You also have the right to lodge a complaint with an EU/UK supervisory authority.
  - right: know, correct, delete (CCPA)
    text: you have the right to know what personal data we collect, correct inaccuracies, delete data, and restrict the use of sensitive personal information.
  role:
    text: we process subscription and transaction data on your behalf as a data processor
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: For a list of the third-party sub-processors we engage, please refer to our Sub-processors List .
    url: https://billdog.io/subprocessors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BillDog
provenance_date: '2026-11-09'
provider_name: BillDog
provider_slug: billdog-io
slug: billdog-io-privacy-policy
source_date: '2026-11-09'
source_filename: billdog-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://billdog.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BillDog\naid: billdog-io\nurl: https://billdog.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we process subscription and transaction data on your behalf as a data processor\ndata_categories:\n- category: identifying\n  text: Name and email address\n- category: contact\n  text: 'Sign-in identifiers: the email address, phone number, or username a user signs in with'\n- category: financial\n  text: Payment information (processed securely by third-party providers)\n- category: device\n  text: Device information and IP addresses\n- category: behavioral\n  text: Analytics data about how you\
  \ use our services\n- category: other\n  text: 'Credential material: password hashes (Argon2id, combined with a server-side pepper held outside the database),\n    TOTP secrets, single-use backup codes, and passkey public keys.'\npurposes:\n- purpose: Provide, maintain, and improve services\n  text: Provide, maintain, and improve our services\n- purpose: Process transactions\n  text: Process transactions and send related information\n- purpose: Fraud and abuse prevention\n  text: Detect and prevent fraud and abuse\n- purpose: Legal compliance\n  text: Comply with legal obligations\nretention:\n- scope: In-product analytics events\n  period: 540 days\n  text: In-product analytics event retention defaults to 540 days unless a shorter window is configured in your\n    project settings.\n- scope: Soft-deleted relational records\n  period: 90 days\n  text: Soft-deleted relational records are purged within 90 days.\nresidency:\n- region: United States\n  text: Authentication data — password\
  \ hashes, MFA secrets, passkey public keys, refresh tokens, and signing keys\n    — is stored in the United States for every project, whatever data region that project has selected.\n- region: Singapore (Asia cluster)\n  text: This aligns with our Singapore-based Asia data residency cluster.\ntransfers: []\nsubprocessors:\n  url: https://billdog.io/subprocessors\n  text: For a list of the third-party sub-processors we engage, please refer to our Sub-processors List .\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact privacy officer at privacy@billdog.io\n  text: To exercise any of these rights, please contact our privacy officer at privacy@billdog.io.\nrights:\n- right: access\n  text: you have the right to access, rectify, or erase your account data, object to or restrict processing, request\n    data portability, and withdraw consent.\n- right: complaint to supervisory authority\n  text: You also have the right to lodge a complaint with an EU/UK supervisory\
  \ authority.\n- right: know, correct, delete (CCPA)\n  text: you have the right to know what personal data we collect, correct inaccuracies, delete data, and restrict\n    the use of sensitive personal information.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/billdog-io/privacy/billdog-io-privacy-policy.yml
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
summary_line: 21 quoted statements, read from BillDog's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Analytics
- Monetization
- Software-as-a-Service
- Platform
- Company
---
