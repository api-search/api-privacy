---
api_specs:
- filename: affitor-com-tracking-api-openapi.yml
  format: yaml
  label: Affitor Tracking API
  slug: affitor-com-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/affitor-com/openapi/affitor-com-tracking-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: when you create an account on Affitor, we collect account information such as your name, email address, and company name
  - category: financial
    text: To pay Partners, we store the payout details they give us, such as the account holder's name and bank or Wise account details.
  - category: location
    text: an approximate location (country, region, and city) that we look up from the visitor's IP address
  - category: behavioral
    text: we collect usage data, such as pages viewed, clicks, and device and browser type
  - category: device
    text: device type, operating system, browser details, screen size, language, time zone
  - category: contact
    text: we create a one-way hash (SHA-256) of it
  deletion:
    route: email hello@affitor.com or account settings
    text: Ask us to delete your personal data or close your account. We will, except for the records described in Section 5.2 that we keep for the other side or by law.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: attribution
    text: 'We use data to run the Service: to attribute referrals and to calculate and pay commissions.'
  - purpose: fraud prevention
    text: We analyze aggregated patterns and device signals to detect and prevent fraudulent activity.
  - purpose: payouts
    text: We use Partner account and payment information to process commission payments.
  - purpose: history and reports
    text: We keep your history and show it in your dashboard, so you can reconcile payments
  residency:
  - region: United States
    text: Affitor is based in the United States, and our database and backups are stored there.
  retention:
  - period: null
    scope: account and history
    text: While your account is open, we keep all of it except test data (see 5.2), with no time limit
  - period: 90 days
    scope: closed account data
    text: we keep your account data for up to 90 days, so we can restore the account if you change your mind
  - period: 30 days
    scope: test data
    text: 'Test data : test clicks, sign-ups, sales and commissions, and the test customer records behind them, are deleted after they are 30 days old.'
  - period: null
    scope: backups
    text: Data that was changed or deleted later can remain in older backups until those backups are removed.
  rights:
  - right: access
    text: you have the right to access the personal data we hold about you and to correct it
  - right: correction
    text: correct inaccurate personal information
  - right: deletion
    text: request deletion of your personal information (subject to legal exceptions)
  - right: copy / portability
    text: You can ask for a copy in a structured, commonly used format
  - right: objection
    text: you can object to or restrict certain types of processing
  role:
    text: Affitor acts as a Data Processor when processing end-customer data on behalf of Advertisers, and as a Data Controller for direct user accounts (Advertiser and Partner accounts).
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your data.
  subprocessors:
    text: Our Subprocessors page (affitor.com/legal/subprocessors) lists each one, what it does for us, the personal data it receives, and where it is located.
    url: affitor.com/legal/subprocessors
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Affitor
provenance_date: '2026-11-09'
provider_name: Affitor
provider_slug: affitor-com
slug: affitor-com-privacy-policy
source_date: '2026-11-09'
source_filename: affitor-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://affitor.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Affitor\naid: affitor-com\nurl: https://affitor.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Affitor acts as a Data Processor when processing end-customer data on behalf of Advertisers, and as a Data\n    Controller for direct user accounts (Advertiser and Partner accounts).\ndata_categories:\n- category: identifying\n  text: when you create an account on Affitor, we collect account information such as your name, email address,\n    and company name\n- category: financial\n  text: To pay Partners, we store the payout details they give us, such as the account holder's name and bank\
  \ or\n    Wise account details.\n- category: location\n  text: an approximate location (country, region, and city) that we look up from the visitor's IP address\n- category: behavioral\n  text: we collect usage data, such as pages viewed, clicks, and device and browser type\n- category: device\n  text: device type, operating system, browser details, screen size, language, time zone\n- category: contact\n  text: we create a one-way hash (SHA-256) of it\npurposes:\n- purpose: attribution\n  text: 'We use data to run the Service: to attribute referrals and to calculate and pay commissions.'\n- purpose: fraud prevention\n  text: We analyze aggregated patterns and device signals to detect and prevent fraudulent activity.\n- purpose: payouts\n  text: We use Partner account and payment information to process commission payments.\n- purpose: history and reports\n  text: We keep your history and show it in your dashboard, so you can reconcile payments\nretention:\n- scope: account and history\n\
  \  period: null\n  text: While your account is open, we keep all of it except test data (see 5.2), with no time limit\n- scope: closed account data\n  period: 90 days\n  text: we keep your account data for up to 90 days, so we can restore the account if you change your mind\n- scope: test data\n  period: 30 days\n  text: 'Test data : test clicks, sign-ups, sales and commissions, and the test customer records behind them, are\n    deleted after they are 30 days old.'\n- scope: backups\n  period: null\n  text: Data that was changed or deleted later can remain in older backups until those backups are removed.\nresidency:\n- region: United States\n  text: Affitor is based in the United States, and our database and backups are stored there.\ntransfers: []\nsubprocessors:\n  url: affitor.com/legal/subprocessors\n  text: Our Subprocessors page (affitor.com/legal/subprocessors) lists each one, what it does for us, the personal\n    data it receives, and where it is located.\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: email hello@affitor.com or account settings\n  text: Ask us to delete your personal data or close your account. We will, except for the records described in\n    Section 5.2 that we keep for the other side or by law.\nrights:\n- right: access\n  text: you have the right to access the personal data we hold about you and to correct it\n- right: correction\n  text: correct inaccurate personal information\n- right: deletion\n  text: request deletion of your personal information (subject to legal exceptions)\n- right: copy / portability\n  text: You can ask for a copy in a structured, commonly used format\n- right: objection\n  text: you can object to or restrict certain types of processing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your data.\n"
source_yaml_url: https://artifacts.apis.io/affitor-com/privacy/affitor-com-privacy-policy.yml
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
summary_line: 24 quoted statements, read from Affitor's own page on 2026-11-09.
synthetic: false
tags:
- Affiliates
- Software-as-a-Service
- Artificial Intelligence
- Marketing
- Affiliate Network
---
