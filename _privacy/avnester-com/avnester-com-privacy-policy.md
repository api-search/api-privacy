---
api_specs:
- filename: avnester-com-public-api-openapi.yml
  format: yaml
  label: AVnester Public API
  slug: avnester-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avnester-com/openapi/avnester-com-public-api-openapi.yml
claim_count: 35
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account: name, email, phone, role (buyer / seller / agent / builder / developer), city, property preferences.'
  - category: financial
    text: 'Payments: name, billing address, GSTIN if you provide one, and a payment token.'
  - category: location
    text: 'Location: approximate city-level location, only with your explicit consent.'
  - category: device
    text: 'Usage telemetry: pages viewed, searches, device, browser, IP, referrer.'
  - category: behavioral
    text: 'Session diagnostics: a small percentage of sessions are recorded (clicks, scrolls, masked inputs) by Sentry and PostHog for crash diagnosis and UX research.'
  - category: communication
    text: 'Voice call recording: when you place a voice call with Ava, we record the call — your spoken audio together with Ava''s spoken replies'
  deletion:
    route: Settings → Delete account, or request deletion without signing in at /delete-account
    text: 'To delete your account and personal data: if you are signed in, use Settings → Delete account for instant removal; otherwise request deletion without signing in at /delete-account.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate the Platform
    text: 'To operate the Platform: account management, listing publication, inquiry routing, search, recommendations, customer support.'
  - purpose: Safety and security
    text: 'To keep the Platform safe: fraud prevention, abuse detection, security investigation, enforcement of our terms.'
  - purpose: Legal obligations
    text: 'To meet legal obligations: GST invoicing, RERA-related disclosures, court or regulator orders, IT Act intermediary duties.'
  - purpose: Product improvement
    text: 'To improve the Platform: product analytics, error monitoring, A/B tests on UX changes.'
  - purpose: Advertising measurement and remarketing
    text: 'To advertise AVnester: to measure which of our ads lead to sign-ups, listings and enquiries, and to show our ads to people who have visited AVnester before (remarketing), using Google Ads'
  residency:
  - region: India (AWS Mumbai)
    text: Operational data is stored in AWS Mumbai (ap-south-1); some sub-processors process data abroad under contractual safeguards.
  - region: United States
    text: Text AI inference (the Anthropic API, US, and Amazon Bedrock, us-east-1)
  retention:
  - period: 30 days
    scope: Account
    text: retained while the account is active and 30 days after a deletion request.
  - period: 3 years
    scope: Inquiries
    text: 'Inquiries: 3 years (limitation period under the Indian Contract Act, 1872).'
  - period: 90 days
    scope: Usage telemetry
    text: 90 days for product analytics; aggregated thereafter.
  - period: 30 days
    scope: Session diagnostics
    text: 'Session diagnostics: a small percentage of sessions are recorded (clicks, scrolls, masked inputs) by Sentry and PostHog for crash diagnosis and UX research. Form fields, passwords, OTPs, and free-text PII are masked at capture. 30 days.'
  - period: 90 days
    scope: Voice call recordings
    text: retain it for up to 90 days, after which it is automatically deleted.
  - period: 8 years
    scope: Invoices
    text: 'Invoices: 8 years (GST Act).'
  - period: 7 years
    scope: Audit logs
    text: 'Audit logs: access logs, security events, admin actions. 7 years.'
  - period: 180 days
    scope: Removed or flagged content
    text: 'Removed or flagged content: 180 days after removal (IT (Intermediary Guidelines) Rules, 2021).'
  - period: 14 months
    scope: Google Analytics data
    text: Google Analytics keeps this data for up to 14 months
  - period: 180 days
    scope: Google Ads remarketing lists
    text: our Google Ads remarketing lists keep a visitor for up to 180 days after their last visit.
  rights:
  - right: Access and summary
    text: ask for a summary of the personal data we hold about you and how it has been processed
  - right: Correction
    text: ask us to correct or update inaccurate data
  - right: Erasure
    text: ask us to erase data we no longer need, subject to retention required by law
  - right: Nominate a representative
    text: nominate a person to exercise these rights on your behalf if you die or become incapacitated
  - right: Withdraw consent
    text: withdraw consent
  - right: Grievance
    text: file a grievance
  - right: Portability and objection
    text: Where the GDPR applies, you also have data portability and the right to object to processing based on legitimate interests.
  role:
    text: We are the Data Fiduciary (DPDPA 2023) / Controller (GDPR) for the personal data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal data or share it with data brokers.
  subprocessors:
    text: 'Sub-processors: see the next section.'
    url: null
  transfers:
  - mechanism: SCC
    text: Such transfers are made under contractual safeguards (Standard Contractual Clauses or equivalent)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AVnester
