---
api_specs:
- filename: phone-inc-openapi-generated.yml
  format: yaml
  label: Phone Inc API
  slug: phone-inc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/phone-inc/openapi/_ae-authored/phone-inc-openapi-generated.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account and profile data – name, email address, password (stored hashed), company name, job role, and account settings.
  - category: financial
    text: Business and billing data – business address, tax or VAT identifiers, billing details, subscription status, invoices, and payment information processed by our payment provider (we do not store full card numbers).
  - category: identifying
    text: Identity and verification data – information you provide for Know Your Customer (KYC) checks, proof of address, or fraud prevention, when we request it.
  - category: device
    text: Usage and device data – logins, IP address, browser or app version, device identifiers, push notification tokens, signaling data, and how you interact with our website, dashboard, and mobile apps.
  - category: communication
    text: Communications metadata – call and message timestamps, durations, phone numbers, routing information, voicemail metadata, and similar telephony records needed to provide and bill for the service.
  - category: communication
    text: Communications content – voicemails, greetings you configure, message content where messaging features are available, and – where enabled – call recordings and transcriptions .
  - category: behavioral
    text: Website and marketing data – sign-ups, cookie preferences where applicable, and analytics data from our website.
  deletion:
    route: Email compliance@phone.inc to request deletion of personal data for which Phone.inc is the controller; requests about customer data are forwarded to the business.
    text: You can ask us to delete personal data for which Phone.inc is the data controller. Email compliance@phone.inc .
  dpa:
    available: true
    text: Data Processing Agreement
    url: null
  purposes:
  - purpose: Provide and operate the service
    text: Provide, operate, maintain, and improve Phone.inc
  - purpose: Billing and payments
    text: Process payments, manage subscriptions, and handle billing disputes
  - purpose: Fraud and abuse prevention
    text: Verify identity, prevent fraud – including payment and account fraud detection through our service providers – and enforce our Terms of Service
  - purpose: Legal compliance
    text: Comply with legal obligations and respond to lawful requests from authorities
  - purpose: Analytics and product development
    text: We may use aggregated or de-identified data that no longer identifies you for analytics, product development, and reporting.
  residency:
  - region: Denmark
    text: Phone.inc is based in Denmark.
  - region: EEA, United States and other countries
    text: We and our service providers may process personal data in Denmark, elsewhere in the European Economic Area, the United States, and other countries where we or our providers operate.
  retention:
  - period: null
    scope: Account data
    text: Account data is kept while your account is active and for a reasonable period afterward.
  - period: null
    scope: Billing and tax records
    text: Billing and tax records are kept for the period required by applicable law.
  - period: null
    scope: Call records and messaging activity
    text: Call records, messaging activity, and compliance investigation logs may be kept longer where needed to meet regulatory obligations, respond to traceback requests, prevent or investigate fraud, or establish, exercise, or defend legal claims.
  rights:
  - right: Access
    text: Access the personal data we hold about you
  - right: Correction
    text: Correct inaccurate data
  - right: Restriction or objection
    text: Restrict or object to certain processing, including processing based on legitimate interests
  - right: Portability
    text: Receive a copy of your data in a portable format where technically feasible
  - right: Withdraw consent
    text: Withdraw consent where processing is based on consent
  - right: Complaint
    text: Lodge a complaint with your local data protection authority
  role:
    text: Phone Incorporated ApS, CVR DK-46213564, Højbro Plads 10, 1200 Copenhagen K, Denmark, is the data controller for the personal data described in this policy.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data.
  subprocessors:
    text: Our Data Processing Agreement separately lists the sub-processors that process customer-controlled personal data on our behalf.
    url: null
  transfers:
  - mechanism: SCC
    text: Where required, we use appropriate safeguards for international transfers, such as the EU Standard Contractual Clauses or equivalent mechanisms approved under applicable law.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Phone Inc
