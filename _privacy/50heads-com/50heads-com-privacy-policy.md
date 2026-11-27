---
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: email, name, sign-in provider'
  - category: contact
    text: Phone number One person, one account; sign-in checks
  - category: financial
    text: Payments, payouts, invoices To take and make payments
  - category: biometric
    text: Photo of your ID document and a live selfie (Tier 2), handled by Stripe, never by 50heads
  - category: device
    text: Device integrity-check results, touch and timing signals, device identifiers
  - category: demographic
    text: Age band (Tier 2), worked out from the date of birth
  - category: professional
    text: Tax details (name, address, date of birth, tax number; US Form W-9; Canadian SIN)
  deletion:
    route: Delete account in the app, or contact form; withdraw consent in Privacy, data and appeals
    text: when you delete your account, or withdraw consent in the app ( You , then Privacy, data and appeals ), we ask Stripe to delete the data from your checks and you move to Tier 1.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Run account and provide service
    text: To run your account
  - purpose: Fraud prevention
    text: To detect bots, emulators and account farms
  - purpose: Identity verification
    text: To check the ID is genuine and that it is you, and to stop one person holding several accounts
  - purpose: Tax and sanctions compliance
    text: Platform reporting to HMRC, and to the IRS for US heads (Form 1099-NEC)
  - purpose: AI processing for users
    text: We use AI on your data only to do things for you.
  - purpose: Marketing email
    text: News about 50heads Consent, or soft opt-in for customers
  residency:
  - region: Ireland and United States (Stripe)
    text: Stripe processes and stores the check in Ireland and the United States.
  - region: EU and United States (hosting)
    text: The result we keep is stored with our hosting provider in the EU and the US.
  retention:
  - period: null
    scope: Biometric identifiers held by Stripe
    text: Stripe keeps the biometric identifiers made from your selfie and ID photo for no longer than one year, only to detect fraud
  - period: 12 months after
    scope: Phone number
    text: Phone number While your account exists; a scrambled copy 12 months after
  - period: 6 years after the tax year
    scope: Payments, invoices, tax identifiers
    text: Payments, invoices, statements, tax identifiers 6 years after the tax year, in the live file and in the backup copy
  - period: 2 years
    scope: Support messages
    text: Support messages 2 years
  - period: 12 months
    scope: Email logs
    text: Email logs 12 months
  - period: 90 days
    scope: Raw touch and timing signals
    text: Raw touch and timing signals 90 days; derived patterns 24 months
  rights:
  - right: access
    text: You can ask to access, correct, delete, restrict or move your data
  - right: object
    text: object to processing based on legitimate interests
  - right: withdraw consent
    text: and withdraw consent.
  role:
    text: 50heads Limited (company number 17486968), registered office 66 Paul Street, London, EC2A 4NA, United Kingdom, is the controller of your personal data.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don't sell data, track you across other apps or sites, or collect your location or contacts.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: We use the UK Extension to the EU–US Data Privacy Framework where the provider is certified
  - mechanism: other
    text: the UK International Data Transfer Agreement or EU Standard Contractual Clauses, with a transfer risk assessment.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 50heads
provenance_date: '2026-11-09'
provider_name: 50heads
provider_slug: 50heads-com
slug: 50heads-com-privacy-policy
source_date: '2026-11-09'
source_filename: 50heads-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://50heads.com/en-us/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 50heads\naid: 50heads-com\nurl: https://50heads.com/en-us/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 50heads Limited (company number 17486968), registered office 66 Paul Street, London, EC2A 4NA, United Kingdom,\n    is the controller of your personal data.\ndata_categories:\n- category: identifying\n  text: 'Account: email, name, sign-in provider'\n- category: contact\n  text: Phone number One person, one account; sign-in checks\n- category: financial\n  text: Payments, payouts, invoices To take and make payments\n- category: biometric\n  text: Photo of your ID document\
  \ and a live selfie (Tier 2), handled by Stripe, never by 50heads\n- category: device\n  text: Device integrity-check results, touch and timing signals, device identifiers\n- category: demographic\n  text: Age band (Tier 2), worked out from the date of birth\n- category: professional\n  text: Tax details (name, address, date of birth, tax number; US Form W-9; Canadian SIN)\npurposes:\n- purpose: Run account and provide service\n  text: To run your account\n- purpose: Fraud prevention\n  text: To detect bots, emulators and account farms\n- purpose: Identity verification\n  text: To check the ID is genuine and that it is you, and to stop one person holding several accounts\n- purpose: Tax and sanctions compliance\n  text: Platform reporting to HMRC, and to the IRS for US heads (Form 1099-NEC)\n- purpose: AI processing for users\n  text: We use AI on your data only to do things for you.\n- purpose: Marketing email\n  text: News about 50heads Consent, or soft opt-in for customers\nretention:\n\
  - scope: Biometric identifiers held by Stripe\n  period: null\n  text: Stripe keeps the biometric identifiers made from your selfie and ID photo for no longer than one year, only\n    to detect fraud\n- scope: Phone number\n  period: 12 months after\n  text: Phone number While your account exists; a scrambled copy 12 months after\n- scope: Payments, invoices, tax identifiers\n  period: 6 years after the tax year\n  text: Payments, invoices, statements, tax identifiers 6 years after the tax year, in the live file and in the\n    backup copy\n- scope: Support messages\n  period: 2 years\n  text: Support messages 2 years\n- scope: Email logs\n  period: 12 months\n  text: Email logs 12 months\n- scope: Raw touch and timing signals\n  period: 90 days\n  text: Raw touch and timing signals 90 days; derived patterns 24 months\nresidency:\n- region: Ireland and United States (Stripe)\n  text: Stripe processes and stores the check in Ireland and the United States.\n- region: EU and United States\
  \ (hosting)\n  text: The result we keep is stored with our hosting provider in the EU and the US.\ntransfers:\n- mechanism: DPF\n  text: We use the UK Extension to the EU–US Data Privacy Framework where the provider is certified\n- mechanism: other\n  text: the UK International Data Transfer Agreement or EU Standard Contractual Clauses, with a transfer risk assessment.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account in the app, or contact form; withdraw consent in Privacy, data and appeals\n  text: when you delete your account, or withdraw consent in the app ( You , then Privacy, data and appeals ), we\n    ask Stripe to delete the data from your checks and you move to Tier 1.\nrights:\n- right: access\n  text: You can ask to access, correct, delete, restrict or move your data\n- right: object\n  text: object to processing based on legitimate interests\n- right: withdraw consent\n  text: and withdraw consent.\n\
  sale_or_sharing:\n  stance: prohibited\n  text: We don't sell data, track you across other apps or sites, or collect your location or contacts.\n"
source_yaml_url: https://artifacts.apis.io/50heads-com/privacy/50heads-com-privacy-policy.yml
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
summary_line: 29 quoted statements, read from 50heads's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Verification
- Surveys
- Platform
---