provenance_date: '2026-11-09'
provider_name: AVnester
provider_slug: avnester-com
slug: avnester-com-privacy-policy
source_date: '2026-11-09'
source_filename: avnester-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://avnester.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AVnester\naid: avnester-com\nurl: https://avnester.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are the Data Fiduciary (DPDPA 2023) / Controller (GDPR) for the personal data described here.\ndata_categories:\n- category: identifying\n  text: 'Account: name, email, phone, role (buyer / seller / agent / builder / developer), city, property preferences.'\n- category: financial\n  text: 'Payments: name, billing address, GSTIN if you provide one, and a payment token.'\n- category: location\n  text: 'Location: approximate city-level location, only with your explicit consent.'\n\
  - category: device\n  text: 'Usage telemetry: pages viewed, searches, device, browser, IP, referrer.'\n- category: behavioral\n  text: 'Session diagnostics: a small percentage of sessions are recorded (clicks, scrolls, masked inputs) by Sentry\n    and PostHog for crash diagnosis and UX research.'\n- category: communication\n  text: 'Voice call recording: when you place a voice call with Ava, we record the call — your spoken audio together\n    with Ava''s spoken replies'\npurposes:\n- purpose: Operate the Platform\n  text: 'To operate the Platform: account management, listing publication, inquiry routing, search, recommendations,\n    customer support.'\n- purpose: Safety and security\n  text: 'To keep the Platform safe: fraud prevention, abuse detection, security investigation, enforcement of our\n    terms.'\n- purpose: Legal obligations\n  text: 'To meet legal obligations: GST invoicing, RERA-related disclosures, court or regulator orders, IT Act intermediary\n    duties.'\n- purpose:\
  \ Product improvement\n  text: 'To improve the Platform: product analytics, error monitoring, A/B tests on UX changes.'\n- purpose: Advertising measurement and remarketing\n  text: 'To advertise AVnester: to measure which of our ads lead to sign-ups, listings and enquiries, and to show\n    our ads to people who have visited AVnester before (remarketing), using Google Ads'\nretention:\n- scope: Account\n  period: 30 days\n  text: retained while the account is active and 30 days after a deletion request.\n- scope: Inquiries\n  period: 3 years\n  text: 'Inquiries: 3 years (limitation period under the Indian Contract Act, 1872).'\n- scope: Usage telemetry\n  period: 90 days\n  text: 90 days for product analytics; aggregated thereafter.\n- scope: Session diagnostics\n  period: 30 days\n  text: 'Session diagnostics: a small percentage of sessions are recorded (clicks, scrolls, masked inputs) by Sentry\n    and PostHog for crash diagnosis and UX research. Form fields, passwords, OTPs, and free-text\
  \ PII are masked\n    at capture. 30 days.'\n- scope: Voice call recordings\n  period: 90 days\n  text: retain it for up to 90 days, after which it is automatically deleted.\n- scope: Invoices\n  period: 8 years\n  text: 'Invoices: 8 years (GST Act).'\n- scope: Audit logs\n  period: 7 years\n  text: 'Audit logs: access logs, security events, admin actions. 7 years.'\n- scope: Removed or flagged content\n  period: 180 days\n  text: 'Removed or flagged content: 180 days after removal (IT (Intermediary Guidelines) Rules, 2021).'\n- scope: Google Analytics data\n  period: 14 months\n  text: Google Analytics keeps this data for up to 14 months\n- scope: Google Ads remarketing lists\n  period: 180 days\n  text: our Google Ads remarketing lists keep a visitor for up to 180 days after their last visit.\nresidency:\n- region: India (AWS Mumbai)\n  text: Operational data is stored in AWS Mumbai (ap-south-1); some sub-processors process data abroad under contractual\n    safeguards.\n- region: United\
  \ States\n  text: Text AI inference (the Anthropic API, US, and Amazon Bedrock, us-east-1)\ntransfers:\n- mechanism: SCC\n  text: Such transfers are made under contractual safeguards (Standard Contractual Clauses or equivalent)\nsubprocessors:\n  url: null\n  text: 'Sub-processors: see the next section.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings → Delete account, or request deletion without signing in at /delete-account\n  text: 'To delete your account and personal data: if you are signed in, use Settings → Delete account for instant\n    removal; otherwise request deletion without signing in at /delete-account.'\nrights:\n- right: Access and summary\n  text: ask for a summary of the personal data we hold about you and how it has been processed\n- right: Correction\n  text: ask us to correct or update inaccurate data\n- right: Erasure\n  text: ask us to erase data we no longer need, subject to retention required by law\n- right: Nominate a representative\n\
  \  text: nominate a person to exercise these rights on your behalf if you die or become incapacitated\n- right: Withdraw consent\n  text: withdraw consent\n- right: Grievance\n  text: file a grievance\n- right: Portability and objection\n  text: Where the GDPR applies, you also have data portability and the right to object to processing based on legitimate\n    interests.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal data or share it with data brokers.\n"
source_yaml_url: https://artifacts.apis.io/avnester-com/privacy/avnester-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 35 quoted statements, read from AVnester's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Artificial Intelligence
- Property Listings
- India
- Marketplace
---