provenance_date: '2026-11-10'
provider_name: Phone Inc
provider_slug: phone-inc
slug: phone-inc-privacy-policy
source_date: '2026-11-10'
source_filename: phone-inc-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.phone.inc/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Phone Inc\naid: phone-inc\nurl: https://www.phone.inc/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Phone Incorporated ApS, CVR DK-46213564, Højbro Plads 10, 1200 Copenhagen K, Denmark, is the data controller\n    for the personal data described in this policy.\ndata_categories:\n- category: identifying\n  text: Account and profile data – name, email address, password (stored hashed), company name, job role, and account\n    settings.\n- category: financial\n  text: Business and billing data – business address, tax or VAT identifiers, billing details, subscription status,\n    invoices,\
  \ and payment information processed by our payment provider (we do not store full card numbers).\n- category: identifying\n  text: Identity and verification data – information you provide for Know Your Customer (KYC) checks, proof of address,\n    or fraud prevention, when we request it.\n- category: device\n  text: Usage and device data – logins, IP address, browser or app version, device identifiers, push notification\n    tokens, signaling data, and how you interact with our website, dashboard, and mobile apps.\n- category: communication\n  text: Communications metadata – call and message timestamps, durations, phone numbers, routing information, voicemail\n    metadata, and similar telephony records needed to provide and bill for the service.\n- category: communication\n  text: Communications content – voicemails, greetings you configure, message content where messaging features are\n    available, and – where enabled – call recordings and transcriptions .\n- category: behavioral\n\
  \  text: Website and marketing data – sign-ups, cookie preferences where applicable, and analytics data from our\n    website.\npurposes:\n- purpose: Provide and operate the service\n  text: Provide, operate, maintain, and improve Phone.inc\n- purpose: Billing and payments\n  text: Process payments, manage subscriptions, and handle billing disputes\n- purpose: Fraud and abuse prevention\n  text: Verify identity, prevent fraud – including payment and account fraud detection through our service providers\n    – and enforce our Terms of Service\n- purpose: Legal compliance\n  text: Comply with legal obligations and respond to lawful requests from authorities\n- purpose: Analytics and product development\n  text: We may use aggregated or de-identified data that no longer identifies you for analytics, product development,\n    and reporting.\nretention:\n- scope: Account data\n  period: null\n  text: Account data is kept while your account is active and for a reasonable period afterward.\n\
  - scope: Billing and tax records\n  period: null\n  text: Billing and tax records are kept for the period required by applicable law.\n- scope: Call records and messaging activity\n  period: null\n  text: Call records, messaging activity, and compliance investigation logs may be kept longer where needed to meet\n    regulatory obligations, respond to traceback requests, prevent or investigate fraud, or establish, exercise,\n    or defend legal claims.\nresidency:\n- region: Denmark\n  text: Phone.inc is based in Denmark.\n- region: EEA, United States and other countries\n  text: We and our service providers may process personal data in Denmark, elsewhere in the European Economic Area,\n    the United States, and other countries where we or our providers operate.\ntransfers:\n- mechanism: SCC\n  text: Where required, we use appropriate safeguards for international transfers, such as the EU Standard Contractual\n    Clauses or equivalent mechanisms approved under applicable law.\nsubprocessors:\n\
  \  url: null\n  text: Our Data Processing Agreement separately lists the sub-processors that process customer-controlled personal\n    data on our behalf.\ndpa:\n  available: true\n  url: null\n  text: Data Processing Agreement\ndeletion:\n  route: Email compliance@phone.inc to request deletion of personal data for which Phone.inc is the controller;\n    requests about customer data are forwarded to the business.\n  text: You can ask us to delete personal data for which Phone.inc is the data controller. Email compliance@phone.inc\n    .\nrights:\n- right: Access\n  text: Access the personal data we hold about you\n- right: Correction\n  text: Correct inaccurate data\n- right: Restriction or objection\n  text: Restrict or object to certain processing, including processing based on legitimate interests\n- right: Portability\n  text: Receive a copy of your data in a portable format where technically feasible\n- right: Withdraw consent\n  text: Withdraw consent where processing is based on\
  \ consent\n- right: Complaint\n  text: Lodge a complaint with your local data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/phone-inc/privacy/phone-inc-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from Phone Inc's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Communications
- Cloud
- Business
---
