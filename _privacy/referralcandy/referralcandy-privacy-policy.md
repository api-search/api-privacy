---
api_specs:
- filename: referralcandy-openapi-generated.yml
  format: yaml
  label: ReferralCandy API
  slug: referralcandy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/referralcandy/openapi/_ae-authored/referralcandy-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account and contact details: your name, email address, phone number, company and store details.'
  - category: financial
    text: 'Billing details: your plan and payment history. Stripe processes card payments for us. We don’t store card numbers.'
  - category: location
    text: 'Log data: IP address, browser and device details, operating system, time zone, approximate location and login details.'
  - category: behavioral
    text: 'Usage data: clicks, pages visited, actions taken and errors seen on our website, in the dashboard and in referral widgets.'
  - category: communication
    text: 'Support messages: what you send us by live chat, email or phone.'
  deletion:
    route: Merchants delete shopper data in the ReferralCandy dashboard; or email compliance@referralcandy.com
    text: Merchants can delete shopper data at any time.
  dpa:
    available: true
    text: A Data Processing Addendum (DPA) for every merchant.
    url: https://www.referralcandy.com/privacy/
  purposes:
  - purpose: Run the referral program
    text: Logging merchants in, saving settings, tracking referrals and orders, sending referral emails, issuing rewards and coupon codes, processing payments, and hosting referral pages.
  - purpose: Prevent fraud and security
    text: Detecting fake or self-referrals, protecting accounts, monitoring systems and investigating incidents.
  - purpose: Improve ReferralCandy
    text: Understanding how ReferralCandy is used, testing features, collecting feedback and analysing data.
  - purpose: Marketing to merchants
    text: Emails about product updates, new features and content. You can unsubscribe at any time.
  residency:
  - region: Singapore
    text: We store data mainly in Singapore, on Amazon Web Services (AWS region ap-southeast-1).
  - region: United States
    text: Some processing happens in the United States, including email delivery, content delivery, logging, monitoring and support.
  retention:
  - period: up to 30 days
    scope: Backups
    text: copies of deleted data may stay in our backups for up to 30 days, until those backups are deleted.
  - period: null
    scope: Merchant account and shopper data while using service
    text: 'While a merchant uses ReferralCandy: we keep the merchant’s account data and the shopper data in its program.'
  rights:
  - right: Access
    text: 'Access: get a copy of the personal data we hold about you.'
  - right: Correction
    text: 'Correction: fix data that is wrong.'
  - right: Deletion
    text: 'Deletion: ask us to delete your data when we no longer need it.'
  - right: Portability
    text: 'Portability: get your data in a machine-readable format (CSV) to take to another service.'
  - right: Restriction and objection
    text: 'Restriction and objection: ask us to limit or stop some processing, including profiling and direct marketing.'
  - right: Withdraw consent
    text: 'Withdraw consent: where we rely on your consent, you can withdraw it at any time.'
  role:
    text: Under the GDPR we are the controller . This policy explains how we use it.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data. We do not share personal data for cross-context behavioural advertising.
  subprocessors:
    text: Subprocessors and service providers
    url: https://www.referralcandy.com/privacy/
  transfers:
  - mechanism: SCC
    text: the EU Standard Contractual Clauses (2021), the UK International Data Transfer Addendum and Swiss-specific adjustments, all included in our DPA
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: ReferralCandy
provenance_date: '2026-11-10'
provider_name: ReferralCandy
provider_slug: referralcandy
slug: referralcandy-privacy-policy
source_date: '2026-11-10'
source_filename: referralcandy-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.referralcandy.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ReferralCandy\naid: referralcandy\nurl: https://www.referralcandy.com/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Under the GDPR we are the controller . This policy explains how we use it.\ndata_categories:\n- category: contact\n  text: 'Account and contact details: your name, email address, phone number, company and store details.'\n- category: financial\n  text: 'Billing details: your plan and payment history. Stripe processes card payments for us. We don’t store card\n    numbers.'\n- category: location\n  text: 'Log data: IP address, browser and device details, operating system,\
  \ time zone, approximate location and\n    login details.'\n- category: behavioral\n  text: 'Usage data: clicks, pages visited, actions taken and errors seen on our website, in the dashboard and in\n    referral widgets.'\n- category: communication\n  text: 'Support messages: what you send us by live chat, email or phone.'\npurposes:\n- purpose: Run the referral program\n  text: Logging merchants in, saving settings, tracking referrals and orders, sending referral emails, issuing rewards\n    and coupon codes, processing payments, and hosting referral pages.\n- purpose: Prevent fraud and security\n  text: Detecting fake or self-referrals, protecting accounts, monitoring systems and investigating incidents.\n- purpose: Improve ReferralCandy\n  text: Understanding how ReferralCandy is used, testing features, collecting feedback and analysing data.\n- purpose: Marketing to merchants\n  text: Emails about product updates, new features and content. You can unsubscribe at any time.\nretention:\n\
  - scope: Backups\n  period: up to 30 days\n  text: copies of deleted data may stay in our backups for up to 30 days, until those backups are deleted.\n- scope: Merchant account and shopper data while using service\n  period: null\n  text: 'While a merchant uses ReferralCandy: we keep the merchant’s account data and the shopper data in its program.'\nresidency:\n- region: Singapore\n  text: We store data mainly in Singapore, on Amazon Web Services (AWS region ap-southeast-1).\n- region: United States\n  text: Some processing happens in the United States, including email delivery, content delivery, logging, monitoring\n    and support.\ntransfers:\n- mechanism: SCC\n  text: the EU Standard Contractual Clauses (2021), the UK International Data Transfer Addendum and Swiss-specific\n    adjustments, all included in our DPA\nsubprocessors:\n  url: https://www.referralcandy.com/privacy/\n  text: Subprocessors and service providers\ndpa:\n  available: true\n  url: https://www.referralcandy.com/privacy/\n\
  \  text: A Data Processing Addendum (DPA) for every merchant.\ndeletion:\n  route: Merchants delete shopper data in the ReferralCandy dashboard; or email compliance@referralcandy.com\n  text: Merchants can delete shopper data at any time.\nrights:\n- right: Access\n  text: 'Access: get a copy of the personal data we hold about you.'\n- right: Correction\n  text: 'Correction: fix data that is wrong.'\n- right: Deletion\n  text: 'Deletion: ask us to delete your data when we no longer need it.'\n- right: Portability\n  text: 'Portability: get your data in a machine-readable format (CSV) to take to another service.'\n- right: Restriction and objection\n  text: 'Restriction and objection: ask us to limit or stop some processing, including profiling and direct marketing.'\n- right: Withdraw consent\n  text: 'Withdraw consent: where we rely on your consent, you can withdraw it at any time.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data. We do not share personal\
  \ data for cross-context behavioural advertising.\n"
source_yaml_url: https://artifacts.apis.io/referralcandy/privacy/referralcandy-privacy-policy.yml
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
summary_line: 25 quoted statements, read from ReferralCandy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Referrals
- Affiliates
- E-Commerce
- Marketing
---
