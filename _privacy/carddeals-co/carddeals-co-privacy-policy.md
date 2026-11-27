---
api_specs:
- filename: carddeals-co-gift-card-deals-api-openapi.yml
  format: yaml
  label: CardDeals Gift-card deals API
  slug: carddeals-co-gift-card-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/carddeals-co/openapi/carddeals-co-gift-card-deals-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, account ID, IP address, browser user agent, cookie identifiers, and random IDs stored in your browser or the extension
  - category: financial
    text: Gift cards you bought from us or sold to us, amounts, order and payout status, Stripe payment and payout-account references, and the encrypted number and PIN of each card you sold us.
  - category: biometric
    text: The result of the identity check run by Didit, including details read from your ID document (such as your name and document number) and the outcome of selfie, liveness, face-match, and screening checks
  - category: behavioral
    text: Pages viewed, referring page, campaign (UTM) parameters, search terms, offer and banner clicks, and session replays of the sign-in, sign-up, brand, and /sell pages with form inputs masked
  - category: communication
    text: Messages you send to support or through our contact form, and ratings or comments you submit as browser extension feedback
  - category: location
    text: Country (and, in Google Analytics, region or city) derived from your IP address
  - category: device
    text: Browser and operating system details, website error events, and browser extension version
  deletion:
    route: Email us
    text: To delete your account, email us; we complete verified deletion requests within thirty (30) days, except for records we are required or permitted by law to keep.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Authentication, account management, security, fraud prevention, analytics
    text: Authentication, account management, security, fraud prevention, analytics
  - purpose: Verifying buyers and sellers, preventing fraud, chargebacks, and money laundering
    text: Verifying buyers and sellers, preventing fraud, chargebacks, and money laundering, legal compliance
  - purpose: Order fulfillment, payouts, refunds
    text: Order fulfillment, payouts for cards sold to us, refunds, fraud prevention, accounting and tax records
  residency:
  - region: United States
    text: Our servers and databases are located in the United States, and many of our service providers process data there.
  retention:
  - period: null
    scope: Account information
    text: We keep account information while your account is open.
  - period: null
    scope: Records of orders, card sales, payouts, refunds, and identity verification
    text: We keep records of orders, card sales, payouts, refunds, and identity verification for as long as we need them for accounting, tax, warranty, fraud-prevention, and legal purposes, even after you close your account.
  - period: about five weeks
    scope: Public deal API and MCP server records
    text: These records are stored with Axiom for about five weeks
  rights:
  - right: Right to access, inspect, and receive a copy of your personal data
    text: Right to access, inspect, and receive a copy of your personal data
  - right: Right to correct inaccurate or incomplete information
    text: Right to correct inaccurate or incomplete information
  - right: Right to request deletion of your personal data
    text: Right to request deletion of your personal data
  - right: Right to object to or restrict certain processing activities
    text: Right to object to or restrict certain processing activities
  - right: Right to data portability
    text: Right to data portability in a structured, machine-readable format
  role:
    text: CardDeals LLC ("CardDeals", "we", "our", or "us") operates carddeals.co
    value: controller
  sale_or_sharing:
    stance: conditional
    text: CardDeals does not sell personal information for money. Google Analytics' advertising features may use information collected on our site for cross-context behavioral advertising, which the CPRA treats as "sharing," and you have the right to opt out of it.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Where required by law, we ensure appropriate safeguards are in place (such as Standard Contractual Clauses approved by the European Commission) to protect your data during international transfer.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CardDeals
provenance_date: '2026-11-09'
provider_name: CardDeals
provider_slug: carddeals-co
slug: carddeals-co-privacy-policy
source_date: '2026-11-09'
source_filename: carddeals-co-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://carddeals.co/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CardDeals\naid: carddeals-co\nurl: https://carddeals.co/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: CardDeals LLC (\"CardDeals\", \"we\", \"our\", or \"us\") operates carddeals.co\ndata_categories:\n- category: identifying\n  text: Name, email address, account ID, IP address, browser user agent, cookie identifiers, and random IDs stored\n    in your browser or the extension\n- category: financial\n  text: Gift cards you bought from us or sold to us, amounts, order and payout status, Stripe payment and payout-account\n    references, and the encrypted number and PIN of each card\
  \ you sold us.\n- category: biometric\n  text: The result of the identity check run by Didit, including details read from your ID document (such as your\n    name and document number) and the outcome of selfie, liveness, face-match, and screening checks\n- category: behavioral\n  text: Pages viewed, referring page, campaign (UTM) parameters, search terms, offer and banner clicks, and session\n    replays of the sign-in, sign-up, brand, and /sell pages with form inputs masked\n- category: communication\n  text: Messages you send to support or through our contact form, and ratings or comments you submit as browser\n    extension feedback\n- category: location\n  text: Country (and, in Google Analytics, region or city) derived from your IP address\n- category: device\n  text: Browser and operating system details, website error events, and browser extension version\npurposes:\n- purpose: Authentication, account management, security, fraud prevention, analytics\n  text: Authentication, account\
  \ management, security, fraud prevention, analytics\n- purpose: Verifying buyers and sellers, preventing fraud, chargebacks, and money laundering\n  text: Verifying buyers and sellers, preventing fraud, chargebacks, and money laundering, legal compliance\n- purpose: Order fulfillment, payouts, refunds\n  text: Order fulfillment, payouts for cards sold to us, refunds, fraud prevention, accounting and tax records\nretention:\n- scope: Account information\n  period: null\n  text: We keep account information while your account is open.\n- scope: Records of orders, card sales, payouts, refunds, and identity verification\n  period: null\n  text: We keep records of orders, card sales, payouts, refunds, and identity verification for as long as we need\n    them for accounting, tax, warranty, fraud-prevention, and legal purposes, even after you close your account.\n- scope: Public deal API and MCP server records\n  period: about five weeks\n  text: These records are stored with Axiom for about\
  \ five weeks\nresidency:\n- region: United States\n  text: Our servers and databases are located in the United States, and many of our service providers process data\n    there.\ntransfers:\n- mechanism: SCC\n  text: Where required by law, we ensure appropriate safeguards are in place (such as Standard Contractual Clauses\n    approved by the European Commission) to protect your data during international transfer.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email us\n  text: To delete your account, email us; we complete verified deletion requests within thirty (30) days, except\n    for records we are required or permitted by law to keep.\nrights:\n- right: Right to access, inspect, and receive a copy of your personal data\n  text: Right to access, inspect, and receive a copy of your personal data\n- right: Right to correct inaccurate or incomplete information\n  text: Right to correct inaccurate or incomplete information\n\
  - right: Right to request deletion of your personal data\n  text: Right to request deletion of your personal data\n- right: Right to object to or restrict certain processing activities\n  text: Right to object to or restrict certain processing activities\n- right: Right to data portability\n  text: Right to data portability in a structured, machine-readable format\nsale_or_sharing:\n  stance: conditional\n  text: CardDeals does not sell personal information for money. Google Analytics' advertising features may use information\n    collected on our site for cross-context behavioral advertising, which the CPRA treats as \"sharing,\" and you\n    have the right to opt out of it.\n"
source_yaml_url: https://artifacts.apis.io/carddeals-co/privacy/carddeals-co-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from CardDeals's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gift Cards
- Comparison
- Discounts
- E-Commerce
- Real-Time
---
